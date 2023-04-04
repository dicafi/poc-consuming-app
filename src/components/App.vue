
<template>
  <div>
    <router-view />

    <exposed origin="remote"/>

	<br />
	 A demo of a single page application made in Vue.js, PostCSS and Bootstrap

  </div>
</template>

<script>
  import exposed from 'exposing/Exposed'

  export default {
    components: {
      exposed,
    }
  }
</script>
