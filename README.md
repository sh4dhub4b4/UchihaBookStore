# Uchiha Library Management System

This repository contains a Python script that interfaces with Google Sheets to manage a library system. The script includes functionality for both customers and administrators, allowing for book purchases and inventory management.

## Features

### Customer Mode:

- **View Available Books**: Customers can see the list of books available in the library.
- **Purchase Books**: Customers can buy books, which updates the inventory accordingly.

### Admin Mode:

- **Add New Books**: Administrators can add new books to the library inventory.
- **Remove Books**: Administrators can remove books from the library inventory.
- **View Total Income**: Administrators can view the total income generated from book sales.

## Prerequisites

- Python 3.x
- Google Colab account
- Google Sheets API enabled
- Required Python libraries:
  - gspread
  - pandas

## Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-username/Uchiha-Library-Management.git
