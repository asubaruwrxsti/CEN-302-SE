```mermaid
sequenceDiagram
    actor Admin
    participant System
    participant ReportingService

    Admin->>System: login(email, password)
    System-->>Admin: redirectToDashboard()

    Admin->>System: viewPlatformMetrics()
    System->>ReportingService: generateReport()
    ReportingService-->>System: returnReportData()
    System-->>Admin: displayMetrics()
```
