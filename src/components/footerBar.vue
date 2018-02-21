<template>
  <footer class="footer">
    Copyright © Emily Malec Brown {{ thisYear }} | Based on
    <a
      href="https://github.com/viko16/vue-ghpages-blog"
      rel="noopener">vue-ghpages-blog</a>
  </footer>
</template>

<script>
  export default {
    data () {
      return {
        thisYear: new Date().getFullYear()
      }
    }
  }
</script>
