


<!-- <html lang="en">
<head>
<script type="text/javascript" src="https://platform.linkedin.com/badges/js/profile.js" async defer></script>
    <script src="https://code.jquery.com/jquery-1.10.2.js"></script>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
</head> 

<body>
<p>Hello World</p> 
<div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="en_US" data-type="horizontal" data-theme="dark" data-vanity="michael-alleyne-126aa8191"><a class="LI-simple-link" href='https://www.linkedin.com/in/michael-alleyne-126aa8191?trk=profile-badge'>michael alleyne</a></div>
</body> 
</html> 


 -->


 <!doctype html>
<html lang="en">
<head>
  <script src="https://kit.fontawesome.com/d69b1b7db0.js" crossorigin="anonymous"></script>
  <script type="text/javascript" src="https://platform.linkedin.com/badges/js/profile.js" async defer></script>
    <script src="https://code.jquery.com/jquery-1.10.2.js"></script>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
    <link rel="stylesheet" href="indexstyles.css"> 
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>

<script>
function printContact(){

  $("div.border1").replaceWith( `<div class=" col-sm border1 rounded col-spacing"> <!-- contact section -->
      <h3>Contact</h3> 
      <div class="row"> 
        <p class="col">Name: Michael Alleyne </p>
        <!-- <div class="col"> 2</div> -->
      </div>
      <div class="row"> 
        <p class="col">Ph: 914-882-5427 </p>
        <!-- <div class="col">4</div> -->
      </div>
      <div class="row"> 
        <p class="col">Email: malleyne747@gmail.com </p>
        
      </div>
      <div class="row"> 
        <p class="col">Github: https://github.com/malleyne747 </p>
        <a href="https://github.com/malleyne747"> <i class="fab fa-github fa-2x"></i> </a>
      </div>
      <div class="row"> 
        <p class="col">Download CV: </p>
        <a href="resume-pdf.pdf"> <i class="fas fa-file-download fa-2x "></i> </a>
      </div>
      </div>`); 
  // $("#li-badge").html(` <div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="en_US" data-type="horizontal" data-theme="light" data-vanity="michael-alleyne-126aa8191"><a class="LI-simple-link" href='https://www.linkedin.com/in/michael-alleyne-126aa8191?trk=profile-badge'>michael alleyne</a></div>`); 
  }
function printAbout(){
  
  $("div.border1").replaceWith(`<div class="col-sm border1 rounded col-spacing "> <!-- about section -->
      <h3> About me </h3> 
      <p>Hello, my name is Michael Alleyne. I am a technical support engineer currently based in North Carolina.</p>
      <p>I love technology and working with people. In my current role I provide B2B support for WalkMe's Digital adoption platform</p>
      <p> Some of my interests outside of work include Music, Travel and Food.</p> 
      <p> Thank you for taking the time to view my Page! you may click "Resume" to the left in order to view an embeded version of my resume and download a copy of it.</p>  
    </div>`); 
}
function printResume(){
  $("div.border1").replaceWith(`<div class="resume col-sm border1 rounded col-spacing "> <!-- Resume section -->
      <h3> Resume</h3> <embed src="resources/resume-pdf.pdf" type="application/pdf" width="100%" height="100%"> </div> `); 
}

function printWork(){
  $("div.border1").replaceWith(`<div class="resume col-sm border1 rounded col-spacing "> <!-- Resume section -->
      <h3>Recent Work</h3> <embed src="resources/resume-pdf.pdf" type="application/pdf" width="100%" height="100%"> </div> `); 
}
 </script>
}

</head> 

<body>



<div class="container">
  <div class="row">
    <ul class="list-group">
      <li onclick="printAbout()" class="list-group-item"> About me </li>
      <li onclick="printContact()" class="list-group-item"> Contact </li>
      <li onclick="printAbout()" class="list-group-item"> Recent work </li> 
      <li onclick="printResume()" class="list-group-item"> Resume </li>
    </ul>
    <div class="col-sm border1 rounded col-spacing "> <!-- about section -->
      <h3> About me </h3> 
      <p>Hello, my name is Michael Alleyne. I am a technical support engineer currently based in North Carolina.</p>
      <p>I love technology and working with people. In my current role I provide B2B support for WalkMe's Digital adoption platform</p>
      <p> Some of my interests outside of work include Music, Travel and Food.</p> 
      <p> Thank you for taking the time to view my Page! you may click "Resume" to the left in order to view an embeded version of my resume and download a copy of it.</p>  
    </div>
    <div class="col-sm border2 rounded col-spacing "> <!-- Linkedin section -->
      <h3> Linkedin </h3> 
      <div id="li-badge"><div class="LI-profile-badge"  data-version="v1" data-size="medium" data-locale="en_US" data-type="horizontal" data-theme="dark" data-vanity="michael-alleyne-126aa8191"><a class="LI-simple-link" href='https://www.linkedin.com/in/michael-alleyne-126aa8191?trk=profile-badge'>michael alleyne</a></div></div>
  </div>
    
    </div>
</div>


</body> 
</html> 


