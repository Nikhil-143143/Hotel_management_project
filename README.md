Hotel Management System
This project provides a basic hotel management system using both a Java console program and a web interface with HTML, CSS, and JavaScript. It allows users to manage room occupancy with options for checking guests in, checking guests out, and viewing room statuses.

Features:-
1.Java Console Program: Provides command-line options for room management (Check-In, Check-Out, View Occupancy, and Exit).
2.Web-Based Interface:
(a)User-friendly graphical interface for managing rooms.
(b)Styled with CSS for a modern look and feel.
(c)Interactive JavaScript functions for handling room assignments.

Java Console Program:-
Code Structure
1.String[][] rooms: Stores room numbers and occupancy status.
2.checkIn(): Assigns a guest to a specified room if it’s empty.
3.checkOut(): Clears the room’s occupancy if it’s occupied.
4.viewOccupancy(): Displays all rooms and their current occupancy status

Usage Instructions:-
1.0Run the Program: Compile and execute the program using a Java compiler.
2.Select Menu Options: Enter the number corresponding to the desired action (1 for check-in, 2 for check-out, etc.).
3.Check-In a Guest: Choose an available room, then enter the guest's name.
4.Check-Out a Guest: Choose an occupied room to mark it as empty.
5.View Occupancy: Display the occupancy status of all rooms.
Web-Based Interface:-
The web interface provides similar functionality as the Java console program with a graphical interface, using HTML, CSS, and JavaScript.

Code Structure
HTML (index.html):
1.Sets up the page structure, including buttons for Check-In, Check-Out, and View Occupancy.
2.An output section (output div) displays messages and room updates.

CSS (style.css):
Provides a clean, responsive design for the interface.
JavaScript: Contains functions that manage room status and handle user interactions.

HTML Overview
The HTML file includes:
1.<!DOCTYPE html> declaration and <html>, <head>, and <body> sections.
2.Buttons: The Check-In, Check-Out, and View Occupancy buttons are connected to JavaScript functions.
3.Output Section: A div with id="output" displays room status updates.

CSS Overview
The CSS file (style.css) is designed for a professional, modern look:

General Styles:
1.Resets margin and padding for a consistent appearance.
2.Centers content in the browser window using display: flex and align-items: center.

Container Styling:
1.Sets up a white card-style container with padding, border-radius, and a box shadow.
2.Centers and constrains width for readability.

Button Styles:
1.Appearance: Full-width, bold, and rounded buttons for usability.
2.Colors: Primary blue background with hover and active states for user feedback.

Output Box:
1.A scrollable, bordered area where messages are displayed.
2.Styled for readability with soft colors and overflow control to handle long content.

JavaScript Overview
Main Functions:
1.checkIn(): Prompts the user to enter a room number and guest name, updating the room status.
2.checkOut(): Prompts for a room number and checks out the guest if occupied.
3.viewOccupancy(): Displays the status of all rooms in the output area.
4.displayMessage(): Dynamically updates the output area with messages about room statuses.

Usage Instructions
1.Open index.html: Open this file in a web browser.
2.Click Buttons: Use Check-In, Check-Out, or View Occupancy buttons.
3.Follow Prompts: Enter room numbers and guest names as prompted.
