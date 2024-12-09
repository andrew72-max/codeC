# Shopping List Application

This is a simple shopping list web application where users can add items to a list, mark them as purchased, and clear the entire list. The application utilizes HTML, CSS, and JavaScript to create an interactive and user-friendly interface.

## Features

- **Add Items**: Users can add items to the shopping list by typing them in the input field and clicking the "Add Items" button.
- **Mark as Purchased**: Each item has a button to mark it as purchased. When an item is marked, it gets a line-through effect and a green-yellow background color.
- **Clear List**: The entire shopping list can be cleared with the "Clear List" button.

## Files

1. **HTML**: The core structure of the shopping list page, including input fields, buttons, and an unordered list for the items.
2. **CSS**: Styling for the shopping list, including background colors, item spacing, and button designs.
3. **JavaScript**: Logic for adding items to the list, marking them as purchased, and clearing the list.

## Code Breakdown

### HTML

The HTML structure contains:
- An input field (`<input>`) for entering new shopping items.
- A button to add items (`<button id="additem">`).
- A button to clear the list (`<button id="clear">`).
- An unordered list (`<ul id="itemlist">`) where the items are displayed.

### CSS

The CSS styles:
- The body background color is set to a custom color.
- Items that are marked as purchased have a green-yellow background and a line-through decoration.
- Buttons are styled with padding, font size, and background color to make them visually appealing.

### JavaScript

The JavaScript functionality includes:
- An event listener for the "Add Items" button that adds the typed item to the list.
- An event listener for the "Clear List" button that clears all items from the list.
- An event listener for each "Mark Purchased" button, which toggles the "purchased" class for each item, visually indicating that the item is marked as purchased.

## How to Use

1. Open the HTML file in a web browser.
2. Type an item into the input field.
3. Click the "Add Items" button to add the item to the list.
4. Click "Mark Purchased" next to an item to mark it as purchased.
5. To clear the entire list, click the "Clear List" button.

## Example Usage

1. **Adding Items**: Type "Milk" into the input field and click "Add Items". "Milk" will appear in the list.
2. **Marking Items as Purchased**: After adding items, click the "Mark Purchased" button next to an item to mark it as purchased.
3. **Clearing the List**: Click "Clear List" to remove all items from the shopping list.

## License

This project is open-source and free to use. Feel free to modify it as you like!