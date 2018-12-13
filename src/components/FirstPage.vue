<template>
    <div>
        <div class="title-box">
            <h1 class="title">Portfolio</h1>

        </div>
        <a class="folder1-container" href="#" v-scroll-to="'#third-page'">
            <img src="../assets/f.png" alt="folder" class="folder-image" >
            <div class='font-folder'>Education</div>
        </a>
        <a class="folder2-container"  href="#" v-scroll-to="'#second-page'">
            <img src="../assets/f.png" alt="folder" class="folder-image" >
            <div class='font-folder'>About Me</div>
        </a>
        <img src= "../assets/pic 1.png" alt="Me photo" class="gai-image">
        <div>
            <h3 class= "kawiya-font">Kawiya Pholjaroen</h3>
        </div>
        
    </div>
</template>
<style>
.title-box{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 350px;
    height: 150px;
    background-color: rgb(249, 186, 0);
    margin-left: 100px;
    box-shadow: 13px 12px #888888;
}
.title {
    font-size: 90px;
    color: aliceblue;
}
.gai-image {
    width: 800px;
}
.folder-image{
    width: 150px;
}
.folder1-container{
    position: absolute;
    right: 250px;
    top: 90px;
}
.font-folder{
    font-size: 25px;
    margin-top: -20px;
}
.folder2-container{
    position: absolute;
    right: 50px;
    top: 300px;
}
.kawiya-font{
    color:rgb(255, 126, 121);
    font-size: 90px;
    text-shadow: 10px 5px rgb(118, 118, 118);
    margin-left: 500px
}

@media only screen and (max-width: 800px) {
    .title-box{
        width: 250px;
        height: 100px;
        background-color: rgb(249, 186, 0);
        margin-left: 100px;
        box-shadow: 13px 12px #888888;
    }
    .title {
        font-size: 50px;
        color: aliceblue;
    }
    .gai-image {
        margin-top: 50px;
        width: 400px;
    }
    .folder-image{
        width: 50px;
    }
    .folder1-container{
        position: absolute;
        top: 650px;
    }
    .font-folder{
        font-size: 14px;
        margin-top: -5px;
    }
    .folder2-container{
        position: absolute;
        top: 650px;
    }
    .kawiya-font{
        color:rgb(255, 126, 121);
        font-size: 50px;
        text-shadow: 5px 2px rgb(118, 118, 118);
        margin-left: 0px;
        margin-top: 10px;
    }    
}
</style>
