Sleep Health and Digital Screen Exposure Dataset
📌 Context

Understanding the relationship between sleep quality, stress levels, and exposure to the digital screen is crucial to analyzing the health impacts of modern lifestyle. This dataset provides detailed insights into various factors that affect sleep and eye health, including sleep duration, stress, physical activity, medical history, and digital device use before bed.

📂 Dataset Description

The dataset contains a wealth of information about individuals, including sleep habits, general health, and use of digital devices. The following is a description of the columns:

📝 Variables

Gender: Gender of Individual (M/F)

Age: Age of the individual (in years)

Sleep Duration: Average sleep duration (in hours)

Sleep Quality: Self-reported sleep quality (Scale: 1 - Poor to 5 - Excellent)

Stress Level: Stress level (Scale: 1 - Low to 5 - High)

Blood Pressure: Blood pressure recorded (systolic/diastolic in mmHg)

Heart Rate: Resting heart rate (in bpm)

Daily Steps: Average daily steps taken

Physical Activity: Level of physical activity (quantified measure)

Height: Height of individual (in cm)

Weight: Weight of the individual (in kg)

Sleep Disorder: Whether the individual has a sleep disorder (S/N)

Waking Up During the Night: Whether the individual wakes up during the night (Y/N)

Feeling Sleepy During the Day: If the individual feels sleepy during the day (Y/N)

Caffeine Consumption: Whether the individual consumes caffeine (S/N)

Alcohol Consumption: Whether the individual consumes alcohol (Y/N)

Smoker: If the individual is a smoker (Y/N)

Medical Problem: Any existing medical conditions (Y/N)

Medication in Progress: Whether the individual is taking medication (Y/N)

Smart Device Before Bed: Use of Digital Devices Before Bed (Y/N)

Average Screen Time: Average daily screen time (in hours)

Blue Light Filter: Whether the individual uses a blue light (S/N) filter

Eye Strain: Experience of discomfort or eye strain (Y/N)

Eye Redness: Eye Redness Experience (Y/N)

Eye Irritation: Experience of itching or eye irritation (Y/N)

Dry Eye Disease: Diagnosis or Symptoms of Dry Eye (S/N) Disease

⚙️ Data Processing

The following steps have been applied to the dataset:

Data loading: Reading the CSV file using pandas.

Column Renaming: Translation of column names into Portuguese.

Binary value conversion: Replacement of "Y" with "S" to facilitate data interpretation.

Blood Pressure Separation: Creation of the 'Systolic' and 'Diastolic' columns.

Conversion to numerical values: Handling of possible errors in the conversion.

Calculating Average Pressure: Creating a new Average Pressure column.

📊 Analytics and Visualizations

We used the pandas, numpy, matplotlib and seaborn libraries to explore the dataset. Some analyses include:

Distribution of sleep quality and stress levels.

Relationship between screen time and sleep quality.

Impact of the use of digital devices on eye health.

Correlation between physical activity and sleep quality.
