<template>
  <div role="tablist">
    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-1 variant="info">Vue 공지사항</b-button>
      </b-card-header>
      <b-collapse id="accordion-1" visible accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>I start opened because <code>visible</code> is <code>true</code></b-card-text>
          <b-card-text>
            <img src='../static/pic1.jpg' alt='pic1'/> 
          <!-- <b-img :src="require('../static/pic1.jpg')" alt='pic1'></b-img> -->
          {{ text }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-2 variant="info">Vue 자료실</b-button>
      </b-card-header>
      <b-collapse id="accordion-2" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>
           <img src='../static/pic2.jpg' alt='pic2'/>
          {{ text2 }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>

    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-3 variant="info">Vue 갤러리</b-button>
      </b-card-header>
      <b-collapse id="accordion-3" accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>
          <img src='../static/pic3.jpg' alt='pic3'/>
          {{ text3 }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>
    <b-card no-body class="mb-1">
      <b-card-header header-tag="header" class="p-1" role="tab">
        <b-button block v-b-toggle.accordion-4 variant="info">Vue 새소식</b-button>
      </b-card-header>
      <b-collapse id="accordion-4" visible accordion="my-accordion" role="tabpanel">
        <b-card-body>
          <b-card-text>I start opened because <code>visible</code> is <code>true</code></b-card-text>
          <b-card-text>
            <img src='../static/pic1.jpg' alt='pic1'/> 
          <!-- <b-img :src="require('../static/pic1.jpg')" alt='pic1'></b-img> -->
          {{ text }}</b-card-text>
        </b-card-body>
      </b-collapse>
    </b-card>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        text: `
          공지사항입니다. 새로운 소식은 공지사항을 참조하세요.
        `,
        text2: `
          VUE관련 소스자료실입니다. 자세한내용은 게시판을 참조하세요. 
        `,
        text3: `
         VUE 부트스트랩의 갤러리기능입니다.
        `,
	text4: `
         VUE 부트스트랩의 갤러리기능2입니다.
        `
      }
    }
  }
</script>