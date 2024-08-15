<script>
import product from './product.vue';
import data from '../data.json'



export default {
  name: 'App',
  components: {
    product,
  },
  data() {
    return {
        data1: data,
    }
  }
};
</script>



<template>
    <div class="box">
        <div class="productsBox">
          <product v-for="(item, index) in data1" :key="index" :nivti="item" class="product1"/>
        </div>
    </div>
</template>



<style scoped>
.productsBox{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
} 


.product1 {
  flex: 0 0 calc(33.33% - 10px); /* 33.33% width minus spacing */
  margin-top: 20px;
}

</style>