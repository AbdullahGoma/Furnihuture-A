Furnihuture
Welcome to Furnihuture, an e-commerce platform specializing in furniture. This project demonstrates the use of .NET 8, N-Tier Architecture, and various advanced features to create a robust and user-friendly online shopping experience.

Table of Contents
Features
Technologies Used
Installation
Usage
Screenshots
Contributing
License
Contact


Features
1. User Authentication and Authorization
Registration and Login: Users can create accounts and log in securely using email and password.
Role-Based Authorization: Different user roles (Admin, Customer) have specific access permissions. Admins can manage products, orders, and user accounts, while customers can browse and purchase products.
Two-Factor Authentication: An additional layer of security is provided for user accounts.
2. Product Management
CRUD Operations: Admins can create, read, update, and delete products with detailed attributes such as name, description, price, and stock status.
Product Categorization: Products can be organized into categories for easy navigation and filtering.
3. Shopping Cart and Checkout
Shopping Cart: Customers can add products to their cart, update quantities, and remove items.
Order Management: A streamlined checkout process allows customers to review their order, provide shipping information, and complete the purchase.
Payment Integration: Secure payment processing for seamless transactions (if integrated).
4. Order Tracking and History
Order Status Updates: Customers receive real-time updates on their order status (Pending, Approved, Completed, Denied).
Order History: Users can view their past orders and reorder products easily.
5. Advanced Search and Filtering
Search Bar: Users can search for products by name, category, or other attributes.
Filtering Options: Advanced filtering by price, category, availability, and more helps users find exactly what they're looking for.
6. Reporting and Analytics
Admin Dashboards: Visual dashboards for admins to track sales, inventory, customer behavior, and more.
Export to Excel and PDF: Reports can be exported for further analysis and record-keeping.
7. Background Job Processing
Hangfire Integration: Background tasks like sending email notifications, processing large datasets, or cleaning up incomplete orders are handled efficiently without blocking the main application flow.
8. Email Notifications
Transactional Emails: Automated emails for order confirmations, shipping notifications, password resets, etc.
Marketing Emails: Optional promotional emails to keep customers informed about new products and discounts.
9. Responsive Design
Mobile-Friendly: The application is fully responsive, providing an optimal viewing experience on desktops, tablets, and smartphones.
10. Performance Optimization and Security
Optimized Queries and Caching: Efficient data retrieval and caching mechanisms for faster page loads.
Security Best Practices: Implementation of security measures like data encryption, secure password storage, and protection against common vulnerabilities.


Installation
Clone the repository:
bash
Copy code
git clone https://github.com/AbdullahGoma/Furnihuture.git
Navigate to the project directory:
bash
Copy code
cd Furnihuture
Install the required packages:
bash
Copy code
dotnet restore
Set up the database by updating the connection string in appsettings.json and running migrations:
bash
Copy code
dotnet ef database update
Usage
Start the application:
bash
Copy code
dotnet run
Access the application in your web browser at http://localhost:5000.
Admin Account
Username: Admin15
Password: AAAAaaaa1!
Customer Account
Email: AbdullahGomaa@SignUp.com
Password: AAAAaaaa1!
You can also create your own customer account to explore the features.

Screenshots
Include screenshots of the application here to showcase the user interface and functionality.

Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements, bug fixes, or new features.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any inquiries or feedback, please contact:

Abdullah Gomaa
LinkedIn
