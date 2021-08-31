<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">{{ authorName }}</h1>
      // This is the sample
    </div>
  </div>
</template>
<script lang="ts">
import { Component, Vue } from "nuxt-property-decorator";
import Logo from "~/components/VuetifyLogo.vue";

@Component({
  components: {
    Logo
  }
})
export default class extends Vue {
  authorName: string = "Usong";
}
</script>
