# TiredVPN Availability Report — 2026-07-06

**Date:** 2026-07-06  |  **Version:** 1.3.19

## Summary

| Client ISP → Server | OK | Blocked | Best strategy | Best latency |
|---------------------|----|---------|--------------:|-------------|
| Rostelecom → Hetzner Amsterdam | 20 | 1 | confusion_1 | 41ms |
| Rostelecom → Hetzner Nuremberg | 16 | 5 | confusion_0 | 43ms |

## Strategy Results

### → Hetzner Amsterdam

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ✅ 105ms |
| REALITY Protocol | ✅ 124ms |
| HTTP Polling (meek-style) | ✅ 130ms |
| HTTP/2 Steganography | ❌ — |
| WebSocket Salamander | ✅ 148ms |
| Traffic Morph (Yandex Video) | ✅ 179ms |
| Traffic Morph (VK Video) | ✅ 165ms |
| Traffic Morph (Baidu Video) | ✅ 175ms |
| Traffic Morph (Aparat Video) | ✅ 187ms |
| Geneva (Russia TSPU) | ✅ 126ms |
| Geneva (China GFW) | ✅ 170ms |
| Geneva (Iran DPI) | ✅ 143ms |
| Anti-Probe Resistance | ✅ 894ms |
| Protocol Confusion (DNS) | ✅ 42ms |
| Protocol Confusion (HTTP) | ✅ 41ms |
| Protocol Confusion (SSH) | ✅ 47ms |
| Protocol Confusion (SMTP) | ✅ 47ms |
| Protocol Confusion (Multi-Layer) | ✅ 42ms |
| SSH Camouflage | ✅ 164ms |
| IMAP Camouflage | ✅ 166ms |
| State Table Exhaustion | ✅ 2088ms |

### → Hetzner Nuremberg

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ✅ 94ms |
| REALITY Protocol | ❌ — |
| HTTP Polling (meek-style) | ✅ 134ms |
| HTTP/2 Steganography | ❌ — |
| WebSocket Salamander | ✅ 124ms |
| Traffic Morph (Yandex Video) | ✅ 165ms |
| Traffic Morph (VK Video) | ✅ 174ms |
| Traffic Morph (Baidu Video) | ✅ 166ms |
| Traffic Morph (Aparat Video) | ✅ 180ms |
| Geneva (Russia TSPU) | ❌ — |
| Geneva (China GFW) | ❌ — |
| Geneva (Iran DPI) | ❌ — |
| Anti-Probe Resistance | ✅ 907ms |
| Protocol Confusion (DNS) | ✅ 43ms |
| Protocol Confusion (HTTP) | ✅ 49ms |
| Protocol Confusion (SSH) | ✅ 45ms |
| Protocol Confusion (SMTP) | ✅ 44ms |
| Protocol Confusion (Multi-Layer) | ✅ 45ms |
| SSH Camouflage | ✅ 169ms |
| IMAP Camouflage | ✅ 182ms |
| State Table Exhaustion | ✅ 2098ms |

---
*Generated automatically.*
