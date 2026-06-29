📥 Dataset Setup

Due to GitHub's file size limitations, the dataset is not included in this repository.

Step 1: Download the Raw Dataset

Download the dataset from Kaggle:

Kaggle Link:
https://www.kaggle.com/datasets/brianmcgloughlin/japanese-housing-prices-2005-2024

then extract the zip and obtain the all_prefecture......csv file

Step 2: Create the Folder Structure

Inside the project directory, create the following folder if it does not already exist:

data/
└── raw/

Step 3: Copy the Dataset

Place the obtained CSV file inside the "data/raw/" folder.

Example:

data/
└── raw/
    └── all_prefecture....csv

«Note: Keep the original filename unchanged unless you also update the file path inside "src/eda.py".»

---

🧹 Generate the Cleaned Dataset

The cleaned dataset is generated automatically by the preprocessing script.

Step 1

Open a terminal in the project folder.

Step 2

Run the preprocessing script:

python src/eda.py

Step 3

The script will:

- Load the raw dataset
- Clean and preprocess the data
- Handle missing values and formatting
- Save the processed dataset as:

data/
└── cleaned.csv

Once "cleaned.csv" has been created, the remaining analysis scripts can be executed normally.
afterwards go to the japan_property_eda.ipynb under the folder named "notebook" and simply run the jupyter notebook

---

▶️ Running the Project

After generating "cleaned.csv", run the analysis scripts as usual.

Example:

python src/your_analysis_script.py

Replace "your_analysis_script.py" with the name of the analysis file you want to execute.


## What does the project demonstrate
Using pandas, matplotlib and introductory seaborn, i have taken a japan housing prices b/w the years 2005-2014,
cleaned the csv file and made out meaning insights about the data.
It visually demonstrates buisness and analytical questions with observations recorded. 
It also compares the drasticity of elements(price, region) over the span of years mentioned.

