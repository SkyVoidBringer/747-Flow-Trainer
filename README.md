Cockpit Flow Trainer
The Cockpit Flow Trainer is a web-based application designed for pilots and aviation enthusiasts to create, practice, and master aircraft procedures and checklists. It provides a highly interactive and customizable environment to build visual representations of a cockpit, define flows, and train on them in a guided or practice mode.

The application is composed of two main parts: the Trainer and the Sequencer.

CockpitFlowTrainer.html: The main interface where you create panels, upload cockpit images, define interactive "hotspots" for every button and switch, and build simple flows.

FlowSequencer.html: A companion tool that opens in a new window, allowing you to chain multiple flows and custom dialogue boxes together to create complex, multi-part sequences (e.g., a full "Before Takeoff" procedure).

Key Features
Visual Cockpit Builder: Upload images of any cockpit panel and define its layout.

Interactive Hotspots: Create clickable areas on your cockpit images for every switch, button, and lever.

Intuitive Flow Creation: Link hotspots together in a specific order to create a procedural flow.

Advanced Sequence Builder: Use the pop-out Sequencer to arrange multiple flows and add rich-text dialogue or instruction cards.

Practice & Training Modes:

Practice Mode: Guides you step-by-step through a flow, highlighting the next correct hotspot.

Test Mode (Implicit): Simply click the hotspots in order without guidance to test your memory.

AI-Assisted Setup: Paste a written checklist, and the app uses the Gemini AI to automatically parse it and guide you through creating the corresponding hotspots.

Full Data Portability: All your data is saved in the browser's localStorage. You can easily import and export your entire setup as a single .json file to move it between computers or share it.

Customizable UI: Features both Light and Dark themes for user comfort.

How to Use
1. Local Setup
To use the application locally, simply download the files and open CockpitFlowTrainer.html in a modern web browser like Chrome, Firefox, or Edge.

2. Initial Configuration
Add a Panel: In the "Panels" section on the left, give your first panel a name (e.g., "Overhead Panel") and click "Add".

Upload an Image: With the new panel selected, drag and drop a corresponding image of that cockpit panel onto the main area on the right.

Enable Edit Mode: At the top of the left column, toggle the switch from "Practice" to "Edit".

Create Hotspots: Click and drag on the cockpit image to create a new hotspot. Give it a name when prompted. You can move and resize hotspots as needed.

Create a Flow: In the "Flows" section, give a new flow a name (e.g., "APU Start") and click "Add".

Add Steps to the Flow: Expand the new flow you created. Use the dropdown menu to select hotspots from the current panel and add them as steps to the flow.

3. Training
Toggle the main switch back to "Practice" mode.

Select the flow or sequence you wish to practice from the dropdown menu.

Click "Start Training".

Follow the on-screen prompts to complete the procedure.

4. Using the AI Feature
Go to Settings (gear icon).

Enter your Gemini API Key. You can get one from Google AI Studio. The key is saved only in your browser.

Paste a written checklist into the "AI-Assisted Setup" text box.

Click "Start AI Setup". The application will guide you to click on each control to automatically create the named hotspots for that checklist.

Hosting Online
You can host this application for free on any static web hosting service. This allows you to access it from any device.

Requirement: Both CockpitFlowTrainer.html and FlowSequencer.html must be in the same directory for the Sequencer pop-up to communicate with the main window.

Recommended Services:

GitHub Pages: Create a public GitHub repository, upload the two HTML files, and enable GitHub Pages in the repository settings.

Netlify: Create a free account, and simply drag the folder containing your two HTML files onto the Netlify dashboard to deploy instantly.

Vercel: Similar to Netlify, Vercel offers a simple way to deploy static sites from a connected GitHub repository.
