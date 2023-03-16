<template>
    <div id="setting">
        <iframe name='iframeName' :src=src style="height: 1000px; width: 100%;" frameborder="no"></iframe>
    </div>
</template>
<script>
export default {
name: "index",
  data(){
      return{
      src: "http://1.12.238.58:8666/cp/tzset"
      }
  },
  created() {
  },
  methods:{
  }
}
</script>

<style >
</style>