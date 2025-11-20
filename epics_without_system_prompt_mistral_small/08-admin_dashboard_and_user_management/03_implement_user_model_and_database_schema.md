# Implement User Model and Database Schema

- Define a `User` struct with fields like ID, Username, Email, PasswordHash, Role (Admin/Regular), CreatedAt, UpdatedAt
- Use GORM for ORM with PostgreSQL/MySQL backend
- Implement GORM hooks for automatic timestamp management
- Add validation using struct tags (e.g., `json` and `gorm` tags)
- Consider using `ulid` package for generating unique IDs

---

