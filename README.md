# Movie Recommender System
This is a content-based movie recommendation system. The system recommends movies similar to the movie user selects. 

## Getting Started

To get a local copy up and running follow these simple steps:

1. Clone the repository
   ```sh
   git clone https://github.com/chaitanya-24/Movie-Recommender-System.git
   ```
   
2. Install the required libraries
   ```sh
   pip install -r requirements.txt
   ```
   Run the movie-recommender-system.ipynb file so that it can generate two pickle files that is required in app.py

3. Replace YOUR_API_KEY in the main.py file with your API key(From [TMDB](https://www.themoviedb.org/)). 
   ```sh
   YOUR_API_KEY = 'ENTER YOUR API KEY HERE'
   ```
4. Run the app.py file
   ```sh
   streamlit run app.py
   ```
5. Open your browser and type http://localhost:8501/ in the address bar.

## Usage

The details of the movies (title, genre, poster, etc) are fetched using an API by TMDB, and using the IMDB id of the movie in the API. 

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Chaitanya Sawant - [@chaitanya-24](https://github.com/chaitanya-24)

Project Link: [https://github.com/chaitanya-24/Movie-Recommender-System](https://github.com/chaitanya-24/Movie-Recommender-System.git)

Please let me know if you need any further assistance.

## Video Demonstration
[streamlit-app-2023-11-17-14-11-23.webm](https://github.com/chaitanya-24/Movie-Recommender-System/assets/62403348/d55102e1-f7f1-477d-a19a-542e9b6bd3e8)
