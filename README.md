# Ex04 Places Around Me
## Date: 14/11/25

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
map.html
```
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Nagercoil</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Jayasree T S(24900147)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="700,250,850,400" href="hospital.html" title="Asaripallam Medical Hospital">
<area shape="circle" coords="600,230,45"    href="home.html"   title="My Home Town">
<area shape="circle" coords="210,150,200"    href="temple.html"  title="Arulmigu Mandaikadu Bhagavati Temple">
<area shape="rect" coords="250,50,250"     href="beach.html"   title="Lemur Beach">
<area shape="rect" coords="1000,600,900,500"    href="church.html"     title="st.Micheal's Church">
</map>
</center>
</body>
</html>
```
beach.html
```
<html>
    <head>
      <title>My Home Town</title>  
    </head><h
    <body bgcolor="purple">
      <h1 align="center">
        <font color="red"><b>Nagercoil</b></font>
      </h1>  tml>
      <h3 align="center">
        <font color="black"><b>Lemur Beach</b></font>
      </h3>
      <hr size="3" color="red">
      <p align="justify">
        <font face="Georgia" size="5">
        Lemur Beach is located in muttom in nagercoil.It is a Tourist place,where foreigners come to visit that beach.
        The children's used to collect shells and play  with that.

      </p>
    </body>
</html>
```
church.html
```
<html>
    <head>
      <title>My Home Town</title>  
    </head>
    <body bgcolor="orange">
      <h1 align="center">
        <font color="red"><b>Nagercoil</b></font>
      </h1>  
      <h3 align="center">
        <font color="black"><b>st.Micheal Church</b></font>
      </h3>
      <hr size="3" color="red">
      <p align="justify">
        <font face="Georgia" size="5">
            st.Micheal church is located in rajavoor in nagercoil.It is the famous roman catholic christian church in nagercoil,where most of the 
            people go and pray for their lives.that church is filled with full of peace and positive thinking.
            

      </p>
    </body>
</html>
```
home.html
```
<head>
      <title>My Home Town</title>  
    </head>
    <body bgcolor="pink">
      <h1 align="center"><html>

        <font color="red"><b>Nagercoil</b></font>
      </h1>  
      <h3 align="center">
        <font color="black"><b>Nagercoil-My Home Town</b></font>
      </h3>
      <hr size="3" color="red">
      <p align="justify">
        <font face="Georgia" size="5">
             My favourite place is my home town.My home town is nearby seashore areas .So I often go to seashores,
             and i like my home town very much.

      </p>
    </body>
</html>
```
hospital.html
```
<html>
    <head>
      <title>My Home Town</title>  
    </head>
    <body bgcolor="cyan">
      <h1 align="center">
        <font color="red"><b>Nagercoil</b></font>
      </h1>  
      <h3 align="center">
        <font color="blue"><b>Asaripallam Medical Hospital</b></font>
      </h3>
      <hr size="3" color="red">
      <p align="justify">
        <font face="Georgia" size="5">
            The Hospital is located at asaripallam in nagercoil.it is also a government medical college.It is a multispeciality hospital.
            It provides special care and doctors are very experienced to handle the patients.they have well inffrastructure and it is near to my home.
            It is the famous hospital in nagercoil.

      </p>
    </body>
</html>
```
temple.html
```
<html>
    <head>
      <title>My Home Town</title>  
    </head>
    <body bgcolor="yellow">
      <h1 align="center">
        <font color="black"><b>Nagercoil</b></font>
      </h1>  
      <h3 align="center">
        <font color="blue"><b>Arulmigu Mandaikadu Bhagavati Temple</b></font>
      </h3>
      <hr size="3" color="red">
      <p align="justify">
        <font face="Georgia" size="5">
        The templle's main deity is Bhagavayi amman.it has special aechitecture.it has curve paintings and stone sculptres.It is constucted by pallavas.
            


      </p>
    </body>
</html>
```



## OUTPUT
![alt text](<Screenshot 2025-11-14 155509.png>)
![alt text](<Screenshot 2025-11-14 155413.png>)
![alt text](<Screenshot 2025-11-14 155238.png>)
![alt text](<Screenshot 2025-11-14 155216.png>)
![alt text](<Screenshot 2025-11-14 155350.png>)
![alt text](<Screenshot 2025-11-14 155320.png>)



## RESULT
The program for implementing image maps using HTML is executed successfully.
