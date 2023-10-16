<template>
  <div>
    <h2>About</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta libero facere, magni molestias sed reprehenderit adipisci temporibus unde ipsam quo aliquam qui cupiditate sequi esse sit nihil aperiam sint praesentium.</p>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatem officia commodi numquam quos similique provident molestias! Velit ullam ex facere! Provident odio cupiditate nostrum maxime necessitatibus fugiat doloremque illum eligendi.</p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
  // const { data } = await useFetch('/api/ninja?name=mario', {
  //   method: 'post',
  //   body: { age: 30 }
  // })
</script>

<style scoped>
  h2 {
    margin-bottom: 20px;
    font-size: 36px;
  }

  p {
    margin: 20px 0;
  }

</style>
