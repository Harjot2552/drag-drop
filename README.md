# Drag and Drop Webpage ✨

## Overview
This is a simple drag-and-drop webpage built using **HTML**, **CSS**, and **JavaScript**. It demonstrates the basic functionality of moving draggable list items between two containers.

## Features ✅
- Drag and drop items between two boxes.
- Smooth drag-and-drop functionality with visual feedback.
- Minimal and clean UI.

## How It Works 🛠️
1. **Draggable Items:** The list items on the left container can be dragged and dropped into the right container and vice versa.
2. **Event Listeners:** JavaScript handles drag events (`dragstart`, `dragover`, and `drop`) to allow seamless interaction.
3. **Droppable Areas:** Both left and right containers support drag-and-drop operations.

## Code Explanation 📚
### HTML
- Contains two primary sections (`#left` and `#right`) for draggable list items.
- Items marked with the `draggable="true"` attribute can be moved.

### CSS
- Provides layout styling for the containers and list items.
- Ensures responsive design and visual clarity.

### JavaScript
- Handles the drag-and-drop logic using event listeners:
  - `dragstart`: Stores the currently selected element.
  - `dragover`: Prevents default behavior to enable dropping.
  - `drop`: Appends the dragged element to the target container.

## How to Use 🔄
1. Open the project in your web browser.
2. Drag any list item from the left box.
3. Drop it into the right box, or move it back to the left.

## Project Structure
```
project-folder/
|-- index.html
|-- style.css
|-- script.js
|-- drag_drop_icon.png
```

## Screenshots 🖼️
### Initial View
![Initial Drag and Drop Page](screenshot.png)

## Improvements 📊
- Add hover effects when dragging over droppable areas.
- Provide user feedback (e.g., background color change) during the drag operation.
- Enable persistence using local storage.

## Learnings 💡
- Gained hands-on experience with drag-and-drop event handling.
- Enhanced understanding of event propagation and DOM manipulation.

## License 🔒
This project is free to use for educational purposes.

---
Enjoy dragging and dropping! 💚 Happy Coding! 🚀

