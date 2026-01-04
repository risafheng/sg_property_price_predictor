# sg_property_price_predictor

### Setup
This project was developed using 
- Computer
    - Apple M2 Pro
    - macOS Sequoia 15.1.1
- Visual Studio Code
    - Version: 1.84.2 (Universal)
    - OS: Darwin arm64 24.1.0
- Python
    - Version 3.11.13
- Install requirements.txt
    - `pip install -r requirements.txt`
- Run Python Notebook
    - sg_property_price_predictor.ipynb

### Respository Structure
sg_property_price_predictor<br>
├── README.md<br>
├── sg_property_price_predictor.ipynb<br>
├── data<br>
│   └── resale-flat-prices-based-on-approval-date-1990-1999.csv<br>
│   └── resale-flat-prices-based-on-approval-date-2000-feb-2012.csv<br>
│   └── resale-flat-prices-based-on-registration-date-from-jan-2015-to-dec-2016.csv<br>
│   └── resale-flat-prices-based-on-registration-date-from-jan-2017-onwards.csv<br>
│   └── resale-flat-prices-based-on-registration-date-from-mar-2012-to-dec-2014.csv<br>
├── models<br>
│   └── lasso.pkl<br>
│   └── lightgbm_tuned.pkl<br>
│   └── lightgbm.pkl<br>
│   └── ridge.pkl<br>
├── .gitignore<br>
└── requirements.txt<br>