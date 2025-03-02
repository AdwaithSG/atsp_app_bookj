# ParkIT - Smart Parking System 🚗

## Introduction
ParkIT is an intelligent and seamless parking reservation system built with Flutter. It allows users to book parking slots conveniently, ensuring a smooth and efficient parking experience. This repository contains the core files of the system, including the main logic and UI components.

## Project Structure 🌿
The project follows a structured hierarchy for better maintainability and scalability:

```
📂 ParkIT
├── 📂 assets
│   ├── booking_data.json   # Sample booking data
├── 📂 lib
│   ├── main.dart            # Application entry point
│   ├── booking_page.dart    # UI for the booking page
│   ├── booking_page_widgets.dart  # Widgets and components for the booking page
├── pubspec.yaml             # Project dependencies and assets declaration
```

## Core Files 📄
### 1️⃣ `main.dart`
- The entry point of the application.
- Loads the booking data from `assets/booking_data.json`.
- Navigates to the `BookingPage` with the loaded data.

### 2️⃣ `booking_data.json`
- Contains sample booking details such as parking location, booking time, and available vehicles.
- Includes attributes like:
  - `fromLocation`, `toLocation`, `parkingSlot`, `bookingTime`, `parkingName`, etc.
  - A list of `vehicleOptions` with different car models.

### 3️⃣ `booking_page.dart`
- Displays booking confirmation details.
- Implements an interactive sliding panel for additional options.
- Features a carousel for parking images.

### 4️⃣ `booking_page_widgets.dart`
- Houses reusable components such as:
  - `BookingSlidingPanel` for selecting vehicle and viewing booking details.
  - `VehicleOption` and `BookingData` models for structured data handling.

## Installation & Setup 🛠
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/ParkIT.git
   cd ParkIT
   ```

2. **Install Dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the App**
   ```bash
   flutter run
   ```

## Developed By 👨‍💻
**Adwaith S Gopal**

---
📌 *Feel free to contribute and enhance the system!* 🚀

![bk1](https://github.com/user-attachments/assets/3d60a060-3f91-45fa-a827-4fb520685e39)

![bk2](https://github.com/user-attachments/assets/9ba465e1-ad9d-45e2-920d-22f2c7e64423)

![bk3](https://github.com/user-attachments/assets/6d1da487-63ed-49d9-b4e4-b3408da8e6ef)

![bk4](https://github.com/user-attachments/assets/2f1bdf9d-1276-46c6-afcf-dc4eb341c021)
