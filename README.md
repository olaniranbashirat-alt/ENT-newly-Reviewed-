# ENT-newly-Reviewed-
Student Performance Analyser


#STUDENT PERFORMANCE ANALYZER
username = 'Bashirat Olaniran'
userage = "25"
department = "Mathematics Education"
m = int("90")
p = int("98")
s = int("92")
total = int(90 + 98 + 92)
average_score = float(total / 3)
highest_score = max( m, p, s)
lowest_score = min(m, p, s)
if average_score >= 50:
     passed = "True"
if average_score <50:
     passed = "False"
print ("STUDENT PERFORMANCE ANALYZER")
print("Name:", username)
print('Age:', userage)
print("Department:",department)
print('Mathematics:', m)
print('Python:', p)
print("Statistics:", s)
print("Total:", total)
print("Average Score:", average_score)
print("Highest Score:", highest_score)
print("Lowest Score:", lowest_score)
print("Passed:", passed)