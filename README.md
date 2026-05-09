# GridFit - Smart Gym & Body Recomposition App

GridFit is a full-stack gym management and personalized body recomposition application. It provides real-time gym load tracking, coach scheduling, and personalized workout protocols based on the user's current and target body metrics.

## Technologies Used

### Frontend
*   **HTML5 / CSS3 / JavaScript (Vanilla):** No complex frameworks required, lightweight and fast.
*   **Tailwind CSS:** Utility-first CSS framework for rapid UI styling (via CDN).
*   **Chart.js:** For rendering gym load predictions and macro/micro workout splits.
*   **Lucide Icons:** Clean, scalable SVG icons.

## Features

*   **Live Gym Load:** View real-time and predicted gym capacities.
*   **Body Recomposition Matrix:** Calibrate your current and target body types to generate a custom macro/micro split (Resistance vs. Cardio).
*   **Coach Scheduling:** Browse available coaches, view their schedules, and book in-gym or at-home sessions.
*   **Workout Timer:** Built-in full-screen immersive timer to track workout sessions.

## Setup Instructions

### Frontend Setup

The frontend is built with vanilla web technologies and can be served statically. 

**Important:** Do not double-click the HTML file to open it directly (this causes CORS issues when fetching data or loading modules). Instead, use a local web server.

1.  Navigate to the frontend directory containing your HTML file (e.g., `index.html` or `24pre.html`).
2.  Start a simple HTTP server. 
    *   **Using Python:**
        ```bash
        python -m http.server 3000
