<script>
  export let size = "md"
</script>

<button class={size}>
  <slot />
</button>

<style>
  button {
    margin: 0;
  }

  .sm {
    width: 100px;
    height: 50px;
  }

  .md {
    width: 200px;
    height: 100px;
  }
</style>