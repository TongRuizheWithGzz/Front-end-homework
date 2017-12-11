<template>
	<nav role="navigation" class="navbar navbar-default navbar-fixed-top">
	    <div class="container">
	      <div class="navbar-header">
	        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
	          <span class="icon-bar"></span>
	          <span class="icon-bar"></span>
	          <span class="icon-bar"></span>
	        </button>
	        <a class="navbar-brand" href="index.html"><em><strong>Discover</strong></em></a>
	      </div>
	      <div class="navbar-collapse collapse">
	        <ul class="nav navbar-nav">
	          <li class="active"><a href="#welcome">Welcome</a></li>
	          <li><a href="#discover">发现</a></li>
	          <li><a href="#share">分享</a></li>
	          <li><a href="#about">关于我们</a></li>
	        </ul>
	      </div><!--/.nav-collapse -->
	    </div><!--/.container -->
     </nav>
</template>

<script>
export default {
  name: 'navbar',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>