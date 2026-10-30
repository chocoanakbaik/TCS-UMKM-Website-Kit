# TCS Public Publisher Certificate

Public self-signed code-signing certificate for The Choco Studios.

- Subject / Issuer: `CN=The Choco Studios`
- Validity: 2026-10-30 through 2046-10-30
- SHA-1 thumbprint: `7C28085E23B23E163D66C6F3E0BB948F61D5ECFD`
- Public certificate: `TCS-Publisher.cer`

## Security
- This `.cer` contains public certificate material only.
- The matching `.pfx` and password are private. Never commit or distribute them.
- This is self-signed, not issued by a public Certificate Authority. It does not establish Microsoft Verified Publisher status or make SmartScreen trust the application.
- Do not tell customers to add it to Trusted Root merely to suppress warnings. Customers should verify the fingerprint and understand the trust implications.
- Adding this file does not sign a binary. A valid Authenticode signature must be applied separately.
