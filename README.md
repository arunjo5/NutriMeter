# NutriMeter
NutriMeter is a smart calorie tracking web application for anyone, from athletes to casual users. 
Type in your food and quantity (ex. 16oz sprite) and the app will tell you the nutrition facts along with what you have to do to burn those calories.
Warnings will be given to the user if the food item has a high amount of sodium or sugar. At the bottom, there is a pie chart with the percentages of each nutrient. 

Installation instructions for MacOS: 

Clone the github: `git clone https://github.com/arunjo5/NutriMeter.git`

Set up the virtual environment:  ` python -m venv ./venv` then `source venv/bin/activate`

Install requirements:  `pip install -r requirements.txt`

Apply migrations: `python manage.py migrations`

Run the app:   `python manage.py runserver`



