<template>
  <div>Hello {{ value }}
     <h1>HUMBLE</h1>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World"
    };
  }
};
</script>
