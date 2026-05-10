# XJTLU CPT208 Group B3-4: GridFit - Smart Gym & Body Recomposition App

GridFit is a full-stack gym management and personalized body recomposition application. It provides real-time gym load tracking, coach scheduling, and personalized workout protocols based on the user's current and target body metrics.

## Live Demo

- **Online Preview:** [GridFit on Vercel](https://fitgrid-project.vercel.app/)

## Individual Contributions

| Team Member | Student ID | Role | Contributions | Contribution % |
| :--- | :--- | :--- | :--- | :---: |
| Shuaifei Fan | 2362984 | UX Researcher & PM | Led "Motivation & Research" rationale.<br>Synthesized 4 papers & 4 products.<br>Defined stakeholders & Personas.<br>Led Mid-term Poster production. | 25% |
| Haijin Xia | 2361793 | QA & Media Editor | Conducted Usability Testing with 3 users.<br>Documented "Before & After" refinements.<br>Recorded High-Fi prototype screen captures.<br>Produced the final 2-minute teaser video. | 25% |
|Xiyu Zhang| 2364446 | Lead Developer | Built the functional web prototype (Vercel).<br>Programmed 3 "must-have" features.<br>Designed System Architecture diagram.<br>Managed GitHub repo and README. | 25% |
| Zhichong Zhao | 2364597 | UI/UX Designer | Mapped the User Journey.<br>Led rapid ideation ("Crazy Eights").<br>Conducted Design Alternatives comparison.<br>Developed Low-Fi & High-Fi interfaces. | 25% |

## Setup Instructions

### Frontend Setup
The frontend is built with vanilla web technologies and can be served statically.

1. **Do not double-click the HTML file** to open it directly (this causes CORS issues when fetching data). Instead, use a local web server.
2. Navigate to the frontend directory containing `index.html`.
3. Start a simple HTTP server. For example:
   * Using Python: `python -m http.server 3000`
   * Using Node.js: `npx http-server -p 3000`
   * Or use the **Live Server** extension in VS Code.
4. Open your browser and navigate to the local server URL (e.g., `http://localhost:3000/24pre.html`).

## Technologies Used

### Frontend
* **HTML5/CSS3/JavaScript (Vanilla)**: No complex frameworks required, lightweight and fast.
* **Tailwind CSS**: Utility-first CSS framework for rapid UI styling (via CDN).
* **Chart.js**: For rendering gym load predictions and macro/micro workout splits.
* **Lucide Icons**: Clean, scalable SVG icons.

## Features

* **Live Gym Load**: View real-time and predicted gym capacities.
* **Body Recomposition Matrix**: Calibrate your current and target body types to generate a custom macro/micro split (Resistance vs. Cardio).
* **Coach Scheduling**: Browse available coaches, view their schedules, and book in-gym or at-home sessions.
* **Workout Timer**: Built-in full-screen immersive timer to track workout sessions.



## Vibe Coding Logs

AI-assisted coding and prompts used during the development of the Body Matrix and UI components are stored in the `/ai-logs` directory. 
- `/ai-logs/ai-logs` - Prompt history and debugging process for core logic generation.
