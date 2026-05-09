# GridFit - Smart Gym & Body Recomposition App

GridFit is a full-stack gym management and personalized body recomposition application. It provides real-time gym load tracking, coach scheduling, and personalized workout protocols based on the user's current and target body metrics.

## Technologies Used

### Frontend
* **HTML5/CSS3/JavaScript (Vanilla)**: No complex frameworks required, lightweight and fast.
* **Tailwind CSS**: Utility-first CSS framework for rapid UI styling (via CDN).
* **Chart.js**: For rendering gym load predictions and macro/micro workout splits.
* **Lucide Icons**: Clean, scalable SVG icons.

### Backend
* **Java 17**: Core programming language.
* **Spring Boot 3.2.0**: For creating the standalone RESTful API.
* **Maven**: Dependency management and build tool.

##  Setup Instructions

### 1. Backend Setup
The backend is a Spring Boot application providing REST APIs for the frontend.

1. Ensure you have **Java 17** installed on your machine.
2. Open a terminal and navigate to the `backend` directory.
3. Run the application using the Maven wrapper:
   * **Windows**: `mvnw.cmd spring-boot:run`
   * **macOS/Linux**: `./mvnw spring-boot:run`
4. The backend server will start and listen on `http://localhost:8080`.

### 2. Frontend Setup
The frontend is built with vanilla web technologies and can be served statically.

1. **Do not double-click the HTML file** to open it directly (this causes CORS issues when fetching data). Instead, use a local web server.
2. Navigate to the frontend directory containing `24pre.html`.
3. Start a simple HTTP server. For example:
   * Using Python: `python -m http.server 3000`
   * Using Node.js: `npx http-server -p 3000`
   * Or use the **Live Server** extension in VS Code.
4. Open your browser and navigate to the local server URL (e.g., `http://localhost:3000/24pre.html`).

##  Features
* **Live Gym Load**: View real-time and predicted gym capacities.
* **Body Recomposition Matrix**: Calibrate your current and target body types to generate a custom macro/micro split (Resistance vs. Cardio).
* **Coach Scheduling**: Browse available coaches, view their schedules, and book in-gym or at-home sessions.
* **Workout Timer**: Built-in full-screen immersive timer to track workout sessions.
