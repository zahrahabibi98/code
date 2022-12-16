# code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>zahra habibi</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="/assets/css/all.min.css" />
  </head>
  <title>Zahra Habibi</title>
  <link rel="shortcut icon" href="favicon.ico" type="image/x.icon" />

  <body>
    <!-- HEADER -->

    <header class="header">
      <img src="/assets/2.jpg" alt="habibi" />
      <div class="title">
        <h1>Zahra Habibi</h1>
        <h2 class="position">
          <i class="fa-solid fa-angle-right"></i>
          Front-end developer
        </h2>
        <a
          href="https://github.com/zahrahabibi98"
          target="_blank"
          class="button"
        >
          <i class="fa-brands fa-github"></i>
          My github profile
        </a>
      </div>

      <a href="./fa.html" class="lang">
        <i class="fa-solid fa-globe"></i>
        Farsi
      </a>
    </header>
    <div class="container">
      <!-- NAV BAR-->
      <nav>
        <ul>
          <li class="active">
            <span class="marker"><i class="fa-solid fa-angle-right"></i></span>
            About me
          </li>
          <li class="active">
            <span class="marker"> <i class="fa-solid fa-angle-right"></i></span>
            My skills
          </li>
          <li class="active">
            <span class="marker"> <i class="fa-solid fa-angle-right"></i></span>
            My projects
          </li>
        </ul>
      </nav>
      <div class="sections">
        <!--SECTION-->
        <section>
        
          <h5>About me</h5>
          <p>
            Hi every one.<br/>My name is zahra and I'm so
            eager to learn web desining.you can check
            my work sample on my github account.
          </p>

          <div class="contact">
            <div>
          <h5>Email</h5>
          <p>hbi.zahra@yahoo.com <i class="fa-regular fa-clone"></i></p>
        </div>
       <div>
          <h5>Phone Number</h5>
          <p>09017113950 <i class="fa-regular fa-clone"></i></p>
        </div>
      </div>

          <div>
          <ul class="socials">
            <h5>Social Media</h5>
            <li>
              <a href="#" target="_blank">
                <span class="linkedin"></span>
              </a>
            </li>
            <br />
            <li>
              <a href="#" target="_blank">
                <span class="instagram"></span>
              </a>
            </li>
            <br />
            <li>
              <a href="#" target="_blank">
                <span class="stackoverflow"></span>
              </a>
            </li>
            <br />
            <li>
              <a href="#" target="_blank">
                <span class="github"></span>
              </a>
            </li>
            <br />
            <li>
              <a href="#" target="_blank">
                <span class="whatsapp"></span>
              </a>
            </li>
            <br />
            <li>
              <a href="#" target="_blank">
                <span class="telegram"></span>
              </a>
            </li>
            <br />

          </ul>
        </section>
        
        <!--SKILLS-->
        <section>
          <h4>My Skills</h4>
          <h4><b>Technology</b></h4>
          <ul>
            <li><img src="  /assets/icons/social/html.png" /> HTML Advanced</li>
            <li><img src="/assets/icons/social/css.png" />CSS3 Advanced</li>
            <li>
              <img src="/assets/icons/social/js.png" />JavaScript Advanced
            </li>
            <li><img src="/assets/icons/social/react.png" />React Advanced</li>
          </ul>
          <h4><b>Tools</b></h4>
          <ul>
            <li><img src="/assets/icons/social/git.png" /> Git Intermediate</li>
            <li>
              <img src="/assets/icons/social/vscode.png" /> VScode Advanced
            </li>
          </ul>
          <h4><b>Other Skills</b></h4>
          <ul>
            <li>Redux</li>
            <li>Saas</li>
            <li>Scrum</li>
            <li>Less</li>
            <li>Agile Methodology</li>
            <li>Responsive Web Design</li>
          </ul>
        </section>
        <section>
          <h4><b>My Project</b></h4>
          <div>
            <img src="/assets/icons/social/placeholder.png" />
            <h6>Project title</h6>
            <p>this is my first project</p>
          </div>
          <h4>Tech Used:</h4>
          <ul>
            <li><img src="/assets/icons/social/html.png" /></li>
            <li><img src="/assets/icons/social/css.png" /></li>
          </ul>
          <a href="#">demo</a>
          <a href="#"><img src="/assets/icons/social/github.png" />view code</a>
        </section>
      </div>
    </div>
  </body>
