# MJ विकास V5 — Web + Secure Backend Foundation

Upgraded from V4 with:
- Secure-backend API contract (OpenAPI)
- Device pairing architecture
- Server-side AI proxy architecture (secrets stay server-side)
- Web Dark-Neon dashboard
- Voice/chat dashboard placeholder
- Authorized remote command UI
- Android remote-command allowlist
- V5 version metadata

Important:
This package contains the integration foundation, not a deployed production server.
A real deployment still needs HTTPS, authentication provider, database, device tokens,
WebSocket/push transport, rate limits, CSRF/origin protections where applicable,
and production Android networking code.

Remote commands remain permission-checked on the Android device.
