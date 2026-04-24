📊 Dataset Explanation and Analysis Process
🧠 1. Dataset Creation
The file BD_CursoMongo.Estudiantes.csv contains student information.

Each row represents a student, and each column represents a characteristic (name, age, course, etc.).

🏗️ 2. Data Structure
The dataset is tabular:

Rows: students\
Columns: attributes
⚙️ 3. Processing in Python
Pandas was used to work with the dataset:

import pandas as pd
df = pd.read_csv("BD_CursoMongo.Estudiantes.csv")
Exploration:
df.head()
Analysis:
df.describe()
📝 4. Report Generation
A Markdown file was generated using:

df.head().to_markdown()
df.describe().to_markdown()
🎯 5. Conclusion
A complete workflow was implemented:

Data Loading\
Exploration\
Analysis\
Documentation
🚀 Future Improvements
Visualizations\
Data Cleaning\
Integration with MongoDB
