<template>
  <div class="footer-menus"></div>
</template>

<script>

import { mapState } from 'vuex'

export default {
  computed: {
    ...mapState('space', ['name']),
  },
}

</script>

<style></style>
