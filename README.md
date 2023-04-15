# TMDB Movie/Show Poster Downloader

This is a Python script that utilizes the TMDb API to download the posters of movies and TV shows based on a list of titles provided in an Excel file. It was created with the help of ChatGPT-3.

## Prerequisites
* Python 3.x
* requests module
* openpyxl module

## Installation
You can install the required modules by running the following command in your terminal:

```pip install requests openpyxl ```

## Usage
1. Obtain an API key from TMDb.
2. Create an Excel file with a list of movie/show titles in the third column and their type (MOVIE/SHOW) in the fourth column.
3. Save the Excel file as "---.xlsx" in the same directory as the script.
4. Set the API key in the `api_key` variable.
5. Run the script using the following command:

```python Movie-Show_Poster_Downloader.py```

## Notes
* The downloaded posters will be saved in the same directory as the script.
* The script searches for posters based on the exact title of the movie/show, so make sure that the titles in the Excel file match the titles in TMDb.
* If a poster is not found for a movie/show, the script will print a message indicating so.
