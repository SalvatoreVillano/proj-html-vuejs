<template>
  <HeaderComponent :headerMenu="headerElem" />
  <MainComponent />
  <FooterComponent />
</template>

<script>
import FooterComponent from './components/FooterComponent.vue';
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';

export default {
  components: { HeaderComponent, MainComponent, FooterComponent },
  data() {
    return {
      headerElem: [
        {
          name: 'Home'
        },
        {
          name: 'About'
        },
        {
          name: 'Services'
        },
        {
          name: 'Process'
        },
        {
          name: 'Team'
        },
        {
          name: 'Blog'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>