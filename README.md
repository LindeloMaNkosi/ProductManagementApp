# Product Management Application

This Java GUI application helps keep track of a company's products by storing and displaying product details, including product ID, product name, and product price.

## Features

- **Product Details Capture**: Three text fields for capturing product ID, name, and price.
- **Display Area**: Non-editable text area to display product details.
- **Submit Button**: Saves product details to a `Products.txt` file when clicked.
- **Search Button**: Allows users to search for a product based on the product ID. Prompts the user with an input box to enter the product ID and displays the product name and price.

## File Handling

- **Products.txt**: A sequential file that stores product details with fields for product ID, product name, and product price.
- **Data Loading**: Loads product details from `Products.txt` and populates the text area on form load and whenever a new product is saved.

## Setup and Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/LindeloMaNkosi/ProductManagementApp.git
