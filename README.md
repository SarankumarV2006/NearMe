Ex04 Places Around Me

Date: 30-10-2025

AIM

To develop a website to display details about the places around my house.

DESIGN STEPS

STEP 1

Create a Django admin interface.

STEP 2

Download your city map from Google.

STEP 3

Using <map> tag name the map.

STEP 4

Create clickable regions in the image using <area> tag.

STEP 5

Write HTML programs for all the regions identified.

STEP 6

Execute the programs and publish them.

CODE
```
map.html :

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Thiruvallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Adharsh Vidyardh U (24900088)</b></font>
</h3>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="80,80,300,300" href="home.html" title="">
<area shape="circle" coords="570, 230,45" href="hotel.html" title="Nithya Amirtham">
<area shape="circle" coords="640, 400,100" href="cinema.html" title="Rakki Cinemas">
<area shape="circle" coords="1120, 360, 250" href="mahal.html" title="BTM  Mahal">
<area shape="rect" coords="950, 120, 1100, 150" href="shop.html" title="D Mart">
</map>
</center>
</body>
</html>

shop.html :

<html>
<head>
<title>shivan temple</title>
</head>
<body bgcolor="white">
<h1 align="center">
<font color="black"><b>THIRUVALLUR</b></font>
</h1>
<h3 align="center">
<font color="darkblue"><b></b>D Mart</font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
D-Mart is a popular Indian retail chain offering groceries, household items, and clothing at affordable prices.
Founded by Radhakishan Damani in 2002, it operates hundreds of stores across India.
It’s known for quality products, budget-friendly deals, and heavy customer footfall.
</p>
</body>
</html>

mahal.html :

<html>
<head>
<title>MAHAL</title>
</head>
<body bgcolor="darkmagenta">
<h1 align="center">
<font color="black"><b>Thiruvallur</b></font>
</h1>
<h3 align="center">
<font color="darkblue"><b>BTM Mahal</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
BTM Mahal A/C is a well-known marriage hall and lodging facility in Thiruvallur, 
Tamil Nadu, offering a perfect blend of tradition and modern amenities. The Mahal is spacious, fully air-conditioned, 
and ideal for hosting weddings, receptions, family gatherings, cultural events, and corporate functions.
Along with the banquet hall, it also provides comfortable residency rooms for guests, ensuring convenience for those attending functions. 
The venue is appreciated for its cleanliness, ample parking space, good hospitality, and easy accessibility within the city.
</p>
</body>
</html>

hotel.html :

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>THIRUVALLUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Nithya Amirtham </b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Nithya Amirtham is an unfunded company based in Chennai (India), founded in 2007 by Parthibhan Kesavaraj. 
It operates as a Provider of traditional Indian sweets and savories, upholding values of purity and deliciousness.
Nithya Amirtham has not raised any funding yet
</p>
</body>
</html>

cinema.html:

<html>
<head>
<title>CINEMAS</title>
</head>
<body bgcolor="red">
<h1 align="center">
<font color="cyan"><b>Thiruvallur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Rakki Cinemas</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Georgia" size="5">
Rakki Cinemas in Ambattur, Chennai, is a popular four-screen multiplex known for its large seating capacity
It offers plush interiors, good sound and picture quality, and ample parking space.
However, some reviews mention varying screen quality and occasional cleanliness issues.
</body>
</html>

temple.html

<html>
<head>
<title>temple</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>THIRUVALLUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Veeraragawaswamy Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Sri Vaidhya Veeraraghava Swamy Temple at Thiruvallur is one of the 108 Sri Vaishnavaite Thiruthalams.
The sthala is also the 21st Thiruthalam in Thondainadu, and is praised in verses by two of the twelve
Alvars Thirumangai Alvar and Thirumzhisai Alvar which are referred to as Divya Prabandham
</p>
</body>
</html>
```

OUTPUT
<img width="1917" height="1146" alt="Screenshot 2025-10-24 192238" src="https://github.com/user-attachments/assets/c6ec6504-e8a0-4ed0-835d-dfef40fa4c4e" />
  
<img width="1913" height="1144" alt="Screenshot 2025-10-24 192327" src="https://github.com/user-attachments/assets/9185d5d3-edbd-4b50-8ab7-535b5beff849" />

<img width="1919" height="1065" alt="Screenshot 2025-10-27 121348" src="https://github.com/user-attachments/assets/8bcad259-67a2-4426-89e4-67bcb9aa7adc" />

<img width="1913" height="1147" alt="Screenshot 2025-10-24 192450" src="https://github.com/user-attachments/assets/b57e6b66-601f-492c-8cf9-ef73ea144fb3" />

<img width="1904" height="1143" alt="Screenshot 2025-10-24 192635" src="https://github.com/user-attachments/assets/ff9333f7-2657-4bf9-b0a2-2141afbb0ece" />

<img width="1915" height="1148" alt="Screenshot 2025-10-24 192910" src="https://github.com/user-attachments/assets/1723fed3-dc22-4bb5-8a2e-48c6d740a2da" />

RESULT
The program for implementing image maps using HTML is executed successfully.
