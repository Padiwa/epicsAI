# Set Up Basic Logging for API Requests

**Description:** As a developer, I want to set up basic logging for API requests so that we can track and debug API usage.

**Go-Specific Considerations:** Use the `log` package or a structured logging library like `github.com/sirupsen/logrus`. Implement middleware for logging API requests and responses.

**Acceptance Criteria:**
- API requests and responses are logged
- Logs include relevant context (e.g., request method, path, status code)
- Logs are formatted consistently
- Logs are stored and accessible for debugging

---

