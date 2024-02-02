# Hacker News Reader
- - -
*Unofficial UI for news.ycombinator.com*

This project was started out of frustration from lack of proper mobile layout and other minor annoyances.
The main goal of the project is to give a more user friendly interface that should work on every platform. Mobile support is especially important. 

**Current features:** 
* Frontpage submissions with simple sorting and filtering options (new, top, Ask HN, etc.).
* Comprehensive support for viewing comments, including polls and Ask HN posts.
* Functions as an API in Reddit style (append .json to any page for JSON output).
* Responsive layout facilitated by Bootstrap with custom tweaks.
* Comment enhancements, such as highlighting the original poster's name in a different color and comment collapsing. More enhancements are in the pipeline.
* Written in Python 2.7 and utilizes the following technologies:
Django
* Bootstrap as a CSS framework
* BeautifulSoup for HTML parsing
* Sass/Compass for CSS
jQuery
* PostgreSQL
* Various timezone/time packages
* Check requirements.txt for a complete list of Python packages

The project currently scrapes news.ycombinator.com directly, leading to some issues:

Difficulty scraping older comments frequently.
The "official" HNSearch API doesn't support fetching by ID, rendering it unsuitable for this project. Most other unofficial APIs also have formatting issues.
Semi-random IP banning during scraping.
The AppFog free tier, on which the project is hosted, only provides one IP. While there is a working port for Google App Engine, it faces challenges scraping Hacker News.
The project's current state involves scraping Hacker News directly, which has limitations. Future updates may include:

Exploring alternative methods for obtaining older comments.
Investigating solutions to address semi-random IP banning.
Potentially migrating to a different hosting platform for improved flexibility.
Feel free to contribute to the project and stay tuned for updates!

Visit the project on GitHub
