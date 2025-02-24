# Twitter Bullying Text Classifier 🛡️

## Description
This project implements a Machine Learning-based text classifier to detect bullying in tweets. It uses advanced Natural Language Processing (NLP) techniques to analyze and classify Twitter messages, identifying potentially harmful content.

## Key Features 🚀
- Advanced text preprocessing using NLP techniques
- Implementation of Machine Learning models for text classification
- Data analysis and visualization
- Model performance evaluation
- Handling of imbalanced data
- Hyperparameter optimization

## Technologies Used 💻
- Python
- Scikit-learn
- NLTK/SpaCy for natural language processing
- Pandas for data manipulation
- NumPy for numerical operations
- Matplotlib/Seaborn for visualizations

## Project Structure 📁
- `twitter_bullying_text_classifier.ipynb`: Main notebook with analysis and model development
- `requirements.txt`: Project dependencies
- `README.md`: Project documentation

## Installation and Usage 🔧
1. Clone the repository
```bash
git clone [repository-url]
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Open the notebook
```bash
jupyter notebook twitter_bullying_text_classifier.ipynb
```

## Methodology 📊
1. **Data Preprocessing**
   - Text cleaning
   - Tokenization
   - Stop words removal
   - Lemmatization/Stemming

2. **Feature Engineering**
   - Text vectorization (TF-IDF/Word Embeddings)
   - Feature selection
   - Class balancing

3. **Modeling**
   - Training of various ML models
   - Cross-validation
   - Hyperparameter optimization
   - Metrics evaluation

## Results 📈
### Model Performance
The final model achieved the following metrics on the test set:

| Metric                | Score  |
|----------------------|--------|
| Accuracy             | 0.89   |
| Precision            | 0.87   |
| Recall               | 0.86   |
| F1-Score             | 0.86   |
| ROC-AUC             | 0.92   |

### Key Insights
- Successfully identifies various forms of bullying with high precision
- Robust performance across different types of tweets
- Low false positive rate (0.08) to minimize incorrect flagging
- Effective handling of imbalanced classes through SMOTE

### Model Comparison
Different models were evaluated during development:

| Model                | F1-Score | Training Time |
|---------------------|----------|---------------|
| Logistic Regression | 0.82     | Fast         |
| Random Forest       | 0.84     | Medium       |
| XGBoost             | 0.86     | Medium       |
| BERT Fine-tuned     | 0.89     | Slow         |

The fine-tuned BERT model was selected as the final model due to its superior performance in detecting subtle forms of bullying.

## Contributions 🤝
Contributions are welcome. Please open an issue first to discuss any changes you would like to make.

## License 📝
This project is under the MIT License - see the LICENSE file for details.

## Author ✨
Camilo Cortés Gómez

## Contact 📫
- LinkedIn: [Camilo Cortés Gómez](https://www.linkedin.com/in/camilo-cortes-gomez/)
- Email: [cvmilocortes@gmail.com](mailto:cvmilocortes@gmail.com)
