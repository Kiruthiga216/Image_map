# Ex04 Places Around Me
# Name:Kiruthiga.B
# Reg.no:212224040160
# Date:11/04/2025
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
college.html

<html>
<head>
<title></title>
</head>
<body bgcolor="LightYellow">
<h1 align="center">
<font color="Maroon"><b>Chidambaram</b></font>    
</h1>
<h3 align="center">
<font color="Maroon"><b></b></font>    
</h3>
<hr size="3" color="MidnightBlue">
<p align="justify">
<front face="Georgia" size="S">
   " Established in 1985 as Rajah Muthiah Medical College within Annamalai University, the institution is now known as Government Cuddalore Medical College and Hospital. In January 2021, it was transferred to the Health and Family Welfare Department of the Government of Tamil Nadu, aligning its fee structure with other state-run medical colleges."

</p> 
</body>
</html>


temple.html

<html>
<head>
<title>Thillai Nataraja Temple Chidambaram</title>
</head>
<body bgcolor="LightYellow">
<h1 align="center">
<font color="Maroon"><b>Chidambaram</b></font>    
</h1>
<h3 align="center">
<font color="Maroon"><b>Thillai Nataraja Temple Chidambaram</b></font>    
</h3>
<hr size="3" color="MidnightBlue">
<p align="justify">
<front face="Georgia" size="S">
"​Thillai Nataraja Temple, located in Chidambaram, Tamil Nadu, is a renowned Hindu temple dedicated to Lord Shiva in his Nataraja form, symbolizing the cosmic dance of creation and destruction. The temple complex is notable for its expansive size, intricate architecture, and cultural significance, serving as a pivotal center for both spiritual worship and classical performing arts."
</front>
</p> 
</body>
</html>
uni.html

<html>
<head>
<title>Faculty Of Agriculture,Annamalai University</title>
</head>
<body bgcolor="LightYellow">
<h1 align="center">
<font color="Maroon"><b>Chidambaram</b></font>    
</h1>
<h3 align="center">
<font color="Maroon"><b>Faculty Of Agriculture,Annamalai University</b></font>    
</h3>
<hr size="3" color="MidnightBlue">
<p align="justify">
<front face="Georgia" size="S">
"Established in 1951, the Faculty of Agriculture at Annamalai University in Chidambaram, Tamil Nadu, offers undergraduate and postgraduate programs in agriculture and horticulture. The faculty comprises nine departments, including Agronomy, Soil Science and Agricultural Chemistry, Genetics and Plant Breeding, Microbiology, Plant Pathology, Entomology, Agricultural Economics, Horticulture, and Animal Husbandry. "
</front>
</p> 
</body>
</html>

farm.html

<html>
<head>
<title>Krish Garden Farm Resorts</title>
</head>
<body bgcolor="LightYellow">
<h1 align="center">
<font color="Maroon"><b>Chidambaram</b></font>    
</h1>
<h3 align="center">
<font color="Maroon"><b>Krish Garden Farm Resorts</b></font>    
</h3>
<hr size="3" color="MidnightBlue">
<p align="justify">
<front face="Georgia" size="S">
"Krish Garden Farm Resort in Chidambaram offers a serene, nature-immersed experience with amenities like ponds, diverse birdlife, and a children's play area. Located near the railway station, it provides comfortable rooms, a swimming pool, and proximity to attractions such as the Thillai Nataraja Temple and Pichavaram Mangrove Forest."
</front>
</p> 
</body>
</html>


amman.html
<html>
<head>
<title>Thillai Kaali Amman kovil</title>
</head>
<body bgcolor="DarkGrey">
<h1 align="center">
<font color="DarkSlateBlue"><b>Chidambaram</b></font>    
</h1>
<h3 align="center">
<font color="blue"><b>Thillai Kaali Amman kovil</b></font>    
</h3>
<hr size="3" color="#FF8C00">
<p align="justify">
<front face="Georgia" size="S">
"Thillai Kaali Amman Kovil, located in Chidambaram, Tamil Nadu, is a revered temple dedicated to Goddess Kaali, symbolizing divine feminine energy. It is believed that the temple marks the site where Goddess Kaali competed in a cosmic dance with Lord Shiva."
</front>
</p>
</body>
</html>

map.html


<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Chidambaram</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>Kiruthiga.B (212224040160)</b></font>
</h2>
<center>
<img src="map.png" usemap="#MyCity" height='610' width='1450'>
<map name="MyCity">
<area target="" alt="Thillai Kaali Amman kovil" title="Thillai Kaali Amman kovil" href="amman.html" coords="827,37,969,67" shape="rect">
<area target="" alt="Krish Garden Farm Resorts" title="Krish Garden Farm Resorts" href="krish.html" coords="1072,643,60" shape="circle">
<area target="" alt="Faculty Of Agriculture,Annamalai University" title="Faculty Of Agriculture,Annamalai University" href="uni.html" coords="1642,621,1739,728" shape="poly">
<area target="" alt="Thillai Nataraja Temple Chidambaram" title="Thillai Nataraja Temple Chidambaram" href="temple.html" coords="792,299,985,286" shape="rect">
<area target="" alt="Goverment Medical College" title="Goverment Medical College" href="college.html" coords="1560,321,1693,334" shape="rect">
</map>
</center>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-04-11 223712.png>) 
![alt text](<Screenshot 2025-04-11 223126.png>)
![alt text](<Screenshot 2025-04-11 223202.png>)
![alt text](<Screenshot 2025-04-11 223429.png>)
![alt text](<Screenshot 2025-04-11 223454.png>)
![alt text](<Screenshot 2025-04-11 223228.png>)


# RESULT
The program for implementing image maps using HTML is executed successfully.
