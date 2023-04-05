# Ecommers-Purchases

Hlw everyone My English is not Good 

This Data set get from kaggle 
link:

![Screenshot (5)](https://user-images.githubusercontent.com/107715043/230179346-a25d8f75-6334-4bb7-bb8a-69d42fc24685.png)
this is my file are present here i make this project using Jupyter Notebook


At first  I intert data direct kaggle 
![Screenshot (7)](https://user-images.githubusercontent.com/107715043/230179561-1c59d13f-173a-4975-95f6-13e3c653ebd8.png)

After Then this file locaton store in  a file name variable ![Screenshot (8)](https://user-images.githubusercontent.com/107715043/230179752-92f2615e-a8e4-4c76-ba8d-268e0ca2449c.png)

now i import library and show top 10 data and last 10 data in this data set




after check null value in dataset
![Screenshot (9)](https://user-images.githubusercontent.com/107715043/230180702-eb693292-696f-437b-95c3-f65199869e91.png)


after That find how many columns and row are presnt in dataset
![Screenshot (10)](https://user-images.githubusercontent.com/107715043/230180914-42c9a8f2-d249-4995-9131-473e2390489f.png)

Now Find Height and lowest price this data set
![Screenshot (11)](https://user-images.githubusercontent.com/107715043/230183598-a6d18c83-0885-4484-b8a5-8e8a598b4378.png)

NOW Find How Many people are have french using df[df['Language'] == 'fr']


now find job title contains enginner




![Screenshot (12)](https://user-images.githubusercontent.com/107715043/230184024-57f3a725-ddfa-4843-ade7-aaa42b4757fa.png)

after that find how man y people are mastercard with made a purchase above 50

 use this line : len(df[(df['CC Provider'] == 'Mastercard') & (df['Purchase Price']>50])


![Screenshot (13)](https://user-images.githubusercontent.com/107715043/230184740-c4632a33-31af-4d35-9129-186cf21a9456.png)



here i use bar of purchase during the am or pm 

using this code
<button> time = df['AM or PM"].value_counts() </button>

![Screenshot (14)](https://user-images.githubusercontent.com/107715043/230184905-c250aaa2-ec39-485e-b321-0ef0b58a10e9.png)


How Many People Have Cradit Card expires in 2020
and top  5 popular gmail providers


![Screenshot (16)](https://user-images.githubusercontent.com/107715043/230185619-d4881482-eecb-4924-908c-d235bb325614.png)


top 5 email provider  process:
 list1 = []
 for email in df['Email']:
     list1.append(email.splite('@')[1])
 
 
 df['temp'] = list1
 
 
 df['temp'].value_counts().head()
 
 
 ![Screenshot (17)](https://user-images.githubusercontent.com/107715043/230186474-3cdf547d-605d-405e-95c4-36dcd3b6323c.png)


Thank You!
