- **NAME:** PARVATHALA SRI KOWSHIK
- **COMPANY:** CODTECH IT SOLUTIONS PRIVATE LIMITED
- **INTERN ID:** CIS255
- **DOMAIN:** EMBEDDED SYSTEMS
- **DURATION:** 6 WEEKS
- **INTERNSHIP PERIOD:** 12TH NOVEMBER 2026 TO 24TH DECEMBER 2026
- **MENTOR:** NEELA SANTHOSH KUMAR

# Smart Agriculture Monitor

## Project Overview

This project is a browser-based simulation of a smart agriculture monitor. It displays simulated soil moisture and temperature readings and provides basic watering advice based on those readings.

This version does not connect to physical sensors or control an irrigation system.

## Features

- Shows soil moisture as a percentage.
- Shows temperature in degrees Celsius.
- Includes sliders to adjust the simulated readings.
- Displays advice based on moisture and temperature.
- Works locally in a web browser.

## Technologies Used

- HTML
- CSS
- JavaScript

## Project Files

Smart-Agriculture-Monitor/
├── index.html
└── README.md

How to Run
1. Save the project code as index.html.
2. Save this README as README.md in the same folder.
3. Open index.html in a web browser.
4. Move the sliders to change the simulated sensor readings.
You can also open the folder in Visual Studio Code and use the Live Server extension.
Advice Rules
Condition	Displayed advice
Soil moisture below 30%	Watering is recommended
Soil moisture above 80%	Avoid watering
Temperature at least 35°C, with moisture between 30% and 80%	Monitor the crop and soil
Other readings	Conditions look suitable; keep monitoring


How It Works
JavaScript reads the values from the sliders and updates the displayed readings. It compares the soil moisture and temperature with simple thresholds, then updates the advice message.

CSS styles the dashboard and its reading cards. HTML defines the page structure and controls.
Possible Improvements
- Connect an Arduino or ESP32 and real soil moisture and temperature sensors.
- Record readings over time.
- Add a chart for historical data.
- Add alerts or irrigation control in a hardware version.

-Output of the project:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bfbceeab-459a-401d-a6f8-9b96981d4ea6" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f0e2daad-8df6-42f9-801a-f86ad7dfbe55" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/41ed7c4a-db60-4015-b0c7-ead4b1980d5b" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/76148737-eae7-4ee9-b5f1-38baaac20a5f" />
