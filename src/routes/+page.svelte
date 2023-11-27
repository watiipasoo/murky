<script>
  import Herosection from "../components/HeroSection/herosection.svelte";
  import Companiessection from "../components/CompaniesSection/companiessection.svelte";
  import Brandingsection from "../components/BrandingSection/brandingsection.svelte";
  import Customsection from "../components/CustomSection/customsection.svelte";
  import Testimonialsection from "../components/TestimonialSection/testimonialsection.svelte";
  import Contactsection from "../components/ContactSection/contactsection.svelte";
  import Footer from "../components/Foooter/footer.svelte";
</script>

<section>
  <Herosection />
  
  <div class="relative">
    <img src="/ell1.svg" alt="" class="hidden lg:block absolute right-0" />
    <Companiessection />
    <img src="/ell1.svg" alt="" class="block lg:hidden absolute bottom-[-200px]" />
    <Brandingsection />
    <Customsection />
  </div>
  <Testimonialsection />
  <Contactsection />
  <Footer />
</section>
