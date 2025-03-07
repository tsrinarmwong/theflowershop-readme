# Flower Shop Web App 🌸
A modern eCommerce application for selling flower products and services. Now available at https://theflowershop.azurewebsites.net/

---

![screencapture-localhost-5051-2024-11-20-15_19_47](https://github.com/user-attachments/assets/9f6e0845-e786-416d-8c7e-42247a1efa16)
![screencapture-localhost-5051-Shop-2024-11-20-15_21_22](https://github.com/user-attachments/assets/f3ae3235-1046-4992-aad8-1bb3569e5cd0)
---
    use ID: customer@example.com
    password: Customer@123

## Development
This project was developed from scratch over approximately **30 hours**. It includes features designed to create a smooth shopping experience for customers and efficient management for administrators.

## Project Status
Paused until further applied use cases

## Features
- **Landing Page**: A welcoming homepage highlighting flower products and services.
- **Contact Form**: Integrated with **Brevo** (formerly Sendinblue) for inquiries and customer communication.
- **Identity Authentication**:
  - User registration and login system.
  - Admin and customer roles with specific permissions.
- **Admin Dashboard**:
  - Product management (CRUD operations for inventory).
- **Customer-Facing Shop**:
  - Browsable shop page showcasing products.
  - Add-to-cart functionality.
- **Cart Page**: Allows users to view, modify, and proceed with their selected items.

## Future Implementation
- **Correct Product Model**: Remove CustomerId from /Model/Product.cs.
- **Payment Integration**: Support for payment gateways like **PayPal** or **Apple Pay** to enable seamless checkout.
- **Social Login**: Allow users to log in using **Google**, **Apple**, or other third-party authentication providers.
- **Order Management System**:
  - Enable customers to view their past orders and track current orders.
  - Add an admin panel for managing orders (e.g., updating status, canceling, etc.).
- **Wishlist Feature**: Let users save items for later purchases.
- **Inventory Management**: Real-time stock updates and notifications for low-stock products.
- **Customer Reviews and Ratings**: Allow customers to leave reviews and ratings for products.
- **Search and Filter Options**: Enable advanced search and filters for a better shopping experience (e.g., by price, category, availability).
- **Localization**: Support for multiple languages and currencies to expand the reach of the eShop.
- **Analytics Dashboard**: Add analytics for admins to track sales, customer activity, and other metrics.

---

### Closing Section

## Key Takeaways
This project demonstrates a solid foundation for an eCommerce platform, with essential features for both customers and administrators. It leverages secure practices, like using `secrets.json`, to keep sensitive information safe during development and deployment.

---

## Getting Started
### Prerequisites
- **.NET 6+**
- **SQL Server** (or any other database provider supported by EF Core)

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/FlowerShopWebApp.git
2. Navigate to the project directory:
   ```bash
   cd FlowerShopWebApp
4. Add your configuration to secrets.json (API keys, connection strings, etc.). 
   ```bash
   "SendGrid:SendGridKey": "", "Brevo:BrevoKey": "", "ConnectionStrings:TheFlowerShop:SqlDb": "", "ConnectionStrings:TheFlowerShop:blob": ""
5. Run the project: 
   ```bash
   dotnet run
6. Open your browser at https://localhost:5xxx.
--- 

## License
This project is licensed under the MIT License.

---

### Why These Features?
1. **Payment Integration**: Completes the shopping flow for customers.
2. **Social Login**: Reduces friction in user registration.
3. **Order Management**: Enhances usability for both customers and admins.
4. **Wishlist & Reviews**: Boosts customer engagement.
5. **Search & Filter**: Improves navigation and accessibility.
6. **Analytics**: Provides insights for business growth.

By implementing some of these, your eShop will feel even more complete and user-friendly. Let me know if you'd like me to expand further on any of these! 😊
