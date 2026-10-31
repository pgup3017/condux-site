---
title: Condux 지원
home: true
---

<div class="container support-grid">
  <article class="support-main">
    <header id="about" class="project-intro">
      <p class="section-label">소개 및 사용 안내</p>
      <h1>Condux</h1>
      <p class="lead">여러 AI를 한곳에서 사용하는 Mac 앱입니다.</p>
      <p>Claude·GPT와 대화하고, 사진과 파일을 주고받고, 다른 AI에게 답변 검토를 맡길 수 있습니다.</p>
      <div class="intro-actions">
        <a class="button button-primary" href="{{ '/guide.html' | relative_url }}">사용 가이드 읽기</a>
        <a class="button" href="#contact">문의하기</a>
      </div>
    </header>

    <section class="overview" aria-labelledby="overview-title">
      <h2 id="overview-title">기본 정보</h2>
      <table class="facts-table">
        <tbody>
          <tr><th scope="row">사용 환경</th><td>Mac · <a href="{{ '/guide.html#2-두-가지-버전' | relative_url }}">앱스토어판과 직접 설치판 비교</a></td></tr>
          <tr><th scope="row">AI 연결</th><td>Claude API · OpenAI API<br>직접 설치판은 Codex·Claude 구독도 지원합니다.</td></tr>
          <tr><th scope="row">API 비용</th><td>대화마다 작업 예산을 정합니다. 요금은 AI 회사에 직접 지불합니다.</td></tr>
          <tr><th scope="row">대화 기록</th><td>이 Mac에 저장합니다. <a href="{{ '/privacy.html' | relative_url }}">개인정보 처리방침</a></td></tr>
        </tbody>
      </table>
    </section>

    <figure class="app-screen">
      <img src="{{ '/condux-app.png' | relative_url }}" width="1440" height="900" alt="Condux에서 Claude와 대화하고 OpenAI에게 검토를 맡기는 실제 앱 화면">
      <figcaption>Condux 실제 앱 화면</figcaption>
    </figure>

    <section id="start" class="start-section" aria-labelledby="start-title">
      <h2 id="start-title">처음 사용하기</h2>
      <p>처음이라면 아래 순서대로 진행합니다. 각 링크에 자세한 설명이 있습니다.</p>
      <ol class="start-list">
        <li><strong>사용할 AI를 연결합니다.</strong> API 키를 준비하거나 직접 설치판에서 구독 계정을 연결합니다.<br><a href="{{ '/guide.html#3-처음-설정' | relative_url }}">AI 연결 방법</a></li>
        <li><strong>새 대화에서 질문을 보냅니다.</strong> 사진이나 PDF도 함께 보여 줄 수 있습니다.<br><a href="{{ '/guide.html#4-첫-대화' | relative_url }}">첫 대화 보내기</a></li>
        <li><strong>필요한 기능을 더 사용합니다.</strong> 파일을 주고받거나, 다른 AI에게 검토를 맡깁니다.<br><a href="{{ '/guide.html#5-사진파일-주고받기' | relative_url }}">파일 주고받기</a> · <a href="{{ '/guide.html#7-자동-릴레이' | relative_url }}">AI 검토 사용하기</a></li>
      </ol>
    </section>

    <section id="faq" class="faq-section" aria-labelledby="faq-title">
      <h2 id="faq-title">자주 묻는 질문</h2>
      <p>질문을 누르면 답변을 펼치거나 접을 수 있습니다.</p>
  <div class="faq-list">
    <details open><summary>API 키는 어디서 만드나요?</summary><div class="faq-answer"><p>사용할 AI 회사의 사이트에서 계정을 만들고, API Keys 메뉴에서 발급합니다.</p><p><a href="https://platform.claude.com">Claude API 키 만들기 ↗</a><br> <a href="https://platform.openai.com">OpenAI API 키 만들기 ↗</a></p><p>Condux의 ‘API 설정’에 키를 붙여 넣고 저장하면 됩니다. 자세한 순서는 <a href="{{ '/guide.html' | relative_url }}">사용 가이드</a>에서 확인할 수 있습니다.</p></div></details>
    <details><summary>비용은 어떻게 청구되나요?</summary><div class="faq-answer"><p>API 사용 요금은 Anthropic 또는 OpenAI가 사용자에게 직접 청구합니다. Condux 앱 안에서는 결제를 받지 않습니다.</p><p>앱에 표시되는 비용은 공식 요율표로 계산한 추정치이며, 실제 청구 금액과 다를 수 있습니다.</p></div></details>
    <details><summary>앱스토어판과 직접 설치판은 무엇이 다른가요?</summary><div class="faq-answer"><p>앱스토어판은 본인의 API 키로 AI와 대화합니다. 직접 설치판에서는 Codex·Claude 구독 연결, 프로젝트 폴더에서 코드 고치기, 외부 도구 연결도 사용할 수 있습니다.</p><p><a href="{{ '/guide.html' | relative_url }}">사용 가이드에서 두 버전 비교하기 →</a></p></div></details>
    <details><summary>대화 기록은 어디에 저장되나요?</summary><div class="faq-answer"><p>대화 기록은 이 Mac의 앱 데이터 폴더에 저장됩니다. 개발자는 대화 기록을 볼 수 없습니다.</p><p>AI에게 보내는 메시지는 선택한 AI 서비스로 전송됩니다. 자세한 내용은 <a href="{{ '/privacy.html' | relative_url }}">개인정보 처리방침</a>을 확인해 주세요.</p></div></details>
    <details><summary>API 예산을 다 쓰면 어떻게 되나요?</summary><div class="faq-answer"><p>해당 대화의 API 전송이 멈춥니다. 계속하려면 앱에서 ‘예산 +$1’을 누르거나 새 대화를 시작합니다. 구독 사용 한도가 끝났다고 유료 API로 자동 전환하지 않습니다.</p></div></details>
  </div>
    </section>

    <section id="contact" class="contact-section" aria-labelledby="contact-title">
      <h2 id="contact-title">문의</h2>
      <p>문제나 제안은 GitHub 이슈로 남겨 주세요. 어떤 화면에서 무엇을 했는지 함께 적어 주시면 도움이 됩니다.</p>
      <p><a href="https://github.com/pgup3017/condux-site/issues">GitHub에서 문의하기</a></p>
      <p class="muted small">문의를 남기려면 GitHub 계정이 필요합니다.</p>
    </section>
  </article>

  <aside class="support-sidebar" aria-label="지원 안내">
    <section>
      <h2>이 페이지</h2>
      <nav aria-label="페이지 목차">
        <a href="#about">소개</a>
        <a href="#overview-title">기본 정보</a>
        <a href="#start">처음 사용하기</a>
        <a href="#faq">자주 묻는 질문</a>
        <a href="#contact">문의</a>
      </nav>
    </section>
    <section>
      <h2>문서</h2>
      <ul>
        <li><a href="{{ '/guide.html' | relative_url }}">사용 가이드</a></li>
        <li><a href="{{ '/privacy.html' | relative_url }}">개인정보 처리방침</a></li>
      </ul>
    </section>
    <section>
      <h2>AI 서비스</h2>
      <ul>
        <li><a href="https://platform.claude.com">Claude API</a></li>
        <li><a href="https://platform.openai.com">OpenAI API</a></li>
      </ul>
      <p class="muted small">각 서비스의 계정과 API 키는 직접 준비합니다.</p>
    </section>
  </aside>
</div>
