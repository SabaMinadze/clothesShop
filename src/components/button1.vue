<script>
export default {
    props: {
        linkk: {
            required: true,
        }
    }
   
}
</script>

<template>
    <div>
        <a href=""><button>view</button></a>
    </div>
</template>




<style scoped>
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