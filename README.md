# Ex.07 Software Product Company Website
## Date:

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
mainpage.html

<html>
<title>GFA company</title>
<style>
    body{
        background:url(milky-way.jpg) ;
        background-size: cover;
    }

    h1{
        color: rgb(7, 52, 92);
    }
    h2{
        color: rgb(8, 47, 81);
    }
    h3{
        color:rgb(85, 11, 11);
        align:center;
    }

/* the main window options*/
.styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #6e1515; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(15, 49, 79); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #5f1616; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#581414; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:rgb(74, 57, 37);
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(69, 34, 69); /* Adjust the color as needed */
}

.login{
    margin-top: -100;
    margin-left: 1100;
    margin-right: 100;    
    background:url(123.jpg);

    scroll-padding-left: 5px;
    border:2px solid rgb(74, 42, 42);
}
.login input[type="button"] {
    padding: 10px 20px; /*  button size */
    background-color: #3498db;
    color: #7c4d4d;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="button"]:hover {
    color:#000;
    background-color:rgb(204, 32, 204);
}
.login input[type="submit"]{
    padding: 10px 15px; /*  button size */
    background-color:#4234db;
    color: #6c2929;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.login input[type="submit"]:hover {
    color:#000;
    background-color:chocolate;
}
.login input[type="text"] { 
    padding: 10px; /* Add padding for better appearance */
    transition: background-color 0.3s; /* Add transition for a smooth effect */
        /* Set initial background color */
        background-color: #702a2a;
}
.login input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:slateblue; /* Adjust the color as needed */
}
.join{
    padding: 10px 20px; /*  button size */
    background-color: #3498db;
    color: #770f0f;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
}
.join:hover {
    color: rgb(15, 107, 76);
    background-color: #4234db;
}

/main html/
</style>
<body >
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="product.html">
                <input type="button" value="OUR PRODUCTS">
            </a>

            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>

    <h1>HELLO this is GFA Company</h1>
    <h2>one of the most trusted and valuble company</h2>
    <h2>PRODUCTS</h2>
    <a href="sign.html">
        <input type="button" value="JOIN US" class="join">
    </a>  
    
    <h3>"Technology is best when it brings people together"</h3>

         <center>
        <div class="login">
            <div class="login-box">
            <p style="color: rgb(32, 80, 122);">DONT HAVE AN ACCOUNT</p>
            <a href="sign.html">
                <input type="button" value="SIGN IN"><br><br>
            </a>  
            <p style="color: rgb(17, 55, 88);">LOGIN</p>
            <input type="text" value="Username or email" ><br><br>
            <input type="text" value="Password"><br><br>
            <a href="product.html">
                <input type="submit" value="SUBMIT"><br><br>
            </a>  
        </div>
        </div>
    </center>

</body>
<footer style="background-color:darkmagenta;margin-top: 143; border: none;">
    <P style="color:#370808; ;"align="center">Designed and Developed by Akshayaa </P>
</footer>
</html>

products.html

<html>
    <title>our products</title>
    <style>  
    body{
        background:url(pixel.jpeg);
        background-size:contain;
    } 
    h1{
        color: rgb(15, 48, 77);
    }  
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #3f1b1b; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(23, 69, 109); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #553535; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#4e1e1e; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:rgb(111, 69, 18);
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(89, 10, 89); /* Adjust the color as needed */
}
</style>
    
    <body>
        <form class="styled ">
            <div class=>
                <a href="home.html">
                    <input type="button" value="HOME">
                </a>
                <a href="product.html">
                    <input type="button" value="OUR PRODUCTS">
                </a>
                <a href="about.html">
                    <input type="button" value="ABOUT US">
                </a>
                <a href="sign.html">
                    <input type="button" value="SIGN IN">
                </a>
                <a href="contact.html">
                    <input type="button" value="CONTACT">
                </a>  
                <input type="text">
                <input type="submit"value="SEARCH">  
            </div>
        </form>
        
        <center>
            <h1 >OUR PRESTIGEOUS PROJECTS</h1>
        <img src="software company prodect image.jpg" height="500" width="800">
    </center>
    </body>
    <footer style="background-color:darkmagenta;margin-top: 64; border: none;">
        <P style="color:#e90808; ;"align="center">Designed and Developed by Akshayaa</P>
    </footer>
</html>

about.html

