<template>
    <div>
    <b-container>
      <b-row>
       <b-col cols="12">
         <b-jumbotron header="Vue Login" lead="Bootstrap v4 Components for Vue.js 2">
            <p>For more information visit website</p>
    
              <b-col sm="12">
               <b-form-input  id="input-default" placeholder="아이디입력"></b-form-input>
              </b-col>           
              
              <b-col sm="12">
                <b-form-input id="input-default" type="password" placeholder="비밀번호입력"></b-form-input>
              </b-col>
          
                <b-button variant="primary" href="#" >LOGIN</b-button>
         </b-jumbotron>         
        </b-col>   
      </b-row>
    </b-container>
   </div>
</template>
<script>
export default {
  nama: "Login",
  data() {
        return {
        
      }
   
    }
    
  }  
</script>