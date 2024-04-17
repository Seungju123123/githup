<!DOCTYPE html>
<html lang="en">

<head>
    <script src="https://kit.fontawesome.com/5cfbf3b586.js" crossorigin="anonymous"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cute+Font&family=Nanum+Pen+Script&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Instrument+Sans:ital,wght@0,400..700;1,400..700&display=swap');

        * {
            font-family: "Cute Font", sans-serif;
        }






        .h1 {
            font-size: 30px;

        }

        h2 {
            font-family: "Instrument Sans", sans-serif;

        }


        html,
        body {
            width: 100%;
            height: 100%;
            margin: 0px;

        }

        .container {
            width: 100%;
            height: 100%;
            background: white;

            line-height: 40px;
        }

        .boxitem {
            width: 450px;
            height: 600px;
            margin: 100px auto;


            color: black;

            padding-top: 50px;
            border-bottom: 1px solid rgb(207, 207, 207);

            background-image: url(https://i.ibb.co/HN2wbQn/306021-P7-XZN3-667.jpg);
            background-size: cover;

            margin-left: 0px;
            margin-right: 200px;
        }

        #love {

            display: grid;
            grid-template-columns: 250px 1fr;
        }

        button {
            margin: 10px auto;

            font-size: 20px;
            background-color: transparent;
            border: 1px solid transparent;
            cursor: pointer;

            font-family: "Instrument Sans", sans-serif;
            text-align: center;
        }

        button:hover {
            background: silver;
            border-radius: 5px;
        }

        .open1 {
            /* 선 */
            border-right: 1px solid rgb(223, 223, 223);
        }

        .circle {
            /* 원을 그리는 코드*/
            width: 50px;
            height: 50px;
            border-radius: 50%;
            border: 1px solid black;
            /*원과 원 사이의 간격조정 코드*/
            margin-top: 5px;
            flex-direction: column;


        }

        .img-block {
            /* 이미지에 맞게 들어가게 하는 코드 */
            /* 원형은 알아서 따로 해줘야한다. */
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        #sort {
            /* 정렬 id */
            display: flex;
            flex-direction: right;
            justify-content: left;
            text-align: left;
            margin: 0px auto;




        }

        p {
            font-family: "Instrument Sans", sans-serif;
            color: gray;

            margin-top: 10px;
            margin-bottom: 0px;
        }

        h3 {
            margin-left: 150px;
        }

        .nope {
            margin: 250px;
        }

        img {
            max-width: 100%;
        }

        .jb-a {
            width: 100%;

            position: relative
        }

        .jb-c {
            position: absolute;
            top: 0px;
            left: 0px;
            display: none;
        }

        .jb-a:hover .jb-c {
            display: block;
        }
    </style>
</head>

