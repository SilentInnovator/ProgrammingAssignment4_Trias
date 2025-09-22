# ProgrammingAssignment4_Trias
### import matplotlib.pyplot as plt
### import pandas as pd
### import dataframe board2.xlsx using code pd.read_excel('board2.xlsx') and store it under variable df
### get the average grade of each student using code df.iloc[:, [4,5,6,7]].mean(axis=1) and store it under variable Ave
### add the average grade to the table using code df.assign(Average=Ave) and store the table under variable J
### create a dataframe where in track is constant as Instrumentation and hometown Luzon by using the code pd.DataFrame() and store it under variable Instru
### create a dataframe where in hometown is constant as Mindanao and gender Female by using the code pd.DataFrame() and store it under variable Mindy
### specify the size of the visualization by using code plt.figure(figsize=(30, 10))
### create a bar graph to show the relation between gender and average grades using code plt.bar(J['Gender'], J['Average'])
### create a bar graph to show the relation between track and average grades using code plt.bar(J['Track'], J['Average'])
### creata a bar graph to show the relation between hometown and average grades using code plt.bar(J['Hometown'], J['Average'])
