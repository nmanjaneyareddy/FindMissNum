#Missing Numbers Detector

#Overview

This script processes an uploaded Excel file (.xlsx), extracts numeric values from the first column of the first sheet, and identifies any missing numbers in the range. It is useful for checking gaps in sequential numbering, such as book accession numbers, serial records, or inventory lists.


#Features

Accepts an Excel file (.xlsx) via an interactive file upload widget.

Extracts numeric values from the first column of the first sheet, even if mixed with text.

Identifies missing numbers within the detected range.

Provides informative messages and error handling.


#Requirements

Ensure you have the following Python libraries installed:

pandas

ipywidgets

IPython

You can install missing dependencies using:

pip install pandas ipywidgets


#How It Works

The script prompts the user to upload an Excel file (.xlsx).

It reads the first sheet and extracts numeric values from the first column.

The script sorts the numbers and identifies missing values within the detected range.

Results are displayed, including:

The range of numbers found.

The count of missing numbers.

A list of missing numbers.


#Usage

Run the script in a Jupyter Notebook/Google colab.

Upload an Excel file (.xlsx) when prompted.

View the output to check for missing numbers.

Error Handling

The script handles:

Empty or non-existent sheets.

Non-numeric values.

Unexpected file errors.

Invalid or corrupted files.

Update History

03/02/2025 - Latest update with improved error handling and user messages.

#Author

Developed by Anjaneya Reddy