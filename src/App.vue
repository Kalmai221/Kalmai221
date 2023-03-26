<script setup>
import Title from './components/Title.vue'
import Section1 from './components/Section1.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <Title msg="An Average Intermediate Developer" />
      <svg height="5" width="100%">
        <line x1="0" y1="0" x2="20" y2="0"
        style="stroke:rgb(128, 128, 128);stroke-width:1" />
       </svg>
    </div>
  </header>

  <main>
    <br>
    <Section1></Section1>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
  
</style>
