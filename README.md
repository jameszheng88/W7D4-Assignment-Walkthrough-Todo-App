## W7D4-Assignment-Walkthrough-Todo-App

### Overview
This project is a simple app that creates a to do list. You can add, delete, change, cross out, and make priority tasks.

### Running the project
You will need to install Flask and flask_sqlalchemy. Documentations can be found below  

[Flask](https://flask.palletsprojects.com/en/3.0.x/)  
[Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/3.1.x/)  

You will also need to create a virtual environment:
- Windows  
  \> mkdir myproject  
  \> cd myproject  
  \> py -3 -m venv .venv  

- Mac  
  $ mkdir myproject  
  $ cd myproject  
  $ python3 -m venv .venv  

To activate the virtual environment:
- Windows  
  \> .venv\Scripts\activate  

- Mac/Linux  
  $ . .venv/bin/activate  
<br>

### Challenges and lessons
It was difficult to update the app with more functions as we weren't taught on how to connect Flask with Flask_SQLAlchemy and the syntax used in the HTML file.  
<br>
My first idea was to do a strikethrough where the item can be crossed out. I used JavaScript with the onClick function but it only applied the strikethrough on the first task. I looked at the code again and realized I can follow each route and change a few of the code snippets to have the app do the action I want it to do. After consulting with chatGPT, I was able to implement the function. After the first function was done, the second function, which was to make a task priority, took less time. 
