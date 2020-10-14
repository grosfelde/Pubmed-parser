# Pubmed-parser
uses async lib to quickly parse in https://pubmed.ncbi.nlm.nih.gov/

== Description ==

The .py file allows the required search query to be entered into a window, after which the script searches in https://pubmed.ncbi.nlm.nih.gov/ for information on a given search query and saves it as an Excel table with columns "name", "pmid", "doi", "year" and "url". 

== Installation ==

Into Python 3.7

Open Command prompt-

Press Windows key + R, type cmd and press Enter.

Or you can simply type cmd in windows search bar and open Command Prompt.

Go to the location where you have saved pubmed_parser.py file (using file explorer)

Click on the address bar, select the whole address and copy it.

Type the following command into the cmd and press Enter-

cd “paste the location inside these double quotes”

Press Enter.

This is how you enter into  pubmed_parser.py file location through Command Prompt.

If you have your file in some other drive, say drive A, then simply type a: and press Enter. Then follow the same steps as above.

Type the following command into the cmd to run your python program and press Enter-

python  pubmed_parser.py 

Press Enter.

Enter the required search term in the window

Press Enter.

The search result will be saved to the directory of your choice as an Excel table with columns "name", "pmid", "doi", "year" and "url"
