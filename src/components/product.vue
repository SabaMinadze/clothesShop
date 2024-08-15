<!-- eslint-disable vue/no-unused-components -->
<script>
import button1 from './button1.vue'
import data from "../data.json"
export default {
  name: 'App',
  components: {
    button1,
  },
  data (){
        return{
            data1: data,
            
        }
    },
    props: {
        nivti: {
            required: true,
            type: Object,
        }
    }
};
</script>


<template>
    <div class="card">
        <div class="bigBox">
            <center><img :src="nivti.link" alt="error" height="230px" width="300px"></center>
            <center><h1>{{ nivti.shopName }}</h1></center>
            <p>{{ nivti.description }}</p>
                 <h3 class="price">{{ nivti.price }} GEL</h3>
                 <center><a :href="nivti.location"><button>view</button></a></center>
                 <br/><br/><br/><br/><br/><br/>
        </div>   
    </div>
</template>




<style scoped>
.card{
    display: flex;
}


.bigBox{
    width: 350px;
    height: 450px;
    background-color: rgb(255, 255, 255);
    border: 5px solid black;
    margin-right: 50px;
}

.bigBox:hover{
    transition: 0.5s;
    background-color: rgb(177, 30, 145);
}

p{
    margin-left: 10px;
}

h3{
    font-size: 20px;
    margin-left: 10px;
    font-weight: 600;
}

button{
    height: 40px;
    width: 120px;
    background-color: cornflowerblue;
    font-size: 15px;
    border: none;
    font-weight: 900;
    cursor: pointer;
    border-radius: 20px;

}

button:hover{
    height: 40px;
    width: 120px;
    background-color: cornflowerblue;
    font-size: 15px;
    border: none;
    font-weight: 900;
    cursor: pointer;
    border-radius: 20px;

}

.btn:hover{
    transition: 0.5s;
    width: 10px;
    height: 10px;
    width: 20px;
    border: 40px;
    background-color: rgb(177, 30, 145);
}

</style>