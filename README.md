# Spotify Music Analytics Dashboard

A Tableau dashboard built to analyze the Spotify Tracks dataset, exploring artist performance, genre trends, popularity patterns, and song characteristics.

## Overview

This project uses Tableau to visualize and derive insights from a detailed Spotify tracks dataset containing information on song popularity, danceability, energy, genre, duration, and more.

## Dataset

- **Source file:** `spotify-tracks-dataset-detailed.csv`
- **Total records:** 113,999 songs
- **Unique artists:** 31,437
- **Key fields:** Track Name, Artists, Album Name, Track Genre, Popularity, Danceability, Energy, Duration (ms), Explicit, Acousticness, Liveness, Loudness, Speechiness, Tempo, and more

## Dashboard Contents

The workbook includes 13 worksheets combined into a single dashboard:

| Sheet | Description |
|---|---|
| Total Songs | Total count of songs in the dataset |
| Total Artists | Distinct count of artists |
| Average Popularity | Average popularity score across all songs |
| Average Danceability | Average danceability score across all songs |
| Top 10 Artists | Top 10 artists by number of songs |
| Top 10 Songs | Top 10 songs by average popularity |
| Genre Distribution | Distribution of songs across top genres |
| Popularity by Genre | Average popularity broken down by genre |
| Energy vs Danceability | Scatter plot comparing energy and danceability across genres |
| Popularity Distribution | Histogram showing how popularity scores are distributed |
| Explicit vs Non-Explicit | Comparison of explicit vs non-explicit tracks |
| Song Duration Analysis | Histogram of song durations (binned by minutes) |
| Top 10 Artists by Popularity | Top 10 artists ranked by average popularity |

## Key Insights

- Most songs fall between 2–4 minutes in duration.
- Popularity scores are approximately normally distributed, centered around 30–40.
- A small fraction of tracks (under 10%) are marked explicit.
- Genre popularity varies significantly, with genres like *pop-film* and *k-pop* scoring highest on average popularity.

## How to View

1. Download `Spotify.twb` from this repository.
2. Download the dataset `spotify-tracks-dataset-detailed.csv` (see Dataset section). Tableau may ask you to locate the file. Select it.
3. Open `Spotify.twb` using [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/).
4. Navigate to the **Spotify Music Analytics Dashboard** tab to view the combined dashboard.
