<template>
  <nav class="nav-bar">
      <div class="nav-pages">
          <h1 id="logo"><nuxt-link to="/">Shortly</nuxt-link></h1>
          <ul class="nav-menu">
              <li><nuxt-link to="/features" class="link">Features</nuxt-link></li>
              <li><nuxt-link to="/pricing" class="link">Pricing</nuxt-link></li>
              <li><nuxt-link to="/resources" class="link">Resources</nuxt-link></li>
          </ul>
      </div>
      <div class="nav-connection">
          <nuxt-link to="/login" class="link">Login</nuxt-link>
          <nuxt-link to="/signup" id="signUp">Sign Up</nuxt-link>
      </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style>
.nav-bar {
    display: flex;
    justify-content: space-between;
    margin-top: 30px;
    font-weight: bold;
    font-size: 15px;
    align-items: center;
}

.nav-bar a {
    text-decoration: none;
}

.link {
    color: hsl(0, 0%, 75%);
}

.link:hover {
    color: hsl(257, 27%, 26%);
}

#logo {
    display: inline-block;
    font-size: 2.1em;
}

#logo a{
    color: #333333;
}

.nav-pages {
    display: inline-block;
}

.nav-menu {
    display: inline;
}

.nav-menu li{
    list-style-type: none;
    display: inline-block;
    margin-right: 15px;
}

.nav-connection a{
    margin-right: 20px;
}

#signUp {
    background-color: hsl(180, 66%, 49%);
    color: white;
    padding: 5px 15px 6px 15px;
    border-radius: 15px;
    transition: background-color 0.2s;
}

#signUp:hover {
    background-color: hsl(180, 71%, 57%);
}

</style>