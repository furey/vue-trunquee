<template>
  <div class="container">
    <Trunquee :text="text"/>
  </div>
</template>

<script>

import Trunquee from './components/Trunquee.vue';

export default {

  name: 'demo',

  components: {
    Trunquee,
  },

  data: () => ({
    text: 'Super-cali-fragil-isitc-expi-alid-ocious!',
  }),

}

</script>

<style>

html, body {
  margin: 0;
  padding: 0;
}

html {
  height: 100%;
  overflow: auto;
}

body {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: 'Arial';
}

.container {
  flex: 0 1 auto;
  width: 60vw;
  font-size: 6vw;
  font-weight: bold;
  letter-spacing: -0.2vw;
}

</style>
