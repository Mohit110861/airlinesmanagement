# ✈️ Travel Management System - Flight Fare Optimization

This project is a **Travel Management System** built in **C++**, which helps users book flight tickets between major Indian cities by finding the **cheapest travel route** available.  
It implements **Bellman-Ford Algorithm** to calculate the **minimum cost** between any two cities, even if there is no direct flight available.

The system is fully console-based and handles user authentication, ticket booking, and route optimization.

---

## 🚀 Features

- **User Login/Signup:** Create a new account or log in with an existing account.
- **List of Cities:** View a list of 15 major Indian cities.
- **Route Optimization:** Find the cheapest route (direct or via other cities) using Bellman-Ford Algorithm.
- **Flight Cost Display:** View ticket prices for different paths.
- **Passenger Details:** Input and store passenger information (name, age, gender).
- **Ticket Generation:** Generate and display e-tickets with journey details.
- **Data Storage:** Login and passenger details saved in text files (`login.txt` and `ticket.txt`).

---

## 🛠️ Technologies Used

- **C++**
- **File Handling (for login and ticket storage)**
- **Bellman-Ford Algorithm (for cheapest route detection)**
- **OOP Concepts (Classes, Structures, Inheritance)**

---

## 🏙️ Cities Covered

- Delhi
- Mumbai
- Chennai
- Kolkata
- Kerala
- Hyderabad
- Pune
- Goa
- Bangalore
- Amritsar
- Jaipur
- Patna
- Puducherry
- Srinagar
- Bhopal

---

## 📂 How to Run

1. **Clone or Download** the project files.
2. **Compile** the C++ file using a compiler like `g++`.
   ```bash
   g++ travel.cpp -o travel
