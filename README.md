# Portfolio-Carlos
Ejemplo de Pagina Portfolio

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Style.css">
    <link rel="stylesheet" type="text/css" href="css/bootstrap.min.css"
</head>
<body>
    <div class="header-container"> 
         <header>
              <nav class="navbar">
                  <div class="nav-logo">
                       <h2>S<span>S</span></h2>
                  </div>
                  <ul class="menu">
                      <li><a href="#">Home</a></li>
                      <li><a href="#">About me</a></li>
                      <li><a href="#">Portfolio</a></li>
                      <li><a href="#">Contact</a></li>
                  </ul>
              </nav>
         </header>
         <main class="main">

            <div class="info-content">
               <h1>I'm <span>Sebastian</span>Suhurt</h1>
               <p>I am a sound technician and I am studying programming. I am constantly developing in the fields that I decided to study.</p>
               <a download href="#"><button class="download-cv">
                   Download CV
                  </button>
               </a>
            </div>
            <img src="Yo.jpeg">
    
        </main>
    </div> 
     

    <div class="about">
        <img src="About.jpeg">
    <div class="about-info">
      <h2>About me</h2>
        <div class="divider"></div>
          <p>In relation to music, my main instrument is the piano, but I also play the drums. At the same time I studied with different teachers about film scoring and production.</p>
          <p>As for programming, I am enrolled in the Faculty of La PLata in the 3-year program in programming. I am also taking various frontend and backen courses.</p>
          <button class="read-more"> Read More</button>
        </div>
    </div>

    <div class="portfolio">
        <div class="portfolio-headings">
            <h2>My portfolio</h2>
            <div class="divider"></div>
        
            <div class="container-portfolio">
            <div class="card">
                <div class="card-img">
                </div> 
            </div>
            <div class="container-card-title">
                <div class="card-title">
                    <h2>Projects</h2>
                </div>
                <div class="project-links">
                <a href="" target="_blank"><i class="fab fa-github-alt"></i></a>
                <a href=""><i class="fas fa-music"></i></a>
                </div>
            </div>

        </div>

    </div>

    <div class="contact-section">
        <div class="contact-heading">
            <h2>My Contact!</h2>
            <div class="divider"></div>
        </div>

        <div class="contact-form">
            <h4>Send me a message...</h4>
            <form class="form">
                <input type="text" placeholder="Name">
                <input type="email" placeholder="Email">
                <textarea placeholder="Place your message here">
                </textarea>
                <button type="submit" class="btn-submit"> Send Message</button>
            </form>
        </div>

    </div>

    <footer class="footer">
        <div class="footer-content">
            <h2>Sebastian Suhurt</h2>
            <h5>frontend</h5>
        </div>
        <div class="social-network">
            <i class="fab fa-twitter"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-linkedin"></i>
        </div>

    </footer>
</body>
<script src="https://kit.fontawesome.com/acbcd066ff.js" crossorigin="anonymous"></script>
</html>
