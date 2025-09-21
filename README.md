# SCT_DS_01
The World Population Dashboard, built with Google Colab, Streamlit, Plotly, and Pandas, visualizes global population trends using the World Population Dataset . Features include country trends, top populated nations, and an interactive world map with year filters.
👇

🌍 World Population Dashboard

The World Population Dashboard is an interactive data visualization project built using Google Colab, Streamlit, Plotly, and Pandas. It helps analyze and explore global population trends with charts, filters, and maps for better insights.

📊 Features

📈 Population trends by country (line charts)
🏆 Top 10 most populated countries (bar charts)
🗺 World population distribution (choropleth map)

<img width="809" height="529" alt="image" src="https://github.com/user-attachments/assets/1b8de13c-bc86-40e3-9863-11c95d272846" />


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

Population Trend of India 
<img width="850" height="547" alt="image" src="https://github.com/user-attachments/assets/5ba17fef-ab77-4dd0-a7af-b26a4c7742fd" />
<img width="868" height="547" alt="image" src="https://github.com/user-attachments/assets/2d33cfda-3153-4ec8-9e9c-9cbae5d39553" />

Top 10 Most Populated Countries (Latest Year)
<img width="1189" height="690" alt="image" src="https://github.com/user-attachments/assets/3f7b44ea-851e-4c8f-8133-7232552e9a7a" />
<img width="1190" height="690" alt="image" src="https://github.com/user-attachments/assets/90168374-1ccf-4fd9-98c7-576388bbbf5b" />

World Population Map

![Screenshot_21-9-2025_145810_colab research google com](https://github.com/user-attachments/assets/10f67e7d-e1eb-474f-950e-caddbe52b844)
<img width="797" height="525" alt="image" src="https://github.com/user-attachments/assets/75d523cd-89eb-402e-a3c6-cda8b86cb42c" />

🔮 Future Enhancements

📊 Add growth rate & forecast analysis

🌐 Compare multiple countries side by side

📥 Enable CSV/Excel export of filtered data

🤖 Integrate population prediction models

🛠️ Tech Stack

Python – Pandas, Plotly, Streamlit

Google Colab – Development environment

Pyngrok / LocalTunnel – Hosting dashboard from Colab
