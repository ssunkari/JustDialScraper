# Justdial-Scrapper

JustDial Scrapper to scrap all the requested data which includes their name, address, email address and phone number.
Place the url of the searched page in the input txt file under the Data folder in the format "https://www.justdial.com/Dehradun/Schools/page-", and then run the file main.py.
Data will be saved in csv file in the data folder.

## Runtime Requirements

### Python

Install [python](https://www.python.org/downloads/) latest version for windows

### How to run the program

- Browse to Justdial folder in CommandPrompt C:\JustdialSrc\Justdial
- Run command `python -m pip install requests`
- Run command `python -m pip install selenium`
- Run command `python -m pip install bs4`
- Run command `python -m pip install lxml`
- Now Run Command `python main.py`

### How long does it take to run

- Depends on the number of pages in the search results usually about 10 min for large queries.
- The console(cmd prompt) should exit gracefully when the job completes.
- You may notice headless browser mozilla firefox opens and automatically browse the site, do not close as this will automatically cleanup at the end.

### How to get the output

- The output of the scrape results are stored in .csv format in Data folder relative to the project named output.csv
