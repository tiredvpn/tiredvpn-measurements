# TiredVPN Availability Report — 2026-06-25

**Date:** 2026-06-25  |  **Version:** 1.1.3

## Summary

| Client ISP → Server | OK | Blocked | Best strategy | Best latency |
|---------------------|----|---------|--------------:|-------------|
| Rostelecom → Hetzner Amsterdam | 16 | 3 | confusion_4 | 84ms |
| Rostelecom → Hetzner Nuremberg | 16 | 3 | confusion_2 | 83ms |

## Strategy Results

### → Hetzner Amsterdam

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ❌ — |
| REALITY Protocol | ❌ — |
| HTTP Polling (meek-style) | ❌ — |
| HTTP/2 Steganography | ✅ 138ms |
| WebSocket Salamander | ✅ 124ms |
| Traffic Morph (Yandex Video) | ✅ 129ms |
| Traffic Morph (VK Video) | ✅ 125ms |
| Traffic Morph (Baidu Video) | ✅ 130ms |
| Traffic Morph (Aparat Video) | ✅ 135ms |
| Geneva (Russia TSPU) | ✅ 175ms |
| Geneva (China GFW) | ✅ 124ms |
| Geneva (Iran DPI) | ✅ 129ms |
| Anti-Probe Resistance | ✅ 881ms |
| Protocol Confusion (DNS/TLS) | ✅ 85ms |
| Protocol Confusion (HTTP/TLS) | ✅ 89ms |
| Protocol Confusion (SSH/TLS) | ✅ 86ms |
| Protocol Confusion (SMTP/TLS) | ✅ 87ms |
| Protocol Confusion (Multi-Layer) | ✅ 84ms |
| State Table Exhaustion | ✅ 2085ms |

### → Hetzner Nuremberg

| Strategy | Rostelecom |
|----------|------------|
| QUIC Salamander | ❌ — |
| REALITY Protocol | ❌ — |
| HTTP Polling (meek-style) | ❌ — |
| HTTP/2 Steganography | ✅ 124ms |
| WebSocket Salamander | ✅ 124ms |
| Traffic Morph (Yandex Video) | ✅ 139ms |
| Traffic Morph (VK Video) | ✅ 129ms |
| Traffic Morph (Baidu Video) | ✅ 139ms |
| Traffic Morph (Aparat Video) | ✅ 136ms |
| Geneva (Russia TSPU) | ✅ 175ms |
| Geneva (China GFW) | ✅ 163ms |
| Geneva (Iran DPI) | ✅ 123ms |
| Anti-Probe Resistance | ✅ 875ms |
| Protocol Confusion (DNS/TLS) | ✅ 84ms |
| Protocol Confusion (HTTP/TLS) | ✅ 95ms |
| Protocol Confusion (SSH/TLS) | ✅ 83ms |
| Protocol Confusion (SMTP/TLS) | ✅ 91ms |
| Protocol Confusion (Multi-Layer) | ✅ 86ms |
| State Table Exhaustion | ✅ 2086ms |

---
*Generated automatically.*
