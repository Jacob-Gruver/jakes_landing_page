<template>
  <header>
    <Navbar />
  </header>
  <main>
    <router-view v-slot="{Component}">
      <transition name="route" mode="out-in">
        <component :is="Component" />
      </transition>
    </router-view>
  </main>
  <footer>
    <div class="text-primary text-center p-4">
      Made with 💖 by a CodeMonkey
    </div>
  </footer>
</template>

<script>
import { computed } from 'vue'
import { AppState } from './AppState'
export default {
  name: 'App',
  setup() {
    return {
      appState: computed(() => AppState)
    }
  }
}
</script>
<style lang="scss">
@import "./assets/scss/main.scss";

footer {
  background-color: azure;
}

</style>
