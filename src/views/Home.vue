<template>
<div class="wrapper">
  <div class="home">
    <h1 class="heading">Heading</h1>
    <p class="lorem">Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro, assumenda veritatis aspernatur dolorum dolore debitis rem saepe itaque! Illo, eum.
    </p>
  </div>
</div>  
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style lang="scss" scoped>
  .wrapper{
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    .home{
      width: 50vw;
      height: 20vh;
    }
  }
       .heading{
        font-size: 2em;
        color: #191919;
        .lorem{
          font-family: Verdana, sans-serif;
          font-size: 1.5em;
        }
      }
</style>
