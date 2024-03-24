# Social Media Engagement Analyzer

## Introduction
This project utilizes machine learning and artificial intelligence techniques to analyze social media user engagement based on various factors such as sentiment, likes, retweets, and hashtags. The goal is to understand user behavior and identify patterns that contribute to higher engagement on social media platforms.

## Installation and Set-up
This project can either be executed on your local machines using Jupyter Notebook or using Google Colab.

### Using Google Colab
1. Go to the following [link](https://colab.research.google.com/) to use Google Colab.
![googlecolab1](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/gdrive1.png)
2. Clone the repository.
4. Go to File option in the Menu Bar and click on "Open Notebook" to open the ipynb file saved on your device. Conversely, you can also use the Keyboard shortcut Ctrl+O.
![googlecolab2](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/googlecolab2.png)
3. Click on "Upload" and select the downloaded ipynb file from the cloned repository.
![googlecolab3](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/googlecolab3.png)
4. While executing the following code snippet, you will be presented with a prompt. 
![gdrivecodesnippet](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/gdrivecodesnippet.png)
For the code snippet to work, you need to allow Google Colab to access your Google Drive to access the CSV dataset file present on your Google Drive.
   - Permit the Notebook to access the google drive. Click "Connect to Drive".
   ![gdrive1](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/gdrive1.png)
   - Choose the Google Account you are working on.
   ![gdrive2](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/gdrive2.png)
   - Sign in to Google Drive for Desktop by clicking "Continue".
   ![gdrive3](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/gdrive3.png)
   - Allow additional access to Google account. [Read the Consent Summary carefully]
   ![gdrive4](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/gdrive4.png)


### Using Jupyter Notebook
1. Install Jupyter Notebook using default installation method.
2. Clone the repository and open the ipynb file using Jupyter Notebook
3. Execute the code sequentially

## Usage
1. Run the `sentimentdataset.csv` file containing the dataset in the same directory as the Python Notebook.
2. Execute the Python Notebook `social_media_engagement_analyzer.ipynb`.
3. Follow the prompts and instructions provided in the script to preprocess the data, train the machine learning model, and visualize the results.

## Dataset
The dataset used in this project (`sentimentdataset.csv`) contains social media posts with information such as timestamp, sentiment, likes, retweets, and hashtags. The Dataset was taken from Kaggle. Link for the dataset used is given [here.](https://www.kaggle.com/datasets/kashishparmar02/social-media-sentiments-analysis-dataset/data)
![kaggle](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Extras/kaggle.png)

## Models
The project employs a RandomForestClassifier model to analyze user engagement based on various features extracted from social media posts.

## Evaluation
The performance of the model is evaluated using classification report metrics such as precision, recall, and F1-score.

## Visualizations
1. **Time of Day Distribution**: Shows the distribution of user posts based on time of day, categorized as day or night.
![Time of Day](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Visualization/tod.png)

2. **Correlation Heatmap**: Visualizes the correlation between different features of the dataset.
![Correlation Heatmap](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Visualization/corr.png)

3. **Feature Importance Plot**: Illustrates the importance of various features in the RandomForestClassifier model.
![Feature Importance](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Visualization/rfc.png)

4. **Top Hashtags with Maximum User Engagement**: Displays the top hashtags with the highest average combined user engagement scores.
![Top Hashtags](https://github.com/anujeshify/Social-Media-Engagement-Analyzer/blob/main/Visualization/tophash.png)

## Authors

* **Anujesh Bansal** - [anujeshify](https://github.com/anujeshify)

## Contribution
Contributions to this project are welcome! If you have any suggestions, bug fixes, or improvements, please feel free to open an issue or submit a pull request.
For any queries reach me at [anujeshbansaltoo@gmail.com](anujeshbansaltoo@gmail.com)

## Acknowledgments
Special thanks to the contributors and developers of the libraries and tools used in this project, including pandas, scikit-learn, matplotlib, and seaborn.
