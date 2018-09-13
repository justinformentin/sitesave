<template>
  <footer class="footer">
    <div class="container">
      <div class="container">
        <div class="content has-text-centered">
          <p>Made by <a href="http://justinformentin.com" target="_blank">Justin Formentin</a>.
            All screenshots &copy; of their respective owners.
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
</script>

<style scoped>
footer.footer {
  background: #fff;
  padding-bottom: 2rem;
  color: hsl(0, 0%, 40%);
}

div.column.about {
  position: relative;
}

div.column.about div.logo {
  position: absolute;
  background-image: url('../assets/sitesave.png');
  background-position: 50% 50%;
  background-repeat: no-repeat;
  background-size: 150px;
  width: 150px;
  height: 30px;
}

div.column.about p.motto {
  position: absolute;
  top: 45px;
  left: 10px;
  color: #7957d5;
}

div.column.about div.copy {
  margin-top: 4.25rem;
}

/* Set text to align left on smaller devices */
@media screen and (max-width: 769px) {
  div.content.has-text-centered {
    text-align: left !important;
  }
}

div.column.foss *,
div.column.info * {
  margin-bottom: 5px;
}

div.column.foss span.highlight {
  color: hsl(0, 0%, 15%);
  font-weight: 700;
}

div.column.foss a.underline {
  text-decoration: underline;
}

div.column.info a.vue span.green { color: #42b883; }
div.column.info a.vue span.blue { color: #35495e; }
</style>
