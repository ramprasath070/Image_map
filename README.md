# Ex04 Places Around Me
# Date: 25.04.2025
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

# PROGRAM CODE

```
map.html

<html>
    <head>
        <style>
            body {
              
              background-repeat: no-repeat;
              background-attachment: fixed;
              background-size: cover;
            }
            </style>
    </head>
    <body> 
        <map name="image-map">    
         <area shape="circle" coords="442,645,6" title="GINGEE FORT" alt="fort" href="fort.html"  >

         <area shape="circle" coords="1136,568,29" title="GINEEE JUNCTION" alt="junction" href="junction.html">

         <area shape="rect" coords="113,462,204,543" title="GINGEE FOREST" href="forest.html">

         <area shape="circle" coords="1121,511,18" title="GINGEE BUS STAND" href="bus.html">

         <area shape="circle" coords="1167,468,22" title="SAARAVANA CINE PLEX" href="cine.html">

        </map>
        <img src="map.png" usemap="#image-map" alt="Map"> 

    </body>
</html>

fort.html
<html>
    <head>

    </head>
    <body>
        <center ><h1 style="font-family: Kristen ITC;"><b>GINGEE FORT</b></h1></center>
        <center><img src="fort.png"  width="1080px" height="580px"></center>
        <p style="font-size: 20px; font-family:'Sitka Display Semibold'; text-align: left;">
             *Location: Villupuram district, Tamil Nadu, India (about 160 km from Chennai and 37 km from Thiruvannamalai).
             *Other Names: Senji Fort, Chenji Fort, or "Troy of the East" – because of its strong fortifications.

             Originally built in the 9th century by the Chola dynasty, later developed by the Vijayanagara Empire in the 13th century.
             It passed through the hands of several rulers: Marathas, Mughals, French, and British.
             Shivaji, the Maratha king, captured it in 1677.
             In 1698, the Mughals took control after a long siege.
             The British finally took it over in 1761.
        </p>
        
    </body>
</html>

forest.html

<html>
    <head>

    </head>
    <body>
        <center ><h1 style="font-family: Kristen ITC;"><b>GINGEE FOREST</b></h1></center>
        <center><img src="forest.png"  width="1080px" height="580px"></center>
        <p style="font-size: 20px; font-family:'Sitka Display Semibold'; text-align: left;">
            **The Gingee Forest, surrounding the historic Gingee Fort in Tamil Nadu, is a scenic dry deciduous forest known for its rocky terrain and diverse flora and fauna. 
            **Located along National Highway 77, the forest covers the hilly region around the fort and offers a unique blend of nature and history. 
            **It is home to wildlife such as Indian hares, peacocks, monkeys, and various birds and reptiles. 
            **The area is also popular for trekking and nature walks, with panoramic views of boulders, ancient trees, and stone structures from centuries past. 
            **Rich in biodiversity and historical significance, the Gingee Forest provides a peaceful escape for nature lovers, trekkers, and history enthusiasts alike.
        </p>
        
    </body>
</html>

junction.html

<html>
    <head>

    </head>
    <body>
        <center ><h1 style="font-family: Kristen ITC;"><b>GINGEE JUNCTION</b></h1></center>
        <center><img src="junction.png"  width="1080px" height="580px"></center>
        <p style="font-size: 20px; font-family:'Sitka Display Semibold'; text-align: left;">
            **Gingee lies right on NH 77, making it a key junction for travelers and transport between northern Tamil Nadu and the Western Ghats region.

            **This road is commonly used by pilgrims visiting Tiruvannamalai and travelers heading towards Bangalore or Hosur.
            **Mostly a 2-lane highway, being upgraded in some parts.

            **Scenic with plenty of greenery and small hills, especially near Gingee Fort.
            **NH 77 makes Gingee a busy bus stop, with TNSTC buses frequently stopping en route to Tiruvannamalai, Vellore, and more.

        </p>
        
    </body>
</html>

cine.html

<html>
    <head>

    </head>
    <body>
        <center ><h1 style="font-family: Kristen ITC;"><b>SARAVANA CINE PLEX</b></h1></center>
        <center><img src="cine.png"  width="1080px" height="580px"></center>
        <p style="font-size: 20px; font-family:'Sitka Display Semibold'; text-align: left;">
            **Saravana Cineplex is one of the most popular and modern theatres in the town of Gingee, located at 87, Mahatma Gandhi Road, Viluppuram District, Tamil Nadu – 604202. Conveniently situated near the town center, it serves as a go-to spot for movie lovers in and around Gingee.

            **Air-conditioned halls with comfortable seating and clear views from every angle

            **Equipped with Dolby sound system and digital projection, ensuring a high-quality cinematic experience
            
            **Clean premises with decent washrooms and a small snacks counter for refreshments
            
            **Safe and family-friendly environment

            **Screens the latest Tamil films, and occasionally Bollywood and Hollywood releases

            **Regular show timings include: 11:30 AM, 3:00 PM, 6:30 PM, and 10:00 PM
            
            **During big releases, additional morning or late-night shows may be added
        </p>
    </body>
</html>

bus.html

<html>
    <head>

    </head>
    <body>
        <center ><h1 style="font-family: Kristen ITC;"><b>GINGEE BUS STAND</b></h1></center>
        <center><img src="Bus.png"  width="1080px" height="580px"></center>
        <p style="font-size: 20px; font-family:'Sitka Display Semibold'; text-align: left;">
            **The Gingee Bus Stand serves as a vital transportation hub in the Viluppuram district of Tamil Nadu. Strategically located along National Highway 77 (NH 77), it connects Gingee to major towns and cities such as Tindivanam, Tiruvannamalai, Villupuram, and Chennai. The bus stand facilitates both government and private bus services, ensuring regular and convenient travel options for passengers.
            
            **In 2021, the Directorate of Town Panchayats, Government of Tamil Nadu, initiated a tender for the development of the Gingee Bus Stand under the Kalaignar Nagarpura Mempattu Thittam (KNMT) 2021–22 scheme . This project aimed to enhance the infrastructure and amenities of the bus stand, improving the overall experience for commuters.
            
            **For travelers, the Gingee Bus Stand offers access to various destinations, with services available throughout the day. The facility's location and connectivity make it a convenient point for both local residents and tourists visiting attractions like the historic Gingee Fort.


        </p>
        
    </body>
</html>
```
# OUTPUT

![alt text](<Screenshot 2025-04-25 131429.png>)
![alt text](<Screenshot 2025-04-25 131443.png>)
![alt text](<Screenshot 2025-04-25 131456.png>)
![alt text](<Screenshot 2025-04-25 131508.png>)
![alt text](<Screenshot 2025-04-25 131519.png>)
![alt text](<Screenshot 2025-04-25 131531.png>)


# RESULT
The program for implementing image maps using HTML is executed successfully.
