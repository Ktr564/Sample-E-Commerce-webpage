# Sample-E-Commerce-webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>RedShoppe | Ecommerce Website Design</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Joan&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.1/css/fontawesome.min.css">
</head> 
<body>
    
    <div class="header">
    <div class="container">
        <div class="navbar">
        <div class="logo">
             <img src="images/logo.png" width="125px">
        </div>
        <nav>
            <ul id="MenuItems">
                <li><a href ="">Home</a></li>
                <li><a href ="">Products</a></li>
                <li><a href ="">About</a></li>
                <li><a href ="">Contact</a></li>
                <li><a href ="">Account</a></li>
            </ul>
        </nav>
            <img src="images/cart.png" width="30px" height="30px">
            <img src="images/menu.png" class="menu-icon" onclick="menutoggle()">
     </div>
     </div>
        
        <div class="login-page">
           <div class="container">
               <div class="row">
                  <div class="col-2">
                      <img src="images/image1.png" width="100%">
                   </div>
                   <div class="col-2">
                      <div class="form-container">
                            <div class="form-btn">
                              <span onclick="login()">Login</span>
                            <span onclick="register()"> Register</span>
                            <hr id="Indicator">
                          </div>
                          <form id="LoginForm">
                              <input type="text" placeholder="Username">
                              <input type="password" placeholder="Password">
                              <button type="submit" class="btn">Login</button>
                              <a href="">Forgot Password</a>
                          </form>
                          <form id="RegistrationForm">
                              <input type="text" placeholder="Username">
                              <input type="email" placeholder="Email">
                              <input type="Password" class="Password">
                              <button type="submit" class="btn">Register</button>
                          </form>
                       </div>
                   </div>
               </div>
            </div>
        </div>
        
        
        
        
        
        
   <div class="footer">
       <div class="container">
           <div class="row">
               <div class="footer-col-1">
                   <h3>Download App</h3>
                   <p>Download App for Android and ios.</p>
                   <div class="app-logo">
                       <img src="images/play-store.png">
                       <img src="images/app-store.png">
                   </div>
               </div>
                <div class="footer-col-2">
                   <img src="images/logo-white.png"
                   <p>Our purpose is to make the pleasure and benefits of sports accesible to many. </p>
               </div>
                <div class="footer-col-3">
                   <h3>Useful links</h3>
                   <ul>
                        <li>Coupons</li>
                        <li>Blog post</li>
                        <li>Return Policy</li>
                        <li>Join Affiliate</li>
                    </ul>
               </div>
               <div class="footer-col-4">
                   <h3>Social media</h3>
                   <ul>
                        <li>Facebook</li>
                        <li>Instagram</li>
                        <li>Youtube</li>
                    </ul>
               </div>
           </div>
       </div>
   </div>
   
    
    <script>
        var LoginForm= document.getElementById("LoginForm");
        var RegForm= document.getElementById("RegForm");
        var Indicator= document.getElementById("Indicator");
        function register(){
            RegForm.style.transform = "translateX(0px)";
            LoginForm.style.transform = "translateX(0px)";
            Indicator.style.transform = "translateX(100px)";
            
        }
        function login(){
            RegForm.style.transform = "translateX(300px)";
            LoginForm.style.transform = "translateX(300px)";
            Indicator.style.transform = "translateX(0px)";
        }
    </script>
    
    
</body>
</html>     
