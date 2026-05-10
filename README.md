# XJTLU CPT208 Group B3-4  GridFit - Smart Gym & Body Recomposition App

GridFit is a full-stack gym management and personalized body recomposition application. It provides real-time gym load tracking, coach scheduling, and personalized workout protocols based on the user's current and target body metrics.

## Live Demo

- **Online Preview:** (https://fitgrid-project.vercel.app/)

## Individual Contributions

| Team Member | Student ID | Role | Contributions | Contribution % |
| --- | --- | --- | --- | :---: |
| [你的名字] | [学号] | [例如: UI/UX & Core Logic] | [例如: 负责 3x3 矩阵交互逻辑与沉浸式计时器开发] | 25% |
| Haijin Xia | [学号] | [例如: Frontend Development] | [简述具体负责的功能，例如：教练排班系统开发] | 25% |
| Yifan Xu | [学号] | [例如: Data Visualization] | [简述具体负责的功能，例如：使用 Chart.js 渲染健身房人流预测图表] | 25% |
| Yiyang Lu | [学号] | [例如: Testing & Documentation] | [简述具体负责的功能，例如：项目可用性测试与素材整理] | 25% |

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

## Related Documents

- `docs/project-vision.md` - 项目的设计初衷与产品愿景
- `docs/poster-presentation.pdf` - 答辩展示海报与视觉图表设计
- `docs/defense-script.md` - 项目答辩演讲稿与常见问题准备

## Vibe Coding Logs

AI-assisted coding and prompts used during the development of the Body Matrix and UI components are stored in the `/ai-logs` directory. 
- `/ai-logs/ai-logs` - 核心逻辑生成的 Prompt 历史记录与排错过程
