# Question 2 — Online E-Commerce Platform (Retail Industry)

## Scenario

A technology startup is launching an online marketplace where independent sellers can list their products and customers can purchase them. You have been brought in to design the database that will power this platform.

**Sellers** must register before they can list any products. Each seller has a unique seller ID, a store name, a full legal name, a verified email address, a phone number, a bank account number for receiving payments, and a registration date. A seller can list as many products as they want on the platform.

Every **product** listed on the platform belongs to exactly one seller. A product record includes a product ID, a product title, a detailed description, the listed price, the available stock quantity, and the date it was listed. Products are also assigned to a **category** to help customers browse. A category has a category ID, a category name, and a short description. Each product belongs to exactly one category, but a category can contain many products.

**Customers** create accounts to shop on the platform. A customer's profile stores their customer ID, full name, email address, a hashed password, phone number, date of birth, and the date they joined the platform. A customer can save multiple **shipping addresses** to their account — each address has an address ID, a street, a city, a postal code, and a country. A customer may have many saved addresses but selects one specific address per order.

When a customer decides to buy, they place an **order**. An order has an order ID, the date and time it was placed, the shipping address chosen for that order, the overall order status (e.g., Pending, Processing, Shipped, Delivered, Cancelled), and the total amount charged. One customer can place many orders, but each order belongs to one customer.

An order can contain multiple products — for example, a customer might order a phone, a case, and a charger in one order. Each product can also appear in orders from many different customers. This means the relationship between orders and products is many-to-many. For each product within a specific order, the system must record the quantity the customer ordered and the unit price of the product at the exact time of purchase (since prices may change over time).

Every order must go through a **payment** process. Each payment is linked to exactly one order and records the payment ID, the payment method used (e.g., Credit Card, PayPal, Bank Transfer, Cash on Delivery), the transaction reference number provided by the payment gateway, the date and time the payment was processed, the amount paid, and the payment status (Successful, Failed, Refunded).

After receiving their products, customers are encouraged to leave a **review** for each product they have purchased. A review contains a review ID, a star rating between 1 and 5, a written comment, and the date the review was submitted. A customer can write at most one review per product. A product can receive reviews from many customers.

---

## Your Task

Draw a complete **Entity-Relationship (ER) Diagram** for the Online E-Commerce Platform described above.

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
