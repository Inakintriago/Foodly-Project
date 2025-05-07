# 🍔 Foodly: User Behavior Analysis

## 📝 Context
Foodly is a startup that offers food products through a mobile app. The goal of this project is to analyze user behavior within the app to optimize the sales funnel and assess the impact of a design change (fonts).

### 🎯 Objectives
1. **Study the Sales Funnel**: Analyze how users reach the purchase stage, identify at which stages most users drop off, and improve conversion.
2. **Evaluate an A/A/B Test**: Measure the impact of a design change (fonts) on user interaction.

## 🛠️ Tools Used
- **Python**: Data analysis and statistical modeling.
- **Pandas** and **NumPy**: Data cleaning and transformation.
- **Matplotlib** and **Seaborn**: Visualization of patterns and trends.
- **SciPy**: Statistical tests to evaluate the impact of differences between groups.
- **Jupyter Notebook**: Interactive documentation and analysis.

## 📂 Data Description
The dataset contains user event logs from the app. The main columns are:

- **EventName**: Name of the event performed.
- **DeviceIDHash**: Unique user identifier.
- **EventTimestamp**: Timestamp of the event.
- **ExpId**: Experiment number (246 and 247 are the control groups, 248 is the test group).

## 📊 Results Analysis

### 1. **Data Preprocessing**:
   - Loading and exploring the dataset.
   - Cleaning missing values and handling data types.
   - Aggregating date and time columns for easier temporal analysis.

### 2. **Sales Funnel Analysis**:
   - Study of the recorded events and their frequency.
   - Calculation of the proportion of users who perform each action and their progress in the funnel.
   - Identification of the stage where most users drop off.

### 3. **A/A/B Test Analysis**:
   - Comparison between the two control groups (246 and 247) to validate data consistency.
   - Statistical evaluation of user behavior differences between the control groups and the test group (248).
   - Analysis of the impact of the new fonts on user conversion, comparing results across groups.

### 4. **Hypothesis Testing**:
   - Determining statistical significance for differences between control and test groups.
   - Calculating p-values for each key event to validate results.

## 📋 Conclusions
- **Sales Funnel**: Critical stages where a large number of users drop off were identified. Improvements in these stages could significantly increase the conversion rate.
- **A/A/B Test**: No significant differences were found between the control groups, validating the correct assignment of users to groups. However, a small positive impact of the new fonts on user interaction was observed.
- **Data-Driven Decisions**: The conclusions from the analysis will help the design and marketing teams make informed decisions regarding design changes in the app.

## 📝 Next Steps
- Improve the stages of the funnel where most users drop off.
- Conduct further tests with other design modifications to assess their impact.
- Continue monitoring the data to ensure that implemented changes are effective in the long run.
