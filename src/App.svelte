<script>
  // export let name;
</script>

<style>
  main {
    display: flex;
    align-items: center; /* flex-direction: row;
    flex-wrap: nowrap;
    justify-content: flex-start;
    align-content: flex-start;
 */

    width: 100%;
    margin: 0 auto;
    max-width: 66.67vh;
    height: 100vh;
  }

  .board {
    display: grid;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    width: 100%;
  }

  .board > div {
    background-color: #69f;
    outline: solid 1px #40404a;
    cursor: pointer;
  }

  .board > div:before {
    display: inline-block;
    content: "";
    padding-bottom: 100%;
  }
</style>

<main>
  <div class="board">
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
    <div />
  </div>
</main>
