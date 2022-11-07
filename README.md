<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Test web</title>
        <style>
            * {
                padding: 0;
                margin: 0;
                font-family: cursive;
            }
            body {

                height: fit-content;
                width: 100%;
                background-color: #56001B;
                color: #FFB4ED;
                z-index: 0;
            }
            .pic {
                background-attachment: fixed;
                background-image: url("https://media.tenor.com/3ECC7iA1hqsAAAAd/power-chainsaw-man.gif");
                opacity: 0.7;
                width: 100%;
                height: 800px;
                background-size: 100%;
                background-repeat: no-repeat;
                clip-path: circle(200vh at 50% -100vh);
            }
            .say {
                color:#F05895;
                text-align: center;
                margin-left:20%;
                top: 400px;
                font-size: larger;
                z-index: 99;
                font-size: 40px;
                position: absolute;
                transition: 2s;
                animation: sayAnimate  2.5s ease-in infinite;
                transform: translateX(0%);
            }
            @keyframes sayAnimate {
                0% {
                    transform: translateX(-300%);
                }
                50% {
                    transform: translateX(0%);
                }
                100% {
                    transform: translateX(0%);
                }
            }

            .nav {
                background-color: #000000;
                display: flex;
                position: fixed;
                z-index: 9999;
                width: 100%;
            }
            hr {
                opacity: 0;
            }
            #OneS {
                margin-bottom: 200px;

            }
            #twoS {
                margin-bottom: 200px;
            }
            h2 {
                text-shadow: 0 0 1px #F05895;
                width: 300px;
                font-size: 30px;
                color: #F05895;
                position: fixed;
               margin:10px;
            }
            .logo {
                width: 200px;
                margin-left: 150px;
            }
            .nav-btn{
                width: 100%;
                margin: auto;
                margin-left: 400px;
            }
            .nav-btn > a {
                margin: 10px;
            }
            
           
            .container {
                width: 100%;
                height: 100vh;
                font-size: 20px;
                display: flex;
                margin: 10px auto auto;
            }
            h3 {
                margin: 10px;
                text-align: center;
            }
            #text {
                text-align: justify;
                color: #FFF4FA;
                width: 500px;
                overflow: hidden;
                margin: 50px 50px 50px 200px;
                transition: 2s;
            }
            #powerpic {
                width: 500px;
                height: fit-content;
                margin: 50px;
                border-radius: 10%;
                box-shadow: 0 0 20px black;
                transition: 2s;

            }
            #powerpic:hover {
                transform: rotateY(-20deg);
            }
            .animate {
                margin-top: 10px;
                color: #000000;
                animation: animate 3s ease-in-out;
            }
            @keyframes animate {
                0% {
                    transform: translateX(-200%);
                }
                50% {
                    transform: translateX(10%);

                }
                100% {
                    transform: translateX(0%);
                }
            }
            .animatePic {
                width: 30px;
                animation: animatePic 1.5s ease-in-out !important;
            }
            @keyframes animatePic {
                0% {

                    transform: rotateX(10deg) rotateY(160deg);
                }
                50% {

                    transform: rotateX(30deg) rotateY(160deg);
                }
                100% {
                    transform: translateX(0%);

                }
            }
            .twoS {
                display: flex;
                margin: auto;
                padding-top: 200px;
                overflow: hidden;
                padding: 10px;
            }

            #pictwo {
                width: 350px;
                margin: auto 20px auto auto;
                border-radius: 10%;
                box-shadow: 0 0 15px black;
                transition: 2s;
                height: fit-content;
                transform: translateY(10%);

            }
            #pictwo:hover {
                transform: translateY(0%);
                transition: 1s;

            }
            .animatepicTwo {
                animation: pictwo 1.5s !important;

            }
            @keyframes pictwo {
                0% {
                    transform: translateY(90%);
                    border-radius: 100%;
                    opacity: 1;
                }
                50% {
                    transform: translateY(50%);

                }
                100% {
                    border-radius: 10%;
                    opacity: 1;
                    transform: translateY(10%);
                }
            }
            #text-two {
                color: #FFF4FA;
                width: 500px;
                font-size: 20px;
                height: 350px;
                margin: auto auto auto 0;
                transition: 2s ease-in-out;
                box-shadow: 0 0 20px rgb(52, 50, 50);
                padding: 10px;
                border-radius: 5px;
                overflow: hidden;
            }
            #text-two:hover {
                cursor: pointer;
            }
            .animatetwo {
                animation: animatetwo 2s;
            }
            @keyframes animatetwo {
                0% {
                    transform: translate(200%);

                }
                50% {
                    transform: translate(10%);
                    margin-left: 0;

                }
                100% {
                    transform: translate(0%);
                }

            }
            p {
                padding: 10px;
            }
            a {
                color: #FFF4FA;
                background-color: #8b053a;
                text-decoration: none;
                border-radius: 20px;
                padding: 5px 30px;
                transition: 0.5s;
            }
            a:hover {
                background-color: #F05895;
                color: #000000;
                box-shadow: 0 0 5px #FFF4FA;
            }
            #AllPic {
                width: 100%;
                height: auto;
                margin-top: 150px;
                padding-bottom: 200px;
            }
            .AllPhoto {
                margin-top: 100px;
                width: 100%;

                height: auto;
                display: grid;
                grid-template-columns: repeat(auto-fit,minmax(300px,1fr));
            }
            .photo {
                width: 300px;
                height: 300px;
                border-radius: 10px;
                margin: 10px;
                overflow: hidden;
            }

            .photo > img {
                border-radius: 10px;
                width: 300px;
                height: 300px;
                opacity: 0.85;

            }
            .powerpics {
                animation: powerpic 1.5s ease-in-out;
            }
            @keyframes powerpic {
                0% {
                    opacity: 0;
                }
                100% {
                    opacity: 0.8;
                }

            }
            .photo > img:hover {
                opacity: 2;
                transition: 3s;
                transform: scale(1.3);
            }
            h1 {
                text-align: center;
                color: #FFF4FA;
            }

            .threeS {
                width: 100%;
                height: 100vh;
                margin: 300px auto auto;
            }
            @media screen and (max-width : 400px) {

                body {
                    background-color: #010101;
                }
                .pic {
                    height: 200px;
                    background-position: center;
                    clip-path: circle(200px at 50% -100px);
                }
                h2 {
                    text-align: center;
                    width: 100%;

                }
                .container {
                    height: 100px;
                    display: block;
                    margin-top: 100px;

                }
                #text {
                    font-size: 15px;
                    width: 300px;
                    height: 350px;
                    margin: auto;
                    transition: 2s;
                }
                #powerpic {
                    display: block;
                    width: 300px;
                    height: 200px;
                    margin: 50px auto auto;
                    box-shadow: 0 0 15px rgb(143, 139, 139);
                }
                .twoS {
                    display: block;
                    width: fit-content;
                    margin: 550px auto auto;
                }
                #pictwo {
                    margin: auto auto 50px;
                    display: block;
                    width: 200px;
                    box-shadow: 0 0 15px rgb(96, 87, 87);
                    height: 300px;
                }
                .animate {
                    margin-top: 10px;
                    color: #fffdfd;
                    animation: animate 3s ease-in-out;
                }
                #text-two {
                    color: #ffffff;
                    width: 250px;
                    font-size: 15px;
                    height: 400px;
                    margin: auto;
                    box-shadow: 0 0 10px rgb(87, 80, 80);
                }
                .AllPic {
                    width: 100%;
                    height: auto;
                    margin-top: 150px;
                    padding-bottom: 200px;
                }
                .AllPhoto {
                    margin-top: 100px;
                    width: 100%;
                    height: auto;
                    display: flex;
                    flex-direction: column;
                    margin: auto;

                }
                .photo {
                    width: 300px!important;
                    height: 300px !important;
                    border-radius: 10px;
                    margin: 10px auto auto;
                    overflow: hidden;
                    background-position: center;
                }

                .photo > img {
                    border-radius: 10px;
                    width: 300px !important;
                    height: fit-content !important;
                    background-position: center;
                    opacity: 0.8;

                }

            }
        </style>
    </head>
    <body>
        <div class="nav">
            <h2>
                The Blood Fiend (Power)</h2>
            <img
                class="logo"
                src="https://preview.redd.it/sxpisaayqjc71.png?width=3840&format=png&auto=webp&s=81745fac2767fce6a347f314374a1bcb1076140a"
                alt="">
            <div class="nav-btn">
                <a href="#">Home</a>
                <a href="#OneS">Intro</a>
                <a href="#twoS">About</a>
                <a href="#threeS">Photo Collection</a>
            </div>
        </div>
        
        <div class="pic">
           
        </div>
        <h1 class="say">"Grovel, human! My name is Power!" Power </h1>
        <hr id="OneS">
        <div class="container" >
           
            <div id="text">
                <h3>Intro about Power</h3>
                <p>
                    Power is a Blood Fiend and a Public Safety Demon Hunter, who is part of Makima’s
                    special squad. Power is one of the main female characters in the whole franchise
                    and her importance in the first part of Chainsaw Man is undeniable.Power is
                    childish, greedy, and almost entirely self-motivated.</p>
                <a href="#pictwo">See More</a>
            </div>
            
            <div id="infopic">
                <img
                    id="powerpic"
                    src="https://i.pinimg.com/originals/1f/38/c5/1f38c5f7ac42fd2aee6cba8878dd47ff.jpg"
                    alt="">
            </div>

        </div>
        <hr id="twoS">
        <div class="twoS">
            <img
                id="pictwo"
                src="https://external-preview.redd.it/dRIjfThDkOHqQon5TCfQ_ci_Cy0iA325jYeA0i38CPo.jpg?auto=webp&s=3ed42ff5e1914aec90b1f611373684162672535d"
                alt="">
            <div id="text-two">
                <h3>About Power...</h3>
                <p>
                    Power is childish, greedy, and almost entirely self-motivated. She tends to
                    fight as if she has something to gain and is certain of her victory, and has no
                    problems with running away from a fight where she is outmatched. She feels the
                    need to boast her superiority over her fellow Devil Hunters due to her status as
                    a fiend. She has no loyalty to humans or devils, openly admitting th…</p>
                <a href="#">See More</a>
            </div>
        </div>
        <hr id="threeS">
        <div id="AllPic">
            <h1>Power PHOTO Collection</h3>
            <div class="AllPhoto">
                <div class="photo one" style="grid-row:span 1 ;height: 620px;"><img
                    style="height: 620px;"
                    src="https://cdnb.artstation.com/p/assets/images/images/039/541/761/large/mirco-cabbia-sciamano240-power-cm-1-3.jpg?1626204723"
                    alt="">
                </div>
                <div class="photo two" style="grid-column:span 2 ;width: 600px;height: 620px;">
                    <img
                        style="width: 600px;height: 620px;"
                        src="https://wegotthiscovered.com/wp-content/uploads/2022/10/power-chainsaw-man2-1.jpg"
                        alt="">
                </div>
                <div class="photo three" style="height: 620px;">
                    <img
                        style="height: 620px;"
                        src="https://wallpapercave.com/wp/wp8650189.png"
                        alt="">
                </div>
                <div class="photo four" style="height: 620px;">
                    <img
                        style="height: 100%;"
                        src="https://wallpapercave.com/uwp/uwp1691911.png"
                        alt="">
                </div>
                <div
                    class="photo five"
                    style="grid-column:span 2;grid-row:span 2;height: 920px;width:600px;">

                    <img
                        style="height: 920px;width:600px;"
                        src="https://a-static.besthdwallpaper.com/chainsaw-man-power-wallpaper-2560x1920-79290_27.jpg"
                        alt="">
                </div>
                <div class="photo six" style="width: 300px;">
                    <img
                        style="width: 300px;"
                        src="https://wallpapers.com/images/hd/minimalist-chainsaw-man-power-s8l89yfok28o8b50.jpg"
                        alt="">
                </div>
                <div class="photo seven" style="grid-column: span 2;width: 600px;">
                    <img
                        style="width: 600px;"
                        src="https://animecorner.me/wp-content/uploads/2022/11/chainsaw-man-power-figure.png"
                        alt="">
                </div>
                <div class="photo eight" style="height: 600px;">
                    <img
                        style="height: 600px;"
                        src="https://cdna.artstation.com/p/assets/images/images/038/133/616/large/isaac-liew-cheesewoo-power1200.jpg?1622260546"
                        alt="">
                </div>
                <div class="photo nine" style="grid-column:span 1 ;width:600px ;height:600px;">
                    <img
                        style="width:600px ;height:600px;"
                        src="https://wallpaperaccess.com/full/6299598.png"
                        alt="">
                </div>
                <div class="photo ten" style="grid-column: span 2;width: 600px;">
                    <img
                        style="width: 600px;"
                        src="https://w0.peakpx.com/wallpaper/203/1/HD-wallpaper-anime-chainsaw-man-kobeni-higashiyama-power-chainsaw-man.jpg"
                        alt="">
                </div>
                <div class="photo eleven" style="width: 300px;">
                    <img
                        style="width: 300px;"
                        src="https://a-static.besthdwallpaper.com/chainsaw-man-power-wallpaper-2560x2048-79288_33.jpg"
                        alt="">
                </div>
                <div class="photo twelve" style="width: 300x;">
                    <img
                        style="width: 300x;"
                        src="https://a-static.besthdwallpaper.com/chainsaw-man-power-blood-devil-4k-wallpaper-2560x1600-79283_7.jpg"
                        alt="">
                </div>
                <div class="photo twelve" style="width: 300x;">
                    <img
                        style="width: 300x;"
                        src="https://images4.alphacoders.com/128/1281669.jpg"
                        alt="">
                </div>

            </div>
            <div class="threeS">

                <h4>Continue ...</h4>
            </div>
        </div>

        <script>
            const text = document.getElementById('text');
            const powerpic = document.getElementById('powerpic');
            const textTwo = document.getElementById('text-two');
            const pictwo = document.getElementById('pictwo');
            const photos = document.querySelectorAll('img');

            window.addEventListener('scroll', animate);
            //* clip-path: circle(180vh at 100% -50vh); */

            function animate() {
                const timimg = window.innerHeight;
                const userview = text
                    .getBoundingClientRect()
                    .top;
                const userviewTwo = textTwo
                    .getBoundingClientRect()
                    .top;

                if (userview < timimg) {
                    text
                        .classList
                        .add('animate');
                    powerpic
                        .classList
                        .add('animatePic');

                } else {
                    text
                        .classList
                        .remove('animate');
                    powerpic
                        .classList
                        .remove('animatePic');
                }

                if (userviewTwo < timimg) {
                    textTwo
                        .classList
                        .add('animatetwo');
                    pictwo
                        .classList
                        .add('animatepicTwo')
                } else {
                    textTwo
                        .classList
                        .remove('animatetwo');
                    pictwo
                        .classList
                        .remove('animatepicTwo')
                }
                photos.forEach(photos => {
                    const userviewpics = photos
                        .getBoundingClientRect()
                        .top;
                    if (userviewpics < timimg) {
                        photos
                            .classList
                            .add('powerpics');
                    } else {
                        photos
                            .classList
                            .remove('powerpics');
                    }

                })

            }
        </script>

    </body>
</html>
