<template>
  <div>
    <AHeader />

    <div class="uk-section uk-section-default">
      <div class="uk-container uk-container-large">
        <Nuxt />
      </div>
    </div>
  </div>
</template>

<style></style>
<script>
import AHeader from '~/components/AHeader'
export default {
  components: { AHeader },
}
</script>
