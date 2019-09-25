<template>
  <div class="home">
    <Jumbotron />
    <Hero />
    <div class="parallax1"></div>
    <About />
    <div class="parallax1"></div>
    <Manufacturing />
    <div class="parallax1"></div>
    <Referens />
    <div class="parallax1"></div>
    <Partners />
    <div class="parallax1"></div>
    <Work />
  </div>
</template>

<script>
import Jumbotron from '../components/Jumbotron'
import Hero from '../components/Hero'
import About from '../components/About'
import Manufacturing from '../components/Manufacturing'
import Referens from '../components/Referens'
import Partners from '../components/Partners'
import Work from '../components/Work'


export default {
  name: "home",
  components: {
    Jumbotron,
    Hero,
    About,
    Manufacturing,
    Referens,
    Partners,
    Work
  }
};
</script>

<style>
.parallax1 {
  
  background-image: url("../assets/images/parallax.jpg");
  filter: opacity(.5);

  /* Set a specific height */
  min-height: 500px; 

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
