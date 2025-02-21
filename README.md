# -event-ticket-booking-backend


Event Ticket Booking System - Backend 🎟️

This is the backend service for the Event Ticket Booking System, providing APIs for user registration, event management, ticket booking, QR code generation, and check-in validation. Built using Spring Boot with SQL database, this system ensures secure and efficient event ticketing.

Features

✅ User Authentication & Authorization (JWT-based security)
✅ Event Management (CRUD operations for events)
✅ Ticket Booking (Generate and manage tickets)
✅ QR Code Check-In (Validate ticket check-ins)
✅ Payment Integration (Secure ticket purchases)
✅ Admin Dashboard APIs (Manage users, events, and transactions)

Tech Stack
	•	Backend: Spring Boot, Java
	•	Database: MySQL / PostgreSQL
	•	Security: JWT Authentication, Spring Security
	•	QR Code: ZXing for QR Code Generation
	•	Payment Integration: Stripe / PayPal API
	•	API Documentation: Swagger

Setup Instructions

1️⃣ Clone the repository
2️⃣ Configure database credentials in application.yml
3️⃣ Run mvn spring-boot:run
4️⃣ Access APIs at http://localhost:8080/api/v1
