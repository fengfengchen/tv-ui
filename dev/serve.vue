<script>
import Vue from "vue";
// Uncomment import and local "components" registration if library is not registered globally.
import { TvButton } from "@/entry.esm";

export default Vue.extend({
  name: "ServeDev",
  components: {
    TvButton,
  },
});
</script>

<template>
  <div id="app">
    <tv-ui-sample />
    <TvButton text="USA I'm your father"></TvButton>
  </div>
</template>
