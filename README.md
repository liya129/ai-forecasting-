\# Rossmann AI Sales Forecasting



An end-to-end Machine Learning application designed to forecast Rossmann store sales and customer demand using historical retail data.



\## Project Overview



This project uses machine learning to predict future sales and customer demand for Rossmann stores. It provides an interactive Streamlit dashboard where users can explore forecasts and analyze business performance.



\## Key Features



\- AI-powered sales forecasting

\- Customer demand prediction

\- Interactive dashboard

\- Store-level forecasting

\- Data visualization and analysis

\- 42-day forecasting view

\- User-friendly Streamlit interface



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Scikit-learn

\- LightGBM

\- Streamlit

\- Plotly

\- Joblib

\- Hugging Face Hub



\## Project Structure



```text

Rossmann\_AI\_Forecasting/

│

├── app.py

├── requirements.txt

├── README.md

├── store.csv

├── train.csv

├── test.csv

├── sample\_submission.csv

│

└── models/

&#x20;   ├── rossmann\_customer\_rf\_07-11-2026-22-31-55.pkl

&#x20;   ├── rossmann\_feature\_lstm.keras

&#x20;   ├── rossmann\_feature\_scaler.pkl

&#x20;   └── rossmann\_rf\_01-10-2026-14-31-51.pkl

```



\## Installation



1\. Clone the repository:



```bash

git clone YOUR\_GITHUB\_REPOSITORY\_URL

```



2\. Navigate to the project directory:



```bash

cd Rossmann\_AI\_Forecasting

```



3\. Install dependencies:



```bash

pip install -r requirements.txt

```



4\. Run the application:



```bash

streamlit run app.py

```



\## Model Information



The current application downloads its LightGBM model files from Hugging Face Hub.



The local Random Forest and LSTM model files are separate project artifacts and are not currently loaded by the dashboard.



\## Dataset



The project uses the Rossmann Store Sales dataset, containing historical store sales, customer information, and store attributes.



\## Author



\*\*Anish Kumar Tiwari\*\*



\- GitHub: https://github.com/anish071

\- LinkedIn:www.linkedin.com/in/prashanthi-k-2a7229329



\---



\*Built with Python and Machine Learning.\*

