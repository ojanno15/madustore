<template>
  <div>
    <Navbar/>
    <Jumbotron/>
    <Embed/>
    <CardProduct/>
    <Benefit/>
    <TestimoniSection/>
    <FooterSection/>
  </div>
</template>

<script>
import NavbarSection from '~/components/NavbarSection.vue'
import JumbotronSection from '~/components/JumbotronSection.vue'
import Embed from '~/components/Embed.vue'
import Product from '~/components/Product.vue'
import Testimoni from '~/components/Testimoni.vue'
import Footer from '~/components/Footer.vue'
import Benefit from '~/components/Benefit.vue'
export default {
  components: {
    Navbar: NavbarSection,
    Jumbotron: JumbotronSection,
    Embed: Embed,
    CardProduct: Product,
    Benefit: Benefit,
    TestimoniSection: Testimoni,
    FooterSection: Footer,
  }
}
</script>

<style>
</style>
