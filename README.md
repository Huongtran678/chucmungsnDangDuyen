# chucmungsnDangDuyen
<html
    __fvdsurfcanyoninserted="1"
    class="
        clickberry-extension
        clickberry-extension-standalone
        clickberry-extension
        clickberry-extension-standalone
        clickberry-extension
        clickberry-extension-standalone
    "
>

    <head>
        <meta charset="UTF-8" />
        <!-- 0. Phần icon của website (thay đổi link đến icon nếu bạn muốn sửa nó) -->
        <link rel="shortcut icon" type="image/png" href="./birthdayCake.png"/>

        <!-- 1. Đây là phần title của website -->
        <title>Happy Birthday</title>
        <link rel="stylesheet" href="trang1.css">
        <script>
            window.open = function () {};
            window.print = function () {};
            // Support hover state for mobile.
            if (false) {
                window.ontouchstart = function () {};
            }
        </script>
        <script
            type="text/javascript"
            src="chrome-extension://bfbmjmiodbnnpllbbbfblcplfjjepjdn/js/injected.js"
        ></script>
        <meta content="clickberry-extension-here" />
    </head>

    <body>
        <link
            href="https://fonts.googleapis.com/css?family=Wendy+One"
            rel="stylesheet"
            type="text/css"
        />
        <div class="container">
            <!-- 2. Dòng chữ Happy Birthday
            Nếu bạn muốn thêm chữ vào thì phải thay đổi css tương ứng cho nó -->
            <div class="balloon">
                <div><span>H</span></div>
                <div><span>A</span></div>
                <div><span>P</span></div>
                <div><span>P</span></div>
                <div><span>Y</span></div>
                <div><span>B</span></div>
                <div><span>I</span></div>
                <div><span>R</span></div>
                <div><span>T</span></div>
                <div><span>H</span></div>
                <div><span>D</span></div>
                <div><span>A</span></div>
                <div><span>Y</span></div>

            </div>
            <div class="avatar">
                <!-- 3. Avatar của người bạn muốn gởi lời chúc -->
                <img src="./ảnh/z3344104874500_aff68ad82bbc3c69f8c9e2b558cc8743.jpg" alt="" class="avatar__img" onclick="showMessage()" />
                <!-- 4. Tên của người đó -->
                <h1 onclick="showMessage()" class="avatar__title">Đặng Duyên</h1>
            </div>
            
            <!-- 5. Phần nhạc -->
            <audio id="player" autoplay loop>
                <source src="./nhạc/y2meta.com - Khúc Hát Mừng Sinh Nhật [Remix] - Phan Đinh Tùng [Full HD] - DJ.T-Bản Remix™ (128 kbps).mp3" type="audio/mp3">
            </audio>
        </div>
        <script>
            if (document.location.search.match(/type=embed/gi)) {
                window.parent.postMessage("resize", "*");
            }
            function showMessage() {
                
                swal({
title: "Lời chúc",
text: "Chúc mừn sinh nhật!",
type: "success"
}).then(function() {
window.location = "trang2.html";
});
            }
            
        </script>
        <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>
       
    </body>
</html>


@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');

