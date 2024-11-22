# Risk Classification Web Application

## Overview

The **Risk Classification Web Application** is a simple, interactive tool designed to categorize tasks based on their probability of failure and the impact of failure. This tool visualizes the risk classification using a color-coded grid (Low, Medium, High Risk) and places a marker (`X`) on the grid to represent the task's risk level dynamically.

This application is suitable for project managers, risk assessors, and decision-makers who need to prioritize tasks or actions based on risk levels.

---

## Features

1. **Interactive Form:**
   - Allows the user to input a task name, probability of failure (1-3), and impact of failure (1-3).
   - Classifies the task based on the selected values.

2. **Risk Classification Logic:**
   - **Low Risk**: Minimal probability and impact.
   - **Medium Risk**: Moderate probability or impact.
   - **High Risk**: High probability and/or high impact.

3. **Color-Coded Risk Matrix:**
   - **Green:** Low Risk.
   - **Yellow:** Medium Risk.
   - **Red:** High Risk.

4. **Dynamic Visualization:**
   - Places an "X" marker on the grid to visually represent the task's risk level.

5. **Clear Labels:**
   - Axis labels (`Probability of Failure` and `Impact/Damage`) are positioned outside the grid for better clarity.

---

## Purpose

This application is built to:
1. Help users quickly identify and prioritize tasks based on their risk levels.
2. Provide a simple, visual representation of risks for easy understanding.
3. Support decision-making processes in fields such as project management, safety engineering, and quality assurance.

---

## How to Use

1. **Open the Application:**
   - Copy the provided HTML code into a file (e.g., `index.html`) and open it in a web browser.

2. **Input Task Information:**
   - Enter a task name in the input field.
   - Select the probability of failure (`Low`, `Medium`, or `High`).
   - Select the impact of failure (`Low`, `Medium`, or `High`).

3. **Classify Risk:**
   - Click the **"Classify Risk"** button.
   - The application will:
     - Display the task's risk classification as text (e.g., "Low Risk").
     - Mark the corresponding cell in the grid with an "X".

---

## Technical Details

1. **Technologies Used:**
   - **HTML5**: For the web structure.
   - **CSS3**: For styling, including the color-coded grid and dynamic visualization.
   - **JavaScript**: For the classification logic and grid interaction.

2. **Grid Design:**
   - The grid is created using a CSS Grid layout.
   - Rows represent `Probability of Failure`, while columns represent `Impact/Damage`.

3. **Dynamic Marker:**
   - The marker (`X`) is dynamically added to the grid based on the input values.

---

## Example

### Input:
- Task: "Fix Critical Bug"
- Probability: High (3)
- Impact: High (3)

### Output:
- Classification: "High Risk"
- Grid Visualization:
  - "X" is placed in the top-right cell (High Probability, High Impact).

---

## Future Enhancements (Optional)
- Add export functionality (e.g., download the grid as an image or PDF).
- Include multiple tasks in a session and display a list of all tasks and their classifications.
- Implement a backend to save data for long-term analysis.

---

## Author
This web application is built with simplicity and usability in mind. Feel free to modify it for your specific needs!
