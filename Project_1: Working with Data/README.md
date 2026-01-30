# Project 1: Working with Data
This project is an introduction of working with data using python.

## Overview

This project works with entertainment industry data to study movies and TV shows, with a focus on the **"Golden Age" of television** (from 1999 onward, starting with *The Sopranos*).

**Goal:** Test whether highly-rated TV shows from the Golden Age also receive the most votes on IMDb—i.e., whether the number of votes a title gets is related to its rating.

## Data

**File:** `movies_and_shows.csv`

Columns (after cleaning in the notebook):

| Column        | Description                          |
|---------------|--------------------------------------|
| name          | Name of the actor or actress         |
| character     | Character they played                |
| role          | Role type (e.g., ACTOR)              |
| title         | Title of the movie or show           |
| type          | MOVIE or SHOW                        |
| release_year  | Year of release                      |
| genre         | Genres of the title                  |
| imdb_score    | IMDb rating                          |
| imdb_votes    | Number of IMDb votes                 |

## What’s in the notebook

- **Data overview** — `head()`, `shape`, `info()`
- **Data cleaning** — Rename columns, drop duplicates, handle missing values (fill title with `'unknown'`, drop rows missing `imdb_score` / `imdb_votes`)
- **Basic exploration** — Highly rated titles (≥9.0), unique top-rated movies (function), top movies by decade (function), list actors for a title (function), categorize by IMDb score (function)

The notebook sets up the data and exploration; testing the Golden Age / votes assumption can be done as a next step.

## Contents

- **`movies_and_shows.ipynb`** — Main notebook (cleaning + exploration above).

## Tools

- Python, pandas