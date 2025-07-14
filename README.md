Australia Wildfire Dashboard 🔥
An interactive visualization tool to analyze historical wildfire patterns across Australia using Dash, Plotly, and Pandas.

🚀 Features
Region Selection: Choose from 7 Australian regions:

New South Wales (NSW)

Northern Territory (NT)

Queensland (QL)

South Australia (SA)

Tasmania (TA)

Victoria (VI)

Western Australia (WA)

Year Selection: Filter data by specific years.

Dynamic Visualizations:

📊 Pie Chart showing Monthly Average Estimated Fire Area.

📊 Bar Chart showing Monthly Average Count of Pixels for Presumed Vegetation Fires.

📂 Project Structure
project-root/
│
├── Dash_wildfire.py        # Main Dash app
├── requirements.txt             # Python dependencies
├── README.md                    # Project documentation
🛠️ Technologies Used
Dash (Python Web Framework)

Plotly Express (Graphing Library)

Pandas (Data Manipulation)

Python 3.8+

📊 Data Source
Dataset: Historical Wildfires Dataset

Fields used:

Region

Date

Estimated_fire_area

Count

📦 Setup Instructions
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/australia-wildfire-dashboard.git
cd australia-wildfire-dashboard
Install Dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Dashboard:

bash
Copy
Edit
python wildfire_dashboard.py
Access:
Open your browser and navigate to http://127.0.0.1:8050/.

📋 Requirements.txt (Sample)
nginx
Copy
Edit
dash
pandas
plotly
🎯 Usage
Select a region from radio buttons.

Select a year from the dropdown.

View:

Pie chart: Monthly Average Estimated Fire Area.

Bar chart: Average Count of Vegetation Fires (pixels).

📈 Output Example
Pie chart: Visualizes distribution of fire-affected areas across months.

Bar chart: Highlights monthly activity of vegetation fires.

📌 Notes
Dashboard uses live rendering with dcc.Graph.

Modular structure using callbacks for interactive updates.

Handles multiple inputs (region & year) simultaneously.

