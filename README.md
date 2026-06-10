<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Travel Guide</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Malgun Gothic',sans-serif;
}

body{
    background:#f5f5f5;
    color:#333;
}

header{
    background:#0099cc;
    color:white;
    padding:20px;
    position:sticky;
    top:0;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

.menu a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

.hero{
    height:500px;
    background:url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e') center/cover;
    display:flex;
    justify-content:center;
    align-items:center;
    color:white;
    text-align:center;
}

.hero h1{
    font-size:50px;
    background:rgba(0,0,0,0.5);
    padding:20px;
    border-radius:10px;
}

section{
    padding:60px 10%;
}

h2{
    margin-bottom:30px;
    text-align:center;
    color:#0099cc;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 3px 10px rgba(0,0,0,0.1);
}

.card img{
    width:100%;
    height:200px;
    object-fit:cover;
}

.card-content{
    padding:15px;
}

.review{
    background:white;
    padding:20px;
    margin-bottom:15px;
    border-radius:10px;
}

.contact-form{
    background:white;
    padding:20px;
    border-radius:10px;
}

.contact-form input,
.contact-form textarea{
    width:100%;
    padding:10px;
    margin:10px 0;
}

.contact-form button{
    background:#0099cc;
    color:white;
    border:none;
    padding:10px 20px;
    cursor:pointer;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">Travel Guide</div>
<div class="menu">
<a href="#home">Home</a>
<a href="#travel">Travel</a>
<a href="#restaurant">Restaurant</a>
<a href="#review">Review</a>
<a href="#contact">Contact</a>
</div>
</nav>
</header>

<section class="hero" id="home">
<h1>
당신의 특별한 여행을 시작하세요!<br>
전국 여행지와 맛집 정보를 한눈에!
</h1>
</section>

<section id="travel">
<h2>인기 여행지 추천</h2>

<div class="cards">

<div class="card">
<img src="https://images.unsplash.com/photo-1517486808906-6ca8b3f04846">
<div class="card-content">
<h3>제주도</h3>
<p>아름다운 자연경관과 다양한 관광 명소가 있는 국내 대표 여행지</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1542051841857-5f90071e7989">
<div class="card-content">
<h3>부산</h3>
<p>해운대, 광안리, 감천문화마을 등 다양한 볼거리를 제공</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb">
<div class="card-content">
<h3>강릉</h3>
<p>경포대와 커피거리로 유명한 동해안 대표 관광도시</p>
</div>
</div>

</div>
</section>

<section id="restaurant">
<h2>맛집 추천</h2>

<div class="cards">

<div class="card">
<img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836">
<div class="card-content">
<h3>부산 해산물 맛집</h3>
<p>대표 메뉴 : 회 정식</p>
<p>평점 : ★★★★★</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4">
<div class="card-content">
<h3>제주 흑돼지</h3>
<p>대표 메뉴 : 흑돼지 구이</p>
<p>평점 : ★★★★☆</p>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1552566626-52f8b828add9">
<div class="card-content">
<h3>강릉 초당순두부</h3>
<p>대표 메뉴 : 순두부 정식</p>
<p>평점 : ★★★★★</p>
</div>
</div>

</div>
</section>

<section id="review">
<h2>여행 후기</h2>

<div class="review">
<h3>제주도 여행 후기</h3>
<p>풍경이 정말 아름다웠고 음식도 맛있었습니다.</p>
<p>★★★★★</p>
</div>

<div class="review">
<h3>부산 여행 후기</h3>
<p>광안대교 야경이 정말 인상적이었습니다.</p>
<p>★★★★☆</p>
</div>

<div class="review">
<h3>강릉 여행 후기</h3>
<p>바다와 커피를 함께 즐길 수 있어 좋았습니다.</p>
<p>★★★★★</p>
</div>

</section>

<section id="contact">
<h2>문의하기</h2>

<div class="contact-form">
<input type="text" placeholder="이름">
<input type="email" placeholder="이메일">
<textarea rows="5" placeholder="문의 내용을 입력하세요"></textarea>
<button>전송</button>
</div>

<br>

<p>이메일 : travelguide@email.com</p>
<p>SNS : Instagram / Facebook</p>

</section>

<footer>
<p>© 2025 Travel Guide. All Rights Reserved.</p>
</footer>

</body>
</html>
