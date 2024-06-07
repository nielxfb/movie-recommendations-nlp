# Movie Recommendation App using NLP

Welcome to the Movie Recommendation App! This application uses Natural Language Processing (NLP) techniques to provide movie recommendations based on user reviews. The app leverages the following technologies:

- **Naive Bayes Classifier** for sentiment analysis
- **TF-IDF Vectorizer** to generate movie recommendations based on the inputted review
- **SpaCy** for Named Entity Recognition (NER)

## Features

- Analyze the sentiment of movie reviews
- Recommend movies based on the review content
- Identify named entities in the reviews

## Installation

Follow these steps to set up the project on your local machine.

### Prerequisites

Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).

### Installing Dependencies

1. **Upgrade pip, setuptools, and wheel**

    ```sh
    pip install -U pip setuptools wheel
    ```

2. **Install the required Python packages**

    ```sh
    pip install -r requirements.txt
    ```

3. **Install SpaCy**

    ```sh
    pip install -U spacy
    ```

4. **Download SpaCy language model**

    ```sh
    python -m spacy download en_core_web_sm
    ```

## Usage

Once you have installed the dependencies, you can run the application and start using it to analyze movie reviews and get recommendations. Below is an example of how to use the app:

1. **Sentiment Analysis**

    Input a movie review and the app will classify the sentiment as positive or negative using the Naive Bayes Classifier.

2. **Movie Recommendations**

    Based on the content of the review, the TF-IDF Vectorizer will recommend similar movies.

3. **Named Entity Recognition**

    The app will identify named entities such as movie titles, actors, and other relevant entities using SpaCy.

## Contributing

We welcome contributions! Please fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Thanks to the developers of NLTK, scikit-learn, pandas, and SpaCy for their amazing libraries.
- Special thanks to the open-source community for their continuous support.

---

Feel free to customize this README further based on your specific project details and requirements.
