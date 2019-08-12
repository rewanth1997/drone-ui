<template>
  <div class="container">
    <div class="logout">
      <h1>Your are now signed out</h1>
      <form action="/logout" method="GET">
        <Button type="submit" theme="primary" size="l">LogOuuuut</Button>
      </form>
    </div>
  </div>
</template>

<script>
import Button from "@/components/buttons/Button.vue";
export default {
  name: "logout",
  components: {
    Button
  }
};
</script>

<style scoped>
div.container {
  align-items: center;
  background: #fbfbfb;
  box-sizing: border-box;
  display: flex;
  justify-content: center;
  padding: 30px;
  height: 100%;
  width: 100%;
}

.logout {
  width: 300px;

  background: #fff;
  border: 1px solid #e8eaed;
  border-radius: 3px;
  box-shadow: 0px 0px 8px 1px #e8eaed;
  padding: 30px;
}
</style>
