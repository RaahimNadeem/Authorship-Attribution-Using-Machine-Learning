# Authorship Attribution Using Machine Learning

<p align="center">
  <img src="https://github.com/RaahimNadeem/Authorship-Attribution-Using-Machine-Learning/assets/114340940/60d2da7b-9bd9-487c-988b-778a12246762" alt="Image">
</p>

## Project Overview
This project focuses on authorship attribution using various machine learning techniques. The main objective is to identify the author of a text from a given set of candidates. In this specific case, we use tweets from different personalities and employ machine learning models to attribute these tweets to their correct authors. The project is divided into two phases, each emphasizing different aspects of the authorship attribution process.

## Phase 1: Data Collection and Preprocessing
Highlights:
1. Scraped over 1000 tweets each from accounts of notable personalities (e.g., Roger Federer, Bill Gates).
2. Preprocessed the data by cleaning tweets, removing unnecessary symbols, and normalizing the text.

Key Tasks:
1. Data Collection: Tweets were collected using Twitter's API and stored for further analysis.
2. Data Cleaning: Tweets were cleaned to remove URLs, special characters, and non-ASCII symbols.
3. Feature Engineering: Extracted relevant features from the cleaned data, ensuring suitability for machine learning models.


## Phase 2: Model Training and Evaluation
Highlights:
1. Employed various machine learning models like KNN, Neural Networks, and Ensemble methods.
2. Utilized different feature extraction methods such as Bag of Words and Sentence Embeddings.

Key Tasks:
1. Model Selection and Training: Several machine learning models were trained using different feature sets.
2. Hyperparameter Tuning: Conducted extensive hyperparameter tuning to optimize model performance.
3. Model Evaluation: Evaluated models based on accuracy, precision, recall, and F1-score. Analyzed results using confusion matrices and classification reports.


## Results and Conclusion
1. Found that Ensemble methods, particularly Random Forest, showed promising results in authorship attribution.
2. Demonstrated that the choice of feature extraction method significantly affects model performance.
3. Concluded that embedding methods capturing contextual information performed better in attributing authorship.

## Future Work
1. Explore advanced NLP techniques for feature extraction.
2. Expand the dataset with more authors and diverse text samples.
3. Experiment with deep learning models for improved accuracy.


## Technologies Used
1. Python
2. Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Sentence Transformers
   
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-github-username/authorship-attribution-project.git
  ``
2. Install required packages

## Usage
Run the Python scripts for each phase to process the data and train the models:
```bash
python Phase1.py
python Phase2.py
```

## Contributing
Contributions are welcome. Please open an issue first to discuss what you would like to change or improve.

   
