# BOOK MY METRO

A Python-based Metro Route Planner that finds the shortest route between stations using **Breadth-First Search (BFS)**. The application calculates fares based on the number of stops, zones crossed, transfers, and peak-hour pricing while generating a detailed travel ticket.

---

## 📌 Features

- 🚇 Shortest route calculation using BFS
- 💰 Fare calculation based on:
  - Number of stops
  - Zone crossings
  - Line transfers
  - Peak-hour multiplier
- 🗺️ Multi-line metro network support
- 🚫 Closed station detection
- ⏱️ Estimated journey time
- 📍 Distance estimation
- 🎟️ Detailed ticket generation
- ✅ Input validation for stations
- 🧩 Modular and beginner-friendly code

---

## 🛠️ Technologies Used

- Python 3
- Graph Data Structure
- Breadth-First Search (BFS)
- Dictionaries
- Lists
- Functions

---

## 📂 Project Structure

```
Meridian-Metro/
│── main.py
│── README.md
```

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/your-username/meridian-metro.git
```

### Move into the project directory

```bash
cd meridian-metro
```

### Run the program

```bash
python main.py
```

---

## 🧭 Metro Network

The project includes multiple metro lines:

- 🔴 Red Line
- 🔵 Blue Line
- 🟡 Yellow Line
- 🟣 Purple Line

Some stations can be marked as **closed**, and the planner automatically avoids them while searching for routes.

---

## 💳 Fare Calculation

The total fare is calculated using:

- Base boarding fare
- Per-stop fare
- Zone surcharge
- Transfer surcharge
- Peak-hour multiplier

A complete fare breakdown is displayed on the generated ticket.

---

## 📷 Sample Output

```
======================================
        MERIDIAN METRO
======================================

Start Station: Harbor
Destination Station: University

🎟️ YOUR TICKET 🎟️

Start                 Harbor
Destination           University
Estimated Time        ~15 mins
Distance              7.2 km

Subtotal              $5.75
TOTAL                 $5.75

😊 Thank you for riding with us!
```

---

## 🎯 Learning Objectives

This project demonstrates:

- Graph Traversal
- Breadth-First Search (BFS)
- Route Planning
- Fare Management System
- Python Function Design
- Input Validation
- Modular Programming

---

## 🚀 Future Improvements

- GUI using Tkinter
- Web application using Flask
- Interactive metro map
- Dijkstra's Algorithm for weighted routes
- Database integration
- Real-time train scheduling
- REST API support

---
If you found this project useful, consider giving it a ⭐ on GitHub!
