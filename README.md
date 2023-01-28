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
Layout CSS
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: black;
  color: black;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px grey;
}

.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: center;
  font-size: 60px;
  background-image: url("https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQMLGfr8uWQjav6EcEUMwetAmvdzhsn2JSNxQ&usqp=CAU");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: white;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: grey;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #004445;
}

.menuitem a {
  text-decoration: none;
  color: white;
}

.content {
  display: block;
  width: 100%;
  background-image:url("https://p4.wallpaperbetter.com/wallpaper/83/705/244/abstract-shapes-colorful-minimalism-wallpaper-preview.jpg");
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
  color: green;
  background-repeat: no-repeat;
  background-size: 100% 100%;

}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
  color: green;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  color: white;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
  color: white;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
  color: white;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: grey;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: white;
}
```
Home.html
```
<body>
    <div class="container">
      <div class="banner">Prakasam Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/html/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/html/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/html/people.html">People</a></div>
        <div class="menuitem"><a href="/static/html/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/logo.png" alt="logo" />
          <div class="contenttext">
            We Prakasam pvt.ltd provide many original softwares for low prices than than the original prices.
            We are the best to provide you many softwares to make your work easy. 
            <br />
            All the softwares are verified and original. All the products will be shipped to your home or 
            college or office within 3 days all over India and will be shipped in 5 days for Overseas.
            <ul>
              <li>All Original Softwares</li>
              <li>Easy to buy</li>
              <li>Can Cancel before 3 days</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Prakasam Private Limited, Developed by Prakasam.
      </div>
    </div>
  </body>
</html>
```
Products.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Prakasam Private Limited</title>
    <link rel="stylesheet" href="../css/layout.css" />
    <link rel="icon" href="../img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Prakasam Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/html/home.html">Home</a></div>
        <div class="menuitemselected"> <a href="/static/html/products.html">Products</a> </div>
        <div class="menuitem"><a href="/static/html/people.html">People</a></div>
        <div class="menuitem"><a href="/static/html/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/71yiZAejRRL._SL1500_.jpg"  alt="product image">
                  </div>
                  <div class="itemname">MacAfee Anti-virus</div>
                  <div class="itemprice">Price: Rs.799/yr </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://m.media-amazon.com/images/I/61H7xThAX2L._SL1500_.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Microsoft Office</div>
                  <div class="itemprice">Price: Rs.7999/yr </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://buy-static.norton.com/norton/ps/ad/pages/in/images/norton-antivirus-1d_r.png" alt="product image">
                </div>
                <div class="itemname">Norton Anti-Virus</div>
                <div class="itemprice">Price: Rs.699/yr </div>
              </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://m.media-amazon.com/images/I/51fOMflEfcL._SL1000_.jpg"  alt="product image">
              </div>
              <div class="itemname">Microsoft Home</div>
              <div class="itemprice">Price: Rs.8000 </div>
            </div>
            <div class="productitem"> 
            <div class="itemimage">
            <img src="https://m.media-amazon.com/images/I/71HpEfZSgkL._SL1500_.jpg"  alt="product image">
            </div>
            <div class="itemname">Microsoft 365 Personal</div>
            <div class="itemprice">Price: Rs.4000 </div>
            </div>
            
            
          <div class="productitem"> 
          <div class="itemimage">
          <img src="https://m.media-amazon.com/images/I/71yVflZyOYL._SL1500_.jpg"  alt="product image">
          </div>
          <div class="itemname">Windows 10</div>
          <div class="itemprice">Price: Rs.10,000 </div>
          </div>
          <div class="productitem"> 
          <div class="itemimage">
          <img src="https://m.media-amazon.com/images/I/71rqzSt18FL._SL1500_.jpg"  alt="product image">
          </div>
          <div class="itemname">Microsoft 365 Family</div>
          <div class="itemprice">Price: Rs.6000</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://m.media-amazon.com/images/I/51OGrl+T1cL._SL1100_.jpg"  alt="product image">
          </div>
          <div class="itemname">QuickHeal Anti-Virus</div>
          <div class="itemprice">Price: Rs.1000/yr </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://m.media-amazon.com/images/I/7194gvJcpyS._SL1500_.jpg"  alt="product image">
          </div>
          <div class="itemname">Avast Anti-Virus</div>
          <div class="itemprice">Price: Rs.799/yr </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://images-na.ssl-images-amazon.com/images/I/41oWzyP0yYL._SX372_BO1,204,203,200_.jpg"  alt="product image">
          </div>
          <div class="itemname">Adobe Photoshop</div>
          <div class="itemprice">Price: Rs.3999/yr </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://m.media-amazon.com/images/I/41-XPb2+0qL.jpg"  alt="product image">
        </div>
        <div class="itemname">Ubuntu</div>
        <div class="itemprice">Price: Rs.9000 </div>
      </div>
      <div class="productitem"> 
      <div class="itemimage">
      <img src="https://m.media-amazon.com/images/I/41yasVr7MIL.jpg"  alt="product image">
      </div>
      <div class="itemname">PureOS</div>
      <div class="itemprice">Price: Rs.16,000 </div>
      </div>
      </div>
          </div>        
        </div>
      <div class="footer">
        Copyright &#169; 2021 Prakasam Private Limited, Developed by Prakasam.
      </div>
    </div>
  </body>
</html>
```

