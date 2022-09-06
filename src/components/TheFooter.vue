
  
  <script>
    export default {
      name: 'TheFooter',
       data(){
            return{
              name: 'Odeyale Kehinde',
    
            }
       
    }
    }
    </script>
<template>
    <div class="thefooter">
       <span>&copy; copyright 2022. My Resume with Vue Js, created by: {{ name }}</span>
      
      
    </div>
  </template>

  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
  
  span {
     
    font-family: Verdana, Geneva, Tahoma, sans-serif;
  color: cadetblue;
    margin-top: 5rem;
    margin-left: 1rem;     
    text-align: center;   

  }
  </style>
  