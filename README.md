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
