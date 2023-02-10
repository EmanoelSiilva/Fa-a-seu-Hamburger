<template>
  <div>
    <Banner />
    <div class="main-container">
      <h1>Monte o seu burger:</h1>
      <BurgerForm/>
    </div>
  </div>
</template>

<script>
import BurgerForm from '../components/BurgerForm';
import Banner from '../components/Banner'

export default {
  name: 'Home',
  components: {
    Banner,
    BurgerForm
}
}
</script>