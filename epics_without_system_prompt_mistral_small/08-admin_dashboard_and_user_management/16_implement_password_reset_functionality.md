# Implement Password Reset Functionality

- Create password reset flow endpoints:
  - `/api/auth/forgot-password` (POST - initiate reset)
  - `/api/auth/reset-password` (POST - complete reset)
- Use secure tokens with expiration
- Send emails using `gomail` or similar package
- Validate token before allowing password change

---

