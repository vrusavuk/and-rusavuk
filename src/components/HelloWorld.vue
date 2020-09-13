<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
     <a href="mailto:contact@wemake.services">Связатсья со мной по email</a>
    </p>
    <p>
     <a href="tel:+79819151655">+7 (981) 915-16-55</a>
    </p>
    <div class="andrey-rusavuk-navigation">
      <nav class="navigation-bar">
        <a href="https://bible.and-rusavuk.ru">проповеди</a> | <a href="https://medium.com/@vrusavuk">статьи</a>
      </nav>
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
<style scoped lang="scss">
h1 {
  margin-bottom: 40px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  text-decoration: none;
  color: black;
  
}
a:link {
    text-decoration: none;
}

a:visited {
    text-decoration: none;
}

a:hover {
    background-color: rgb(223, 223, 223);
}

a:active {
    text-decoration: underline;
}

.andrey-rusavuk-navigation {
    max-width: 250px;
    margin: 0 auto;
    text-align: center;
    position: absolute;
    bottom: 50px;
    right: 0;
    left: 0;
}
</style>
