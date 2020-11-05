<template>
  <div class="main text-center flex flex-col items-center justify-center">
    <!-- <logo /> -->
      <contact-form />
  </div>
</template>

<script>
import ContactForm from '~/components/ContactForm'
export default {
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }]
    }
  },
  components: { ContactForm }
}
</script>