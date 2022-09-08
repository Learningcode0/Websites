<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-
    awesome/6.2.0/css/all.min.css">
    <title>My Portfolio !</title>
</head>
<body>
    
<!----Start of Portfoilio---->
   
    <div class="hero">
        <nav>
            <span>
            <h2 class="logo">Portfo<span>lio</span></h2>
            </span>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Skills</a></li>
                <li><a href="#">More</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
            <a href="#" class="btn">Subscribe</a>
            </div>
        </nav>  
    <div class="content">
            <h4>Hello, My name is</h4>
            <h1>Ahmari <span>Ferreira</span></h1>
            <h3>I'am a Front-End Web Dev.</h3>
            <div class="newslatter">
                <form>
                    <input type="email" name="email" id="mail" placeholder="Enter Your email">
                    <input type="submit" name="submit" id="mail" Value="lets start">
                </form>
            </div>
        </div>
    </div>
    
    <!----About Section Start---->
    <section class="about">
        <div class="main">
        <img src="img/images.lpg.jpg" alt="">
        <div class="about-text">
        <h2>About Me</h2>
        <h5>FrontEndDev & <span>Desginer</span></h5>
        <p>I am a Front-End Developer. I can provide you good Working websites for you.
            I can Build Tribute pages, application's, landing pages etc.......
            I also make websites more responsive or any kind of way the consumer like it. 
            I'am also learning Javascript.</p>
           <Button type="button">Let's Talk</Button>
            </div>
        </div> 
     </section>
     
     
     <!------service section start------>
<div class="service">
    <div class="title">
        <h2>Our Service</h2>
    </div>
    
    <div class="box">
        <div class="card">
            <h5><em>Web Development</em></h5>
            <div class="pra">
                <p><em>Every website should be Build with teo primary goals:
                site needs to be working across all devices, vest fast responsive site.</em></p>

                <p style="text-align: center;">
                    <a class="button" href="#">Read More</a>
                </p>
            </div>
        </div>
        
        <div class="card">
            <h5>Web Development</h5>
            <div class="pra">
                <p><em>Every website should be Build with teo primary goals:
                site needs to be working across all devices, vest fast responsive site.</em></p>

                <p style="text-align: center;">
                    <a class="button" href="#">Read More</a>
                </p>
            </div>
        </div>
        <div class="card">
            <h5>Web Development</h5>
            <div class="pra">
                <p>Every website should be Build with teo primary goals:
                site needs to be working across all devices, vest fast responsive site.</p>

                <p style="text-align: center;">
                    <a class="button" href="#">Read More</a>
                </p>
            </div>
        </div>
    </div>
</div>

  <!------Contact Me------>
  <div class="contact-Me">
    <p>Let me Build You a Fast responsive website.</p>
    <a class="button-two" href="#">Hire Me</a>
  </div>

  <!---Footer Start--->
  <footer>
    <p>Ahmari Ferreira</p>
    <P>For More HTML, CSS, and coding tutorial - please click on the link below to 
        Subscribe to my channel</P>
        <p class="end">CopyRight By Ahmari Ferreira
            <a id="tribute-link"href="https://www.youtube.com/channel/UCgRWHT8ycXEUJbWam0hILtA">Youtube</a>
        </p>
  </footer>
</body>
</html




*{
margin: 0px;
padding: 0%;
font-family: monospace;
box-sizing: border-box;
}

.hero{
    height: 100vh;
    width: 100%;
    background-size: cover;
    background-position: center;
    background-image: url(img/Darkness-landscape-wallpaper_950.jpeg);
    }

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 45px;
    padding-left: 8%;
    padding-right: 8%;
}

.logo{
    color: white;
    font-size: 35px;
    letter-spacing: 1px;
    cursor: pointer;

}

span{
   color: rgb(236, 17, 17);
}

nav ul li{
    list-style-type: none;
    display: inline-block;
    padding: 10px 25px;
    font-size: 15px;
}

nav ul li a{
    color: white;
    text-decoration: none;
    font-weight: bold;
    text-transform: capitalize;
}

nav ul li a:hover{
    color: rgb(236, 17, 17);
    transition: .4s;
}
.btn{
    background-color: rgb(236, 17, 17);
    color: white;
    text-decoration: none;
    border: 2px solid transparent ;
    font-weight: bold;
    padding: 10px 25px;
    border-radius: 30px;
    transition: transform .4s;
}

.btn:hover{
    transform: scale(1.2);
}

