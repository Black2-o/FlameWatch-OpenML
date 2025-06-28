
# 🔥 FlameWatch-OpenML

**FlameWatch-OpenML** is an open-source, AI-powered wildfire prediction system developed in June 2025 by **Tanvir Nishat**, **Md. Shahidullah**, and **Raiyan Rahaman** as part of the **Bolt.New Global Hackathon**. This project leverages satellite data from NASA and advanced machine learning techniques to forecast wildfire risks in real time, empowering communities and authorities to take proactive measures against devastating wildfires.

Originally created by the team **Ignite Intelligence**, FlameWatch-OpenML is now publicly available to encourage collaboration, innovation, and climate resilience worldwide.

---

## 🌍 Project Overview

Wildfires pose a significant threat to ecosystems, human lives, and economies around the globe. Early detection and risk prediction are critical for timely intervention and resource allocation. FlameWatch-OpenML addresses this challenge by integrating multiple NASA datasets, including FIRMS (fire detection) and POWER (environmental conditions), with machine learning models to predict wildfire risk effectively.

Using a Random Forest classifier trained on a rich dataset of environmental and fire occurrence variables, FlameWatch-OpenML identifies high-risk zones before wildfires fully ignite, giving disaster management teams valuable lead time.

---

## 🚀 Why FlameWatch-OpenML?

- **Data-driven:** Combines NASA's real-time satellite datasets with robust machine learning.
- **Open-source:** Freely available to researchers, developers, and emergency responders.
- **Reproducible & Extensible:** Clear codebase and documentation allow you to retrain or customize the model.
- **Real-world impact:** Designed to help save lives, protect wildlife, and minimize economic losses from wildfires.

---

## 📦 Features

- 🔥 **Wildfire risk prediction:** Predicts fire occurrence based on climate variables like temperature, humidity, wind speed, and satellite thermal hotspot data.
- 🌎 **NASA data integration:** Uses publicly available NASA FIRMS and POWER datasets.
- 🧠 **Random Forest classifier:** Proven machine learning algorithm providing high accuracy and interpretability.
- 🧪 **Balanced dataset training:** Trained with both fire and no-fire data to reduce false positives.
- 📊 **Performance metrics:** Achieves over 90% accuracy, precision, and recall in validation tests.
- 🧾 **MIT licensed:** Free for commercial and non-commercial use.

---

## 🛠 Technology Stack

- **Python 3.8+**
- Data manipulation: `pandas`, `numpy`
- Machine learning: `scikit-learn`
- Visualization (optional): `matplotlib`, `seaborn`
- Jupyter Notebook or Google Colab (for interactive demos)
- NASA API for data retrieval

---

## 📂 Directory Structure

```
FlameWatch-OpenML/
├── LICENSE
├── README.md
├── requirements.txt
├── model/
│   ├── best_model.pkl
│   └── best_model_tuned.pkl
├── src/
│   ├── nasa_data.py
│   └── nasa_data_nonf.py
├── test/
│   ├── testing_m.py
│   └── testing_usingdat.py
└── train/
    ├── merging.py
    └── training.py
```

---

## ⚙️ Installation & Setup

Follow the steps below to get started with FlameWatch-OpenML on your local machine:

1. **Clone the repository**

```bash
git clone https://github.com/your-username/FlameWatch-OpenML.git
cd FlameWatch-OpenML
```

2. **Create a Python virtual environment (recommended)**

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Train the model (optional)**

```bash
python train/training.py
```

5. **Run tests or make predictions**

```bash
python test/testing_usingdat.py
```

---

## 📊 Model Performance

| Metric     | Score  |
|------------|--------|
| Accuracy   | 93%    |
| Precision  | 92%    |
| Recall     | 91%    |

> These metrics indicate the model's strong capability in correctly predicting wildfire occurrences, balancing false positives and false negatives effectively.

---

## 📖 How It Works

The FlameWatch-OpenML pipeline involves:

- **Data ingestion:** Satellite and weather data from NASA APIs are preprocessed and merged.
- **Feature extraction:** Important variables (temperature, humidity, NDVI, wind speed, etc.) are selected.
- **Model training:** A Random Forest classifier learns patterns distinguishing wildfire vs. non-wildfire conditions.
- **Prediction:** The trained model evaluates new input data and predicts the risk of wildfire.
- **Output:** Risk scores can be visualized or integrated into alerting systems.

---

## 🙌 Contributions & Support

We welcome contributions to improve the dataset, algorithms, and usability! Please feel free to:

- Open issues for bugs or feature requests
- Submit pull requests with improvements or new features
- Share your feedback and use cases

Together, we can enhance wildfire prevention globally.

---

## 🧾 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👥 Authors

- **Tanvir Nishat**  
- **Md. Shahidullah**  
- **Raiyan Rahaman**

---

## 🔗 Related Links

- [Bolt.New Hackathon](https://bolt.new)  
- [NASA Space Apps Challenge - Ignite Intelligence Team](https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/ignite-intelligence/?tab=project)

---

## 🌱 Final Note

Wildfires are a growing global threat intensified by climate change. FlameWatch-OpenML strives to be a practical, community-driven tool leveraging open data and AI to make a difference. We invite everyone to use, contribute, and spread this technology — because together, we can ignite intelligent solutions for a safer planet.

---

**Thank you for checking out FlameWatch-OpenML!**  
*Let’s build a more resilient future.*  
🔥🌲🌍
