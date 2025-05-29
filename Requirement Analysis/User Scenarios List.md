
| Nr    | Name                                            | Description                                                                                                                              |
| ----- | ----------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| US_01 | User logs in                                    | Users: Admin, Owner, and Manager enter their credentials (email and password) to access their personalized dashboard.                    |
| US_02 | Create a reservation for a new client           | Manager creates a reservation for a new client who visits the branch, entering their details and selecting an available car.             |
| US_03 | Create a reservation for an existing client     | Manager creates a reservation for an existing client already registered in the branch’s database.                                        |
| US_04 | View reservations                               | Users: Owner and Manager view a list of pending reservations for their branch.                                                           |
| US_05 | View calendar                                   | Users: Owner and Manager view each car on a calendar reservation for their branch.                                                       |
| US_06 | Clients’ list                                   | Users: Owner and Manager view all clients registered at their branch.                                                                    |
| US_07 | Filter car in Calendar by date and availability | Users: Owner and Manager filter the cars by date and availability for easily finding cars available on those dates.                      |
| US_08 | Managers list                                   | Owner views all Managers assigned to their branch.                                                                                       |
| US_09 | Search a client                                 | Users: Owner and Manager search for a specific client by name, email, or phone number.                                                   |
| US_10 | Search a manager                                | Owner searches for a specific Manager by name or email within their branch.                                                              |
| US_11 | View own profile                                | Users: Owner and Manager view their profile details (e.g., full name, role, branch).                                                     |
| US_12 | Add a new Manager or Owner                      | Owner adds a new Manager to their branch, assigning a username, email, and password.                                                     |
| US_13 | Edit a reservation                              | Owner or Manager edit a reservation for a specific client, updating the start/end dates in the pending list.                             |
| US_14 | Remove a reservation                            | Owner can remove a reservation from the list.                                                                                            |
| US_15 | View client’s rental history                    | Owner views a specific client’s rental history. Admin can view aggregated rental data across branches.                                   |
| US_16 | Download rental receipt                         | Owner or Manager downloads a PDF receipt of a client’s rental details for record-keeping or client use.                                  |
| US_17 | View reports                                    | Owner views branch-specific reports (e.g., rental stats, revenue). Admin views platform-wide reports.                                    |
| US_18 | User logs out                                   | Users: Admin, Owner, and Manager log out from their accounts.                                                                            |
| US_19 | Add new car                                     | Owner or Manager adds a new car to the branch’s inventory, provided it’s within the subscription limit.                                  |
| US_20 | View car inventory                              | Users: Owner and Manager view the full list of cars in the branch, including statuses (e.g., available, rented).                         |
| US_21 | Add new branch                                  | Admin adds a new branch to the platform, assigning an Owner and setting the time and subscription.                                       |
| US_22 | View activity logs                              | Owner views a log of all actions within their branch (e.g., car added, reservation updated).                                             |
| US_23 | View Manager activity report                    | Owner views a report detailing reservations and actions performed by Managers in their branch.                                           |
| US_24 | Mark a reservation as returned                  | Owner or Manager marks a reservation as returned when the client brings back the car, updating its status to available.                  |
| US_25 | Adding days to a reservation                    | Owner or Manager extends the reservation by adding how many days the client keeps or wants to keep the car longer.                       |
| US_26 | View main page before logging in                | Users access the main page before logging in to read general information about the car rental platform.                                  |
| US_27 | View Overview (Dashboard Home)                  | Users: Owner and Manager view a dashboard with key metrics upon logging in. Admin sees platform-wide overview.                           |
| US_28 | View Upcoming Returns                           | Users: Owner and Manager view a list of cars scheduled to be returned today or tomorrow for their branch.                                |
| US_29 | Search car with license plate                   | Users: Owner and Manager search for a specific car by its license plate number to view its status and rental history.                    |
| US_30 | Filter reservations                             | Users: Owner and Manager filter reservations by car, client, or status (e.g., show only pending reservations for a specific car).        |
| US_31 | Attach return notes & additional fees           | Owner or Manager attaches notes (e.g., “minor scratch on door”) and additional fees (e.g., $20 late fee) when marking a car as returned. |
| US_32 | Generate final invoice after return             | Owner or Manager generates a final invoice (e.g., PDF) including rental cost, additional fees, and notes after a car is returned.        |
| US_33 | Add services and maintenance for cars           | Owner adds car service/maintenance (e.g., oil change, cost, date) and updates car status (e.g., in service).                             |
| US_34 | View car services and maintenance history       | Users: Owner and Manager view a car’s service history (e.g., type, date, cost, status) in a table.                                       |
| US_35 | Check payment page                              | Admin expands to show all payments, with method details.                                                                                 |
| US_36 | Generate invoice from payment page              | Allows Owners to create an invoice from the payment page, consolidating client payments (online/cash) and rental details.                |

