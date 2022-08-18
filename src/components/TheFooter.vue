<template>
  <footer>
    <div class="container">
      <router-link class="logo-font" :to="{ name: 'home', params: {} }">
        conduitdsadas
      </router-link>
      <span class="attribution">
        An interactive learning project from
        <a rel="noopener noreferrer" target="blank" href="https://thinkster.io"
          >Thinkster 2</a
        >. Code &amp; design licensed under MIT.
      </span>
    </div>
  </footer>
</template>

<script>
export default {
  name: "RwvFooter"
};
</script>
