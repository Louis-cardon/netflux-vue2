<template>
 <div id="NavBar">
   <div class="div">
     <span>
      <label class="logo">NETFLUX</label>
    </span>
     <button class="BtnNavBar">Série</button>
     <button class="BtnNavBar">Film</button>
     <button class="BtnNavBar">Nouveauté</button>
     <button class="BtnNavBar">Ma liste</button>
     <button class="BtnNavBar">A Propos</button>
   </div>
   <div class="div">

   </div>
 </div>

</template>

<script>
export default {
  name: "NavBar"
}
</script>

<style scoped>
@font-face {
  font-family: "Bebas Neue";
  src: url("/src/assets/fonts/Bebas_Neue");
}
#NavBar {
  background: black;
  height: 10vh;
  padding: 0;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: 100vw;
}

.logo{
  font-family: "Bebas Neue",sans-serif;
  color: red;
  margin-left: 1em;
  font-size: 30px;
  margin-right: 2em;
}

.BtnNavBar{
  color: white;
  background-color: black;
  margin: 0.5em;
}

.div{
  width: 50vw;
}
</style>