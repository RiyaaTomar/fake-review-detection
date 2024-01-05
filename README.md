# fake-review-detection

## Overview

This project aims to detect fake reviews using natural language processing (NLP) techniques and machine learning algorithms. The primary focus is on utilizing a Random Forest Classifier to achieve an accuracy of approximately 84.34%.

## Installation

Ensure you have the required libraries installed:

```bash
pip install pandas numpy scikit-learn nltk
```

## Usage

To run the evaluation or test functions, use the provided `main()` 

## Dataset

The project uses the "fake reviews dataset.csv" file.

## Pre-processing

The text data undergoes several pre-processing steps, including the removal of emojis, lowercasing, stemming, lemmatization, and more. The `pre_process` function in the code handles these tasks.

## Model Training

The project employs a Random Forest Classifier for training. The model is trained on the pre-processed text data using TF-IDF vectorization. 

## Evaluation

The model's performance is evaluated using metrics such as confusion matrix, accuracy score, and classification report. The `evaluation` function in the code provides these results.

## Results

The model achieves an accuracy of approximately 84.34%, as evidenced by the evaluation metrics.

## Testing

You can test the model on your own reviews using the provided `test` function. Simply run the `main()` function and choose option 2.

## Future Improvements

Potential future improvements include experimenting with different models, incorporating advanced NLP techniques, and expanding the dataset.

## Acknowledgments

Special thanks to the authors of the dataset and the libraries used in this project.

## Contributing

Feel free to contribute by providing feedback, reporting issues, or suggesting improvements.


## Contact

For any questions or feedback, please contact [Riya Tomar] at [riyatomar155@gmail.com].