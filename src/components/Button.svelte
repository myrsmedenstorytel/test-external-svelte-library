<script>
  import Icon from "./Icon.svelte";
</script>

<style>
  .button {
    padding: 10px 20px;
    background-color: #f50;
    color: #fff;
    font-weight: bold;
  }
</style>

<button class="button"><Icon />
  <slot /></button>
