# Market analyse with book scraper

This code allow to extract images and information from a website. From there, but not developped yet, we can analyse the price evolution of a book for sample

### Prerequisites

This project is developped in Python, if you did not get a python environnement you can download it from : https://www.python.org/downloads/
You can also download IDE (Integrated Development Environment) like sypder, pycharm, Jupyter Notebook... It usually provides features such as build automation, code linting, testing and debugging.<br />
On my side, I developped this project with spyder.


### Installing

The first step is to retreive the files from github. You can install Git on your computer with the following link : https://git-scm.com/downloads
Move to the folder where you wish to saved this project using the command cd C:/Users/XXXX/XXXX/XXXX<br />
We will then clone the file located in the Github platform using the following command in Git prompt : <br />
>git init<br />
>git remote add Name_given https://github.com/amelie2107/openclassroom.git <br />
>git clone https://github.com/amelie2107/openclassroom.git <br />

The second step is to work on the same environnement, I mean with the same package versions to be sure the project will be run in the same condition as me. 
For that, you can run the "requirement.txt" file using the following lines in your command prompt :<br />
>Python -m venv env #to create the new virtual environnement<br />
>env\\Scripts\\Activate.ps1 #to activate the environnement<br />
>pip install -r requirements.txt #to download the package in the required version<br />


### Running the tests

You can then lauch the python file using the following line :<br />
>python book_scraper.py<br />

The programm is running.<br />
Many lines must appear :<br />
>"This program will extract data from the following website : http://books.toscrape.com/"<br />
>"STARTING EXTRACTION TRANSFORMATION LOADING"<br />
>"we scraped X page(s) of the category : XXXXX"<br />
>...<br />

The programm is scraping all pages of the following website : http://books.toscrape.com.
The scraped information are saved in the root of the project folder.
From those information we can realised a market analyse.


### Deployment

To improve this programm, it should be nice to request the webside automatically and regulary in the aim to see the price variation.
A graphic should be the better way to analyse the variation.
In addition, an alert could be sent if the current price is the lowest/highest price never seen.

### Author

* **Amélie Noury** 

### Acknowledgments

* This project has been requested by the openclassroom training

