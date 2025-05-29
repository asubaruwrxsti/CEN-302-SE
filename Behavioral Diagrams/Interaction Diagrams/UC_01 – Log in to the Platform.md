```mermaid
sequenceDiagram
    actor User
    participant LoginPage
    participant AuthService

    User->>LoginPage: submitLoginForm(username, password)
    LoginPage->>AuthService: authenticate(username, password)
    AuthService-->>LoginPage: returnToken(sessionToken)
    LoginPage-->>User: redirectToDashboard()
```
