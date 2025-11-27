Music Playlist Analyzer

A beginner-friendly Data Science with Python project that analyzes a custom music playlist using a CSV dataset.
This project demonstrates skills in data loading, data analysis, visualization, and insights generation using Python.

Project Files
*music_playlist.csv* – Dataset containing 10–12 songs
playlist_analyzer.py / .ipynb* – Python script or Jupyter Notebook
*Charts* (auto-generated) – Duration chart, genre charts

Features

The project performs the following tasks:

1. Load the dataset

Reads a CSV file containing:

* Song Name
* Artist
* Duration (seconds)
* Genre
* Release Year

2. Calculate average song duration

Uses Pandas to compute the mean duration of all songs.

3. Identify the most common genre

Finds the most frequently occurring genre using `mode()`.

4. Visualize duration per song

Creates a *bar chart* showing how long each track is.

5. Visualize genre distribution

Generates:

*Bar chart* for genre counts
*Pie chart* showing percentage distribution

6. Provide listening insights

Three observations are made based on the dataset, such as:

Preferred genre
Release year pattern
Typical song length

Technologies Used

*Python*
*Pandas*
*Matplotlib*
*Jupyter Notebook*

How to Run the Project

Step 1: Install dependencies

```bash
pip install pandas matplotlib
```

Step 2: Place your CSV file

Ensure `music_playlist.csv` is in the same folder as your script.

Step 3: Run the Python file

```bash
python playlist_analyzer.pynb
```
Sample Output

Average song duration
Most common genre
Bar chart: Duration per song
Bar chart: Genre distribution
Pie chart: Genre distribution
3 insights on listening pattern

Insights Generated

Preference for Pop-style music
Mostly modern music between 2017–2021
Average duration around 3–4 minutes

Future Improvements

Add Spotify API integration
Add audio features (tempo, energy, loudness)
Build a recommendation system
