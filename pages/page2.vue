<template>
  <section class="container">
    <div>
      <logo />
      <h1 class="title">
        Page2
      </h1>
      <div class="links">
        <nuxt-link to="/conversion">
          <div class="button--grey">Conversion 獲得</div>
        </nuxt-link>
      </div>
    </div>
  </section>
</template>

<!-- Access Code -->
<script type="text/javascript" src="//apojaws.localhost/js/piwik/piwik.js"></script>
<script type="text/javascript" src="//apojaws.localhost/js/piwik/piwik_check.js?cid=e53d9c58d9fe28c6456e25f7a29be310" ></script>
<!-- End Access Code -->


<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
