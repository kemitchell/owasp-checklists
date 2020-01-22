# Session Management

## Session IDs
- [ ]  Don't give overly descriptive names.  Use something like `id`.
- [ ]  >= 128 bits
- [ ]  >= 64 bits of entropy
- [ ]  Make sure the value is meaningless.
- [ ]  Use cryptographic hash functions.

## Implementation
- [ ]  Prefer implementations like cookies that allow setting security parameters.
- [ ]  In general, prefer built-in session management features of languages and frameworks.
- [ ]  Use cookies.
- [ ]  Don't accept via other channels.
- [ ]  Use TLS.
- [ ]  Use the `Secure` cookie attribute.
- [ ]  Don't switch sessions from HTTPS to HTTP.
- [ ]  Regenerate cookies after switching to HTTPS.
- [ ]  Don't mix encrypted and unencrypted elements.
- [ ]  Use HTTP Strict Transport Security.

## Cookies
- [ ]  `Secure`
- [ ]  `HttpOnly`
- [ ]  `SameSite`
- [ ]  `Domain`
- [ ]  `Path`
- [ ]  Prefer non-persistent cookies.
