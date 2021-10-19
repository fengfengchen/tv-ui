<script>
import Vue from "vue";
// Uncomment import and local "components" registration if library is not registered globally.
import { FccButton } from "@/entry.esm";

export default Vue.extend({
  name: "ServeDev",
  components: {
    FccButton,
  },
});
</script>

<template>
  <div id="app">
    <tv-ui-sample />
    <FccButton text="i'm your father"></FccButton>
  </div>
</template>
