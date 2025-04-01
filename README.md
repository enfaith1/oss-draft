# Optical Shop System

The **Optical Shop System (OSS)** is a Java-based desktop application designed to streamline the operations of an optical shop. It provides features for managing inventory, customer records, appointments, point-of-sale transactions, and more. The system leverages JSON files for data storage and retrieval, ensuring a lightweight and efficient solution.

---

## Features

1. **Login System**  
   - Secure login functionality using credentials stored in a JSON file (`users.json`).
   - Displays error messages for incorrect username or password.

2. **Main Menu**  
   - Centralized navigation hub for accessing various modules:
     - Inventory Management
     - Customer Records
     - Appointment Records
     - Eye Doctor Schedule
     - Point of Sale
     - Logout functionality

3. **Inventory Management**  
   - View, add, edit, and delete inventory items such as eyeglass frames and lenses.
   - Data is stored in JSON files (`frame_material.json` and `frame_lenses.json`).
   - Displays inventory details in a tabular format.

4. **Customer Records**  
   - Manage customer details and records.  
   - Placeholder for future enhancements.

5. **Appointment Records**  
   - Manage and view appointment schedules for customers.  
   - Placeholder for future enhancements.

6. **Eye Doctor Schedule**  
   - Manage and view schedules for eye doctors.  
   - Placeholder for future enhancements.

7. **Point of Sale**  
   - Facilitates sales transactions.  
   - Placeholder for future enhancements.

---

## Project Structure

```
OpticalShopSystem/
├── src/
│   └── OpticalShopSystem/
│       ├── Login.java
│       ├── MainMenu.java
│       ├── Inventory.java
│       ├── CustomerRecords.java
│       ├── AppointmentRecords.java
│       ├── EyeDoctorSchedule.java
│       ├── PointOfSale.java
│       ├── users.json
│       ├── frame_material.json
│       └── frame_lenses.json
└── README.md
```

---

## Prerequisites

- **Java Development Kit (JDK)** installed.
- A Java IDE (e.g., NetBeans, IntelliJ IDEA, Eclipse) or command-line tools.
- Basic understanding of JSON file structures.

---

## How to Run

1. **Setup**:
   - Clone or download the project to your local machine.
   - Ensure the JSON files (`users.json`, `frame_material.json`, `frame_lenses.json`) are in the correct directory.

2. **Execution**:
   - Open the project in your preferred IDE.
   - Run the `Login.java` file to start the application.

---

## File Descriptions

### Java Files
- **`Login.java`**: Handles user authentication.
- **`MainMenu.java`**: Provides navigation to different modules.
- **`Inventory.java`**: Manages inventory operations.
- **`CustomerRecords.java`**: Placeholder for customer management.
- **`AppointmentRecords.java`**: Placeholder for appointment management.
- **`EyeDoctorSchedule.java`**: Placeholder for managing doctor schedules.
- **`PointOfSale.java`**: Placeholder for sales transactions.

### JSON Files
- **`users.json`**: Stores user credentials for login.
- **`frame_material.json`**: Contains details about eyeglass frame materials, including stock and price.
- **`frame_lenses.json`**: Contains details about eyeglass lenses, including grades, stock, and price.

---

## JSON File Structures

### `users.json`
```json
{
    "users": [
        { "username": "1", "password": "1" },
        { "username": "2", "password": "2" },
        { "username": "3", "password": "3" }
    ]
}
```

### `frame_material.json`
```json
{
    "eyeglass_frame_materials": {
        "metal": [
            { "frame_material": "Stainless Steel", "stock": 50, "price": 2000 },
            { "frame_material": "Titanium", "stock": 50, "price": 5000 }
        ],
        "plastic": [
            { "frame_material": "Acetate", "stock": 50, "price": 2500 },
            { "frame_material": "TR-90", "stock": 50, "price": 1800 }
        ]
    }
}
```

### `frame_lenses.json`
```json
{
    "eyeglass_frame_lenses": [
        {
            "lens_type": "Single Vision",
            "grades": {
                "-1.00": { "price": 2000, "stock": 50 },
                "-1.50": { "price": 2000, "stock": 50 }
            }
        },
        {
            "lens_type": "Bifocal",
            "grades": {
                "+1.00": { "price": 1800, "stock": 50 },
                "+1.50": { "price": 1800, "stock": 50 }
            }
        }
    ]
}
```

---

## Future Enhancements

- **Customer Records**: Add functionality for managing customer details.
- **Appointment Records**: Implement appointment scheduling and management.
- **Eye Doctor Schedule**: Add features for managing doctor availability.
- **Point of Sale**: Complete the sales transaction module.
- **Database Integration**: Replace JSON files with a relational database for scalability.

---

## Contact

For any inquiries or support, please contact the project administrator.
