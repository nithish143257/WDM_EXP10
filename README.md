### EX10 [PROJECT] Sentimental Analysis on Any Dataset Using Rapidminer
### DATE: 01/05/2024
### AIM: 
To create a project for Sentimental Analysis on Any Dataset a Using Rapidminer

### Description: 
<div align = "justify">

### Procedure:
1) ***Import Excel data***
    <p>a. Drag the "Read Excel" operator from the IO folder onto the process canvas.
    <p>b. Double-click on the operator to open its configuration panel.
    <p>c. Specify the path to the Excel file you want to analyze.
    <p>d. Configure options such as sheet selection, header inclusion, etc.
    <p>e. Click on the "Run" button to execute the operator and import the Excel data.
2) ***Perform sentiment analysis with Generate Attributes operator***
    <p>a. Drag the "Generate Attributes" operator from the Operators panel onto the canvas.
    <p>b. Connect the output of the "Extract Sentiment" operator to the input of the "Generate Attributes" operator.
    <p>c. Double-click on the "Generate Attributes" operator to configure it.
    <p>d. Specify a name for the new sentiment attribute you want to generate (e.g., "Sentiment").
    <p>e. Choose the sentiment analysis algorithm, "VADER."
    <p>f. Click on the "Run" button to perform sentiment analysis on the Excel data and generate the sentiment attribute.
3) ***Interpret and export the results***
    <p>a. Analyze the sentiment analysis results from the generated visualizations.
    <p>b. If desired, drag the "Write Excel" operator onto the canvas to export the sentiment analysis results to a new Excel file.
    <p>c. Connect the output of the visualization operator(s) to the input of the "Write Excel" operator.
    <p>d. Configure the file path and other settings for the Excel export.
    <p>e. Click on the "Run" button to export the sentiment analysis results to a new Excel file.

### Output:

![image](https://github.com/nithish143257/WDM_EXP10/assets/113762839/fb530933-6d3e-496e-9758-b4cf1bfbd6e8)

![image](https://github.com/nithish143257/WDM_EXP10/assets/113762839/77d29a34-0f6b-49b5-bfba-f18c2f7e3160)

![image](https://github.com/nithish143257/WDM_EXP10/assets/113762839/50be3d9a-be11-4614-8702-0fd3d5132097)

### Result:
Thus sentimental analysis for twitter data is executed successfully using rapidminer.
