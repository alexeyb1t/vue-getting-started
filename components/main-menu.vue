<template>
  <div>
    <header class="container">
      <div class="tabs">
        <ul>
          <li>
            <NuxtLink to="/">Main</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/about-us">About us</NuxtLink>
          </li>
          <li>
            <NuxtLink to="/contact">Contact</NuxtLink>
          </li>
        </ul>
      </div>
    </header>
  </div>
</template>

<script>

export default {
  name: 'MainMenu',
}

</script>
