## Don’t Know Wines? Don’t Wine About It!
### Wine_Multiclass_Perceptron_Final_Project

Team: Felicia Zheng, Asya Tarabar, Daniel Coria, Morgan Taylor

**Overview:** This project builds a multi-class perceptron classifier that categorizes wines into one of seven categories: dry red, medium red, sweet red, dry white, medium white, sweet white, or rosé. Given a wine's features, the model predicts its class, making wine information accessible without needing a sommelier.

**Requirements:**

No installation needed if you are running in Google Colab — NumPy, Scikit-Learn, and Matplotlib come pre-installed. The notebook will run a pip install automatically as its first cell just in case.

**Data:**

The dataset CSV file (XWines_Full_100K_wines.csv) is included in the zip file submission. You do not need to download it separately.

If for any reason the file is missing, it can also be downloaded from the project GitHub repository: https://github.com/danielcoria8/Wine_Multiclass_Perceptron_Final_Project

Additionally, it is included in the zip file that we submitted to Gradescope.

## How to Run:

**1. Open Intro_ML_Final_Project.ipynb in Google Colab**

**2. Run all cells in order — the first cell will automatically install any required dependencies**

*Note*: The CSV file should be automatically cloned in the Colab file. However, if this does not work, upload the CSV file (XWines_Full_100K_wines.csv) to your Colab session by clicking the folder icon on the left sidebar, then clicking the upload button, and selecting the CSV file from the unzipped folder

## Output:

After running the notebook, you will see:

- results of K-Fold cross validation
- the distribution of true and predicted labels within the test set
- final model accuracy
- a confusion matrix comparing the predicted and true labels from the final model

## Notes:

- Make sure the dataset file is in the correct directory before running or the notebook will not load the data properly
