<template>
  <div class="social-networks">
    <SocialLink
      name="Github"
      to="https://github.com/jairo-ab"
      icon="github.svg"
    />
    <SocialLink
      name="Facebook"
      to="https://github.com/jairo-ab"
      icon="facebook.svg"
    />
    <SocialLink
      name="Twitter"
      to="https://github.com/jairo-ab"
      icon="twitter.svg"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
  components: { SocialLink }
})
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
