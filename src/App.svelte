<script>
  import Card from "./Card.svelte";

  let cards = new Array(20).fill().map(() => {
    return Math.floor(Math.random() * 16777215).toString(16);
  });

  // export let name;
</script>

<style>
  main {
    display: flex;
    align-items: center;
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
</style>

<main>
  <div class="board">
    {#each cards as card}
      <Card color={card} />
    {/each}
    <!--
		<div style="background-color:#369;" />
    <div style="background-color:#379;" />
    <div style="background-color:#469;" />
    <div style="background-color:#468;" />
    <div style="background-color:#368;" />
    <div style="background-color:#269;" />
    <div style="background-color:#279;" />
    <div style="background-color:#378;" />
    <div style="background-color:#257;" />
    <div style="background-color:#267;" />
    <div style="background-color:#458;" />
    <div style="background-color:#258;" />
    <div style="background-color:#278;" />
    <div style="background-color:#457;" />
    <div style="background-color:#27a;" />
    <div style="background-color:#36a;" />
    <div style="background-color:#46a;" />
    <div style="background-color:#37a;" />
    <div style="background-color:#369;" />
    <div style="background-color:#369;" />
 -->
  </div>
</main>
