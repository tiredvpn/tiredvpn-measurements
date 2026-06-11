# tiredvpn-measurements

Daily availability measurements of censorship-circumvention transports against TSPU
(the DPI system deployed by Russian ISPs), collected since 2026-05-05.

Each day, an automated stand inside Russia attempts a full tunnel handshake with 19
different transport strategies (QUIC obfuscation, REALITY, protocol confusion, traffic
morphing, Geneva-derived and others) and records which ones connect, which get blocked,
and at what latency. The full strategy list with handshake descriptions will live in
`METHODOLOGY.md`.

## Vantage points

| ISP | Access type | Notes |
|---|---|---|
| Rostelecom | wired broadband | |
| MegaFon | LTE (USB tethering) | blocks non-standard ports, so measured on 443 |

Destination servers: Hetzner Amsterdam and Hetzner Nuremberg. More ISPs (MTS, Beeline,
Tele2, one regional) are planned - see the roadmap in the main repo.

Vantage points are residential and mobile connections. Published data identifies them
by ISP and nothing else.

## Layout

```
reports/
  2026-05-05/
    report.md     # human-readable daily table: strategy x ISP x server
  ...
```

Machine-readable JSON (per-attempt records with latency and error type) is produced by
the stand for every run and is being added to this archive next, including backfill.

## Known gaps

- 2026-05-07 and 2026-05-10: stand did not run, no data exists for these dates.
- Reports for 2026-05-05 .. 2026-06-10 were recovered from git history of the main
  repository after an automated cleanup job had been deleting anything older than
  14 days. The job is disabled; this repository keeps everything.

## Reading the data

A ✅ means the strategy completed a handshake and passed a traffic check; the number is
round-trip latency of the tunnel. A ❌ means the attempt failed - the current markdown
format does not yet distinguish an RST injected by DPI from a silent drop or a timeout.
That classification (with pcaps for each blocking event) is the next methodology step.

One example of why daily granularity matters: REALITY connected to Nuremberg fine
until 2026-05-12, failed on 2026-05-13 on both ISPs at once, and has not recovered
since - while the same strategy to Amsterdam kept working the whole time. Per-route
blocking like this is invisible in any single-day snapshot.

## License

Data is published under [CC-BY 4.0](LICENSE). Use it, cite
`tiredvpn-measurements, https://github.com/tiredvpn/tiredvpn-measurements`.

Main project: [tiredvpn/tiredvpn](https://github.com/tiredvpn/tiredvpn).