<html>
<title>about us</title>
<style>
    p{
        color: rgb(79, 50, 14);
    }
    body{
        background:url(aa.png);
        background-size: cover;
    }
    .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #5a1313; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(18, 32, 44); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #092d44; /* initial background color */
            color: #642626; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#440f0f; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:rgb(67, 42, 12);
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(81, 9, 81); /* Adjust the color as needed */
}
.photos{
    display:flex;
    justify-content: space-around;
    margin-top: 200px;
}
.names{
    display:flex;
    justify-content: space-around;

}
.position {
    display: flex;
    justify-content: space-around;
    margin-left: 10px;
    border-image:5px;
    border-image: rgb(88, 54, 8);
}

</style>
<body>
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="product.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="photos">
    <img src="akshayaa.jpg" height="200" width="200">
    <img src="vijay.jpg" height="200" width="200">
    <img src="dhoni.jpg" height="200" width="200">
    <img src="gv prakash.png" height="200" width="200">
    <img src="dhruv.jpg" height="200" width="200">
</div>
<div CLASS="names">
    <P>AKSHAYAA</P>    
    <P>VIJAY</P>      
    <P>DHONI</P>    
    <P>GV PRAKASH</P>    
    <P>DHRUV VIKRAM</P>    
</div>
<DIV class="position">
    <p>FOUNDER </p>
    <p>CEO </p>
    <p>CO-FOUNDER </p>
    <p>CO-FOUNDER </p>
    <p>DIRECTOR </p>


</DIV>
</body>
<footer style="background-color:darkmagenta;margin-top: 143; border: none;">
    <P style="color:#681010; ;"align="center">Designed and Developed by Akshayaa </P>
</footer>
</html>


contact.html

<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <style>
        b{
            color:rgb(8, 32, 76)
        }
        p {
            color: rgb(10, 44, 73);
        }

        body {
            background:url(black.jpg);
        }

        .yourinfo {
            background:url(black.jpg);
            border:5px solid rgb(129, 10, 10);
            margin-right: 800px ;
            
            margin-top: 200px; /* Adjusted margin-top */
            padding: 10px; /* Added padding for better spacing */
        }
        .yourinfo input[type="text"] {
            width: 500px;
            transition: background-color 0.3s; 
        }
        .yourinfo input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color: #0a375e; /* Adjust the color as needed */
}

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #0d3754;
            color: #531212;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: rgb(14, 77, 77);
            background-color: #4234db;
        }
        .styled form {
            display: flex;
            justify-content: space-evenly;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #0e3c5b; /* initial background color */
            color: #6a2121; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(11, 62, 106); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #072b43; /* initial background color */
            color: #4f0f0f; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:purple; /*background color on hover */
            color:#801919; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:rgb(96, 61, 19);
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(77, 8, 77); /* Adjust the color as needed */
}
    
.company{

margin-left: 900px;
margin-top: -330px;
background:url(bg5.jpg);

scroll-padding-left: 5px;
border:2px solid rgb(90, 23, 23);
}
.message textarea {
        background-color: rgb(95, 17, 17); /* Set the default background color */
        color: rgb(87, 5, 5); /* Set the default text color */
    }

    /* Styles for the text area when it is in focus */
.message    textarea:focus {
        background-color: rgb(20, 86, 86); /* Set the background color when in focus */
        color: rgb(100, 12, 12); /* Set the text color when in focus */
    }
    </style>
</head>
<body>
    <form class="styled">
        <div>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="product.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>
            <input type="text" >
            <input type="submit" value="SEARCH">
        </div>
    </form>
    <div class="yourinfo">
        <center>
        <p>Contact Information</p>
        <div>            
            <input type="text" maxlength="100" placeholder="Your Name"><br><br>
            <input type="text" maxlength="100" placeholder="Your Email"><br><br>
            <div class="message">
            <textarea rows="5" cols="65" placeholder="Your Message"></textarea><br><br>
        </div>
            <input type="button" value="SUBMIT" class="buttons">
        
        </center>
        </div>
    </div>
    <div class="company">
        <center>
        <h3 style="color: rgb(7, 49, 85);">GFA Company Information</h3>
       <p> <b >Address</b></p>
        <p >3766+H3F</p>
        <p >new street</p>
        <p >vellore,TN-632009</p>
        <b >Email:</b>
        <p >akshayaa111426@gmail.com</p>
        <b >Phone</b>
        <p >7010256205</p>
    </center>
    </div>
