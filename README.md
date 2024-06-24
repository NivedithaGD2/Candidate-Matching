# RESUME-RANKER
Resume Ranker (analyzer) is a web application designed to rank resumes based on their relevance to a given job description. The application uses TF-IDF vectorization and cosine similarity to perform the ranking. The project is built with Flask as the backend framework and uses HTML and CSS for the frontend.
## Requirements
To run this project, you will need to install the following dependencies:
- Flask
- numpy
- scikit-learn
### You can install the required packages using the following command:
```bash
pip install -r requirements.txt
```
## Web
<img width="900" alt="Screenshot 2024-05-22 at 10 17 18 PM" src="https://github.com/Manusd04/RESUME-RANKER-/assets/92382837/40e46081-06c6-40b8-bf9b-eb7a370f651f">
<img width="900" alt="Screenshot 2024-05-22 at 10 19 34 PM" src="https://github.com/Manusd04/RESUME-RANKER-/assets/92382837/2a721514-3354-4fb0-a972-96aeb16328db">


## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/resume-ranker.git
    cd resume-ranker
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Flask application:**

    ```bash
    flask run
    ```

5. **Open your web browser and navigate to:**

    ```
    http://127.0.0.1:5000
    ```

## Project Structure

```
resume-ranker/
├── static/
│   ├── css/
│   │   └── styles.css
├── templates/
│   ├── index.html
│   ├── result.html
├── app.py
├── requirements.txt
└── README.md
```

## Usage

1. Upload the job description and resumes through the web interface.
2. Click on the "Rank Resumes" button to compute the similarity scores.
3. View the ranked list of resumes based on their relevance to the job description.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, please contact [your email address].
