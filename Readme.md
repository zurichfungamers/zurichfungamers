# Zurich Fun Gamers

This repository contains resources used by Zurich Fun Gamers.

## Games Table

The resources for the games table is located under `games-table`. It is split in two parts, the list of games stored as a JSON file and the HTML file for displaying the list.  
The file `Games-Table.local.html` uses the local games list, while `Games-Table.github.html` uses the games list from the `main` branch on Github.  
For local development and testing, use `Games-Table.local.html` (you will need to set up a development server to avoid CORS issues, or change the browser settings to allow access to the JSON file).  
The version used on the website is `Games-Table.github.html`, so the games displayed on the website will be in sync with the `main` branch.