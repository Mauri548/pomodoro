<template>
    <button class="button" @click="onClick()">
        <slot/>
    </button>
</template>

<script>

export default {
  name: 'Button',

  methods: {
    onClick() {
      this.$emit('click-button');
    },
  },

};
</script>

<style lang="scss" scoped>
.button {
    all: unset; // resetea todas las propiedades de button x defecto
    width: 100%;
    padding: 10px;
    font-weight: 500;
    background-color: var(--application-color-accent);
    text-align: center;
    border-radius: 5px;
    box-shadow: 0 0 10px 2px rgba(0, 0, 0, 0.1);
    text-transform: uppercase;
    cursor: pointer;
}
</style>
