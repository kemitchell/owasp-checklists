# Authentication

<https://owasp.org/www-project-cheat-sheets/cheatsheets/Authentication_Cheat_Sheet.html>

## User IDs
- [ ]  case-insensitive user IDs
- [ ]  unique user IDs

## Reuse
- [ ]  don't allow login with administrative accounts
- [ ]  don't reuse internal authentication systems

## Passwords
- [ ]  >= 8 characters
- [ ]  maximum length
  - 128 characters
  - if the hash function truncates, set max at truncation point (e.g. 64 characters for bcrypt)
- [ ]  allow Unicode and whitespace characters
- [ ]  password strength meter
- [ ]  Use a secure password verification function.

## General
- [ ]  Use TLS.
- [ ]  Require reauthentication for sensitive operations.
- [ ]  Use generic error messages.
  - incorrect ID
  - incorrect password
  - account doesn't exist
  - account locked or disabled
  - e-mailed reset
  - account signup
- [ ]  Use multi-factor authentication
- [ ]  Lock out accounts for repeated authentication failures.

## Logging
- [ ]  Log all failures.
- [ ]  Log all lockouts.
