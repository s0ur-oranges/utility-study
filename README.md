# Study-Buddy
 A utility app for students containing functions like making notes , add deadlines for homeworks , create to-do lists , and finally an article summariser. To read about the article summariser , please visit 
 
## Overview
 
 The home page appears as such in the browser window ,
 
 
 ![Screenshot (28)](https://user-images.githubusercontent.com/91944643/183061155-39f34be3-3baf-4b3c-a5b0-7f231d3714e0.png)
 
 
 







 
 There are 4 different options present , notes , homeowork , adding tasks , and article summariser.
 
 Notes: 
 
 
 ![Screenshot (31)](https://user-images.githubusercontent.com/91944643/183062396-c561a41e-66d6-4fe4-a01f-deca7507e7c5.png)

![Screenshot (32)](https://user-images.githubusercontent.com/91944643/183062420-45dcbb3c-8ee1-4224-8c97-cea9097b72cf.png)

 
 
 Homework:
 
  ![Screenshot (33)](https://user-images.githubusercontent.com/91944643/183061674-7a6bf89f-669c-4ff6-b457-2d143f447554.png)
  
 

 
 
 Todos:
 
 ![Screenshot (34)](https://user-images.githubusercontent.com/91944643/183062344-b9f13ace-539b-4c82-b4de-c4b39da8f6fa.png)

 
 
 
 
Article summariser:


![image](https://user-images.githubusercontent.com/91944643/183048673-1f033f87-422f-43ee-b23d-4cc656f55c9c.png)



Here is the sample text article inside the input :
```
There are numerous benefits of recycling. Recycling helps recover resources that can be used to make use of them in a different way. New products can be made by recycling general Waste. Solid Wastes like wood, glass, plastic, electronic devices, clothing and leather items can be t decompose easily and can pile up as a landfill for many years, sometimes ending up in the ocean and killing animals who choke on them accidentally. The use of such products that are harmful to everyone should be Reduced. Alternative options have been developed to Reduce the use of plastic such as jute bags instead of polythene bags, paper straws and packaging to be used in place of those made of plastic are a few to name.

```


By clicking on summarise text , the summary is generated as follows (the sentences are printed alongwith the scores) 

```

0.33: There are numerous benefits of recycling.

0.20: The use of such products that are harmful to everyone should be Reduced.

0.17: New products can be made by recycling general Waste.

0.11: Recycling helps recover resources that can be used to make use of them in a different way.

0.06: Alternative options have been developed to Reduce the use of plastic such as jute bags instead of polythene bags, paper straws and packaging to be used in place of those made of plastic are a few to name.


```





![image](https://user-images.githubusercontent.com/91944643/183048327-e6082b33-c776-4e02-b0d4-783163e70fea.png)



For your own purpose , replace the default text with your own in the input , and click again on summarise text button.





Profile Page

![Screenshot (29)](https://user-images.githubusercontent.com/91944643/183062495-0573efce-c523-4d30-a9c0-435cb32f2ab5.png)


Login/Logout


![Screenshot (36)](https://user-images.githubusercontent.com/91944643/183062248-e6cad79d-8988-4ccd-8d61-03b5d33b22a0.png)



![Screenshot (35)](https://user-images.githubusercontent.com/91944643/183062293-f3f9134f-f59f-4be0-8b03-90454686889f.png)



## How to run this in your local computer?

1)Download source code

2)After downloading , open the command prompt and navigate to main directory and activate a virtual env by running the command

```mkvirtualenv {name of your virtual env} ```

3)After activating virtual environment , run 
``` pip install django ```

4) Also run ```pip install django-crispy-forms```

5)Then run this command to open the website in your own localhost
```python manage.py runserver```

6)The app should open as follows:


 ![Screenshot (28)](https://user-images.githubusercontent.com/91944643/183061155-39f34be3-3baf-4b3c-a5b0-7f231d3714e0.png)



