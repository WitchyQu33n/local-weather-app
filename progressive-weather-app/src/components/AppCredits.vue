<template>
  <footer>
    <small>© <b><a href="https://twitter.com/asgardian" target="_blank" rel="noopener">I.T mela 2022 by:ayush.a.m-abhirami.s</a></b> {{ year }} - A <cite>freeCodeCamp</cite> Project</small>
  </footer>
</template>

<script>
export default {
  name: 'AppCredits',

  props: {
    year: {
      type: Number,
      required: true
    }
  }
}
</script>

<style scoped>
footer {
  text-align: center;
  position: absolute;
  bottom: 10px;
  visibility: hidden;
}

@media screen and (min-width: 450px) {
  footer {
    visibility: visible;
  }
}
</style>
