# Question 2 — Online E-Commerce Platform (Retail Industry)

## Scenario

An online retail company wants to design a database for its e-commerce platform. The platform allows **sellers** to register and list their **products** for sale. A seller can list many products, but each product listing belongs to one seller.

Products are organized into **categories** (e.g., Electronics, Clothing, Books). A product belongs to one category, but a category can have many products.

**Customers** register on the platform to browse and purchase products. A customer can place many **orders**, but each order belongs to one customer. An order can contain multiple products, and the same product can appear in multiple orders. For each product in an order, the quantity ordered and the unit price at the time of purchase must be stored.

Each order is linked to a **payment**. A payment records the payment method (e.g., Credit Card, PayPal), payment date, and status (Pending, Completed, Failed). One order has exactly one payment.

The platform also supports **reviews**. A customer can write a review for a product they have purchased. A review has a rating (1–5), a comment, and the review date. A customer can review the same product only once.

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
| Seller | SellerID, Name, Email, Phone, StoreName |
| Product | ProductID, ProductName, Description, Price, StockQty |
| Category | CategoryID, CategoryName |
| Customer | CustomerID, Name, Email, Address, Phone |
| Order | OrderID, OrderDate, TotalAmount, Status |
| Payment | PaymentID, Method, PaymentDate, Status |
| Review | ReviewID, Rating, Comment, ReviewDate |

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
