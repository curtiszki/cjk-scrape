# Chinese Character Scraping Tool

This is a python CLI tool to be used to retrieve all Chinese characters from a webpage via data scraping and the BeautifulSoup4 module. 
Then using the returned and filtered text, alongside the definitions are outputted into a .csv file.
The corresponding character definitions are provided using CC-CEDICT.

There are several requisite modules that need to be installed before you can run this application:
  - httplib2 - A HTTP Client library.
  - BeautifulSoup4 - A library primarily centered around efficiently pulling data from HTML/XML files.

## How to Use

Please ensure you have the requisite files installed (specified above). From the command line you can run the app using the following format:

'''
  $ python main.py website_url [output_dir]
'''
