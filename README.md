# Try-Next.js
Learning to use Next.js, creating a online food delivery system

Online Food delivery - Next.js / MySQL/ 

- A web-based food ordering system where users can register, browse a menu, place orders, and track their order status, while admins manage orders and menu items through a dashboard.

*System Scope* 

- Customer Side 
   * Login / Signup
   * Browse Menu
   * Add to cart 
   * Place Order
   * View Status

- Admin Side
  * Login
  * View all orders (Dashboard)
  * Update order status
  * Manage menu (add/edit/delete)
 
*System Architecture* 

#Frontend (Next.js UI)
  - Pages
    * Login
    * Dashboard(Admin only)
    * Menu
    * Status

#Backend (Next.js API)
  - Handles
    * Authentication
    * Order Processing
    * CRUD
    * Status updates

Database (stores)
  * Users
  * Products
  * Orders
  * Order items
