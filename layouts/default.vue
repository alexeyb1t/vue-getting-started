<template>
  <div>
    <header>
      <main-menu/>
    </header>

    <div class="block">
      <Nuxt/>
    </div>

    <div class="footer">
      <div class="container">
        Footer
      </div>
    </div>
  </div>
</template>

<script>
import MainMenu from '../components/main-menu';
export default {
  name: 'DefaultLayout',
  components: {MainMenu},
}
</script>
