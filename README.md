# Movie-Suggested-Website
## This page suggest movies for who don't know what they want to see
### Code Home page 

``` sh
<!DOCTYPE html>
<html>
<head>
	<title>Home page</title>
	<link rel="stylesheet" type="text/css" href="stylep.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>  
</head>
<body>
  <main>  
	<div class="container-fluid">    
    <div class="row ">
      <div class=" col-md-2 col-sm-2 col-lg-2 my-menu">
        
        <!-- this class for logo -->
        <div class="logo"><h1> Logo</h1></div>        
         <!-- this class for menu 1 -->
        <div class="menu1">          
          <div class="menu11">
            <a class="home" href="">Home</a>
          </div>
          <div class="menu12">
            <a class="search" href="">Search</a>
          </div>
          <div class="menu13">
            <a class="library" href="">Your library</a>
          </div>          
        </div> 
        <!-- this class for menu 2 -->
        <div class="menu2">
          <hr  width="100%" size="5px" align="center" color="orange" />  
            <a href="">Action</a></br>
            <a href="">Adventure</a></br>
            <a href="">Comedies</a></br>
            <a href="">Crime Films</a></br>
            <a href="">Drama films</a></br>
            <a href="">Epics/ Historical films</a></br>
            <a href="">Horror</a></br>
            <a href="">Musicals/ Dance films</a></br>
            <a href="">War films</a></br>
            <a href="">Animation</a></br>                       
        </div>
        <!-- this class for menu 3 -->        
        <div class="menu3">
           <hr  width="100%" size="10px" align="center" color="orange" />  
          <a href=""><img id="imgUser" src="user.jpg" width="30px" height="30px" alt=""> Your Account </a>
        </div>
      </div>
      <div class="col-md-10 col-sm-10 col-lg-8">
          <div class="d-flex flex-column">
              <iframe width="1200" height="500" src="https://www.youtube.com/embed/ITlQ0oU7tDA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>              
          <div class="container-fluid my-test">
            <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner ">
                <div class="menu5">
                  <div class="carousel-item active">                  
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0px" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0px" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0px" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                
                  </div>
                  <div class="carousel-item">
                    <iframe width="250" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="250" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="250" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                  
                  </div>
                    <div class="carousel-item">
                      <iframe width="250" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                      <iframe width="250" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                      <iframe width="250" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                  
                    </div>
                  </div>
                </div>              
              <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </a>              
            </div>
          </div>                     
        </div> 
      </div>            
    </div>   
</main>
</body>
</html> 
```
### Code personal pase
```
<!DOCTYPE html>
<html>
<head>
  <title>Personal Wall</title>
  <link rel="stylesheet" type="text/css" href="stylep.css">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  
</head>
<body>
  <main>  
	<div class="container-fluid">    
    <div class="row ">
      <div class=" col-md-2 col-sm-2 col-lg-2 my-menu">
        
        <!-- this class for logo -->
        <div class="logo"><h1> LoGo</h1></div>        
         <!-- this class for menu 1 -->
        <div class="menu1">          
          <div class="menu11">
            <a class="home" href="">Home</a>
          </div>
          <div class="menu12">
            <a class="search" href="">Search</a>
          </div>
          <div class="menu13">
            <a class="library" href="">Your library</a>
          </div>          
        </div> 
        <!-- this class for menu 2 -->
        <div class="menu2">
          <hr  width="100%" size="5px" align="center" color="orange" />  
            <a href="">Action</a></br>
            <a href="">Adventure</a></br>
            <a href="">Comedies</a></br>
            <a href="">Crime Films</a></br>
            <a href="">Drama films</a></br>
            <a href="">Epics/ Historical films</a></br>
            <a href="">Horror</a></br>
            <a href="">Musicals/ Dance films</a></br>
            <a href="">War films</a></br>
            <a href="">Animation</a></br>                       
        </div>
        <!-- this class for menu 3 -->        
        <div class="menu3">
           <hr  width="100%" size="10px" align="center" color="orange" />  
          <a href=""><img id="imgUser" src="user.jpg" width="30px" height="30px" alt=""> Your Account </a>
        </div>
      </div>
      <div class="col-md-10 col-sm-10 col-lg-10">
          <div class="container-fluid my-test">       
            <div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner ">
                <div class="menu5">
                  
                  <div class="carousel-item active">                  
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                  
                  </div>                
                  <div class="carousel-item">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                 
                  </div>              
                  <div class="carousel-item">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                  
                  </div>
                </div>
              </div>
              <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </a>
            </div>
          </div> 
          <div class="container-fluid my-test">
            
            <hr  width="1000px" size="5px" align="center" color="orange" />
            <div id="carouselExampleControls1" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner ">
                <div class="menu5">
                  <div class="carousel-item active">                  
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                  
                  </div>                
                  <div class="carousel-item">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                 
                  </div>              
                  <div class="carousel-item">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                  
                  </div>
                </div>
              </div>
              <a class="carousel-control-prev" href="#carouselExampleControls1" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleControls1" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </a>
            </div>
          </div>
          <div class="container-fluid my-test">
            <hr  width="1000px" size="5px" align="center" color="orange" />
            <div id="carouselExampleControls2" class="carousel slide" data-ride="carousel">
              <div class="carousel-inner ">
                <div class="menu5">
                  <div class="carousel-item active">                  
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                  
                  </div>                
                  <div class="carousel-item">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                 
                  </div>              
                  <div class="carousel-item">
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/PrX1JJ5dduA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/2Mi0CFBghiw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    <iframe width="300" height="200" src="https://www.youtube.com/embed/NrQT3Wlzc3Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>                  
                  </div>
                </div>
              </div>
              <a class="carousel-control-prev" href="#carouselExampleControls2" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </a>
              <a class="carousel-control-next" href="#carouselExampleControls2" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </a>
            </div>
          </div>                    
        </div> 
      </div>            
    </div>
</main>
</body>
</html>
```
### Code Css
```
*{

}
html{
    background-color: #313439;
  }
  .home
  {
    border-color: white;
    border-width: 10px;
  }
  main {
    float: left ;
    margin: 20px;
  }
  .logo
  {
    margin: 20px 60px;
    color: white;
  }
  .my-menu{
    
    border-width: 10px; 
    border: 1px solid black;
    border-radius: 20px 20px 20px 20px;
    background-color: #111111;
  }
  
.menu1
  {
    margin: 20px 2px;    
  }
  .menu11,.menu12,.menu13
  {
    font-size: 25px;
    border-color: #444444;
    border-style: solid;
    border-width: 1px;
    border-radius: 10px 10px 10px 10px;
    background-color: #444444;
    margin: 5px 2px;     
  }
  .home
  {
    margin: 10px 70px;
  }
  .search
  {
    margin: 10px 70px;
  }
  .library
  {
  margin: 10px 39px;
  }
.menu2
  {
     margin: 20px 30px;
  }
.menu3
  {
    font-size: 20px;
    margin-top: 70%;
    float: top;
  }
 
  .carousel-item
  {
    margin: 5px 130px;
    
  }  
  h2
  {
    color: white;
  }
  .my-video
  {
    border: 1px;
    margin: 10px;
  }
  #imgUser
  {
    border-radius: 50% 50% 50% 50%;
  }
  
  
  hr
  {
  color: orange;
  }

```
# thank you for your time 