</body>
<footer style="background-color:darkmagenta;margin-top: 118px; border: none;">
    <P style="color:#752525 ;"align="center">Designed and Developed by Akshayaa </P>
</footer>
</html>
sign.html

<!DOCTYPE html>
<html>
<head>
    <title>Sign Up</title>
    <style>
        body {
            background:url(northern.ligts.jpg);
            background-size: cover;
            color: rgb(60, 48, 31);
            font-family: Arial, sans-serif;
        }

        .form {
            margin: 0 auto;
            width: 300px;
            padding: 20px;
        }

        label {
            color: rgb(63, 39, 22);
        }

        .purpose {
            color: rgb(11, 75, 75);
        }

        .buttons {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #073858;
            color: #510707;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .buttons:hover {
            color: rgb(40, 75, 75);
            background-color: #4234db;
        }
        .styled form {
            margin margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
        .styled [type="button"] {
            padding: 10px 20px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #6f1b1b; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="button"]:hover {
            background-color:purple; /*background color on hover */
            color:rgb(20, 59, 93); /*text color on hover */
        }
        .styled [type="submit"] {
            border-radius: 10px;
            padding: 5px 10px; /* button size */
            background-color: #3498db; /* initial background color */
            color: #a49696; /*initial text color */
            border: none;
            transition: background-color 0.3s, color 0.3s; /*smooth transition */
        }
        .styled [type="submit"]:hover {
            background-color:rgb(9, 1, 9); /*background color on hover */
            color:#463b3b; /*text color on hover */
        }
        .styled [type="text"] {
            margin-left: 500px;
            transition: background-color 0.3s; 
            background-color:rgb(6, 6, 6);
        }
        .styled input[type="text"]:focus {
    /* Change background color when input is focused */
    background-color:rgb(96, 12, 96); /* Adjust the color as needed */
}
.text{
    transition: background-color 0.3s, color 0.3s;

}
.text :focus{
    background-color:rgb(18, 76, 99) 59, 76);  
}
.full{
    background:url(northern.ligts.jpg);
    padding: 10px;
    border:4px double rgb(18, 119, 55);
}
    </style>
</head>
<body>
    <form class="styled ">
        <div class=>
            <a href="home.html">
                <input type="button" value="HOME">
            </a>
            <a href="product.html">
                <input type="button" value="OUR PRODUCTS">
            </a>
            <a href="about.html">
                <input type="button" value="ABOUT US">
            </a>
            <a href="sign.html">
                <input type="button" value="SIGN IN">
            </a>
            <a href="contact.html">
                <input type="button" value="CONTACT">
            </a>  
            <input type="text">
            <input type="submit"value="SEARCH">  
        </div>
    </form>
    <div class="form">
        <p align="center">JOIN THE FAMILY OF GFA Company</p>
        <p align="center">DON'T HAVE AN ACCOUNT YET?</p>
        <div class="full">
        <div class="text">
           
        <label>Unique Username</label>
        <input type="text" value="username"><br><br>
        <label>Email</label>
        <input type="email" value="email"><br><br>
        </div>
        <label>DOB</label>
        <input type="date"><br><br>
        <label>Gender</label><br>
        <div class="purpose">
            <input type="radio" name="gender">Male<br>
            <input type="radio" name="gender">Female<br><br>
        </div>
        <label>Purpose</label><br>
        <div class="purpose">
            <input type="radio" name="purpose">Study<br>
            <input type="radio" name="purpose">Work<br>
            <input type="radio" name="purpose">Partnership<br><br>
        </div>
        <label>Click the checkbox to prove you are human</label>
        <input type="checkbox"><br><br>
        
            <input type="submit" value="CREATE ACCOUNT" class="buttons">
            <input type="submit" value="DOWNLOAD SOFTWARE"class="buttons">
        
    </div>
</div>
</body>
<footer style="background-color:darkmagenta; border: none;">
    <P style="color:#f3ecec ;"align="center">Designed and Developed by Akshayaa</P>
</footer>
</html>
```

## OUTPUT:
![Alt text](<akshu/softapp/static/Screenshot 2024-01-02 152617.png>)

![Alt text](<akshu/softapp/static/Screenshot 2024-01-02 152635.png>)

![Alt text](<akshu/softapp/static/Screenshot 2024-01-02 152653.png>)

![Alt text](<akshu/softapp/static/Screenshot 2024-01-02 152713.png>)

![Alt text](<akshu/softapp/static/Screenshot 2024-01-02 154115.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
