<template>
  <div class="sidebar">
    <a
      class="headphoto-ring"
      href="https://github.com/violva317018"
      target="_blank"
      rel="noopener"
    >
      <img class="headphoto" src="../assets/myheadphoto.jpg" />
    </a>
    <div class="margin-l"><p class="title">Ryan's blog</p></div>
    <div class="margin-l"><p class="introduction">網頁開發分享小網站。</p></div>
  </div>
</template>

<script>
export default {
  name: "SideBar",
};
</script>

<style scoped>
.sidebar {
  background-color: rgb(75, 74, 73);
  position: absolute;
  width: 350px;
  height: 100%;
}
.headphoto-ring {
  display: block;
  margin: 100px auto 20px auto;
  width: 120px;
  height: 120px;
  border: 2px solid rgb(124, 124, 124);
  border-radius: 50%;
  overflow: hidden;
  transition: 0.5s;
}
.headphoto {
  width: 120px;
  transition: 0.5s;
}
.headphoto:hover {
  transform: scale(1.2);
  transition: 0.5s;
}
.headphoto-ring:hover {
  border: 2px solid rgb(233, 233, 233);
  transition: 0.5s;
}
.title {
  font-family: "Heebo", sans-serif;
  font-size: 1.7rem;
  color: rgb(189, 189, 189);
  letter-spacing: 0.5px;
  text-align: left;
}
.introduction {
  color: #d3cfcf;
  text-align: left;
}
.margin-l {
  margin-left: 105px;
}
</style>
