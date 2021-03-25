# FromBibTexToELEDIA
Python script to convert BibTex citations in ELEDIA format for SOA projects

## Usage
This algorithm is mainly targeted for IEEE papers. 
### Steps
1. Bulk download the papers from IEEE. Remember to download in bulk so that the pdf name is the same as the paper's title. 
2. Export the citations in BibTex format, selecting Citation & Abstract in the menù. Put all the citations in a txt file.
3. In the folder containing the script create a folder named "papers", then put inside it the pdfs you have downloaded.
4. In the folder containing the script put the txt file you created with the citations.
5. Open cmd prompt, navigate to the folder containing the script and run the script in this way                                                                         
   `python fromBibtexToELEDIAFormat.py citations.txt output.txt`

Where *citations.txt* is the file containing the unformatted citations you previously downloaded and *output.txt* is the name of the file where the formatted citations will be stored.

Enjoy.





Created with :purple_heart: by (Uni)Sex
