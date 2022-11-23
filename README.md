## Charity blockchain app

## Author
Dennis Kimani
John Kamau
  
# Description  
a blockchain application for a charitable organization to create trust with donors
##  Live Link  
not yet deployed

 
## User Story  
* Connect nodes
* Add transactions
* Get the chain
* Mine a block
* Verify block validity
* Replace chain

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 bash 
https://github.com/dennis027/blockchain-assignment.git

##### Navigate into the folder and install requirements  
 bash 
cd blockchain-assignment pip install -r requirements.txt 

##### Install and activate Virtual  
 bash 
- python3 -m venv virtual - source virtual/bin/activate  
  
##### Install Dependencies  
 bash 
 pip install -r requirements.txt 
  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 bash 
python manage.py makemigrations instagram
  
 Now Migrate  
 bash 
 python manage.py migrate 

##### Run the application  
 bash 
 python manage.py runserver 
 
##### Testing the application  
 bash 
 python manage.py test 

Open the application on your browser `127.0.0.1:8000`.  
  

 
## Technology used  
  
* [Python3.6](https://www.python.org/)  
* [Django 4.0.5](https://docs.djangoproject.com/en/2.2/)  
 
  
  
## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
## Contact Information   
If you have any question or contributions, please email me at [machariad196@gmail.com] [njugunajk33@gmail.com]  
  
## License 
This project is under the  [MIT](LICENSE) license