# TiredVPN Availability Report — 2026-07-02

**Date:** 2026-07-02  |  **Version:** 1.3.17

## Summary

| Client ISP → Server | OK | Blocked | Best strategy | Best latency |
|---------------------|----|---------|--------------:|-------------|
| Rostelecom → Hetzner Amsterdam | 20 | 1 | confusion_1 | 40ms |
| Rostelecom → Hetzner Nuremberg | 16 | 5 | confusion_2 | 42ms |

## Strategy Results

### → Hetzner Amsterdam

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ✅ 101ms |
| REALITY Protocol | ✅ 121ms |
| HTTP Polling (meek-style) | ✅ 144ms |
| HTTP/2 Steganography | ❌ — |
| WebSocket Salamander | ✅ 140ms |
| Traffic Morph (Yandex Video) | ✅ 164ms |
| Traffic Morph (VK Video) | ✅ 175ms |
| Traffic Morph (Baidu Video) | ✅ 166ms |
| Traffic Morph (Aparat Video) | ✅ 182ms |
| Geneva (Russia TSPU) | ✅ 131ms |
| Geneva (China GFW) | ✅ 131ms |
| Geneva (Iran DPI) | ✅ 141ms |
| Anti-Probe Resistance | ✅ 896ms |
| Protocol Confusion (DNS) | ✅ 46ms |
| Protocol Confusion (HTTP) | ✅ 40ms |
| Protocol Confusion (SSH) | ✅ 46ms |
| Protocol Confusion (SMTP) | ✅ 46ms |
| Protocol Confusion (Multi-Layer) | ✅ 42ms |
| SSH Camouflage | ✅ 187ms |
| IMAP Camouflage | ✅ 169ms |
| State Table Exhaustion | ✅ 2096ms |

### → Hetzner Nuremberg

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ✅ 92ms |
| REALITY Protocol | ❌ — |
| HTTP Polling (meek-style) | ✅ 130ms |
| HTTP/2 Steganography | ❌ — |
| WebSocket Salamander | ✅ 132ms |
| Traffic Morph (Yandex Video) | ✅ 168ms |
| Traffic Morph (VK Video) | ✅ 173ms |
| Traffic Morph (Baidu Video) | ✅ 171ms |
| Traffic Morph (Aparat Video) | ✅ 163ms |
| Geneva (Russia TSPU) | ❌ — |
| Geneva (China GFW) | ❌ — |
| Geneva (Iran DPI) | ❌ — |
| Anti-Probe Resistance | ✅ 885ms |
| Protocol Confusion (DNS) | ✅ 45ms |
| Protocol Confusion (HTTP) | ✅ 42ms |
| Protocol Confusion (SSH) | ✅ 42ms |
| Protocol Confusion (SMTP) | ✅ 45ms |
| Protocol Confusion (Multi-Layer) | ✅ 43ms |
| SSH Camouflage | ✅ 169ms |
| IMAP Camouflage | ✅ 178ms |
| State Table Exhaustion | ✅ 2082ms |

---
*Generated automatically.*
