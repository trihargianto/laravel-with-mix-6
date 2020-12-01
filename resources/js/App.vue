<template>
  <div>Hello Im from Vue</div>
</template>

<script>
export default {
  name: "App",
  mounted() {
    console.log('1.', process);
    console.log('2.', process.env);
    console.log('3.', process.env.TEST);
    console.log('4.', process.env.MIX_TEST);
  },
};
</script>
