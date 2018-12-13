<template>
    <div class="container" id="second-page">
        <div class= "title-box2">
            <h1 class= "title2">About Me</h1>
        </div>
        <div class= "sky-image">
            <img src="../assets/sky 1.jpg" alt="sky1" class="sky-bg">
        </div>
        <div class= "box-2">
            <h3 class= "font-me">
                <br>First Name : Kawiya </br>
                <br>Family Name : Pholjaroen </br>
                <br>Nick Name : Gai </br>
                <br>Birth Day : 28 / 11 / 1999 </br>
                <br>Gender : Female </br>
                <br>Religion : Thai </br>
                <br>Nationality: Thai </br>
            </h3>
        </div>
        <div>
            <img src="../assets/pic.jpg" alt="pic" class= "pic">
        </div>

    </div>

</template>

<style>
    .container {
        height: 1000px;
    }
    .title-box2{
        width: 500px;
        height: 130px;
        background-color: rgb(249, 186, 0);
        margin-top: 15px;
        margin-left: 450px;
        box-shadow: 13px 12px #888888;
    }
    .title2{
        font-size: 90px;
        color:aliceblue;   
    }
    .sky-image{
        position: absolute;
        width: 100%;
        margin-top: 30px;
    }
    .pic{
        width: 400px;
        z-index: 2;
        position: absolute;
        margin-top: 90px;
        left: 250px;
    }
    .box-2{
        width: 500px;
        height: 550px;
        background-color: rgb(255, 126, 121); 
        position: absolute;
        margin-top: 150px;
        right: 200px;
    }
    .font-me{
        color: aliceblue;
        font-size: 28px;
    }
@media only screen and (max-width: 800px) {
    .container {
        height: 1000px;
    }
    .title-box2{
        display: flex;
        justify-content: center;
        align-items: center;
        width: 300px;
        height: 100px;
        background-color: rgb(249, 186, 0);
        margin-left: 50px;
        box-shadow: 13px 12px #888888;
        margin-top: 250px;
    }
    .title2{
        font-size: 50px;
        color:aliceblue;   
    }
    .sky-image{
        position: absolute;
        /* width: 100%; */
        width: 100px;
        margin-top: 5px;
    }
    .sky-bg {
        width: 90vw;
        display: none;
    }
    .pic{
        width: 200px;
        z-index: 2;
        position: absolute;
        margin-top: 50px;
        left: 25%;
    }
    .box-2{
        width: 300px;
        height: 400px;
        background-color: rgb(255, 126, 121); 
        position: absolute;
        margin-top: 370px;
        right: 10%;
    }
    .font-me{
        color: aliceblue;
        font-size: 16px;
    }
}
</style>
