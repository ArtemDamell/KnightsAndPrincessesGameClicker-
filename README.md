# Knights And Princesses Game Clicker

This is a C# code snippet for a desktop application in Windows Presentation Foundation (WPF). The application provides a simple user interface with a main window that includes a button to close the application, a button to show an "About" window, and three buttons for mouse-related actions.

The code defines a method DoMouseClick that takes two integers x and y as parameters and simulates a left mouse click at the specified location using the SetCursorPos and mouse_event functions from the Windows API.

The Button_Write method retrieves the current mouse position using the GetMousePosition method and displays the X and Y coordinates in text boxes. The Button_Clear method simply clears the text boxes.

The Button_Start method retrieves the X and Y coordinates and the number of repetitions from text boxes, and then calls the DoMouseClick method the specified number of times.

The code also includes event handlers for mouse down events, key down events, and focus events for the buttons.

## How to use:
1. Setup this
2. Enter the number of repetitions
3. Focus on the add button (TAB)
4. Set cursor to the desired position
5. Press ENTER to record a position
6. Press START button for start

