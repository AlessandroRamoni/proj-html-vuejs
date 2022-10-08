<template>
  <div id="contenitore">
    <div class="mapouter">
      <div class="gmap_canvas">
        <iframe
          width="100%"
          height="300"
          id="gmap_canvas"
          src="https://maps.google.com/maps?q=28041%20Arona&t=&z=13&ie=UTF8&iwloc=&output=embed"
          frameborder="0"
          scrolling="no"
          marginheight="0"
          marginwidth="0"
        ></iframe>
      </div>
    </div>
  </div>
</template>
 
<script>
export default {
  name: "AddGoogleMap",
};
</script>

<style scoped lang="scss">
#contenitore {
  padding-top: 50px;
}

.mapuoter {
  position: relative;
  text-align: right;
  height: 400px;
  width: 100%;
}
.gmap_canvas {
  overflow: hidden;
  background: none !important;
  height: 400px;
  width: 100%;
}
</style>