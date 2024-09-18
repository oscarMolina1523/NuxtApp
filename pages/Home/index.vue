<script>
import ToolBar from '~/components/ToolBar.vue'
import HeaderHistory from '~/components/HeaderHistory.vue'
import BodyHome from '~/components/BodyHome.vue'

export default {
  name: 'PageHome',
  components: {
    ToolBar,
    HeaderHistory,
    BodyHome
  }
}
</script>

<template>
    <div class="container">
        <div class="left-panel">
            <ToolBar/>
        </div>
        <div class="right-panel">
            <HeaderHistory/>
            <br>
            <BodyHome/>
        </div>
    </div>
</template>

<style scoped>
.container{
    display: flex;
}
.left-panel{
    flex:1;
}
.right-panel{
    flex:4;
}
</style>
