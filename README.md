# CBPE
**Title:** The estimation of model performance on unseen data

Link to the paper: https://studenttheses.uu.nl/handle/20.500.12932/44950

**Abstract:**
In the field of machine learning, the evaluation of models typically involves training them on a specific dataset and assessing their performance on a separate test set. However, assessing their performance in real-world environments can be challenging, especially when there is a shortage of labeled data. This study focuses on estimating the performance of machine learning classifiers in financial audits, specifically on unseen accounting data. By employing the Confidence Based Probability Estimation methodology, performance metrics can be accurately estimated, considering both predicted labels and probabilities. These estimates can be made under the assumption that there is no concept drift, the model is well calibrated, and it exhibits consistent performance across all classes. The findings of this study have practical implications for auditors, offering insights into the feasibility and usability of integrating machine learning models into audit procedures. This enables auditors to make informed decisions regarding the adoption of these models. Furthermore, this research contributes to the field by emphasizing the importance of considering class discrepancies and promoting a data-driven approach to improve sampling methods beyond traditional random sampling. In future research, it would be valuable to address challenges such as multiclass calibration, class imbalance, threshold selection methods, and real-time monitoring of model performance. These areas of investigation would enhance the robustness and applicability of machine learning models in production settings.

**Additional Notes:**
The codebase provides access to the implementation of the CBPE used in this project. However, it's important to highlight that the data, which includes transactions and descriptions from two ministries, is bound by strict confidentiality agreements and therefore cannot be publicly shared. For those seeking a parallel for further exploration, a similar dataset (albeit in English) was employed in research conducted by Bao et al. (2020). The dataset, alongside the associated research paper titled "Detecting Accounting Fraud in Publicly Traded U.S. Firms Using a Machine Learning Approach," can be accessed via the following link: [Detecting Accounting Fraud](https://github.com/JarFraud/FraudDetection)

*Stopwords File:*
The stopwords file utilized in this project was developed in preceding research by Gene Diaz. The file, along with the related research documentation, is available for review and use here: [Link to Stopwords File and Research](https://github.com/stopwords-iso/stopwords-nl).

*Dutch Word2Vec File:*
The Dutch Word2Vec file, crafted for the research paper "Evaluating Unsupervised Dutch Word Embeddings as a Linguistic Resource" by Stephan Tulkens, Chris Emmery, and Walter Daelemans, is available for download and further investigation at the following location: [Dutch Word2Vec File](https://github.com/clips/dutchembeddings).

We encourage fellow researchers and developers to explore these resources and extend gratitude to the original authors for their invaluable contributions to the field. Your feedback and contributions to our project are also highly welcomed and appreciated.

**Conference Presentation:**
![image](https://github.com/AlexEssaijan/CBPE/assets/60449675/670c137a-8839-47bd-95c1-72aae82b6451)
