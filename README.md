# SCT_DS_01
The World Population Dashboard, built with Google Colab, Streamlit, Plotly, and Pandas, visualizes global population trends using the World Population Dataset . Features include country trends, top populated nations, and an interactive world map with year filters.
👇

🌍 World Population Dashboard

The World Population Dashboard is an interactive data visualization project built using Google Colab, Streamlit, Plotly, and Pandas. It helps analyze and explore global population trends with charts, filters, and maps for better insights.

📊 Features

📈 Population trends by country (line charts)

🏆 Top 10 most populated countries (bar charts)

🗺 World population distribution (choropleth map)

🎚 Year slider & country filter for interactivity

📂 Dataset

We use the World Population Dataset
 from DataHub:

Columns:

Country Name – Name of the country

Country Code – ISO3 code

Year – Year of observation

Value – Population count

🚀 Installation & Usage
In Google Colab

Open Google Colab
.

Install dependencies:

!pip install pandas plotly streamlit pyngrok


Save the app code as app.py.

Run Streamlit with LocalTunnel:

!streamlit run app.py & npx localtunnel --port 8501


Open the generated public URL to access the dashboard.

📷 Sample Visuals

Population Trend of India (2000–2020)

Top 10 Most Populated Countries (Latest Year)

World Population Map

(Add screenshots here once you run the dashboard)

🔮 Future Enhancements

📊 Add growth rate & forecast analysis

🌐 Compare multiple countries side by side

📥 Enable CSV/Excel export of filtered data

🤖 Integrate population prediction models

🛠️ Tech Stack

Python – Pandas, Plotly, Streamlit

Google Colab – Development environment

Pyngrok / LocalTunnel – Hosting dashboard from Colab
