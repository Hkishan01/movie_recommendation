Movie Recommendation System

This project is a movie recommendation system built using Streamlit. It recommends movies based on user selection and displays their posters using data from the TMDB database.
Features

    Movie Recommendations: Get a list of five recommended movies based on the selected movie.
    Poster Display: Fetch and display movie posters from the TMDB database.
    Interactive UI: Select a movie and view recommendations with a simple button click.

Setup

    Install Dependencies: Ensure you have Python installed, then run:

    bash

    pip install streamlit pandas requests

    API Key: Replace the placeholder in the code with your TMDB API key.

    Data Files: Ensure you have movies.pkl and similarity.pkl in the project directory.

Usage

    Run the Application:

    bash

    streamlit run app.py

    Select a Movie: Choose a movie from the dropdown menu.

    Get Recommendations: Click the 'Recommend' button to view movie recommendations and posters.

Code Explanation

    fetch Function: Retrieves movie poster URLs using TMDB API.
    recommend Function: Computes similar movies based on precomputed similarity data.
    Streamlit Interface: Creates an interactive web app with options to select movies and view recommendations.

Customization

    Styling: Modify CSS in the st.markdown section to change the app's appearance.
    Data: Update movies.pkl and similarity.pkl for different datasets.

Acknowledgements

    TMDB: Movie data and posters are sourced from the TMDB database.

License

This project is open-source and available under the MIT License.
