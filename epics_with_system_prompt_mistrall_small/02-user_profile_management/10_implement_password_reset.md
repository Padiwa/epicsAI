# Implement Password Reset

**Description:**
As a user, I want to reset my password so that I can regain access to my account if I forget my password.

**Go-Specific Considerations:**
- Use bcrypt for password hashing.
- Implement email sending for password reset links.

**Acceptance Criteria:**
- Users can request a password reset.
- Password reset link is sent to the user's email.
- Users can reset their password using the link.
- New password is hashed and saved to the database.

---

