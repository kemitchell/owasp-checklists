# Forgot Password

<https://owasp.org/www-project-cheat-sheets/cheatsheets/Forgot_Password_Cheat_Sheet.html>

## Step 1: Gather identity data or security questions.
- [ ]  Present at least two security questions.
- [ ]  Limit users to three to five guesses.

## Step 2: Verify security questions.
- [ ]  Don't send the user ID as a parameter, hidden or visible.

## Step 3: Send token over side channel.
- [ ]  Lock out the account immediately.

## Step 4: Allow the user to change password in the existing session.
- [ ]  Require reset before any other user action.

## Step 5: Log.
- [ ]  Log security question answers.
- [ ]  Log failed attempts.

## Miscellaneous
- [ ]  On password reset, invalidate all other sessions.
- [ ]  Require stronger questions for administrative accounts.
- [ ]  Rotate questions.
