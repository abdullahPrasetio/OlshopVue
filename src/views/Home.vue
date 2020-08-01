<template>
  <div class="home">
    <HeaderOlshop/>
    <HeroOlshop/>
    <WomenOlshop/>
    <InstaOlshop/>
    <LogoOlshop/>
    <FooterOlshop/>

  </div>
</template>

<script>
// // @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderOlshop from '@/components/HeaderOlshop.vue';
import HeroOlshop from '@/components/HeroOlshop.vue';
import WomenOlshop from '@/components/WomenOlshop.vue';
import InstaOlshop from '@/components/InstaOlshop.vue';
import LogoOlshop from '@/components/LogoOlshop.vue';
import FooterOlshop from '@/components/FooterOlshop.vue';

export default {
  name: 'Home',
  components: {
    HeaderOlshop,
    HeroOlshop,
    WomenOlshop,
    InstaOlshop,
    LogoOlshop,
    FooterOlshop
  }
}
</script>
