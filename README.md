# 🛡️ Network Intrusion Detection Using Random Forest and Gradient-Boosted Trees

## 📌 Project Overview

Network Intrusion Detection Using Random Forest and Gradient-Boosted Trees is a machine learning-based cybersecurity project designed to identify and classify malicious activities in network traffic.

The system analyzes network traffic patterns to distinguish normal network activities from potential intrusions. It uses two ensemble machine learning algorithms, Random Forest and Gradient-Boosted Trees, to learn patterns from historical network data and compare their effectiveness in intrusion detection.

## 🎯 Objectives

- Identify suspicious and malicious network traffic.
- Classify network traffic into normal and intrusive categories.
- Implement Random Forest and Gradient-Boosted Trees.
- Compare the performance of both machine learning models.
- Evaluate classification performance using standard evaluation metrics.
- Explore machine learning approaches for improving network security monitoring.

## 🧠 Algorithms Used

### 1. Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make a final prediction. It is used to learn patterns in network traffic and classify traffic as normal or malicious.

### 2. Gradient-Boosted Trees

Gradient-Boosted Trees build decision trees sequentially, with later trees learning from errors made by earlier trees. This approach provides a second model for comparison in network intrusion classification.

## 📂 Dataset

**Dataset:** CIC-IDS2017

CIC-IDS2017 contains network traffic records representing normal activities and different attack scenarios. It provides features suitable for machine learning-based intrusion detection.

The dataset is distributed across multiple CSV files. The final dataset size and dimensions will depend on the files selected and the preprocessing performed.

Dataset resource: [CIC-IDS2017 — Canadian Institute for Cybersecurity](https://www.unb.ca/cic/datasets/ids-2017.html)

## ⚙️ Project Methodology

1. **Data Collection:** Obtain the required network traffic files from CIC-IDS2017.
2. **Data Preprocessing:** Clean the dataset and handle missing or unsuitable values as required.
3. **Feature Preparation:** Select and prepare relevant network traffic features.
4. **Model Training:** Train Random Forest and Gradient-Boosted Trees using the prepared data.
5. **Classification:** Classify traffic into normal, intrusive, or attack categories.
6. **Performance Evaluation:** Compare both models using accuracy, precision, recall, F1-score, and confusion matrix analysis.

## 🛠️ Technologies

- **Programming Language:** Python
- **Dataset:** CIC-IDS2017
- **Data Processing:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Algorithms:** Random Forest, Gradient-Boosted Trees
- **Data Format:** CSV

## 📊 Evaluation Metrics

| Metric | Description |
|---|---|
| Accuracy | Measures the overall proportion of correct predictions. |
| Precision | Measures the proportion of predicted attacks that are actual attacks. |
| Recall | Measures the proportion of actual attacks correctly detected. |
| F1-score | Combines precision and recall into a single metric. |
| Confusion Matrix | Summarizes correct and incorrect classifications. |

The final performance comparison will be reported after training and evaluating both models.

## 📁 Project Structure

```text
network-intrusion-detection/
├── dataset/
│   └── README.md
├── notebooks/
│   └── intrusion_detection.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── train_random_forest.py
│   ├── train_gradient_boosting.py
│   └── evaluate_models.py
├── results/
│   └── README.md
├── requirements.txt
└── README.md
```



## 🚀 Getting Started

### Prerequisites

- Python 3.9 or a compatible version for your selected libraries
- pip
- CIC-IDS2017 dataset files

### Installation

1. Clone the repository:

   ```bash
   git clone <YOUR_GITHUB_REPOSITORY_URL>
   ```

2. Navigate to the project directory:

   ```bash
   cd network-intrusion-detection
   ```

3. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment.

   **Windows:**
   ```bash
   venv\Scripts\activate
   ```

   **Linux/macOS:**
   ```bash
   source venv/bin/activate
   ```

5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Place the selected CIC-IDS2017 CSV files in the dataset directory and run the project scripts or notebook according to your implementation.

*The installation and execution steps should be updated to match your actual code and dependency versions.*

## 📈 Expected Outcome

The project aims to provide a machine learning-based approach to network intrusion detection and a comparative analysis of Random Forest and Gradient-Boosted Trees.

The results are intended to help determine the relative effectiveness of the two algorithms for classifying normal and malicious network traffic.

## 🔮 Future Enhancements

- Add a real-time network traffic classification interface.
- Develop visual dashboards for model performance.
- Explore additional machine learning algorithms.
- Integrate alert generation for detected intrusions.
- Investigate deployment in a network monitoring environment.

These are possible extensions and are not claims about currently implemented features.

## 👥 Team Members

- **Tanya Sri** — `2520030112`
- **Prudhvi Sai** — `2520030286`

## 📄 License

Choose and add an appropriate open-source license before distributing this project publicly.

---

**Keywords:** Network Security, Intrusion Detection System, Machine Learning, Random Forest, Gradient-Boosted Trees, CIC-IDS2017, Cybersecurity, Classification.