</html>



css


/*GLOBALLY*/
* {
  font-family: "Poppins", sans-serif;
  box-sizing: border-box;
}

body {
  background-color: #fafafa;
  color: #333533;
  font-size: 18px;
  margin: 0;
}

a {
  text-decoration: none;
}

h2 {
  font-weight: 400;
}

h5 {
  margin-bottom: 5px;
  color: #a0a0a0;
  font-weight: 500;
  font-size: 18px;
}

ul {
  list-style: none;
  padding: 0;
}

/*CONAINERS*/

.header,
.container {
  display: flex;
  padding: 45px 0;
  justify-content: center;
}

/*HEADER*/

.header {
  background-color: #333533;
  height: 376px;
  align-items: center;
}

.header .title {
  margin: 0 50px;
}

.header .title h1 {
  color: #ffd100;
  font-size: 56px;
  margin: 0;
  line-height: 1;
}

.header .position {
  color: #fafafa;
  font-size: 32px;
  margin: 40px 0;
}

.header .position i {
  color: #ffd100;
}

.button {
  color: #ffd100;
  border: 1px solid #ffd100;
  border-radius: 4px;
  padding: 8px 24px;
}

.button:hover {
  background-color: #ffd100;
  color: grey;
}

.button i {
  margin-right: 6px;
}

.lang {
  color: white;
  border: 1px solid white;
  border-radius: 4px;
  padding: 4px 8px;
  font-size: 12px;
  opacity: 0.7;
  align-self: flex-start;
}

.lang:hover {
  opacity: 1;
}

.lang i {
  margin-right: 4px;
}

.header img {
  width: 290px;
  height: 290px;
  border-radius: 50%;
}

.container {
  display: flex;
  justify-content: center;
  padding: 45px 0;
}

/*NAVBAR*/

nav {
  width: 250px;
  font-size: 24px;
}

nav ul li {
  cursor: pointer;
  font-weight: 500;
}

nav ul li .marker {
  width: 42px;
  height: 42px;
  line-height: 42px;
  border: 1px solid #333533;
  border-radius: 50%;
  display: inline-block;
  text-align: center;
  vertical-align: middle;
  margin-right: 12px;
}

nav ul li.active .marker i {
  color: #ffd100;
  font-size: 22px;
}

nav ul li:hover .marker {
  background-color: #333533;
}

nav ul li:not(:last-child):after {
  content: "";
  display: block;
  height: 48px;
  border-left: 1px dashed #333533;
  margin: 16px 0px 16px 21px;
}

/*sections*/

.sections {
  width: 700px;
  border-left: 1px solid #333533;
  padding-left: 50px;
}

.contact {
  display: flex;
}

.contact div {
  width: 50%;
}

.contact p {
  margin: 0;
}

.contact p i {
  margin-left: 10px;
  font-size: 16px;
  color: #a0a0a0;
  cursor: pointer;
}

.contact p i:hover {
  color: #333533;
}

.social li {
  display: inline-block;
  margin-right: 24px;
}

.socials li span {
  display: inline-block;
  width: 56px;
  height: 56px;
}

.socials li span .linkedin {
  background-image: url("../icons/social/linkedin.png");
}

.socials li:hover span .linkedin {
  background-image: url("../icons/social/linkedin.png");
}

.socials li span .instagram {
  background-image: url("../icons/social/instagram.png");
}

.socials li:hover span .instagram {
  background-image: url("../icons/social/instagram.png");
}

.socials li span .stackoverflow {
  background-image: url("../icons/social/stackoverflow.png");
}

.socials li:hover span .stackoverflow {
  background-image: url("../icons/social/stackoverflow.png");
}

.socials li span .github {
  background-image: url("../icons/social/github.png");
}

.socials li:hover span .github {
  background-image: url("../icons/social/github.png");
}

.socials li span .whatsapp {
  background-image: url("../icons/social/whatsapp.png");
}

.socials li:hover span .whatsapp {
  background-image: url("../icons/social/whatsapp.png");
}

.socials li span .telegram {
  background-image: url("../icons/social/telegram.png");
}

.socials li:hover span .telegram {
  background-image: url("../icons/social/telegram.png");
}
