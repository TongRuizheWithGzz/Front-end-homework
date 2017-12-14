<template>
  <div class="waterfall row">
    <div class="reviews js-masonry" data-masonry-options='{"itemSelector": ".hreview" }'>
      <div class="col-sm-6 col-md-4">
      <div class="hreview review-item-1 thumbnail">
        <img src="../assets/food1.jpg" alt="Customer Photo1">
        <div class="caption">
          <blockquote class="description"><p>这是一幅食品的图片.</p></blockquote>
          <p class="reviewer">Smiling Customer1</p>
        </div><!-- /.caption -->
      </div><!-- /.hreview -->
      <div class="hreview review-item-2 thumbnail ">
        <img src="../assets/food2.jpg" alt="Customer Photo2">
        <div class="caption">
          <blockquote class="description"><p>这是一幅食品的图片.</p></blockquote>
          <p class="reviewer">Smiling Customers2</p>
        </div><!-- /.caption -->
      </div><!-- /.hreview -->
      <div class="hreview review-item-3 thumbnail ">
        <img src="../assets/food3.jpg" alt="Customer Photo3">
        <div class="caption">
          <blockquote class="description"><p>这是一幅食品的图片.</p></blockquote>
          <p class="reviewer">Smiling Customer3</p>
        </div><!-- /.caption -->
      </div><!-- /.hreview -->
      </div>
      <div class="col-sm-6 col-md-4">
      <div class="hreview review-item-4 thumbnail ">
        <img src="../assets/food4.jpg" alt="Customer Photo4">
        <div class="caption">
          <blockquote class="description"><p>这是一幅食品的图片.</p></blockquote>
          <p class="reviewer">Smiling Customer4</p>
        </div><!-- /.caption -->
      </div><!-- /.hreview -->
      <div class="hreview review-item-5 thumbnail ">
        <img src="../assets/food5.jpg" alt="Customer Photo5">
        <div class="caption">
          <blockquote class="description"><p>这是一幅食品的图片.</p></blockquote>
          <p class="reviewer">Smiling Customer5</p>
        </div><!-- /.caption -->
      </div><!-- /.hreview -->
      <div class="hreview review-item-6 thumbnail ">
        <img src="../assets/food6.jpg" alt="Customer Photo6">
        <div class="caption">
          <blockquote class="description"><p>这是一幅食品的图片.</p></blockquote>
          <p class="reviewer">Smiling Customer6</p>
        </div><!-- /.caption -->
      </div><!-- /.hreview -->
      </div>
      <div class="col-sm-6 col-md-4">
      <div class="hreview review-item-7 thumbnail ">
        <img src="../assets/food7.jpg" alt="Customer Photo7">
        <div class="caption">
          <blockquote class="description"><p>这是一幅食品的图片.</p></blockquote>
          <p class="reviewer">Smiling Customer7</p>
        </div><!-- /.caption -->
      </div><!-- /.hreview -->
      </div>
    </div><!-- /.reviews -->
  </div>
</template>

<script >
export default {
  name: 'waterfall',
  data () {
      return {
        images:[
          {
            src:"static/img/1.jpg",
            href:""
          },
          {
            src:"static/img/6.jpg",
            href:""
          },
          {
            src:"static/img/7.jpg",
            href:""
          },
          {
            src:"static/img/1.jpg",
            href:""
          },,
          {
            src:"static/img/6.jpg",
            href:""
          },,
          {
            src:"static/img/7.jpg",
            href:""
          },
          {
            src:"static/img/1.jpg",
            href:""
          }
        ],
      }
    }
}

</script>

<style >
.waterfall .reviews.hreview {
    position: relative;
    padding: 0 10px;
    border: none;
  }
.waterfall .reviews.hreview .caption {
    position: absolute;
    top: auto;
    left: 10px;
    right: 10px;
    bottom: 0;
    line-height: 1.1;
    background: hsla(0,0,10%,0.55);
}
.waterfall .reviews.hreview blockquote,.reviewer {
      margin: 0 6px;
      padding: 0;
}
.waterfall .reviews.hreview blockquote {
      margin-top: 4px;
      border: none;
      font-family: @font-family-serif;
      font-size: @font-size-large;
      color: #fff;
}
.waterfall .reviews.hreview .reviewer {
      margin-top: 2px;
      margin-bottom: 4px;
      text-align: right;
      color: @gray-lighter;
}


</style>


