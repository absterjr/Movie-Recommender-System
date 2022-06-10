# Movie-Recommender-System

This recommender system was made as a part of course curriculum of My University.

It contains a [Movie Recommender System made Using KNearest Neighbours](https://github.com/absterjr/Movie-Recommender-System/blob/main/movie-recommendation.ipynb).

The [API](https://github.com/absterjr/Movie-Recommender-System/blob/main/API/main.py) used was Fastapi and the FrontEnd was made using [HTML](https://github.com/absterjr/Movie-Recommender-System/blob/main/templates2/form2.html).
The front end made for this project is the most basic one.

The input is given to the api using the HTML form which is also the front end of the project.
After the input is given the main.py file runs and shows the output in the form of a table. 

If one directly uses the API file and not take input via the html form but directly edit it on the ip address then the output comes in the form of JSON. That was not User-Friendly so the output was changed using json2html library which gives the output in the form of a table.
