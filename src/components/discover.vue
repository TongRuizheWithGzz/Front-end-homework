<template>
  <div id="discover" class="container">
    <waterfall />
    <div class="container text-center">
      <div class="row pagination-wrap">
        <ul class="pagination">
          <li><a href="#"><span class="fa fa-chevron-left"></span> Prev</a></li>
          <li><a href="#">1</a></li>
          <li><a href="#">2</a></li>
          <li><a href="#">3</a></li>
          <li><a href="#">4</a></li>
          <li><a href="#">Next <span class="fa fa-chevron-right"></span></a></li>
        </ul>
      </div><!-- /.row.pagination-wrap -->
    </div>
  </div>
</template>

<script >
import waterfall from './waterfall.vue'
export default {
  name: 'discover',
  components:{
    waterfall
  }
}
</script>