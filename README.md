# Movie-Recommender-System
This project was made using python and HTML(FrontEnd).

The project contains 2 datasets namely movies.csv and rating.csv.
It has a recommender system made using python KNN notebook which contains how the recommender system was made.
The API contains a main.py file which has the api for the recommender system.
templates2 contains the front end of the project which was made using HTML.


### Instructions to Run
- Install all the libraries imported in main.py
- Open a terminal 
- Type uvicorn main:api --reload
- (If you get error saying "uvicorn is not recognized as the name of cmdlet...) Type python -m uvicorn main:api --reload
- In the terminal an IP address will come. Follow the link. 
- In the URL after address write "/recommendations" (as we defined it in our main.py file)
- Enter a movie name say "Bad Boys". Click Submit and it will show you the similar movies along with their similarity score.
