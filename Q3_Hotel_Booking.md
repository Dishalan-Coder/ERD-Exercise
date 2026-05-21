# Question 3 — Hotel Booking System (Hospitality Industry)

## Scenario

A hotel chain that operates properties across multiple cities wants to build a centralized booking and management database. You have been engaged as a database consultant to design this system from scratch.

The chain operates several **hotels**, each located in a different city. Every hotel has a unique hotel ID, a hotel name, a full street address, the city it is in, a country, a contact phone number, and an official star rating (1 to 5 stars). Each hotel is independently managed but shares the same central database system.

Within each hotel, there are different categories of **room types** offered to guests. For example, a hotel might offer Single Rooms, Double Rooms, Deluxe Rooms, Junior Suites, and Presidential Suites. Each room type has a type ID, a type name, a description of what is included (e.g., sea view, king bed, private jacuzzi), the maximum number of guests allowed, and a base price per night. A hotel can offer many room types, and the same type name can exist across multiple hotels — but the pricing and details may differ per hotel.

Each physical **room** in a hotel belongs to exactly one hotel and is of exactly one room type. A room has a room ID, a room number (e.g., 101, 202), a floor number, and a status indicating whether it is currently Active, Under Maintenance, or Decommissioned. Multiple rooms in the same hotel can share the same room type (e.g., ten rooms are all Double Rooms on floor 2).

**Guests** must register a profile before making any booking. A guest's profile includes a guest ID, full name, email address, phone number, nationality, passport or national ID number, and the date they first registered with the system. A guest can make bookings at any hotel in the chain.

When a guest wants to stay at a hotel, they create a **booking**. A booking has a booking ID, the date the booking was made, the check-in date, the check-out date, the number of guests in the party, the booking status (Confirmed, Checked-In, Checked-Out, Cancelled, No-Show), and the total cost calculated at the time of booking. Each booking is for exactly one room, and each booking belongs to exactly one guest. A room can have many bookings over time (different guests at different dates), and a guest can make many bookings across their lifetime as a customer.

Guests can choose to add **extra services** to their booking to enhance their stay. The hotel chain offers a fixed catalogue of services such as Airport Transfer, Breakfast Package, Honeymoon Decoration, Spa Treatment, and Late Checkout. Each service in the catalogue has a service ID, a service name, a description, and a fixed price. When a guest adds a service to their booking, the date on which that service is to be delivered must also be recorded. A single booking can include many services, and the same service can be added to many different bookings.

After completing their stay, guests may submit a **review** for the hotel they visited. A review has a review ID, an overall rating (1 to 10), separate sub-ratings for Cleanliness, Comfort, Location, and Staff (each out of 10), a written comment, and the date the review was submitted. A guest can submit only one review per completed booking. A hotel can receive many reviews from many guests over time.

---

## Your Task

Draw a complete **Entity-Relationship (ER) Diagram** for the Hotel Booking System described above.

Your diagram must:

1. Identify and clearly label all **entities** in the system.
2. List the **attributes** for each entity — underline or mark the **primary key** attribute.
3. Identify all **relationships** between entities and give each relationship a meaningful name.
4. Specify the correct **cardinality** (1:1, 1:N, or M:N) and **participation constraints** (total or partial) for every relationship.
5. Identify any **weak entities** and their identifying relationships.
6. For every **M:N relationship**, identify and include the **relationship attributes** that belong to the association, not to either individual entity.

---

## Marking Criteria

| Criteria | Marks |
|----------|-------|
| Correct entities identified | 10 |
| Correct attributes with primary keys | 10 |
| Correct relationships & cardinality | 15 |
| Weak entities / relationship attributes | 10 |
| Diagram clarity and notation | 5 |
| **Total** | **50** |