---

### 3.1.1.2 User Scenarios Extended

#### US_01 – User logs in
a. User (Admin, Owner, or Manager) enters their email and password based on their role.  
b. User presses the “Login” button.  
c. If the credentials are correct, the user is redirected to their personalized dashboard.  
d. If the credentials are incorrect, an error message (e.g., “Invalid email or password”) is shown, and the user repeats the process from step a.

#### US_02 – Create a reservation for a new client
a. User logs in as Manager by following the steps in US_01.  
b. Manager presses the “New Client Reservation” button on the dashboard.  
c. Manager enters the client’s first and last name.  
d. Manager enters the client’s email address.  
e. Manager enters the client’s phone number.  
f. Manager enters the rental start date and end date.  
g. Manager selects an available car from a dropdown.  
h. Manager enters the rental cost.  
i. Manager presses the “Save” button.  
j. If the data is valid, the reservation is created, a notification pops that says “Car is booked successfully” and the car’s status is updated to “rented.”  
k. If the data is invalid, the reservation is not created, a notification pops that says “ERROR! Check the date or other information”.

#### US_03 – Create a reservation for an existing client
a. User logs in as Manager by following the steps in US_01.  
b. Manager presses the “Existing Client Reservation” button on the dashboard.  
c. Manager searches for the client by name and selects them.  
d. Manager selects an available car from a dropdown.  
e. Manager enters the rental start date and end date.  
f. Manager enters the rental cost.  
g. Manager presses the “Save” button.  
h. If the data is valid, the reservation is created, a notification pops that says “Car is booked successfully” and the car’s status is updated to “rented.”  
i. If the data is invalid, the reservation is not created, a notification pops that says “ERROR! Check the date or other information”.

#### US_04 – View Reservations
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Reservations” on the dashboard.  
c. A table of pending reservations for the branch is shown for each day.  
d. The table columns include client name, car name, start date, end date, cost, status, and actions (e.g., postpone, cancel).

#### US_05 – View Calendar
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Calendar” on the dashboard.  
c. Calendar page header has all dates of the month, and the first column has all the cars.  
d. The colored rows show the dates reserved. Each square is colored according to the car and the date reserved.  
e. User can click a reservation to view details (e.g., client, car, dates).

#### US_06 – Filter car in Calendar by date and availability
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Calendar” on the dashboard.  
c. User enters the filter dates and presses the “Search” button.  
d. The calendar shows only available cars for those dates.

#### US_07 – Clients’ list
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Clients” on the dashboard.  
c. A table of all clients registered at the branch is shown.  
d. The table columns include first name, last name, email, phone number, and registration date.

#### US_08 – Managers list
a. User logs in as Owner by following the steps in US_01.  
b. Owner goes to the “Managers” section on the dashboard or Managers’ page.  
c. A table of all Managers assigned to the branch is shown.  
d. The table columns include first name, last name, email, phone number, and role.

#### US_09 – Search a client
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Search Clients” or enters a query in a search bar on the clients’ page.  
c. User types the client’s name, email, or phone number.  
d. A filtered list of matching clients is shown with details (e.g., name, email, rental history).

