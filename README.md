# PDF Extraction

This is more of a practical task that has some solutions and is worth a weekend project though I have put it off and it has become a "back burner" project. 

So I decided to at least put it up as a reference for anyone who has put their hands on raw pdf code in python.

### The Goal: 
We are extracting tabular data from PDF's. This is of interest to any non-tech person who wants to collect infromation from sources that are not databases. I started this because I know a small business who wants to transfer all tables from catalogues in PDF format to a database for the purpose of consolidating the selection of different distributors for the supply to interested buyers. In this case, the distributors are medical suppliers and the buyers are hospitals. 

So I knew that if I could get at the raw code in the PDFs, I could clean up the text and get it into an acceptable state to put it into a dataframe or database or spreadsheet. 

I first looked for some libraries that might help me, and found:
- PyPDF2
- fitz
- tabula-py

I will update this exploration as I learn how to use these different libraries based on the results I get and the results I can work with the best.

