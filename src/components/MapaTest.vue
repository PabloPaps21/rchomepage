<template>
  <div class="gmap_canvas"><iframe width="300" height="170" id="gmap_canvas" src="https://maps.google.com/maps?q=Benito%20Ju%C3%A1rez%2C%20Col.%20del%20Valle%2C%2003100%20CDMX%2C%20M%C3%A9xico&t=&z=13&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"></iframe>Google Maps Generator by <a href="https://www.embedgooglemap.net">embedgooglemap.net</a></div>
</template>
<script>
/* global google */
// eslint-disable-next-line no-unused-vars
let map;
// eslint-disable-next-line no-unused-vars
function initMap() {
  map = new google.maps.Map(document.getElementById('map'), {
    center: { lat: -99.159091, lng: 19.379869 },
    zoom: 8,
  });
}
</script>

<style>
  /* Always set the map height explicitly to define the size of the div
    * element that contains the map. */
  #map {
    height: 100%;
  }
  /* Optional: Makes the sample page fill the window. */
</style>
