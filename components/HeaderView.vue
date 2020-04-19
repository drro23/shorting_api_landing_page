<template>
  <div class="header">
    <div class="header-container">
      <h1 class="header-title">
        More than just
        <br />shorter links
      </h1>
      <p class="header-info">Build your brand's recognition and get detailed insights on how your links are performing.</p>
      <nuxt-link to="/start" id="getStarted">Get Started</nuxt-link>
    </div>
    <img class="illustration" src="~assets/images/illustration-working.svg" alt="working illustration">
  </div>
</template>

<script>
export default {
  name: "HeaderView"
};
</script>

<style>
.header {
    display: flex;
    justify-content: space-between;
    background-color: white;
    margin-bottom: 150px;
}

.header-container {
    width: 40vw;
    margin-top: 110px;
}

.header-title {
    font-size: 4.2em;
    color: hsl(257, 27%, 26%);
}

.header-info {
    color: hsl(0, 0%, 75%);
    font-size: 1.5em;
}

.illustration {
    margin-right: -20%;
    display: inline-block;
    margin-top: 50px;
    width: 700px;
    height: 450px;
}

#getStarted {
    display: inline-block;
    margin-top: 30px;
    background-color: hsl(180, 66%, 49%);
    color: white;
    padding: 10px 20px 10px 20px;
    border-radius: 20px;
    transition: background-color 0.2s;
    text-decoration: none;
}

#getStarted:hover {
    background-color: hsl(180, 71%, 57%);
}
</style>