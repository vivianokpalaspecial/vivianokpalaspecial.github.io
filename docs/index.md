<!doctype html>
<html lang="en">
  <head>
    <title>Portfolio</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<link rel="stylesheet" href="index.css">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
  </head>      

<body>

  <!-------******Social Media Icon*****------->
    <div class="icon-bar">
      <a href="#" class="facebook"><i class="fa fa-facebook"></i> Facebook</a> 
      <a href="#" class="twitter"><i class="fa fa-twitter"></i>Twitter</a> 
      <a href="#" class="google"><i class="fa fa-google"></i>google</a> 
      <a href="#" class="linkedin"><i class="fa fa-linkedin"></i>LinkedIn</a>
      <a href="#" class="youtube"><i class="fa fa-youtube"></i>Youtube</a> 
    </div>
    
<!--------******Header******----------->
  <div class="jumbotron text-center" style="height: 100px;">
    <img class="img-fluid rounded-pill" src="images\my logo.jpg" style="width: 50px; float: left;">
          
    <h1><blockquote><b><strong>MY PORTFOLIO</strong></b></blockquote></h1>
    <p id="today"></p>
    <script>
    const d = new Date();
    document.getElementById("today").innerHTML = d;
    </script> 
    </div>
  </div>
 
  
  <!--------*****Login***-------->
  <button class="open-button" onclick="openForm()">Login</button>

  <div class="form-popup" id="myForm">
    <form action="/action_page.php" class="form-container">
      <h1>Login</h1>
  
      <label for="email"><b>Email</b></label>
      <input type="text" placeholder="Enter Email" name="email" required>
  
      <label for="psw"><b>Password</b></label>
      <input type="password" placeholder="Enter Password" name="psw" required>
  
      <button type="submit" class="btn">Login</button>
      <button type="button" class="btn cancel" onclick="closeForm()">Close</button>
    </form>
  </div>
  
  <script>
  function openForm() {
    document.getElementById("myForm").style.display = "block";
  }
  
  function closeForm() {
    document.getElementById("myForm").style.display = "none";
  }
  </script>



<!--------********Navbar*******------>


<button class="tablink" onclick="openPage('Home', this, 'red')" id="defaultOpen">HOME</button>
<button class="tablink" onclick="openPage('Education', this, 'green')">Education</button>
<button class="tablink" onclick="openPage('Experiences', this, 'blue')">Work Experiences</button>
<button class="tablink" onclick="openPage('Services', this, 'orange')">Services</button>



<!--------****Home*****------------->
<div id="Home" class="tabcontent">
    <div class="content">
      <div class="row">
        <div class="col-7">
                <p> Hi! I'am <h1>Vivian Okpala</h1></p>
        <br> Am a <h1>Web Developer and Educator</h1>,
        I Specialize in the Design and Development <br>
        of Responsive and interactive Websites.
             <h1>Hire Me</h1> 
               
         

             <!-----------****Progress Bar******------------->
          <div class="container" style="width: 200px; float: left;">
            <h5>My Programing skills</h5>
            <p>HTML</p>
            <div class="progress">
              
              <div class="progress-bar" style="width:95%">95%</div>
            </div>
            <p>CSS</p>
            <div class="progress">
              
              <div class="progress-bar" style="width:80%">80%</div>
            </div>
            <p>JAVASCRIPT</p>
            <div class="progress">
              
              <div class="progress-bar" style="width:30%">8%</div>
            </div>
            <p>PHP</p>
            <div class="progress">
              
              <div class="progress-bar" style="width:70%">70%</div>
            </div>
            <p>BOOTSTRAP</p>
            <div class="progress">
              
              <div class="progress-bar" style="width:70%">70%</div>
            </div>
          </div>
        </div>
      
            <div class="col-5">
                <img class="img-fluid" src="images\DSC_4000.JPG">
                      </div>
  </div>
    </div>
</div>
</div>



  <!-- **********EDUCATION & CERTIFICATIONS ************* -->  
<div id="Education" class="tabcontent">

    <div class="container">
     
        <section class="section1">
          <h3>LinkedIn  learning CERTIFICATIONS</h3>
          <p>Web Development Certifications  Certificate, 2022</p>
      .<p>developed skills in Html, CSS Bootstrap Frameworks and JavaScripts throught the LinkedIn learning training by</p>
          <p> Christinatruong on LinkedIn < a ref "https://www.linkedin.com/in/christinatruong/</a></p>
          <p> certifications by Codenga in Python I and II</p>
        </section>

        <section class="section2">
          <h3>NNamdi Azikiwe University, Awka</h3>
          <p>Ph. D Student in Public Health Edu. 2015-Present</p>
          <p>Majoring in the area of Mental Health </p>
        </section >

        <section class="section3">
          <h3>NNamdi Azikiwe University, Awka</h3>
          <p>M.Sc. in Public Health Edu. 2011-2014</p>
          <p>Majored in Occupational Health and Safety</p>
        </section >

        <section class="section4">
          <h3>NNamdi Azikiwe University, Awka</h3>
          <p>B.Sc. (Ed). In Health Edu</p>
        </section 
      
    
    </section 
</div>
</div>
</div>


<div id="Services" class="tabcontent">
  <h3>Contact</h3>
  <p><article>
    <h3>Work Experiences</h3>
    <img class="img-fluid rounded-circle" src="iimages\DSC_3915.JPG" style="width: 200px;">
    <h3>The Wire Ipsum</h3>
    <p>After coming back from teaching a JavaScript workshop, I felt inspired to create something just for fun. 
      <p>I realized that of all the content/lorem ipsum generators available, there was nothing for HBO’s The Wire fans.</p>
      <p> I searched for <a href="http://thewireipsum.com" target="_blank">thewireipsum.com</a> domain and it was available!</p><p> Generate some content for your projects today.</p     <a class="btn" href="http://thewireipsum.com" target="_blank">View live site</a>
      </article>
  </p>
