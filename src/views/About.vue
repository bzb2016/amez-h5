<template>
  <div class="page" key="about">
    <Pagination @currPage="goPage" :currPage="cpage" :totalPages="totalPages"></Pagination>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  data () {
    return {
      cpage: 15,
      totalPages: 20
    }
  },
  created () {

  },
  components: {

  },
  mounted () {

  },
  methods: {
    goPage (page) {
      console.log(page)
    }
  }
}
</script>

<style scoped lang="scss">

</style>

