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
import matplotlib.pyplot as plt

x_values = [ 0, 1, 2, 3, 4, 5 ] y_values = [ 0, 1, 4, 9, 16, 25]

plt.plot(x_values, y_values)

plt.show()

```

<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/3b367425-592f-4b99-910c-62f8e0a106ed" />


```
import matplotlib.pyplot as plt

x = [1, 2, 3] y = [2, 4, 1]

plt.plot(x, y)

plt.xlabel('x - axis') plt.ylabel('y - axis') plt.title('My first graph!')

plt.show()

```

<img width="771" height="563" alt="image" src="https://github.com/user-attachments/assets/9a9df62d-6793-4589-a445-09b108771738" />

```
import matplotlib.pyplot as plt
x1 = [1, 2, 3]

y1 = [2, 4, 1]

plt.plot(x1, y1, label="line 1")

x2 = [1, 2, 3]

y2 = [4, 1, 3]

plt.plot(x2, y2, label = "line 2")

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('Two lines on same graph!')

plt.legend()

plt.show()

```


<img width="771" height="563" alt="image" src="https://github.com/user-attachments/assets/0d5828c7-e742-4b0d-8224-aa31aaf375a4" />


```

import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5, 6]

y = [2, 4, 1, 5, 2, 6]

plt.plot(x, y, color='green', linestyle='dashed', linewidth = 3, marker='o', markerfacecolor='blue', markersize=12)

plt.ylim(1, 8)

plt.xlim(1, 8)

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('Some cool customizations!!')

plt.show()

```


<img width="758" height="563" alt="image" src="https://github.com/user-attachments/assets/c51d5a01-cb08-48f0-8d5e-28a67a1d0acb" />

```
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]

plt.plot(yield_apples)

```


<img width="769" height="505" alt="image" src="https://github.com/user-attachments/assets/29a037e8-acf6-45bb-bef3-aff676c3ec2a" />

```
years = range(2000, 2012)

apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]

oranges = [0.962, 0.941, 0.930, 0.923, 0.918, 0.908, 0.907, 0.904, 0.901, 0.898, 0.9, 0.896,0.8]

plt.plot(years, apples)

plt.plot(years, oranges)

plt.xlabel('Year')

plt.ylabel('Yield (tons per hectare)')

```


<img width="769" height="505" alt="image" src="https://github.com/user-attachments/assets/f47b1132-15c5-482c-9576-a399a3025fff" />


```
import matplotlib.pyplot as plt

years = range(2000, 2012)

apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931, 0.934, 0.936, 0.937, 0.9375, 0.9372, 0.939]

oranges = [0.962, 0.941, 0.93, 0.923, 0.918, 0.908, 0.907, 0.904, 0.901, 0.898, 0.9, 0.896]

plt.plot(years, apples)

plt.plot(years, oranges)

plt.xlabel('Year')

plt.ylabel('Yield (tons per hectare)')

plt.title('Crop Yields in Kanto')

plt.legend(['Apples', 'Oranges'])

plt.show()


```


<img width="451" height="299" alt="image" src="https://github.com/user-attachments/assets/ae564fe8-9cf7-43b9-99bb-ec3b3e70d552" />

```

import matplotlib.pyplot as plt

x_values = [0,1,2,3,4,5]

y_values = [0,1,4,9,16,25]

plt.scatter(x_values, y_values, s=30, color="blue")

plt.show()

```


<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/f8b0c9f7-ca91-4847-bf73-adc421bdbc3e" />

```

import matplotlib.pyplot as plt

x = [1,2,3,4,5,6,7,8,9,10]

y = [2,4,5,7,6,8,9,11,12,12]

plt.scatter(x, y, label="stars", color="green", marker="*", s=30)

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('My scatter plot!')

plt.legend()

plt.show()

```


<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/786ec9f3-4da5-4af1-addb-3086e53ed830" />

```
import matplotlib.pyplot as plt import numpy as np import pandas as pd

x = np.arange(0,10) y = np.arange(11,21)

x
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
 plt.ylabel('Y axis')
 plt.title('Graph in 2D')
 plt.savefig('Test.png')

```


<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/f5773e2d-5d80-4df7-9a98-9eb70b2d0694" />


```

y = x*x

plt.plot(x,y,'g*',linestyle='dashed',linewidth=2, markersize=12)
 plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')

```


<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/d85dc7ef-138b-49aa-b0f6-8064b4165646" />

```

plt.subplot(2,2,1) plt.plot(x,y,'r--') plt.subplot(2,2,2) plt.plot(x,y,'g*--') plt.subplot(2,2,3) plt.plot(x,y,'bo') plt.subplot(2,2,4) plt.plot(x,y,'go')

```


<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/56e8c6a7-b368-4e15-9c7a-7a3790a8b310" />

```
x = np.arange(0, 4 * np.pi, 0.1)
y = np.sin(x)
plt.title("sine wave form")

plt.plot(x, y) plt.show()

```


<img width="773" height="536" alt="image" src="https://github.com/user-attachments/assets/ad066a5a-36f0-46b3-961a-8eee075555b8" />

```

