<template>
  <MainContainer>
    <HeaderComponent/>
  </MainContainer>
</template>

<script>
import {defineComponent} from "vue";
import HeaderComponent from "@/components/HeaderComponent.vue";
import MainContainer from "@/components/MainContainer.vue";

export default defineComponent({
  components: {MainContainer, HeaderComponent}
})
</script>