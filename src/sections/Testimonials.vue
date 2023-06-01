<template>
  <section class="center">
    <div class="home">
      <div class="home-left"></div>
      <div class="home-right">
        <h4 class="color-primary mb-4">Testimonials</h4>
        <h1 class="mb-4">Client's Feedback</h1>
        <h4 class="mb-4 color-secondary">
          It is a long established fact that a reader will be distracted by the readable content of
          a page when looking at its layout. The point of using Lorem Ipsum is that it has a
          more-or-less normal distribution of letters
        </h4>
        <Button label="See more reviews" />
      </div>
    </div>
  </section>
</template>

<script>
import Button from '../components/Buttons/PrimaryButton.vue'
export default {
  components: {
    Button
  }
}
</script>
