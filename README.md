# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

home.html
```html 
<html>
    <head>
        <link rel="stylesheet" href="stylehome.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./logo.png" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="peroson.html">People</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div class="home">
        <div class="head">
        <h1>A Software Agency shaping</br>ideas into </br>Products</h1>
        <p class="quote">"People who are really in serious about Software </br>should make their hardware"- Alan key </p>
        <button class="join">Join us</button>
    </div>
    <div class="login">
        <h2 class="log">login Here</h2> 
        <div class="logbox">
        <input type="text" placeholder="username or email" class="but"></input></br></br>
        <input type="text"  placeholder="password" class="but"> </input></br></br>
        <button type="submit" class="bute">Login</button></br></br>
        <hr id="loge">
        </div>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;Don't have an account </br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<u>Sign up</u> here.</p>

    </div>
    </div>
    <footer>
        <div  class="colored-line">
            <h5>Design and developed by Mr.R.Harish kumar &copy;2023</h5>
        </div>
    </footer>

    
    
    </body>
</html>
```
## person.html
```html
<html>
    <head>
        <link rel="stylesheet" href="./personstyle.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./logo.png" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="peroson.html">People</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div class="person">
        <li> <img src="./my.jpeg" class="bod"></br><span> &nbsp;&nbsp;&nbsp;Harish</span><p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CEO</p></li>
        <li> <img src="./bheem.jpeg" class="bod"></br><span>&nbsp;&nbsp;&nbsp;Bheem</span><P>&nbsp;&nbsp;&nbsp;&nbsp;Founder</P></li>
        <li> <img src="./hat.jpeg"class="bod"></br><span>&nbsp;&nbsp;&nbsp;Hatori</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Co-Founder</li>
        <li> <img src="./dori.jpg" class="bod" ></br><span>&nbsp;&nbsp;&nbsp;Doramen</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Director</p></li>
        <li> <img src="./mot.jpeg "class="bod"></br><span>&nbsp;&nbsp;&nbsp;Motu-paltu</span><p>&nbsp;&nbsp;&nbsp;&nbsp;Assi Director</p></li>
        <li> <img src="./shinchan.png "class="bod"></br><span>&nbsp;&nbsp;&nbsp;ShinChan</span><P>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MD</P></li>
    </div>
    <footer>
    <div  class="colored-line">
        <h5>Design and developed by Mr.R.Harish kumar  &copy;2023</h5>
    </div>
</footer>
    
    
    </body>
</html>
```
### Person.css
```css 
.nav{
    display: flex;
    justify-content:center;
    gap: 50px;
    margin-top: 25px ;  
}

li{
    list-style: none;
    font-weight: 100px;
    
}
.person{
    display: flex;
    margin-top: 230px;
    justify-content: center;
    gap: 20px;
}
.bod{
    height: 100px;
    border: 3px solid rgb(243, 198, 182);

}
*{
    font-size:20px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 60px;
}
span{
    font-size: 20px;
    font-weight: 1000;
    text-indent: 20px;
    
}
.colored-line {
    width: 100%; 
    height: 25px; 
    background-color:rgb(6, 247, 167);
    text-align: center;
    margin-top: 200px;
  }
  body{
    background-color: gold;

  }
  .button{
        background-color: chocolate;
      
  }
```
### product.html
```html
<html>
    <head>
        <link rel="stylesheet" href="styleproduct.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./logo.png" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="peroson.html">People</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" >
            <button type="submit" class="button" >search</button>
            
        </div>
    </div>
    <div>
        <img src="./products.png" alt="product" class="imge">
    </div>
    <footer>
        <div  class="colored-line">
            <h5>Design and developed by Mr.R.Harish kumar  &copy;2023</h5>
        </div>
    </footer>
    
    
    </body>
</html>
```
### Product.css
```css 
.nav{
    display: flex;
    justify-content:center;
    gap: 50px;
    margin-top: 25px ;  
}

li{
    list-style: none;
    font-weight: 100px;
    
}


*{
    font-size:20px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 10px;
}

  body{
    background-color: #f10e80;

  }
.imge{
    border-radius: 10px;
    height: 450;
    margin-top: 60px;
    margin-left: 450px;
}
.colored-line {
    width: 100%; 
    height: 25px; 
    background-color:rgb(92, 25, 25);
    text-align: center;
    margin-top: 110px;
    border-radius: 0;
  }

  .contact{
    display: flex;
    justify-content:center;
    align-items: center;
    height: 80vh;
    gap: 300px;

  }
  span{
    font-weight: 1000px;
  }
  .info{
    background-color:rgb(10, 25, 235);
    padding: 10px;
    border: 3px solid rgb(223, 177, 91);
    border-radius: 30px;
    
  }
  .detail{
    background-color: rgb(231, 18, 54);
    padding: 10px;
    border: 3px solid rgb(10, 10, 9);
    border-radius: 30px;

  }
  .comment{
    padding:50px; }
  .submit{
    background-color: rgb(69, 241, 16);
  }
  .button{
    background-color: rgb(9, 22, 211);
  }
  
```
### contact 
```html
<html>
    <head>
        <link rel="stylesheet" href="stylecontact.css">

    </head>
    <body>
        <div class="nav">
            <div class="logo"><img src="./logo.png" alt="logo" height="60px"></div>
            <li><a href="./home.html">Home</a></li>
            <li><a href="peroson.html">People</a></li>
            <li><a href="./products.html">Products</a></li>
            <li><a href="./contact.html">Contacts</a></li>
        <div>
            <input type="text" placeholder="Enter to search" class="button">
            <button type="submit" class="submit" >search</button>
                
    </div>
</div>
<div class="contact">
    <div class="detail">
    <h1> Contact Us</h1>
    <br>
    <input type="text" placeholder="Your Name"></inupt> 
    <br><br>
    <input type="text" placeholder="Your Email"></inupt>
    <br><br>
    <input type="text" placeholder="Your Message" class="comment"></inupt>
    <br><br>
    <button type="submit" class="submit">Submit</button>

</div>
<div class="info">
    <h1>Contact information</h1>
    <br>
    <span><strong>Address:</strong></span>    Church street,kommedu,gingee,villupuram-604205.</p>
    <span><strong>Email:</strong></span>    cris.jpt@gmail.com</p>
    <span><strong>Phone: </strong></span> 044-46055</p>

</div>
</div>
<footer>
    <div  class="colored-line">
        <h5>Design and developed by Mr.R.Harish kumar &copy;2023</h5>
    </div>
</footer>
    
  
    
    
    </body>
</html>
```
### contact.css

```css
.contact{
    display: flex;
    justify-content:center;
    align-items: center;
    height: 80vh;
    gap: 300px;

  }
  span{
    font-weight: 1000px;
  }
  .info{
    background-color:rgb(253, 12, 12);
    padding: 10px;
    border: 3px solid orange;
    border-radius: 30px;
    text-align: center;
    
  }
  .detail{
    background-color: rgb(49, 224, 14);
    padding: 10px;
    border: 3px solid orange;
    border-radius: 30px;
    

  }
  .comment{
    padding:50px; }
  .submit{
    background-color: chocolate;
  }
  body{
    background-color: gold;

  }
  
*{
    font-size:20px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    border-radius: 10px;
}
li{
    list-style: none;
    font-weight: 100px;
    
}
.nav{
    display: flex;
    justify-content:center;
    gap: 50px;
    margin-top: 25px ;  
}
h1{
    font-size: 1.5rem;
  }
  .colored-line {
    width: 100%; 
    height: 25px; 
    background-color:red;
    text-align: center;
    margin-top: 35px;
  }
```
## OUTPUT:

### Home Page:

![](./out4.png)

### Person

![](./out1.png)

### Product 
![](./out2.png)


### Contact

![](./out3.png)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
