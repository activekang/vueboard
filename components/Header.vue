<template>

  <div class="header-info">
    <b-navbar toggleable="lg" type="light">
      <b-navbar-brand to="/">BkSite</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item to="/">자유게시판</b-nav-item>
          <b-nav-item to="/Login">로그인</b-nav-item>
          <b-nav-item to="/gallery">갤러리</b-nav-item>
          <b-nav-item to="/boardlist">VUE리스트</b-nav-item>
          <b-nav-item to="/card">Card이미지</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {

    }
  }
};
</script>
<style scoped>
.header-info {
  margin-top:10px;
  width:100%;
  height:auto;
 
  background:rgb(238, 186, 16);
  color:white;
}   
</style>
