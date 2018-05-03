<template>
  <div id="app">
    <Header />
    <Container />
    <Footer />
  </div>
</template>

<script>
import Header from './components/common/Header'
import Footer from './components/common/Footer'
import Container from './components/Container'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Container
  }
}
</script>

<style>

</style>
