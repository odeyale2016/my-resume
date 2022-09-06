<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>My Resume</template>
<p class="welcome">
    My name is Odeyale Kehinde Musiliudeen, a fullstack developer, with set skills of PHP Laravel, VueJs, Reactjs and Django.I have developed both the functional and aesthetic components of websites and applications. I believe I can make an immediate impact on your organization with my unique blend of skills and passion. My professional experience includes using programming languages such as HTML, Python and JavaScript to create various web applications. I also have experience in developing and managing SQL and PSQL databases. Combine this with my ability to thrive in a collaborative environment. Here are some highlights of my accomplishments as a Web Developer: Successfully collaborated and efficiently communicated with project stakeholders to bring their vision to digital reality. Earned a Bachelor’s degree in Computer Science from Obafemi Awolowo University, Ile-Ife. Developed databases using SQL/MYSQL proficiency. Wrote code for various website functions using HTML, CSS,
     and JavaScript. Tested and troubleshoot all Web functions to ensure optimal user experience.
    </p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Career Objectives</template>

    <p class="welcome">
      Creative and Enthusiastic Backend Developer with 5+ years of practical 
      and hands-on experience in designing and developing digital solutions 
      for start-ups and businesses. Dedicated worker with excellent communication, 
      time management and computer skills. Aiming to leverage my abilities to successfully ﬁll the vacancy at your company. Frequently praised as hardworking by my peers , I can rely upon to help your company achieve its goals
    </p>
  </WelcomeItem>

 

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>

    <p class="welcome">
    Email: odeyale.k@gmail.com, odeyale_kehinde@yahoo.com <br />
 Phone: +234 80 534 566 34, +234 70 659 320 24 <br />
 Github: https://github.com/odeyale201 <br />
 Linkedin: https://www.linkedin.com/in/odeyale-kehinde-musliudeen <br />
</p>
  </WelcomeItem>

  
</template>
<style>
.welcome{
    text-align: justify;
    color: cadetblue;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 0.6rem;
  }
  img{
    border-radius: 8px;
  }
</style>
