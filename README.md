# 01
interface for the shopping card         
<html> 
 <head> 
  
     <title>Shopping Cart</title> 
     <link rel="stylesheet" href="styles.css"> 
  
 </head> 
 <body style="background-color:grey;"> 
  
<center> <div id="login-section" class="hidden"> 
         <h1><p style="color:black;">Login</h1> 
         <form onsubmit="return login"> 
             <input type="text" id="username" placeholder="Username" required><br> 
             <input type="password" id="password" placeholder="Password" required><br> 
            <input type="password" id="email" placeholder="email" required><br> 
             <button type="submit">Login</button> 
         </form> 
         <pstyle="color:white;">Don't have an account? <a href="#" onclick="showRegistration()">Register here</a></p> 
     </div> </center>
       <center><h1 style="color:white;">or</h1></center>
  
  
        <center> <div id="registration-section" class="hidden"> 
         <h1><p style="color:black;">Register</h1> 
  
         <form onsubmit="return register()"> 
             <input type="text" id="regUsername" placeholder="Username" required><br> 
             <input type="password" id="regPassword" placeholder="Password" required><br>
             <input type="password" id="renter password" placeholder="renter password" required><br>
             <button type="submit">Register</button> 
         </form> 
  
             
     </div> </center> 
         <div id="main-section" class="hidden"> 
         <h1>Shopping Cart</h1> 
  
         <div class="product"> 
         <div class="product">
         <h2>#1</h2>
             <img src="https://th.bing.com/th/id/OIP.Uno6ltXipRB9OgWtI-RqVAHaJ4?w=185&h=247&c=7&r=0&o=5&pid=1.7">
              <h3>US POLO (red & blue checked men shirt)</h3>
             <p style="color:black;">Price: 799/-<del>1500/-</del></p> 
             <p><mark>upto 60% off</mark></p>
             <p style="color:white;">Available in.</p> 
             <button>S</button><button>M</button><button>L</button><button>XL</button><br>
             <p></p><br>
             <button class="add-to-cart" onclick="addToCart('Product 1', 10)">Add to Cart</button> 
         </div> 
  
        
         <h3>#2</h3>
             <img src="https://th.bing.com/th/id/OIP.d79wh0MvHDwGqT-_7dpyywHaIq?w=185&h=216&c=7&r=0&o=5&pid=1.7">
             <h2>Highlander(black plane shirt)</h2>
             <pstyle="color:black;">Price: 499/- <del>1000/-</del></p> 
             <p>(<mark>upto 50%off</mark>)</p>
             <p style="color:white;">Available in.</p> 
             <button>S</button><button>M</button><button>L</button><button>XL</button><br>
              <p></p><br>
             <button class="add-to-cart" onclick="addToCart('Product 2', 20)">Add to Cart</button> 
         </div> 
             </div>
  
        <center> <div class="cart"> 
             <h2>Shopping Cart</h2> 
             <ul id="cart-items"></ul> 
             <p>Total: $<span id="total">0</span></p> 
             <button onclick="checksout()">Checkout</button> 
         </div></center>
     </div>
  
 <script src="script.js"></script> 
 </body> 
 </html
            
            
