# 🎬 InoxPress — Movie Ticket Booking App

**InoxPress** is a modern React Native application that empowers users to effortlessly browse movies, book tickets, and make secure payments — all within a smooth, intuitive interface. Powered by Supabase backend and integrated with Razorpay for seamless transactions, this app replicates a full-fledged movie ticketing experience inspired by Inox cinemas.

---

## ✨ Key Features

### 🎥 Movie Browsing  
- Browse a dynamic catalog of movies with high-quality posters, genres, and descriptions.  
- Responsive, clean UI with polished cards and Inox-inspired branding.

### 🎟️ Ticket Booking & Payment  
- Select preferred showtimes and seats with real-time availability checks.  
- Enter your email and pay securely via integrated Razorpay payment gateway (WebView).  
- Instant booking confirmation with unique booking IDs.

### 🔖 QR Code Ticket Generation  
- After successful payment, generate a scannable QR code as your ticket.  
- QR code enables easy theater-side confirmation and entry management.

### 🛠️ Admin Panel  
- Secure login for admins to manage movie listings and showtimes.  
- Add, edit, or remove movies and showtime details effortlessly.

### 🪑 Seat Management  
- Automatic update of booked seats in the database to prevent double booking.  
- Real-time feedback for seat availability.

### 📧 Validation & Alerts  
- Email validation ensures accurate user input.  
- Graceful error handling and success notifications provide smooth UX.

---

## 🛠️ Technology Stack

| Technology          | Purpose                                |
|---------------------|--------------------------------------|
| React Native & Expo | Cross-platform mobile UI & navigation|
| Expo Router         | File-based routing and navigation    |
| Supabase            | Backend database, authentication     |
| Razorpay            | Payment gateway integration           |
| react-native-svg    | QR code generation                    |
| react native (uuid)                | Unique booking ID generation          |

---

## 🔐 Security & Environment

- All sensitive API keys and credentials are securely stored in environment variables (`.env`), never committed to version control.  
- Admin authentication is validated against Supabase to protect the admin panel.  
- Razorpay test keys are used for secure payment processing during development.

---

## 🏞️ User Journey

1. **Discover:** Browse movies with rich details and posters.  
2. **Select:** Choose showtime and preferred seats.  
3. **Pay:** Enter email and complete payment securely via Razorpay.  
4. **Confirm:** Receive booking confirmation with a unique ID.  
5. **Ticket:** View and present a QR code for theater entry.  
6. **Admin:** Manage content and bookings securely via admin panel.

---

## 🚀 What Sets This Project Apart

- **End-to-end flow:** From movie discovery to payment and ticket generation.  
- **Real-time seat management:** Ensures seamless booking without conflicts.  
- **Clean, professional UI:** Inspired by Inox branding, emphasizing usability and aesthetics.  
- **Robust backend:** Supabase provides a scalable and reliable data store and authentication system.  
- **Extensible architecture:** Designed to easily add features like user profiles, notifications, and analytics.

---

## 📈 Future Enhancements

- User authentication with profile management and booking history.  
- Real-time seat selection with live updates and seat maps.  
- Push notifications for reminders and promotions.  
- Multilingual support for wider reach across regions.  
- Advanced admin analytics dashboard for insights and reporting.

---

**InoxPress** demonstrates a practical, production-ready mobile app integrating modern cloud backend services and payment solutions — perfect for showcasing your full-stack development skills in mobile ecosystems.
