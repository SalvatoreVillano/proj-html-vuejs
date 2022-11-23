<template>
  <HeaderComponent :headerMenu="headerElem" />
  <MainComponent />
  <FooterComponent :footerMenu="FooterElem" />
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
      ],
      FooterElem: [
        {
          section: 'About',
          elem: [
            {
              name: 'The company'
            },
            {
              name: 'Institutional'
            },
            {
              name: 'Social & Events'
            },
            {
              name: 'Innovation'
            },
            {
              name: 'Environment'
            },
            {
              name: 'Technology'
            }
          ]
        },
        {
          section: 'Services',
          elem: [
            {
              name: 'Audit & Assurance'
            },
            {
              name: 'Financial Advisory'
            },
            {
              name: 'Analytics'
            },
            {
              name: 'Middle Marketing '
            },
            {
              name: 'Legal Consulting'
            },
            {
              name: 'Regulatory Risk'
            }
          ]
        },
        {
          section: 'Support',
          elem: [
            {
              name: 'The company'
            },
            {
              name: 'Institutional'
            },
            {
              name: 'Social & Events'
            },
            {
              name: 'Innovation'
            },
            {
              name: 'Environment'
            },
            {
              name: 'Technology'
            },
          ],
        },
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

</style>