
This project uses the TrackMate plugin from ImageJ to process videos and analyze cell movement. Below are the steps to prepare and analyze the data:
Data Preparation

Initial Processing:
-
Movement data is obtained by processing videos with the TrackMate plugin in ImageJ.
In the final step, export a .csv file for each video. This file should contain the tracks for each cell along with their measurements.

File Organization:
-

        Place all the exported .csv files into the Data folder.

    Creating a Record Excel Sheet:
    
        In the Data folder, create an Excel spreadsheet to log the necessary information.
        Populate the spreadsheet with the following fields:
            Type of experiment: Describe the type of experiment conducted.
            Source folder: Specify the location of the original data.
            Date: Record the date of the experiment.
            Replicate number: Indicate the replicate number for the experiment.
            Qualitative information: Include details such as control, treatment, metrics, etc.
            Track number: List the identifiers of the tracks you want to analyze.

Data Analysis
-

    The code will read the .csv files from the Data folder and classify each track based on the categories specified in the Excel sheet.
    The results will then be processed and plotted automatically.

Additional Notes
-

    Ensure that file names and category labels in the Excel sheet are consistent to avoid errors during analysis.
    
