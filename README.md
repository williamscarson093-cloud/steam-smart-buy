# Steam Smart Buy

My app helps gamers on a budget decide which Steam game to buy by comparing games based on their budget, favorite genre, current deals, and reviews.

> A course project for **MIST 4600: Computer Programming in Business** at the University of Georgia's Terry College of Business (Fall 2026).

## Problem

There are so many games on Steam, and it can be very hard to decide which ones are worth buying. My app helps gamers find games that they can afford with good reviews and deals so they don't waste their money.

## What it does

My app answers three questions:

1. **Genre and Budget:** Which highly rated games match the gamer's favorite genre and budget?
2. **Deals:** Which games are on sale right now, and how close are they to their lowest price?
3. **Reviews:** Which games have at least 10,000 reviews so we know a lot of people have played and rated them?

## Data

The [Steam Games Dataset](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset) on Kaggle, collected in March 2025. The dataset is shared under the MIT License by its creator, artermiloff. This project uses `steam_games.csv`, which contains 1,000 of the most reviewed games.

## Built with

Python
pandas
Google Colab
CheapShark API (price information)
ipywidgets (interactive interface)
GitHub

## How to run it

1. Open steam_smart_buy.ipynb in Google Colab.
2. Make sure steam_games.csv is available in Google Drive.
3. Run all notebook cells in order.
4. Select a game genre from the dropdown menu.
5. Choose a max budget using the slider.
6. Click "Find My Games".
7. View the recommended games, prices, and estimated savings.

An internet connection is required to retrieve prices from CheapShark.

## Example output

Example search: Action games with a $20 budget.

Game

Dataset Price

Lowest Price

Estimated Savings

Katana ZERO

$14.99

$8.99

40%

Vampire Survivors

$4.99

$4.99

0%

Pizza Tower

$19.99

$19.99

0%

People Playground

$9.99

$9.99

0%
## AI Use Disclosure

Ai was used for general trouble shooting and help with integrating Cheapshark Api, it also helped me understand errors and helped fix them, But all code was mine.
## Author

Carson Williams
