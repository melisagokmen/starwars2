<template>
<div>
    <router-view></router-view>

    <div class="all">
      <div class="lefter">
        <div class="lefter-image">
        <router-link to="/people"> <img src="https://image.flaticon.com/icons/svg/86/86483.svg"style=" margin-left:3px"height="150px" width="200px"/></router-link>
      </div>
      </div>
      <div class="left">
        <div class="left-image">
          <router-link to="/planets"  > <img src="https://image.flaticon.com/icons/png/512/1146/1146347.png"style=" margin-left:25px"height="150px" width="155px"/></router-link>
      </div>
      </div>
       <div class="center">
        <div class="explainer">
          <span>STAR WARS</span>
        
        <div class="explainer-image">
         
           <router-link to="/films" style="margin-top:200px"> <img src="https://image.flaticon.com/icons/svg/206/206950.svg"style=" margin-left:3px"height="150px" width="200px"/></router-link>
        </div>
        </div>
      </div>
      <div class="right">
        <div class="right-image">
          <router-link to="/species"> <img src="https://image.flaticon.com/icons/png/512/993/993673.png"style=" margin-left:30px"height="150px" width="140px"/></router-link>
     
        </div>
      </div>
      <div class="righter">
        <div class="righter-image">
         <router-link to="/vehicles"> <img src="https://image.flaticon.com/icons/svg/1946/1946010.svg"style=" margin-left:3px"height="150px" width="200px"/></router-link>
        </div>
      </div>
      <div class="order">
        <div class="order-image">
          <router-link to="/starships"> <img src="https://image.flaticon.com/icons/svg/115/115751.svg"style=" margin-left:3px"height="150px" width="200px"/></router-link>
        
        </div>
      </div>
    </div>
  </div>
  

</template>


<script>
export default {
  components: {},
  name: "player",
  data() {
    return {};
  }
};
</script>
