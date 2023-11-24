# Ex04 Places Around Me
## Date: 22.11.2023

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
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="blue"><b>Thanjavur</b></font>
</h1>
<h3 align="center">
<font color="red"><b> Elamukilan G (23003756)</b></font>
</h3>
<center>
<img src="map.png" usemap="#Mycity" height="610" width="1450">
<map name="Mycity">
<area shape="rect" coords="600,150,800,250" href="thanjavur.html" title="Thanjavur">
<area shape="rect" coords="1200,550,1440,600" href="peraiyur.html" title="Peraiyur">
<area shape="rect" coords="150,0,200,80" href="poondi.html" title="poondi">
<area shape="rect" coords="150,350,300,450" href="sengipatti.html" title="sengipatti">
<area shape="rect" coords="100,150,160,300" href="vendayampatti.html" title="vendayampatti">
</map>
</center>
</body>
</html>

peraiyur.html

<html>
    <head>
        <title> my home town</title>    
</head>
<body bgcolor="red">
<h1 align="center"><b>Peraiyur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Nearest place</b></font>
</h3>
<hr size="2" color="red">
<p align="justify"
<font face="georgia" size="18" colour="white">
    According to Census 2011 information the location code or village code of Peraiyur I village is 638225.
     Peraiyur I village is located in Mannargudi taluka of Thiruvarur district in Tamil Nadu, India. 
     It is situated 10km away from sub-district headquarter Mannargudi (tehsildar office) and 42km away from district headquarter Thiruvarur. 
     As per 2009 stats, Kattakudi is the gram panchayat of Peraiyur I village.
The total geographical area of village is 508.52 hectares. 
Peraiyur I has a total population of 2,439 peoples, out of which male population is 1,171 while female population is 1,268.
 Literacy rate of peraiyur i village is 69.58% out of which 77.71% males and 62.07% females are literate. 
 There are about 649 houses in peraiyur i village. Pincode of peraiyur i village locality is 614018.
</font>



</body>
</html>



poondi.html




<html>
    <head>
        <title> my home town</title>    
</head>
<body bgcolor="pink">
<h1 align="center"><b>poondi</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Nearest place</b></font>
</h3>
<hr size="2" color="red">
<p align="justify"
<font face="georgia" size="18" colour="white">
    Poondi is a village located from 14 kilometer from Thanjavur. It is on the Thanjavur Nagapattinam Road
    . Highly fertile wet land . The Vandaiyar family are big Land lord.
     Some of the known people namely Rav Bahadur Veeraiya Vandaiyar
     Krisnasamy Vandaiyar fromer Congress Member of Legislative council,
      Thulasiya vandaiyar former congress MLA. They have started one of the famous Sri
      .Puspam College of Arts and Science with service motive benefit to the local population. 
      There is one Old 7 th day Adventis Christian Higher secondary School Englsih medium with hostel faiclities with goo
       teaching staff in the midst of wetlands adjuscent to the Sri Pushpam college.
       The entire village and adjoining villages land and small enterprises and shops are owned by this few Vandaiyar family members 
       of Kallar cast. There are lot of temples of small and bigger ones in the whole villages. 
       Fom Poondi to Thanjavur 3 kilometer one famous Marriaman koil covered with big big samutram lakes for about 4 kilometer .
        Lot of stories of underground passage connecting Thanjavur king Palace.



</body>
</html>



sengipatti.html




<html>
    <head>
        <title> my home town</title>    
</head>
<body bgcolor="brown">
<h1 align="center"><b>Sengipatti</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Nearest place</b></font>
</h3>
<hr size="2" color="red">
<p align="justify"
<font face="georgia" size="18" colour="white">
    Sengipatti is a village in Budalur taluk on the Tanjore–Trichy National Highway of Tanjore district, Tamil Nadu.
     It is located 23 kilometers from Thanjavur 33 kilometers from Tiruchirapalli 46 kilometers from Pudukkottai 65 kilometers from Ariyalur and 
     66 kilometers from kumbakonam. 
     It is the main junction of bus routes for Thanjavur, Trichy and Pudukottai districts.
