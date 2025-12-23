<div align="center">

[![Backend](https://img.shields.io/badge/Backend-Laravel-FF2D20.svg)](https://laravel.com/)  
[![Project Type](https://img.shields.io/badge/Type-Car%20Rental%20Marketplace-blue.svg)](#)  
[![Project Stage](https://img.shields.io/badge/Status-In%20Development-orange.svg)](#)  
![Documentation](https://img.shields.io/badge/Documentation-WIP-blue.svg)  
![Focus](https://img.shields.io/badge/Focus-Multi--Role%20Rental%20System-green.svg)

</div>

---

<div align="center">

**[VISION](#-vision) •  
[FEATURE HIGHLIGHTS](#-feature-highlights) •  
[SYSTEM MODULES](#-system-modules) •  
[INSTALLATION](#-installation)**

</div>

---

# 🚗 Vision

**CarRent** is a car rental marketplace inspired by the Airbnb model, designed to connect car owners (lessors) with renters through a structured, role-based platform.

The system allows renters to browse available cars, compare prices, select rental periods using a calendar-based flow, and complete reservations through checkout and payment.  
At the same time, lessors can list vehicles, manage bookings, and control availability.

The platform is built with **Laravel**, focusing on:
- Real-world rental workflows
- Clear role separation
- Scalable marketplace architecture
- Administrative oversight and reporting

---

# 🚀 Feature Highlights

## Public Website (Marketplace)

Core capabilities available to visitors and authenticated users:

- **Home Page & Listings**
  - Display available cars with pricing, location, and images
  - Clean, card-based layout for browsing
  - Direct access to listing details

- **Search & Discovery**
  - Search cars by keywords and location
  - Filter available listings based on availability

- **Calendar-Based Rental Flow**
  - Select rental start and end dates
  - Automatic calculation of rental duration and cost

- **Checkout & Payment**
  - Reservation confirmation
  - Payment flow after date selection
  - Booking stored and tracked in the system

---

## Authentication & Role-Based Access

The system is divided into three main roles, each with its own interface and permissions.

---

# 🧩 System Modules

## 1) Lessor (Car Owner Portal)

- Dedicated registration and login as a lessor
- Dashboard to manage owned cars
- Add car listings with:
  - Rental location and address
  - Daily rental price
  - Availability
  - Image gallery
- Accept or reject booking requests
- View rental history and booking status

---

## 2) Renter (Customer Portal)

- User registration and authentication
- Browse all available cars
- Search and select suitable listings
- Choose rental period using a calendar
- Complete reservation and payment
- View booking history
- Reference link to Airbnb for conceptual UX comparison

---

## 3) Admin (System Management)

- Centralized admin dashboard
- View platform statistics:
  - Total renters
  - Total lessors
  - Active and completed rentals
- Full user management (renters and lessors)
- Monitor all reservations
- View sales and platform activity
- Create, edit, update, and delete:
  - Users
  - Listings
  - Reservations

---

# ⚙️ Installation

To run the project locally, ensure you have **PHP**, **Composer**, and **MySQL** installed.


1. **Clone the Repository**

    ```bash
    git clone https://github.com/Aseel-Aburumman/DreamRent.git
    cd DreamRent
    ```

2. **Install Dependencies**  
   Run the following command to install Laravel and its dependencies:

    ```bash
    composer install
    ```

3. **Environment Setup**  
   Duplicate `.env.example` as `.env` and configure your database settings:

    ```plaintext
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=DreamRent
    DB_USERNAME=root
    DB_PASSWORD=
    ```

4. **Generate Application Key**  
   This key secures your application:

    ```bash
    php artisan key:generate
    ```

5. **Database Migration and Seeding**  
   Run the migrations to set up the database tables and initial data:

    ```bash
    php artisan migrate --seed
    ```

6. **Start the Application**  
   Launch the Laravel development server:

    ```bash
    php artisan serve
    ```

    DreamRent  is now live on [http://localhost:8000](http://localhost:8000)!

---

# 🎉 Get Started
 
--- 

