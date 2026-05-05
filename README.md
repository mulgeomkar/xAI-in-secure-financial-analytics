# EXPLAINABLE AI FOR SECURE ANALYTICS IN FINANCIAL SECTORS

Real-time fraud detection with transparent AI. Combines XGBoost machine learning with SHAP explainability to show exactly why a transaction is flagged as fraud.

---

## What is SecureScan AI?

SecureScan AI is a fraud detection dashboard that does not just predict fraud—it explains why. Using XGBoost for prediction and SHAP for interpretability, analysts and compliance teams get trustworthy, transparent fraud detection.

**Key Insight:** Instead of a black-box "fraud/safe" verdict, you see which factors contributed to the decision.

---

## Features

- **Real-Time Risk Audit** - Instantly evaluates transactions with fraud probability meter
- **Explainable Predictions** - Shows human-readable reasons for fraud flags
- **SHAP Visualizations** - Interactive charts showing feature contributions
- **Dark-Mode Dashboard** - Clean, responsive UI with smooth animations
- **Modern Stack** - FastAPI backend + React frontend with Vite

---

## Tech Stack

### Backend
- Python 3.13
- FastAPI (REST API)
- XGBoost (ML model)
- SHAP (Explainability)
- Pandas & Scikit-Learn (Data processing)

### Frontend
- React 19 + Vite
- Material-UI Components
- Chart.js (Visualizations)
- Framer Motion (Animations)

---



## How It Works

1. **Input** - User enters transaction details (amount, device, merchant, location)
2. **Process** - Data cleaned and transformed by Scikit-Learn pipeline
3. **Predict** - XGBoost model predicts fraud probability
4. **Explain** - SHAP calculates which features pushed the prediction up or down
5. **Display** - React dashboard visualizes the explanation

### Example: Feature Impact

| Factor | Impact |
|--------|--------|
| High Amount | Increases Fraud Risk |
| New Location | Increases Fraud Risk |
| Known Device | Decreases Fraud Risk |
| Trusted Merchant | Decreases Fraud Risk |

---

## Use Cases

- Banking & FinTech fraud monitoring
- Payment gateway auditing
- Compliance & regulatory reporting
- Explainable AI research
- Risk analyst dashboards

---



## Project Structure

```
explainable-AI-in-secure-financial-analytics/
├── backend/
│   ├── app.py              # FastAPI server
│   ├── requirements.txt    # Python dependencies
│   └── xgboost_model.json  # Trained model
├── frontend/
│   ├── src/
│   │   ├── App.jsx         # Main component
│   │   └── main.jsx        # Entry point
│   ├── package.json        # NPM dependencies
│   └── vite.config.js      # Vite config
└── README.md
```





