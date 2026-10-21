# 🚌 Bus Ticket Booking System in C++

A console-based **Bus Ticket Booking and Reservation System** developed in C++. The application allows passengers to book tickets and view booking details, while administrators can manage buses, seat availability, routes, and schedules.

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [How to Use](#-how-to-use)
- [Sample Outputs](#-sample-outputs)
- [Fare Calculation](#-fare-calculation)
- [Expected Outcomes](#-expected-outcomes)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

## 📌 Project Overview

The Bus Ticket Booking System is a C++ application designed to simplify basic bus reservation and management operations through a command-line interface.

It provides separate administrator and passenger functionalities, enabling bus management, ticket booking, seat availability checks, booking display, and fare calculation with an optional insurance charge.

## ✨ Features

### 🔐 Administrator Functions

- Add new buses with relevant details.
- Manage seat allotment and availability.
- View registered buses and their schedules.
- Maintain route information, including sources and destinations.
- Manage bus and ticket-related operations.

### 🎫 Passenger Functions

- View available buses.
- Select a bus for ticket booking.
- Book tickets for available buses.
- View booked ticket information.
- Calculate fares according to passenger categories.
- Add optional insurance charges where supported.

### 💰 Fare Calculation

The system demonstrates different fare categories:

- Child fare
- Adult fare
- Temporary fare, as shown in the provided sample output
- Optional insurance charges based on distance and passenger category

## 🛠️ Technologies Used

- **Programming Language:** C++
- **Interface:** Command-line interface (CLI)
- **Compiler:** GCC (`g++`) or another compatible C++ compiler
- **Core Concepts:** Conditional statements, loops, functions, user input, data management, and fare calculation

## 🚀 Installation

### Prerequisites

Install a compatible C++ compiler and ensure that `g++` is accessible from your terminal.

### 1. Clone the Repository

```bash
git clone https://github.com/usmana0820/Bus-Ticket-Booking-System.git
```

### 2. Navigate to the Project Directory

```bash
cd Bus-Ticket-Booking-System
```

### 3. Compile the Program

If the main source file is named `main.cpp`, compile it using:

```bash
g++ main.cpp -o bus-reservation
```

If the project contains multiple C++ source files, include the required files in the compilation command.

### 4. Run the Application

On Linux or macOS:

```bash
./bus-reservation
```

On Windows Command Prompt:

```bash
bus-reservation.exe
```

**Note:** The commands assume the main source file is `main.cpp`. Adjust the filename and compilation command to match the actual repository contents.

## 🧭 How to Use

### Administrator Mode

1. Launch the application.
2. Select the administrator option from the menu.
3. Log in using the appropriate credentials, if required.
4. Add new buses and enter their details.
5. View bus schedules and manage seat availability.

### Passenger Mode

1. Select the passenger option.
2. View available buses.
3. Choose a bus using its bus number.
4. Enter the required booking details.
5. Review the fare and optional insurance charges.
6. View the booked ticket information.

## 🖥️ Sample Outputs

The following examples illustrate the application's documented workflows. Actual output may vary depending on the implementation.

### 1. Adding a Bus

```text
Adding a Bus

Enter bus no: 1234
Enter Driver's name: John Doe
Arrival time: 09:00 AM
Departure: 05:00 PM
From: CityA
To: CityB

Seats initialized.
```

### 2. Selecting a Bus for Booking

```text
Select the Bus No: 1234

----------------------------------------------------------------
Bus No | Source | Destination | Bus Name | Distance (KM)
----------------------------------------------------------------
1234   | CityA  | CityB       | ABC Bus  | 100

Arrival: 09:00 AM
Departure: 05:00 PM
Duration: 8 hrs
```

### 3. Displaying a Booked Ticket

```text
Booked Bus is ...

----------------------------------------------------------------
Bus No | Source | Destination | Bus Name | Distance (KM)
----------------------------------------------------------------
1234   | CityA  | CityB       | ABC Bus  | 100

Arrival: 09:00 AM
Departure: 05:00 PM
Duration: 8 hrs
```

### 4. Viewing Available Buses

```text
Bus no: 1234
Driver: John Doe

Arrival time: 09:00 AM
Departure time: 05:00 PM

From: CityA
To: CityB
```

## 💵 Fare Calculation

The provided example demonstrates category-based fares and an optional insurance selection.

```text
Child fare: 500
Adult fare: 1000
Temporary fare: 1500

Want to take insurance (y/n)? y

Rs 1/Km for child
Rs 2/Km for adult

Total fare: 1600
```

The final fare depends on the program's calculation logic, passenger category, distance, and selected insurance option. The example above preserves the values from the original documentation.

## 📈 Expected Outcomes

- Simplified bus reservation through a console interface.
- Organized bus schedules and route information.
- Improved visibility of seat availability.
- Convenient access to booking details.
- Basic passenger fare calculation.
- Practical experience with C++ programming and application logic.

## 🤝 Contributing

Contributions and suggestions are welcome.

1. Fork this repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature-branch
   ```

3. Commit your changes:

   ```bash
   git commit -m "Improve booking functionality"
   ```

4. Push your branch:

   ```bash
   git push origin feature-branch
   ```

5. Open a pull request.

## 📄 License

This project is documented as using the MIT License. See the [`LICENSE`](LICENSE) file for details if it is present in the repository.

## 👩‍💻 Contact

**Usmana Zulfiqar**

- GitHub: [@usmana0820](https://github.com/usmana0820)
- Email: [usmanazulfiqar20@gmail.com](mailto:usmanazulfiqar20@gmail.com)

Feel free to reach out with questions, feedback, or suggestions.