#### US_10 – Search a Manager
a. User logs in as Owner by following the steps in US_01.  
b. Owner presses “Search Managers” or enters a query in a search bar on the Managers’ page.  
c. Owner types the Manager’s name or email.  
d. A filtered list of matching Managers is shown with details (e.g., name, email).

#### US_11 – View own profile
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Profile” or their name/avatar on the navigation.  
c. The system displays the user’s details, including full name, role, email, and branch.

#### US_12 – Add a new Manager or Owner
a. User logs in as Owner by following the steps in US_01.  
b. Owner presses “Add Manager” on the Managers’ page.  
c. Owner enters the Manager’s first name, last name, email, phone number, and password.  
d. Owner assigns the Manager or Owner role.  
e. Owner presses the “Save” button.  
f. If the data is valid, the Manager or Owner is added, and a notification pops confirming the addition.

#### US_13 – Edit a reservation
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User navigates to the “Reservations” page as in US_04.  
c. User selects a reservation and presses the “Edit” action button.  
d. User enters new edited information.  
e. User presses “Confirm” to update the reservation.

#### US_14 – Remove a reservation
a. User logs in as Owner by following the steps in US_01.  
b. User navigates to the “Reservations” page as in US_04.  
c. User selects a reservation and presses the “Remove” action button.  
d. A confirmation modal is shown.  
e. User presses “Confirm” to remove the reservation or “Cancel” to abort.

#### US_15 – View client’s rental history
a. User logs in as Owner by following the steps in US_01.  
b. Owner navigates to “Clients” as in US_07 and selects a client.  
c. Owner presses “View Rental History” for the client.  
d. A table of the client’s past and active rentals is shown, including car name, dates, cost, and status.

#### US_16 – Download rental receipt
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User navigates to a reservation via US_04.  
c. User presses “Download Receipt” for the reservation.  
d. The system generates and downloads a PDF with rental details (e.g., client name, car, dates, cost).

#### US_17 – View reports
a. User logs in as Owner or Admin by following the steps in US_01.  
b. User presses “Reports” on the dashboard.  
c. User selects a report type (e.g., rental stats for Owner, platform-wide for Admin) and date range.  
d. A report is displayed with relevant metrics (e.g., number of rentals, car utilization).

#### US_18 – User logs out
a. User logs in as Admin, Owner, or Manager by following the steps in US_01.  
b. User presses “Logout” on the dashboard or navigation bar.  
c. The system logs the user out and redirects to the login page.

#### US_19 – Add new car
a. User logs in as Owner by following the steps in US_01.  
b. Owner presses “Add Car” on the cars’ page.  
c. Owner enters car details (e.g., name, license plate, type).  
d. Owner presses “Save.”  
e. If within the subscription limit, the car is added; otherwise, an error prompts to upgrade.

#### US_20 – View car inventory
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Cars” on the dashboard.  
c. A table of all cars in the branch is shown, including name, license plate, status (e.g., available, rented), and type.

#### US_21 – Add new branch
a. User logs in as Admin by following the steps in US_01.  
b. Admin presses “Add Branch” on the branches’ page.  
c. Admin enters branch details (e.g., name, location, Owner email).  
d. Admin sets the number of cars (e.g., 57 cars = $57/month).  
e. Admin presses “Save,” and the branch is created with the Owner.

#### US_22 – View activity logs
a. User logs in as Owner by following the steps in US_01.  
b. Owner presses “Activity Logs” on the dashboard.  
c. A table of actions within the branch is shown.  
d. The table includes user, action, and timestamp.

#### US_23 – View Manager activity report
a. User logs in as Owner by following the steps in US_01.  
b. Owner presses “Manager Reports” on the dashboard.  
c. Owner selects a Manager and/or date range.  
d. A report shows the Manager’s actions with details.

#### US_24 – Mark a reservation as returned
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User navigates to “Returns” page.  
c. User selects a reservation and presses “Mark as Returned.”  
d. User confirms; a modal pops asking if there are late charges, fines, or additional fees.  
e. If user clicks “NO,” the reservation status is updated to “returned,” and the car is set to “available.”

