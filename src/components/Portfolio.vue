<template>
  <div class="container">
    <div>
      <b-nav align="right">
        <b-nav-item href="#portfolio-project">Portfolio</b-nav-item>
        <b-nav-item href="#2">My Stack</b-nav-item>
        <b-nav-item href="contact">Contact</b-nav-item>
      </b-nav>
      <div>
        <b-jumbotron>
          <div>
            <img src="../assets/ay.jpg" height="500px" width="500px" />
          </div>
          <h1>
            Hi, I'm Ayodele Salimonu a <textra
              :data="words"
              :timer="1.5"
              :infinite="true"
              filter="left-right"
            />
            
          </h1>
          <h2>
            I'm a guy with some coding skills. who love to architect, code
            solutions and solving coding challenges. Started my career as a
            freelancer during college. Currently working as a software engineer
            at Groupe Rhinos, Dubai. Most of the free times playing video games
            or solving something on HackerRank®
          </h2>
          <div class="space">
            <b-button variant="primary disabled" href="#">Hire Me</b-button>
            <b-button variant="success" href="#">Download CV</b-button>
          </div>
        </b-jumbotron>
      </div>
    </div>
    <hr />
    <h2>My Projects</h2>
   <Project />
    <!-- <b-navbar toggleable type="dark" variant="dark">
    <b-navbar-brand href="#">NavBar</b-navbar-brand>

    <b-navbar-toggle target="navbar-toggle-collapse">
      <template v-slot:default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">Link 1</b-nav-item>
        <b-nav-item href="#">Link 2</b-nav-item>
        <b-nav-item href="#" disabled>Disabled</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar> -->
    <h2>Contact Us</h2> 
      <ContactForm />
    
  </div>
</template>

<script>
// eslint-disable-next-line no-unused-vars
import ContactForm from "./ContactForm.vue";
import Project from "./Project.vue";

export default {
  components: {
    // eslint-disable-next-line vue/no-unused-components

    ContactForm,
    Project,
  },
  data() {
    return {
      words: ["Web Developer", "Mobile Developer", "Blogger", "Gamer"],
    };
  },
};
</script>

<style scoped>
.btn {
  margin: 0 5px;
}
#portfolio-project {
  
  box-shadow: 10px;
}
/* .container{
   grid-gap: 20px;
    display: grid;
    border: 5px solid #2c3e50;
    grid-template-rows: 100px 100px 100px;
    grid-template-columns: 1fr 1fr 1fr;
  
}
.head{
    text-align: center;
    color: white;
    font-size: 30px;
    background-color: aqua;
    grid-gap: 10px;
} */
</style>
