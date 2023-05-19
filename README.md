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

map.html

<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>THIRUKOVILUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SUBALAKSHMI S (212222100051)</b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="420" width="1100">
<map name="MyCity">
<area shape="circle" coords="390,250,50" href="/static/html/temple.html" title="SHRI ULAGALANTHA PERUMAL TEMPLE">
<area shape="circle" coords="200,300,60" href="/static/html/school.html" title="SRI SARADHA VIDHYASHRAM">
<area shape="rectangle" coords="550,50,100,60" href="/static/html/river.html" title="THEN PENNAI RIVER">
<area shape="rectangle" coords="700,40,20,100" href="/static/html/rock.html" title="KABILAR KUNDRU">
<area shape="circle" coords="400,250,100" href="/static/html/theatre.html" title="SRINIVASA THEATRE">
</map>
</center>
</body>
</html>

river.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>RIVER</title>
</head>
<body bgcolor="brown">
<h1 align="center">
<font color="black"><b>THIRUKOVILUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>THEN PENNAI RIVER</b></font>
</h3>
<hr size="3" color="black">
<p align="justify">
<font face="Arial" size="5">
<b>
he Thenpennai River is flowing continuously for 5000 kilometer. It passes through many villages’ town and Thiruvannamalai district .It is Perennial river and monsoon based catchment. The Thenpennai river is the main source for irrigating over 17,980 acres in Thiruvannamalai district. It is also the main sources of drinking water to more hundred villages many polluted are added to this river at all points ,especially those closes to human settlement and industrial development suffer from acute level of pollution river that flow through densely populated area including towns and housing area are often polluted with solid wastes. To use the river water to water supply to many towns which includes Thiruvannamalai, Thirukovilur, etc. Entire flow on the river as turbidity. Considerable amount of population depend upon the river directly for the daily become use a study has necessary to the present day to determine the suitability of the river water for domestic use.
</b>
</font>
</p>
</body>
</html>

rock.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>KUNDRU</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>THIRUKOVILUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>KABILAR KUNDRU</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
Kabilar Kundru (or Kabilar rock) is a hill rock in the middle of the Ponnaiyar River near Tirukoilur in Viluppuram district, Tamil Nadu, India. It is known for Tamil poet Kapilar did Vadakirrutal (fast unto death) here, after his friend Vēl Pāri was killed in a battle. It is one of the protected monuments in Tamil Nadu by the Archaeological Survey of India.
</b>
</font>
</p>
</body>
</html>

school.html

<html lang="en">
<head>
<title>SCHOOL</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>THIRUKOVILUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> SRI SARADHA VIDHYASHARAM</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Tahoma" size="5">
Established in the year 2016, Sri Saradha Vidhyashram Senior Secondary School is a co- education CBSE School, located at Tirukoilur, Kallakurichi District runs under the aegis of Eshwari Educational Trust. Consequent to growing demand, the Management has come up with a capacious and palatial structure at T.Keeranur village with a serene atmosphere and good ambience to cater to the needs of the students of the locality and surroundings. The affiliation number of our school is 1931046.
</font>
</p>
</body>
</html>

temple.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>TEMPLE</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b>THIRUKOVILUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SHRI ULAGALANTHA PERUMAL TEMPLE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Courier New" size="5">
<b>

Ulagalantha Perumal Temple or Trivikrama Temple is a Hindu temple dedicated to Vishnu located in Tirukkoyilur, Tamil Nadu, India. Constructed in the Dravidian style of architecture, the temple is glorified in the Naalayira Divya Prabandham, the early medieval Tamil canon of the Alvar saints from the 6th–9th centuries CE. It is one of the 108 Divya Desams dedicated to Vishnu, who is worshipped as Ulagalantha Perumal and his consort Lakshmi as Poongothai.[1] The temple is believed to have been built by the Medieval Cholas, with later contributions from Vijayanagara kings and Madurai Nayaks. The temple covers an area of 5 acres (20,000 m2) and has a temple tower that is the third tallest in Tamil Nadu, measuring 192 ft (59 m) in height.

According to Hindu myths, Vamana, a Brahmin dwarf avatar of Vishnu, appeared here to quell the pride of the asura king Bali. The temple is believed to be the place where the first three Alvars, the Vaishnava Saints, namely, Poigai Alvar, Bhoothathalvar, and Peyalvar attained salvation. The temple is one of the Panchakanna (Krishnaranya) Kshetrams, the five holy temples associated with Krishna, an avatar of Vishnu.

Ulagalantha Perumal is believed to have appeared to King Mahabali and the Alvars. Six daily rituals, and a dozen yearly festivals, are held at the temple, out of which the chariot festival, celebrated during the Tamil month of panguniபங்குனி (March–April), is the most prominent. The temple is maintained and administered by the Hindu Religious and Endowment Board of the Government of Tamil Nadu.

</b>
</font>
</p>
</body>
</html>

theatre.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>THEATRE</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>THIRUKOVILUR</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>SRINIVASA THEATRE</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Arial" size="5">
<b>
One of the best cinema theatre in tirukoilur with latest technology Barco 4K & Dolby Atmos.
you can book your tickets in online mode also through the bookmyshow. 
</b>
</font>
</p>
</body>
</html>



## OUTPUT


## HTML VALIDATOR


## RESULT
The program for implementing image maps using HTML is executed successfully.
