<template>
  <div>
    <header class="site-header jumbotron">
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <h1>请发表对React的评论</h1>
          </div>
        </div>
      </div>
    </header>
    <div class="container">
      <add></add>
      <list></list>
    </div>
  </div>
</template>
<script>
  import add from './add.vue'
  import list from './list.vue'
  export default{
    components:{
      add,
      list
    }
  }
</script>

<style>

</style>