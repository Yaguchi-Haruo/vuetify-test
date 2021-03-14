<template>
  <v-card elevation="2" :color="getColor">
    <v-list-item three-line>
      <v-list-item-content>
        <div class="overline mb-4">
          OVERLINE
        </div>
        <v-list-item-title class="headline mb-1">
          Headline 5
        </v-list-item-title>
        <v-list-item-subtitle
          >Greyhound divisely hello coldly fonwderfully
        </v-list-item-subtitle>
      </v-list-item-content>
    </v-list-item>
  </v-card>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class CardMenu extends Vue {
  @Prop()
  public color: string | undefined;
  get getColor() {
    return this.color;
  }
}
</script>
