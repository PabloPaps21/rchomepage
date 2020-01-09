<template>
  <div class="home">
    <Head />
    <OurServices />
    <WhyUs />
    <ListUs />
  </div>
</template>

<script>
// @ is an alias to /src
import Head from '@/components/Head.vue';
import OurServices from '@/components/OurServices.vue';
import WhyUs from '@/components/WhyUs.vue';
import ListUs from '@/components/ListUs.vue';

export default {
  name: 'home',
  components: {
    Head,
    OurServices,
    WhyUs,
    ListUs,
  },
};
</script>
