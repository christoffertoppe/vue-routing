<head>
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
      integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
      crossorigin=""/>

<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
        integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
        crossorigin="">

</script>
    <title>Routing</title>
</head>
<template>
  <div id="app" class="small-container">
   <!-- <h1>Employees</h1>
      <employee-table/> -->
    <h1>Citybikes</h1>
      <Kartta/>
      <Bikes/>
  </div>
</template>

<script>
 // import EmployeeTable from '@/components/Tyontekijataulu.vue'
  import Bikes from '@/components/pyorat.vue'
  import Kartta from '@/components/kartta.vue'

  export default {
    name: 'app',
    components: {
    //  EmployeeTable,
      Bikes,
      Kartta,
    },
  }
</script>

<style>
  h1{
   font-style: italic;
    margin-left: 5px;
  }
  #app {
    margin-left: 5px;
  }
</style>