<!DOCTYPE html>
<html lang="en">
<head>
    <title>Olympics</title>
    <!-------corousel-------------------------------------------------------------------------------------------------->
     <meta charset="utf-8">
     <meta name="viewport" content="width=device-width, initial-scale=1">
     <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
     <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
     <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    <!-----css---------------------------------------------------------------------------------------------------------->
    <link rel="stylesheet" href="olymp.css">        
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" >
    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <!-------------------w app------------------------------------------------------------------------------------------->
    
</head>
<!-------body----------------------------------------------------------------------------------------------------->
<body >
    
  <section id="nav-bar" style="font-size: 15px"  >
    <nav class="navbar navbar-expand-lg navbar-light bg-dark">
  <a class="navbar-brand" href="" ><img src="https://stillmed.olympic.org/media/Images/OlympicOrg/Global/logo.png?interpolation=lanczos-none&resize=90:*" height="50px" width="100px"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
<!-------------icon--------------------------------------------------------------------------------------------->      
      
    <span class="navbar-toggler-icon"></span>
  </button>
<!-----------------------------------nav-bar--------------------------------------------------------------------------------->
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav ml-auto">
      <li class="nav-item active ml-auto">
        <a class="nav-link dropdown-toggle" href="#" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true" style="font-size: 20px;float: right; color: white;">Home </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown" style="font-size:15px;float: right;">
        <i class="fa fa-angle-down" aria-hidden="true"></i>
          <a class="dropdown-item" href="#Games" role="button">games</a>
          <a class="dropdown-item" href="#social-media">social media</a>
    
          <a class="dropdown-item" href="#vam">vision and mission</a>
        </div>  
      </li>
      <li class="nav-item">
        <a class="nav-link" href="https://www.olympicchannel.com/en/live/" style="color:red; font-size:15px ">Live</a>
      </li>
<!-------------------------dropdown------------------------------------------------------------------------------------------->
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true" style="font-size: 15px">
         About
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown" style="font-size:15px">
          <a class="dropdown-item" href="history.html" role="button">History</a>
          <a class="dropdown-item" href="partners.html">Partners</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="https://www.olympic.org/prevention-competition-manipulation/regulations-legislation">Rules and regulations</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link news" role="button" href="https://news.google.com/search?q=olympics%20updates&hl=en-IN&gl=IN&ceid=IN%3Aen">News</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0" >
      <input  id="ids" name="ids"class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search" style="font-size:16px" method="POST" action="olymp.php" required autocomplete="off">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit" style="font-size:12px">Search</button>
    </form>
  </div>
</nav>  
</section> 
<!----------------corousel effect---------------->
<section id="corousel" >
  <div class="container" > 
  <div id="myCarousel" class="carousel slide" data-ride="carousel" >
    <!-- Indicators -->
  <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
  </ol>

     <!-- Wrapper for slides -->
   <div class="carousel-inner" style="height:400px;">
   <div class="item active">
   <img src="https://cdn.pixabay.com/photo/2013/02/09/04/23/swimmers-79592_960_720.jpg" alt="Aquatics" style="width:100%;">
   </div>

   <div class="item">
        <img src="https://cdn.pixabay.com/photo/2016/03/09/09/10/man-1245658_960_720.jpg" alt="Running" style="width:100%;">
   </div>
    
   <div class="item">
        <img src="https://cdn.pixabay.com/photo/2017/06/07/09/04/shuttlecock-2379720_960_720.jpg" alt="Badminton" style="width:100%;">
   </div>
   </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>
 </section> 
