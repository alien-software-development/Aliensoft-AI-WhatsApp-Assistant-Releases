# Security Policy

## Reporting a Vulnerability
If you discover a security issue in **Aliensoft AI WhatsApp Assistant**, please contact **Alien Software Development** directly rather than posting sensitive exploit details publicly:
- Email: `aliensoftwaredevelopment@gmail.com`
- WhatsApp Direct: `+880 1710-978997`

## Built-In Security Architecture
1. **Zero Public Secrets:** `.gitignore` strictly excludes local `.db` files, `.log` files, QR `.auth` sessions, private license keys (`.local-secrets/`, `*.private.pem`), and installers.
2. **Windows DPAPI Encryption:** API keys (DeepSeek, OpenAI, Gemini), Meta Cloud tokens, Cloudflare tunnel tokens, QR webhook secrets, Google Sheets credentials, and trial ledgers are encrypted via `ProtectedData.Protect(..., DataProtectionScope.CurrentUser)`.
3. **Database Hardening:** Local storage runs with WAL crash-recovery journaling, strict foreign-key enforcement, immediate secure deletion (`secure_delete`), and owner-only Windows NTFS access control lists (`DatabaseFileSecurity`).
4. **Asymmetric Licensing:** Client builds embed only the ECDSA P-256 SPKI public key (`LicenseTokenCodec`). Private signing keys remain strictly offline inside the operator's admin generator environment.
5. **Loopback Isolation:** Embedded Minimal API binds exclusively to `127.0.0.1` (`5085`) and rejects tunneled management calls and missing bearer tokens.
