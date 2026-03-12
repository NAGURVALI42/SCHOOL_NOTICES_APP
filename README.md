# School Notices App

> **The School Notices App is an Android-based communication platform designed to simplify how schools share important information. It provides a centralized digital notice board, allowing teachers to publish updates in real-time and students to access them instantly.**

---

# Problem Statement

**Traditional school communication relies heavily on physical notice boards or word-of-mouth. This outdated approach frequently leads to:**
* Missed or overlooked announcements.
* Delayed communication during urgent situations.
* A lack of centralized, easily accessible information.

**Solution:** This application bridges the communication gap by digitizing the notice management process, ensuring timely, organized, and accessible information sharing for everyone.

---

# Core Features

## Teacher Module
* **Full CRUD Operations:** Add, edit, and delete notices.
* **Media Support:** Upload images alongside text notices.
* **Event Management:** Organize and manage school events and announcements.
* **Analytics:** View basic statistics on notice visibility.

## Student Module
* **Instant Access:** View the latest notices and school announcements in real-time.
* **Event Tracking:** Access specific details, dates, and times for upcoming events.
* **Intuitive UI:** A simple, distraction-free interface built for quick reading.

## Universal App Features
* **Role-Based Authentication:** Secure login routing for Teachers vs. Students.
* **Dynamic Content:** RecyclerView-based lists for smooth scrolling and dynamic data loading.
* **Real-Time Data:** Fetches live data via REST APIs.
* **Modern Design:** Clean, Material Design UI guidelines.

---

# Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | Android (Kotlin) |
| **UI Components** | RecyclerView, ViewBinding, Material UI |
| **Backend API** | PHP (REST APIs) |
| **Database** | MySQL |
| **Local Server** | XAMPP |
| **Networking** | Retrofit Library |

---

# Database Architecture

**The system utilizes MySQL to securely store and manage application data, structured around the following key entities:**
* **Users:** Authentication details and role indicators (Teacher / Student).
* **Notices:** Text content, timestamps, and author IDs.
* **Events:** Scheduled dates, descriptions, and related metadata.
* **Media:** File paths and references for uploaded notice images.
