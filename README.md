# CRUD Operation - Product Management

This is a simple CRUD (Create, Read, Update, Delete) web application for managing product information. It allows users to add, update, and delete product records including product code, name, quantity, and price.

## Features
- **Create**: Add a new product to the list with product code, name, quantity, and price.
- **Read**: View all product records in a tabular format.
- **Update**: Edit existing product details.
- **Delete**: Remove a product from the list.

## Technologies Used
- **HTML**: For creating the structure of the web page.
- **CSS**: For styling the webpage and table.
- **JavaScript**: For handling the logic for CRUD operations.

## File Structure

```plaintext
├── index.html          # The main HTML file with the form and table
├── style.css           # The CSS file for styling the page
├── script.js           # The JavaScript file with logic for CRUD operations
├── README.md           # Project description and instructions
```
## How to Use

Clone the repository to your local machine:

```bash
git clone https://github.com/Prathamesh2911/CRUD_Operation.git
```
Open the `index.html` file in any modern web browser.

You can now add products by filling in the form, view the list of products, update any product details, and delete unwanted records.

### Form Actions:
- **Submit**: Adds or updates a product in the list.
- **Reset**: Clears the form for a new entry.

### Table Actions:
- **Edit**: Allows you to update a product's details.
- **Delete**: Allows you to remove a product from the list.


## How It Works

### Adding a Product:

When you submit the form, the new product information is added to the table.
If there is an existing entry (like when updating), the form will pre-fill with that data and upon submitting, it will update the record in the table.

### Editing a Product:

Clicking the "Edit" button next to a product will fill the form with that product’s details, allowing you to make changes and submit to update.

### Deleting a Product:

Clicking the "Delete" button will remove the product from the list. A confirmation prompt will appear to confirm the deletion.

## Demo

You can test this CRUD app locally by cloning the repository and opening the `index.html` in your browser.

## OUTPUT

<img src="![CRUD_Operation](https://github.com/user-attachments/assets/9ca6b510-a0a5-4005-8614-813c424aeca1)" alt="Alt text for the GIF" />


