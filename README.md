# Ex03 Places Around Me
## Date: 29/11/25

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
dhivya.html
```
<html>
    <head>
        <title>My city</title>
    </head>
    <body>
        <h1 align="center">MADURAI</h1>
        <h2 align="center">DHIVYA DARSHNEE.U</h2>
        <h3 align="center">25009986</h3>
        <img src="Screenshot (30).png"usemap="#Madurai"

    <map name="My City">
    <area target="" alt="Pasumalai Hill" title="Pasumalai Hill" href="hill.html" coords="485,314,636,366" shape="rect">
    <area target="" alt="Madurai Airport" title="Madurai Airport" href="Airport" coords="522,631,78" shape="circle">
    <area target="" alt="PTR COLLEGE OF ENGINEERING AND TECHNOLOGY" title="PTR COLLEGE OF ENGINEERING AND TECHNOLOGY" href="college.html" coords="45,416,99,395,151,412,192,438,180,486,141,504,76,505,34,498,17,469,13,435" shape="poly">
    <area target="" alt="Arulmigu Sri Pandi Muneeswaran Temple" title="Arulmigu Sri Pandi Muneeswaran Temple" href="temple.html" coords="946,187,101" shape="circle">
    <area target="" alt="Athisayam Theme Park" title="Athisayam Theme Park" href="park.html" coords="99,-1,293,71" shape="rect">
</map>
    </body>
</html>

```
Hill.html
```
<html>
    <head>
        <title>Pasumalai Hill</title>
    </head>
    <body bgcolor="brown">
        <h2 align="center" >Pasumalai Hill</h2>
        <font face ="Times New Roman" color="yellow">Pasumalai is a prominent hill and a surrounding neighborhood located in the city of Madurai, in the state of Tamil Nadu, India.In Tamil, "Pasu" means cow (or animal) and "Malai" means hill or mountain. The hill is one of three key hills (along with Yanaimalai and Nagamalai, named after the elephant and snake, respectively) that form the natural boundary of the city and are often associated with local legends. </font>
        <h4 >Historical Significance</h4>
        <font face="Times New Roman" color="yellow">The area has historical importance, with the Taj Gateway Hotel property on top of the hill once serving as the residence for a British official of the J.B. Coats company over a century ago.
        The 20th-century political leader Pasumpon Muthuramalinga Thevar established the Mahalakshmi Mills Labour Welfare Association here.
</font>
    </body>
</html>
```
Temple.html
```
<html>
    <head>
        <title>Temple</title>
    </head>
    <body bgcolor="pink">
        <h2 align ="center">Arulmigu Sri Pandi Muneeswaran Temple</h2>
        <font face ="Times New Roman" color="blue">The Arulmigu Sri Pandi Muneeswaran Temple is an ancient temple in Madurai, Tamil Nadu, known for its unique origin story and powerful deity, Pandi Muneeswarar. According to local legend, the deity is believed to be the ancient Pandya king Nedunchezhiyan, who is said to have been meditating as a penance for his role in the injustice done to Kovalan, the husband of Kannagi. The temple is located in the Melamadai area and is a significant spiritual site for those seeking divine justice and protection.  </font>
        

    </body>
</html>
```
Airport.html
```
<html>
    <head><title>Madurai Airport</title>
    </head>
    <body bgcolor="yellow">
        <h2 align="center" >Madurai Airport</h2>
        <font face="Times New Roman" color="pink">Madurai Airport (IXM) is a 24/7 customs airport in Tamil Nadu, India, located about 12 km from the city center. Established in 1957, it serves both domestic and international flights and features two adjacent terminals and a single runway. The airport has amenities like baggage storage, restrooms, and wheelchair accessible facilities.  </font>
    </body>
</html>
```
park.html
```
<html>
    <head>
        <title>Park</title>
    </head>
    <body bgcolor="blue">
        <h2 align="center">ATHIYASAM THEME PARK</h2>
        <font face="Times New Roman" color="brown">Athisayam is a 70-acre amusement and water park located in Madurai, Tamil Nadu, about 12 km from the city on the Madurai-Dindigul National Highway. It offers a variety of rides for all ages, including water rides like the Water Chute, Wave Pool, and Crazy River, as well as dry rides such as the Roller Coaster, Carousel, and Ranger. The park is designed for family fun, with options ranging from thrilling attractions to more relaxed family rides. </font>
    </body>
</html>
```
college.html
```
<html>
    <head>
        <title>college</title>
    </head>
    <body bgcolor="orange">
        <h2 align="center">PTR COLLEGE OF ENGINEERING AND TECHNOLOGY</h2>
        <font face="Times New Roman" color="green">P.T.R. College of Engineering and Technology is a private, non-profit college in Madurai, established in 2001. It is affiliated with Anna University and offers undergraduate and postgraduate engineering programs, including B.E. in Civil, Computer Science, Electrical and Electronics, and Mechanical Engineering, along with a B.Tech in Artificial Intelligence & Data Science. The college is known for its infrastructure, labs, and placement cell, with facilities like hostels, libraries, and transportation services.</font>
    </body>
</html>


```
## OUTPUT
![alt text](<Screenshot (30).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (25).png>)
![alt text](<Screenshot (27).png>)
![alt text](<Screenshot (28).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
