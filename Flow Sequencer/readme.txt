*******************************************************************************
* *
* COCKPIT FLOW TRAINER                              *
* *
*******************************************************************************

Hello!

This is a simple tool to help you practice and memorize your cockpit flows and 
procedures. It's composed of two main parts: the Cockpit Flow Trainer, where 
you can practice, and the Flow Sequencer, where you can create and edit your 
own procedures.

===============================================================================
  HOW TO USE THE TRAINER (CockpitFlowTrainer.html)
===============================================================================

1.  **Open the file:**
    Simply open the `CockpitFlowTrainer.html` file in your web browser (like 
    Chrome, Firefox, or Safari).

2.  **Import Data:**
    You'll need to load a data file to get started.
    * Click on the "Import" button.
    * Select the .json file that contains the cockpit layout and procedures 
      (e.g., CockpitFlowTrainer_Export_2025-07-09T03-41-58-443Z.json).
    * The cockpit image and hotspots will then be loaded.

3.  **Practice Mode:**
    * Make sure "Edit Mode" is turned OFF.
    * Select a flow from the "Flow" dropdown menu.
    * Click the "Start Practice" button.
    * The trainer will guide you through the selected flow, highlighting the 
      hotspots you need to interact with in sequence.

===============================================================================
  HOW TO CREATE AND EDIT FLOWS (FlowSequencer.html)
===============================================================================

If you want to create your own procedures or edit existing ones, you can use 
the `FlowSequencer.html` file. 

*** The AI Builder is the PREFERRED and EASIEST method. ***

-------------------------------------------------------------------------------
  Using the AI Builder (Recommended)
-------------------------------------------------------------------------------

The AI Builder simplifies the process of creating a flow by using a checklist.

1.  **Open the Flow Sequencer:**
    Open `FlowSequencer.html` in your web browser.

2.  **Go to the AI Builder:**
    Find the "AI Builder" panel.

3.  **Use the Checklist:**
    You will see a checklist of all the available interactions (hotspots) in 
    the cockpit.

4.  **Select Items:**
    Go through the checklist and check the box next to each item you want to 
    include in your new flow. Make sure you select them in the correct order 
    you want them to appear in the procedure.

5.  **Generate the Flow:**
    * Give your new flow a name in the "Flow Name" field.
    * Click the "Generate" button.

6.  **Review and Refine:**
    The AI will create the flow based on your checklist selections. The new 
    flow will appear in the "Builder Panel". You can then make any final 
    adjustments by dragging and dropping steps.

-------------------------------------------------------------------------------
  Manual Flow Creation
-------------------------------------------------------------------------------

If you prefer, you can still create a flow manually:

1.  **Open the Flow Sequencer:**
    Open the `FlowSequencer.html` file in your web browser.

2.  **Creating a Flow:**
    * In the "Builder Panel", you can create and name a new flow.
    * You can add steps to your flow from the "Library Panel" by dragging 
      and dropping them into the builder.

===============================================================================
  EXPORTING AND SHARING
===============================================================================

- Once you're happy with your flow, whether you created it with the AI Builder
  or manually, you can export it.
- Click on the "Export" button and save the .json file.
- You can then share this .json file with your friends, and they can import 
  it into the `CockpitFlowTrainer.html` to practice the flows you've created.

===============================================================================
  THE DATA FILE (.json)
===============================================================================

The .json file is what contains all the information for the trainer. It 
includes:

- The cockpit image.
- The locations of all the hotspots.
- The different flows and procedures you've created.

You can share this single file with your friends, and they'll have everything 
they need to start practicing.

*******************************************************************************