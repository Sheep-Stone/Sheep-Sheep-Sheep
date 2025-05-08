<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>나의 첫 웹사이트</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #4a90e2;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    section {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }
    .button {
      display: inline-block;
      background-color: #4a90e2;
      color: white;
      padding: 0.75rem 1.5rem;
      text-decoration: none;
      border-radius: 8px;
      transition: background-color 0.3s ease;
    }
    .button:hover {
      background-color: #357ABD;
    }
    footer {
      background-color: #eee;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>안녕하세요!</h1>
    <p>이것은 나의 첫 번째 웹사이트입니다</p>
  </header>

  <section>
    <h2>소개</h2>
    <p>이 웹사이트는 HTML과 CSS로 만든 간단한 예시입니다. 구조와 스타일을 분리하지 않고 한 파일에 담았습니다.</p>
    <a href="#" class="button">더 알아보기</a>
  </section>

  <footer>
    © 2025 나의 웹사이트. 모든 권리 보유.
  </footer>
</body>
</html>

