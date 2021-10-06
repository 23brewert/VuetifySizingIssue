<template>
  <div style="text-align:center">
    <h2>Please attempt this via npm run dev and then npm run start (make sure to run npm run build before start) to see issue.</h2>
    <div style="margin-top:30px;color:white;background-color:grey;">
      <p>This div Is only supposed to take up the entire width of the page. (Control)</p>
    </div>
    <div style="margin-top:10px;color:white;background-color:grey;" class="col-9">
      <p>This div Is only supposed to take up 3/4 the width of your page. (Test 1)</p>
    </div>
    <div style="margin-top:10px;color:white;background-color:grey;" class="col-6">
      <p>This div Is only supposed to take up 1/2 the width of your page. (Test 2)</p>
    </div>
    <div style="margin-top:10px;color:white;background-color:grey;" class="col-3">
      <p>This div Is only supposed to take up 1/4 the width of your page. (Test 3)</p>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>