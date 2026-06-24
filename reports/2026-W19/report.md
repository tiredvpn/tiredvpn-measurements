# TiredVPN Availability Report — 2026-W19

**Date:** 2026-05-05  |  **Version:** test

## Summary

| Client ISP → Server | OK | Blocked | Timeout | Best strategy | Best latency |
|---------------------|----|---------|---------|--------------|--------------|
| Rostelecom → Hetzner Amsterdam | 17 | 0 | 2 | confusion_1 | 108ms |
| Rostelecom → Hetzner Nuremberg | 15 | 0 | 4 | confusion_2 | 82ms |

## Strategy Results

| Strategy | → Hetzner Amsterdam | → Hetzner Nuremberg |
|----------|---------------------|---------------------|
| QUIC Salamander | ✅ ok      108ms    | ✅ ok      86ms     |
| REALITY Protocol | ✅ ok      206ms    | ✅ ok      163ms    |
| HTTP Polling (meek-style) | ✅ ok      136ms    | ✅ ok      124ms    |
| HTTP/2 Steganography | ⏱️ timeout —        | ✅ ok      118ms    |
| WebSocket Salamander | ⏱️ timeout —        | ✅ ok      138ms    |
| Traffic Morph (Yandex Video) | ✅ ok      956ms    | ⏱️ timeout —        |
| Traffic Morph (VK Video) | ✅ ok      970ms    | ⏱️ timeout —        |
| Traffic Morph (Baidu Video) | ✅ ok      971ms    | ⏱️ timeout —        |
| Traffic Morph (Aparat Video) | ✅ ok      949ms    | ⏱️ timeout —        |
| Geneva (Russia TSPU) | ✅ ok      177ms    | ✅ ok      120ms    |
| Geneva (China GFW) | ✅ ok      158ms    | ✅ ok      153ms    |
| Geneva (Iran DPI) | ✅ ok      130ms    | ✅ ok      120ms    |
| Anti-Probe Resistance | ✅ ok      925ms    | ✅ ok      873ms    |
| Protocol Confusion (DNS/TLS) | ✅ ok      113ms    | ✅ ok      83ms     |
| Protocol Confusion (HTTP/TLS) | ✅ ok      108ms    | ✅ ok      89ms     |
| Protocol Confusion (SSH/TLS) | ✅ ok      122ms    | ✅ ok      82ms     |
| Protocol Confusion (SMTP/TLS) | ✅ ok      116ms    | ✅ ok      93ms     |
| Protocol Confusion (Multi-Layer) | ✅ ok      115ms    | ✅ ok      88ms     |
| State Table Exhaustion | ✅ ok      2103ms   | ✅ ok      2084ms   |

---
*Generated automatically by weekly-report.sh*
