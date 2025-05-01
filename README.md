# Competition in the 5 major European football leagues

## Introduction
This project is split into 2 parts. Part 1 investigates the competitiveness of each of the 5 major European football leagues respective titles by utilising a competitiveness index. Part 2 identifies changes in competition over time using HHI and graphical analysis

## Repository overview

├── README\
├── data.csv\
├── project.ipynb

## Running instructions

### Running from Jupyter notebook

If you run the code in Jupyter note book it's only necessary to run the first cell and the code from when the blog begins, graphs rely on calculations from previous cells so it's necessary to run the cells in order. 


### Running from the Command Line

Plotly graphs will only appear when exported to a **web-based or GUI environment** such as HTML.

Use the following command to execute the notebook and export it as an HTML file:

```bash
jupyter nbconvert --to html --execute project.ipynb
```

Then you can open the HTML file in your browser using one of these commands, depending on your operating system:
```
open my_notebook.html      # macOS
```
```
xdg-open my_notebook.html  # Linux
```
```
start my_notebook.html     # Windows
```

### Required Libraries
This code works as intended with the following libraries and versions:

> Python 3.11.4\
> Pandas 1.5.3\
> BeautifulSoup from bs4 4.12.2\
> requests 2.29.0\
> plotly 5.9.0\
> stats from scipy 1.10.1

## More resources
The Athletic study mentioned in the blog is located here:\
https://onefootball.com/fr/news/ligue-1-ranked-as-most-competitive-league-in-europe-39421849

Another article on the topic:\
https://www.ticketgum.com/blog/the-most-competitive-of-the-top-5-european-leagues-in-the-last-decade

An article on the financial difficulties within La Ligua discussed in the blog:\
https://www.nytimes.com/athletic/5482052/2024/05/16/barcelona-financial-problems-la-liga/

