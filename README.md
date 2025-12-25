# Spotify Music Trends Analysis (1990–2024)
1️⃣ Project Overview

This project analyzes music trends on Spotify using data spanning from 1990 to 2024.
The objective is to understand how music production, genres, emotional impressions, and popularity evolved over time, and how external events (such as COVID-19) may have influenced these trends.

The analysis focuses on descriptive and comparative insights, rather than prediction, to provide a clear view of long-term musical patterns.

2️⃣ Data Cleaning & Preparation (Brief)

The dataset contained significant quality issues, especially in the Genre column.

Key Problems:

Genre values mixed with:

Years (e.g., 80s, 2018 single)

Ratings (4 stars, 7 of 10)

BPM values (118 bpm)

Names of people, movies, playlists, or free text

Over 1000+ distinct genre values, many of them invalid or noisy

Cleaning Approach:

Removed numeric-only and year-like genre values

Standardized valid genres into known musical categories

Mapped non-musical or unclear values to Unknown

Kept the genre dimension flat (no multi-column splitting) to support dashboard clarity

Used average popularity instead of max to reduce outlier bias

3️⃣ Dashboard Overview & Visual Explanation
🎭 Emotional Distribution (Donut Chart)

Shows the overall emotional composition of songs.

Insight: Happiness and sadness dominate, reflecting music’s role in expressing core human emotions.

⭐ Top 10 Most Popular Artists

Ranks artists based on average popularity.

Insight: Popularity is concentrated among a small group of artists rather than evenly distributed.

📈 Songs & Artists Over Time (Timeline)

Displays the growth of music production and artist participation across years.

Insight:

Strong growth until 2018

A noticeable decline starting in 2020, aligned with the COVID-19 period

Gradual recovery after 2021

🎶 Genre Focus

Only the top 6 genres are shown:

Chosen to reduce noise from inconsistent tagging

Represent the most analytically meaningful and frequent genres

Enable clearer comparison across time
