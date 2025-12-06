# Ex03 Places Around Me
## Date: 29-11-2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
mapapp.html
<html>
    <head>
        <title>GMAP</title>
    </head>
    <body>
        <h1 align="center">THIRUVALLUR</h1>
        <h2 align="center">Manigandan S 25004934 </h2>
        <img src="Screenshot 2025-11-26 114747.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="PS4 Veg Restaurant" title="PS4 Veg Restaurant" href="hotet.html" coords="611,677,836,763" shape="rect">
            <area target="" alt="Arulmigu Veeraraghava Perumal Temple" title="Arulmigu Veeraraghava Perumal Temple" href="Temple.html" coords="892,493,150" shape="circle">
            <area target="" alt="Nithya Amirtham" title="Nithya Amirtham" href="Hotel.html" coords="440,585,641,657" shape="rect">
            <area target="" alt="D Mart" title="D Mart" href="dmart.html" coords="1308,244,105" shape="circle">
            <area target="" alt="Rakki Cinemas" title="Rakki Cinemas" href="cinema.html" coords="1239,487,1356,552,1354,590,1171,597,1164,528" shape="poly">
        </map>
    </body>
</html>

cinema.html
<html>
    <head>
        <title> Rakki Cinemas</title>
    </head>
    <body bgcolor="read">
        <h1 align="center" > THIRUVALLUR</h1>
        <h2 align="center">Rakki Cinemas</h2>
        Rakki Cinemas in Thiruvallur is a multiplex with 4 screens, 1,754 seats, 4K Dolby Atmos, and offers comfortable viewing with push-back seats and online booking. Located in Mgm Nagar, the cinema is a popular spot with high foot traffic, ample parking, and an array of amenities beyond movies like food and potentially future entertainment options. 
        Address: Kakkalur Rd, opp. to vinayagar temple, MGM Nagar, Tamil Nadu 602001
    </body>
</html>

dmart.html
<html>
   <head>
        <title> DMART Thiruvallur</title>
   </head>
   <body bgcolor="cyan">
    <h1 align="center">THIRUVALLUR </h1>
    <h2 align="center"> DMART</h2>
    Location: The D-Mart is situated in Chinnaekkadu, Tiruvallur.
Industry: It is a prominent establishment in the grocery store category within Tiruvallur.
Product Range: The store offers a diverse selection of products, including groceries, kitchen appliances, crockery, apparel, footwear, and baby products.
Customer Focus: The business emphasizes customer satisfaction and aims to provide value for money to customers.
Accessibility: It is easy to commute to, with various modes of transport readily available.
Services: In addition to the physical store, an online grocery platform, D-Mart Ready, is available for online orders and delivery
   </body>
</html>

hotel.html
<html>
    <head>
        <title>Nithya Amirtham</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center"> THIRUVALLUR</h1>
        <h2 align="center">Nithya Amirtham</h2>
        Nithya Amirtham lives up to its reputation as a famous sweet shop in Thiruvallur. Even ordering from outside the city via their website, the freshness and taste are unparalleled. Thiruvallur sweet at its best, anywhere in India
        Service options: 
All you can eat
 · Vegan options
 · Kids' menu
Address: No.5/4, CV Naidu Rd, Selai, Tamil Nadu 602001
Phone: 075399 62555
    </body>
</html>

hotet.html
<html>
    <head>
        <title>PS4 Veg Restaurant </title>
    </head>
    <body bgcolor="orange">
        <h1 align="center"> THIRUVALLUR</h1>
        <h2 align="center">PS4 Veg Restaurant</h2>
        "Tiruvallur PS4" likely refers to PS4 Pure Veg Restaurant, a restaurant chain affiliated with Perambur Sri Srinivasa Sweets & Snacks. It's a vegetarian restaurant in the Thiruvallur area that serves a wide variety of South Indian and North Indian dishes, biryanis, and other items. The company is known for its quality, has been around since 1981, and has many branches in the Chennai and Tiruvallur regions. 
        Service options: 
All you can eat
 · Vegan options
 · Kids' menu
Located in: PS4 Perambur Sri Srinivasa Sweets & Snacks
Address: No: 4/3A, C.V. Naidu salai 205 national Highways Tiruvallur, near IOB bank, Chennai, Tamil Nadu 602001
Phone: 078239 99943

    </body>
</html>

Temple.html
<html>
    <head>
        <title> Arulmigu Veeraraghava Perumal Temple</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center"> THIRUVALLUR</h1>
        <h2 align="center">Arulmigu Veeraraghava Perumal Temple</h2>
        Sri Vaidhya Veeraraghava Swamy Temple at Thiruvallur is one of the 108 Sri Vaishnavaite Thiruthalams. The sthala is also the 21st Thiruthalam in Thondainadu, and is praised in verses by two of the twelve Alvars - Thirumangai Alvar and Thirumzhisai Alvar which are referred to as Divya Prabandham.Swamy Sri Desikan has also praised the deity in his Kingruhesa Stuthi.
        Veeraraghava Swamy Temple is a temple dedicated to the Hindu god Vishnu, located in Tiruvallur, Chennai Metropolitan City, an area and headquarters in Tiruvallur district in the South Indian state of Tamil Nadu
        Address: Bazaar Street, Sannathi St, MGM Nagar, Tamil Nadu 602001
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (67).png>)
![alt text](<Screenshot (62).png>)
![alt text](<Screenshot (63).png>)
![alt text](<Screenshot (64).png>)
![alt text](<Screenshot (65).png>)
![alt text](<Screenshot (66).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
