<template>
  <div class="header_icon">
    <div style="float: left">
      <el-button  type="info" @click="test()">测试</el-button>
    </div>
      <div style="float: right">
        <img id="service" src="../imag/service.png" style="" width="40" height="40" alt=""/>
        <img id="disk" src="../imag/disk.png" width="40" height="40" alt=""/>
        <img id="server" src="../imag/server.png" width="40" height="40" alt=""/>
        <img id= "net" src="../imag/net.png" width="40" height="40" alt=""/>
        <img id="soft" src="../imag/soft.png" width="40" height="40" alt=""/>
      </div>

  </div>
</template>


<script>
export default {
  name: "header_icon",
  methods:{
    test()
    {
      alert("hello");
    }
  }
}

</script>

test()
{
  alert("hello");
}

<style scoped>

</style>