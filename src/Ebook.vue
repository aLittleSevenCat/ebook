<template>
 <div>
     aaa
 </div>
</template>

<script>
import Epub from 'epubjs'
const DOWLOAD_URL = '/static/2018_Book_AgileProcessesInSoftwareEngine'
export default {
  methods: {
    showEpub () {
      this.book = new Epub(DOWLOAD_URL)
      console.log(this.book)
    }
  },
  mounted () {

  }
}
</script>

<style lang='scss' scoped>

</style>
