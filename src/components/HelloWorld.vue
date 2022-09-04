<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h2 class="green">{{ msg }}</h2>
    <b><h6> 
      PHP | PYTHON | Laravel | Django | JavaScript | VueJs | ReactJs
     
    </h6></b>
    <h5><strong>
      (234) 80-534 566 34 | odeyale.k@gmail.com | https://github.com/odeyale2016
    </strong>
    </h5>
    <blockquote><h6>Creative and Enthusiastic Backend Developer with 5+ years of practical and hands-on experience in designing and developing digital solutions for start-ups and businesses. Dedicated worker with excellent communication, time management and computer skills. Aiming to leverage my abilities to successfully ﬁll the vacancy at your company. Frequently praised as hardworking by my peers , I can rely upon to help your company achieve its goals</h6></blockquote>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
  color:cadetblue;
}
h5 {
  font-size: 0.8rem;
  color:cornflowerblue;
}
h6 {
  font-size: 0.7rem;
  color:rgb(18, 23, 32);
  text-align: justify;
  text-decoration: wavy;
}
.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
