# Password Reset in Active Directory

## Scenario
User is unable to log in because they forgot their password or the account is locked.

## Prerequisites
- Access to Active Directory Users and Computers
- User identity verified as per company policy

## Steps
1. Open Active Directory Users and Computers
2. Search for the affected user account
3. Right-click the user and select "Reset Password"
4. Set a temporary password
5. Enable "User must change password at next logon"
6. Unlock the account if it is locked

## Validation
- Confirm with the user that login is successful
- Ensure the account status shows as active

## Common Mistakes
- Resetting the wrong user account
- Forgetting to unlock the account
- Not enforcing password change at next login
