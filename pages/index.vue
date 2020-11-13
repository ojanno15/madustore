<template>
  <div>
    <NavbarSection/>
    <JumbotronSection/>
    <AboutSection/>
    <ProductSection/>
    <TestimoniSection/>
    <BenefitsSection/>
    <FooterSection/>
  </div>
</template>

<script>
import Navbar from '~/components/NavbarSection.vue'
import Jumbotron from '~/components/JumbotronSection.vue'
import About from '~/components/AboutSection.vue'
import Product from '~/components/ProductSection.vue'
import Testimoni from '~/components/TestimoniSection.vue'
import Benefits from '~/components/BenefitsSection.vue'
import Footer from '~/components/FooterSection.vue'
export default {
  components: {
    NavbarSection: Navbar,
    JumbotronSection: Jumbotron,
    AboutSection: About,
    ProductSection: Product,
    TestimoniSection: Testimoni,
    BenefitsSection: Benefits,
    FooterSection: Footer,
  }
}
</script>
<style>
*{
  height: auto!important;
}
body {
  background-color: white!important;
}
</style>
