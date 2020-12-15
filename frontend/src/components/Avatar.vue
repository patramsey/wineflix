<template>
  <span class="user-avatar">
    <a :href="url">{{ letter }}</a>
  </span>
</template>

<script>
export default {
  name: 'Avatar',
  props: {
    letter: String,
    url: String,
    class: String,
  },
};
</script>
