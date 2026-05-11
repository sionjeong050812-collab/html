<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>(주)비에이텍 - 워터펌프 제작·설치·수리 전문기업</title>
    <style>
        /* 기본 스타일 초기화 */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Pretendard', sans-serif; color: #333; line-height: 1.6; }
        a { text-decoration: none; color: inherit; }
        ul { list-style: none; }

        /* 헤더 & 네비게이션 */
        header {
            width: 100%;
            height: 80px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 5%;
            position: fixed;
            top: 0;
            background: rgba(255, 255, 255, 0.95);
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            z-index: 1000;
        }
        .logo h1 { color: #0056b3; font-size: 1.5rem; }
        nav ul { display: flex; gap: 30px; }
        nav ul li a { font-weight: 500; transition: color 0.3s; }
        nav ul li a:hover { color: #00a8ff; }

        /* 메인 히어로 섹션 (깨끗한 물 이미지 강조) */
        .hero {
            height: 100vh;
            background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)), 
                        url('https://images.unsplash.com/photo-1518152006812-edab29b069ac?auto=format&fit=crop&q=80&w=1920') no-repeat center/cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
            padding-top: 80px;
        }
        .hero h2 { font-size: 3.5rem; margin-bottom: 20px; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
        .hero p { font-size: 1.2rem; margin-bottom: 30px; }
        .btn-more {
            padding: 15px 40px;
            background: #00a8ff;
            color: #fff;
            border-radius: 30px;
            font-weight: bold;
            transition: transform 0.3s;
        }
        .btn-more:hover { transform: translateY(-5px); background: #0086cc; }

        /* 푸터 정보 */
        footer {
            background: #222;
            color: #ccc;
            padding: 40px 5%;
            font-size: 0.9rem;
        }
        .footer-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .footer-info h4 { color: #fff; margin-bottom: 15px; }
        .copyright {
            text-align: center;
            margin-top: 30px;
            border-top: 1px solid #444;
            padding-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">
            <h1>(주)비에이텍</h1>
        </div>
        <nav>
            <ul>
                <li><a href="intro.html">기업소개</a></li>
                <li><a href="product.html">주요제품</a></li>
                <li><a href="equipment.html">장비</a></li>
                <li><a href="sales_history.html">업력</a></li>
                <li><a href="map.html">찾아오시는 길</a></li>
                <li><a href="inquiry.html">문의</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h2>물, 그 이상의 가치를 만듭니다</h2>
        <p>(주)비에이텍은 워터펌프 제작, 설치, 수리 분야의 기술력을 바탕으로 깨끗한 수자원 관리를 선도합니다.</p>
        <a href="product.html" class="btn-more">제품 둘러보기</a>
    </section>

    <footer>
        <div class="footer-content">
            <div class="footer-info">
                <h4>(주)비에이텍</h4>
                <p>주소: 춘천시 퇴계로 1번지</p>
                <p>담당자: aaa@naver.com</p>
            </div>
            <div class="footer-info">
                <h4>Contact Us</h4>
                <p>TEL : 033-248-1111</p>
                <p>FAX : 033-248-1234</p>
            </div>
            <div class="footer-info">
                <h4>Business</h4>
                <p>워터펌프 제작 / 설치 / 수리 전문</p>
            </div>
        </div>
        <div class="copyright">
            &copy; 2026 (주)비에이텍. All Rights Reserved.
        </div>
    </footer>

</body>
</html>