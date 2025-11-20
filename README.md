# Star Gigs – Project Overview

## 🎵 About Star Gigs

**Star Gigs** is a dynamic web platform designed to connect event organizers with talented performers. It simplifies discovering, booking, and managing performances with separate dashboards for clients and organizers.

## 🌐 Project Structure

Below is the full list of files currently included in the Star Gigs project:

### 🔸 Core Pages

* **index.html** – Homepage introducing the platform with navigation to all sections.
* **About Us.html** – Details the mission, vision, and purpose of Star Gigs.
* **Contact us.html** – Integrated contact form (connected to Formspree) for user inquiries.
* **Login.html** – Login page for both organizers and clients.
* **Sign up.html** – User registration page.
* **sign up organizer.html** – Dedicated sign-up for organizers.
* **Forgot Password.html** – Password recovery page.

### 🔹 Dashboards

* **dashboard.html** – Organizer dashboard for managing gigs and bookings.
* **dashboard client.html** – Client dashboard for browsing, booking, and managing events.

### 📅 Calendars

* **calender.html** – Organizer view of upcoming events and bookings.
* **calender client.html** – Client view for tracking booked or attended performances.

### 💬 Messaging

* **Messages.html** – Messaging interface for organizers.
* **Messages client.html** – Messaging interface for clients.

### 🎤 Gigs & Performance Management

* **Gigs.html** – Organizer’s page to list, edit, or manage performances.
* **Gigs client.html** – Client-facing gig browsing and booking page.
* **performance.html** – Organizer’s performance overview.
* **performance client.html** – Client-side view of performances.
* **Review.html** – Page where users can leave or view reviews for performers or organizers.

### 💵 Payouts

* **payout.html** – Organizer payout and earnings dashboard.
* **payout client.html** – Client payment and invoice tracking page.

### 👤 Profiles

* **Profile.html** – Organizer profile management.
* **Profile client.html** – Client profile page with editable user details.

### ⚙️ Settings

* **Settings.html** – General settings for organizers.
* **Settings client.html** – Settings page for client preferences.

## 💬 Contact Form Integration

The contact form on `Contact us.html` is fully integrated with **Formspree**:

```html
<form action="https://formspree.io/f/xkgyqknr" method="POST">
```

### Features

* Real-time success/error messages using JavaScript.
* Honeypot spam protection.
* Works on all static hosting platforms (GitHub Pages, Netlify, etc.).

## 🧩 Technologies Used

* **HTML5** – Semantic web structure.
* **TailwindCSS** – Modern, responsive styling framework.
* **JavaScript (ES6)** – Handles dynamic form submission and interactivity.
* **Formspree** – Backend-free contact form solution.

## 🚀 How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/star-gigs.git
   ```
2. Open `index.html` in your browser or use **Live Server** in VS Code.
3. Test the **Contact Us** form to confirm message delivery via Formspree.
4. Deploy easily using **GitHub Pages**, **Netlify**, or **Vercel**.

## 🧑‍💻 Future Enhancements

* Backend integration using Node.js or Firebase for real-time data management.
* Authentication system for clients and organizers.
* Rating and review system for performances.
* Live chat and notifications.

## 📬 Contact

For collaborations or feedback:
**Email:** [contact@stargigs.com](mailto:contact@stargigs.com)
**Website:** [Star Gigs](https://stargigs.com)

---

© 2025 **Star Gigs**. All rights reserved.
