# Ex04 Places Around Me
## Name: HARI PRASATH E
## Ref No: 25007799
## Date: 21-09-2025

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
map.html

<html>
    <head>
        <title>MAP</title>
    </head>

    <body bgcolor="cyan">
        <h1 align="center">VILLUPURAM -- HARI PRASATH E (25007799)</h1>
        <br>
        
        
       <img src="map (2).png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="MGR GOVT COLLEGE" title="MGR GOVT COLLEGE" href="clg.html" coords="901,685,592,803" shape="rect">
    <area target="" alt="VILLUPURAM RAILWAY STATION" title="VILLUPURAM RAILWAY STATION" href="rs.html" coords="922,323,1084,377" shape="rect">
    <area target="" alt="PANAMPET LAKE" title="PANAMPET LAKE" href="lake.html" coords="1059,738,147" shape="circle">
    <area target="" alt="VALEESHWARAR TEMPLE" title="VALEESHWARAR TEMPLE" href="temple.html" coords="1603,474,1907,565" shape="rect">
    <area target="" alt="THENDRAL PARK" title="THENDRAL PARK" href="park.html" coords="765,229,958,308" shape="rect">
</map>
</body>
</html>


clg.html

<html>
    <head>
        <title>MGR GOVT COLLEGE</title>
    </head>
    <body>
        <h>MGR GOVT COLLEGE</h>
        <p>  Dr.M.G.R. Government Arts and Science College for Women, Villupuram was established in the year 2017, in memory of Late Chief Minister of Tamil Nadu, Bharat Ratna, Dr. M.G.Ramachandran. Affiliated to the Thiruvalluvar University, the College aims to impart knowledge and holistic development to aspiring young women especially from the socially and economically backward classes of the society. Standing by its moto "ulluvadhellam uyarvullal" meaning  whatever you ponder let your aim be lofty still, the college has created a niche for itself in a very short span of time. With over 1400 students the college offers a wide range of undergraduate programs in Science, Arts and Humanities.</p>
    </body>
</html>

lake.html

<html>
    <head>
        <title>PANAMPET LAKE</title>
    </head>
    <body>
        <h>PANAMPET LAKE</h>
        <p>Panampet Lake is a lake located in Viluppuram, Tamil Nadu, India. It is known for its biodiversity and attracts numerous bird species, making it a popular spot for birdwatching. 
Location and overview
Location: The lake is in the Viluppuram district of Tamil Nadu. It is a well-known landmark in the area, and a guest house is located nearby.  </p>
    </body>
</html>

park.html

<html>
    <head>
        <title> THENDRAL PARK</title>
    </head>
    <body>
        <h>THENDRAL PARK</h>
        <p> Thendral Park is an inn located in Villupuram, Tamil Nadu. It is not a public park, but a lodging facility. 
Key details about Thendral Park Inn:
Location: It is situated on Hospital Road, within the city limits of Villupuram, and is easily accessible from both the highway and the railway station.
Facilities: The guest house offers air-conditioned, soundproof family rooms with a flat-screen TV and a private bathroom. Other amenities include free Wi-Fi, a 24-hour front desk, and an elevator.</p>
    </body>
</html>

rs.html

<html>
    <head>
        <title>VILLUPURAM RAILWAY STATION</title>
    </head>
    <body>
        <h>VILLUPURAM RAILWAY STATION</h>
        <p>Villupuram Junction (VM) is a major and busy railway station in Tamil Nadu that serves as a vital interchange for trains connecting Chennai to the southern and central parts of the state. As of June 2024, the station was undergoing redevelopment under the Amrit Bharat Scheme to enhance its amenities and infrastructure. 
Key features
Connectivity: Villupuram is a crucial junction where train lines diverge, connecting to various parts of South India. It is a major hub for trains going to and from Chennai, Tiruchirappalli, Ramanathapuram, and other southern destinations. </p>
    </body>
</html>

temple.html

<html>
    <head>
        <title>VALEESHWARAR TEMPLE</title>
    </head>
    <body>
        <h>VALEESHWARAR TEMPLE</h>
        <p> The Aadhi Valeeswarar Temple in Villupuram is a Shiva temple known for its association with the mythical Vanara king, Vali, from the epic Ramayana. Located in the Poonthottam area, the temple has ancient origins and has been renovated over time. 
Key details about the temple:
Deity: Lord Shiva, worshipped as Aadhi Valeeswarar. The name reflects the legend that the mythical Vanara King, Vali, worshipped Shiva at this location.</p>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot 2025-10-15 194003.png>)
![alt text](<Screenshot 2025-10-15 194055.png>)
![alt text](<Screenshot 2025-10-15 194156.png>)
![alt text](<Screenshot 2025-10-15 194218.png>)
![alt text](<Screenshot 2025-10-15 194241.png>)
![alt text](<Screenshot 2025-10-15 194340.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
