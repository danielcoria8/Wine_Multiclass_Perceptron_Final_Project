## Wine_Multiclass_Perceptron_Final_Project

Team: Felicia Zheng, Asya Tarabar, Daniel Coria, Morgan Taylor

**Overview:** This project builds a multi-class perceptron classifier that categorizes wines into one of seven categories: dry red, medium red, sweet red, dry white, medium white, sweet white, or rosé. Given a wine's features, the model predicts its class, making wine information accessible without needing a sommelier.

**Requirements:**

No installation needed if you are running in Google Colab — NumPy, Scikit-Learn, and Matplotlib come pre-installed. The notebook will run a pip install automatically as its first cell just in case.

**Data:**

The dataset is hosted on Google Drive. Download it and place it in the same directory as the notebook before running.

Download the dataset here: https://drive.google.com/file/d/1S3E8MeDTQ7i2IC8NzSn13zhuHZYfjW2J/view?usp=sharing

## How to Run:

**1. Download the dataset CSV from the link above**

**2. Open Intro_ML_Final_Project.ipynb in Google Colab**

**3. Upload the CSV file to your Colab session by clicking the folder icon on the left sidebar, then clicking the upload button, and selecting the downloaded CSV file**

**4. Run all cells in order — the first cell will automatically install any required dependencies**

## Output:

After running the notebook, you will see:

- Training and validation accuracy scores across k-fold cross-validation
- Final test set accuracy
- A confusion matrix visualizing where categories overlap

## Notes:

- The model targets a mean accuracy of at least 80% using a multi-class perceptron with a one-vs-rest strategy
- If the perceptron does not meet the benchmark, a multi-layer perceptron or non-linear kernel fallback is implemented
- Make sure the dataset file is in the correct directory before running or the notebook will not load the data properly
