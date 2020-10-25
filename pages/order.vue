<template>
  <div>
    order
    <v-navigation-drawer :right="right" fixed app>
      <v-list></v-list>
    </v-navigation-drawer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      fixed: false,
      right: true,
    }
  },
}
</script>
