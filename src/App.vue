<template>
  <hero/>
  <cards />
  <hr />
  <forms />
  <foot />
</template>

<script>
import hero from "./components/hero.vue";
import cards from "./components/cards.vue";
import forms from "./components/forms.vue";
import foot from "./components/foot.vue";

export default {
  name: "App",
  components: {
    hero,
    cards,
    forms,
    foot
  },
  data(){return{
    img:require('./assets/logo.png')
  }}
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap");
.container {
  margin: 0;
  width: 100vw;
  height: auto;
}

.hero-body {
  display: flex;
  justify-content: center;
}

.hero {
  /* background-image: url("https://images.unsplash.com/photo-1518655048521-f130df041f66?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1500&q=80"); */
  background-image:url('assets/bg.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  opacity: 0.8;
  position: relative;
}
.hero-content {
  position: relative;
  z-index: 100;
  text-align: center;
  display: flex;
  flex-direction: column;
}
.hero .title {
  font-size: 4em;
  font-family: Roboto;
}
.hero .subtitle {
  font-size: 2em;
}

#sec .box {
  text-align: center;
  height: 100%;
}
#sec .title {
  font-family: Roboto;
}
#sec .line {
  width: 50%;
  height: 0.5rem;
  background-color: blue;
}
#sec .iconify {
  width: 5em;
  color: #ecf0f1;
  height: 5em;
  background-color: #1dd1a1;
  padding: 0.5em;
  margin: 1em;
  border-radius: 10px;
}

form {
  font-family: Roboto;
  background: transparent;
}
form .input,
form .textarea {
  background: none repeat scroll 0 0 rgba(255, 255, 255, 0.5);
  border-radius: 0;
  box-shadow: none;
  height: 10vh;
  padding-left: 20px;
  letter-spacing: 2px;
  font-family: Roboto;
}
form .button {
  padding: 0.8em 1.4rem;
  border-radius: 0;
  height: auto;
  background-color: #1dd1a1;
  color: #ecf0f1;
  letter-spacing: 2px;
  font-weight: bold;
}
form .button:hover {
  box-shadow: 5px 5px 6px 1px #1abc9c;
  color: #ecf0f1;
}

footer hr {
  background-color: #bdc3c7;
}
footer .iconify {
  width: 2em;
  height: 2em;
  font-weight: lighter;
}
footer .iconify:hover {
  color: #1dd1a1;
}

/*# sourceMappingURL=style.css.map */
</style>
