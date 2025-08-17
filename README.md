📌 Simple Kanban Board

A lightweight drag-and-drop Kanban Board built with HTML, CSS, and JavaScript.
This project demonstrates how to create a Trello-like task management interface without external libraries.

🚀 Features

📝 Three lists: To Do, In Progress, and Done

🎯 Drag-and-drop support for moving tasks between lists

📱 Responsive design (works on desktop & mobile)

✨ Smooth hover and drag effects for better UX

📂 Project Structure
├── index.html   # Main HTML file (board structure)
├── style.css    # Styling for layout, cards, and responsiveness
└── script.js    # Drag-and-drop functionality

🖥️ Demo Preview

To Do → Initial tasks (e.g., Wash Dishes, Buy Groceries)

In Progress → Tasks currently being worked on (e.g., Learn to code)

Done → Completed tasks

Users can drag a task card and drop it into any column.

⚙️ How It Works

Each card is draggable (draggable="true")

Drag events (dragstart, dragend) capture the selected task

Drop zones (the lists) handle events like dragover, dragenter, and drop

When dropped, the card is appended to the target list

📋 Usage

Clone or download this repository

Open index.html in your browser

Drag tasks between columns to organize your work

📱 Responsiveness

On desktop, lists appear side by side

On mobile, lists stack vertically for easy navigation

🔮 Future Improvements

Add local storage to save task positions

Enable task creation & deletion

Add color labels or priorities

Implement drag handle & smooth animations
