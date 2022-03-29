<template>
  <div id="app">
    <Header />

    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Header,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

:root {
  --black: rgba(0, 0, 0, 1);
  --blue-stone-2: rgba(0, 102, 102, 0.38);
  --blue-stone: rgba(0, 102, 102, 1);
  --eerie-black: rgba(32, 32, 32, 1);
  --white: rgba(255, 255, 255, 1);

  --font-size-s: 9px;
  --font-size-m: 18px;
  --font-size-l: 24px;
  --font-size-xl: 48px;
  --font-size-xxl: 72px;
  --font-size-xxxl: 96px;

  --font-family-montserrat: "Montserrat";
  --font-family-roboto: "Roboto";
  --font-family-rye: "Rye";
}

.roboto-bold-white-24px {
  color: var(--white);
  font-family: var(--font-family-roboto);
  font-size: var(--font-size-l);
  font-weight: 700;
  font-style: normal;
}

.rye-normal-blue-stone-48px {
  color: var(--blue-stone);
  font-family: var(--font-family-rye);
  font-size: var(--font-size-xl);
  font-weight: 400;
  font-style: normal;
}

.montserrat-semi-bold-eerie-black-24px {
  color: var(--eerie-black);
  font-family: var(--font-family-montserrat);
  font-size: var(--font-size-l);
  font-weight: 600;
  font-style: normal;
}

.roboto-normal-blue-stone-48px {
  color: var(--blue-stone);
  font-family: var(--font-family-roboto);
  font-size: var(--font-size-xl);
  font-weight: 400;
  font-style: normal;
}

.roboto-normal-white-18px {
  color: var(--white);
  font-family: var(--font-family-roboto);
  font-size: var(--font-size-m);
  font-weight: 400;
  font-style: normal;
}

.rye-normal-blue-stone-72px {
  color: var(--blue-stone);
  font-family: var(--font-family-rye);
  font-size: var(--font-size-xxl);
  font-weight: 400;
  font-style: normal;
}

.roboto-bold-white-9px {
  color: var(--white);
  font-family: var(--font-family-roboto);
  font-size: var(--font-size-s);
  font-weight: 700;
  font-style: normal;
}

.montserrat-medium-white-24px {
  color: var(--white);
  font-family: var(--font-family-montserrat);
  font-size: var(--font-size-l);
  font-weight: 500;
  font-style: normal;
}

.roboto-normal-white-48px {
  color: var(--white);
  font-family: var(--font-family-roboto);
  font-size: var(--font-size-xl);
  font-weight: 400;
  font-style: normal;
}

.rye-normal-white-48px {
  color: var(--white);
  font-family: var(--font-family-rye);
  font-size: var(--font-size-xl);
  font-weight: 400;
  font-style: normal;
}

.roboto-normal-white-24px {
  color: var(--white);
  font-family: var(--font-family-roboto);
  font-size: var(--font-size-l);
  font-weight: 400;
  font-style: normal;
}
</style>
