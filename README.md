# ✈️ FlyEase – Online Flight Booking Website

FlyEase is a dynamic and user-friendly online flight reservation system built with PHP and MySQL. It provides passengers with an intuitive interface to search, book, and manage their flights, while also offering a powerful admin panel for flight scheduling, booking oversight, and payment tracking.

Whether you’re a traveler looking to book a trip or an admin managing airline operations, FlyEase is built to streamline the entire process with simplicity and efficiency.

---

## 📌 Key Features

### 👤 Passenger/User Module

- 📝 **User Registration & Login**
  - Secure login and registration system for passengers.
  - Password handling and session management.

- 📅 **Search & Book Flights**
  - Real-time flight availability display.
  - Book flights with personalized passenger details.
  - Dynamic pricing and scheduling.

- 🎫 **E-Ticket Generation**
  - Automatically generates an electronic ticket (PDF-style layout).
  - Viewable and printable by passengers after successful booking.

- 💳 **Payment System**
  - Integrated payment simulation with success flow.
  - Generates confirmation on successful payment.

- 📂 **My Bookings**
  - Users can view all their previous and upcoming flights.
  - Download tickets and booking summaries.

- ✍️ **Feedback System**
  - Submit comments or concerns after travel.

---

### 🛠 Admin Module

- 🛫 **Flight Management**
  - Add, update, or delete flight records.
  - Set destinations, times, capacities, and pricing.

- 📊 **Booking Oversight**
  - View all passenger bookings.
  - Track payment statuses and flight occupancy.

- 💬 **User Feedback Review**
  - Read feedback submitted by passengers.
  - Analyze satisfaction or issues.

---

## 🧰 Technologies Used

| Layer        | Tech Stack              |
|--------------|--------------------------|
| Frontend     | HTML5, CSS3, JavaScript  |
| Backend      | PHP                      |
| Database     | MySQL                    |
| Server       | Apache (via XAMPP/Laragon)  |

---

## 🛠️ Setup & Installation Guide

To run FlyEase on your local machine:

### Prerequisites:
- XAMPP/Laragon or any LAMP/WAMP stack
- A web browser
- A code editor (e.g., VS Code)


### Steps

1.  **Download the Repository:**


2.  **Move the Project to XAMPP's `htdocs` Directory:**

    Move the downloaded `FlyEase` directory into your XAMPP's `htdocs` folder. For example:

    ```
    C:\xampp\htdocs\FlyEase
    ```

3.  **Start Apache and MySQL:**

    Open the XAMPP Control Panel and start the Apache and MySQL services.

4.  **Create and Import the Database:**

    * Open phpMyAdmin in your web browser: `http://localhost/phpmyadmin`
    * Create a new database named `flyease` (or any name you prefer).
    * Import the SQL file located in the `/database/` directory of the FlyEase project into the newly created database.

5.  **Access the Application:**

    Open your web browser and navigate to:

    ```
    http://localhost/FlyEase/
    ```
