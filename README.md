<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym</title>
    <style>
        *{
    margin: 0;
    padding: 0;
} 


header {
  background-color: #fff;
  color: black;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 70px;
  
}

header img {
margin-left: 5px;

}

nav ul {
  list-style-type: none;
  display: flex;
}

nav ul li {
  margin: 20px 20px;
  
}

nav ul li a {
  color: #130e0e;
  
  font-size: 25px;
  text-decoration: none;
}
nav ul li a:hover{
  color:black;
  

}


h1 {
    text-align: center;
    color: orange;
}

/* Photo Section */
.photos {
    display: flex;
    justify-content: center;
    gap: 50px; /* Proper spacing between photos */
    margin: 40px;
    padding: 20px;
    flex-wrap: wrap;
}

/* Individual Photo Card */
.photo {
    width: 300px; /* Adjust width to match image style */
    text-align: center;
    border: none; /* Removed border for cleaner look */
}

/* Image Styling */
.photo img {
    width: 100%;
    height: auto;
    border-radius: 5px; /* Slightly rounded corners */
}

/* Heading Styling */
.photo h2 {
    font-size: 20px;
    font-weight: bold;
    color: #000;
    margin-top: 15px;
}

/* Description Text */
.photo p {
    font-size: 18px;
    color: gray;
    line-height: 1.9;
    padding: 0 10px;
}
button {
        padding: 10px 20px;
        background-color: white;
        color: black;
        
        border-radius: 5px;
        cursor: pointer;
        font-size: 16px;
        transition: background-color 0.3s ease; /* Smooth transition */
    }
    
    button:hover {
        background-color: orange;
        color: black;/* Optional: change text color for better contrast */
    }
    
    

footer {
    background-color: black;
    color: white;
    text-align: center;
    padding: 20px 10px;
    font-size: 14px;
    margin-top: 50px;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    max-width: 1200px;
    margin: auto;
    padding: 10px;
}

.footer-left, .footer-center, .footer-right {
    flex: 1;
    text-align: center;
}

.footer-left p, .footer-right p {
    margin: 5px 0;
}

.footer-center a {
    color: white;
    text-decoration: none;
    margin: 0 10px;
    font-weight: bold;
}

.footer-center a:hover {
    text-decoration: underline;
}

.footer-left a {
    color: orange;
    text-decoration: none;
    font-weight: bold;
}

.footer-left a:hover {
    text-decoration: underline;
}

    </style>
    
</head>
<body>
    <header>
        <img src="https://img1.wsimg.com/isteam/ip/282a0fb7-7f88-41cf-980e-f0ecae91f95f/Burn%20Logo.png/:/rs=w:535,h:100,cg:true,m/cr=w:535,h:100/qt=q:100/ll">
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="form.html">Contact us</a></li>
                
            </ul>
        </nav>
    </header>
    <img src="https://img1.wsimg.com/isteam/ip/282a0fb7-7f88-41cf-980e-f0ecae91f95f/banner-6-dec-b0d5640.jpeg/:/rs=w:1280,h:483" alt="logo" height="570"><br><br><br>
    <h1>Burn Gym- Premium Fitness Club
    </h1>
    <div class="photos">
        <div class="photo">
            <img src="https://img1.wsimg.com/isteam/ip/282a0fb7-7f88-41cf-980e-f0ecae91f95f/2022-09-24%20(1).jpg/:/cr=t:0%25,l:0%25,w:100%25,h:100%25/rs=w:365,h:365,cg:true" alt="image 1">
            <h3>Phase 9, Mohali</h3>
            <p>Burn Gym was founded with the belief that fitness should be accessible to everyone. Our founder, John, struggled to find a gym that he felt comfortable in, so he decided to create his own. Today, Burn Gym is a thriving community of members who share John's vision.

            </p>
            <button>GET A FREE TRIAL</button>
        </div>
        <div class="photo">
            <img src="https://img1.wsimg.com/isteam/ip/282a0fb7-7f88-41cf-980e-f0ecae91f95f/ph%205-5.jpg/:/cr=t:0%25,l:0%25,w:100%25,h:100%25/rs=w:365,h:365,cg:true" alt="image 2">
            <h3>Phase 5,Mohali</h3>
            <p>BURN believes in empowering you to take care of your body, strengthening and improving your potency at the same time. We believe that while exercising is important to maintain a good shape, it should also be a way of life.

            </p>
            <button>GET A FREE TRIAL</button>
        </div>
        <div class="photo">
            <img src="https://img1.wsimg.com/isteam/ip/282a0fb7-7f88-41cf-980e-f0ecae91f95f/2023-01-23-a18d77f.jpg/:/cr=t:0%25,l:12.5%25,w:75%25,h:100%25/rs=w:365,h:365,cg:true" alt="image 3">
            <h3>Sector 8, Chandigarh</h3>
            <p> At Burn Gym, we give you the option to employ a personal trainer who would exclusively work with you to help achieve your fitness goals. We employ the best personal trainers in Chandigarh for keeping track of your fitness. 

            </p>
            <button>GET A FREE TRIAL</button>
        </div>
  
         
    </div>
    <footer>
        <div class="footer-content">
            <div class="footer-left">
                <p>Copyright © 2024 Burn Gym - All Rights Reserved.</p>
                <p>Mobile no - 08360603201 | <a href="mailto:abcd1444@gmail.com">abcd1444@gmail.com</a></p>
            </div>
            <div class="footer-center">
                <a href="#">HOME</a>  
                <a href="#">PRIVACY POLICY</a>
            </div>
            <div class="footer-right">
                <p>Powered by xyz</p>
            </div>
        </div>
    </footer>
    
    
</body>
</html>     
