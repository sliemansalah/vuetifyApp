<template>
  <v-app :dir="direction">
    <SideHeaderBar />
  </v-app>
</template>

<script>
import SideHeaderBar from "@/components/SideHeaderBar";
export default {
  components: {
    SideHeaderBar,
  },
  data() {
    return {
      direction: "rtl",
    };
  },
};
</script>