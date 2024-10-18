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
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![328015283-c66f5c32-89e6-4b10-b7a7-71af59e2c247](https://github.com/user-attachments/assets/b57d4498-157f-41d0-b982-30dc309f6ba6)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![328015338-a608dd72-b67b-4022-aa78-371b1619d43c](https://github.com/user-attachments/assets/6e47808d-210b-47bb-bc7e-82943399dac3)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![328015383-a00621d6-3311-4fa2-acf5-391c2acd66cf](https://github.com/user-attachments/assets/9aaef014-2efe-48d9-bc59-d508201bb763)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![328015427-5dee0bba-9ea2-45c8-98f9-4d07e83cc8b7](https://github.com/user-attachments/assets/4e25fc59-d57c-4052-a9ad-d7c0e7004615)
```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```
![328015477-6012f3f0-6f87-4cf8-bd6e-5ba507a1b06d](https://github.com/user-attachments/assets/3ba44aa9-c936-48ab-b5e5-812cae6e5e2c)
```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![328015506-bb1912de-70f1-4707-b42c-360d1d3fe09f](https://github.com/user-attachments/assets/8575585e-45d1-4cff-a27a-05f7eaf9e803)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![328015530-f13513f0-5c94-4933-864e-287b241a7927](https://github.com/user-attachments/assets/371d9253-5b28-4d08-b5fb-271bc7a390a1)
```
y
```
![328015569-a870782e-3cd4-4d44-a653-4ab7cd289888](https://github.com/user-attachments/assets/5d1fdb8b-f2f3-4c88-a161-7c24c423d36c)
```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![328015605-d201a979-810e-4735-a49c-8ef3c57f6a74](https://github.com/user-attachments/assets/550c5481-eb41-4c41-a640-b3c14c24741d)
```
y=x*x
y
```
![328015625-809779da-a186-4e40-b85b-2760598b20b9](https://github.com/user-attachments/assets/076f2b58-1f10-4af5-bf0f-2fb77074c137)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![328015651-d7751af4-13ae-490a-a352-4ab023c36fc1](https://github.com/user-attachments/assets/d2c18396-c9c5-4572-b249-7d15e32f6c12)
```
np.pi
```
![328015682-d8c70094-b994-4503-9832-4fba61e65f9a](https://github.com/user-attachments/assets/73364814-2c3a-4102-8f2b-f5bf34aa017a)
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![328015725-57d1482c-2b3b-4a7c-9cf8-12980dd73b17](https://github.com/user-attachments/assets/0354a4d2-7271-49f2-8336-b3b04efcfc9b)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```
![328015790-6f1efd80-4e8d-45bb-bd8a-97e7cfeac3bd](https://github.com/user-attachments/assets/3b876f09-466d-46a1-a6e3-d57d8d5a40a3)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![328015815-3dee5ad9-ae9e-4bab-9112-ecb29018bc9e](https://github.com/user-attachments/assets/42c5cf94-4273-4dc7-83f4-7a456e3dc951)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![328015838-1e1a02fb-7398-44e6-b06e-35c1db335bb0](https://github.com/user-attachments/assets/d7152531-bde3-4e5d-be09-50b1db1dca20)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![328015865-2631e29c-cc9b-4d12-9f07-0bd21b2b9db5](https://github.com/user-attachments/assets/2ed719fa-85d5-46c5-a041-876a3eab8cf0)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![328015887-0c306853-c5be-4dca-a879-0dfc4a30bff8](https://github.com/user-attachments/assets/52849a1d-cc95-4608-840e-aeed7b5d00c0)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![328015920-70bf4782-2179-44ea-aa7d-7dba6eebf101](https://github.com/user-attachments/assets/3a77295a-0c2a-45c6-99f8-a9b13d1c4080)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![328015945-0f940dad-69e3-4c11-bca0-838d3c32ea79](https://github.com/user-attachments/assets/f842defe-1581-4d3b-91a3-8cb676d9f436)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![328015969-04c6c150-926c-4f18-adf4-cf8273c26d01](https://github.com/user-attachments/assets/8a9eda52-43ee-49fe-8932-6df1cf87da9c)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![328015992-ecf37e01-15ea-4221-bc99-df88d93bdcb3](https://github.com/user-attachments/assets/e11e6da5-a1ea-4742-9f2b-fea9ae776f49)

# Result:
 Thus, The implementation of data visualization using matplotlib has been successfully verified.
