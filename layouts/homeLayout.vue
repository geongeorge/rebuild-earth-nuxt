<template>
  <div>
      <Navigation></Navigation>
      <nuxt/>
  </div>
</template>

<script>
import Navigation from '~/components/utils/Navigation'

export default {
    components : {
        Navigation
    }
}
</script>