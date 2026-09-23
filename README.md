# A.S Sports Shop Billing System

A Python-based sports shop billing and inventory management system developed as a Class 12 school project.

The project includes two implementations:

1. Console-based billing application
2. Tkinter-based graphical application

Product information is stored in a CSV file and processed using Pandas.

## Features

- View available sports products
- CSV-based product inventory
- Purchase multiple products
- Enter product quantities
- Calculate total purchase amount
- Generate and display bills
- Customer name validation
- 10-digit phone number validation
- Customer rating system
- Feedback collection
- Pandas-based data handling
- Tkinter graphical user interface

## Technologies Used

- Python
- Pandas
- Tkinter
- CSV

## Project Structure

```
AS-Sports-Shop-Billing-System/
├── README.md
├── requirements.txt
└── sports_shop_billing/
    ├── products.csv
    ├── sports_shop_billing.py
    └── sports_shop_billing_gui.py
```

## Files

| File | Description |
|---|---|
| sports_shop_billing.py | Console-based billing application |
| sports_shop_billing_gui.py | Tkinter-based GUI application |
| products.csv | Sports product inventory |
| requirements.txt | Python package dependencies |

## Installation

### Prerequisites

- Python 3.x
- pip

### Steps

Check your Python version:

```
python --version
```

Clone the repository:

```
git clone https://github.com/Adix10/AS-Sports-Shop-Billing-System.git
```

Navigate to the project directory:

```
cd AS-Sports-Shop-Billing-System
```

Install the required dependencies:

```
pip install -r requirements.txt
```

Note: Tkinter is included with standard Python installations on Windows, so no separate installation is required for it.

## Running the Application

### Console Version

```
python sports_shop_billing/sports_shop_billing.py
```

### GUI Version

```
python sports_shop_billing/sports_shop_billing_gui.py
```

## Application Workflow

```
Customer Details
      ↓
View Products
      ↓
Select Products
      ↓
Enter Quantity
      ↓
Calculate Total
      ↓
Generate Bill
      ↓
Rating & Feedback
```

## Product Inventory

The inventory is stored at:

```
sports_shop_billing/products.csv
```

It contains information such as:

- Product ID
- Product Name
- Stock Quantity
- Rate

## Concepts Practiced

- Functions
- Conditional statements
- Loops
- Lists
- User input
- Input validation
- Pandas DataFrames
- CSV file handling
- Billing calculations
- Tkinter GUI development
- GUI dialogs and user interaction

## Project Background

This was developed as a Class 12 school project to learn and apply Python programming through a practical billing-system use case. It includes both command-line and graphical implementations.

## Author

**Aditya Sharma**

GitHub: [https://github.com/Adix10](https://github.com/Adix10)

## License

This project is intended for educational and learning purposes.
