# TiredVPN Availability Report — 2026-06-24

**Date:** 2026-06-24  |  **Version:** 1.1.3

## Summary

| Client ISP → Server | OK | Blocked | Best strategy | Best latency |
|---------------------|----|---------|--------------:|-------------|
| Rostelecom → Hetzner Amsterdam | 16 | 3 | confusion_3 | 115ms |
| Rostelecom → Hetzner Nuremberg | 15 | 4 | confusion_3 | 81ms |

## Strategy Results

### → Hetzner Amsterdam

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ❌ — |
| REALITY Protocol | ❌ — |
| HTTP Polling (meek-style) | ❌ — |
| HTTP/2 Steganography | ✅ 190ms |
| WebSocket Salamander | ✅ 188ms |
| Traffic Morph (Yandex Video) | ✅ 154ms |
| Traffic Morph (VK Video) | ✅ 142ms |
| Traffic Morph (Baidu Video) | ✅ 155ms |
| Traffic Morph (Aparat Video) | ✅ 134ms |
| Geneva (Russia TSPU) | ✅ 206ms |
| Geneva (China GFW) | ✅ 209ms |
| Geneva (Iran DPI) | ✅ 189ms |
| Anti-Probe Resistance | ✅ 923ms |
| Protocol Confusion (DNS/TLS) | ✅ 141ms |
| Protocol Confusion (HTTP/TLS) | ✅ 138ms |
| Protocol Confusion (SSH/TLS) | ✅ 128ms |
| Protocol Confusion (SMTP/TLS) | ✅ 115ms |
| Protocol Confusion (Multi-Layer) | ✅ 121ms |
| State Table Exhaustion | ✅ 2127ms |

### → Hetzner Nuremberg

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ❌ — |
| REALITY Protocol | ❌ — |
| HTTP Polling (meek-style) | ❌ — |
| HTTP/2 Steganography | ✅ 134ms |
| WebSocket Salamander | ✅ 141ms |
| Traffic Morph (Yandex Video) | ✅ 136ms |
| Traffic Morph (VK Video) | ✅ 129ms |
| Traffic Morph (Baidu Video) | ✅ 127ms |
| Traffic Morph (Aparat Video) | ✅ 140ms |
| Geneva (Russia TSPU) | ✅ 170ms |
| Geneva (China GFW) | ✅ 116ms |
| Geneva (Iran DPI) | ✅ 134ms |
| Anti-Probe Resistance | ❌ — |
| Protocol Confusion (DNS/TLS) | ✅ 97ms |
| Protocol Confusion (HTTP/TLS) | ✅ 87ms |
| Protocol Confusion (SSH/TLS) | ✅ 86ms |
| Protocol Confusion (SMTP/TLS) | ✅ 81ms |
| Protocol Confusion (Multi-Layer) | ✅ 90ms |
| State Table Exhaustion | ✅ 2092ms |

---
*Generated automatically.*
