<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" />
    <title>ZiLin</title>
    <link rel="stylesheet" href="./fontawesome/css/all.css">
    <link href="./Cup.ico" rel="SHORTCUT ICON" />

</head>
<style>
    *{
        margin: 0;
        padding: 0;
    }
    body{
        max-width:fit-content;
        margin: 0 auto;
    }
    #app{
        width: 720px;
        padding-left:36px;
        padding-right:36px;
        /* background-color:rgb(139, 145, 143) */
        margin-bottom: 21.6px;
    }
    .imgDiv{
        position: relative;
        width: 648px;
        height: 104.4px;
        margin: 0 auto;
        padding: 54px 0 0;
        /* background-color: antiquewhite; */
        
    }
    .img1{
        width: 60px;
        height: 40px;
        position: absolute;
        left: 50%;
        top: 50%;
        margin: -30px 0 0 -20px;
    }
    

    .huChen{
        width: 648px;
        height: 236px;
        /* background-color: aquamarine; */
        /* margin: 0 auto; */
    }
    .name{
        width: 648px;
        height: 43.2px;
        font-size: 42px;

        color: rgb(54, 53, 53);
        /* background-color:aquamarine; */
        margin-bottom: 18px ;
        font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        margin-top: 10px;
        letter-spacing: 6px;
    }
    .text1{
        margin-top: 9px;
        font: 22px/2 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        text-align: left;
        letter-spacing: 2px;
    }
    .project{
        letter-spacing: 2px;
        margin-top:51px ;
        margin-bottom: 17px;
        color: rgb(105, 152, 201);
        font-size: 32px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif; ;
    }
    .recent{
        margin-left: 30px;
        /* background-color: antiquewhite; */
        font: 22px/2 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
        text-align: left;
    }
    a,p{
        display: inline;
    }
    a{
        font-weight:bolder;
        color: rgb(31, 31, 31);
        text-decoration: none;
        border-bottom: 4px solid rgb(224, 214, 235);
    }
    a:hover{
        background-color: rgb(224, 214, 235);
    }
    .text2,.last{
        letter-spacing: 2px;
        line-height: 50px;
        margin-bottom: 9px;
    }
    hr{
        font-weight:bolder;
        color: rgb(31, 31, 31);
        /* text-decoration: none; */
        /* border-bottom: 4px solid rgb(224, 214, 235); */
        border: none;
        height: 4px;
        color: #F5F3F7 ;
        margin: 68px 0 34px;
        background-color: rgb(245, 243, 247);
    }
    .last{
        margin-bottom: 200px;
        font-size: 22px;
        letter-spacing: 2px;

    }
  
</style>
<body>
    <div id="app">
        <!-- Part of logo -->
        <div class="imgDiv">
            <img class="img1" src="./Cup.svg" alt="logo">
        </div>

        <!--self-introduction  -->
        <div class="huChen">
            <h1 class="name">Hi,I'm ZiLin</h1>
            <div class="text1">
                I live in Foshan, Guangdong Province. I am a software engineering student. I write code in Vue, CSS, HTML. My hobby is to read some literary works and some ancient poems.
            </div>
        </div>

            <h1 class="project">Recent Project</h1>
            <ul class="recent">
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">Gitee</a>
                    <p class="ftext"> - I'll post some practical projects</p>
                </li>
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">About this site</a>
                    <p class="mine"> - Why did I create this site</p>
                </li>
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">About this site</a>
                    <p class="mine"> - I live in Foshan, Guangdong Province. I am a software engineering student. I write code in Vue, CSS, HTML.</p>
                </li>
            </ul>

            <h1 class="project">Recent Project</h1>
            <ul class="recent">
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">Gitee</a>
                    <p class="ftext"> - I'll post some practical projects</p>
                </li>
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">About this site</a>
                    <p class="mine"> - Why did I create this site</p>
                </li>
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">About this site</a>
                    <p class="mine"> - I live in Foshan, Guangdong Province. I am a software engineering student. I write code in Vue, CSS, HTML.</p>
                </li>
            </ul>


            <h1 class="project">Recent Project</h1>
            <ul class="recent">
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">Gitee</a>
                    <p class="ftext"> - I'll post some practical projects</p>
                </li>
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">About this site</a>
                    <p class="mine"> - Why did I create this site</p>
                </li>
                <li class="text2">
                    <a href="https://gitee.com/zhang-lara">About this site</a>
                    <p class="mine"> - I live in Foshan, Guangdong Province. I am a software engineering student. I write code in Vue, CSS, HTML.</p>
                </li>
            </ul>

        <hr>
        <div class="last">
            <a href="https://gitee.com/zhang-lara">Say hi</a>
            <p class="mine"> to zhang-lara</p>
        </div>

    </div>
    <script src="../js/vue.js"></script>
    <script>
        const app = new Vue({
            el: '#app',
            data: {

            },
            methods: {

            }
        })
    </script>
</body>

</html>
