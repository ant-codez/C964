# C964 Capstone Project Demo

Machine learning-based profanity filter. Takes a Phrase and determines if the Phrase contains Profanity and classifies what type of profanity is being used.

## ✨ Try it in your browser ✨

➡️ **[Click Here to Open the Project!!*](https://ant-codez.github.io/C964/lab/index.html)*

![github-pages](https://user-images.githubusercontent.com/591645/120649478-18258400-c47d-11eb-80e5-185e52ff2702.gif)

## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+


## User Guide:

# Step 1: Accessing the Notebook
- Open the JupyterLite interface in Firefox 90+ or a Chromium 89+ browser.
- Click on the Blue Link Provided Above
- Navigate to File named Capstone.ipynb and double click it

# Step 2: Loading the Data
- In the first cell [1] either press Shift + Enter or Click on the ▶️ Button on the nav menu above the cell. 
- Wait for a Classification Report to show up below the first Cell to ensure the model is trained on the test data. This may take a while.

# Step 3: Executing the Application
- Navigate to the second cell [2] containing the profanity filter application code.
- Enter any phrase in the userPhrase variable
- Click on the cell and press Shift + Enter to execute it. The application will then display whether the text is offensive and, if so, categorize the type of profanity detected.

# Step 4: Visualizations(Optional)
- Navigate the filesystem to Visualizations.ipynb and double click it
- In the first cell [1] either press Shift + Enter or Click on the ▶️ Button on the nav menu above the cell. 
- Two Box Graphs will appear when the Cell is finished processing
- In the second cell [2] either press Shift + Enter or Click on the ▶️ Button on the nav menu above the cell. 
- A Pie chart and Two Words clouds will appear when the Cell is finished processing. 
- ⚠️ Caution the word cloud will contain offensive and derogatory words! ⚠️ 

# Example Usage:
- Input: "I really love the weather today."
- Output: "The phrase is not offensive."
- Input: "You are such a [profanity]."
- Output: "The phrase is offensive and belongs to [specific category]."

# Closing the Application
- Once you're done using the application, you can simply close the JupyterLite tab in your browser.
