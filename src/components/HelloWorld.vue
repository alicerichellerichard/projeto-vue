<template>
  <div id="header">
    <header class="header">
        <div>
          <img src="" alt="">
          </div>
          <div></div>
            <nav class="nav-header">
              <div class="router-link">
                <router-link to="/">Pagina Inicial</router-link>
                <router-link to="/">Sobre nós</router-link>
                <router-link to="/">Contato</router-link>
              </div>
            </nav>
          </div>
       </div>
    </header>
</template>

<script>
export default {
  name: "Header",
}
</script>
<style scoped>
header {
  width: 100vw;
  height: 80px;
}
</style>