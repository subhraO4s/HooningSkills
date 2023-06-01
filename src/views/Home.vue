<template>
  <Nav />
  <div class="container vh100">
    <Main />
    <About />
    <WhoAreWe />
    <Mission />
    <Testimonials />
    <BlogSection />
    <NewsLetter />
    <Footer />
  </div>
</template>

<script>
import Main from '../sections/Main.vue'
import About from '../sections/About.vue'
import WhoAreWe from '../sections/WhoAreWe.vue'
import Mission from '../sections/Misssion.vue'
import Testimonials from '../sections/Testimonials.vue'
import BlogSection from '../sections/BlogSection.vue'
import Footer from '../sections/Footer.vue'
import Nav from '../sections/Navigation.vue'
import NewsLetter from '../sections/NewsLetter.vue'
export default {
  components: {
    Nav,
    Main,
    About,
    WhoAreWe,
    Mission,
    Testimonials,
    BlogSection,
    NewsLetter,
    Footer
  }
}
</script>

<style scoped></style>
