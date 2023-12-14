# Depression Detector NLP

## Description

Depression Detector NLP is a Python project developed in Google Colab for analyzing text-based negative sentiment data that may indicate a risk of depression. The project involves web scraping data from Twitter using six negative keywords related to depression, including "เศร้า", "อยากตาย", "เกลียดตัวเอง", "ท้อ", "หมดหวัง", and "เกิดมาทำไม". The collected data is then cleaned, and text processing techniques, such as Word Tokenization, are applied.

The next steps involve creating Word Clouds for each keyword, visualizing the most frequently occurring words associated with the negative sentiments. Following that, the project utilizes machine learning models for classification, including Gaussian Naive Bayes (GaussianNB), Decision Tree, k-nearest neighbors, and artificial neural network, to train a model that can accurately classify text into negative and positive sentiment categories.

## Project Details

- *Language:* Python
- *Environment:* Google Colab

## Results

The developed model exhibits an accuracy of 83%, showcasing its capability to accurately classify text data into negative and positive sentiment categories. This tool can be valuable for identifying individuals expressing signs of depression based on their online text content.

## Dependencies

- Python
- Jupyter Notebook
- Libraries: scikit-learn, nltk, wordcloud, etc. (Install dependencies using pip install -r requirements.txt)

## Usage

1. Clone the repository:

    
    git clone [https://github.com/yourusername/depression-detector-nlp.git](https://github.com/NatchayaSU/Project-in-Artificial-Intelligence-for-Data-Analytics/)
    cd depression-detector-nlp
    

2. Open the Jupyter Notebook in Google Colab and run each cell sequentially.

3. Follow the instructions in the notebook to train the models and analyze the data.

Feel free to customize and extend the project to suit your specific requirements.

## Contributors

- Natchaya Suklad
- Phatthraphon Phomngern


## License

This project is licensed under the [MIT License](LICENSE).
