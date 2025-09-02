# Predictive-Maintenance-for-Healthcare-Equipment
This project uses **Machine Learning** to predict when healthcare equipment (e.g., MRI machines, ventilators, infusion pumps) will require maintenance.  
By analyzing IoT sensor data (usage hours, temperature, humidity, vibration, error rates), this solution aims to **reduce downtime, improve patient safety, and optimize maintenance schedules**.

---

## 🔍 Features
- ✅ Data preprocessing and feature scaling
- ✅ Predictive model using **Random Forest Classifier**
- ✅ Feature importance visualization
- ✅ Confusion matrix and performance evaluation
- ✅ Email notifications for maintenance alerts
- ✅ Model saving/loading using `joblib`
- ✅ Easy integration with IoT/real-time data streams

---

## 📂 Project Structure
📁 predictive-maintenance-healthcare/
├── data/
│ └── healthcare_equipment_maintenance_data.csv
├── models/
│ └── predictive_maintenance_model.pkl
├── notebooks/
│ └── exploration_and_modeling.ipynb
├── app/
│ └── send_alerts.py
├── main.py
├── requirements.txt
└── README.md

yaml
Copy code

---

## 🧪 How It Works
1. **Data Input:** Collect sensor data for healthcare devices.
2. **Preprocessing:** Normalize features with `StandardScaler`.
3. **Training:** Train a Random Forest model on historical data.
4. **Prediction:** Predict which devices need maintenance.
5. **Alerts:** Send automated emails to maintenance teams.

---

## 🛠️ Installation

```bash
# Clone this repository
git clone https://github.com/your-username/predictive-maintenance-healthcare.git

# Navigate to the folder
cd predictive-maintenance-healthcare

# Install dependencies
pip install -r requirements.txt

🚀 Usage
# Train the model
python main.py

# Predict and send alerts
python main.py --predict
