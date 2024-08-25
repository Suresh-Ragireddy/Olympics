# Olympic Evolution: A 128-Year Journey - Python <a href="https://olympics-world.streamlit.app/" target="_blank">Web App</a>

### App Link
Access the web app 1 here: [Olympic Evolution: A 128-Year Journey](https://olympics-world.streamlit.app/)

- Web app 1 : https://olympics-world.streamlit.app/  ( Faster )

- Web app 2 : https://olympics-seq6.onrender.com

### Data Source Links
- **1896-2016 Dataset**: [Original Kaggle Dataset](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
- **2020 Tokyo Dataset**: [Kaggle Dataset for Tokyo 2020](https://www.kaggle.com/datasets/arjunprasadsarkhel/2021-olympics-in-tokyo)
- **2024 Paris Dataset**: [Kaggle Dataset for Paris 2024](https://www.kaggle.com/datasets/sajkazmi/paris-olympics-2024-games-dataset-updated-daily)

## Introduction
This project presents an in-depth analysis of the modern Olympic Games, covering 128 years from Athens 1896 to Paris 2024. The aim is to explore the evolution of the Olympics, highlighting changes in participation, gender dynamics, and performance across various nations and sports. A new comprehensive dataset has been compiled, incorporating the latest data from the Tokyo 2020 and Paris 2024 Games. The complete dataset is available in the repository's data folder, with links to the individual datasets for Tokyo and Paris provided above.

## Data Source
The core dataset for this analysis is sourced from <a href="https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results" target="_blank"><strong>Kaggle</strong></a>, covering up to the Rio 2016 Olympics. It includes:

- **`athlete_events.csv`**: 271,116 records with 15 attributes detailing athlete participation in individual Olympic events. Key fields include:
  - ID: Athlete's unique identifier
  - Name: Athlete's full name
  - Sex: Gender (M/F)
  - Age: Athlete's age
  - Height: Height in centimeters
  - Weight: Weight in kilograms
  - Team: Team or country name
  - NOC: National Olympic Committee code
  - Games: Year and season of the Olympics
  - Year: Year of the event
  - Season: Summer or Winter
  - City: Host city
  - Sport: Sport category
  - Event: Specific event within the sport
  - Medal: Type of medal won (Gold, Silver, Bronze, or NA)


## Python Web App
The project is accessible via a Streamlit web app that provides interactive visualizations and insights. You can explore it <a href="https://olympics-world.streamlit.app/" target="_blank"><strong>here</strong></a>. **Note:** All graphs and charts are interactive, allowing for hover details and PNG downloads.

## Web App Features
The web app offers four main sections for exploring the Olympic dataset:

### 1. Medal Tally
- **Overview**: Displays medal counts for all participating countries.
- **Filters**: Users can filter by country and year to view specific medal tallies.

### 2. Overall Analysis
- **Olympic Statistics**: Presents top statistics including Editions, Hosts, Sports, Events, Nations, and Athletes.
- **Participation Trends**: Line graphs showing the number of countries and athletes over the years.
- **Event Analysis**: Line graphs for the number of events organized annually.
- **Sport-Specific Analysis**: Heatmap showing the correlation between the number of events and the year for each sport.
- **Top Athletes**: A table listing the top 15 medal-winning athletes, filterable by sport.

### 3. Country-wise Analysis
- **Medal Trends**: Line graph showing the medal tally over time for selected countries.
- **Sports Excellence**: Heatmap revealing the sports in which a country excels.
- **Top Athletes**: Table displaying the top 10 athletes from the selected country.

### 4. Athlete-wise Analysis
- **Age Distribution**: Curves showing the age distribution of medal-winning athletes.
- **Gold Medalists**: Curves showing age distribution by sport for Gold medalists.
- **Gender Ratio**: Scatter plot comparing height vs weight of athletes, with a filter for sports.
- **Gender Participation**: Line graph tracking male vs female participation over the years.

## How to Run the Project Locally
1. **Clone the Repository**: Run `git clone https://github.com/Suresh-Ragireddy/Olympics.git` in your terminal.
2. **Install Dependencies**: Use `pip install -r requirements.txt` to install required libraries.
3. **Run the App**: Start the app by running `streamlit run app.py`.
4. **Access the Web App**: The app will open automatically in your browser.


