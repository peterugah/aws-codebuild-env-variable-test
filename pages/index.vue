<template>
  <div class="columns is-mobile">
    <div class="column is-6 has-text-centered">{{ ADMIN_END_ROUTE }}</div>
    <div class="column is-6 has-text-centered">hello</div>
  </div>
</template>

<script>
export default {
  asyncData({ $config }) {
    return {
      ADMIN_END_ROUTE: $config.ADMIN_END_ROUTE,
    }
  },
}
</script>
