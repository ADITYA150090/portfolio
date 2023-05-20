<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADITYA</title>
    <link rel="stylesheet" href="style/">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            border: 0;
        }
        
        body {
            background-color: rgb(82, 82, 244);
            color: white;
            font-family: 'Poppins', sans-serif;
        }
        
        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(53, 53, 207);
        }
        
        nav ul {
            display: flex;
            justify-content: center;
        }
        
        nav ul li {
            list-style: none;
            margin: 0 23px;
        }
        
        nav ul li a {
            text-decoration: none;
            color: white;
            justify-content: space-around;
            margin: 10px;
        }
        
        nav ul li a:hover {
            color: rgb(43, 226, 186);
            font-size: 1.02rem;
        }
        
        .left {
            font-size: 2rem;
        }
        
        .firstsection {
            display: flex;
            justify-content: space-around;
            align-items: center;
        }
        
        .firstsection>div {
            width: 35%;
        }
        
        .leftsection {
            font-size: 3rem;
            width: 70%;
            margin: 170px 0;
        }
        
        .leftsection .btn {
            padding: 12px;
            border-radius: 12px;
            border: 2px;
            background: rgb(8, 212, 219);
            font-size: 20px;
        }
        
        .leftsection .btn:hover {
            color: black;
            cursor: pointer;
        }
        
        .rightsection img {
            width: 640px;
            height: 640px;
        }
        
        .purpule {
            color: rgb(246, 255, 0);
        }
        
        .text-gray {
            color: gray;
        }
        
        #element {
            color: rgb(246, 255, 0);
        }
        
        .secondsection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }
        
        hr {
            color: red;
            background: border-box;
            height: -2.5px;
            display: block;
            unicode-bidi: isolate;
            margin-block-start: 0.5em;
            margin-block-end: 0.5em;
            margin-inline-start: auto;
            margin-inline-end: auto;
            overflow: hidden;
            border-style: inset;
            border-width: 1px;
            margin: 34px;
        }
        
        .secondsection h1 {
            color: rgb(255, 255, 255);
            font-size: 2rem;
        }
        
        .box {
            background: white;
            width: 200vh;
            height: 2px;
            margin: 4px;
        }
        
        footer {
            background-color: rgb(53, 53, 207);
            height: 225px;
        }
        
        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
            list-style: none;
        }
        
        footer ul li {
            list-style: none;
        }
        
        .text-center {
            display: flex;
            padding: 40px;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Aditya 1000</div>
            <div class="right">
                <ul>

                    <li>
                        <a href="C:\Users\USER\Desktop\my web\index.html">home</a></li>
                    <li>
                        <a href="l" target="_blank">about</a></li>
                    <li>
                        <a href="l" target="_blank">projects</a></li>
                    <li>
                        <a href="l" target="_blank">contact me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">Hello, my name is
                <div></div><span class="purpule">ADITYA 1000</span>
                <div>and i am </div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download resume</button>
                    <button class="btn">Github</button>
                </div>
            </div>
            <div class="rightsection">
                <img src="images/pg.webp" alt=""></div>

        </section>
        <!-- 
        <hr>
        <section class="secondsection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work experience</h1>
            <div class="box"></div>
        </section> -->

    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3></h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>home</li>
                    <li>about</li>
                    <li>services</li>
                    <li>contact</li>
                </ul>
            </div>
            <div class="footer-third">
                <li>instagram</li>
                <li>facebook</li>
                <li>discord</li>
                <li>github</li>
            </div>
            <div class="footer-fourth">
                <li>youtube</li>
                <li>whatsapp</li>
                <li>linkdin</li>
                <li>indeed</li>
            </div>
        </div>
        <div class="text-center">
            www.aditya1000portfolio.com | All rights Reserved @2023
        </div>
    </footer>

    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <script>
        var typed = new Typed('#element', {
            strings: ['CHESS PLAYER', 'WEBSITE DEVELOPER', 'Front-end DEVELOPER', 'WEB DEVELOPER'],
            typeSpeed: 80,
        });
    </script>
</body>

</html>
</script>
</body>

</html>
