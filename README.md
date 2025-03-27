# Flight Booking System

## Overview
This is a **Flight Booking System** built using Java, following an Object-Oriented Programming (OOP) approach. The system allows customers to book flights, cancel bookings, and manage flight schedules.

## Features
- Add new customers
- Add flights with capacity constraints
- Book flights for customers
- Cancel flight bookings
- Save and load data using serialization

## Project Structure
The project is structured into separate modules:
```
📂 flight-booking-system
├── 📂 src
│   ├── 📂 commands        # Contains booking system logic
│   ├── 📂 data            # Manages file storage (saving/loading)
│   ├── 📂 main            # Entry point of the application
│   ├── 📂 model           # Contains core models (Customer, Flight, Booking)
│   ├── 📂 gui             # Placeholder for gui of the project
└── README.md             # Documentation
```

## Installation
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/flight-booking-system.git
   ```
2. **Open in Eclipse**
   - Open Eclipse IDE.
   - Import the project as an existing Java project.
3. **Run the Application**
   - Navigate to `main/Main.java`
   - Run the `Main` class.

## Usage
1. Start the program.
2. Choose an option from the menu.
3. Enter customer or flight details when prompted.
4. Book or cancel flights as needed.
5. Exit the system to save data.

## Dependencies
- Java 8 or higher
- Eclipse IDE (or any Java IDE)

## Future Enhancements
- Implement GUI using JavaFX or Swing.
- Add a database instead of file-based storage.
- Introduce user authentication for admins and customers.

## License
This project is licensed under the MIT License.

---
Created by **Animesh Maharjan** 🚀

