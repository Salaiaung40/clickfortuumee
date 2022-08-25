<template>
  <button class="button-87" type="button">
    <!-- <slot v-on="Link - 1"> </slot> v-on="(href = '{{ }}')" -->
    <img class="but-imgs" src="@/assets/Money.jpg" alt="_" /> <br />

    Click Here
  </button>
</template>

<script>
export default {};
</script>

<style scoped>
.button-87 {
  margin: 10px;
  padding: 15px 30px;
  max-width: 50%;
  text-align: center;
  text-transform: uppercase;
  transition: 0.5s;
  background-size: 200% auto;
  color: white;
  border-radius: 10px;
  display: block;
  border: 0px;
  /* font-size: 50%; */
  font-size: 2.5vw;
  /* font-size-adjust: inherit; */
  font-weight: 700;
  box-shadow: 0px 0px 14px -7px #f09819;
  background-image: linear-gradient(
    45deg,
    #ff512f 0%,
    #f09819 51%,
    #ff512f 100%
  );
  cursor: pointer;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}

.button-87:hover {
  background-position: right center;
  /* change the direction of the change here */
  color: #fff;
  text-decoration: none;
}

.button-87:active {
  transform: scale(0.95);
}

.but-imgs {
  width: 7vw;
  /* padding: 0 0 0.5em 0; */
  /* size: 0.5em; */
}
</style>
