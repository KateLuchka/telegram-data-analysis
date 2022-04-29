
# Research and Analysis of Data from Telegram dialogs

In this project was conducted an in-depth research and analysis of data from dialogues downloaded from Telegram.

To do research were used (imported):
- matplotlib
- seaborn
- plotly.graph_objects
- plotly.subplots
- collections (Counter)
- wordcloud
- PIL
- datetime, calendar
- CategoricalDtype
- simplemma
- nltk.tokenize
- nltk.corpus





## Preparing Data
    1. Download your Data
        i. Merge all dialogs_data (csv files) into one
        ii. Merge all dialogs_meta_data (json files) into one
    2. Import all needed packages
   (Some packages may require the installation from python console)

## How to use
Jupyter-notebook is the way you can view our analysis of your data.

To get the results of analysis (including dataframes and visual part of research) you need to run all cells in order. (Some steps may need time to be completed)
## How to reuse code
For lemmatizing use:

    langdata = simplemma.load_data('uk')
    def preprocess_text(text)
For calculating sentiment use:

    def calculate_msg_sentiment(msg)
    def add_dialog_sentiment(data)
    def calculate_avg_subdialog_sentiment(data)
For visualisation of sentiment use:

    def visualize_user_sentiment(sentiment_data, user_id)