<!------------------------------------------introduction---------------------------------------------------->    
    <section id="intro" style="font-size:15px ">
    <div class="row">
    <div class="col-md-12">       
    <H1>WORLD OLYMPICS</H1>
     <p>The Olympic Games are an international sports festival that began in ancient Greece. The original Greek games were staged every fourth year for several hundred years, until they were abolished in the early Christian era. The revival of the Olympic Games took place in 1896, and since then they have been staged every fourth year, except during World War I and World War II</p>   
        <p> The earliest reliable date that recorded history gives for the first Olympics is 776 B.C., although virtually all historians presume that the Games began well before then.It is certain that during the midsummer of 776 B.C. a festival was held at Olympia on the highly civilized eastern coast of the Peloponnesian peninsula. That festival remained a regularly scheduled event, taking place during the pre-Christian golden age of Greece. As a testimony to the religious nature of the Games (which were held in honor of Zeus, the most important god in the ancient Greek pantheon), all wars would cease during the contests.</p>
        </div>
        </div> 
    </section><br><br><br><br>
    <!---------------------------------------------------Games------------------------------------------------------------>
   <section id="Games">
     <div class="container text-center">
    <h1 class="title">Games</h1><br><br>
    <div class="row text-centre">
    <div class="col-md-4 Games" style="font-size:15px;text-align: left; ">
    <ul>
       <li><u>Aquatics</u></li> 
        <li><u>Archery</u></li> 
        <li><u>Athletics</u></li> 
        <li><u>Badminton</u></li> 
        <li><u>Baseball</u></li> 
        <li><u>Basketball</u></li> 
        <li><u>Boxing</u></li> 
        <li><u>Canoe</u></li> 
        <li><u>Cycling</u></li> 
        <li><u>Equestrain</u></li> 
    </ul>
        
    </div> 
     <div class="col-md-4 Games" style="font-size:15px;text-align: left;">
     <ul>
       <li><u>Fencing</u></li> 
        <li><u>Football</u></li> 
        <li><u>Golf</u></li> 
        <li><u>Gymnastics</u></li> 
        <li><u>Handball</u></li> 
        <li><u>Hockey</u></li> 
        <li><u>Judo</u></li> 
        <li><u>Karate</u></li> 
        <li><u>Modern Pentathlon</u></li> 
        <li><u>Rowing</u></li> 
    </ul>
         
         
    </div> 
     <div class="col-md-4 Games" style="font-size:15px;text-align: left;">
    <ul>
       <li><u>Rugby</u></li> 
        <li><u>Sailing</u></li> 
        <li><u>Shooting</u></li> 
        <li><u>Skateboarding</u></li> 
        <li><u>Sport Climbing</u></li> 
        <li><u>Surfing</u></li> 
        <li><u>Table Tennis</u></li> 
        <li><u>Tennis</u></li> 
        <li><u>volleyball</u></li> 
        <li><u>Weightlifting</u></li>
        <li><u>Wrestling</u></li>
    </ul>
    </div> 
    </div>
        <button type="button" class="btn btn-primary">About games</button>
    </div>
     </section>
<!-------------------------------------------------vision and mission--------------------------------------------------------> 
    <section id="vam">
     <div class="vm text-center">
    <h1 class="title">VISION AND MISSION</h1><br><br>
    <div class="row text-centre">
    <div class="col-md-6 vm" style="text-align:center;">
      <h4 style="font-size:20px"><u>VISION</u></h4> 
        <p style="font-size:18px">Buildig a better world through sport</p>
        <P  style="font-size:18px"><b>Values:</b></P>
        <ul  style="font-size:18px">
        <li style="color: red">Excellence</li>
         <li style="color: blue">Respect</li>
         <li style="color: green">Friendship</li>
        </ul>
    </div>
      <div class="col-md-6 vm" style="font-size:15px;text-align: left; ">
      <a> <img class="vis" src="https://i.ytimg.com/vi/f-RNRgQ0NP8/maxresdefault.jpg" height="400px" width="100%"></a> <br>
     </div>
         <div class="col-md-6 vm" style="font-size:15px;text-align: left; ">
     <a> <img src="https://stillmed.olympic.org/media/Images/OlympicOrg/News/General/olympic-flag.jpg" height="400px" width="100%"></a>     
    
    </div>
         <div class="col-md-6 vm" style="font-size:15px;text-align: left; ">
      <h4 style="font-size:20px"><center><U>MSSION</U></center></h4> 
        <ul style="font-size:18px">     
        <li>Ensure the uniqueness and the regular celebration of the olympic games</li>    
        <li>Put athletes at the heart of the olympic movement </li>   
        <li>Promote sport and olympic values in society, with a focus on young people</li>
    </ul>
    </div>
        
        </div>
        </div> 
    </section>
<!---------------------------------------------social media---------------------------------------------------------------------->
    <section id="social-media">
        <div class="container text-center">
        <p><u> FIND US ON SOCIAL MEDIA</u></p>
            <div class="social-icons">
            <a href="#"><img src="whatsapp.png"></a>
             <a href="#"><img src="facebook.png"></a>
             <a href="#"><img src="insta.png"></a>
            <a href="#"><img src="linkin.png"></a>
            <a href="#"><img src="youtube.png"></a>
             <a href="#"><img src="twitter.png"></a>
            </div>
            </div>
    </section>
<!--------------------------------------------contact us------------------------------------------------------>    
     <div class="contact us">
    <h1 class="title text-center"> CONTACT US </h1><br><br>
         <center>
         <P style="font-size:12px "><B> For any query, suggestion or feedback, feel free to contact us using below details.</B></P>
             <P style="font-size:12px "><B>  contact us on.</B></P>
           <P style="font-size:12px "><B> <i class="fa fa-phone"></i>+91 9606507688</B></P>
           <P style="font-size:12px "><B><i class="fa fa-envelope-o"></i>yashwanth5181@gmail.com</B></P>
         </center>
        </div>   
        <div>
            <center>
            <p><b>REGISTER NOW FOR join us</b></p>
            <input type="E mail" class="form-control" placeholder="enter your Email">
            <button type="button" class="btn btn-primary">REGISTER</button>
            </center>
            </div>
        
        <div>
            <center>
            <hr>
            <p class="copyright" style="color:red"> website created by Ranjith  </p>
            </center>
        </div>
    <!-----------smooth scroll------------->
        <script src="smooth-scroll.js"></script>
        <script>
	var scroll = new SmoothScroll('a[href*="#"]');
</script>
</body>


</html>
