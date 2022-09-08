
<template>
  <div class="hello">
    <div class="menu">
        <div class="menu-logo">
          <div class="menu-text"><img src="../assets/logo.png" alt="wine icon"/>The Wine Guide</div>
        </div>
        <div class="menu-item">
         <div class="menu-text">My Favorites</div> 
        </div> 
      <div class="menu-item">
        <div class="menu-text">My Account</div>
      </div>
      <div class="menu-item">
        <div class="menu-text">Buy Wine</div>
      </div>
    </div>
    </div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.menu {
  display:flex;
  align-items:center;
  justify-content: space-around;
  margin-top:10px;
}

.menu-item {
  flex:1;
  text-align: center;
  font-size: 20px;
}

.menu-text{

color: #818181;
padding:10px;
border: 2px solid #080808;
cursor: pointer;
width: fit-content;
}

.menu-text:hover {
  border-bottom: 2px solid #4d0013;

}

.menu-logo {
  font-size: 1.8rem;
  color: #EAEAEA;
  flex:1;
  justify-content: space-between;
  
}
img{
  width: 1.8rem;
  height: 1.8rem;
  margin-right:1rem;
}

</style>
