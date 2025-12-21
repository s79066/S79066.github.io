abTimer Pro | Research Assistant
LabTimer Pro is a specialized productivity tool designed for researchers and students in scientific fields like Food Science. It combines a high-precision countdown timer with a persistent laboratory task manager to streamline bench work and experimental monitoring.

🔬 Core Functionality
The application serves as a dedicated "Analysis Module" for time-sensitive laboratory procedures:

Precision Countdown: Features a default 15-minute analysis cycle, essential for monitoring reactions or thermal processing.

Dynamic Visual Feedback: Uses a "Pet Display" system where icons change based on state: 🧪 (Standby), 🔬 (Analyzing), and ✅ (Complete).

Audio Alerts: Implements a synthesized triangle-wave frequency ramp to signal the end of a process without the need for external media files.

Persistent Checklist: A built-in "Lab Checklist" allows users to track sub-tasks like sample preparation or reagent additions.

🧪 Laboratory Theme Features
The application is built with a professional research aesthetic:

State-Driven Animations: When the timer is active, the microscope icon pulses to indicate an ongoing analysis.

System Status Console: A dedicated status box provides real-time system feedback (e.g., "SYSTEM: ANALYZING SAMPLES...") mirroring laboratory instrument displays.

Data Persistence: Integrated with localStorage, the checklist ensures that your laboratory protocol remains intact even if the browser is refreshed or closed accidentally.

Scientific UI: Designed with a "Lab Blue" and "Success Green" color palette to maintain a clean, high-contrast environment suitable for laboratory settings.

🛠️ Technical Stack
HTML5/CSS3: Utilizes CSS variables for theme consistency and Flexbox for a responsive, centered layout.

Vanilla JavaScript: Handles time calculations, DOM manipulation, and state management without external dependencies.

Web Audio API: Generates native browser tones for alerts, ensuring high compatibility and zero latency.

LocalStorage API: Manages browser-side data storage for the task list.

🚀 How to Use
Start Analysis: Click the Start button to begin the countdown and trigger the "Analyzing" state.

Manage Tasks: Type a task (e.g., "Prepare Buffer solution") and click Add. Tasks can be toggled as completed with a click (strike-through).

Reset/Pause: Use the control panel to halt the timer or reset the module to its default standby state.

Clear Records: Use the Clear All Tasks button to wipe the current checklist for a new experiment.
