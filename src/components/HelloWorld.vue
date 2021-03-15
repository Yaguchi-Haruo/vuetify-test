<template>
  <v-col>
    <v-row>
      <CardMenu color="rgb(139, 38, 166)" />
      <CardMenu color="rgb(30, 30, 30)" />
      <CardMenu color="rgb(248, 182, 46)" />
    </v-row>
    <v-row>
      <CardMenu color="rgb(72, 92, 189)" />
      <CardMenu color="rgb(30, 30, 30)" />
      <CardMenu color="rgb(186, 214, 0)" />
    </v-row>
    <v-row>
      <CardMenu color="rgb(255, 81, 69)" />
      <CardMenu color="rgb(30, 30, 30)" />
      <CardMenu color="rgb(0, 187, 223)" />
    </v-row>
    <v-row>
      <CardMenu color="rgb(25, 215, 25)" />
      <CardMenu color="rgb(30, 30, 30)" />
      <CardMenu color="rgb(240, 45, 125)" />
    </v-row>
  </v-col>
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

<style lang="scss"></style>
