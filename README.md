# Top Movie Rating Site

This web application allows users to create and manage a list of their top 10 favorite movies. It enables users to search for movies using the Movie Database (TMDb) API, rate and review them, and organize them according to their personal preferences.

## Features

- **Add Movies**: Search for movies by title and add them to your top 10 list using the TMDb API.
- **Rate and Review**: Provide a rating and write a review for each movie.
- **Organize**: Rank your movies and reorder them as you like.
- **Responsive Design**: The site is fully responsive and works on all devices.

## Technologies Used

- **[Flask](https://flask.palletsprojects.com/)**: A lightweight WSGI web application framework in Python.
- **[SQLAlchemy](https://www.sqlalchemy.org/)**: SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **[WTForms](https://wtforms.readthedocs.io/)**: A flexible forms validation and rendering library for Python.
- **[Bootstrap 5](https://getbootstrap.com/)**: A front-end component library used for styling.
- **[TMDb API](https://www.themoviedb.org/documentation/api)**: External API for fetching movie data.
- **HTML/CSS**: Custom templates and styling for the site.
- **SQLite**: Lightweight database used for storing movie information.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Fariha223/top_movie_rating.git
    cd top_movie_rating
    ```

2. Set up a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the database:
    ```bash
    flask db upgrade
    ```

5. Set your TMDb API key:
    - Replace the `API_KEY` variable in `app.py` with your TMDb API key.

6. Run the application:
    ```bash
    flask run
    ```

7. Open your browser and navigate to:
    ```
    http://127.0.0.1:5000/
    ```

## Usage

- **Home Page**: View your top 10 movies with their ratings and reviews.
- **Add Movie**: Search and add movies to your list.
- **Edit Movie**: Update the rating and review of a movie.
- **Delete Movie**: Remove a movie from your list.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any changes.

## Contact

For any inquiries or feedback, feel free to reach out to me via [GitHub](https://github.com/Fariha223).
