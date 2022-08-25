<template>
  <div class="body">
    <div class="header">
      <h1>{{ msg }}</h1>
      <h2>Essential Links</h2>
    </div>
    <div class="but-grup">
      <ButtonsCompo
        onclick="window.location.href = 'https://salai.be/';"
        target="'_blank';"
      >
      </ButtonsCompo>

      <ButtonsCompo></ButtonsCompo>
      <ButtonsCompo></ButtonsCompo>
      <ButtonsCompo onclick="window.open('https://salai.be/','_blank')">
      </ButtonsCompo>
    </div>
  </div>
</template>

<script>
import ButtonsCompo from "@/components/ButtonsCompo.vue";
export default {
  name: "Home-page",
  components: {
    ButtonsCompo,
  },
  data() {
    return {
      msg: "Welcome to  Click for TuuMee",
    };
  },
};
</script>

<style scoped>
.header {
  padding-top: 2vh;
}
.but-grup {
  display: flex;
  flex-wrap: wrap;
  margin: auto;
  width: 80%;
  /* border: 3px solid green; */
  padding: 10px;
}
</style>
