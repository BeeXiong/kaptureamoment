<template>
    <nav class=" body-container navbar navbar-color fixed-top">
        <img class="navbar-logo" src="../assets/kamLogo-kaptureamoment.png" />
    </nav>
</template>

<script>
export default {

  data () {
    return {

    }
  }
}
</script>

<style lang="scss">
.bg-light
{
  background-color:#f8f9fa!important
}

.navbar-color {
    background-color: white;
}

.body-container {
    width: 100%;
    height:50px;
    padding: 20px 75px
}

.navbar {
  position: relative;
  min-height: 50px;
  margin-bottom: 20px;
  border: 1px solid transparent;
}

.navbar-logo{
    width:200px;
}

.fixed-top{
  position:fixed;
  top:0;
  right:0;
  left:0;
  z-index:1030
}
</style>
