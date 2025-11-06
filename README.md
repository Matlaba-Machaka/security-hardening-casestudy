# Web Hardening Mini Case Study

Lightweight recon + defense-in-depth hardening sprint on a site I help maintain.

**What I did**
- Nikto & Nmap (default scripts) for quick recon
- testssl.sh for TLS posture check
- Added/verified modern security headers (HSTS, X-Frame-Options, X-Content-Type-Options, CSP report-only)
- Secured session cookies (Secure, HttpOnly, SameSite=Lax)
- Trimmed legacy ciphers and tightened TLS config
- Hid/restricted admin/mail endpoints
- Small but meaningful extras: Referrer-Policy, Permissions-Policy, 2FA/SSH key-only, monthly checks


> All artifacts are sanitized (no domains, IPs, or sensitive details). Work performed with authorization.
