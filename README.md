<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="개인 포트폴리오 페이지 - 자기소개">
    <title>README - 자기소개 페이지</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        p {
            color: #555;
        }
        ul {
            padding-left: 20px;
        }
        code {
            background-color: #eee;
            padding: 2px 4px;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>📝 포트폴리오 페이지</h1>
        <p>이 프로젝트는 개인 포트폴리오 페이지입니다. 빠르고 유연한 정적 사이트 생성기인 <a href="https://gohugo.io/" target="_blank">Hugo</a>를 사용하여 제작되었습니다. 이 페이지에서는 저의 기술 스택, 프로젝트 경험, 개인적인 강점을 소개하고 있습니다.</p>

        <h2>🛠️ 기술 스택</h2>
        <ul>
            <li><strong>프레임워크</strong>: Hugo</li>
            <li><strong>스타일링</strong>: Bootstrap</li>
            <li><strong>언어</strong>: HTML, CSS, JavaScript</li>
            <li><strong>호스팅</strong>: GitHub Pages</li>
        </ul>

        <h2>🚀 시작하기</h2>
        <h3>필수 조건</h3>
        <p>먼저, 로컬 머신에 <a href="https://gohugo.io/getting-started/installing/" target="_blank">Hugo</a>가 설치되어 있어야 합니다.</p>

        <h3>설치 방법</h3>
        <ol>
            <li><strong>저장소 클론:</strong>
                <pre><code>git clone https://github.com/your-username/your-repo-name.git<br>cd your-repo-name</code></pre>
            </li>
            <li><strong>Hugo 서버 실행:</strong>
                <pre><code>hugo server -D</code></pre>
            </li>
            <li>브라우저에서 <code>http://localhost:1313</code>을 열어 사이트를 확인합니다.</li>
        </ol>

        <h3>사이트 빌드하기</h3>
        <p>배포를 위해 정적 파일을 생성하려면 아래 명령어를 실행하세요:</p>
        <pre><code>hugo</code></pre>
        <p>정적 파일은 <code>public/</code> 디렉토리에 생성되며, 이를 웹 서버나 GitHub Pages와 같은 플랫폼에 업로드하여 호스팅할 수 있습니다.</p>

        <h2>📄 자기소개</h2>
        <p>이 페이지는 저의 개발자 여정을 보여주는 포트폴리오 사이트입니다. 제가 작업한 프로젝트들을 살펴보고, 보유한 기술 스택과 경험에 대해 알아보세요.</p>

        <h2>📫 연락처</h2>
        <p>연락을 원하시면 <a href="https://www.linkedin.com/in/your-linkedin" target="_blank">LinkedIn</a> 또는 <a href="mailto:your-email@example.com">이메일</a>로 연락주세요!</p>
    </div>
</body>
</html>