<body>
    <div id="love" class="container">
        <div class="open1">

            <br><a href="1.html"><button>
                    <h1>calmgram</h1>
                </button></a><br>

            <Nav>
                <br><a href="1.html"><button><i class="fa-solid fa-house"
                            style="font-size:30px; margin-right: 30px;"></i>문승주</button></a><br>
                <br><a href="2.html"><button><i class="fa-solid fa-magnifying-glass"
                            style="font-size:30px; margin-right: 30px;"></i>강아름</button></a><br>
                <br><a href="3.html"><button><i class="fa-regular fa-compass"
                            style="font-size:30px; margin-right: 30px;"></i>박정균</button></a><br>
                <br><a href="4.html"><button><i class="fa-solid fa-clapperboard"
                            style="font-size:30px; margin-right: 30px;"></i>이수빈</button></a><br>
                <br><a href="5.html"><button><i class="fa-regular fa-paper-plane"
                            style="font-size:30px; margin-right: 30px;"></i>박서진</button></a><br>
                <br><a href="6.html"><button><i class="fa-regular fa-heart"
                            style="font-size:30px; margin-right: 30px;"></i>복광수</button></a><br>
            </Nav>
        </div>


        <div id="sort" style="margin-top: 0px; ">

            <div class="boxitem">
                <h3 class="pro" style="font-size: 30px;;">우리들은 차분하조</h3>
                <img height="500">
                <div style="font-size: 25px; text-align: center;">

                </div>
            </div>

            <div id="nope">
                <div id="sort" style="margin-top: 10px; ">
                    <div class="circle">
                        <a href="https://www.instagram.com/spartacodingclub/"><img class="img-block"
                                style="border-radius: 50%;"
                                src="https://www.urbanbrush.net/web/wp-content/uploads/edd/2022/11/urbanbrush-20221108214712319041.jpg"
                                alt="..."></a>
                    </div>
                    <h2 style="font-size: 15px; margin-bottom: 5px; margin-left: 15px;"> 차분하조 </h2>
                </div>

                <p>회원님을 위한 추천</p>


                <div id="sort" style="margin-top: 10px;">
                    <div class="circle">
                        <a href="https://www.instagram.com/99_sj.m/">
                            <div class="jb-a">
                                <img class="img-block" style="border-radius: 50%;"
                                    src="https://www.urbanbrush.net/web/wp-content/uploads/edd/2022/11/urbanbrush-20221108214712319041.jpg"
                                    alt="...">
                                <img src="https://i.ibb.co/WDGN19J/a.png" alt="" class="jb-c" img class="img-block"
                                    style="border-radius: 50%;">
                            </div>
                        </a>
                    </div>
                    <h2 style="font-size: 15px; margin-bottom: 5px; margin-left: 15px;"> @99_sj.m </h2>

                </div>

                <div id="sort">
                    <div class="circle">
                        <a href=https://www.instagram.com/arumi729>
                            <div class="jb-a">
                                <img class="img-block" style="border-radius: 50%;"
                                    src="https://search.pstatic.net/sunny/?src=http%3A%2F%2Fartmug.kr%2Fimage%2Fup_img%2Fdetail%2Fgoods_6476%2F16786031530.gif&type=sc960_832_gif"
                                    alt="...">
                                <img src="https://i.ibb.co/tHFRwdX/b.png" alt="" class="jb-c" img class="img-block"
                                    style="border-radius: 50%;">
                            </div>
                        </a>
                    </div>
                    <h2 style="font-size: 15px; margin-bottom: 5px; margin-left: 15px;"> @arumi729 </h2>
                </div>

                <div id="sort">
                    <div class="circle">
                        <a href="https://www.instagram.com/wjdrbs2024/">
                            <div class="jb-a">
                                <img class="img-block" style="border-radius: 50%;"
                                    src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAxNzAxMDRfNzkg%2FMDAxNDgzNDY1NjYzNzU2.bg4w6I5AQi6x7fMey_PaaHUvKDaUfuvqJpP6lzxAgVgg.d6ARFMDTZK4heN4er1b333u8CQ4_dnNY4tlEBt401Mkg.JPEG.xenom%2F%25B5%25BF%25B9%25B0_%25BA%25B4%25BE%25C6%25B8%25AE_%25C6%25C4%25B6%25F5%25B8%25D3%25B8%25AE.jpg&type=sc960_832"
                                    alt="...">
                                <img src="https://i.ibb.co/K9b04FW/c.png" alt="" class="jb-c" img class="img-block"
                                    style="border-radius: 50%;">
                            </div>
                        </a>
                    </div>
                    <h2 style="font-size: 15px; margin-bottom: 5px; margin-left: 15px;"> @wjdrbs2024</h2>
                </div>

                <div id="sort">
                    <div class="circle">
                        <a href="https://www.instagram.com/sh_unning/">
                            <div class="jb-a">
                                <img class="img-block" style="border-radius: 50%;"
                                    src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyMTA5MjhfMzMg%2FMDAxNjMyNzkyODk2MDM3.6a-vcF3hVKF-wXJlypJFzACcRho32EfG437inB1lZ1Ig.CWrIh5dVUGVqJGHC1A2TXBJqmCRv533NkETEaoV7JPIg.PNG.huganism%2Fimage.png&type=sc960_832"
                                    alt="...">
                                <img src="https://i.ibb.co/LZ9qmVQ/d.png" alt="" class="jb-c" img class="img-block"
                                    style="border-radius: 50%;">
                            </div>
                        </a>
                    </div>
                    <h2 style="font-size: 15px; margin-bottom: 5px; margin-left: 15px;"> @sh_unning </h2>
                </div>

                <div id="sort">
                    <div class="circle">
                        <a href="https://www.instagram.com/ah_ma.do/">
                            <div class="jb-a">
                                <img class="img-block" style="border-radius: 50%;"
                                    src="https://i.ibb.co/XyRPQb1/image-jip.jpg" alt="...">
                                <img src="https://i.ibb.co/c1Xc9G4/e.png" alt="" class="jb-c" img class="img-block"
                                    style="border-radius: 50%;">
                            </div>
                        </a>
                    </div>
                    <h2 style="font-size: 15px; margin-bottom: 5px; margin-left: 15px;"> @ah_ma.do </h2>
                </div>

                <div id="sort">
                    <div class="circle">
                        <a href="https://www.instagram.com/buck_k_s/">
                            <div class="jb-a">
                                <img class="img-block" style="border-radius: 50%;"
                                    src="https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyMTA5MDJfMjU3%2FMDAxNjMwNTY0ODcwNTE3.VjgOeC-KG7iCDeITLNp7FR7lhMg4k7njqYmW_a5LEPAg.9KQ1kWRFlKVogdGM9lkb4BlDze0r-lNQZKvrPFw3yd8g.PNG.ricemuseum1%2F123.png&type=sc960_832"
                                    alt="...">
                                <img src="https://i.ibb.co/QK2zSL3/f.png" alt="" class="jb-c" img class="img-block"
                                    style="border-radius: 50%;">
                            </div>
                        </a>
                    </div>
                    <h2 style="font-size: 15px; margin-bottom: 5px; margin-left: 15px;"> @buck_k_s </h2>

                    <div>




                    </div>
                </div>

            </div>



        </div>

</body>

</html>
