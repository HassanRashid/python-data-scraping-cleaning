# Scraping and cleaning a Disney movies database in Python

## Tasks

**Data scraping:**

- Get Wikipedia movie info box (store in Python dictionary)
- Get info box for all movies

**Data cleaning:**

In order to run analysis on the data, it must be cleaned and without any errors:

1. Remove references "[1]" from data
2. Split up remaining strings of names into lists
3. Investigate "'NoneType' object has no attribute" errors for some movies
4. Running time: convert from string to integer
5. Convert dates to datetime objects

## Data

The data is scraped from the Wikipedia page: https://en.wikipedia.org/wiki/List_of_Walt_Disney_Pictures_films

## Libraries used

- Beautiful Soup (to scrape the data)
- Requests (to get the Wikipedia webpage)
- JSON (to parse, save, and load the movies list as a JSON file)
- Datetime (to convert string of dates to datetime objects)
- Pickle (to save and load list that includes datetime objects)

## Issues fixed:

1. Removed movies from the movies list that do not have a linked Wikipedia page
2. Fixed error due to table headers not being used in some table row elements
3. Fixed JSON file save error due to datetime object (used Pickle library)

## Data cleaning tasks performed:

1. Removed references "[1]", "[2]", etc. from the data
2. Split up remaining strings of names into lists (nested lists)
3. Investigated and fixed "'NoneType' object has no attribute" errors for some movies
4. Running time: converted string to integer
5. Release date: Converted dates to datetime objects
