# Reviewer Extractor

This **Reviewer Extractor** code is from my Fall 2023 NASA internship: Expanding Diversity in the NASA Astrophysics Panel.

## What it does

The Reviewer Extractor uses a csv file (either pre-loaded or the user can upload their own), and can filter what ouput is displayed based
on what the user searches and which specific column they want to search in. The user can then save this filtered csv file directly to their computer.

The code will allow the user to search for words in the following columns:
- Input Author
- Input Institution
- Bibcode
- Abstract
- Panels

While there is a file already referenced within the code, if you choose to use a custom csv file, it **MUST** contain one of the columns listed above.

## What is required
### Imports

- pandas (1.5.3 or later)
- tkinter 
- tkinter.messagebox

### Files needed:
- preloaded csv file

Place this file within the same directory, as the path will be necessary in order for the code to function correctly.

## How to use it

The user can either use the csv file already referenced within the code or click on the `load csv file` button. Once a csv file to search has been established, the user can input
text into the search bar. Afterwards, they are to select which column to search (remember: the file must contain the column name that the user wants to search in). Finally, select 
the `search` button. Columns that contain the input will be displayed in a dataframe within the tkinter window. The user can then choose to save this filtered dataframe by selecting
`Save CSV` button, which will then prompt a popup window to appear, asking the user to name the csv file and selecting a destination on where it can be saved. 

