# match-logger-v02

ChatGPT crafted this for me:

Welcome to the Match Logger Tool, a simple and intuitive web-based interface designed to capture events on a football pitch. The tool allows users to log precise X and Y coordinates on a pitch by clicking or tapping directly on the visual pitch representation. The captured data can be exported as a CSV file, making further analysis or visualization straightforward.

Features:

Event Logging: Tap or click directly on the pitch to log an event's coordinates.
Visual Feedback: A red marker appears where you click, giving you immediate feedback.
Export Functionality: Export all logged events with a timestamp to a CSV file, with data stored in a Cartesian-/matplotlib-friendly format.
Undo Option: Made an error? No problem. The "Undo tap" button allows you to remove the most recent event marker.
Reset Option: Clear all logged events and start anew with the "Reset logger" button.
Usage:

Log an Event: Simply click or tap on the desired location on the pitch. A red marker will appear indicating the exact spot.
Undo Last Event: Click the "Undo tap" button to remove the most recent event marker.
Export Data: After logging your desired events, click the "Export data" button. This will generate a CSV file with the events' x and y coordinates along with their timestamps.
Reset Logger: Want to start over? Click the "Reset logger" button to clear all logged events.
Technical Details:

The pitch aspect ratio is maintained at 68:105, aligning with standard football pitch dimensions.
Coordinates are logged in a manner that is compatible with plotting libraries like matplotlib, ensuring data visualization and further analysis remain straightforward.
The tool is designed to be mobile-responsive, making it accessible on a variety of devices.
