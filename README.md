Livestock Market Chain Analyzer (LMCA)

This project is a data analytics tool developed to support academic research on the live animal market chain in Ethiopia, particularly focusing on the Gursum district. It uses a structured analytical framework based on the Structure-Conduct-Performance (S-C-P) model and the Heckman Two-Stage Selection Model.


---

Features

Clean and analyze livestock market data

Perform exploratory data analysis (EDA)

Assess market structure using CR4 and HHI

Evaluate market conduct (pricing, strategies)

Measure market performance with TGMM

Model determinants of market participation and supply using Heckman 2-stage model



---

Project Structure

livestock-market-analyzer/
│
├── data/                  # CSV datasets for analysis
├── notebooks/             # Jupyter notebooks for EDA and modeling
├── app/                   # Streamlit app code (optional UI)
├── models/                # Saved model outputs
├── utils/                 # Utility scripts for analysis
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation


---

Installation

# Clone the repo
git clone https://github.com/your-username/livestock-market-analyzer.git
cd livestock-market-analyzer

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt


---

Usage

You can run data analysis using the notebooks or launch the app using:

streamlit run app/streamlit_app.py


---

License

This project is licensed under the MIT License - see the LICENSE file for details.


---

Author

Jemal Tahir Mumed


---

Feel free to contribute or fork the project for your own research or academic use!

