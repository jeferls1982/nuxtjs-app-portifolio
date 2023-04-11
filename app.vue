
<template class="all">
  <div class="page">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">

    <HeaderComponent class="header" />
    <MainBodyComponent class="main" />
    <FooterComponent class="footer" />


  </div>
</template>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe" crossorigin="anonymous"></script>

<script>
import HeaderComponent from './components/header/HeaderComponent.vue'
import MainBodyComponent from './components/main/BodyComponent.vue'
import FooterComponent from './components/footer/FooterComponent.vue'
</script>

<style scoped>
.all{
  margin: 0;
  padding: 0;
  border: 0;
}

.page{
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between ;

}
.header{
  /* background-color: purple; */
}
.main{
  background-color: yellow;
  height: 100%;
}

.footer{
  background-color: green;
}

</style>