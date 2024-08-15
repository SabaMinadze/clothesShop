<template>
    <div>
        <div class="box">
            <ul>
                <li><p>კურსები</p></li>
                <li><p>რეზიუმეები</p></li>
                <li><p>ქვიზები</p></li>
                <li><p>გამოწვევები</p></li>
                <li><p>ბლოგი</p></li>
                <li><p>კონვერტორები</p></li>
                <li><p class="txt">შესვლა</p></li>
            </ul>

        </div>
        
    </div>
</template>


<script>
</script>

<style scoped>
.box{
    height: 50px;
    width: 100%;
    background-color: rgb(0, 0, 0);
    color: rgb(108,34,166);
}

ul{
    display: flex;
    list-style: none;
    color: rgb(255, 255, 255);
    gap: 30px;
    font-size: 20px;
    font-weight: 700;
    margin-left: 100px;
}

p{
    font-weight: 800;
    margin-top: 5px;
    cursor: pointer;
}

.txt{
    margin-left: 150px;
}
</style>