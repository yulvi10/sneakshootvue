<template>
  <div class="home">
    <HeaderStore />
    <CarouselStore />
    <ItemsBanner />
    <InstaStore />
    <PartnerStore />
    <FooterStore />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderStore from "@/components/HeaderStore.vue";
import CarouselStore from "@/components/CarouselStore.vue";
import ItemsBanner from "@/components/ItemsBanner.vue";
import InstaStore from "@/components/InstaStore.vue";
import PartnerStore from "@/components/PartnerStore.vue";
import FooterStore from "@/components/FooterStore.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld,
    HeaderStore,
    CarouselStore,
    ItemsBanner,
    InstaStore,
    PartnerStore,
    FooterStore
  }
};
</script>
