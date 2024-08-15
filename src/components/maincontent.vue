<script>
import products from './products.vue';

export default {
  name: 'App',
  components: {
    products,
  },
};
</script>


<template>
    <div>
        <div class="box">
            <br/>
            <center><h1 class="txt1">ჩვენი ბიჭები</h1></center>
           <div class="mainBox">
                <div class="boxColaidor">
                    <p class="txt2">აირჩიეთ თქვენი სასურველი მამაკაცი</p>
                    <br/>
                    <center><input type="text" name="name" class="name" placeholder="search shop name"></center>
                    <br/>
                </div>
                <products/>   
            </div>
        </div>
    </div>
</template>



<style scoped>
.name{
    height: 35px;
    width: 200px;
    font-size: 20px;
}
.box{
    width: 100%;
    height: 750px;
    
}

.txt1{
    font-weight: 800;
    text-align: center;
    color: white;
}

.txt2{
    font-size: 20px;
    text-align: center;
    color: white;
}

.boxColaidor{
    width: 1200px;
    
}

.mainBox{
    width: 1200px;
    height: 750px;
    margin-left: 192.5px;
}


.btn1{
    margin-top: 17px;
}
</style>