body {
    background-image: -webkit-gradient(
        radial,
        50% 50%,
        0,
        50% 50%,
        100,
        color-stop(0%, #374566),
        color-stop(100%, #010203)
    );
    background-image: -webkit-radial-gradient(#d38da2, #741522);
    background-image: -moz-radial-gradient(#d3b4c6, #580827);
    background-image: -o-radial-gradient(#d1acc5, #942257);
    background-image: radial-gradient(#c59eb1, #ac3164);
    font-family: 'Lobster', cursive;
}
span {
    text-transform: uppercase;
}
.container {
    width: 800px;
    height: 100%;
    padding: 10px;
    margin: 0 auto;
    position: relative;
}
.balloon {
    width: 1000px;
    margin: 0 auto;
    padding-top: 30px;
    position: relative;
    font-family: "Wendy One", sans-serif;
}
.balloon > div {
    width: 104px;
    height: 140px;
    background: rgba(182, 15, 97, 0.9);
    border-radius: 0;
    border-radius: 80% 80% 80% 80%;
    margin: 0 auto;
    position: absolute;
    padding: 10px;
    box-shadow: inset 17px 7px 10px rgba(182, 15, 97, 0.9);
    -webkit-transform-origin: bottom center;
}
.balloon > div:nth-child(1) {
    background: rgba(182, 15, 97, 0.9);
    left: 60px;
    box-shadow: inset 10px 10px 10px rgba(135, 11, 72, 0.9);
    -webkit-animation: balloon1 6s ease-in-out infinite;
    -moz-animation: balloon1 6s ease-in-out infinite;
    -o-animation: balloon1 6s ease-in-out infinite;
    animation: balloon1 6s ease-in-out infinite;
}
.balloon > div:nth-child(1):before {
    color: rgba(182, 15, 97, 0.9);
}
.balloon > div:nth-child(2) {
    background: rgba(242, 112, 45, 0.9);
    left: 180px;
    box-shadow: inset 10px 10px 10px rgba(222, 85, 14, 0.9);
    -webkit-animation: balloon2 6s ease-in-out infinite;
    -moz-animation: balloon2 6s ease-in-out infinite;
    -o-animation: balloon2 6s ease-in-out infinite;
    animation: balloon2 6s ease-in-out infinite;
}
.balloon > div:nth-child(2):before {
    color: rgba(242, 112, 45, 0.9);
}
.balloon > div:nth-child(3) {
    background: rgba(45, 181, 167, 0.9);
    left: 300px;
    box-shadow: inset 10px 10px 10px rgba(35, 140, 129, 0.9);
    -webkit-animation: balloon4 6s ease-in-out infinite;
    -moz-animation: balloon4 6s ease-in-out infinite;
    -o-animation: balloon4 6s ease-in-out infinite;
    animation: balloon4 6s ease-in-out infinite;
}
.balloon > div:nth-child(3):before {
    color: rgba(45, 181, 167, 0.9);
}
.balloon > div:nth-child(4) {
    background: rgba(190, 61, 244, 0.9);
    left: 420px;
    box-shadow: inset 10px 10px 10px rgba(173, 14, 240, 0.9);
    -webkit-animation: balloon1 5s ease-in-out infinite;
    -moz-animation: balloon1 5s ease-in-out infinite;
    -o-animation: balloon1 5s ease-in-out infinite;
    animation: balloon1 5s ease-in-out infinite;
}
.balloon > div:nth-child(4):before {
    color: rgba(190, 61, 244, 0.9);
}
.balloon > div:nth-child(5) {
    background: rgba(180, 224, 67, 0.9);
    left: 540px;
    box-shadow: inset 10px 10px 10px rgba(158, 206, 34, 0.9);
    -webkit-animation: balloon3 5s ease-in-out infinite;
    -moz-animation: balloon3 5s ease-in-out infinite;
    -o-animation: balloon3 5s ease-in-out infinite;
    animation: balloon3 5s ease-in-out infinite;
}
.balloon > div:nth-child(5):before {
    color: rgba(180, 224, 67, 0.9);
}
.balloon > div:nth-child(6) {
    background: rgba(242, 194, 58, 0.9);
    left: -150px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(234, 177, 15, 0.9);
    -webkit-animation: balloon4 3s ease-in-out infinite;
    -moz-animation: balloon4 3s ease-in-out infinite;
    -o-animation: balloon4 3s ease-in-out infinite;
    animation: balloon4 3s ease-in-out infinite;
}
.balloon > div:nth-child(6):before {
    color: rgba(242, 194, 58, 0.9);
}

/* ================= 7 ====================== */
.balloon > div:nth-child(7) {
    background: rgba(45, 181, 167, 0.9);
    left: -30px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(45, 181, 167, 0.9);
    -webkit-animation: balloon3 5s ease-in-out infinite;
    -moz-animation: balloon3 5s ease-in-out infinite;
    -o-animation: balloon3 5s ease-in-out infinite;
    animation: balloon3 5s ease-in-out infinite;
}
.balloon > div:nth-child(7):before {
    color: rgba(45, 181, 167, 0.9);
}

/* ================= 8 ====================== */
.balloon > div:nth-child(8) {
    background: rgba(242, 58, 165, 0.9);
    left: 90px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(242, 58, 165, 0.9);
    -webkit-animation: balloon2 3s ease-in-out infinite;
    -moz-animation: balloon2 3s ease-in-out infinite;
    -o-animation: balloon2 3s ease-in-out infinite;
    animation: balloon2 3s ease-in-out infinite;
}
.balloon > div:nth-child(8):before {
    color: rgba(242, 58, 165, 0.9);
}

/* ================= 9 ====================== */
.balloon > div:nth-child(9) {
    background: rgba(182, 15, 97, 0.9);
    left: 210px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(182, 15, 97, 0.9);
    -webkit-animation: balloon4 5s ease-in-out infinite;
    -moz-animation: balloon4 5s ease-in-out infinite;
    -o-animation: balloon4 5s ease-in-out infinite;
    animation: balloon4 5s ease-in-out infinite;
}
.balloon > div:nth-child(9):before {
    color: rgba(182, 15, 97, 0.9);
}

/* ================= 10 ====================== */
.balloon > div:nth-child(10) {
    background: rgba(242, 194, 58, 0.9);
    left: 330px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(234, 177, 15, 0.9);
    -webkit-animation: balloon1 6s ease-in-out infinite;
    -moz-animation: balloon1 6s ease-in-out infinite;
    -o-animation: balloon1 6s ease-in-out infinite;
    animation: balloon1 6s ease-in-out infinite;
}
.balloon > div:nth-child(10):before {
    color: rgba(242, 194, 58, 0.9);
}

/* ================= 11 ====================== */
.balloon > div:nth-child(11) {
    background: rgba(234, 15, 15, 0.9);
    left: 450px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(234, 15, 15, 0.9);
    -webkit-animation: balloon2 4s ease-in-out infinite;
    -moz-animation: balloon2 4s ease-in-out infinite;
    -o-animation: balloon2 4s ease-in-out infinite;
    animation: balloon2 4s ease-in-out infinite;
}
.balloon > div:nth-child(11):before {
    color: rgba(234, 15, 15, 0.9);
}

/* ================= 12 ====================== */
.balloon > div:nth-child(12) {
    background: rgba(64, 241, 28, 0.9);
    left: 580px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(64, 241, 28, 0.9);
    -webkit-animation: balloon1 3s ease-in-out infinite;
    -moz-animation: balloon1 3s ease-in-out infinite;
    -o-animation: balloon1 3s ease-in-out infinite;
    animation: balloon1 3s ease-in-out infinite;
}
.balloon > div:nth-child(12):before {
    color: rgba(64, 241, 28, 0.9);
}

/* ================= 13 ====================== */
.balloon > div:nth-child(13) {
    background: rgba(15, 219, 234, 0.9);
    left: 700px;
    top: 200px;
    box-shadow: inset 10px 10px 10px rgba(15, 219, 234, 0.9);
    -webkit-animation: balloon2 6s ease-in-out infinite;
    -moz-animation: balloon2 6s ease-in-out infinite;
    -o-animation: balloon2 6s ease-in-out infinite;
    animation: balloon2 6s ease-in-out infinite;
}
.balloon > div:nth-child(13):before {
    color: rgba(15, 219, 234, 0.9);
}

/* Avatar  */
.avatar {
    cursor: pointer;
    position: absolute;
    top: 50%;
    left: calc(50% - 100px);
}

.avatar__img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    border: 5px solid rgba(234, 15, 150, 0.9);
    box-shadow: inset 10px 10px 10px rgba(15, 219, 234, 0.9);
    -webkit-animation: balloon1 6s ease-in-out infinite;
    -moz-animation: balloon1 6s ease-in-out infinite;
    -o-animation: balloon1 6s ease-in-out infinite;
    animation: balloon1 6s ease-in-out infinite;
}

.avatar__title {
    cursor: pointer;
    margin-top: -100px;
    -webkit-animation: balloon1 4s ease-in-out infinite;
    -moz-animation: balloon1 4s ease-in-out infinite;
    -o-animation: balloon1 4s ease-in-out infinite;
    animation: balloon1 4s ease-in-out infinite;
}
.balloon > div:before {
    color: rgba(182, 15, 97, 0.9);
    position: absolute;
    bottom: -11px;
    left: 52px;
    content: "▲";
    font-size: 1em;
}
span {
    font-size: 4.8em;
    color: white;
    position: relative;
    top: 30px;
    left: 50%;
    margin-left: -27px;
}
/*BALLOON 1 4*/
@-webkit-keyframes balloon1 {
    0%,
    100% {
        -webkit-transform: translateY(0) rotate(-6deg);
    }
    50% {
        -webkit-transform: translateY(-20px) rotate(8deg);
    }
}
@-moz-keyframes balloon1 {
    0%,
    100% {
        -moz-transform: translateY(0) rotate(-6deg);
    }
    50% {
        -moz-transform: translateY(-20px) rotate(8deg);
    }
}
@-o-keyframes balloon1 {
    0%,
    100% {
        -o-transform: translateY(0) rotate(-6deg);
    }
    50% {
        -o-transform: translateY(-20px) rotate(8deg);
    }
}
@keyframes balloon1 {
    0%,
    100% {
        transform: translateY(0) rotate(-6deg);
    }
    50% {
        transform: translateY(-20px) rotate(8deg);
    }
}
/* BAllOON 2 5*/
@-webkit-keyframes balloon2 {
    0%,
    100% {
        -webkit-transform: translateY(0) rotate(6eg);
    }
    50% {
        -webkit-transform: translateY(-30px) rotate(-8deg);
    }
}
@-moz-keyframes balloon2 {
    0%,
    100% {
        -moz-transform: translateY(0) rotate(6deg);
    }
    50% {
        -moz-transform: translateY(-30px) rotate(-8deg);
    }
}
@-o-keyframes balloon2 {
    0%,
    100% {
        -o-transform: translateY(0) rotate(6deg);
    }
    50% {
        -o-transform: translateY(-30px) rotate(-8deg);
    }
}
@keyframes balloon2 {
    0%,
    100% {
        transform: translateY(0) rotate(6deg);
    }
    50% {
        transform: translateY(-30px) rotate(-8deg);
    }
}
/* BAllOON 0*/
@-webkit-keyframes balloon3 {
    0%,
    100% {
        -webkit-transform: translate(0, -10px) rotate(6eg);
    }
    50% {
        -webkit-transform: translate(-20px, 30px) rotate(-8deg);
    }
}
@-moz-keyframes balloon3 {
    0%,
    100% {
        -moz-transform: translate(0, -10px) rotate(6eg);
    }
    50% {
        -moz-transform: translate(-20px, 30px) rotate(-8deg);
    }
}
@-o-keyframes balloon3 {
    0%,
    100% {
        -o-transform: translate(0, -10px) rotate(6eg);
    }
    50% {
        -o-transform: translate(-20px, 30px) rotate(-8deg);
    }
}
@keyframes balloon3 {
    0%,
    100% {
        transform: translate(0, -10px) rotate(6eg);
    }
    50% {
        transform: translate(-20px, 30px) rotate(-8deg);
    }
}
/* BAllOON 3*/
@-webkit-keyframes balloon4 {
    0%,
    100% {
        -webkit-transform: translate(10px, -10px) rotate(-8eg);
    }
    50% {
        -webkit-transform: translate(-15px, 20px) rotate(10deg);
    }
}
@-moz-keyframes balloon4 {
    0%,
    100% {
        -moz-transform: translate(10px, -10px) rotate(-8eg);
    }
    50% {
        -moz-transform: translate(-15px, 10px) rotate(10deg);
    }
}
@-o-keyframes balloon4 {
    0%,
    100% {
        -o-transform: translate(10px, -10px) rotate(-8eg);
    }
    50% {
        -o-transform: translate(-15px, 10px) rotate(10deg);
    }
}
@keyframes balloon4 {
    0%,
    100% {
        transform: translate(10px, -10px) rotate(-8eg);
    }
    50% {
        transform: translate(-15px, 10px) rotate(10deg);
    }
}
h1 {
    position: relative;
    top: 200px;
    text-align: center;
    color: white;
    font-size: 3.5em;
}
.swal-overlay {
    background-color: rgba(218, 57, 177, 0.45);
}

.swal-text {
    font-size: 20px;
    font-weight: 200;
    word-spacing: 5px;
}