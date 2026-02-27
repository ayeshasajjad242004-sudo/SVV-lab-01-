# Software Requirements Specification (SRS)

## Reviewed and Improved Requirements

---

### Requirement 1

Original:
The system should be user-friendly.

Problems:
- Not measurable
- Not testable
- Not specific
- Ambiguous

Improved Requirement:
The system shall allow a new user to complete registration within 3 minutes without external assistance.

---

### Requirement 2

Original:
The system shall store student records safely.

Problems:
- Not specific
- Not measurable
- Ambiguous ("safely")

Improved Requirement:
The system shall encrypt all student records using AES-256 encryption before storing them in the database.

---

### Requirement 3

Original:
The system should load quickly.

Problems:
- Not measurable
- Not specific
- Ambiguous

Improved Requirement:
The system shall load the dashboard page within 2 seconds under normal network conditions (minimum 10 Mbps).

---

### Requirement 4

Original:
The system shall allow users to register, login, and manage their profile.

Problems:
- Not atomic (contains multiple actions)

Improved Requirements:

4.1 The system shall allow users to register using email and password.

4.2 The system shall allow registered users to log in using valid credentials.

4.3 The system shall allow users to update their profile information including name and password.

---

###Requirement 5

Original:
The system shall send notifications.

Problems:
- Not specific
- Not complete
- Not measurable

Improved Requirement:
The system shall send email notifications to users within 1 minute after successful registration.