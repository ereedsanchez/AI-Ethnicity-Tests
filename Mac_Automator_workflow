# Mac Automator Workflow for Image Processing

This guide will help you create a Mac Automator workflow that:
1. Takes images as input
2. Renames them based on user initials + sequential numbering (e.g., AB_001.jpg)
3. Resizes them to 300 pixels on the longest side while maintaining aspect ratio
4. Converts all images to JPG format

## Step-by-Step Instructions

### Creating the Automator Workflow

1. Open **Automator** from your Applications folder or using Spotlight search
2. Select **New Document**
3. Choose **Workflow** as the document type and click **Choose**

### Setting Up the Workflow

#### Step 1: Get User Input for Initials

1. Search for the **Ask for Text** action in the left sidebar and drag it to the workflow area
2. Configure the action with:
   - Question: "Enter your initials (e.g., AB):"
   - Default Answer: Your initials
   - Make sure "Require an answer" is checked

#### Step 2: Set Up the Image Processing

1. Search for **Get Specified Finder Items** and add it to the workflow
   - This will be a placeholder. When you run the workflow, you'll select the images here

2. Add the **Rename Finder Items** action to your workflow
   - In the dropdown, select "Make Sequential"
   - Format: Text
   - In the "Place after name" field enter: `[text from previous action]_`
   - Start numbers at: 1
   - Number format: Three digits (001, 002, etc.)
   - Click "Options" and check "Show this action when the workflow runs"

3. Add another **Rename Finder Items** action
   - In the dropdown, select "Change File Extension"
   - To: jpg
   - Click "Options" and check "Show this action when the workflow runs"

4. Add the **Copy Finder Items** action
   - Choose a location where you want the processed images to be saved
   - Click "Options" and check "Show this action when the workflow runs"

5. Add the **Scale Images** action
   - Set "To Size (pixels):" to 300
   - Check "Scale proportionally"
   - Check "Scale down only"

### Saving the Workflow

1. Go to **File > Save**
2. Name your workflow (e.g., "Image Processor")
3. Choose a save location
4. Click **Save**

## Using the Workflow

1. Open the saved workflow in Automator
2. Click the "Run" button in the top-right corner
3. Enter your initials when prompted
4. Select the images you want to process when the file dialog appears
5. Confirm any options in the actions that are set to show when the workflow runs
6. The workflow will process your images and save them to the location you specified

## Troubleshooting

- If your images aren't being resized correctly, make sure the "Scale proportionally" option is checked in the Scale Images action
- If you want to change the output format or quality, you can add the "Change Type of Images" action after the Scale Images action
- To create a stand-alone application, save the workflow as an Application instead of a Workflow
