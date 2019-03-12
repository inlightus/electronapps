<template>
  <div>
    <h1>Main page</h1>
    <p>{{ hello }}</p>
    <router-link to="/about">about</router-link>
  </div>
</template>

<script>
  export default {
    name: 'main-page',
    data() {
      return {
        hello: 'hello world',
      };
    },
  };
</script>
