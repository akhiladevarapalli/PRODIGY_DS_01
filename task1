import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

data=pd.read_csv("/content/Salary_Data[1].csv")
data

# Create bar chart for gender distribution(categorical)
gender_counts = df['Gender'].value_counts()
plt.figure(figsize=(8, 5))
sns.barplot(x=gender_counts.index, y=gender_counts.values)
plt.title('Gender Distribution')
plt.xlabel('Gender')
plt.ylabel('Count')
plt.show()

# Create histogram for age distribution
plt.figure(figsize=(8, 5))
sns.histplot(df['Age'], bins=5, kde=False)
plt.title('Age Distribution')
plt.xlabel('Age')
plt.ylabel('Frequency')
plt.show()
