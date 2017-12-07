<template>
  <div class="form-login">
    <!--<md-card-content>-->
    <md-field>
      <label>Username</label>
      <md-input></md-input>
    </md-field>
    <md-field>
      <label>Password</label>
      <md-input v-model="password" type="password"></md-input>
    </md-field>

    <!--</md-card-content>-->
    <!--<md-card-actions>-->
    <md-button>Login</md-button>
    <!--</md-card-actions>-->
  </div>
</template>

<style>
  .form-login{
    width: 400px;
    margin: 0px auto;
  }
</style>

<script>
  // import MdCardContent from "vue-material/src/components/MdCard/MdCardContent/MdCardContent";
  // import MdCardActions from "vue-material/src/components/MdCard/MdCardActions/MdCardActions";

  export default {
    /*components: {
      MdCardActions,
      MdCardContent},*/
    name:"Login",
    data: ()=>({

    })
  }
</script>
