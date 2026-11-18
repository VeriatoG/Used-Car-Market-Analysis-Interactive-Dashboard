Vehicle Listings Dashboard

Project Overview

An interactive web application developed with Python and Streamlit to explore and visualize vehicle listings data.

The dashboard allows users to interact with the dataset through dynamic visualizations, making it easier to explore vehicle mileage and the relationship between mileage and listing prices.

Business Objective

Provide an accessible and interactive way to explore vehicle listing data through a web-based dashboard, demonstrating how data visualization can support exploratory analysis and data-driven insights.

Application Features

- Mileage Distribution: Interactive histogram to explore the distribution of vehicle mileage.
- Price vs. Mileage Analysis: Interactive scatter plot to visualize the relationship between vehicle prices and mileage.
- Interactive Controls: Checkboxes allow users to choose which visualizations to display.
- Web Deployment: Publicly accessible application hosted on Render.

Tools & Technologies

- Python
- Pandas
- Plotly Express
- Streamlit
- Jupyter Notebook
- Git & GitHub
- Render

Project Structure

sprint5-project/
├── .streamlit/
│   └── config.toml
├── notebooks/
├── app.py
├── vehicles.csv
├── requirements.txt
├── .gitignore
└── README.md

Run Locally

1. Clone the repository:

git clone https://github.com/VeriatoG/sprint5-project.git

2. Navigate to the project directory:

cd sprint5-project

3. Install the dependencies:

pip install -r requirements.txt

4. Run the Streamlit application:

streamlit run app.py

Live Application

"Open Vehicle Listings Dashboard" (https://sprint5-project-dsuz.onrender.com/)

Author

Gabriela Veriato

"GitHub Profile" (https://github.com/VeriatoG)
