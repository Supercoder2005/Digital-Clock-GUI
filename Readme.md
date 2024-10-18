

---

# Digital Clock in Python using Tkinter

This is a simple Python application that displays a live digital clock in a graphical window using the Tkinter library. The clock shows the current time, which updates every second.

## Features

- Displays the current time in `HH:MM:SS` format.
- The clock updates every second.
- Customizable background color, font, and border width for the clock display.

## Prerequisites

Make sure you have Python installed on your system. Tkinter is a standard Python library for GUI programming and does not need to be installed separately.

You can verify your Python version and install the necessary packages by running:

```bash
python --version
```

## How to Run

1. Clone or download this repository to your local machine.

2. Navigate to the directory containing the script.

3. Run the Python script using the command:
   ```bash
   python digital_clock.py
   ```

4. A window displaying a live digital clock will appear.

## Code Overview

### Libraries Used

- **tkinter**: Used for creating the graphical user interface (GUI).
- **time**: Provides the current time in `HH:MM:SS` format.

### Main Components

- **Label**: A `Label` widget is used to display the time in a graphical window.
- **digital_clock() function**: This function continuously updates the label every second to display the current time.
- **label.after()**: This method schedules the `digital_clock()` function to run every 1000 milliseconds (1 second), creating an infinite loop that updates the time.

### Customization

- **Font**: The clock font is customizable by adjusting the `text_font` parameter.
- **Background**: Change the `background` variable to alter the clock's background color.
- **Foreground**: Change the `foreground` variable to alter the font color.
- **Border**: You can adjust the border width of the clock using the `border_width` variable.

## Example Screenshot

![alt text](<Screenshot 2024-10-18 174623.png>)
