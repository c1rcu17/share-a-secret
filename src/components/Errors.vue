<template lang="pug">
ul
  li(v-for="e in errors") {{ e }}
</template>

<script>
export default {
  name: 'Errors',
  props: {
    errors: {
      type: Array,
      required: true
    }
  }
};
</script>
