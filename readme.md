# NYC Uber Pickups Dashboard

A quick, interactive dashboard built with **Streamlit** to explore Uber pickup patterns across New York City (using the September 2014 dataset). 

It gives you a visual breakdown of peak rush hours and plots exact pickup locations on a live map.

---

##  Features

* **Instant Data Caching:** Uses `@st.cache_data` so the 100,000+ row dataset loads once and stays snappy.
* **Raw Data Preview:** Toggle the raw dataframe view on and off with a simple checkbox.
* **Rush Hour Insights:** Interactive bar chart showing pickup volume by hour (0–23).
* **Interactive Map:** Pick any hour of the day using the slider to see a heat-style plot of where rides originated.

---

##  Quick Start

### 1. Set up a virtual environment

Open your terminal in the project folder:

```bash
python3 -m venv venv
source venv/bin/activate

### 2. Install dependencies

```bash
pip install -r requirements.txt

### 3. Run the app

```bash
streamlit run app.py