# MovieRecommendation
Movie Recommendations on the basis of 5 emotions using webscrapping lxml and beutifulsoup 
# 🎬 Emotion-Based Movie Recommendation System

This is a simple Python-based web scraper that recommends movies based on the user's emotion or genre preference. It fetches data from IMDb using BeautifulSoup and suggests relevant movies based on the selected emotion.

## 💡 Features

- Input an emotion or genre (e.g., **Drama**, **Action**, **Comedy**, **Horror**, or **Crime**)
- Automatically scrapes the IMDb website for top movies in the selected category
- Displays a list of movie titles (up to 14) from IMDb
- Uses `requests` for HTTP calls and `BeautifulSoup` for HTML parsing

## 🛠️ Technologies Used

- Python 3
- [requests](https://pypi.org/project/requests/)
- [BeautifulSoup (bs4)](https://pypi.org/project/beautifulsoup4/)
- Regular Expressions (`re`)

## 🚀 How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/movie-recommendation-system.git
    cd movie-recommendation-system
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the script:
    ```bash
    python movie_recommendation.py
    ```

4. Enter an emotion when prompted (choose from: `Drama`, `Action`, `Comedy`, `Horror`, `Crime`).

## 📦 Example Output

Enter the emotion: Action ok https://www.imdb.com/search/title/?title_type=feature&genres=action The Dark Knight Mad Max: Fury Road Inception Gladiator ...


## ⚠️ Note

- The script scrapes data directly from IMDb. Changes in IMDb's HTML structure may require updates to the scraping logic.
- This project is for educational purposes only and is not affiliated with IMDb.

## ✅ Valid Inputs

- Drama  
- Action  
- Comedy  
- Horror  
- Crime  

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to contribute or suggest improvements!
