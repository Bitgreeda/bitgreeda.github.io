---
layout: home
title: "Bitgreeda"
classes: [full-width-page]
---

<style>
  body {
    background-color: white;
    padding-bottom: 0;
  }

  /* Hero Image: 전체 표시 + 고정 높이(레터박스 허용) */
  .main-hero {
    width: 100%;
    height: 690px;            /* ← 필요 시 높이 조정 */
    overflow: hidden;
    margin: 0;                /* 푸터와의 간격 제거 */
  }
  .main-hero img {
    width: 100%;
    height: 100%;
    object-fit: contain;      /* 전체 표시, 잘림 없음 */
    object-position: center;  /* 중앙 정렬 */
    display: block;
    background: #f5f5f5;      /* 여백 배경색(원치 않으면 제거 가능) */
  }

  /* Footer */
  .site-footer {
    background: #f8f8f8;
    border-top: 1px solid #eee;
    padding: 24px 16px;
    font-size: 0.92em;
    color: #555;
    margin: 0;                /* 위쪽 여백 제거 */
  }
  /* 이미지 바로 아래에 딱 붙도록 보장 */
  .main-hero + .site-footer { margin-top: 0; }

  .site-footer .container {
    max-width: 1080px;
    margin: 0 auto;
    text-align: center;
    line-height: 1.7;
  }
  /* 푸터 상단 브랜드 타이틀 */
  .site-footer .brand {
    font-size: 2.5em;
    font-weight: 800;
    letter-spacing: 0.02em;
    color: #222;
    margin: 10px 0 40px;   /* ↑ 위아래 간격 추가 */
    padding: 6px 0; 
  }

  .site-footer a {
    color: inherit;
    text-decoration: none;
  }
  .site-footer .meta p {
    margin: 8px 0;
  }
  .site-footer .meta strong {
    display: block; 
    font-weight: bold;
    color: #333; /* 항목명 색상 */
  }
  .site-footer .meta span {
    display: block;
    color: #666; /* 내용 색상 */
  }
  .site-footer .copy {
    margin-top: 50px;
    margin-bottom: 50px;
    font-size: 1.05em; /* 크기 약간 키움 */
    font-weight: normal; /* 굵게 */
    color: #444; 
    
  }
</style>

<div class="main-hero">
  <img src="/assets/images/bg_main.jpg" alt="Bitgreeda Main" />
</div>

<footer class="site-footer">
  <div class="container">
    <p class="brand">BITGREEDA</p>
    <div class="meta">
      <p><strong>CEO</strong><span>Kwanghyun Kim</span></p>
      <p><strong>Business Registration Number</strong><span>176-10-01213</span></p>
      <p><strong>Mail-Order Business Registration Number</strong><span>2025-SeoulGangseo-0464</span></p>
      <p><strong>Address</strong><span>Deungchon-ro 13ba-gil, Gangseo-gu, Seoul, Republic of Korea</span></p>
      <p><strong>E-mail</strong><span><a href="mailto:support@bitgreeda.com">support@bitgreeda.com</a></span></p>
    </div>
    <p class="copy">© 2025 Bitgreeda. All rights reserved.</p>
  </div>
</footer>