.content{
    position: absolute;
    top: 50%;
    left: 8%;
    transform: translateY(-50%);
}

h1{
    color: white;
    margin: 20px 0px 20px;
    font-size: 75px;

}
h3{
    color: white;
    margin-bottom: 50px;
    font-size: 25px;
}
h4{
    color: white;
    margin-top: 50px;
    font-size: 20px;
    letter-spacing: 2px;
}
.newslatter form{
    width: 380px;
    max-width: 100%;
    position: relative;

}
.newslatter form input:first-child{
    display: inline-block;
    width: 100%;
    padding: 14px 130px 14px 15px;
    border: 2px solid rgb(236, 17, 17);
    outline: none;
    border-radius: 30px;
}
.newslatter form input:last-child{
display: inline-block;
position: absolute;
outline: none;
border: none;
padding: 10px 30px;
border-radius: 30px;
background-color: rgb(236, 17, 17);
color: white;
box-shadow: 0px 0px 5px rgb(236, 17, 17), 0px 0px 15px #858585;
top: 6px;
right: 6px;
}
.about{
    width: 100%;
    padding: 100px 0px;
    background-color: #191919;
}
.about img{
    height: auto;
    width: 430px;
}
.about-text{
    width: 550px;
}
.main{
    width: 1130px;
    max-width: 95%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.about-text h2{
    color: white;
    text-transform: capitalize;
    font-size: 75px;
    margin-bottom: 20px;
}
.about-text h5{
    color: white;
    letter-spacing: 2px;
    font-size: 22px;
    margin-top: 25px;
    text-transform: capitalize;
}
.about-text p{
    color: rgb(141, 137, 137);
    letter-spacing: 1px;
    line-height: 28px;
    font-size: 18px;
    margin-bottom: 45px;
}
button{
    color: white ;
    background-color:rgb(236, 17, 17) ;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 13px 30px;
    border-radius: 30px;
    transition: .4s;

}
button:hover{
    background-color: transparent;
    border: 2px solid rgb(236, 17, 17);
    cursor: pointer;

}
.service{
background: #101010;
width: 100%;
padding: 100px 0px;
}
.title h2{
    color: white;
    font-size: 75px;
    width: 1130px;
    margin: 30px auto;
    text-align: center;
}
.box{
    justify-content: center;
    display: flex;
    align-items: center;
    min-height: 400px;
}
.card{
    height: 365px;
    width: 335px;
    padding: 20px 35px;
    background: #191919;
    border-radius: 20px;
    margin: 15px;
    position: relative;
    overflow: hidden;
    text-align: center;
}
.card i{
    font-size: 50px;
    display: block;
    text-align: center;
    margin: 25px 0px;
    color: red;
}
h5{
    color: white;
    font-size: 23px;
    margin-bottom: 15px;
}
.pra p{
color: #858585;
font-size: 16px;
line-height: 27px;
margin-bottom: 25px;
}
.card .button{
    color: white ;
    background-color:rgb(236, 17, 17) ;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 9px 22px;
    border-radius: 30px;
    transition: .4s;
   }
   .card .button:hover{
    background-color: transparent;
    border: 2px solid rgb(236, 17, 17);
    cursor: pointer;
}
.contact-Me{
width: 100%;
height: 290px;
background-color: #191919;
display: flex;
align-items: center;
flex-direction: column;
justify-content: center;
}
.contact-Me p{
    color: white;
    font-size: 30px;
    font-weight: bold;
    margin-bottom: 25px;
}
.contact-Me .button-two{
    color: white ;
    background-color:rgb(236, 17, 17) ;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 13px 30px;
    border-radius: 30px;
    transition: .4s;
}
.contact-Me .button-two:hover{
    background-color: transparent;
    border: 2px solid rgb(236, 17, 17);
    cursor: pointer;
}
footer{
    position: relative;
    width: 100%;
    height: 400px;
    background-color: #101010;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    }
    footer p:nth-child(1){
        font-size: 30px;
        color: white;
        margin-bottom: 20px;
        font-weight: bold;
    }
    footer p:nth-child(2){
        color: white;
        font-size: 17px;
        width: 500px;
        text-align: center;
        line-height: 20px;
    }
    .social{
        display: flex;
    }
    .social a{
        width: 45px;
        height: 45px;
        align-items: center;
        display: flex;
        justify-content: center;
        background-color: rgb(236, 17, 17);
    }
.end{
    position: absolute;
    color: rgb(236, 17, 17);
    bottom: 35px;
    font-size: 14px;
}
