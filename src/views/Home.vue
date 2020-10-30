<template>
  <div class="home">
    <img alt="Vue logo" src="~@img/logo.png">
    <HelloWorld :msg="msg" />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@c/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {
  msg: string = "Welcome to Your Vue.js + TypeScript App __ ty";
  data() {
    return {};
  }
}
</script>
