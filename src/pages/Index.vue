<template>
  <div>
    <q-input v-model="text" type="textarea" autogrow/>
    <q-markdown :src="text" />
  </div>
</template>

<script>
import md from '../assets/testtext.md'
export default {
  name: 'PageIndex',
  data () {
    return {
      text: md
    }
  }
}
</script>
