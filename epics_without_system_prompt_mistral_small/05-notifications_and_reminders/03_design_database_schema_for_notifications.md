# Design Database Schema for Notifications
Define the database schema for storing notifications and reminders.
- **Go Advice**: Use GORM for ORM. Design tables for `notifications` (id, user_id, type, content, status, created_at) and `reminders` (id, user_id, notification_id, scheduled_time, sent_at).

---

