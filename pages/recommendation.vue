<template>
  <div>
    <navTop></navTop>
  </div>
  
</template>

<script>
import navTop from '../../components/navtops'
export default {
  components: {
    navTop, musicnav,
     myfooter:footer,
  },
   data() {
        return {
            music: [
                {
                    path: '/music/hot',
                    title: '热门推荐'
                },
                {
                    path: '/music/top',
                    title: "榜单"
                },
                {
                    path: '/music/list',
                    title: "歌单",
                },
                {
                    path: '/music/radio',
                    title: '电台'
                }
            ],
            

        }
    }

}
</script>

<style lang="scss">

</style>