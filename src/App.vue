<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="search...">
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      api_key: "60bc1e306b6fedb9805794cb8ab47ed3",
    };
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  background-image: url("./assets/imgs/warm.jpg");
  background-position: bottom;
  background-size: cover;
  transition: 0.4s;
}

main {
  min-height: 100vh;
  padding: 25px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,.25), rgba(0,0,0, .75));
}

.search-box {
  width: 100%;
  margin-bottom: 30px;
}

.search-box .search-bar {
  display: block;
  width: 00%;
  padding: 15px;
  color: #313131;
  font-size: 20px;

  appearance: none;
  border: none;
  outline: none;
  background: none;

  background-color: rgba(255,255,255,0.5);
  border-radius: 0px 16px 0px 16px;
  box-shadow: 0px 0px 8px regba(0,0,0,0.25);
  transition: 0.4s
}

.search-box .search-bar:focus {
  background-color: rgba(255,255,255,0.5);
  border-radius: 0px 16px 0px 16px;
  box-shadow: 0px 0px 8px regba(0,0,0,0.25);
}
  
  </style>
