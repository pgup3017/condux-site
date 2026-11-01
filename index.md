---
title: Condux
home: true
---

<section class="hero">
<div class="container hero-text">
<p class="eyebrow">macOS 14 이상 · Apple Silicon · 오픈소스</p>
<h1>여러 AI를 한 화면에서<br>부리는 Mac 작업실</h1>
<p class="lead">Claude, GPT, Codex에게 일을 맡기고, 서로 검토시키고, 결과는 내가 승인합니다. 키와 로그인은 내 Mac에 그대로 둡니다.</p>
<div class="actions">
<a class="button primary" href="https://github.com/pgup3017/condux-app/releases/latest">Mac용 내려받기</a>
<a class="button" href="https://github.com/pgup3017/condux-app">GitHub</a>
<a class="button" href="{{ '/guide.html' | relative_url }}">사용 가이드</a>
</div>
</div>
<div class="container hero-shot">
<picture>
<source srcset="{{ '/images/conversation-light.png' | relative_url }}" media="(prefers-color-scheme: light)">
<img src="{{ '/images/conversation-dark.png' | relative_url }}" width="1440" height="900" alt="Condux 대화 화면. 왼쪽에 대화 목록, 가운데에 웹 검색과 출처가 붙은 답변, 릴레이 검토 기록, 아래에 입력창과 컨텍스트 사용률이 보입니다.">
</picture>
</div>
</section>

<section id="features" class="container features">
<article class="feature">
<div class="feature-text">
<h2>대화는 한곳에서</h2>
<p>API 키로도, 쓰고 있는 구독으로도 연결합니다. 사진과 PDF, ZIP을 붙이면 그 내용을 보고 답합니다. 최신 정보가 필요하면 웹을 검색하고 출처를 함께 보여 줍니다.</p>
<ul>
<li>Claude API · OpenAI API · Claude 구독 · Codex</li>
<li>복사한 이미지를 ⌘V로 바로 첨부</li>
<li>밝은 화면과 어두운 화면</li>
</ul>
</div>
<img class="shot" loading="lazy" src="{{ '/images/start-dark.png' | relative_url }}" width="1440" height="900" alt="새 대화 시작 화면. 가운데 입력창과 예시 질문이 있습니다.">
</article>

<article class="feature flip">
<div class="feature-text">
<h2>AI끼리 만들고 검토합니다</h2>
<p>요청 하나를 릴레이로 보내면 한 AI가 만들고 다른 AI가 검토합니다. 고칠 점이 있으면 자동으로 돌려보내고, 승인되거나 횟수 한도에 닿으면 멈춥니다. 매 단계 버튼을 누를 필요가 없습니다.</p>
</div>
<img class="shot" loading="lazy" src="{{ '/images/conversation-light.png' | relative_url }}" width="1440" height="900" alt="릴레이 시작, 구현 답변, 받은 파일, 검토자 승인 기록이 차례로 보이는 대화 화면">
</article>

<article class="feature">
<div class="feature-text">
<h2>GitHub와 내 프로그램까지</h2>
<p>직접 설치판에서는 프로젝트 폴더를 맡길 수 있습니다. 코드를 고치고, 빌드하고, 커밋과 PR까지 시키세요. 다른 앱을 여는 일도, Chrome에서 페이지를 읽고 누르는 일도 맡길 수 있습니다.</p>
<ul>
<li>GitHub CLI 로그인 그대로 사용</li>
<li>Figma, Mobbin, Xcode, Chrome 도구(MCP)</li>
<li>명령은 실행 전마다 승인 카드로 확인</li>
</ul>
</div>
<img class="shot sheet" loading="lazy" src="{{ '/images/connections-light.png' | relative_url }}" width="600" height="680" alt="연결 관리 창. AI 연결, 작업 폴더, GitHub, 다른 프로그램 제어, 로컬 AI 항목이 보입니다.">
</article>

<article class="feature flip">
<div class="feature-text">
<h2>얼마나 썼는지 보입니다</h2>
<p>대화마다 컨텍스트가 얼마나 찼는지, 토큰을 얼마나 주고받았는지 봅니다. API 대화는 예산을 정해 두면 넘지 않고 멈춥니다. 구독에서 유료 API로 몰래 넘어가지 않습니다.</p>
</div>
<img class="shot small" loading="lazy" src="{{ '/images/usage-dark.png' | relative_url }}" alt="사용량 창. 컨텍스트 19퍼센트, 주고받은 토큰, 예상 비용과 예산이 표시됩니다.">
</article>
</section>

