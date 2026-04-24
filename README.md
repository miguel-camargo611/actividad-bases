📊 Dataset Explanation and Analysis Process

🧠 1. Dataset Creation
The file BD_CursoMongo.Estudiantes.csv contains student information.
Each row represents a student, and each column represents a characteristic (name, age, course, etc.).

🏗️ 2. Data Structure
The dataset follows a tabular structure:

Rows: students
Columns: attributes

⚙️ 3. Processing in Python
The dataset was processed using the Pandas library:

import pandas as pd

df = pd.read_csv("BD_CursoMongo.Estudiantes.csv")
Exploration:
df.head()
Analysis:
df.describe()

📝 4. Report Generation
A Markdown report was generated using:

df.head().to_markdown()
df.describe().to_markdown()

🎯 5. Conclusion
A complete workflow was implemented, including:

Data loading
Data exploration
Data analysis
Documentation

🚀 Future Improvements

Add visualizations
Perform data cleaning
Integrate with MongoDB
