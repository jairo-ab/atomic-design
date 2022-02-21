<template>
  <div class="component">
    <Home />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Home } from '@/components/templates'

export default defineComponent({
  components: { Home }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
