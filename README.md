# Level Adjustment Detection

## Description

This project detects and analyzes level adjustments in data or signals. It uses signal processing techniques.

## Features

* Detects level shifts in a given dataset.
* Analyzes the characteristics of the detected shifts.
* Provides visualization of the original data and detected shifts.

## Technologies Used

* Python
* NumPy
* SciPy
* Matplotlib

## Setup and Installation

## Running the Code

1.  **Prepare your data:**
    * The input data should be a time series or signal stored in a CSV file or a similar format that Pandas can read.
    * Modify the script to load your specific data file.

2.  **Run the main script:**
* Run the .py file in VS Code, google collab or other platform with the ability of running this file.
* The script will process the data, detect level adjustments, and display the results.

## Data Format
The data should be in a tabular format with three columns, that represent level, velocity and flow in that order.
It should also be passed the diameter of the pipe where that data ahs been collected. Pass it in the last for digits of the filename. Example: filename_0032 = a 32 inch pipe Diameter

## Configuration
   * The script may have parameters that can be adjusted, such as the sensitivity of the shift detection.  These will be detailed in the script itself.


