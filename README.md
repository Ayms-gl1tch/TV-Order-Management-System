
TV Order Management System
A web-based application for managing television purchase orders, allowing users to select items and calculate totals dynamically.

Project Description
This application provides a front-end interface for browsing a TV catalog and managing a shopping cart. It automatically handles price calculations, including taxes, and prepares data for processing.

Key Features
Dynamic Catalog: The product list is generated from a structured JavaScript data object.

Validation: Ensures user input for quantities is restricted to a range between 1 and 10.

Real-time Totals: Calculates the Total HT (Excluding Tax) and Total TTC (Including Tax) instantly as the cart changes.

Cart Controls: Users can add products to a list or remove specific entries.

JSON Serialization: Converts the final order into a JSON string for easy data transfer.

Technologies Used
HTML5: For the document structure.

CSS3: For the layout and visual styling.

JavaScript: For the application logic and state management.

File Structure
The project is self-contained within gem.html:

Styles: Contains the CSS for the container, table, and button layouts.

Interface: Includes the selection menu, quantity input, and the order table.

Scripts: Contains the product data and functions for cart management.

url:
