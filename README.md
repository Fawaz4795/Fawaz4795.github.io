# Mohammed Fawaz — Robotics & Automation Portfolio

Personal engineering portfolio covering mechanical design, robotics, embedded systems, computer vision, and AI integration.

**[View the portfolio](https://fawaz4795.github.io/)**

## Current focus

- Bringing mechanical design, hardware, and software together in practical robotic prototypes.
- Computer vision, conversational AI, and embedded control.
- Developing a bipedal robot concept with a movable balancing tail, with mechanical design, actuator selection, balance control, simulation, and prototype testing planned.

## Featured projects

- **[Jenny Bot — Humanoid Desktop Animatronic (V2)](https://fawaz4795.github.io/projects/humanoid-animatronic-v2/)** — Featured first in the project gallery. Combines face tracking, speech-to-text, Groq-based conversation and function calling, and Python servo control on Raspberry Pi / Jetson hardware.
- **[ArecaSort V1](https://fawaz4795.github.io/projects/arecasort-v1/)** — Arecanut grading with YOLOv10 and TensorRT, alongside a mechanical sorting test model.
- **[Automated Fish Sorting & Grading System](https://fawaz4795.github.io/projects/fish-sorting-grading/)** — SolidWorks design, YOLOv8 species identification and defect detection, and Raspberry Pi integration.
- **[Autonomous Robot Navigation](https://fawaz4795.github.io/projects/autonomous-nav-lidar-gazebo/)** — LiDAR mapping, AMCL localisation, and path planning in ROS and Gazebo.
- **[AI Agent Chatbot via n8n](https://fawaz4795.github.io/projects/ai-agent-chatbot-n8n/)** — A conversational workflow with session memory and an external calculator API.

[Explore all projects](https://fawaz4795.github.io/projects/) · [Balancing-tail biped: in development](https://fawaz4795.github.io/current-goals/)

## Technologies

- **Robotics and embedded systems:** Python, C/C++, Arduino Uno, Raspberry Pi, NVIDIA Jetson Orin Nano Super, PCA9685 / I2C, ROS, Gazebo, CoppeliaSim, Lua.
- **AI and automation:** YOLOv8 / YOLOv10, TensorRT, Roboflow, speech-to-text, Groq API, function calling, n8n, webhooks.
- **Design and analysis:** SolidWorks, Fusion 360, MATLAB, RoboAnalyzer, ANSYS Workbench.
- **Portfolio website:** Astro, TypeScript project data, HTML/CSS, GitHub Actions, GitHub Pages.

## Local setup

Requires **Node.js >=22.12.0**, npm, and Git. Run these steps in a terminal:

1. Clone the repository and enter its directory:

   ```sh
   git clone https://github.com/Fawaz4795/Fawaz4795.github.io.git
   cd Fawaz4795.github.io
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Start the development server in background mode:

   ```sh
   npm run dev -- --background
   ```

   Open `http://localhost:4321`. Manage the server with `npm run dev -- status`, `npm run dev -- logs`, and `npm run dev -- stop`.

4. Build and preview the production site:

   ```sh
   npm run build
   npm run preview
   ```

   The build output is written to `dist/`; open the local URL printed by the preview command.

## Content and deployment

- `src/pages/index.astro` — About Me and responsive portrait.
- `src/data/projects.ts` — Project descriptions, technologies, and galleries.
- `src/pages/current-goals.astro` — Current biped project.
- `public/` — Static assets, including project images.
- `.github/workflows/deploy.yml` — Builds and deploys to GitHub Pages on pushes to `main`.