#### US_25 – Adding days to a reservation
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User selects an active reservation.  
c. User enters the number of days to extend.  
d. The system checks if extension is possible.  
e. If conflict exists, an error is shown; else reservation is updated with new dates and cost.

#### US_26 – View main page before logging in
a. User visits the car rental platform’s main page without logging in.  
b. User views general information.  
c. User can click “Login” to proceed to US_01 or continue browsing.

#### US_27 – View Overview (Dashboard Home)
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User is redirected to the dashboard home page.  
c. Dashboard displays key metrics (e.g., total cars, active reservations, upcoming returns).  
d. User can navigate to other sections (e.g., Clients, Cars) from the dashboard.

#### US_28 – View Upcoming Returns
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Upcoming Returns” on the dashboard.  
c. A table shows cars due to be returned today or tomorrow.  
d. The table includes client name, phone number, car name, license plate, and expected return date.

#### US_29 – Search car with license plate
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User presses “Search Cars” or enters a query in a search bar on the cars’ page.  
c. User types the car’s license plate number.  
d. The system displays the car’s details (e.g., name, status, current rental) if found.

#### US_30 – Filter reservations
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User navigates to “Reservations” or “Calendar.”  
c. User selects filter options (e.g., by car, client name, or status like “pending”).  
d. The system updates the reservation list or calendar to show only matching entries.

#### US_31 – Attach return notes & additional fees
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User navigates to “Returns” page.  
c. User selects a reservation and presses “Mark as Returned.”  
d. User confirms; a modal pops asking if there are late charges, fines, or additional fees.  
e. If confirmed, user enters return notes (e.g., “minor scratch on door”) and additional fees (e.g., $20 late fee).  
f. User presses “Confirm,” updating the reservation with notes and fees.

#### US_32 – Generate final invoice after return
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User navigates to a reservation in the Reservation Page.  
c. User presses “Generate Invoice” after marking the reservation as returned.  
d. The system creates a PDF invoice with rental cost, additional fees, notes, and client details.  
e. User downloads the invoice to the client.

#### US_33 – Find client with a previous date and license car
a. User logs in as Owner by following the steps in US_01.  
b. Owner presses “Find Client for Ticket” on the Clients or Cars’ page.  
c. Owner enters the car’s license plate number and the specific date of the ticket.  
d. The system searches rental records and displays the client who rented the car on that date, including name, email, and contact details.  
e. Owner can view the client’s profile to address the ticket.

#### US_34 – Add services and maintenance for cars
a. User logs in as Owner or Manager by following the steps in US_01.  
b. Owner navigates to “Cars” on the dashboard and selects a car from the inventory.  
c. Owner presses “Add Service/Maintenance” for the selected car.  
d. Owner enters service details (e.g., “Oil change,” “Tire replacement”), date of service, and cost (e.g., $50).  
e. Owner selects a status (e.g., “In Service,” “Completed”) and presses “Save.”  
f. The system updates the car’s status (e.g., to “in service”) and logs the maintenance record.

#### US_35 – View car services and maintenance history
a. User logs in as Owner or Manager by following the steps in US_01.  
b. User navigates to “Cars” on the dashboard and selects a car from the inventory.  
c. User presses “View Service History” for the selected car.  
d. A table displays all past and ongoing services/maintenance for the car, including type (e.g., “Oil change”), date, cost, and status.  
e. User can filter the table by date or service type if needed.

#### US_36 – Check payment page
a. User logs in as Admin by following the steps in US_01.  
b. Presses “Payments” on the dashboard.  
c. Views table of all payments (e.g., “Client John: $50 cash,” “Subscription: $57/month online”).  
d. Sees history, method, and car limit, all information needed for every branch.

#### US_37 – Generate invoice from payment page
a. Owner logs in (US_01).  
b. Navigates to the “Payments” page.  
c. Selects a client payment or rental and presses “Generate Invoice.”  
d. PDF is generated with payment method, rental cost, and details.



