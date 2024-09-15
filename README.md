## **Pizza Hut Database Management System**

### **Project Overview**
This project is designed to manage the operations of a Pizza Hut branch by tracking orders, pizzas, and their details using a structured database. It consists of multiple tables that handle orders, pizza types, sizes, prices, and detailed order information. The system efficiently captures and stores customer orders, making it easy to manage and retrieve data as needed.

### **Database Structure**
The database is comprised of four main tables:
- **Orders**: Tracks the `order_id`, `date`, and `time` for each customer order.
- **Pizza_Details**: Stores details about the pizza types including `pizza_type_id`, `name`, `category` (e.g., vegetarian, non-vegetarian), and `ingredients`.
- **Pizzas**: Contains information about individual pizzas including `pizza_id`, `pizza_type_id`, `size`, and `price`.
- **Order_Details**: Links orders and pizzas, tracking `order_details_id`, `order_id`, `pizza_id`, and `quantity`.

### **Key Features**
- **Order Tracking**: Tracks customer orders with date and time.
- **Pizza Management**: Stores information about different pizza types, sizes, and pricing.
- **Detailed Orders**: Records the specific pizzas and their quantities for each order.

### **Workflow**
1. Customers place orders with specific pizzas and quantities.
2. The system records orders in the `Orders` table and stores pizza-specific details in the `Order_Details` table.
3. The database links each order to the corresponding pizzas, capturing size, type, and price.

### **Technologies Used**
- **Database**: MySQL
- **Programming Language**: Python (for future integration, if applicable)
- **Tools**: SQL, ERD (Entity-Relationship Diagram) for database design

### **Future Enhancements**
- Integration with an ordering system (e.g., web or mobile application).
- Adding real-time order tracking for customers.
- Implementing a user interface for staff to manage orders and inventory.