People.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Prakasam Private Limited</title>
    <link rel="stylesheet" href="../css/layout.css" />
    <link rel="icon" href="../img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Prakasam Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/html/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/html/products.html">Products</a>
        </div>
        <div class="menuitemselected"><a href="/static/html/people.html">People</a></div>
        <div class="menuitem"><a href="/static/html/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Council Members</h1>
          <div class="productitem"> 
          <div class="itemimage">
          <img src="https://pbs.twimg.com/profile_images/864282616597405701/M-FEJMZ0_400x400.jpg"  alt="product image">
          </div>
          <div class="itemname">Sundhar Pichai</div>
          <div class="itemprice">CEO</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/78/MS-Exec-Nadella-Satya-2017-08-31-22_%28cropped%29.jpg/1200px-MS-Exec-Nadella-Satya-2017-08-31-22_%28cropped%29.jpg"  alt="product image">
          </div>
          <div class="itemname">Satya Nadella</div>
          <div class="itemprice">MD</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/01/Shantanu_Narayen_-_the_CEO_of_Adobe_Inc.jpg/1200px-Shantanu_Narayen_-_the_CEO_of_Adobe_Inc.jpg"  alt="product image">
          </div>
          <div class="itemname">Shantanu Narayen</div>
          <div class="itemprice">VP of Marketing</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/Mark_Zuckerberg_F8_2019_Keynote_%2832830578717%29_%28cropped%29.jpg"  alt="product image">
          </div>
          <div class="itemname">Mark Zucekrberg</div>
          <div class="itemprice">Cheif Architect</div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://thumbor.forbes.com/thumbor/fit-in/416x416/filters%3Aformat%28jpg%29/https%3A%2F%2Fspecials-images.forbesimg.com%2Fimageserve%2F5c7d7829a7ea434b351ba0b6%2F0x0.jpg%3Fbackground%3D000000%26cropX1%3D206%26cropX2%3D2043%26cropY1%3D250%26cropY2%3D2089"  alt="product image">
        </div>
        <div class="itemname">Mukesh Ambani</div>
        <div class="itemprice">Project Manager</div>
      </div>
      <div class="productitem"> 
      <div class="itemimage">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/ff/Gautam_Adani.jpg"  alt="product image">
      </div>
      <div class="itemname">Gautham Adani</div>
      <div class="itemprice">Technical Lead</div>
      </div>
      </div>
        </div>
      <div class="footer">
        Copyright &#169; 2021 Prakasam Private Limited, Developed by Prakasam.
    </div>    
      </div>
    </div>
  </body>
</html>
```

Contactus.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Prakasam Private Limited</title>
    <link rel="stylesheet" href="../css/layout.css" />
    <link rel="icon" href="../img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Prakasam Private Limited.</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/html/home.html">Home</a></div>
        <div class="menuitem"><a href="/static//html/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/html/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/html/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us</h1>
          <img src="/static/img/logo.png" alt="Logo" />
          <div class="contenttext">
            Email: Prakasampvtltd@gmail.com
            <br>
            Phone: +919876543210
            <br>
            Address: No:88 , PUDHUR , AMBATTUR , CHENNAI - 53.

          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Prakasam Private Limited, Developed by Prakasam.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![output](.d1.png)

### Product Page:
![output](./d2.png)

### People Page:
![output](./d3.png)

### Contact Page:
![output](./d4.png)

### HTML Validator:
![output](./validD.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
