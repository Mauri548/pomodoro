<template>
    <h1>Hello World!</h1>
    <Timer :time="90" />
</template>

<script>
import Timer from '@/components/Timer.vue';

export default {
  name: 'Pomodoro',
  components: {
    Timer,
  },
};
</script>

<style lang="scss" scoped>

</style>
