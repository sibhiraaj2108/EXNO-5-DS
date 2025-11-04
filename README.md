# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
 import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
```

```
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
```
<img width="758" height="692" alt="image" src="https://github.com/user-attachments/assets/4a755522-6e46-4c9d-9688-dfbc2f7ac788" />

```
 student=['A','B','C','D']
 attendence=[90,85,73,88]
 plt.plot(attendence,student)
 plt.xlabel('Attendence')
 plt.ylabel('Student name')
 plt.show()
```

<img width="616" height="441" alt="image" src="https://github.com/user-attachments/assets/56946a0a-8d82-43ee-abf6-97d6842c9987" />

```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
```

<img width="612" height="413" alt="image" src="https://github.com/user-attachments/assets/8cd51263-6bce-4bc6-b765-75c3e677fea8" />

```
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```

<img width="558" height="449" alt="image" src="https://github.com/user-attachments/assets/8e4bd7b8-5365-4087-9cc4-ee0d5c31f9fd" />

```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

<img width="446" height="410" alt="image" src="https://github.com/user-attachments/assets/3a5f47b8-c015-4a1c-952b-58ca4ff10f4f" />

```
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```

<img width="436" height="396" alt="image" src="https://github.com/user-attachments/assets/25515042-49ce-475e-864c-b1d9ac920922" />

```
 x = [1, 2, 3, 4, 5]
 y1 = [10, 12, 14, 16, 18]
 y2 = [5, 7, 9, 11, 13]
 y3 = [2, 4, 6, 8, 10]
 plt.fill_between(x, y1, color='blue')
 plt.fill_between(x, y2, color='green')
 plt.plot(x, y1, color='red')
 plt.plot(x, y2, color='black')
 plt.legend(['y1','y2'])
 plt.show()
```

<img width="559" height="415" alt="image" src="https://github.com/user-attachments/assets/ee6cc264-54b6-4b00-afd8-3483e9a01b21" />

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```

<img width="562" height="444" alt="image" src="https://github.com/user-attachments/assets/32037a42-6d6c-45d4-916f-a7506adfb64a" />

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```

<img width="537" height="406" alt="image" src="https://github.com/user-attachments/assets/82dcadc7-f889-477c-b7ab-a4293f58c0d7" />

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```

<img width="649" height="365" alt="image" src="https://github.com/user-attachments/assets/13ceb069-862f-49f2-bcfc-c300f0bad3d0" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
<img width="558" height="446" alt="image" src="https://github.com/user-attachments/assets/9d883c30-d496-4848-bd75-72b10b5665e7" />

# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.


