

</p>
<h1 align = 'center'>News Aggregator</h1>
<br>

<br>

[![](https://img.shields.io/badge/Made_with-Python3-blue?style=for-the-badge&logo=python)](https://www.python.org "Python3")[![](https://img.shields.io/badge/Made_with-Django-blue?style=for-the-badge&logo=django)](https://www.djangoproject.com/ "Django")

</p>
# 🗞️ News Aggregator

A Django-powered news aggregator that scrapes and displays articles from [The Onion](https://www.theonion.com). This project combines web scraping with dynamic web presentation to deliver categorized satire news articles in a clean and accessible format.

---

## 🔍 Features

- Scrapes the latest articles using `BeautifulSoup` and `requests`
- Stores article titles, images, and links in a SQLite database
- Displays categorized news (Latest, Entertainment, Sports, Politics, Opinion, Breaking News)
- Responsive frontend with Bootstrap styling
- Interactive UI with a "Load News" button to fetch data seamlessly

---

## 🖼️ Screenshots

| Latest | Entertainment | Contact Us | Dark Theme |
|--------|---------------|------------|------------|
| ![Latest](Picture1.png) | ![Entertainment](Picture2.png) | ![Contact](Picture3.png) | ![Dark Theme](Picture4.png) |

---

## 🚀 How to Use

### 📦 Installation

Make sure you have Python 3 installed. Then run:

```bash
pip install bs4
pip install requests
pip install django-social-share


## Description

News aggregator is a Django project to scrape a news website using Beautiful soup and request module and hence combination of web crawlers and web applications.
Both of these technologies have their implementation in Python.

## Features

Our news aggregator works in 3 steps:<br>
1.It scrapes the news website for the articles.In this Django project, we are scraping a website 'www.theonion.com'<br>
(We have scraped news articles from 'latest' section of 'www.theonion.com' for demonstration)<br>
2.Then it stores the article’s images, links, and title.<br>
3.The stored objects in the database are served to the client. The client gets information in a nice template by clicking the 'Load news' button and select the different options available to you.The options are: Latest,Entertainment,Sports,Politics,Opinion,Breaking-News<br>

        ----------------------------------------------------------------------------------------
### Screenshots ###
## Latest

![](https://github.com/kmrabhayak/News-Aggregator/blob/main/Picture1.png)
## Entertainment
![](https://github.com/kmrabhayak/News-Aggregator/blob/main/Picture2.png)

## Contact Us
![](https://github.com/kmrabhayak/News-Aggregator/blob/main/Picture3.png)

## Dark Theme
![](https://github.com/kmrabhayak/News-Aggregator/blob/main/Picture4.png)


## How To Use

#### Software Requirements

Python3

#### Installation

Install the dependencies by running:
```html  
    pip install bs4
    pip install requests
    pip install django-social-share
```

#### Run using Command Prompt

Navigate to the News-Aggregator folder which has manage.py file then run the following command on cmd

```html
python manage.py runserver
```

### Tech stack

`Backend` : Python3,Beautiful soup <br>
`Framework` : Django <br>
`Database` : Sqlite3 <br>
`Frontend` : Html,CSS,Bootstrap <br>
