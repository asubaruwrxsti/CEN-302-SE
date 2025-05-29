
| User Goal                              | Context                               | Actions                                   | Outcome                                             |
| -------------------------------------- | ------------------------------------- | ----------------------------------------- | --------------------------------------------------- |
| Log in                                 | User visits login page                | Enter email and password                  | Access granted to personalized dashboard            |
| Log in                                 | Credentials invalid                   | Submit login form                         | Error message shown, user asked to retry            |
| Create new client reservation          | Manager logged in, new client arrives | Enter client details and select car       | Reservation created, car status updated to "rented" |
| Create existing client reservation     | Manager logged in, client registered  | Select client and car, enter rental dates | Reservation created, car status updated to "rented" |
| View reservations                      | Owner or Manager logged in            | Navigate to reservations page             | List of pending reservations displayed              |
| View calendar                          | Owner or Manager logged in            | Navigate to calendar page                 | Calendar shows reservations by date and car         |
| Filter calendar by date & availability | Owner or Manager logged in            | Apply date and availability filters       | Filtered cars displayed in calendar                 |
| View clients list                      | Owner or Manager logged in            | Navigate to clients page                  | List of registered clients displayed                |
| View managers list                     | Owner logged in                       | Navigate to managers page                 | List of branch managers displayed                   |
| Search client                          | Owner or Manager logged in            | Search client by name/email/phone         | Matching clients displayed                          |
| Search manager                         | Owner logged in                       | Search manager by name/email              | Matching managers displayed                         |
| View own profile                       | Owner or Manager logged in            | Navigate to profile page                  | User profile details shown                          |
| Add new Manager or Owner               | Owner logged in                       | Enter new user details and assign role    | New user added and notified                         |
| Edit a reservation                     | Owner or Manager logged in            | Select reservation and edit details       | Reservation updated                                 |
| Remove a reservation                   | Owner logged in                       | Select reservation and confirm removal    | Reservation removed, car marked available           |
| View client rental history             | Owner logged in                       | Select client and view rental history     | Client’s past rentals displayed                     |
| Download rental receipt                | Owner or Manager logged in            | Select reservation and download receipt   | Rental receipt PDF generated and downloaded         |
| View reports                           | Owner or Admin logged in              | Select report type and date range         | Reports displayed with metrics                      |
| User logs out                          | User logged in                        | Click logout                              | Session ended, redirected to login                  |
| Add new car                            | Owner or Manager logged in            | Enter car details and save                | Car added to inventory                              |
| View car inventory                     | Owner or Manager logged in            | Navigate to cars page                     | List of cars with statuses displayed                |
| Add new branch                         | Admin logged in                       | Enter branch and owner details, save      | Branch created and owner notified                   |
| View activity logs                     | Owner logged in                       | Navigate to activity logs                 | Branch activity logs displayed                      |
| View Manager activity report           | Owner logged in                       | Select manager and date range             | Manager activity report displayed                   |
| Mark reservation as returned           | Owner or Manager logged in            | Mark reservation as returned              | Reservation status updated, car marked available    |
| Add days to a reservation              | Owner or Manager logged in            | Enter extension days and confirm          | Reservation extended                                |
| View main page before login            | Guest visits site                     | Browse main page                          | General platform info displayed                     |
| View dashboard overview                | Owner, Manager, Admin logged in       | Access dashboard                          | Key metrics displayed                               |
| View upcoming returns                  | Owner or Manager logged in            | Access upcoming returns page              | List of upcoming returns displayed                  |
| Search car by license plate            | Owner or Manager logged in            | Enter license plate and search            | Car details displayed                               |
| Filter reservations                    | Owner or Manager logged in            | Apply filters on reservations list        | Filtered reservations displayed                     |
| Attach return notes & fees             | Owner or Manager logged in            | Add notes and fees on returned car        | Notes and fees saved                                |
| Generate final invoice                 | Owner or Manager logged in            | Generate invoice after return             | PDF invoice generated                               |
| Add services/maintenance               | Owner or Manager logged in            | Enter service details and update status   | Service recorded and status updated                 |
| View service history                   | Owner or Manager logged in            | View car’s service records                | Service history displayed                           |
| Check payment page                     | Admin logged in                       | View payment records                      | Payments data displayed                             |
| Generate invoice from payment          | Owner logged in                       | Generate invoice from payment page        | Invoice PDF created                                 |

---

# User Personas

| Persona Name    | Role           | Goals                                                       | Characteristics                                           | Typical Actions                                              |
| --------------- | -------------- | ----------------------------------------------------------- | --------------------------------------------------------- | ------------------------------------------------------------ |
| **Admin**       | System Admin   | Manage branches, oversee platform-wide reports and payments | Oversees multiple branches, controls subscriptions, users | Add branches, manage Owners, view platform-wide reports      |
| **Owner**       | Branch Owner   | Manage branch resources, users, reports                     | Responsible for branch operations, user & car management  | Add Managers, view reservations, add cars, generate invoices |
| **Manager**     | Branch Manager | Manage client reservations and rentals                      | Frontline operator interacting with clients               | Create reservations, download receipts, update rentals       |
| **Client/User** | End User       | Rent vehicles, view rental info                             | Accesses dashboard for personal rental data               | Log in, view dashboard, request rentals via Manager          |
| **Guest**       | Visitor        | Learn about platform services                               | No login required                                         | View main page, browse info, choose to log in                |

