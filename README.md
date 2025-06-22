Sentiment Analysis – Task 4

This project performs sentiment analysis on a dataset using Python. It applies natural language processing techniques to classify and visualize sentiments.

Repository Structure:
```
TASK_4/
├── dataset_task 4.csv               # Raw textual dataset used for sentiment analysis
├── Task 4.py                        # Python script for preprocessing, sentiment scoring, and visualization
├── op_task4.csv                     # Output CSV containing sentiment predictions
└── outputs_task4/                   # Visual outputs of sentiment results
    ├── original_sentiment_bar.png
    ├── sentiment_by_topic_bar.png
    └── vader_sentiment_pie.png
```

Features:
* Text cleaning and preprocessing
* Sentiment analysis using VADER
* Topic-wise sentiment distribution
* Visualizations: sentiment breakdown (pie/bar charts)
* CSV output containing labeled sentiments

Requirements:
* Python 3.x
* pandas
* matplotlib
* seaborn
* nltk
* vaderSentiment

Install dependencies using:
```bash
pip install pandas matplotlib seaborn nltk vaderSentiment
```

How to Run:
1. Clone the repository.
2. Navigate to the `TASK_4/` directory.
3. Run the Python script:
```bash
python "Task 4.py"
```

Output:
* Visualizations are saved in the `outputs_task4/` folder.
* Sentiment predictions are saved in `op_task4.csv`.
