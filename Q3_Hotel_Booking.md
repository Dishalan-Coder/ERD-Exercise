# Question 3 — Hotel Booking System (Hospitality Industry)

## Scenario

A hotel chain with multiple **hotels** across different cities wants to build a central booking database. Each hotel has a name, address, city, and star rating.

Each hotel contains multiple **room types** (e.g., Single, Double, Suite), and each room type has a price per night and a maximum occupancy. A hotel can offer many room types, and the same room type name can exist in multiple hotels (treat each room type per hotel as unique).

Individual **rooms** belong to a specific hotel and are of a specific room type. Each room has a room number and a floor number.

**Guests** register to make bookings. A guest has a name, email, phone number, and nationality. A guest can make many **bookings**, but each booking belongs to one guest.

A booking reserves a specific room for a date range (check-in date and check-out date). One booking is for one room only. Multiple bookings can exist for the same room as long as the dates do not overlap (the system will handle that logic — you only need to model the data).

Each booking can have optional **additional services** added to it (e.g., Airport Pickup, Breakfast Package, Spa Package). A service has a name and a fixed price. A booking can include many services, and the same service can be added to many bookings.

---

## Your Task

Draw a complete **Entity-Relationship (ER) Diagram** for the above system.

### Requirements

1. Identify all **entities** from the scenario.
2. Define the **attributes** for each entity (underline the primary key).
3. Identify all **relationships** between entities.
4. Specify the **cardinality** (1:1, 1:N, M:N) for each relationship.
5. Identify any **weak entities** if applicable.
6. For M:N relationships, identify the **relationship attributes**.

---

## Hints

| Entity (Suggested) | Key Attributes (Suggested) |
|--------------------|---------------------------|
| Hotel | HotelID, Name, City, Address, StarRating |
| RoomType | RoomTypeID, TypeName, PricePerNight, MaxOccupancy |
| Room | RoomID, RoomNumber, Floor |
| Guest | GuestID, Name, Email, Phone, Nationality |
| Booking | BookingID, CheckInDate, CheckOutDate, TotalCost, Status |
| Service | ServiceID, ServiceName, Price |

> Note: These are only hints. You may add or modify attributes as you see fit.

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
