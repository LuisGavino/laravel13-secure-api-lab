## Authentication vs. Authorization

**Authentication** verifies the identity of a user by checking their login credentials or token. It answers the question, "Who are you?"

**Authorization** determines what an authenticated user is allowed to access or perform based on their role and permissions. It answers the question, "What are you allowed to do?"

## Difference Between 401 and 403 HTTP Status Codes

A student receives **403 Forbidden** when accessing the admin dashboard because the system has successfully authenticated the student but does not allow their role to access administrator-only features.

A request without a valid authentication token receives **401 Unauthorized** because the system cannot verify the user's identity. The user must authenticate before accessing protected resources.