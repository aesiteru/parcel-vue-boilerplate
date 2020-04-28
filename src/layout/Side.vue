<template>
  <div class="layout__side">
    <aside>
      Side
    </aside>
    <main>
      <slot />
    </main>
  </div>
</template>

<script>
export default {

}
</script>
<style lang="scss">
.layout__side {
  display: grid;
  height: 100vh;
  border: 1px solid orange;
  grid-template-columns: 0.15fr 0.8fr;

  aside {
    background-color: #333;
    color: #fff;
  }
}
</style>