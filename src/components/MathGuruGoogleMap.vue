<template>
  <div class="map-container">
   <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d8206.749652911732!2d78.54234534846933!3d17.328558353552904!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3bcba20f9a4c25b1%3A0xa22581b5ddc7f9b2!2sSri%20Santoshi%20Mata%20Temple!5e0!3m2!1sen!2sin!4v1759927001776!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </div>
</template>

<script>
export default {
  name: "MathGuruGoogleMap"
}
</script>

<style scoped>
.map-container {
  width: 100%;
  max-width: 800px;
  margin: auto;
  border-radius: 10px;
  overflow: hidden;
}
</style>
