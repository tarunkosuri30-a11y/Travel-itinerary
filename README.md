# Travel-itinerary
It’s professionally formatted with sections like features, technologies, usage instructions, OOP explanation, and future scope 👇

# ✈️ Travel Itinerary Planner (Java)

## 🧩 Overview
**Travel Itinerary Planner** is a Java-based console application designed to help users organize and manage travel plans efficiently.  
It allows users to store and view details about destinations, activities, transportation, and accommodation — all in one place.

This project was developed by **K. Tarun (24501A05B2)** as part of an academic case study demonstrating the use of **Object-Oriented Programming (OOP)** principles in Java.

---

## 🎯 Problem Statement
Planning a trip manually can often be:
- Confusing and unorganized  
- Time-consuming to manage transport, accommodation, and activities separately  
- Lacking a single, clear view of the entire trip  

**Objective:**  
To design a system that allows users to **plan, manage, and visualize** their complete itinerary — including destinations, activities, transport, and hotels — in a structured and efficient way.

---

## 💡 Solution
This project implements a **Java OOP-based system** that models real-world travel components.  
The design follows modular class-based architecture with five main entities:

1. **Activity** – Stores details about individual activities (name, time, location, description)  
2. **Destination** – Contains multiple activities and calculates stay duration  
3. **Transport** – Manages travel details between destinations  
4. **Accommodation** – Stores hotel name, room type, and stay period  
5. **Trip** – Aggregates all components and displays the complete itinerary  

### 📘 Class Hierarchy


Trip
├── Destination
│ └── Activity
├── Transport
└── Accommodation


---

## ⚙️ Technologies Used
- **Programming Language:** Java  
- **Concepts:** Object-Oriented Programming (Encapsulation, Composition, Abstraction)  
- **Libraries:** `java.time.LocalDate`, `java.time.temporal.ChronoUnit`  
- **IDE:** Eclipse / IntelliJ IDEA  

---

## 🧠 OOP Concepts Applied

| Concept | Implementation |
|----------|----------------|
| **Encapsulation** | Each class hides data and exposes only relevant behavior |
| **Composition** | Trip contains Destinations, each containing Activities |
| **Abstraction** | The `showItinerary()` method provides a clear view of all data |
| **Modularity** | Each class handles a specific travel-related responsibility |
| **Reusability** | Easily add new destinations, transport, or hotels |

---

## 💻 How to Run

### 🔹 Step 1: Clone the Repository
```bash
git clone https://github.com/<your-username>/Travel-Itinerary-Planner.git

🔹 Step 2: Navigate to Project Directory
cd Travel-Itinerary-Planner

🔹 Step 3: Compile the Java Files
javac TravelItineraryPlanner.java

🔹 Step 4: Run the Program
java TravelItineraryPlanner

🧩 Example Output
============================================
        ✈ Travel Itinerary Planner ✈
============================================
Trip Name: Europe Vacation
Trip Duration: 2025-06-01 to 2025-06-20

---------- Destinations ----------
Destination: Paris
Stay Duration: 4 days
Activities:
   - Eiffel Tower Visit at 10:00 AM in Eiffel Tower — Sightseeing and photography
   - Louvre Museum at 2:00 PM in Louvre — Explore world-famous art

Destination: Rome
Stay Duration: 4 days
Activities:
   - Colosseum Tour at 11:00 AM in Colosseum — Historic landmark tour
   - Vatican Museum at 3:00 PM in Vatican City — Art and culture visit

---------- Transports ----------
• Flight from HomeCity to Paris (Departure: 08:00 AM, Arrival: 10:00 AM)
• Train from Paris to Rome (Departure: 09:00 AM, Arrival: 05:00 PM)
• Flight from Rome to HomeCity (Departure: 08:00 PM, Arrival: 10:00 PM)

---------- Accommodations ----------
• Deluxe room at Hotel Parisian (2025-06-01 to 2025-06-05)
• Standard room at Hotel Roma (2025-06-06 to 2025-06-10)
============================================

🧾 Project Structure
Travel-Itinerary-Planner/
│
├── src/
│   ├── Activity.java
│   ├── Destination.java
│   ├── Transport.java
│   ├── Accommodation.java
│   ├── Trip.java
│   └── TravelItineraryPlanner.java
│
├── README.md
└── .gitignore

🚀 Future Enhancements

✅ Add a Graphical User Interface (GUI) using JavaFX or Swing

✅ Connect to a database (MySQL) to save and load itineraries

✅ Enable user input instead of hard-coded data

✅ Generate PDF or text-based travel summaries

🧑‍💻 Author

K. Tarun
📧 Email: tarunkosuri30@gmail.com

📜 License

This project is licensed under the MIT License — feel free to use, modify, and distribute it with attribution.

⭐ If you found this project helpful, don’t forget to star this repository on GitHub!

---

Would you like me to include a **README badge section** (Java version, license, build status, etc.) and a **preview image of your poster** at the top (like on GitHub project pages)?  
It’ll make your repository look more professional.
