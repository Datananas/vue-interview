<template>
  <div class="home">
    <SearchField />
  </div>
</template>

<script>
// @ is an alias to /src
import SearchField from '@/components/SearchField.vue'

export default {
  name: 'Home',
  components: {
    SearchField
  }
}
</script>
