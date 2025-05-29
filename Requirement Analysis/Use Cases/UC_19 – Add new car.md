```mermaid
flowchart TD
    Owner((Owner))
    UC19([Add New Car])
    UC20([Upgrade Subscription])

    Owner --> UC19
    UC19 -.->|"«extend»"| UC20
```
