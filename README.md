<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>첫걸음교회</title>
    <!-- Bootstrap CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
		<img src="image.png" alt="로고">
    <style>
        body {
            font-family: 'Arial', sans-serif;
        }
        .navbar {
            margin-bottom: 20px;
        }
        header, section, footer {
            padding: 60px 0;
        }
        section {
            background-color: #f8f9fa;
        }
        footer {
            background-color: #343a40;
            color: #ffffff;
        }
        .carousel-inner img {
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <a class="navbar-brand" href="#">첫걸음교회</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">교회 소개</a></li>
                    <li class="nav-item"><a class="nav-link" href="#services">예배 시간</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">연락처</a></li>
                    <li class="nav-item"><a class="nav-link" href="http://127.0.0.1:5500/프로젝트/공휴일식사나눔운동본부%20활동사진.html" target="_blank">공휴일식사나눔운동본부 활동사진</a></li>
                    <li class="nav-item"><a class="nav-link" href="#" onclick="openFullscreenWindow('http://127.0.0.1:5500/프로젝트/찾아오시는%20길.html')">찾아오시는 길</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <section id="carousel">
        <div id="churchCarousel" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="image1.jpg" alt="Church Image 1">
                </div>
                <div class="carousel-item">
                    <img src="image2.jpg" alt="Church Image 2">
                </div>
                <div class="carousel-item">
                    <img src="image3.jpg" alt="Church Image 3">
                </div>
            </div>
            <a class="carousel-control-prev" href="#churchCarousel" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#churchCarousel" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>교회 소개</h2>
            <p>노원구 상계동에 위치한 대한예수교장로회 첫걸음교회입니다 :)<br><br>
                🙋‍ 전교인이 함께 사역을 이루어 가는 '교인교회'<br>
                👨‍ 상처에 반창고가 되어주는 '이웃교회'<br>
                🧕 건축보다 인류애에 관심있는 '인류교회'<br>
                📚 성경이 삶의 기준인 '복음교회'<br><br>
                서울시 노원구 동일로 1382 4층.</p>
            <p>첫걸음교회 유튜브 : <a href="https://www.youtube.com/channel/UCvZF4uK91Dd6JbCHx6-Sb2Q" target="_blank">첫걸음교회 유튜브</a></p>
    </section>

    <section id="services">
        <div class="container">
            <h2>예배 시간</h2>
            <ul>
                <li>주일 예배: 매주 일요일 오전 11시</li>
                <li>수요 예배: 매주 수요일 오후 8시</li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>연락처</h2>
            <ul>
                <li>전화: 010-8943-9068</li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container text-center">
            <p><섬기는 사람들></p>
            <p>담임목사 : 김대영</p>
            <p>전도사 : 박희지</p>
            <p>행동으로 실천하는 첫걸음교회! 직접 오셔서 느껴보십시요!</p>
        </div>
    </footer>

    <!-- Bootstrap JS, Popper.js, and jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <!-- Custom JS -->
    <script src="scripts.js"></script>
    <script>
        function openFullscreenWindow(url) {
            var newWindow = window.open(url, '_blank', 'fullscreen=yes');
            newWindow.moveTo(0, 0);
            newWindow.resizeTo(screen.width, screen.height);
        }
    </script>
</body>
</html>
