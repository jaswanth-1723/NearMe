# Ex04 Places Around Me
## DATE:25/10/2023
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WEB EXPERIMENT</title>
</head>
<body>
    <h1 align="center">
        <font color=""><b>CHITTOOR</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>JASWANTH NS 212220040057</b></font>
        </h3>
<center>        
<img src="Map.png" usemap="#image-map" height="650" width="1600">
</center>
<map name="image-map">
    <area shape="rectangle" coords="1043,70,1156,108" href="a.html" title="Chittoor Government Hospital">
    <area shape="rectangle" coords="1061,205,908,239" href="b.html" title="Kattamanchi Lake">
    <area shape="rectangle" coords="569,377,693,418" href="c.html" title="Vijayalakshmi Theatre">
    <area shape="rectangle" coords="968,96,913,63" href="d.html" title="Mesonical Grounds">
    <area shape="rectangle" coords="1131,49,977,19" href="e.html" title="Hotel Andra Spice">
</map>
</body>
</html>
```
```
<html>
<head>
<title>Chittoor Government Hospital</title>
</head>
<body bgcolor="white">
<h3 align="center"><font size="+3">Chittoor Government Hospital</font></h3>
<hr size="7" color="red">
<p align="justify">
<font size="+1">Here's Chittoor Government Hospital------</font>
</p>
<p>
    
    <font size="+2">Chittoor government hospital is a hospital and doctor located in Chittoor, Andhra Pradesh. The average rating of this place is 3.20 out of 5 stars based on 136 reviews. The street address of this place is 638V+V88, Church St, Thotapalyam, Chittoor, Andhra Pradesh 517001, India. It is about 4.93 kilometers away from the Siddampalli railway station.</font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>Kattamanchi Lake</title>
</head>
<body bgcolor="yellow">
<h3 align="center"><font size="+3">Kattamanchi Lake</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's Kattamanchi Lake------</font>
</p>
<p>
    
    <font size="+2">1.The tankbund around the lake is already strengthened and provided with butterfly lighting.

        2. Drains flowing into lake are diverted. As already the lake is filled with silt and lake weed, draining of the lake completely and refilling with fresh water is under process.
        
        3. Gardening around the lake along with seating arrangements will be taken up by inviting tenders.
        
        4. Boating and tourist amenities are to be created in PPP mode.
        
        Kattamanchi lake beautification will directly affect the image of Chittoor as it abetts the important RTC bus station, Railway Station etc..</font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>VijayaLakshmi Theatre</title>
</head>
<body bgcolor="cyan">
<h3 align="center"><font size="+3">VijayaLakshmi Theatre</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's VijayaLakshmi Theatre------</font>
</p>
<p>
    
    <font size="+2">Vijayalakshmi Theatre is a popular cinema hall located in Chittoor. It is one of the oldest and most iconic theatres in the city, and has been a popular destination for movie-goers for over 60 years. The theatre is known for its large screens, comfortable seating, and state-of-the-art sound system. It also has a wide variety of food and beverage options available, both inside and outside the theatre complex.

        Vijayalakshmi Theatre was originally built in the 1960s, and has undergone several renovations over the years. The most recent renovation was completed in 2023, which saw the theatre being upgraded to a multiplex with four screens. Each of the screens is equipped with the latest projection and sound technology, and offers a comfortable and immersive viewing experience.</font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>Mesonical Grounds</title>
</head>
<body bgcolor="Green">
<h3 align="center"><font size="+3">Mesonical Grounds</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's Mesonical Grounds------</font>
</p>
<p>
    
    <font size="+2">Masonical Grounds is a sports ground located in Mittoor, Chittoor, Andhra Pradesh, India. It is a popular destination for people of all ages to play sports, go for walks, and relax. The ground is well-maintained and has a variety of amenities, including a playground, a walking track, and a seating area.

        Here is some more information about Masonical Grounds:
        
        It is a 0.3 mile (1,000-step) route located near Mittoor, Chittoor, India.
        This route has an elevation gain of about 0 ft and is rated as easy.
        It is a popular destination for walking, running, and playing sports.
        The ground is well-maintained and has a variety of amenities, including a playground, a walking track, and a seating area.</font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>Hotel Andra Spice</title>
</head>
<body bgcolor="Orange">
<h3 align="center"><font size="+3">Hotel Andra Spice</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's Hotel Andra Spice ------</font>
</p>
<p>
    
    <font size="+2">The restaurant is located in a prime location in the heart of Chittoor, and is easily accessible by public transportation. It is also surrounded by a variety of shops and other amenities, making it a convenient one-stop destination for a meal.

        Andhra Spice Hotel has a spacious and well-lit dining area, which can accommodate large groups. The restaurant also has a private dining area for special occasions.
        
        The restaurant's menu features a wide variety of Andhra dishes, including:
        
        Biryani: Andhra Spice Hotel is known for its biryani, which is made with fresh, high-quality ingredients. The biryani is cooked to perfection and is served with all the traditional accompaniments, such as raita, dalcha, and mirchi ka salan.
        Seafood: Andhra Spice Hotel also offers a wide variety of seafood dishes, such as fish curry, shrimp biryani, and crab masala. The seafood is always fresh and is cooked to perfection.
        Vegetarian options: Andhra Spice Hotel also offers a variety of vegetarian options, such as paneer tikka masala, vegetable korma, and dal makhani. The vegetarian dishes are just as delicious as the non-vegetarian options.
        In addition to its main dishes, Andhra Spice Hotel also offers a variety of appetizers, side dishes, and desserts. The appetizers include chicken lollipop, fish fry, and onion pakora. The side dishes include naan, roti, and paratha. The desserts include gulab jamun, rasmalai, and ice cream.</font>
</p>
</body>
</html>
```

## OUTPUT
![mappp](https://github.com/jaswanth-1723/NearMe/assets/127680667/6a6cce4b-59b9-4264-bc3b-00fd58bc67fd)
![a](https://github.com/jaswanth-1723/NearMe/assets/127680667/438c9b9b-681a-48d3-b11f-38346d65434a)
![b](https://github.com/jaswanth-1723/NearMe/assets/127680667/d94bf5ba-6e91-4fd0-b040-193531814015)
![c](https://github.com/jaswanth-1723/NearMe/assets/127680667/5cd4689d-e4e6-4d27-87d1-60cc0ccd72e6)

![d](https://github.com/jaswanth-1723/NearMe/assets/127680667/137f9cf4-b635-49e3-8427-d7409ca8e796)
![e](https://github.com/jaswanth-1723/NearMe/assets/127680667/9d9358b2-d629-47bc-a04a-b0f461c2bfb3)

## RESULT
The program for implementing image maps using HTML is executed successfully.
