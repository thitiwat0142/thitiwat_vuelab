<template>
  <profiles></profiles>
  <contract></contract>
</template>

<script>
import Profiles from "./page/Profiles.vue";
import Contract from "./page/Contract.vue";
export default {
  name: "App",
  components: {
    Profiles: Profiles,
    Contract: Contract,
  },
};
</script>