import matplotlib.pyplot as plt

import numpy as np

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


<img width="756" height="505" alt="image" src="https://github.com/user-attachments/assets/9c6124e4-d3fa-4096-9cba-c308a25592da" />

```

plt.stackplot(x, y1, y2, y3, labels=['Line 1', 'Line 2', 'Line 3'])

plt.legend(loc='upper left')

plt.title('Stacked Line Chart')

plt.xlabel('X-axis')

plt.ylabel('Y-axis')

plt.show()

```


<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/c452a5ea-4019-45ff-a634-d18b28e6d45b" />


```

import numpy as np import matplotlib.pyplot as plt from scipy.interpolate import make_interp_spline

x = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10]) y = np.array([2, 4, 5, 7,8, 8, 9, 10, 11, 12])

spl = make_interp_spline(x, y)

x_smooth = np.linspace(x.min(), x.max(), 100)

y_smooth = spl(x_smooth)

plt.plot(x, y, 'o', label='data') plt.plot(x_smooth, y_smooth, '-', label='spline') plt.legend() plt.show()

```


<img width="737" height="505" alt="image" src="https://github.com/user-attachments/assets/b60c8156-f63b-4fa7-b6ee-fef140f23ade" />


```

import matplotlib.pyplot as plt values = [5, 6, 3, 7, 2] names = ["A", "B", "C", "D", "E"]

plt.bar(names, values, color="green") plt.show()

```


<img width="725" height="505" alt="image" src="https://github.com/user-attachments/assets/84c8c22d-8982-4198-b583-0948f09a7b86" />

```
import matplotlib.pyplot as plt values = [5, 6, 3, 7, 2] names = ["A", "B", "C", "D", "E"]

plt.barh(names, values, color="yellowgreen") plt.show()

```


<img width="727" height="505" alt="image" src="https://github.com/user-attachments/assets/bd59ed8c-cefc-4c4e-b4a0-76af7759ebe4" />

```

import matplotlib.pyplot as plt

height = [10, 24, 36, 40, 5]

names = ['one', 'two', 'three', 'four', 'five']

c1 = ['red', 'green'] c2 = ['b', 'g'] # we can use this for color plt.bar(names, height, width=0.8, color=c1)

plt.xlabel('x - axis')

plt.ylabel('y - axis')

plt.title('My bar chart!')

plt.show()

```


<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/0975ef24-7815-4afe-9f36-26008134211c" />

```

x = [2,8,10] y = [11,16,9] x2 = [3,9,11] y2 = [6,15,7] plt.bar(x, y, color='r') plt.bar(x2, y2, color = 'g') plt.title('Bar graph') plt.ylabel('Y axis') plt.xlabel('X axis') plt.show()

```



<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/33514f62-3eac-4b99-b5e9-e506c22c75ec" />

```
import matplotlib.pyplot as plt

ages = [2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]

range = (0, 100) bins = 10

plt.hist(ages, bins, range, color='green', histtype='bar', rwidth=0.8)

plt.xlabel('age')

plt.ylabel('No. of people')

plt.title('My histogram')

plt.show()

```


<img width="752" height="563" alt="image" src="https://github.com/user-attachments/assets/f6ae9945-c1b8-465a-8eee-ea2271da7023" />

```

import matplotlib.pyplot as plt

x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]

plt.hist(x, bins = 10, color='blue', alpha=0.5) plt.show()

```


<img width="725" height="505" alt="image" src="https://github.com/user-attachments/assets/ca371985-7bea-4035-9445-0b7d8dcc535e" />


```

import matplotlib.pyplot as plt import numpy as np

np.random.seed(0) data = np.random.normal(loc=0, scale=1, size=100)

fig, ax = plt.subplots() ax.boxplot(data) ax.set_xlabel('Data') ax.set_ylabel('Values') ax.set_title('Box Plot')

plt.show()

```



<img width="768" height="563" alt="image" src="https://github.com/user-attachments/assets/47d8c2b3-d499-422b-9199-6562aed47b19" />

```

import matplotlib.pyplot as plt

activities = ['eat', 'sleep', 'work', 'play']

slices = [3, 7, 8, 6]

colors = ['r', 'y', 'g', 'b']

plt.pie(slices, labels = activities, colors=colors, startangle=90, shadow = True, explode = (0, 0, 0.1, 0), radius = 1.2, autopct = '%1.1f%%')

plt.legend() plt.show()

```



<img width="536" height="490" alt="image" src="https://github.com/user-attachments/assets/7c02db12-e3c8-4848-bab8-c522acd18d22" />


```
labels = 'Python', 'C++', 'Ruby', 'Java' sizes = [215, 130, 245, 210] colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue'] explode = (0, 0.4, 0, 0.5)

plt.pie(sizes, explode=explode, labels=labels, colors=colors, autopct='%1.1f%%', shadow=True)

plt.axis('equal') plt.show()

```


<img width="698" height="472" alt="image" src="https://github.com/user-attachments/assets/23076aaa-d8e6-4d42-bacf-d7b30a4c518a" />












# Result:
 Include your result here
