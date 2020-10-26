<template>
  <div class="columns is-mobile">
    <div class="column is-6 has-text-centered">{{ ADMIN_END_ROUTE }}</div>
    <div class="column is-6 has-text-centered">
      the envionment variale ADMIN_END_ROUTE was read
    </div>
  </div>
</template>

<script>
export default {
  asyncData({ $config }) {
    // get the env variable from the config parameter
    return {
      ADMIN_END_ROUTE: $config.ADMIN_END_ROUTE,
    }
  },
}
</script>
