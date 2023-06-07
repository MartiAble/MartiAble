<head>
    <meta charset='utf-8' />
    <meta name="viewport" content="width=device-width, initial-scale=0.9, maximum-scale=1.0, user-scalable=0" />
    <meta name="theme-color" content="#0a0a0a" />
    <title id='page-title'><?=$title?></title>
    <link rel='stylesheet' href='css/style.css' />
    <meta name="keywords" content="Йосоро, Rito Takagi, рито такаги, Rito,Рито, Zehiro, зехиро, yousoro,йосоро, main page,hub,хаб,лов лайв, love live, omedeto,омедето, флекс, сисадмин, системный администратор, ангел, Angel, sysadmin, yousoro-omedeto.ru, yousoro-omedeto, yousoro_omedeto, design, freelance, дизайн, фриланс, заказы, yousoro">
    <meta name="description" content="Youkoso, gaijin. Main hub by ZeHiRo © 2022">
    <meta name='wmail-verification' content='d3f2c745df3e13d3cf64e3d1536f5c43' />
    <meta name="msvalidate.01" content="308FF96F806F24752E41BE4630D71E2D" />
    <meta name="google-site-verification" content="ulzfbOHMNjbmXBd0XchCIiaGC1PY5JSucOdYw2tgKLw" />
    <meta name="yandex-verification" content="af44984359531c67" />
    <link rel="apple-touch-icon" sizes="114x114" href="../favicon/apple-icon-114x114.png">
    <link rel="icon" type="image/png" sizes="96x96" href="../favicon/favicon-96x96.png">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.11.2/css/all.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

    <style>
        html,
        body,
        header,
        .view {
            /* overflow: visible !important; */
            height: 100%;

        }
        @media (min-width: 560px) and (max-width: 740px) {
            html,
            body,
            header,
            .view {
                height: 650px;
            }
        }
        @media (min-width: 800px) and (max-width: 850px) {
            html,
            body,
            header,
            .view  {
                height: 650px;
            }
        }

        body {
            background-image: url(img/23.jpg) !important;
            background-position: center center !important;
            background-repeat: no-repeat !important;
            background-attachment: fixed !important;
            background-size: cover !important;
            background-color: #dcdcdc;

        }

        input::-webkit-outer-spin-button,
        input::-webkit-inner-spin-button {
            /* display: none; <- Crashes Chrome on hover */
            -webkit-appearance: none;
            margin: 0; /* <-- Apparently some margin are still there even though it's hidden */
        }

        .xYll {
                color: rgb(255, 196, 0) !important;
        }

        .bgProfile {
            background-color: rgba(0,0,0,.4);
            border: 1px solid #2a2a2a;
            backdrop-filter: blur(25px)!important;
        }

        .backMenuProfile {
            background: rgba(239,9,60,0.6);
            border-radius: 3px;
            backdrop-filter: blur(3.5px)!important;
            margin-top: 0.65% !important;
            font-size: 14pt;
            padding-top: .75% !important;
            padding-bottom: 0.75% !important;
            width: 100%;
            cursor: pointer !important;
        }

        .backMenuProfile:hover {
            background: rgba(255, 38, 73, 0.6);
            outline: 2px solid rgba(255,255,255,0.8); /* Пунктирная рамка */
            outline-offset: -1px; /* Выводим рамку внутри элемента */
            border-radius: 2px;
        }
        .backMenuProfileMob {
            background: rgba(239,9,60,0.6);
            border-radius: 3px;
            backdrop-filter: blur(3.5px)!important;
            font-size: 14pt;
            padding-top: .75% !important;
            padding-bottom: .75% !important;
            padding-left: 25%;
            width: 90%;
            margin-left: .9rem;
            cursor: pointer !important;
            margin-bottom: 1rem;
        }

        .backMenuProfileMob:hover {
            background: rgba(255, 38, 73, 0.6);
            outline: 2px solid rgba(255,255,255,0.8); /* Пунктирная рамка */
            outline-offset: -1px; /* Выводим рамку внутри элемента */
            border-radius: 2px;
        }

        .navNum{
            background-color: #44c682 !important;
            padding: .2em .5em .2em .5em;
            border-radius: 5px 0 0 5px;
            border: 2px solid #44c682;
        }
        .navName{
            background-color: #545e59;
            padding: .2em .5em .2em .5em;
            border-radius: 5px;
            border: 2px solid #44c682;
            margin-left:-.9em;
        }
        .carName{
            background-color: #e6e6e6 !important;
            padding: .2em .5em .2em .5em;
            border-radius: 5px 0 0 5px;
            border: 2px solid #e6e6e6;
            color: #8e8e8e;
        }
        .carClass{
            background-color: #44c682;
            padding: .2em .5em .2em .5em;
            border-radius: 5px;
            border: 2px solid #44c682;
            margin-left:-.9em;
        }
        .carNum{
            background-color: #fcfffb;
            padding: .2em .5em .2em .5em;
            border-radius: 5px;
            border: 2px solid #44c682;
            color: #8e8e8e;
            margin-left:-.9em;
        }
        .dragon {
            font-size: 11pt;
            padding-right: .4em;
        }
        .Profile {
            border-radius: 5px;
            background: rgba(239,9,60,0.6);
            backdrop-filter: blur(3.5px)!important;
            margin-top: 0.65% !important;
            font-size: 14pt;
            padding-top: .75% !important;
            padding-bottom: 0.75% !important;
            width: 99.8% !important;
            cursor: pointer !important;
        }
        .Cases {
            border-radius: 5px;
            background: rgba(102, 72, 238, 0.6);
            backdrop-filter: blur(3.5px)!important;
            margin-left: 1% !important;
            padding-top: 8%;
            font-size: 14pt;
            cursor: pointer !important;
        }
        .Behance{
            border-radius: 5px;
            background: rgba(0,0,0,0.5);
            backdrop-filter: blur(3.5px)!important;
            margin-left: 1% !important;
            padding-top: 6%;
            height: 102px;
            width: 50%;
            margin-top: 1%;
            cursor: pointer !important;
        }
        .Vk {
            border-radius: 5px;
            background: rgba(0, 119, 255, 0.5);
            backdrop-filter: blur(3.5px)!important;
            margin-left: 1% !important;
            padding-top: 8%;
            height: 102px;
            width: 50%;
            cursor: pointer !important;
        }
        .Telegram {
            border-radius: 5px;
            background: rgba(52, 171, 223, 0.5);
            backdrop-filter: blur(3.5px)!important;
            height: 100%;
            height: 210px;
            padding-top: 9%;
            cursor: pointer !important;
        }
        @media (min-width: 380px) and (max-width: 576px){
            .navMobile {
                margin-top: 2% !important;
            }
            .Profile {
                background: rgba(239,9,60,0.6);
                backdrop-filter: blur(3.5px)!important;
                margin-top: 1.5% !important;
                font-size: 14pt;
                padding-top: .75% !important;
                padding-bottom: 0.75% !important;
                width: 99.8% !important;
                cursor: pointer !important;
            }
            .Cases {
                background: rgba(95,76,211,0.6);
                backdrop-filter: blur(3.5px) !important;
                margin-left: 0% !important;
                padding-top: 4%;
                margin-top: 1% !important;
                height: 80px;
                width: 99.8% !important;
                font-size: 14pt;
                cursor: pointer !important;
            }
            .Behance{
                background: rgba(0,0,0,0.5);
                backdrop-filter: blur(3.5px) !important;
                padding-top: 8.5%;
                height: 80px;
                font-size: 18pt;
                width: 33%;
                margin-top: 0%;
                margin-left: 1.5% !important;
                margin-bottom: 1%;
                cursor: pointer !important;
            }
            .Vk {
                background: rgba(0, 119, 255, 0.65);
                backdrop-filter: blur(3.5px)!important;
                margin-left: 1.5% !important;
                padding-top: 8.5%;
                font-size: 18pt;
                height: 80px;
                width: 32% !important;
                cursor: pointer !important;
            }
            .Telegram {
                background: rgba(52, 171, 223, 0.75);
                backdrop-filter: blur(3.5px)!important;
                width: 32% !important;
                height: 80px;
                font-size: 18pt;
                padding-top: 8.5%;
                cursor: pointer !important;
            }
            .introMenu {
                margin-top: 25% !important;
            }
        }
        @media (min-width: 380px) and (max-width: 600px){

        }
        .Telegram:hover {
            background-color: rgba(108, 198, 243, 0.5);
            border: 1px solid white;
            border-radius: 2px;
        }
        .Vk:hover {
            background: rgba(0, 165, 255, 0.58);
            border: 1px solid white;
            border-radius: 2px;
        }
        .Behance:hover {
            background: rgba(56, 56, 56, 0.5);
            border: 1px solid white;
            border-radius: 2px;
        }
        .Cases:hover {
            background: rgba(100, 113, 252, 0.6);
            border: 1px solid white;
            border-radius: 2px;
        }
        .Profile:hover {
            background: rgba(255, 38, 73, 0.6);
            border: 1px solid white;
            border-radius: 2px;
        }
        .loadingPage {
            position: fixed;
            width: 100% !important;
            height: 100% !important;
            background: rgba(0,0,0,0.7);
            z-index: 10000 !important;
        }

        .loader-2 {
            display: block;
            height: 32px;
            width: 32px;
            -webkit-animation: loader-2-1 3s linear infinite;
            animation: loader-2-1 3s linear infinite;
        }
        @-webkit-keyframes loader-2-1 {
            0%   { -webkit-transform: rotate(0deg); }
            100% { -webkit-transform: rotate(360deg); }
        }
        @keyframes loader-2-1 {
            0%   { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .loader-2 span {
            display: block;
            position: absolute;
            top: 0; left: 0;
            bottom: 0; right: 0;
            margin: auto;
            height: 32px;
            width: 32px;
            clip: rect(16px, 32px, 32px, 0);
            -webkit-animation: loader-2-2 1.5s cubic-bezier(0.770, 0.000, 0.175, 1.000) infinite;
            animation: loader-2-2 1.5s cubic-bezier(0.770, 0.000, 0.175, 1.000) infinite;
        }
        @-webkit-keyframes loader-2-2 {
            0%   { -webkit-transform: rotate(0deg); }
            100% { -webkit-transform: rotate(360deg); }
        }
        @keyframes loader-2-2 {
            0%   { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .loader-2 span::before {
            content: "";
            display: block;
            position: absolute;
            top: 0; left: 0;
            bottom: 0; right: 0;
            margin: auto;
            height: 32px;
            width: 32px;
            border: 3px solid transparent;
            border-top: 3px solid #FFF;
            border-radius: 50%;
            -webkit-animation: loader-2-3 1.5s cubic-bezier(0.770, 0.000, 0.175, 1.000) infinite;
            animation: loader-2-3 1.5s cubic-bezier(0.770, 0.000, 0.175, 1.000) infinite;
        }
        @-webkit-keyframes loader-2-3 {
            0%   { -webkit-transform: rotate(0deg); }
            100% { -webkit-transform: rotate(360deg); }
        }
        @keyframes loader-2-3 {
            0%   { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .loader-2 span::after {
            content: "";
            display: block;
            position: absolute;
            top: 0; left: 0;
            bottom: 0; right: 0;
            margin: auto;
            height: 32px;
            width: 32px;
            border: 3px solid rgba(255, 255, 255, .5);
            border-radius: 50%;
        }

    </style>
    <!-- Yandex.Metrika counter -->
    <script type="text/javascript" >
        (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
            m[i].l=1*new Date();
            for (var j = 0; j < document.scripts.length; j++) {if (document.scripts[j].src === r) { return; }}
            k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)})
        (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");

        ym(90948677, "init", {
            clickmap:true,
            trackLinks:true,
            accurateTrackBounce:true,
            webvisor:true
        });
    </script>
    <noscript><div><img src="https://mc.yandex.ru/watch/90948677" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
    <!-- /Yandex.Metrika counter -->
</head>
<body style="height: 70% !important;">

<!-- Main Navigation -->
    <!-- Navbar COMP -->
<div class="loadingPage">
    <div class="loader-2 center" style="padding-left: 100%; padding-top: 50%;"><span></span></div>
</div>


    <nav class="navbar navbar-expand-lg navbar-dark fixed-top scrolling-navbar row d-none d-sm-block" style="background-color: rgba(49,49,49,0)">
        <div class="container">
            <div class="col-xl-2 col-lg-2 col-md-3 col-sm-3 col-6" style="margin-left: 10% !important; margin-right: 0 !important;">
                <div style="color: white">
                <span class="navNum"><i class="fas fa-dragon dragon"></i>19</span>
                    <span class="navName">ZeHiRo <i class="fab fa-galactic-senate"></i></span>
                </div>
            </div>
            <div class="navMobile" style="margin-right: 10% !important;">
                <div style="color: white">
                    <span class="carName">2023 yousoro-omedeto.ru #TOYOTA </span>
                    <span class="carClass">X </span>
                    <span class="carNum">999</span>
                </div>
            </div>
        </div>
    </nav>
    <!-- NAVBAR mob -->

    <nav class="navbar navbar-expand-lg navbar-dark scrolling-navbar d-block d-sm-none" style="background-color: rgba(49,49,49,0)">
        <div class="container">
            <div class="col-xl-2 col-lg-2 col-md-3 col-sm-4 col-6">
                <div style="color: white">
                    <span class="navNum"><i class="fas fa-dragon dragon"></i>19</span>
                    <span class="navName">ZeHiRo <i class="fab fa-galactic-senate"></i></span>
                </div>
            </div>
            <div class="navMobile">
                <div style="color: white">
                    <span class="carName">2022 yousoro-omedeto.ru #TOYOTA </span>
                    <span class="carClass">X </span>
                    <span class="carNum">999</span>
                </div>
            </div>
        </div>
    </nav>
    <!-- Navbar -->

    <!-- Intro Section -->
        <div class="mask h-100 d-flex justify-content-center introMenu" style="padding-top: 10%">
            <div class="container">

                <!-- MAIN MENU COMP -->
                <div class="MainMenuComp">
                <div class="row d-none d-sm-block " style="">
                    <div class="col-xl-10 col-lg-11 col-md-12 col-sm-12 col-11 mx-auto mt-5">
                        <div class="card-body" style="">
                            <div class="container">
                                <div class="row row-cols-2 text-center align-middle">
                                    <div class="col-2 Telegram loadingActive" onclick="window.open('https://t.me/yousoro_omedeto')" >
                                        <i class="fab fa-telegram-plane"></i> Telegram
                                    </div>
                                    <div class="row" style="margin-right: -25% !important;">
                                        <div class="col-8 Vk loadingActive" style=""  onclick="window.open('https://vk.com/yousoro_omedeto')" >
                                            <i class="fab fa-vk" style="font-size:24pt"></i><br>
                                        </div>
                                        <div class="col-8 Behance loadingActive" style="" onclick="window.open('https://www.behance.net/martiable')">
                                            <i class="fab fa-behance"></i><br>Behance
                                        </div>
                                    </div>
                                    <div class="col-7 Cases loadingActive" style="" onclick="document.location.href = 'https://yousoro-omedeto.ru/src/cases/casesChoose.php'" >
                                        <i class="fas fa-briefcase"></i><br>Cases
                                    </div>
                                    <div class="col-12 Profile ProfileChangeComp loadingActive" style="">
                                        Profile <i class="fas fa-angle-double-down" style="font-size: 12pt;"></i>
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>
                </div>
                </div>

                <!-- MAIN MENU MOB -->

                <div class="MainMenuMob">
                    <div class="row d-block d-sm-none " style="margin-top: 10%" >
                        <div class="col-xl-10 col-lg-11 col-md-12 col-sm-12 col-11 mx-auto mt- d-block d-xs-none  ">
                            <div class="card-body " style="">
                                <div class="container">
                                    <div class="row text-center align-middle">
                                        <div class="col-3 Telegram loadingActive" onclick="window.open('https://t.me/yousoro_omedeto')" >
                                            <i class="fab fa-telegram-plane"></i>
                                        </div>
                                        <div class="col-3 Vk loadingActive" onclick="window.open('https://vk.com/yousoro_omedeto')" >
                                            <i class="fab fa-vk"></i>
                                        </div>
                                        <div class="col-3 Behance loadingActive" onclick="window.open('https://www.behance.net/martiable')" >
                                            <i class="fab fa-behance"></i>
                                        </div>
                                        <div class="col-10 Cases loadingActive" style="" onclick="document.location.href = 'https://yousoro-omedeto.ru/src/cases/casesChoose.php'" >
                                            <i class="fas fa-briefcase"></i><br>Cases
                                        </div>
                                        <div class="col-12 Profile ProfileChangeMob loadingActive" style="">
                                            Profile <i class="fas fa-angle-double-down" style="font-size: 12pt;"></i>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- PROFILE COMP -->

                <div class="ActiveProfileComp" style="display: none">
                        <div class="row d-none d-xl-block d-lg-block" style="margin-top: -6rem;">
                            <div class="col-xl-10 col-lg-12 col-md-12 col-sm-10 col-10 mx-auto mt-5" >
                                <div class="card bgProfile" style="">
                                    <div class="card-header" >
                                        Профиль: Данил Маратович <a href="/" style="text-decoration: none">| ZeHiRo |</a>
                                    </div>
                                    <div class="card-body">
                                        <div class="row">
                                            <div class="col-4" style="">
                                                <div class="backMenuProfile loadingActive">
                                                     <i class="fas fa-angle-double-left" style="font-size: 10pt !important; padding-left: 1rem"></i> Назад
                                                </div>
                                                <img src="img/profile.jpg" style="width: 100%; border-radius: 6px; margin-top: .5rem">

                                                <p class="d-block" style="padding-left: .2em !important; margin-bottom: 0 !important; margin-top: .5rem"> Подробнее:
                                                    <a href="https://vk.com/yousoro_omedeto" target="_blank">
                                                        <i class="fab fa-vk"></i></a>
                                                    <a href="https://t.me/yousoro_omedeto" target="_blank">
                                                        <i class="fab fa-telegram-plane"></i>
                                                    </a>
                                                </p>
                                            </div>
                                            <div class="col-8" style="">
                                                Завершено работ: <span class="corrective">68</span>
                                                <hr>
                                                Организации:
                                                <br><i class="fab fa-ioxhost" style="font-size: 10pt"> </i> <a href="http://licey94.ru/submenu/1/" target="_blank" style="text-decoration: none">МАОУ "Лицей №94"</a> - Системный администратор
                                                <br><i class="fab fa-ioxhost" style="font-size: 10pt"> </i> <a href="https://www.nefteavtomatika.ru/ru/" target="_blank" style="text-decoration: none">УНУ АО "Нефтеавтоматика"</a> - Инженер АСУ ТП, Системный администратор
                                                <br><i class="fab fa-ioxhost" style="font-size: 10pt"> </i> <a href="https://personasport.ru/about" target="_blank" style="text-decoration: none">PersonaSport</a> - WEB developer (Fullstack: <i class="fab fa-html5" style="font-size: 14pt">&nbsp;+&nbsp;</i><i class="fab fa-css3-alt" style="font-size: 14pt">&nbsp;+&nbsp;</i><i class="fab fa-php" style="font-size: 14pt">&nbsp;+&nbsp;</i><i class="fab fa-java" style="font-size: 14pt"></i>)
                                                <hr>
                                                Деятельность:
                                                <br><i class="fab fa-fantasy-flight-games" style="font-size: 12pt"></i> <a href="https://habr.com/ru/company/polyglot/blog/300046/" target="_blank" style="text-decoration: none">Freelance</a> - WebDev & UX\UI designer (2016-2020)
                                                <br><i class="fab fa-fantasy-flight-games" style="font-size: 12pt"></i> <a href="https://yunarmy.ru/" target="_blank" style="text-decoration: none">Юнармия</a> - Гл. штаба по Советскому району г. Уфа (2019-2021)
                                                <br><i class="fab fa-fantasy-flight-games" style="font-size: 12pt"></i> <a href="404.php" style="text-decoration: none">HonokaBot</a> - Администратор бота (аудитория: 100k+, 2017-2020)
                                                <hr>
                                                DevKit:
                                                <div class="row" style="margin-top: -1em">
                                                <div class="col-4">
                                                    <br><i class="fab fa-html5" style="font-size: 14pt"></i><a href="https://habr.com/ru/company/vdsina/blog/500190/" target="_blank" style="text-decoration: none"> HTML</a>
                                                    <br><i class="fab fa-css3-alt" style="font-size: 14pt"></i> <a href="https://en.wikipedia.org/wiki/CSS#Selector" target="_blank" style="text-decoration: none">CSS</a>
                                                    <br><i class="fab fa-php" style="font-size: 12pt; margin-left: -1.5%"></i><a href="https://thecode.media/php-haters/" target="_blank"  style="text-decoration: none"> PHP</a>
                                                    <br><i class="fab fa-java" style="font-size: 14pt"></i><a href="https://habr.com/ru/post/165649/" target="_blank" style="text-decoration: none"> JavaScript</a>
                                                    <br><i class="fab fa-python" style="font-size: 14pt"></i><a href="https://ru.wikipedia.org/wiki/Python" target="_blank" style="text-decoration: none"> Python</a>
                                                </div>
                                                <div class="col-5">
                                                    <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i>
                                                    <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i>
                                                    <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i>
                                                    <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i>
                                                    <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i>
                                                </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                </div>

                <!-- PROFILE MOB -->

            <div class="ActiveProfileMob" style="margin-top: -10rem !important;  display: none">
                <div class="row d-md-block d-sm-block d-xs-block d-lg-none d-xl-none " style="margin-top: -6% !important;">
                    <div class="col-xl-10 col-lg-12 col-md-12 col-sm-10 col-10 mx-auto mt-5" >
                        <div class="card bgProfile" style=" margin-bottom: 2rem !important;">
                            <div class="card-header">
                                Профиль: Данил Маратович <br>
                                <a href="/" style="text-decoration: none; width: 100%; margin-left: 4.65rem">| ZeHiRo |</a>
                            </div>
                            <div class="card-body" >
                                <div class="row">
                                    <div class="backMenuProfileMob loadingActive">
                                        <i class="fas fa-angle-double-left" style="font-size: 10pt !important; padding-left: 1rem"></i> Назад
                                    </div>
                                    <div class="">
                                        <img src="img/profile.jpg" style="border-radius: 6px;width: 100%; ">
                                    </div>
                                        <p class="d-block" style="margin-top: .5rem"> Подробнее:
                                            <a href="https://vk.com/yousoro_omedeto" target="_blank">
                                                <i class="fab fa-vk"></i></a>
                                            <a href="https://t.me/yousoro_omedeto" target="_blank">
                                                <i class="fab fa-telegram-plane"></i>
                                            </a>
                                        </p>
                                    <div class="col-12" style="">
                                        Завершено работ: <span class="corrective">68</span>
                                        <hr>
                                        Организации:
                                        <br><i class="fab fa-ioxhost" style="font-size: 10pt"></i>
                                        <a href="http://licey94.ru/submenu/1/" target="_blank" style="text-decoration: none">
                                            МАОУ "Лицей №94"</a> <br>Системный администратор
                                        <br><i class="fab fa-ioxhost" style="font-size: 10pt"></i>
                                        <a href="https://www.nefteavtomatika.ru/ru/" target="_blank" style="text-decoration: none">
                                            УНУ АО "Нефтеавтоматика"</a><br> Инженер АСУ ТП, Системный администратор
                                        <br><i class="fab fa-ioxhost" style="font-size: 10pt"></i>
                                        <a href="https://personasport.ru/about" style="text-decoration: none">
                                            PersonaSport</a> <br> WEB developer <br>(Fullstack: <i class="fab fa-html5" style="font-size: 14pt">&nbsp;+&nbsp;</i><i class="fab fa-css3-alt" style="font-size: 14pt">&nbsp;+&nbsp;</i><i class="fab fa-php" style="font-size: 14pt">&nbsp;+&nbsp;</i><i class="fab fa-java" style="font-size: 14pt"></i>)
                                        <hr>
                                        Деятельность:
                                        <br><i class="fab fa-fantasy-flight-games" style="font-size: 12pt"></i>
                                        <a style="text-decoration: none">Freelance</a> <br> WebDev & UX\UI designer (2016-2020)
                                        <br><i class="fab fa-fantasy-flight-games" style="font-size: 12pt"></i>
                                        <a href="https://yunarmy.ru/" target="_blank" style="text-decoration: none">Юнармия</a><br> Гл. штаба по Советскому району г. Уфа (2019-2021)
                                        <br><i class="fab fa-fantasy-flight-games" style="font-size: 12pt"></i>
                                        <a href="" style="text-decoration: none">HonokaBot</a> <br> Администратор бота (аудитория: 100k+, 2017-2020)
                                        <hr>
                                        DevKit:
                                        <div class="row" style="margin-top: -1em">
                                            <div class="col-5">
                                                <br><i class="fab fa-html5" style="font-size: 14pt"></i><a href="https://habr.com/ru/company/vdsina/blog/500190/" target="_blank"  style="text-decoration: none"> HTML</a>
                                                <br><i class="fab fa-css3-alt" style="font-size: 14pt"></i> <a href="https://en.wikipedia.org/wiki/CSS#Selector" target="_blank" style="text-decoration: none">CSS</a>
                                                <br><i class="fab fa-php" style="font-size: 12pt; margin-left: -1.5%"></i><a href="https://thecode.media/php-haters/" target="_blank" style="text-decoration: none"> PHP</a>
                                                <br><i class="fab fa-java" style="font-size: 14pt"></i><a href="https://habr.com/ru/post/165649/" target="_blank" style="text-decoration: none"> JS</a>
                                                <br><i class="fab fa-python" style="font-size: 14pt"></i><a href="https://ru.wikipedia.org/wiki/Python" target="_blank" style="text-decoration: none"> Python</a>
                                            </div>
                                            <div class="col-7">
                                                <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i>
                                                <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i>
                                                <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i>
                                                <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i>
                                                <br><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="fas xYll fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i><i class="far fa-star"></i>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            </div>
        </div>


<!-- Custom scripts -->

<script src="https://code.jquery.com/jquery-3.6.1.min.js" integrity="sha256-o88AwQnZB+VDvE9tvIXrMQaPlFFSUTR+nldQm1LuPXQ=" crossorigin="anonymous"></script>


<script src="https://cdn.jsdelivr.net/npm/vue@2.6.14/dist/vue.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/axios/1.0.0-alpha.1/axios.js" integrity="sha512-uplugzeh2/XrRr7RgSloGLHjFV0b4FqUtbT5t9Sa/XcilDr1M3+88u/c+mw6+HepH7M2C5EVmahySsyilVHI/A==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

<script>
    $(function(){
        $('div.loadingPage').hide();
        $('button.loadingActive').on('click', function(){
            $('div.loadingPage').show();
        });
    });
</script>

<script>
    $(function(){
        $('div.ActiveProfileMob').hide();
        $('div.ProfileChangeMob').on('click', function(){
            $('div.MainMenuMob').hide();
            $('div.ActiveProfileMob').show();

        });
    });
</script>
<script>
    $(function(){
        $('div.ActiveProfileComp').hide();
        $('div.ProfileChangeComp').on('click', function(){
            $('div.MainMenuComp').hide();
            $('div.ActiveProfileComp').show();

        });
    });
</script>

<script>
    $(function(){
        $('div.backMenuProfile').on('click', function(){
            $('div.ActiveProfileComp').hide();
            $('div.MainMenuComp').show();

        });
    });
</script>

<script>
    $(function(){
        $('div.backMenuProfileMob').on('click', function(){
            $('div.ActiveProfileMob').hide();
            $('div.MainMenuMob').show();

        });
    });
</script>


</body>
