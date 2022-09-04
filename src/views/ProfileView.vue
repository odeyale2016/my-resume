<template>
    <div class="portfolios">
      <h1>Profile Page of: {{UserId}}</h1>

     
    </div>
  </template>
  <script>
    export default {
      name: 'Profile',
      
      
      data(){
        return {
            UserId : this.$route.params.user_id
          // UserId : ['1', '2', '3', '4', '5', '6', '7']
        }
    },
    methods:{
    updateId(){
      this.UserId = this.$route.params.user_id
    }
    },
    watch:{
      $route : 'updateId'
    }
  }
    </script>


  <style>
  @media (min-width: 1024px) {
    .profile {
      min-height: 100vh;
      display: block;
      align-items: center;
    }
  }
  </style>
  