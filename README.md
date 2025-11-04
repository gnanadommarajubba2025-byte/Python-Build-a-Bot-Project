# Python-Build-a-Bot-Project

Movie Recommender Bot

This is a simple Python-based command-line application that recommends a movie based on the user's preferred genre and language. The program uses a predefined dataset of popular international movies and randomly selects one that matches the user's input criteria.

The script begins by displaying a list of available genres and languages extracted from the movie dataset. The user is prompted to choose their preferred genre and language. Input validation ensures that the user selects only from the available options. Once valid inputs are provided, the program filters the dataset to find movies that match both the chosen genre and language. If there are any matches, one movie is randomly selected and displayed as the recommendation. If there are no matches, the program informs the user that no suitable movies were found.

The project uses basic Python functionality, including lists, dictionaries, loops, conditionals, and user input handling. The random module is used to select a recommendation from the filtered list of movies. The dataset includes a variety of films across multiple genres such as Drama, Crime, Action, Sci-Fi, Romance, and more, and supports several languages including English, Hindi, Japanese, French, Italian, Korean, and others.

To run the program, clone the repository and ensure you have Python 3 installed on your system. Navigate to the project directory in your terminal and execute the script using the command:
python movie_recommender.py
The program will then guide you through selecting your preferred genre and language and display a movie recommendation based on your choices.

Welcome to the Movie Recommender Bot!
Available Genres: Action, Animation, Comedy, Crime, Drama, Fantasy, Romance, Sci-Fi, Thriller, War, Western
Please enter your preferred movie genre: Drama
Available Languages: English, French, German, Hindi, Italian, Japanese, Korean, Persian, Portuguese, Spanish
Please enter your preferred movie language: English

Based on your preferences, we recommend: Forrest Gump

You can easily customize this project by adding more movies to the dataset, expanding the list of genres and languages, or modifying the recommendation logic to include multiple suggestions or weighted selections. Future improvements could include integrating an external movie API for dynamic data, developing a graphical user interface using Tkinter or Streamlit, or adding features like user ratings and saving preferences.

Author: Gnana Pushyami Dommaraju
