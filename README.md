# Automatic_detection_of_Dark_patterns
A repository for work on automatic detection of different dark pattern types
Most of the problems you may encounter come from the scraper. If you are not intrested in the scraper, it is advised to just use the notebook and change the data it uses to fit your data. Agian it will be noted the scraper is from here: https://github.com/gdprccrawler/ccrawler
There is only done some small changes with regard to language and what is looked for in settings page. Therefore I advice any questions regarding the scraper to be sent to them.

# Prerquisites
Python 3.9+
//
MongoDB
\\
Poetry package manager for python.
Chrome installed and added to path.
ChromeDriver for Selenium installed and added to path, see: https://chromedriver.chromium.org/getting-started 
Jupyter Notebook

# Before run
Set up your MongoDB database and change the connections lines to fit your MongoDB collection
install all dependencies by running poetry install in the project
Then start poetry shell
then run with python main.py

# The classifier / analyzer
Set the connection in the notebook to connect to the MongoDB collection you used for the scraper
Install the needed library
You can now run the notebook, the file cookienotices.csv is the result from the investigation and can be ignored if not of intrest.
