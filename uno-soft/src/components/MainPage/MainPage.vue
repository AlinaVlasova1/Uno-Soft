<script lang="ts">
import {IFriend} from "@/models/friend";
import {defineComponent} from "vue";

export default defineComponent({
  name: "MainPage",
  data() {
    return {
      initialFriendsArray: [] as Array<IFriend>,
    }
  },
})
</script>

<template>
  <div>
    <div>
      <input>
      <button>Построить</button>
    </div>

  </div>
</template>

<style scoped>

</style>