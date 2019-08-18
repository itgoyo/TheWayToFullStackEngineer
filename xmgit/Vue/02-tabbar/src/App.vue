<template>

  <div id="app">

    <tab-bar>
      <tab-bar-item>
       <div>首页</div> 
       </tab-bar-item> 

       <tab-bar-item>
       <div>首页</div> 
       </tab-bar-item> 

       <tab-bar-item>
       <div>首页</div> 
       </tab-bar-item> 

       <tab-bar-item>
       <div>首页</div> 
       </tab-bar-item> 
    </tab-bar>
  </div>
  
</template>

<script>

  import TabBar from './components/tabbar/TabBar'
  import TabBarItem from './components/tabbar/TabBarItem'

export default {
  name: 'App'
}
</script>

<style>

 

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

 @import "./assets/css/base.css";




</style>
