# Add Commenting System for Workouts

- **Description:** Allow users to comment on shared workouts and reply to comments.
- **Go-Specific Advice:**
  - Model comments with GORM and ensure proper relationships.
  - Use transactions (`gorm.Transactional`) to maintain data consistency.
  - Implement real-time updates with WebSockets (`gorilla/websocket`).

---

