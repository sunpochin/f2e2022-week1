<template>
  <div class="outer">
    <!-- <Logo /> -->
    <!-- <img src="" alt=""> -->
    <ul class="xxxxx">
      <li class="mr-8 li">
        <a href="">關卡資訊</a>
      </li>
      <li class="mr-8 li"><a href="">攻略資源</a></li>
      <li class="mr-8 li"><a href="">求職專區</a></li>
      <button class="h-10 border rounded-full w-20 hover:border-accent hover:text-accent">
        <a href="">登入</a>
      </button>
    </ul>
  </div>
</template>

<script setup>
// import Logo from "../image/F2E-Logo.png";
</script>

<style scoped>
.outer {
  display: flex;
}
.xxxxx {
  display: flex;
  justify-content: space-around;
  align-items: center;
  list-style-type: none;
}

li {
  margin: 8px;
}
li a:hover {
  color: white;
  border: black;
}

</style>
