📦 Supply Chain Replenishment Dashboard (Streamlit)

A predictive analytics tool designed to assist supply chain teams in planning replenishment for semiconductor spare parts. 
The app combines machine-learning forecasts, confidence-based safety stock calculations, and business-driven inputs to support data-backed procurement decisions.

🔧 Key Features

Predicts replenishment quantity using a trained ML model (replenishment_model.pkl)

Confidence-based safety stock & reorder point using Z-scores

Visualizes 12-month historical demand + 3-month forecast (Plotly)

Business scoring inputs (criticality, supplier reliability, cost buckets)

Interactive Streamlit UI with KPI tiles & recommendations

🛠 Tech Stack

Python, Streamlit, Pandas, NumPy

Plotly for visualizations

scikit-learn for forecasting

joblib for model deployment

🚀 How to Run
pip install -r requirements.txt
streamlit run app.py

📁 File Structure
├── app.py
├── replenishment_model.pkl
├── requirements.txt
└── README.md

📍 Use Case

Ideal for:

Inventory planners

Spare-parts forecasting

Demand & lead-time modeling

Procurement decision support
