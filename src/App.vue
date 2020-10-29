<template>
  <a-config-provider :locale="locale">
    <div id="app">
      <router-view/>
    </div>
  </a-config-provider>
</template>

<script>

export default {
  data () {
    return {
    }
  },
  created () {
  }
}
</script>
