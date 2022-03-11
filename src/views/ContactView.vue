<template>
  <TheContact />
  <TheInfo />
</template>
<script>
import TheContact from "@/components/TheContact.vue";
import TheInfo from "@/components/TheInfo.vue";
export default {
  name: "ContactView",
  components: {
    TheContact,
    TheInfo,
  },
};
</script>
