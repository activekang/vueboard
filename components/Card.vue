<template>
    <div>
  <b-card no-body>
    <b-tabs card>
      <b-tab no-body title="광고이미지 1">
        <b-card-img bottom  :src="require('../static/ad1.jpg')" alt="Image 21"></b-card-img>
        <b-card-footer>Picture 1 footer</b-card-footer>
      </b-tab>

      <b-tab no-body title="광고이미지 2">
        <b-card-img bottom :src="require('../static/ad2.jpg')" alt="Image 25"></b-card-img>
        <b-card-footer>Picture 2 footer</b-card-footer>
      </b-tab>

      <b-tab no-body title="광고이미지 3">
        <b-card-img bottom :src="require('../static/ad3.jpg')" alt="Image 26"></b-card-img>
        <b-card-footer>Picture 3 footer</b-card-footer>
      </b-tab>

    </b-tabs>
  </b-card>
</div>
</template>
<script>
export default {
    
}
</script>