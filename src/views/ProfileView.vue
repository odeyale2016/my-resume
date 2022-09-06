<template>
    <div class="portfolios">
      <h1>Profile Page 1 of  {{UserId}}</h1>
      <h2>My Profile</h2>
    <p>My name is Odeyale Kehinde Musiliudeen, a fullstack developer, with set skills of PHP Laravel, VueJs,  Reactjs and Django.I have developed both the functional and aesthetic components of websites and applications. I believe I can make an immediate impact on your organization with my unique blend of skills and passion. My professional experience includes using programming languages such as HTML, Python and JavaScript to create various web applications. I also have experience in developing and managing SQL and PSQL databases. Combine this with my ability to thrive in a collaborative environment. Here are some highlights of my accomplishments as a Web Developer:
Successfully collaborated and efficiently communicated with project stakeholders to bring their vision to digital reality.
Earned a Bachelor’s degree in Computer Science from Obafemi Awolowo University, Ile-Ife.
Developed databases using SQL/MYSQL proficiency.
Wrote code for various website functions using HTML, CSS, and JavaScript.
Tested and troubleshoot all Web functions to ensure optimal user experience.</p>
     
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
  p{
  width: 100%;
  font-size: 12px;
  text-align: justify;
  margin-top: 1rem;
  margin-left: 1rem;
  margin-right: 2rem;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  color: cadetblue;
  }
  }
  </style>
  