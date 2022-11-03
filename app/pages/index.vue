<template>
  <div>
    <header>
      <div>
        <h1>Supasoda</h1>
      </div>
      <div>
        <h3>Making Soda great again !</h3>
      </div>
    </header>
    <section>
      <SodaCard />
    </section>
  </div>
</template>

<script>
  export default {
    name: "IndexPage",
  }
</script>

<style>
  * {
    font-family: 'Rubik', sans-serif;
  }

  header {
    text-align: center;
  }
</style>

