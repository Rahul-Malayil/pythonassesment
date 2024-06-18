This project is based on ABC company.In this we need to analyze 
1.the percentage split relative to the total number of employees and its graphical representation.
     data = pd.read_csv("/project.csv.csv")
print(data)
     team_count = data["Name"].value_counts()
     percentage = (team_count / len(data)) * 100
2.Segregate employees based on their positions within the company.
   position = data["Position"].value_counts()
   print("Position Distribution:")
   print(position)
3. Identify the predominant age group among employees
   ages = data["Age"].value_counts()
  print("Age Group Distribution:")
  print(ages)
4.Discover which team and position have the highest salary expenditure.
  highestsalary = data.loc[data["Salary"].idxmax()]
  print("Highest Salary Expenditure:")
  print(highestsalary)
5. Investigate if there's any correlation between age and salary, and represent it visually.
  correlation = data["Age"].corr(data["Salary"])
  print("Correlation Coefficient:")
  print(correlation)
These questions are analyzed using python pandas library,matplotlib&seaborn library.
The graphs are represented using matplotlib and seaborn library.
in this project I learned how to import python code in Github and how to write a breif explanation about the project.






