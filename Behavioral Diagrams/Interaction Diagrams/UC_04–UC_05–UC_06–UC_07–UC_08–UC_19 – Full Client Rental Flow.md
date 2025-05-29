```mermaid
sequenceDiagram
    actor Manager
    participant System
    participant CarInventory
    actor Owner

    Manager->>System: registerClient(name, id, phone)
    System->>System: saveClient()

    Manager->>System: createReservation(clientId, dateRange)
    System->>CarInventory: checkAvailability(dateRange)
    CarInventory-->>System: returnAvailableCars()

    alt carAvailable
        System->>System: saveReservation()
        System->>CarInventory: markAsRented(carId)
        System-->>Manager: confirmReservation()
    else noCars
        System->>Owner: notifyNoCarsAvailable()
        System-->>Manager: showNoCarsMessage()
    end
```
