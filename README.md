# Task5

📋 Summary of Titanic Dataset EDA
✨ Objective:
Extract insights from the Titanic dataset using statistical summaries and visualizations.

🔹 Data Overview:
The dataset contains information about Titanic passengers:

Personal features like Name, Age, Sex

Ticket information: Pclass, Fare, Cabin

Survival status: Survived

Missing values were found in Age, Cabin, and Embarked columns.

🔹 Key Actions Performed:
Descriptive Analysis

Used .describe(), .info(), and .value_counts() to understand data distributions and missing values.

Data Cleaning

Filled missing numerical values (like Age) with the mean.

Filled missing categorical values (like Embarked) with the mode.

Correlation and Pairwise Analysis

Plotted heatmap to find correlations between numerical features.

Plotted pairplot to visualize feature relationships split by survival.

Feature Relationship Study

Analyzed survival probability based on:

Passenger Class (Pclass)

Gender (Sex)

Embarkation port (Embarked)

Distribution and Comparison Plots

Plotted histograms to see distributions.

Plotted boxplots for Age and Fare with respect to survival.

Plotted scatterplots to see relationships between Age, Fare, and Survival.

🔹 Main Insights / Findings:
Gender was a major factor: Females had a higher survival rate.

Passenger class mattered: Higher class (Pclass 1) had higher survival rates.

Fare: Passengers who paid higher fares survived more.

Age: Young children were slightly more likely to survive.

Embarked Port: Passengers from port C had a better survival rate.

🔹 Skills Gained:
Handling missing data correctly

Data exploration using Pandas

Data visualization using Seaborn and Matplotlib

Identifying trends, correlations, and patterns

Writing clean observations based on visuals

🏁 Final Outcome:
✔️ Completed a full exploratory data analysis (EDA)
✔️ Gained skills in finding patterns, trends, and anomalies in a real-world dataset.
