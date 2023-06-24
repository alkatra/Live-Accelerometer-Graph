# Live Accelerometer Graph

The "Live Accelerometer Graph" repository is a project created for an assignment that focuses on implementing socket-based communication with an Arduino connected to an ADXL accelerometer. It uses WebSockets to transmit accelerometer data to a web application in real-time, enabling live data visualization.

Key Components:
1. **ADXL Accelerometer Arduino Integration**: The Arduino is connected to an ADXL accelerometer which is responsible for collecting acceleration data on the x, y, and z axes.
2. **Socket-Based Communication**: The Arduino communicates the acceleration data through a WebSocket, ensuring real-time data transmission to the web application.
3. **Plotly.js Data Visualization**: The live acceleration data from the Arduino is visualized using Plotly.js, a high-level, declarative charting library. This allows the data to be represented as live graphs on the screen, showcasing the x, y, and z values in a user-friendly manner.

This repository provides a fascinating glimpse into the real-time data visualization of accelerometer readings, and showcases the power of socket communication. Whether you're a student, an educator, or just an enthusiast, this project is a great resource for understanding and implementing socket-based communication and live data visualization.

*Note: To use this project, you must have an Arduino set up with an ADXL accelerometer. Please refer to the "Installation" section of the documentation for more information on how to set up and run this project.*
