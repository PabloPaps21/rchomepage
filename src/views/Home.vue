<template>
  <div class="home">
    <Head />
    <OurServices />
    <WhyUs />
    <ListUs />
    <Banner />
    <AskFor />
    <Foot />
  </div>
</template>

<script>
// @ is an alias to /src
import Head from '@/components/Head.vue';
import OurServices from '@/components/OurServices.vue';
import WhyUs from '@/components/WhyUs.vue';
import ListUs from '@/components/ListUs.vue';
import Banner from '@/components/Banner.vue';
import AskFor from '@/components/AskFor.vue';
import Foot from '@/components/Foot.vue';

export default {
  name: 'home',
  components: {
    Head,
    OurServices,
    WhyUs,
    ListUs,
    Banner,
    AskFor,
    Foot,
  },
};
</script>
