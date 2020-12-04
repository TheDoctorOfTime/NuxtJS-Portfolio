<template>
  <div class="hello">
    
    <div class="navbar">
      <ul class="nav">
        <li class="nav-item"><a href="#"> About Me </a></li>
        <li class="nav-item"><a href="Projects"> Projects </a></li>
        <li class="nav-item"><a href="https://rafaelignacio.web.app"> Contact Me </a></li>
      </ul>
    </div>

    <div class="body-container">
      <!-- ================================================================================================ -->

      <div class="title">Hello! I'm <h1>Rafael Ignacio</h1></div>
      <div class="about-card">
        <h3 class="card-title">About Me</h3>
        <p class="card-text">
          My name is Rafael "Rafi" Ignacio. I love developing Desktop Apps, Games, and Websites. I know several languages such as: C, C#, C++, Java, JavaScript, Python, and GoLang, but I prefer using C# or C++ when developing applications or games. I enjoy doing back-end development and excel in front-end development. I have several 2D games that can be found in my itch.io page and I have participated in the several Game Jams such as the Ludum Dare Game Jam, The United Game Jam, The Triple TriJam and many more.
        </p>
        <a href="" class="card-contact">Contact Me</a>
      </div>
      scroll down for <a href="#Projects">Projects</a>
    </div>

    <!-- ================================================================================================ -->

    <div class="banner-head" id="Projects"><h1>PROJECTS</h1></div>

    <div class="project-container">
      <div class="thumbnail"><img src="../assets/logo.png" alt=""></div>
      <h1 class="project-title"><a href="https://thedoctoroftime.itch.io/kirby-has-a-gun">Kirby Has A Gun</a></h1>
      <p class="project-description">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet tenetur natus id esse voluptatum mollitia inventore dolores porro. Voluptatem corrupti similique minima at aperiam illum laborum doloribus quasi odio unde.
        Tempora alias iste assumenda reiciendis praesentium corporis quod consequuntur incidunt laudantium eligendi tempore quasi, soluta libero perferendis dolor facilis debitis magnam aliquid earum adipisci excepturi deleniti dignissimos ipsam ullam? Dicta.
      </p>
    </div>

    <div class="project-container">
      <div class="thumbnail"><img src="../assets/logo.png" alt=""></div>
      <h1 class="project-title"><a href="https://thedoctoroftime.itch.io/contrast">Contrast</a></h1>
      <p class="project-description">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet tenetur natus id esse voluptatum mollitia inventore dolores porro. Voluptatem corrupti similique minima at aperiam illum laborum doloribus quasi odio unde.
        Tempora alias iste assumenda reiciendis praesentium corporis quod consequuntur incidunt laudantium eligendi tempore quasi, soluta libero perferendis dolor facilis debitis magnam aliquid earum adipisci excepturi deleniti dignissimos ipsam ullam? Dicta.
      </p>
    </div>

    <div class="project-container">
      <div class="thumbnail"><img src="../assets/logo.png" alt=""></div>
      <h1 class="project-title"><a href="https://thedoctoroftime.itch.io/continuous">Continuous</a></h1>
      <p class="project-description">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Amet tenetur natus id esse voluptatum mollitia inventore dolores porro. Voluptatem corrupti similique minima at aperiam illum laborum doloribus quasi odio unde.
        Tempora alias iste assumenda reiciendis praesentium corporis quod consequuntur incidunt laudantium eligendi tempore quasi, soluta libero perferendis dolor facilis debitis magnam aliquid earum adipisci excepturi deleniti dignissimos ipsam ullam? Dicta.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="css">
/* // COLOR PALLETE */
h3, h1{
  color: #EA526F;
}
h3{
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
  font-size: 1.2em;
}
li a {
  color: #000000;
  text-decoration: none;
  margin: 0px 2em;
}
li a:hover { color: #25CED1; }
li a:active { color: #000000; }

.navbar{
  text-align: right;
  margin: 3em 5em;
  margin-top: 1.5em;
}


.body-container{
  margin: 3em 12em;
}
.body-container .title{
  margin-top: 3em;
  margin-bottom: 3em;
  font-weight: bold;
  font-size: 2em;
}
.body-container .title h1{
  margin-top: 0em;
  font-size: 3em;
}

.about-card{
  text-align: left;
  margin: 2em;
  padding: 2em 5em;
  padding-bottom: 4.5em;
  background-color: white;
  
  border-radius: 1.5em;
  box-shadow: 0px -2px 1.5em 0.05em rgba(71, 70, 70, 0.219);

}
.about-card .card-title{
  font-size: 2em;
}
.about-card p{
  font-size: 1.2em;
  line-height: 1.9em;
  margin-bottom: 4em
}
.about-card a{
  text-decoration: none;
  font-size: 1.1em;
  background-color: #FF8A5B;
  padding: 1em 2em;
  color: white;
  border-radius: 2em;
}
.about-card a:hover{
  background-color: #25CED1;
}
.about-card a:active{
  background-color: #FFFFFF;
  color: #FF8A5B;
}

.banner-head{
  margin: 0em;
  margin-top: 11.5em;
  background-color: #FF8A5B;
  width: 100vw;
  padding: 2em 0em;
}
.banner-head h1{
  color:white;
  font-size: 3em;
}

.project-container{
  margin: 0em 12em;
  margin-top: 10em;
  line-height: 2em;

}

.project-container .project-title{
  font-size: 3em;
}
.project-container .project-title a{
  text-decoration: none;
  color: #EA526F;
}
.project-container .project-description{
  margin-top: 3em;
  text-align: left;
  font-size: 1.2em;
}

a {
  color: #000000;
  text-decoration: none;
}
a:hover { color: #25CED1; }
a:active { color: #000000; }
</style>
