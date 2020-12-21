<template>
  <div id="app">
    <a :href="myUrl" target="_blank">link</a>
  </div>
</template>

<script>
export default {
  data() {
    return {
      myUrl: window.myUrl
    }
  }
}
</script>