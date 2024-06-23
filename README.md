# Data_Science_Capstone

**README: Data Science Capstone Project**

**Project Title:** Predicting Successful Stage 1 Recovery for Space Y Rockets

**Overview:**
This repository contains the code and documentation for the Data Science Capstone Project by IBM, focusing on predicting the successful recovery of Stage 1 rockets for Space Y, a hypothetical aerospace company. The project leverages machine learning techniques to analyze historical data from SpaceX and other sources to develop predictive models.

**Project Structure:**
1. **Data Collection:**
   - The data was collected using a combination of Space X's public API and web scraping techniques from Space X's Wikipedia page.
   - **Space X API Data Columns:**
     - FlightNumber, Date, BoosterVersion, PayloadMass, Orbit, LaunchSite, Outcome, Flights, GridFins, Reused, Legs, LandingPad, Block, ReusedCount, Serial, Longitude, Latitude
   - **Wikipedia Web Scraping Data Columns:**
     - Flight No., Launch site, Payload, PayloadMass, Orbit, Customer, Launch outcome, Version Booster, Booster landing, Date, Time

2. **Data Preprocessing:**
   - Cleaning and merging of data from both sources.
   - Feature engineering to create relevant features for modeling.
   - Encoding categorical variables and handling missing data.

3. **Exploratory Data Analysis (EDA):**
   - Statistical analysis and visualization to understand the distribution and relationships within the dataset.
   - Identification of key factors influencing Stage 1 recovery success.

4. **Model Development:**
   - Implementation of machine learning models:
     - Logistic Regression
     - Support Vector Machine
     - Decision Tree Classifier
     - K Nearest Neighbors
   - Model training, evaluation, and optimization using GridSearchCV.

5. **Model Evaluation:**
   - Assessment of model performance metrics such as accuracy, precision, recall, and F1-score.
   - Visualization of model results to compare and analyze predictions.

6. **Deployment:**
   - Discussion on potential deployment strategies for the developed models within Space Y's operational framework.
   - Consideration of ongoing model maintenance and updates.

**Files Included:**
- **data/**: Directory containing raw and processed datasets.
- **notebooks/**: Jupyter notebooks detailing data exploration, preprocessing, modeling, and evaluation.
- **README.md**: Project overview, setup instructions, and details on data sources and methodology.
- **requirements.txt**: List of Python packages required to run the project.

**Usage:**
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/SpaceY-Stage1-Recovery-Prediction.git
   cd SpaceY-Stage1-Recovery-Prediction
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

**Acknowledgments:**
- Special thanks to IBM for providing the framework and resources for this capstone project.
- Acknowledgment of Space X for their publicly accessible API and data on Wikipedia, which facilitated this analysis.

