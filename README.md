📊 Spreadsheet Formula Handler

📌 Overview

This project implements a formula evaluation system for a spreadsheet-like grid. Users can input formulas into cells, and the application dynamically calculates and updates the values based on dependencies.

🚀 Features

Dynamic formula evaluation: Supports basic arithmetic operations.

Automatic updates: Changes in dependent cells trigger updates.

Dependency tracking: Maintains parent-child relationships between cells.

UI Integration: Updates UI elements when formulas or values change.

🛠️ How It Works

Formula Input Handling

Users enter formulas (e.g., A1 + A2) into the formula bar.

The system parses and evaluates the formula.

Dependencies are tracked and managed.

Evaluation Process

Identifies referenced cells.

Replaces references with actual values.

Uses JavaScript's eval() function for computation.

Dynamic Updates

When a cell's value changes, its dependent cells update automatically.

The UI is updated to reflect the new values.


📂 File Structure

📦 Project
 ┣ 📜 formula.js    # Handles formula parsing, evaluation, and UI updates
 ┣ 📜 index.html     # Grid layout and UI components
 ┣ 📜 styles.css     # Styling for the spreadsheet UI

🛠️ Technologies Used

JavaScript (for logic and UI updates)

HTML & CSS (for rendering the spreadsheet)

🎯 Future Enhancements

✅ Support for advanced mathematical functions
✅ Implementing undo/redo functionality
✅ Improving performance with optimized formula parsing

✨ Contributing

Feel free to fork this repository, submit issues, or create pull requests to contribute!

💡 Built with passion for spreadsheet lovers!

