<html lang="en">

  <head>
      <meta charset="UTF-8" />
      <meta name ="viewport" content="width = device-width, initial-scale = 1" >
      <title>Kabir's Resume</title>
      <link type="text/css" rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Google+Sans" />
      <link href="https://fonts.googleapis.com/css?family=Poppins:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i"
          rel="stylesheet" />
      <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.9/css/all.css" integrity="sha384-5SOiIsAziJl6AWe0HWRKTXlfcSHKmYV4RBF18PPJ173Kzn7jzMyFuTtk8JA7QQG1"
          crossorigin="anonymous" />
          <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
      <link rel="shortcut icon" href="./favicon.ico">
  </head>

  <style type="text/css">
      body {
    background: linear-gradient(to bottom right, #50a3a2 0%, #2eca7f 100%);
    padding: 0;
    margin: 0;
    border: none;
    font-family: 'Poppins';
    font-size: 14px;
    color: #626262;
    letter-spacing: 0em;
    font-weight: 400;
    -webkit-font-smoothing: antialiased;
}

a {
    text-decoration: none;
    color: #171717;
}



.background.gradient {
    background: #50a3a2;
    background: linear-gradient(to bottom right, #50a3a2 0%, #2eca7f 100%);
    position: fixed;
    overflow: hidden;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

input, textarea, button {
    margin: 0;
    padding: 0;
    display: block;
    font-family: 'Poppins';
    font-size: 13px;
    width: 100%;
    height: 60px;
    color: #171717;
    background: none;
    border: none;
    border-bottom: 1px solid #d8dbe2;
    appearance: none;
    resize: none;
    outline: 0;
    transition: all 0.3s ease 0s;
    border-radius: 0px;
}

input:focus, textarea:focus, button:focus {
    color: #171717;
    border-bottom: 1px solid #2eca7f;
}

.title{
    text-align: left;
    margin: 0 0 15px 20px;
    padding: 0 0 5px 0;
    position: relative;
    font-size: 17px;
    color: #171717;
    line-height: 21px;
    font-weight: 500;
}

/* Círculo verde encima del título */
.title::before{
    content: '';
    position: absolute;
    left: -12px;
    top: 0;
    width: 30px;
    height: 30px;
    background: linear-gradient(135deg, rgba(46, 202, 127, 0.4) 0%, rgba(46, 202, 127, 0.01) 100%);
    z-index: -1;
    border-radius: 30px;
}
/* Línea gris debajo del título */
.title::after{
    content: '';
    position: absolute;
    left: -40px;
    bottom: -15px;
    width: 95%;
    height: 1px;
    background: radial-gradient(ellipse at left, rgba(197, 202, 213, 0.7) 0%, rgba(255, 255, 255, 0) 70%);
}

.line-left{
    position: relative;
}
.line-left::before{
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    width: 1px;
    height: 100%;
    background: radial-gradient(ellipse at top, rgba(197, 202, 213, 0.7) 0%, rgba(255, 255, 255, 0) 70%);
}

.line-down{
    position: relative;
}

.line-down::after{
    content: '';
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    height: 1px;
    background: radial-gradient(ellipse at left, rgba(197, 202, 213, 0.7) 0%, rgba(255, 255, 255, 0) 70%);
}

header{
    background-color: white;
    border-radius: 0 0 5px 5px;
    width: 100%;
    max-width: 540px;
    box-shadow: 0 0 25px rgba(0, 0, 0, 0.05);
    position: fixed;
    top: 0;
    z-index: 100;
}

header nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
}

header nav a {
    width: 100%;
    height: 72px;
    text-align: center;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: center;
    transition: color 0.3s ease 0s;
    font-size: 20px;
}

header nav a::before{
    content: '';
    position: absolute;
    left: 0;
    bottom: 0;
    width: 1px;
    height: 100%;
    background: radial-gradient(ellipse at top, rgba(197, 202, 213, 0.7) 0%, rgba(255, 255, 255, 0) 70%);
}

header nav a .link{
    font-size: 11px;
    font-weight: 500;
    text-transform: uppercase;
    margin-top: 4px;

}

header nav a:hover {
    color: #2eca7f;
}

main{
    margin-top: 88px;
}

main .profile, main .about, main .resume, main .works, main .blog{
    box-sizing: border-box;
    position: relative;
    background: #ffffff;
    text-align: center;
    z-index: 10;
    border-radius: 4px;
    max-width: 540px;
    margin: 0 auto;
}

main .about, main .resume, main .works, main .blog{
    padding: 30px 20px 30px 20px;
    margin-top: 15px;
}

main .profile{
    margin-top: 18px;
    overflow: hidden;
}

.profile-background{
    height: 300px;
}

.profile-image{
    position: relative;
    height: 84px;
}
.profile-image img{
    position: relative;
    top: -82px;
    border-radius: 50%;
    border: 3px solid white;
    width: 134px;
}

.profile-image::before{
    content: '';
    position: absolute;
    top: -69px;
    left: calc(50% - 78px);
    width: 134px;
    height: 134px;
    background: linear-gradient(135deg, rgba(46, 202, 127, 0.4) 0%, rgba(46, 202, 127, 0.01) 100%);
    border-radius: 100%;
}

.profile-name{
    font-size: 32px;
    color: #171717;
    line-height: 32px;
    font-weight: 400;
    margin: 0 auto 0 auto;
}

.profile-profession{
    font-size: 14px;
    color: #2eca7f;
    line-height: 14px;
    font-weight: 400;
}

.profile-social a{
    transition: color 0.3s ease 0s;
    margin: 0 6px;
    font-size: 16px;
}

.profile-social a:hover{
    text-decoration: none;
    color: #2eca7f;
}

.profile-buttons{
    position: relative;
    display: flex;
    margin-top: 58px;
}
.profile-buttons::before{
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 1px;
    background: radial-gradient(ellipse at left, rgba(197, 202, 213, 0.7) 0%, rgba(255, 255, 255, 0) 70%);
}

.profile-buttons a{
    position: relative;
    width: 50%;
    height: 70px;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: color 0.3s ease;
    line-height: 70px;
    font-size: 12px;
    font-weight: 500;
    color: #171717;
}



.profile-buttons a:hover{
    color: #2eca7f;
}

.profile-buttons a:first-child::before, .profile-buttons a:first-child::after{
        content: '';
        position: absolute;
        right: 0;
        top: 0;
        width: 1px;
        height: 100%;
        background: radial-gradient(ellipse at top, rgba(197, 202, 213, 0.7) 0%, rgba(255, 255, 255, 0) 70%);
}

.profile-buttons a i{
    margin-left: 10px;
    font-size: 15px;
}

.about-aboutMe > div{
    padding: 5px 17px;
    position: relative;

}

.about-aboutMe > div > div{
    display: flex;
    flex-wrap: wrap;
}

.about-aboutMe > div > div > div{
    width: 50%;
    text-align: left;
}

.about-aboutMe > div > div > div span{
    font-weight: 500;
    font-size: 13px;
}


.about-aboutMe p{
    text-align: left;
}

.about-services{
    margin-top: 50px;
}

.about-services >div{
   display: flex;
   flex-wrap: wrap;
   position: relative;
}
.about-services >div:after{
    content: '';
    position: absolute;
    left: 50%;
    top: 0;
    width: 1px;
    height: 100%;
    background: radial-gradient(ellipse at top, rgba(197, 202, 213, 0.7) 0%, rgba(255, 255, 255, 0) 70%);
}

.about-services article{
    position: relative;
    width: 50%;
    text-align: left;
    padding: 15px 20px;
    box-sizing: border-box;
}

.about-services article .fas{
    margin: 0;
    width: 60px;
    height: 60px;
    text-align: center;
    font-size: 32px;
    color: #2eca7f;
    background: linear-gradient(135deg, rgba(46, 202, 127, 0.4) 0%, rgba(46, 202, 127, 0.01) 100%);
    border-radius: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.about-services article h4{
    font-size: 13px;
    color: #171717;
    font-weight: 500;
    text-transform: uppercase;
}

.about-services article p{
    font-size: 14px;
    line-height: 1.6;
    padding: 0;
}

.resume-lines{
    display: flex;
}

.resume-line h4{
    margin: 0;
    text-align: left;
    padding: 20px 18px;
    font-size: 13px;
    line-height: 13px;
    color: #171717;
    font-weight: 500;
    text-transform: uppercase;
}

.resume-line h4 .fas{
    position: relative;
    float: left;
    top:-7px;
    width: 40px;
    height: 40px;
    font-size: 26px;
    color: #2eca7f;
}

.resume-line{
    flex: 1;
    text-align: left;
}

.resume-line article{
    padding: 15px 15px;
}

.resume-line .date{
    margin: 0 0 10px 0;
    padding: 0;
    position: relative;
    display: inline-block;
    font-size: 11px;
    line-height: 18px;
    color: #d8dbe2;
    font-weight: 500;
    text-transform: uppercase;
    border-radius: 4px;
}


.resume-line .date::before{    
    content: '';
    position: absolute;
    left: -19px;
    top: 4px;
    width: 9px;
    height: 9px;
    background: #d8dbe2;
    border-radius: 9px;
    -moz-border-radius: 9px;
    -webkit-border-radius: 9px;
    -khtml-border-radius: 9px;
}

.resume-line .date.active{
    color: #2eca7f;
}

.resume-line .date.active::before{
    background: #2eca7f;
}

.resume-line .name{
    margin: 0;
    font-size: 13px;
    color: #171717;
    font-weight: 500;
    text-transform: uppercase;
}

.resume-line .company{
    margin: 0 0 10px 0;
    font-size: 11px;
    color: #999999;
    font-weight: 300;
    text-transform: uppercase;
}

.resume-skills{
    margin-top: 50px;
}
.resume-skills > div{
    display: flex;
}
.resume-skills > div section{
    flex: 1;
    text-align: left;
}

.resume-skills > div section > div{
    padding: 18px 20px;
}

.resume-skills > div section > div > div:first-child{
    margin: 0 0 8px 0;
    font-size: 14px;
    line-height: 14px;
    color: #626262;
    text-align: left;
}

.resume-skills > div section > div > div:last-child{
    width: 100%;
    background: #d8dbe2;
    height: 4px;
}

.resume-skills > div section > div > div > div{
    background: #2eca7f;
    height: 4px;
}

.resume-skills h4{
    margin: 0;
    text-align: left;
    padding: 20px 18px;
    font-size: 13px;
    line-height: 13px;
    color: #171717;
    font-weight: 500;
    text-transform: uppercase;
}

.resume-skills h4 .fas{
    position: relative;
    float: left;
    top:-7px;
    width: 40px;
    height: 40px;
    font-size: 26px;
    color: #2eca7f;
}


main .contact{
    margin-bottom: 40px;
}

.contact-information{
    display: flex;
    flex-wrap: wrap;
    padding: 11px 18px;
}

.contact-information > div{
    width: 50%;
    text-align: left;
}

.contact-information > div span{
    font-weight: 500;
    font-size: 13px;
}


@media only screen and (min-width: 540px){
    header{
        left: calc(50% - 270px);
    }
}

@media only screen and (min-width: 1040px) {
    .selected{
        color: #2eca7f;
    }
    .page{
        position: absolute;
        top:0;
        bottom: 0;
        left: 0;
        right: 0;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    header{
        max-width: 80px;
        position: relative;
        border-radius: 5px;
        left: -6px;
    }
    header nav{
        display: flex;
        flex-direction: column;
    }
    header nav a::before {
        content: '';
        position: absolute;
        left: 0;
        bottom: 0;
        width: 100%;
        height: 1px;
        background: radial-gradient(ellipse at left, rgba(197, 202, 213, 0.7) 0%, rgba(255, 255, 255, 0) 70%);
    }

    main{
        display: flex;
        margin: 0;
        width: 1020px;
    }

    main .about, main .resume, main .contact {
        width: 0;
        height: 0;
        opacity: 0;
        overflow: hidden;
        position: relative;
        top: 16px;
        transform: translateX(-450px);
        transition: opacity 1s ease, transform 1s ease;
        z-index: 0;
        margin: 0;
        padding: 0;
    }

    main .profile{
        width: 480px;
        height: 600px;
        box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.05);
        margin: 0;
    }
  
    main .view{
        height: 574px;
        width: 540px;
        padding: 30px 20px 30px 20px;
        overflow: auto;
        opacity: 1;
        transform: translateX(-8px);
    }

    main .view::-webkit-scrollbar {
        width: 5px;
    }
       
    main .view::-webkit-scrollbar-track {
        background: #ddd;
    }
       
    main .view::-webkit-scrollbar-thumb {
        background: #666; 
    }

    main .contact {
        margin-bottom: 0;
    }
}
  </style>
<body> 
    <div class="background gradient">
    </div>
    <div class="page">
        <header>
            <nav>
                <a href="#about" class="selected" id='getAbout'>
                    <span class="fas fa-user"></span>
                    <span class="link">About</span>
                </a>
                <a href="#resume" id='getResume'>
                    <span class="fas fa-file"></span>
                    <span class="link">Resume</span>
                </a>
            </nav>
        </header>
        <main>
            <section id="presentation" class="profile">
                <div class="profile-background"></div>
                <div>
                    <div class="profile-image">
                        <img src="https://I.ibb.co/423t4F5/IMG-20231210-001145.jpg" alt="Kabir Bhardwaj">
                    </div>
                    <h1 class="profile-name" id="nombre">Kabir Bhardwaj</h1>
                    <h2 class="profile-profession">Web Designer</h2>
                    <div class="profile-social" id="profile-social">
                        <a href="https://instagram.com/akakabira" class="fab fa-instagram"></a>
                        <a href="https://facebook.com/akakabira" class="fab fa-facebook"></a>
                        <a href="https://wa.me/+919835362714" class="fab fa-whatsapp"></a>
                        <a href="https://open.spotify.com/user/31yngk2cj7lle4wpp6qzyuzgg2ky" class="fab fa-spotify"></a>
                    </div>
                </div>
                <div class="profile-buttons">
                    <a href="Resume.html" download>DOWNLOAD CV <i class="fas fa-download"></i></a>
                    <a href="mailto:kabirbhardwaj6020@gmail.com">CONTACT ME <i class="fas fa-arrow-right"></i></a>
                </div>
            </section>
            <section id="about" class="about view">
                <article class="about-aboutMe">
                    <h3 class="title">About Me</h3>
                    <div class="line-left">
                        <p>I am Kabir Bhardwaj, web designer from Bhagalpur, Bihar. I am a tech enthusiast, currently learning about web designing during the internship by Khabai Tech Patna in which I have learnt basic HTML, CSS and BOOTSTRAP scripts. I also have intrests in development and use of AOSP and Linux related to smartphones. I am also somewhat experienced in photo editing and basic video editing.</p>
                        <div>
                            <div>
                                <span>AGE - </span>17
                            </div>
                            <br>
                            <div>
                                <span>SEX - </span>Male
                            </div>
                            <br>
                            <div>
                                <span>MOBILE - </span>+91 98353 62714
                            </div>
                            <br>
                            <div>
                                <span>EDUCATION - </span>Diploma in CSE
                            </div>
                            <br>
                            <div>
                                <span>RESIDENCE - </span>Bihar, India
                            </div>
                            <br>
                            <div>
                                <span>ADDRESS - </span>Bhikhanpur, Bhagalpur
                            </div>
                        </div>
                    </div>
                </article>
                <article class="about-services">
                    <h3 class="title">My Hobbies</h3>
                    <div class="line-left">
                        <article class="line-down">
                            <div class="fas fa-code"></div>
                            <h4>WEB DEVELOPMENT</h4>
                            <p>Still in my learning phase but still able to create an attractive and functional webpages.</p>
                        </article>
                        <article class="line-down">
                            <div class="fas fa-music"></div>
                            <h4>MUSICAL INSTRUMENTS</h4>
                            <p>I learnt a basic of intruments such as Piano, Guitar, Flute, MouthOrgan and Tabla at a ripe age.</p>
                        </article>
                        <article>
                            <div class="fas fa-file"></div>
                            <h4>AOSP</h4>
                            <p>I also have some experience and intrest in development and modification of AOSP (Android Open Source Project) and can do basic OS flashing, booting and rooting.</p>
                        </article>
                        <article>
                            <div class="fas fa-gamepad"></div>
                            <h4>GAMES</h4>
                            <p>Hobby of basically 90% of teens, I'm no different. I play strategic games such as chess, cards etc. Video Games are also in the deepeset of intrests of mine.</p>
                        </article>
                    </div>
                </article>
            </section>
            <section id="resume" class="resume">
                <h3 class="title">Resume</h3>
                <article class="resume-lines">
                    <section class="resume-line line-left">
                        <h4 class="line-down"> <i class="fas fa-university"></i> Education</h4>
                        <article class="line-down">
                            <div class="date">2010 - 2014</div>
                            <h5 class="name">Primary Education</h5>
                            <h6 class="company">Kidzee Play School, Lakhisarai</h6>
                        </article>
                        <article class="line-down">
                            <div class="date">2014 - 2022</div>
                            <h5 class="name">Secondary and Higher Education</h5>
                            <h6 class="company">Sky Vision Public School, Lakhisarai</h6>
                        </article>
                        <article class="line-down">
                            <div class="date">2022 - 2025</div>
                            <h5 class="name">College for Diploma</h5>
                            <h6 class="company">Government Polytechnic Patna 07</h6>
                        </article>
                        <article>
                            <div class="date">11/2023 to 12/2023</div>
                            <h5 class="name">Internship for Web Development</h5>
                            <h6 class="company">Khabai Tech Patna, Hajipur</h6>
                        </article>
                    </section>
                </article>
                <article class="resume-skills">
                    <h3 class="title">My Skills</h3>
                    <div>
                        <section class="line-left">
                            <h4 class="line-down"> <i class="fas fa-tv"></i> DESIGN</h4>
                            <div class="line-down">
                                <div>Web Design</div>
                                <div>
                                    <div style="width: 70%"></div>
                                </div>
                            </div>
                            <div class="line-down">
                                <div>Photo Editing</div>
                                <div>
                                    <div style="width: 90%"></div>
                                </div>
                            </div>
                            <div>
                                <div>Graphic Design</div>
                                <div>
                                    <div style="width: 30%"></div>
                                </div>
                            </div>
                        </section>
                        <section class="line-left">
                            <h4 class="line-down"><i class="fas fa-code"></i> CODING</h4>
                            <div class="line-down">
                                <div>HTML/CSS</div>
                                <div>
                                    <div style="width: 75%"></div>
                                </div>
                            </div>
                            <div class="line-down">
                                <div>JavaScript</div>
                                <div>
                                    <div style="width: 35%"></div>
                                </div>
                            </div>
                            <div>
                                <div>AOSP</div>
                                <div>
                                    <div style="width: 40%"></div>
                                </div>
                            </div>
                        </section>
                    </div>
                </article>
            </section>
        </main>
    </div>
</body>
<script type="text/javascript">
let getAbout = document.getElementById("getAbout");
let getResume = document.getElementById("getResume");let about = document.getElementById("about");
let resume = document.getElementById("resume");
function removeClass() {
    getAbout.classList.remove('selected');
    getResume.classList.remove('selected');
    about.classList.remove('view');
    resume.classList.remove('view');
}
getAbout.addEventListener('click', function (e) {
    if (window.innerWidth > 1040) {
        e.preventDefault();
        removeClass();
        about.classList.add('view');
        getAbout.classList.add('selected');
    }
});
getResume.addEventListener('click', function (e) {
    if (window.innerWidth > 1040) {
        e.preventDefault();
        removeClass();
        resume.classList.add('view');
        getResume.classList.add('selected');
    }
})
</script>
</html>
