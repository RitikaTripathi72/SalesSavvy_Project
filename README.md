
# Sales Savvy - E-Commerce Platform 🛒

## 🌟 Project Overview

**Sales Savvy** is a comprehensive e-commerce solution designed for small and medium businesses. This full-stack application combines modern web technologies to deliver a scalable, secure, and user-friendly online shopping experience.

### 🎯 What Sales Savvy Offers
- **Admin Panel**: Comprehensive management of products, users, and orders
- **Customer Interface**: Intuitive product browsing, shopping, and order tracking
- **Secure Payments**: Integration with Razorpay, PayPal, and Stripe
- **Scalable Design**: Modular architecture for easy feature additions

---

## 🚀 Features

### 👨‍💼 Admin Features
- **User Management**: Create, update, deactivate user accounts
- **Product Management**: Add, edit, delete products and manage categories
- **Order Management**: Approve, cancel, ship orders, and track status
- **Sales Reports**: Generate performance analytics and insights
- **Payment Oversight**: Monitor transaction details and statuses

### 👥 Customer Features
- **Account Management**: Secure registration, login, and profile management
- **Product Browsing**: Search products by category, name, or tags
- **Shopping Cart**: Add, remove, update items with real-time price calculation
- **Order Tracking**: Monitor delivery status (Pending → Approved → Shipped → Delivered)
- **Payment Processing**: Secure transactions via multiple payment gateways

---

## 🛠️ Technology Stack

### Frontend
- **React.js** - Interactive user interfaces
- **CSS/Bootstrap** - Responsive styling and design

### Backend
- **Java** - Core programming language
- **Spring Boot** - Robust backend framework
- **Spring Web** - RESTful API development
- **Spring Data JPA** - Database integration
- **Spring Security** - Authentication and authorization
- **Hibernate** - ORM for database operations

### Database & Payment
- **MySQL** - Primary data storage
- **Razorpay/PayPal/Stripe** - Payment gateways

### DevOps
- **Docker** - Containerization
- **Maven** - Build tool

---

## 🏗️ System Architecture

### Modular Service Framework

#### 1. **Authentication Service**
- JWT token-based session management
- Role-based access control for Admins and Customers

#### 2. **User Management Service**
- User registration with email verification
- Profile management and admin user control

#### 3. **Product Management Service**
- Complete product CRUD operations
- Category and tag management with image upload

#### 4. **Cart Management Service**
- Dynamic cart operations with real-time price calculations

#### 5. **Order Management Service**
- End-to-end order lifecycle management
- Status tracking and shipping options

#### 6. **Payment Service**
- Multi-gateway payment integration
- Secure transaction processing and confirmation

---

## ⚡ Requirements

### Performance
- Support for 100 concurrent users
- Response time under 2 seconds

### Security
- HTTPS for all data transmission
- JWT token-based authentication
- Encrypted password storage
- Secure payment processing

### Scalability
- Modular architecture for easy feature additions
- Database optimization for growth

---

## 🚀 Getting Started

### Prerequisites
- Java 11 or higher
- Node.js 14 or higher
- MySQL 8.0 or higher
- Docker (optional)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/RitikaTripathi72/SalesSavvy_Project.git
   cd SalesSavvy_Project
   ```

2. **Backend Setup**
   ```bash
   cd backend
   mvn clean install
   mvn spring-boot:run
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. **Database Setup**
   ```sql
   CREATE DATABASE sales_savvy;
   ```
   Update `application.properties` with your database credentials.

### Docker Deployment
```bash
docker-compose up -d
```

---

## 📚 Key API Endpoints

### Authentication
- `POST /admin/login` - Admin authentication
- `POST /user/login` - Customer authentication
- `POST /user/register` - Customer registration

### Product Management
- `GET /api/products` - Fetch all products
- `POST /api/products` - Add new product (Admin)
- `PUT /api/products/{id}` - Update product (Admin)

### Order Management
- `GET /api/orders` - Fetch user orders
- `POST /api/orders` - Place new order
- `PUT /api/orders/{id}/status` - Update order status (Admin)

---

## 🗂️ Project Structure

```
sales-savvy/
├── README.md
├── docker-compose.yml
├── backend/
│   ├── src/main/java/com/salessavvy/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── model/
│   │   └── config/
│   ├── pom.xml
│   └── Dockerfile
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── services/
│   ├── package.json
│   └── Dockerfile
└── database/
    └── schema.sql
```

---

## 🎯 Deliverables

- ✅ Fully functional e-commerce website
- ✅ **Microservices-based** architecture
- ✅ **AWS cloud-ready** deployment
- ✅ Dockerized application ready for deployment
- ✅ RESTful API with proper endpoints
- ✅ Responsive frontend interface
- ✅ Secure payment integration

---

## 📈 Future Enhancements

- Recommendation System ("You may also like" features)
- Multi-language and multi-currency support
- Advanced analytics and reporting
- Mobile app development
- Email notifications for orders
- Customer reviews and ratings

---

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📧 Contact

**Project Developer**: [Ritika Tripathi]
- Email: ritikatripathi164@gmail.com
- GitHub: [RitikaTripathi72](https://github.com/RitikaTripathi72)

**Project Link**: https://github.com/RitikaTripathi72/SalesSavvy_Project

---

**⭐ If you found this project helpful, please give it a star!**
