# Time_Savers
Useful blocks of code for students in the Loew lab (And myself!)

Description of Contents:

**Keyword_PDF_Verification** Contains a chunk of code to cycle through a series of pdfs and identify if key word(s) is/are present. This is intended to serve as a quick sanity check for literature reviews. 

**Reading_And_Exporting_CSVs** Contains some simple code chunks to read in and export CSV files.

**NpArray_and_Image_Manipulation** Contains some simple code to modify arrays and images (Change all the values to be > or < than a value, merge some values, etc.).

**Dataframe_Manipulation** Contains some simple code to update column values in a dataframe.

**Directory_Processing** Contains some simple code to cycle through a directory and do things, or to cycle through multiple values and list in tandem. The random example I have in here is for image segmentation masks.

**Text_Column_Manipulation** Contains my favorite little chunk of code - takes a column and breaks it based on a delimiter to create new columns. Useful for very messy data. Can be used to extract specific strings from a large chunk of text (IE "Here's some text Blahblahblah = I need this value," would be split by setting delimiter to "Blahblahblah = " then adding another split at the end for a "," to chunk off the remainder of the text.

**DICOM_Manipulation** Some simple code to load in DICOM images, convert to a pixel array, make a histogram, and convert to PNG.

**Video_Manipulation** Simple code to read in a video file and process it frame by frame.
