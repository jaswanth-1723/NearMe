# Ex04 Places Around Me
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
        <font color=""><b>TAMBARAM</b></font>
        </h1>
        <h3 align="center">
        <font color="blue"><b>KARTHICK APPIREDDY 212220040070</b></font>
        </h3>
<center>        
<img src="Map.png" usemap="#image-map" height="650" width="1600">
</center>
<map name="image-map">
    <area shape="rectangle" coords="1043,70,1156,108" href="a.html" title="TAMBARAM BUS STAND">
    <area shape="rectangle" coords="1061,205,908,239" href="b.html" title="TAMBARAM RAILWAY STATION">
    <area shape="rectangle" coords="569,377,693,418" href="c.html" title="VARADHRAJA CINEMAS">
    <area shape="rectangle" coords="968,96,913,63" href="d.html" title="CHITLAPAKKAM AERI">
    <area shape="rectangle" coords="1131,49,977,19" href="e.html" title="Jambulingeshwarar Temple">
</map>
</body>
</html>
```
```
<html>
<head>
<title>TAMBARAM BUS STAND</title>
</head>
<body bgcolor="white">
<h3 align="center"><font size="+3">TAMBARAM BUS STAND</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's TAMBARAM BUS STAND------</font>
</p>
<p>
    
    <font size="+2">Tambaram Bus Stand is operated by the Metropolitan Transport Corporation (MTC), the government-owned bus operator in Chennai. The bus stand has a large number of platforms, which cater to both city and mofussil buses. There are also a number of private bus operators that operate from Tambaram Bus Stand.

        Tambaram Bus Stand is a major hub for commuters who travel to and from the suburbs of Chennai and neighboring districts. It is also a popular stop for tourists who are visiting Chennai and other parts of Tamil Nadu.</font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>TAMBARAM RAILWAY STATION</title>
</head>
<body bgcolor="cyan">
<h3 align="center"><font size="+3">TAMBARAM RAILWAY STATION</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's TAMBARAM RAILWAY STATION------</font>
</p>
<p>
    
    <font size="+2">Tambaram Railway Station is a bustling railway hub situated in the Tambaram suburb of Chennai, India. It serves as a crucial junction connecting Chennai to various destinations within Tamil Nadu and beyond. The station is a prominent landmark in the area, playing a vital role in facilitating the movement of people and goods.</font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>VARADHRAJA CINEMAS</title>
</head>
<body bgcolor="yellow">
<h3 align="center"><font size="+3">VARADHRAJA CINEMAS</font></h3>
<hr size="7" color="red">
<p align="justify">
<font size="+1">Here's VARADHRAJA CINEMAS------</font>
</p>
<p>
    
    <font size="+2">
        Varadharaja Cinemas is a popular cinema hall in Chennai, India. It is located in Chitlapakkam, a suburb in the south of the city. The cinema hall was established in 1983 and has been a popular destination for moviegoers ever since.Varadharaja Cinemas has a single screen with a seating capacity of over 1000 people. The cinema hall is equipped with state-of-the-art 4K RGB laser projection and Dolby Atmos sound system. This provides an immersive and cinematic experience for the viewers.

        Varadharaja Cinemas screens a variety of Tamil, Hindi, Telugu, and English films. The cinema hall also hosts special events, such as film festivals and live music performances.
        
        Varadharaja Cinemas is a popular destination for families and friends alike. It is a great place to enjoy a movie and have a memorable experience.</font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>CHITLAPAKKAM AERI</title>
</head>
<body bgcolor="white">
<h3 align="center"><font size="+3">CHITLAPAKKAM AERI</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's CHITLAPAKKAM AERI------</font>
</p>
<p>
    
    <font size="+2">Chitlapakkam Lake is an urban lake located in Chitlapakkam, a suburb in the south of Chennai, India. It is the chief water body in the neighbourhood. Originally measuring 86.86 acres, the lake has currently shrunken to 46.88 acres. The lake was last restored in 2003. Chitlapakkam Lake was built in the 19th century to provide irrigation for the surrounding farmland. The lake was once a major source of water for the region, but it has been declining in size due to encroachment and pollution.</font>
</p>
</body>
</html>
```
```
<html>
<head>
<title>Jambulingeshwarar Temple</title>
</head>
<body bgcolor="cyan">
<h3 align="center"><font size="+3">Jambulingeshwarar Temple</font></h3>
<hr size="7" color="black">
<p align="justify">
<font size="+1">Here's Jambulingeshwarar Temple------</font>
</p>
<p>
    
    <font size="+2">Jambulingeshwarar Temple is a Hindu temple dedicated to Lord Shiva, located in the Sembakkam suburb of Chennai, India. The temple is believed to be over 1000 years old and is one of the most popular Shiva temples in Chennai.The presiding deity of the temple is Lord Jambulingeshwarar, who is depicted as a Swayambu lingam (self-manifested lingam). The lingam is enshrined in the sanctum sanctorum of the temple, which is surrounded by a five-tiered Rajagopuram (gateway tower).

        The temple complex also has a number of other shrines, including shrines to Goddess Akilandeshwari (the consort of Lord Shiva), Lord Ganesha, Lord Subramanya, Lord Ayyappa, and Saneeswaran. The temple also has a sacred tank, where devotees can take a holy dip.
        
        The Jambulingeshwarar Temple is a popular pilgrimage site for Hindus from all over India. The temple is especially popular during the festival of Maha Shivratri, which is celebrated every year in honor of Lord Shiva.</font>
</p>
</body>
</html>
```

## OUTPUT

![mapp](https://github.com/KarthickAppireddy/NearMe/assets/107381090/432ac8db-e906-4dd3-a6ec-b2e9258166f9)
![a](https://github.com/KarthickAppireddy/NearMe/assets/107381090/6c3b5bd9-1063-4703-91bc-573d0d9c5bcd)
![b](https://github.com/KarthickAppireddy/NearMe/assets/107381090/f51867b3-8653-426e-8af0-a9aef1c4e25c)
![c](https://github.com/KarthickAppireddy/NearMe/assets/107381090/ed9ff5dc-cd12-428f-8c47-bb53fe7fc242)
![d](https://github.com/KarthickAppireddy/NearMe/assets/107381090/ee302c22-399b-45a5-917f-1bc017de91c7)
![e](https://github.com/KarthickAppireddy/NearMe/assets/107381090/a9f70bc8-16fb-4d37-a8b0-cc1acdaa6d16)







## RESULT
The program for implementing image maps using HTML is executed successfully.
