<template>
  <div id="app">
    <h1 class="display-1">{{message}}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Welcome to My Page!'
    };
  },
  methods: {
    // doSomething() {
    //   alert('Hello!');
    // }
  }
};
</script>
<style lang="scss">
@use "sass:list";
$colors : red, green, blue;

#app {
    h1 {
        color: list.nth($colors,3);
    }
}

</style>