The Mahatma Gandhi Memorial Tuberculosis Sanatorium is a landmark.
 The village is the most westerly village located in Thanjavur district and is situated on the frontier with Tiruchirapalli district.
  SASTRA University is located just 7km from Sengipatti while National Institute of Technology Trichy is located 17km away.
   It is one of the developing villages and has more industries addition to that the state government has set up Government College 
   of Engineering, Thanjavur in 2012.
</body>
</html>



thanjavur.html


<html>
    <head>
        <title> my home town</title>    
</head>
<body bgcolor="orange">
<h1 align="center"><b>Thanjavur</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> My hometown</b></font>
</h3>
<hr size="3" color="red">
<p align="justify"
<font face="georgia" size="8" colour="white">
    Thanjavur is the 11th biggest city in Tamil Nadu. 
    Thanjavur is an important center of South Indian religion, art, and architecture. Most of the Great Living Chola Temples,
     which are UNESCO World Heritage Monuments, are located in and around Thanjavur.
      The foremost among these, the Brihadeeswara Temple, built by the Chola emperor Rajaraja 
      I, is located in the centre of the city. Thanjavur is also home to Tanjore painting, a painting style unique to the region. 
      Thanjavur is the headquarters of the Thanjavur District.
       The city is an important agricultural centre located in the Kaveri Delta and is known as the Rice bowl of Tamil Nadu. 
       Thanjavur is administered by a municipal corporation covering an area of 128.02 km2 (49.43 sq mi) and had a population of
        290,720 in 2011. Roadways are the major means of transportation, while the city also has rail connectivity.
         The nearest airport is Tiruchirapalli International Airport, located 59.6 km (37.0 mi) away from the city. 
         The nearest seaport is Karaikal, which is 94 km (58 mi) away from Thanjavur. 
    The city first rose to prominence during the reign of the Cholas when it served as the capital of the empire.
</font>



</body>
</html>


vendayampatti.html



<html>
    <head>
        <title> my home town</title>    
</head>
<body bgcolor="blue">
<h1 align="center"><b>vendayampatti</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> My hometown</b></font>
</h3>
<hr size="3" color="red">
<p align="justify"
<font face="georgia" size="8" colour="white">
    According to Census 2011 information the location code or village code of Vendayampatti village is 638812.
     Vendayampatti village is located in Thanjavur taluka of Thanjavur district in Tamil Nadu, India.
      It is situated 30km away from Thanjavur, which is both district & sub-district headquarter of Vendayampatti village. 
      As per 2009 stats, Vendayampatti village is also a gram panchayat.
The total geographical area of village is 978.44 hectares. Vendayampatti has a total population of 1,449 peoples,
 out of which male population is 733 while female population is 716. Literacy rate of vendayampatti village is 60.18% out 
 of which 67.80% males and 52.37% females are literate.
There are about 374 houses in vendayampatti village. Pincode of vendayampatti village locality is 613402.
</font>



</body>
</html>







```

## OUTPUT
![new map](https://github.com/Elamukilanguna/NearMe/assets/144870462/a9b85186-e2f4-4e13-bb11-1f70af201385)

![2](https://github.com/Elamukilanguna/NearMe/assets/144870462/a66ef63b-9afd-464d-acba-722b177d32e1)
![3](https://github.com/Elamukilanguna/NearMe/assets/144870462/6736c30b-dd51-44d7-874f-84623744e456)
![4](https://github.com/Elamukilanguna/NearMe/assets/144870462/6980d512-7459-4398-9251-a483af625784)
![5](https://github.com/Elamukilanguna/NearMe/assets/144870462/991e9ce4-2add-4ba9-93a9-5eef09f3d6a0)
![6](https://github.com/Elamukilanguna/NearMe/assets/144870462/78f509f3-27f5-4fc3-8900-e1a6d8e95682)






## RESULT
The program for implementing image maps using HTML is executed successfully.
