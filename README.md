# insuarance_data_seaborn_pandas
## Show the counts of categorical insurance data using Seaborn and Python pandas
# Step 1: Import libraries
* import pandas as pd
* import seaborn as sns
* import matplotlib.pyplot as plt

# Step 2: Create a DataFrame
# Read data from the CSV files
* chit_data= pd.read_csv("C:\\Users\\user\\Desktop\\python-files\\chidata_for_assignment_5 .csv")
* print(chit_data.head())
# Run the code - you get output like this

![image](https://user-images.githubusercontent.com/17750481/113332178-82a92f00-9329-11eb-8a12-1d9d04cfd218.png)

# Display Dataframe Columns
* chit_data.columns
* ![image](https://user-images.githubusercontent.com/17750481/113332373-c3a14380-9329-11eb-88d4-3007a02bfa5c.png)
# Step 3: Print/Display the Column Information limit using the head- for quick testing return the first N rows
![image](https://user-images.githubusercontent.com/17750481/113332542-f51a0f00-9329-11eb-9562-2ad13dabc621.png)
# Print/Display the Column Information
![image](https://user-images.githubusercontent.com/17750481/113332921-8093a000-932a-11eb-9e74-ddbd93108928.png)
# visualize categorical variables gender and insuarance with heatmaps
# see visually the contingency tables using seaborn heatmaps
plt.figure(figsize=(12,8)) 
ax=sns.heatmap(data_crosstab, annot=True, cmap="YlGnBu")
ax.set_title('Python Advances Class Insurances')
plt.show()

![image](https://user-images.githubusercontent.com/17750481/113336827-9d7ea200-932f-11eb-8ed9-c8f5097bc835.png)


