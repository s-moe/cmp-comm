<template>
  <div>
    <active-user></active-user>
    <user-data></user-data>
  </div>
</template>

<script>
import ActiveUser from "./components/ActiveUser.vue";
import UserData from "./components/UserData.vue";
export default {
  components: { ActiveUser, UserData },
};
</script>
