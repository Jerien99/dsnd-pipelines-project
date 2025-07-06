# README Template

Below, you can find all necessary information to work with the files in this repository.

# Predicting Customer Recommendations

The starter.ipynb file in the starter folder of this repository builds a preprocessing and model fitting and evaluation pipeline that predicts whether a customer recommends a product based on their feedback and some customer characteristics. 

Within the starter folder, you will find a data subfolder that contains the .csv file with the data necessary as input for the pipeline. This data contains 8 features and a target column:

- **Clothing ID**: Integer Categorical variable that refers to the specific piece being reviewed.
- **Age**: Positive Integer variable of the reviewers age.
- **Title**: String variable for the title of the review.
- **Review Text**: String variable for the review body.
- **Positive Feedback Count**: Positive Integer documenting the number of other customers who found this review positive.
- **Division Name**: Categorical name of the product high level division.
- **Department Name**: Categorical name of the product department name.
- **Class Name**: Categorical name of the product class name.

The target:
- **Recommended IND**: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.

The numerical, categorical and text features are separated into their own preprocessing pipelines. For the text features, a custom CountWords-class and a tfidf vectorizer are used to extract features from this data.

## Getting Started

To work with this repository, clone the repository from your GitHub account into a local or cloud-based program. Then, install the necessary dependencies using:

python -m pip install -r requirements.txt

SpaCy may require a different manner of installation, depending on the type of computer you are using. For this, refer to the official SpaCy website.

Note that especially the code block in which Randomized Search is executed for hyperparameter tuning, could take a considerable time to run (approximately 20 minutes).

### Dependencies

```
scikit-learn
spacy
notebook
pandas
```

## Testing

To perform automated testing, install a package that is able to execute this, such as pytest. Also make sure that automated tests are performed when performing a commit or merge in GitHub. For this, please refer to the dedicated GitHub settings.

## Built With

* [Item1](www.item1.com) - Description of item
* [Item2](www.item2.com) - Description of item
* [Item3](www.item3.com) - Description of item

Include all items used to build project.

## License

[License](LICENSE.txt)
