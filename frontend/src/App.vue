<template>
  <MainContainer>
    <Header/>
  </MainContainer>
</template>

<script>
import {defineComponent} from "vue";
import Header from "@/components/Header.vue";
import MainContainer from "@/components/MainContainer.vue";

export default defineComponent({
  components: {MainContainer, Header}
})
</script>