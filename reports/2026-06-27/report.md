# TiredVPN Availability Report — 2026-06-27

**Date:** 2026-06-27  |  **Version:** 1.1.3

## Summary

| Client ISP → Server | OK | Blocked | Best strategy | Best latency |
|---------------------|----|---------|--------------:|-------------|
| Rostelecom → Hetzner Amsterdam | 16 | 3 | confusion_3 | 85ms |
| Rostelecom → Hetzner Nuremberg | 16 | 3 | confusion_3 | 88ms |

## Strategy Results

### → Hetzner Amsterdam

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ❌ — |
| REALITY Protocol | ❌ — |
| HTTP Polling (meek-style) | ❌ — |
| HTTP/2 Steganography | ✅ 135ms |
| WebSocket Salamander | ✅ 124ms |
| Traffic Morph (Yandex Video) | ✅ 125ms |
| Traffic Morph (VK Video) | ✅ 136ms |
| Traffic Morph (Baidu Video) | ✅ 125ms |
| Traffic Morph (Aparat Video) | ✅ 125ms |
| Geneva (Russia TSPU) | ✅ 132ms |
| Geneva (China GFW) | ✅ 188ms |
| Geneva (Iran DPI) | ✅ 141ms |
| Anti-Probe Resistance | ✅ 897ms |
| Protocol Confusion (DNS/TLS) | ✅ 92ms |
| Protocol Confusion (HTTP/TLS) | ✅ 96ms |
| Protocol Confusion (SSH/TLS) | ✅ 96ms |
| Protocol Confusion (SMTP/TLS) | ✅ 85ms |
| Protocol Confusion (Multi-Layer) | ✅ 91ms |
| State Table Exhaustion | ✅ 2085ms |

### → Hetzner Nuremberg

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ❌ — |
| REALITY Protocol | ❌ — |
| HTTP Polling (meek-style) | ❌ — |
| HTTP/2 Steganography | ✅ 115ms |
| WebSocket Salamander | ✅ 136ms |
| Traffic Morph (Yandex Video) | ✅ 140ms |
| Traffic Morph (VK Video) | ✅ 128ms |
| Traffic Morph (Baidu Video) | ✅ 127ms |
| Traffic Morph (Aparat Video) | ✅ 133ms |
| Geneva (Russia TSPU) | ✅ 160ms |
| Geneva (China GFW) | ✅ 125ms |
| Geneva (Iran DPI) | ✅ 127ms |
| Anti-Probe Resistance | ✅ 883ms |
| Protocol Confusion (DNS/TLS) | ✅ 104ms |
| Protocol Confusion (HTTP/TLS) | ✅ 91ms |
| Protocol Confusion (SSH/TLS) | ✅ 92ms |
| Protocol Confusion (SMTP/TLS) | ✅ 88ms |
| Protocol Confusion (Multi-Layer) | ✅ 89ms |
| State Table Exhaustion | ✅ 2094ms |

---
*Generated automatically.*
