# 🧠 Smoking Habit Predictor

**A machine learning classifier that predicts smoking status using health and dental data.** This project demonstrates supervised learning with data preprocessing, feature encoding, and Support Vector Machines (SVM) for classification.

---

## 📌 Project Purpose

The goal of this project is to build a predictive model that determines whether an individual is a smoker or non-smoker based on personal health examination records. It can be used for:

* Health risk analysis
* Screening tools in clinics
* Educational demonstrations of classification problems in ML

---

## 🗂 Project Files

| File / Folder        | Description                                |
| -------------------- | ------------------------------------------ |
| `Smoking_copy.ipynb` | Jupyter notebook with complete ML pipeline |
| `smoking.csv`        | Dataset (you must provide it)              |
| `README.md`          | Project documentation (this file)          |

---

## ✨ Key Features

* 📊 **Exploratory Data Analysis**
* 🧼 **Label Encoding for Categorical Data**
* ⚖️ **Feature Scaling using MinMaxScaler**
* 🧠 **Support Vector Machine (SVM) Classification**
* 📈 **Train/Test Split & Evaluation**
* 🔍 **Health-focused Predictive Modeling**

---

## 🧰 Tech Stack

* **Languages**: Python 3.x
* **Libraries**:

  * `pandas`, `numpy`
  * `scikit-learn`
  * `matplotlib` *(optional for visualization)*
* **Environment**: Jupyter Notebook

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/SmokeStatusPredictor.git
cd SmokeStatusPredictor
```

### 2. Install Dependencies

Just run:

```bash
pip install pandas numpy scikit-learn jupyter
```

### 3. Run the Notebook

Launch the notebook environment:

```bash
jupyter notebook
```

Open `Smoking_copy.ipynb` and run all cells.

---

## 🚀 Usage Example

Once the notebook is open, follow the steps:

```python
# Load and preprocess data
df = pd.read_csv('smoking.csv')

# Train-test split, label encode
# Train SVM classifier
# Evaluate accuracy
```

---

## 🖼️ Screenshots

*(You can replace these with actual images or links to notebook renders)*

**📈 Model Training Example**
![SVM Classification Output](https://via.placeholder.com/600x200.png?text=Model+Training+Screenshot)

---

## 📜 License

Feel free to use the project.**.

---

## 🙋‍♀️ Contributing

Pull requests are welcome! For major changes, please open an issue first.

---