</div>

<div id="About" class="tabcontent">
   
<div class="container">
  <header>
    <h1>ABOUT ME</h1>
    <h1> <b>
  
      <i>Vivian Okpala</i>
    </b></h1>
  </header>
     
  <p>
          My name is Vivian Okpala, am a Front-end Web Developer, a Health Blogger, a Public Health Educator, a Fashion Designer,and lots more,
        As a Web Developer, I specialize in  the management and Designing of very beautiful responsive websites.
         As a Health Blogger, I writes Health related articles that seeks to promote and protect the health of individuals and groups
        , click here for more <a href="www.healthandfitnesssite.com"></a> .
        As a Public Health Educator, I am a Lecturer at the Department Of Human Kinetics and Health Education. Nnamdi Azikiwe University, Awka 
         I help to foster learning of ways and methods which improves healthy living.
  
        I am also creating impact in  my world through the establishment of a website that helps to educate the public on relevant
        health matters.  
    
        </p>
        <h4 class="h4">For more my services or more information contact me  through</h4>
            s
  <ul class="links">
    <li><a class=""href="#Phone number">+2347035120768</a></li>
            <li><a class=""href="vu.okpala@unizik.edu.ng">Email</a></li>
              <li><a class=""href="#facebook">Facebook</a></li>
                <li><a class=""href="#linkedin">LinkedIn</a></li>
                  <li><a class=""href="#instagrame">Instagrame</a></li>
                    <li><a class=""href="#whatsapp">Whatsapp</a></li>
            
            </ul><!---container------>
  <img class="img-fluid rounded-circle" src="C:\Users\USER\Desktop\my portfolio\images\DSC_3915.JPG">
  
  
  
  </div>
  
  </div>
  
  
  
    <div id="Experiences" class="tabcontent">
    
  
  <div class="container">
    <div class="container" style="height: 120px;">
    </div>   
    
      <!-- ***********************  WORK EXPERIENCE  *********************** -->
      <header class="jumbotron">
        <div class="content-wrap divider">
          <h2>Work Experiences</h2>
          <p>See my complete work history on <a href="https://www.linkedin.com/in/vivian-uchechi-975522167/">LinkedIn</a>.</p>
        </header>

          <!-- Job 1 -->
          <header class="jumbotron">

              <h3>Front-end Developer & the CEO of SUV Couture</h3>
              <p>Freelance</p>
              <p>January 2022-Present</p>
              <p> Designed and creates <a href="https://www.suvmediablog.com"> SUV media Website </a>.Provides various front-end related services ranging from development work, speaking engagements, instructor training, workshops, and curriculum development. See more at  <a href="http://christinatruong.com">christinatruong.com</a>.</p>
            </div>
          </header>

          <!-- Job 2 -->
          <header class="jumbotron">
              <h3>Lecturer </h3>
              <p>Department of Human Kinetics and Health Education
                 <p>NNamdi Azikiwe University, NAU Awka</p>
              <p>January 2020 - Present</p>
            <div class="job-summary">
              <p>Serverd as the Academic Board Secretary for 2020/2021 academic  session, served as the academic adversisers of 2018/2019 session.<p/></p>
              <p>Supervised students Degree Projects</p>
              <p> Have taught the foloowing coures to the undergarduates of  my Department</p>
              <p> Attended several conferences in relation to Public health and have Published several Papers in repitable journals, check out my google schoolar account 
                <a href="#"</a> 
              </p>
              
              <ul>
                <li>Health care Delivery System in Nigeria.</li>
                    <li>Occupational Health and Safety Management in Nigeari</li>
                    <li>Maternal and Child Health Education</li>
                    <li>School Health Education Programme</li>
                    <li>Consumer Health Education</li>
                  </ul>
                </li>
            </div></header>
             

          <!-- Job 3 -->
          <header class="jumbotron">
            <div class="job-details""display-2 mb-4">
              <h3>Fashion Designing</h3>
              <p>Founder SUV Couture</p>
              <p>January, 2018 - Present</p>
            </div>
            <div class="job-details""display-2 mb-4">
              <p> Founded the SUV Coutour Fashion Brand in Nigeria.</p>
              <p>Key contributions:</p>
              <ul>
                <li>Responsible for the Desining of the projects and training of our prospective students .</li>
                <li>Ensures on the quality production from my team .</li>
                <li>Responsible in the manangement of the affairs of the business.</li>
              </ul>
            </div>
          </header>
        </div>
      </header>

</div>


      
    </div>
</div>
</div>
<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}
// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>


<!--------*******Footer*******-------->
<div class="footer fixed">
    <nav class="navbar navbar-dark bg-danger navbar-expand-sm">
      <div class="container">
        <div class="navbar-brand"> <h4>For more information contact us through</h4></div>
      <ul class="navbar-nav">
      <li class="nav-item"><a class="nav-link"href="#email">Email</a>
        <li class="nav-item"><a class="nav-link"href="#facebook">Facebook</a>
          <li class="nav-item"><a class="nav-link"href="#linkedin">LinkedIn</a>
            <li class="nav-item"><a class="nav-link"href="#instagrame">Instagrame</a>
              <li class="nav-item"><a class="nav-link"href="#whatsapp">Whatsapp</a>
      
      </ul><!---container------>
     

      </div>
    </nav>
    </div>
   




<!-- Optional JavaScript -->
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
</body>
</html>
