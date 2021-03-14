<template>
  <v-container>
    <v-container class="card">
      <CardMenu color="rgb(139, 38, 166)" />
      <CardMenu color="rgb(248, 182, 46)" class="ml-2" />
    </v-container>
    <v-container class="card">
      <CardMenu color="rgb(72, 92, 189)" />
      <CardMenu color="rgb(186, 214, 0)" class="ml-2" />
    </v-container>
    <v-container class="card">
      <CardMenu color="rgb(255, 81, 69)" />
      <CardMenu color="rgb(0, 187, 223)" class="ml-2" />
    </v-container>
    <v-container class="card">
      <CardMenu color="rgb(25, 215, 25)" />
      <CardMenu color="rgb(240, 45, 125)" class="ml-2" />
    </v-container>
  </v-container>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import CardMenu from "@/components/CardMenu.vue";

@Component({
  components: {
    CardMenu
  }
})
export default class HelloWorld extends Vue {}
</script>

<style lang="scss">
.card {
  display: flex;
  justify-content: center;
}
</style>
