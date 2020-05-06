# Anime Search
**Anime Search** is a Flask web scraping application allowing you to find out on which legal streaming platform you can watch the animation series you are looking for.

The data is retrieved from the [Nautiljon] website (https://www.nautiljon.com/).

The link to the site [Anime Search](https://emmanuel-cse17019.herokuapp.com/).


## The application has 3 pages:
- The * home * page for searching for a series.
- The * results display * page which shows the results corresponding to our search.
- The page of * details * of a series, where you can see information about the series.

The application also allows you to view the details of a series more quickly at the expense of image quality by activating the * "Speed Mode" * button on the search page.

## Technologies utilisées
- Le micro-framework Flask
- Le langage Python 3.8
- L'installeur de paquets pip 20.1
- Bibliothèque Python :
	- Beautiful Soup 4 (Webscraping)
	- lxml (Parser)
	- requests (requête HTTP)
	- gunicorn (déploiement en production)
## Application deployment
The application has been deployed on [Heroku] (https://heroku.com) which allows free deployment of web applications (NodeJS, Python, Java, Go, PHP, ...)
