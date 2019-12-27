<template>
  <div>
    <h1>{{ title }}</h1>
    <h1>{{ haha }}</h1>
    <h2>{{ huhu }}</h2>
  </div>
</template>
<script>
export default {
  name: "demo",
  drops: {
    title: String
  },
  data() {
    return {
      haha: "xin chao",
      huhu: "tam biet"
    };
  }
};
</script>
