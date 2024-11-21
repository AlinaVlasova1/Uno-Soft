<script lang="ts">
import {defineComponent} from 'vue';
import {IFriend} from "@/models/friend";
export default defineComponent({
  name: "FriendPage",
  data() {
    return {
      friendsArray: [] as Array<IFriend>,

    }
  },
})
</script>

<template>
  <div>
    <div class="friends"></div>
    <div class="notes"></div>
    <button>Назад</button>
  </div>
</template>

<style scoped>

</style>