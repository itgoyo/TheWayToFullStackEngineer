<template>
    <div id="tab-bar">

      <slot>
            <tar-bar-item></tar-bar-item>
      </slot>
    </div>
</template>

<script>
    import TarBarItem from '../tabbar/TabBarItem'
  export default {
    name: 'TabBar',
    component:{

    }
  }

</script>

<style scoped>
  #tab-bar {
    background-color: #f6f6f6;
    display: flex;
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    box-shadow: 0 -1px 1px rgb(100, 100, 100, .1);
  }

</style>
