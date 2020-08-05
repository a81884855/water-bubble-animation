<template>
  <div class="background">
    <div class="navbar">
      <img src="../assets/logo.png" class="logo" />
      <button type="button">Sign up</button>
    </div>
    <div class="content">
      <small>Welcome to our</small>
      <h1>
        World's
        <br />Creative Studio
      </h1>
      <button type="button">Take a tour</button>
    </div>
    <div class="side-bar">
      <img src="../assets/menu.png" class="menu" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Jumbotron"
};
</script>

<style scoped>
.background {
  width: 100%;
  height: 100vh;
  background-image: url(../assets/background.png);
  background-size: cover;
  background-position: center;
  position: relative;
  overflow: hidden;
}

.logo {
  width: 100px;
  cursor: pointer;
}

.navbar {
  width: 85%;
  height: 15%;
  margin: auto;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

button {
  color: #fbfcfd;
  padding: 10px 25px;
  background: transparent;
  border: 1px solid #fff;
  border-radius: 20px;
  outline: none;
  cursor: pointer;
}

.content {
  color: #fbfcfd;
  position: absolute;
  top: 50%;
  left: 8%;
  transform: translateY(-50%);
  z-index: 2;
}

h1 {
  font-size: 80px;
  margin: 10px 0 30px;
  line-height: 80px;
}

.side-bar {
  width: 50px;
  height: 100vh;
  background: linear-gradient(#00545d, #000729);
  position: absolute;
  right: 0;
  top: 0;
}
</style>