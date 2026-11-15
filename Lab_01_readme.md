<h1 align="center">
<span style = "color:#00008B;" >Rajshahi University of Engineering and Technology
</span>
</h1>
<h2 align="center">
<span style = "color:#01416A;" >
Hotel Booking & Guest Services Management System
</span>
</h2>


## _Project Purpose_

The purpose of this project is to help hotel staff manage a guest’s visit from the first room enquiry to the final bill. Using a MySQL database, the system connects room reservations, guest records, payments and services to the same booking. A receptionist can check whether a room is free for the requested dates, see how much the guest has paid and explain any remaining balance. Housekeeping staff can track cleaning tasks, while managers can review occupancy and payments across the hotel.

## _Project Requirements_

### 1. Room Availability and Booking

Staff can search for rooms by check-in date, check-out date, room type and preferred side of the hotel. A room must be available for the entire requested stay. A guest can reserve more than one room under a single booking and the system records the agreed nightly rate for each room.

### 2. Guest Records, Occupancy, and Stay

The person making a booking may reserve rooms for family members or other guests. The system therefore records who made the reservation and who will occupy each room. It also keeps the planned dates separate from the actual arrival and departure times. Standard check-in is at 1:00 PM and standard check-out is at noon.

### 3. Meal Packages and Guest Services

Each booked room can have a meal package that specifies whether breakfast, lunch or dinner is included. Services used during the stay, such as spa, swimming or tennis are recorded separately. Each service entry includes the quantity and unit price so staff can explain how the charge was calculated.

### 4. Payments, Cancellation, and Refunds

A booking requires an advance of at least 50% of the room charge before it can be confirmed. The system records each payment and calculates the remaining balance from room charges, additional services and payments received. If a booking is cancelled, the cancellation record is retained. A charge of 25% of the room charge is deducted from the amount paid to determine any refund due.

### 5. Housekeeping and Staff Access

The manager assigns room cleaning tasks, and housekeeping staff update each task as work begins or is completed. Access depends on the staff member’s role. For example, a housekeeper can view the cleaning queue without gaining access to confidential guest records.

### 6. Reports and Dashboard

The dashboard brings together booking status, room occupancy, payments received and outstanding balances. These reports help staff answer practical questions: Which guests are currently staying at the hotel? Which rooms need cleaning? Which bookings still have an unpaid balance?

## _Project Elements_

| Element | Purpose |
|---|---|
| Room availability | Finds available rooms by date, room type and side. |
| Guest and occupant records | Identifies who made the booking and who will stay in each room. |
| Room booking | Reserves one or more rooms and records the agreed nightly rate. |
| Check-in and check-out | Records actual arrival and departure times. Standard check-in is 1:00 PM and check-out is 12:00 noon. |
| Meal packages | Records the selected package and whether it includes breakfast, lunch or dinner. |
| Payments and billing | Records payments and the balance due. A minimum 50% advance on the room charge is required to confirm a booking. |
| Cancellation and refund | Records cancellations, applies a 25% charge on the room charge, and tracks any refund due. |
| Guest services | Tracks the use and cost of services such as spa, swimming and tennis. |
| Staff and access control | Restricts access to records according to each staff members role. |
| Housekeeping | Tracks room cleaning tasks, assigned staff and completion status. |
| Reports and dashboard | Summarizes bookings, occupancy, payments and outstanding balances. |