<section class="band">
<div class="container promises">
<div><h3>키는 내 Mac에</h3><p>API 키는 키체인에만 저장합니다. 구독 로그인 토큰은 앱이 읽지 않습니다. Condux에는 별도 서버가 없습니다.</p></div>
<div><h3>실행 전에 묻습니다</h3><p>명령은 자동으로 허용하지 않습니다. 파일을 고치기 전에는 원본을 백업해 되돌릴 수 있습니다.</p></div>
<div><h3>코드를 볼 수 있습니다</h3><p>무엇을 어디로 보내는지 소스 코드로 직접 확인할 수 있습니다.</p></div>
</div>
</section>

<section id="versions" class="container section">
<h2>두 가지 판</h2>
<div class="table-wrap">
<table>
<thead><tr><th scope="col"></th><th scope="col">GitHub판</th><th scope="col">앱스토어판</th></tr></thead>
<tbody>
<tr><th scope="row">Claude API · OpenAI API</th><td>있음</td><td>있음</td></tr>
<tr><th scope="row">웹 검색 · 파일 첨부 · 릴레이</th><td>있음</td><td>있음</td></tr>
<tr><th scope="row">Claude 구독 · Codex 연결</th><td>있음</td><td>없음</td></tr>
<tr><th scope="row">프로젝트 폴더 · GitHub</th><td>있음</td><td>없음</td></tr>
<tr><th scope="row">Chrome · 다른 프로그램 제어</th><td>있음</td><td>없음</td></tr>
<tr><th scope="row">Figma · Mobbin · Xcode 도구</th><td>있음</td><td>없음</td></tr>
<tr><th scope="row">로컬 AI (시험 기능)</th><td>Apple Silicon</td><td>없음</td></tr>
<tr><th scope="row">설치</th><td>내려받기 또는 소스 빌드</td><td>Mac App Store</td></tr>
</tbody>
</table>
</div>
<p class="muted">앱스토어 앱은 샌드박스 안에서 돌기 때문에 다른 프로그램을 조작할 수 없습니다.</p>
</section>

<section id="start" class="container section">
<h2>GitHub판 설치</h2>
<p><a href="https://github.com/pgup3017/condux-app/releases/latest">최신 버전</a>을 받아 압축을 풀고 <code>Condux.app</code>을 응용 프로그램 폴더로 옮기면 됩니다. Apple 공증을 받은 파일입니다.</p>
<p>소스에서 직접 빌드하려면 Xcode를 설치하고 아래 명령을 실행합니다.</p>
<pre><code>git clone https://github.com/pgup3017/condux-app.git
cd condux-app
scripts/build-local.sh</code></pre>
<p>처음 켠 뒤에는 왼쪽 아래 연결 상태를 눌러 <strong>연결 관리</strong>를 열고, AI를 하나 이상 연결하면 됩니다. 자세한 순서는 <a href="{{ '/guide.html' | relative_url }}">사용 가이드</a>에 있습니다.</p>
</section>

<section id="faq" class="container section faq">
<h2>자주 묻는 질문</h2>
<details><summary>구독과 API 키 중 무엇을 써야 하나요?</summary><p>이미 Claude나 ChatGPT 구독이 있고 GitHub판을 쓴다면 구독으로 시작하세요. 쓴 만큼 내는 방식이 좋거나 앱스토어판을 쓴다면 API 키를 사용합니다. 앱은 구독에서 API로 자동 전환하지 않습니다.</p></details>
<details><summary>API 비용은 어떻게 청구되나요?</summary><p>각 AI 회사가 키 주인에게 직접 청구합니다. 앱에 보이는 금액은 공식 요율로 계산한 추정치라 실제 청구와 다를 수 있습니다. 웹 검색은 1회당 약 $0.01과 결과 토큰 비용이 더해집니다.</p></details>
<details><summary>대화 기록은 어디에 저장되나요?</summary><p>이 Mac에만 저장합니다. 메시지는 사용자가 고른 AI 서비스로만 전송됩니다. 자세한 내용은 <a href="{{ '/privacy.html' | relative_url }}">개인정보 처리방침</a>을 보세요.</p></details>
<details><summary>AI가 마음대로 명령을 실행하나요?</summary><p>아닙니다. 명령은 실행 전마다 승인 카드가 뜹니다. 파일 수정 자동 허용을 켜도 작업 폴더 안의 파일 수정에만 적용되고, 명령은 계속 묻습니다.</p></details>
<details><summary>GitHub에는 어떻게 연결하나요?</summary><p>GitHub CLI(<code>gh</code>)에 로그인되어 있으면 앱이 그 상태를 보여 줍니다. 로그인은 터미널에서 직접 하고, 앱은 토큰을 읽지 않습니다.</p></details>
</section>
