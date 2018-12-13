<template>
<div id="third-page">
    <div>
        <h1 class= "font-edu">Education</h1>
        <img src="../assets/sky 2.jpg" alt="sky 2" class="box-edu">
    </div>
    <div class= "infor-edu">
        <img src="../assets/edu.png" alt="edu" class="media-info">
    </div>
</div>
    
</template>

<style>
.font-edu{
    z-index: 5;
    position: absolute;
    left: 400px;
    font-size: 140px;
    color: aliceblue;
    margin-top: 110px;
    text-shadow: 10px 5px rgb(118, 118, 118);
}
.box-edu{
    width: 1000px;
    height: 250px;
    margin-top: 100px;
}
.infor-edu{
    width: 60px;
    height: 40px;
    position: absolute;
    left: 350px;
}
@media only screen and (max-width: 800px) {
    .font-edu{
        z-index: 5;
        position: absolute;
        left: 65px;
        font-size: 60px;
        color: rgb(255, 126, 121);
        margin-top: 110px;
        text-shadow: 5px 5px rgb(118, 118, 118);
    }
    .box-edu{
        width: 1000px;
        height: 250px;
        margin-top: 100px;
        display: none;
    }
    .infor-edu{
        width: 100%;
        height: 40px;
        position: absolute;
        left: 5px;
        margin-top: 250px;
    }
    .media-info{
        width: 100%;

    }
}
</style>
