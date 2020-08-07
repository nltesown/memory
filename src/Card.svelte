<script>
  export let color;
</script>

<style>
  div {
    cursor: pointer;
  }

  div:before {
    display: inline-block;
    content: "";
    padding-bottom: 100%;
  }
</style>

<div style="background-color:#{color || '69f'}" />
