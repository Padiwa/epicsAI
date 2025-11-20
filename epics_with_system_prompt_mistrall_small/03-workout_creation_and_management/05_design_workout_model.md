# Design Workout Model

**Description:** As a developer, I need a workout model to store workout data so that users can create and manage their workouts.

**Go-Specific Considerations:** Define a `Workout` struct with fields like `ID`, `UserID`, `Name`, `Description`, `Exercises`, and `CreatedAt`. Use `gorm` for ORM functionality.

**Acceptance Criteria:**
- Workout model is defined with all necessary fields.
- The model includes relationships to the User model.
- The model is integrated with the database using `gorm`.

---

