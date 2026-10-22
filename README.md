# chaewooda1[승인썸네일스튜디오 (1).html](https://github.com/user-attachments/files/33803120/1.html)
<!doctype html>
<html lang="ko">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<style>html,body{margin:0}img{max-width:100%}[hidden]{display:none!important}</style>
<title>승인 썸네일 스튜디오</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bagel+Fat+One&family=Black+Han+Sans&family=Do+Hyeon&family=Gaegu:wght@700&family=Gasoek+One&family=Gothic+A1:wght@900&family=Gugi&family=Hi+Melody&family=IBM+Plex+Mono:wght@500&family=IBM+Plex+Sans+KR:wght@400;500;600;700&family=Jua&family=Nanum+Gothic:wght@800&family=Nanum+Myeongjo:wght@800&family=Nanum+Pen+Script&family=Noto+Sans+KR:wght@500;700;800;900&family=Sunflower:wght@700&display=swap">
<style>
/* Layout: one working column — input bench on top, then analysis, five thumbnail proofs, five ad-copy sets, and the policy sheet. */
:root{
  --bg:#f2f3ef; --surface:#ffffff; --surface-2:#f7f8f5; --ink:#15181c; --muted:#5a626b; --line:#dadde0;
  --accent:#0c7550; --accent-ink:#ffffff; --accent-soft:#e1f1e8;
  --warn:#9a5600; --warn-soft:#fff1da; --bad:#bf2418; --bad-soft:#fde6e2; --good:#0c7550; --good-soft:#e1f1e8;
  --navy:#0c1489; --focus:#1d5fd1; --shadow:0 1px 2px rgba(20,24,28,.06),0 6px 24px rgba(20,24,28,.06);
  --ui:"IBM Plex Sans KR","Apple SD Gothic Neo","Malgun Gothic",system-ui,sans-serif;
  --display:"Do Hyeon","IBM Plex Sans KR","Apple SD Gothic Neo",sans-serif;
  --mono:"IBM Plex Mono",ui-monospace,SFMono-Regular,Menlo,monospace;
  --r:10px;
}
@media (prefers-color-scheme: dark){ :root:not([data-theme="light"]){
  --bg:#0f1113; --surface:#171a1d; --surface-2:#1d2125; --ink:#eceef0; --muted:#9aa2aa; --line:#2b3035;
  --accent:#38c98b; --accent-ink:#04231a; --accent-soft:#12301f;
  --warn:#f0a63f; --warn-soft:#33250e; --bad:#ff6b5d; --bad-soft:#3a1613; --good:#38c98b; --good-soft:#12301f;
  --navy:#8d95ff; --focus:#7aa7ff; --shadow:0 1px 2px rgba(0,0,0,.4),0 8px 28px rgba(0,0,0,.35); color-scheme:dark }}
:root[data-theme="dark"]{
  --bg:#0f1113; --surface:#171a1d; --surface-2:#1d2125; --ink:#eceef0; --muted:#9aa2aa; --line:#2b3035;
  --accent:#38c98b; --accent-ink:#04231a; --accent-soft:#12301f;
  --warn:#f0a63f; --warn-soft:#33250e; --bad:#ff6b5d; --bad-soft:#3a1613; --good:#38c98b; --good-soft:#12301f;
  --navy:#8d95ff; --focus:#7aa7ff; --shadow:0 1px 2px rgba(0,0,0,.4),0 8px 28px rgba(0,0,0,.35); color-scheme:dark }

*{box-sizing:border-box}
html,body{background:var(--bg);color:var(--ink)}
body{font-family:var(--ui);font-size:15px;line-height:1.55;-webkit-font-smoothing:antialiased}
.wrap{max-width:1240px;margin:0 auto;padding-left:max(16px,env(safe-area-inset-left,0px));padding-right:max(16px,env(safe-area-inset-right,0px))}
h1,h2,h3{margin:0;text-wrap:balance}
button,input,textarea,select{font:inherit;color:inherit}
:focus-visible{outline:2px solid var(--focus);outline-offset:2px}

/* header */
.top{border-bottom:1px solid var(--line);background:var(--surface)}
.top .wrap{display:flex;flex-wrap:wrap;gap:12px 24px;align-items:center;justify-content:space-between;padding-block:18px}
.brand{display:flex;gap:14px;align-items:center;min-width:0}
.mark{flex:none;width:44px;height:44px;border-radius:10px;background:#0c1489;display:grid;place-items:center}
.brand h1{font-family:var(--display);font-weight:400;font-size:30px;letter-spacing:.01em;line-height:1.1}
.brand p{margin:2px 0 0;color:var(--muted);font-size:14px}
.engine{display:inline-flex;align-items:center;gap:8px;font-size:13px;padding:6px 12px;border-radius:999px;border:1px solid var(--line);background:var(--surface-2);color:var(--muted)}
.engine i{width:8px;height:8px;border-radius:50%;background:var(--muted)}
.engine.on{color:var(--good);border-color:color-mix(in srgb,var(--good) 35%,var(--line))}
.engine.on i{background:var(--good)}

main{padding-block:24px 64px;display:grid;gap:28px}
.card{background:var(--surface);border:1px solid var(--line);border-radius:var(--r);box-shadow:var(--shadow)}
.sec-head{display:flex;flex-wrap:wrap;gap:10px 16px;align-items:end;justify-content:space-between;margin-bottom:12px}
.sec-head h2{font-size:20px;font-weight:700}
.sec-head p{margin:2px 0 0;color:var(--muted);font-size:14px}
.step{font-family:var(--mono);font-size:12px;color:var(--muted);letter-spacing:.06em;text-transform:uppercase}

/* inputs */
.bench{display:grid;grid-template-columns:minmax(0,1.6fr) minmax(0,1fr);gap:16px;align-items:start}
@media (max-width:900px){.bench{grid-template-columns:minmax(0,1fr)}}
.pane{padding:18px;display:grid;gap:14px;align-content:start}
label.lab{font-weight:600;font-size:14px;display:block;margin-bottom:6px}
.hint{color:var(--muted);font-size:13px}
textarea,input[type=text]{width:100%;background:var(--surface-2);border:1px solid var(--line);border-radius:8px;padding:10px 12px}
textarea{min-height:240px;resize:vertical;line-height:1.6}
.row2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
@media (max-width:520px){.row2{grid-template-columns:1fr}}
.drop{position:relative;border:1.5px dashed color-mix(in srgb,var(--muted) 45%,transparent);border-radius:10px;padding:14px;display:flex;gap:14px;align-items:center;background:var(--surface-2);cursor:pointer;transition:border-color .15s,background .15s}
.drop:hover,.drop.over{border-color:var(--accent);background:var(--accent-soft)}
.drop input{position:absolute;inset:0;opacity:0;cursor:pointer;width:100%}
.drop .thumb{flex:none;width:76px;height:76px;border-radius:8px;background:repeating-conic-gradient(#d7dade 0 25%,#f4f5f6 0 50%) 0 0/14px 14px;overflow:hidden;display:grid;place-items:center}
.drop .thumb img,.drop .thumb canvas{width:100%;height:100%;object-fit:contain}
.drop strong{display:block;font-size:14px}
.drop span{font-size:13px;color:var(--muted)}
.status{font-size:13px;padding:8px 10px;border-radius:8px;background:var(--surface-2);color:var(--muted)}
.status.good{background:var(--good-soft);color:var(--good)}
.status.warn{background:var(--warn-soft);color:var(--warn)}
.status.busy{background:var(--surface-2);color:var(--ink)}
.opts{display:grid;gap:10px}
.opt{display:flex;align-items:center;gap:10px;font-size:14px}
.opt input[type=range]{flex:1;accent-color:var(--accent)}
.opt output{font-family:var(--mono);font-size:12px;color:var(--muted);min-width:42px;text-align:right}
.chk{display:flex;gap:8px;align-items:center;font-size:14px}
.chk input{accent-color:var(--accent);width:16px;height:16px}

.actions{display:flex;flex-wrap:wrap;gap:12px;align-items:center}
.btn{display:inline-flex;align-items:center;gap:8px;border:1px solid var(--line);background:var(--surface);border-radius:8px;padding:9px 14px;font-size:14px;font-weight:600;cursor:pointer}
.btn:hover{border-color:var(--ink)}
.btn.primary{background:var(--accent);color:var(--accent-ink);border-color:var(--accent);padding:13px 22px;font-size:16px}
.btn.primary:hover{filter:brightness(1.06)}
.btn:disabled{opacity:.55;cursor:progress}
.btn.small{padding:6px 10px;font-size:13px;font-weight:500}
.progress{font-size:14px;color:var(--muted)}
.progress b{color:var(--ink);font-weight:600}

/* analysis */
.analysis{padding:18px;display:grid;gap:14px}
.facts{display:grid;grid-template-columns:repeat(4,minmax(0,1fr));gap:10px}
@media (max-width:820px){.facts{grid-template-columns:repeat(2,minmax(0,1fr))}}
.fact{border:1px solid var(--line);border-radius:8px;padding:10px 12px;background:var(--surface-2);min-width:0}
.fact dt{font-size:12px;color:var(--muted)}
.fact dd{margin:2px 0 0;font-weight:600;overflow-wrap:anywhere}
.chips{display:flex;flex-wrap:wrap;gap:6px}
.chip{font-size:13px;padding:3px 10px;border-radius:999px;background:var(--accent-soft);color:var(--good)}
.summary{margin:0;color:var(--ink)}
.risk-wrap{overflow-x:auto}
table.risk{width:100%;border-collapse:collapse;font-size:14px;min-width:560px}
table.risk th{text-align:left;font-size:12px;color:var(--muted);font-weight:600;padding:6px 8px;border-bottom:1px solid var(--line)}
table.risk td{padding:8px;border-bottom:1px solid var(--line);vertical-align:top}
.src{font-size:12px;color:var(--muted)}

/* severity pills */
.pill{display:inline-flex;align-items:center;gap:6px;font-size:12px;font-weight:600;padding:3px 9px;border-radius:999px;white-space:nowrap}
.pill.ok{background:var(--good-soft);color:var(--good)}
.pill.warn{background:var(--warn-soft);color:var(--warn)}
.pill.bad{background:var(--bad-soft);color:var(--bad)}
mark.hl{background:var(--bad-soft);color:var(--bad);border-radius:3px;padding:0 2px}
mark.hl.w{background:var(--warn-soft);color:var(--warn)}

/* thumbnails */
.tgrid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px}
@media (max-width:900px){.tgrid{grid-template-columns:minmax(0,1fr)}}
.tcard{display:grid;gap:10px;padding:12px;align-content:start}
.tc-head{display:flex;gap:10px;align-items:center;flex-wrap:wrap}
.tc-head .num{font-family:var(--display);font-size:22px;line-height:1}
.tc-head .tname{font-weight:600}
.tc-head .ref{font-size:12px;color:var(--muted)}
.tc-head .pill{margin-left:auto}
.tcard canvas{width:100%;height:auto;aspect-ratio:16/9;max-width:100%;display:block;border-radius:6px;background:#111;cursor:grab}
.tcard canvas.dragging{cursor:grabbing}
@media (pointer:coarse){.tcard canvas{cursor:auto}}
.pctl{display:grid;gap:8px;padding:10px 12px;border:1px solid var(--line);border-radius:8px;background:var(--surface-2)}
.pctl-head{display:flex;flex-wrap:wrap;gap:4px 12px;justify-content:space-between;align-items:baseline;font-size:13px}
.pctl-head span{color:var(--muted);font-size:12px}
@media (pointer:coarse){.pctl-head span{display:none}}
.pctl-row{display:grid;grid-template-columns:repeat(3,minmax(0,1fr)) auto;gap:8px 14px;align-items:end}
@media (max-width:620px){.pctl-row{grid-template-columns:minmax(0,1fr)}}
.pc{display:grid;grid-template-columns:minmax(0,1fr) auto;gap:2px 8px;min-width:0;font-size:12px;color:var(--muted)}
.pc input{grid-column:1/-1;width:100%;margin:0;accent-color:var(--accent)}
.pc output{font-family:var(--mono);color:var(--ink)}
.issues{display:grid;gap:4px;font-size:13px}
.issues .it{display:flex;gap:8px;align-items:baseline}
.issues .it b{font-weight:600}
.imgchk{font-size:12px;color:var(--muted)}
.tips h3{font-size:17px}
.tips ol{margin:0;padding-left:20px;display:grid;gap:8px;font-size:14px}
.tips li::marker{font-family:var(--mono);color:var(--muted)}
details.edit{border-top:1px solid var(--line);padding-top:8px}
details.edit summary{cursor:pointer;font-weight:600;font-size:14px}
.fields{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:8px 12px;margin-top:10px}
@media (max-width:520px){.fields{grid-template-columns:minmax(0,1fr)}}
.fields .f{min-width:0}
.fields .f.wide{grid-column:1/-1}
.fields label{display:flex;justify-content:space-between;font-size:12px;color:var(--muted);margin-bottom:3px}
.fields label .n{font-family:var(--mono)}
.fields label .n.over{color:var(--bad)}
.fields input,.fields select{padding:7px 10px;font-size:14px;width:100%;background:var(--surface-2);border:1px solid var(--line);border-radius:8px}
.fontbar{display:flex;flex-wrap:wrap;gap:8px 12px;align-items:center;padding:10px 12px;border:1px solid var(--line);border-radius:var(--r);background:var(--surface);margin-bottom:14px;font-size:14px}
.fontbar label{font-weight:600}
.fontbar select{padding:7px 10px;background:var(--surface-2);border:1px solid var(--line);border-radius:8px;min-width:0;max-width:100%}
.fontbar .hint{flex-basis:100%}
.fontbar .upl{position:relative;overflow:hidden}
.fontbar .upl input{position:absolute;inset:0;opacity:0;cursor:pointer}
.dl{display:flex;flex-wrap:wrap;gap:8px}

/* ads */
.ads{display:grid;gap:14px}
.adcard{padding:14px 16px;display:grid;gap:8px}
.adcard h3{font-size:16px;display:flex;gap:10px;align-items:center;flex-wrap:wrap}
.adcard h3 .angle{font-weight:500;color:var(--muted);font-size:14px}
.adcard h3 .pill{margin-left:auto}
.adrow{display:grid;grid-template-columns:92px minmax(0,1fr) 64px auto;gap:10px;align-items:center}
@media (max-width:620px){.adrow{grid-template-columns:minmax(0,1fr) auto auto}.adrow .k{grid-column:1/-1}}
.adrow .k{font-size:13px;font-weight:600;color:var(--muted)}
.adrow .k small{display:block;font-weight:400;font-size:11px}
.adrow input{padding:8px 10px;font-size:15px}
.adrow .cnt{font-family:var(--mono);font-size:12px;color:var(--muted);text-align:right}
.adrow .cnt.over{color:var(--bad)}

/* policy */
details.policy{padding:16px 18px}
details.policy summary{cursor:pointer;font-weight:700}
.pgrid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px;margin-top:14px}
@media (max-width:820px){.pgrid{grid-template-columns:minmax(0,1fr)}}
.pbox{border:1px solid var(--line);border-radius:8px;padding:12px;font-size:14px;background:var(--surface-2)}
.pbox h4{margin:0 0 6px;font-size:14px}
.pbox ul{margin:0;padding-left:18px}
.pbox.no h4{color:var(--bad)} .pbox.yes h4{color:var(--good)}

.toast{position:fixed;left:50%;bottom:calc(20px + env(safe-area-inset-bottom,0px));transform:translateX(-50%);background:var(--ink);color:var(--bg);padding:10px 16px;border-radius:8px;font-size:14px;z-index:30;max-width:calc(100% - 32px)}
@media (prefers-reduced-motion:no-preference){.tcard canvas{transition:opacity .2s}}
.busy canvas{opacity:.55}
.sr{position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0 0 0 0)}
</style>
</head>
<body>
<header class="top">
  <div class="wrap">
    <div class="brand">
      <div class="mark" aria-hidden="true"><svg width="26" height="26" viewBox="0 0 26 26"><path d="M4 13.5l5.5 5.5L22 6.5" fill="none" stroke="#FFE600" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/></svg></div>
      <div>
        <h1>승인 썸네일 스튜디오</h1>
        <p>대본을 넣으면 클릭베이트 정책 가이드 기준으로 썸네일 5종과 광고 제목 5세트를 만들어요.</p>
      </div>
    </div>
    <div class="engine" id="engine"><i></i><span>분석 엔진 확인 중…</span></div>
  </div>
</header>

<main class="wrap">
  <section aria-labelledby="s1">
    <div class="sec-head"><div><div class="step">Step 1</div><h2 id="s1">대본과 인물 사진 넣기</h2></div></div>
    <div class="bench">
      <div class="card pane">
        <div>
          <label class="lab" for="script">대본</label>
          <textarea id="script" spellcheck="false"></textarea>
          <div class="hint" id="scriptHint">예시 대본이 들어 있어요. 지우고 실제 대본을 붙여넣으세요.</div>
        </div>
        <div class="row2">
          <div><label class="lab" for="brand">제품·브랜드명 <span class="hint">(선택)</span></label><input type="text" id="brand" placeholder="예: 슬로벨라"></div>
          <div><label class="lab" for="topic">핵심 주제 <span class="hint">(선택)</span></label><input type="text" id="topic" placeholder="비우면 대본에서 자동 추출"></div>
        </div>
      </div>
      <div class="card pane">
        <div>
          <span class="lab">인물 사진 <span class="hint">— 여기에 넣은 사진이 시안 5개의 인물로 들어가요</span></span>
          <label class="drop" id="personDrop">
            <input type="file" id="personFile" accept="image/*" aria-label="인물 사진 선택">
            <div class="thumb" id="personThumb"><svg width="34" height="34" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.6" opacity=".55"><circle cx="12" cy="8" r="4"/><path d="M4 21c1.5-4 4.5-6 8-6s6.5 2 8 6"/></svg></div>
            <div><strong>사진을 끌어다 놓거나 눌러서 선택</strong><span>복사한 사진은 Ctrl+V로 붙여넣어도 돼요. 배경은 자동으로 지워요.</span></div>
          </label>
        </div>
        <div class="status" id="personStatus" role="status">지금은 예시 실루엣이 들어가 있어요.</div>
        <button class="btn small" id="personRetry" type="button" hidden>자동 누끼 다시 시도</button>
        <div class="opts">
          <label class="chk"><input type="checkbox" id="pFlip"> 인물 좌우 반전 (시안 5개 모두)</label>
          <div class="hint">인물 크기와 위치는 Step 3에서 시안마다 따로 맞출 수 있어요.</div>
        </div>
      </div>
    </div>
  </section>

  <div class="actions">
    <button class="btn primary" id="go" type="button">대본 분석하고 시안 5개 만들기</button>
    <button class="btn" id="stop" type="button" hidden>분석 멈추기</button>
    <span class="progress" id="progress" role="status"></span>
  </div>

  <section aria-labelledby="s2">
    <div class="sec-head"><div><div class="step">Step 2</div><h2 id="s2">대본 분석</h2></div><span class="src" id="anSrc"></span></div>
    <div class="card analysis" id="analysis"></div>
  </section>

  <section aria-labelledby="s3">
    <div class="sec-head">
      <div><div class="step">Step 3</div><h2 id="s3">썸네일 시안 5개</h2><p>문구를 고치면 바로 다시 그려지고 정책 검수도 다시 돌아요. 4K PNG는 3840×2160, 유튜브용 JPG는 1280×720·2MB 이하예요.</p></div>
      <button class="btn" id="zipAll" type="button">5개 모두 받기 (ZIP)</button>
    </div>
    <div class="fontbar">
      <label for="fontAll">글씨체 한 번에 바꾸기</label>
      <select id="fontAll"></select>
      <button class="btn small" id="fontReset" type="button">모두 기본 글씨체로</button>
      <label class="btn small upl" for="fontFile">내 글꼴 파일 추가<input type="file" id="fontFile" accept=".ttf,.otf,.woff,.woff2,font/ttf,font/otf,font/woff,font/woff2"></label>
      <span class="hint">시안마다 다르게 하려면 각 시안의 ‘글씨체 바꾸기’를 여세요. 직접 올린 글꼴(G마켓 산스 등)은 목록 맨 아래에 추가돼요. 상업용 사용이 허락된 글꼴인지 확인하세요.</span>
    </div>
    <div class="tgrid" id="thumbs"></div>
  </section>

  <section aria-labelledby="s4">
    <div class="sec-head">
      <div><div class="step">Step 4</div><h2 id="s4">광고 세팅용 제목 5세트</h2><p>Google Ads는 한글 1자를 2자로 셉니다. 숫자는 Google Ads 기준 글자 수예요.</p></div>
      <button class="btn" id="copyAllAds" type="button">5세트 전체 복사</button>
    </div>
    <div class="ads" id="ads"></div>
  </section>

  <section>
    <details class="card policy" id="policy">
      <summary>적용 중인 정책 기준 (Google Ads 클릭베이트 가이드 요약)</summary>
      <div class="pgrid">
        <div class="pbox no"><h4>유형 1 · 정보 은폐</h4><ul><li>‘이것’, ‘이걸로’로 제품·성분을 숨기는 표현</li><li>예: “이것 드시면…”, “이걸로 관리하세요!”</li></ul></div>
        <div class="pbox no"><h4>유형 2 · 효능 단정·긴박감</h4><ul><li>완치·정상화 단정, 인위적 긴박감</li><li>예: “당뇨 탈출!”, “혈당수치 정상!”, “몸이 확 바뀝니다!”, “[긴급 조언!]”</li></ul></div>
        <div class="pbox no"><h4>유형 3 · 자극·공포 썸네일</h4><ul><li>채혈(핏방울)·신체 클로즈업, 공포 연출</li><li>대형 붉은 X, 운전 중 시야 장애 합성, 붉은 경고 배너</li></ul></div>
        <div class="pbox yes"><h4>원칙 1 · 브랜드·성분·주제 명시</h4><ul><li>지시어 삭제</li><li>제품명과 건강 관리 주제를 제목에 직접 표기</li></ul></div>
        <div class="pbox yes"><h4>원칙 2 · 일상 건강 케어 문구</h4><ul><li>‘당뇨 탈출·정상화’ 같은 단정 삭제</li><li>‘식후 혈당 케어 식습관’, ‘시니어 눈 건강 영양 관리’처럼 객관적으로</li></ul></div>
        <div class="pbox yes"><h4>원칙 3 · 유튜브 제목·썸네일도 수정</h4><ul><li>연결된 YouTube 영상의 제목·썸네일도 함께 심사</li><li>썸네일·제목을 고치지 않고 캠페인만 재업로드하면 다시 비승인</li></ul></div>
      </div>
    </details>
  </section>
</main>
<div class="toast" id="toast" role="status" hidden></div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jszip/3.10.1/jszip.min.js"></script>
<script>
'use strict';
const $ = (s, r = document) => r.querySelector(s);
const W = 1280, H = 720;
const EXAMPLE_SCRIPT = `안녕하세요, 시니어 건강 채널입니다. 오늘은 식후 혈당 관리에 대해 이야기해 보겠습니다.
나이가 들수록 밥을 먹고 나면 유난히 나른하고 졸린 분들이 많으시죠. 식후에 혈당이 빠르게 오르내리면 이런 나른함을 느끼기 쉽습니다.
그래서 오늘은 식후 혈당 케어에 도움이 되는 식습관 세 가지를 알려드리겠습니다.
첫째, 채소를 먼저 드세요. 양배추나 브로콜리 같은 채소를 먼저 먹고 밥은 나중에 먹으면 좋습니다.
둘째, 식사 후 10분 정도 가볍게 걸어 보세요.
셋째, 꾸준한 습관이 중요합니다. 바쁜 날에는 슬로벨라처럼 간편하게 챙길 수 있는 제품을 활용하는 것도 방법입니다.
이것만 지키면 혈당수치 정상! 당뇨 탈출도 가능합니다. 절대 방치하지 마세요!`;

/* ───────────── 1. 정책 검수 (PDF 기준) ───────────── */
const TYPE_LABEL = { hide: '정보 은폐', claim: '효능 단정·과장', fear: '공포·긴박감', tone: '자극적 표현' };
const RULES = [
  // 유형 1 · 정보 은폐
  { t: 'hide', lv: 'bad', re: /(?<![가-힣])(이것|이거|이걸|이게|요것|요거|그것|그거)/g, fix: '제품명·성분·주제를 직접 쓰세요' },
  { t: 'hide', lv: 'bad', re: /(?<![가-힣])이\s?(음식|식품|성분|과일|채소|영양제|약초|차|한\s?가지)(?![가-힣])/g, fix: '무엇인지 이름을 직접 쓰세요' },
  { t: 'hide', lv: 'bad', re: /비밀|정체는|○○|OO(?![A-Za-z])|딱\s?하나/g, fix: '숨기지 말고 구체적으로 밝히세요' },
  // 유형 2 · 효능 단정·과장
  { t: 'claim', lv: 'bad', re: /완치|치유|특효|만병|기적|박멸|근절|회춘|즉효|직빵/g, fix: '‘관리·케어·도움’ 같은 표현으로' },
  { t: 'claim', lv: 'bad', re: /치료(?!사)/g, fix: '‘관리’ 또는 ‘케어’로' },
  { t: 'claim', lv: 'bad', re: /낫(?:는|습니다|아요|게|고|기)|나았|나아(?:집|져|진|요)/g, fix: '‘관리에 도움’으로 순화' },
  { t: 'claim', lv: 'bad', re: /정상/g, fix: '수치 정상화 단정 삭제 → ‘관리’로' },
  { t: 'claim', lv: 'bad', re: /탈출/g, fix: '‘관리 습관’으로' },
  { t: 'claim', lv: 'bad', re: /(?:사라|없어)(?:집|져|진|짐|지)/g, fix: '단정 삭제 → ‘관리해요’' },
  { t: 'claim', lv: 'bad', re: /해결/g, fix: '‘관리’로' },
  { t: 'claim', lv: 'bad', re: /100\s?%|백\s?퍼센트/g, fix: '보장 표현 삭제' },
  { t: 'claim', lv: 'bad', re: /즉시|단번에|한\s?방에|(?:하루|이틀|사흘|\d+\s?(?:일|주|시간))\s?만에/g, fix: '기간 단정 삭제 → ‘꾸준한 관리’' },
  { t: 'claim', lv: 'bad', re: /저절로|알아서\s?(?:빠|내려|좋아)/g, fix: '‘꾸준한 습관으로’' },
  { t: 'claim', lv: 'bad', re: /확\s?(?:바뀝|바뀌|달라|좋아)|싹\s?(?:사라|빠|낫|잡)|뚝\s?(?:떨|내려)?/g, fix: '과장 삭제' },
  { t: 'claim', lv: 'bad', re: /(?:떨어|내려|낮아|낮춰)(?:집니다|진다|져요|뜨|갑니다|가요|드립)/g, fix: '수치 변화 단정 삭제 → ‘관리’' },
  { t: 'claim', lv: 'bad', re: /잡(?:는|아줍|아\s?줍|습니다|아요)(?![가-힣])/g, fix: '‘관리하는’으로' },
  { t: 'claim', lv: 'bad', re: /(?:운동|단식|식단|약)[,\s·]*(?:[가-힣]+[,\s·]*)?안\s?해도|안\s?먹어도|약\s?(?:없이|끊|대신)/g, fix: '노력 없이 된다는 단정 삭제' },
  { t: 'claim', lv: 'bad', re: /효과\s?(?:보장|만점|최고)|부작용\s?(?:없|zero|제로)/g, fix: '보장·안전 단정 삭제' },
  { t: 'claim', lv: 'warn', re: /(?:개선|예방|회복)(?:됩|된다|돼|시켜|합니다|해요)|좋아(?:집니다|져요)/g, fix: '‘~에 도움’ 정도로 낮추기' },
  { t: 'claim', lv: 'warn', re: /최고의?|무조건|만능/g, fix: '최상급 표현 줄이기' },
  // 유형 2·3 · 공포·긴박감
  { t: 'fear', lv: 'bad', re: /긴급|경고|위험|비상|충격|경악|소름|공포|무서|끔찍|폭로|대유행/g, fix: '정보형 표현으로' },
  { t: 'fear', lv: 'bad', re: /절대|당장|지금\s?바로|서두르|마감\s?임박|마지막\s?기회|늦기\s?전/g, fix: '긴박감 삭제' },
  { t: 'fear', lv: 'bad', re: /큰일|큰\s?병|죽(?:음|는|습니다|어요|을)|사망|실명|돌연사|급사/g, fix: '공포 유발 삭제' },
  { t: 'fear', lv: 'bad', re: /방치|놓치면|모르면|손해/g, fix: '압박 표현 삭제' },
  { t: 'fear', lv: 'bad', re: /숨기|숨겨|감추|아무도\s?모르|(?:의사|병원|약사)(?:들)?(?:도|이|가)?\s?(?:모르|숨기|안\s?알려|말\s?안)|\d+\s?%\s?(?:가|이|는)?\s?모르/g, fix: '호기심 자극 삭제' },
  { t: 'fear', lv: 'warn', re: /병원에서|조심하세요|주의하세요|합병증/g, fix: '불안 자극 없이 정보형으로' },
  { t: 'tone', lv: 'warn', re: /!{2,}|\?{2,}/g, fix: '느낌표·물음표는 1개만' },
];
function lint(text) {
  const out = [];
  if (!text) return out;
  for (const r of RULES) {
    r.re.lastIndex = 0;
    let m;
    while ((m = r.re.exec(text))) {
      if (!m[0]) { r.re.lastIndex++; continue; }
      out.push({ s: m.index, e: m.index + m[0].length, text: m[0], t: r.t, lv: r.lv, fix: r.fix });
    }
  }
  out.sort((a, b) => a.s - b.s || b.e - a.e);
  const dedup = [];
  for (const x of out) if (!dedup.some(d => x.s < d.e && x.e > d.s)) dedup.push(x);
  return dedup;
}
function verdict(issues) {
  if (issues.some(i => i.lv === 'bad')) return { cls: 'bad', label: '수정 필요' };
  if (issues.length) return { cls: 'warn', label: '주의' };
  return { cls: 'ok', label: '정책 검수 통과' };
}

/* ───────────── 2. 주제 사전 & 규칙 기반 분석 ───────────── */
const TOPICS = [
  { re: /혈당|당뇨|인슐린|당화혈색소/g, key: '혈당', big: '혈당', care: '식후 혈당 케어', sit: '식사 후', sym: ['나른함', '잦은 갈증'], checks: ['채소 먼저 먹기', '식후 가볍게 걷기', '천천히 먹기'], note: ['가벼운 식후', '건강한 하루'], area: '식습관', hook: '식후가 나른하다면' },
  { re: /비문증|시력|침침|황반|안구\s?건조|백내장|녹내장|루테인|눈\s?(?:건강|피로|앞)|날파리/g, key: '눈 건강', big: '눈', care: '침침한 눈 관리', sit: '화면 볼 때', sym: ['침침함', '눈 피로'], checks: ['화면 쉬어가기', '루테인 챙기기', '충분한 수면'], note: ['맑은 눈', '편안한 하루'], area: '눈 관리', hook: '눈이 자주 침침하면' },
  { re: /비염|코막힘|콧물|재채기|축농증|부비동/g, key: '비염', big: '비염', care: '코 건강 관리', sit: '환절기', sym: ['코막힘', '재채기'], checks: ['알레르기 비염', '계절성 비염', '만성 비염'], note: ['숨 쉬는', '행복한 일상'], area: '생활 관리', hook: '환절기 코가 답답하면' },
  { re: /헤르페스|입술\s?(?:물집|수포)|구순\s?포진|대상\s?포진|수포/g, key: '헤르페스', big: '입술', care: '입술 수포 관리', sit: '피곤할 때', sym: ['입술 수포', '입가 물집'], checks: ['충분한 휴식', '면역 관리', '손 청결'], note: ['컨디션', '챙기는 하루'], area: '면역 관리', hook: '피곤하면 입술이 걱정' },
  { re: /혈압/g, key: '혈압', big: '혈압', care: '혈압 관리 습관', sit: '아침마다', sym: ['뒷목 뻐근함', '두통'], checks: ['싱겁게 먹기', '꾸준한 걷기', '숙면하기'], note: ['가벼운 몸', '편안한 하루'], area: '생활 습관', hook: '혈압이 신경 쓰이면' },
  { re: /관절|무릎|연골|글루코사민|보스웰리아/g, key: '관절', big: '관절', care: '무릎 관절 관리', sit: '계단 오를 때', sym: ['무릎 시큰함', '뻣뻣함'], checks: ['가벼운 스트레칭', '체중 관리', '허벅지 근력'], note: ['가벼운', '발걸음'], area: '관절 관리', hook: '계단이 부담된다면' },
  { re: /혈관|콜레스테롤|중성\s?지방|고지혈|혈행|혈액\s?순환/g, key: '혈관', big: '혈관', care: '혈관 건강 관리', sit: '추운 날', sym: ['손발 저림', '쉽게 피로'], checks: ['기름진 음식 줄이기', '등푸른 생선', '꾸준한 걷기'], note: ['맑은 혈관', '활기찬 하루'], area: '식습관', hook: '손발이 자주 저리면' },
  { re: /간\s?(?:건강|수치|기능)|지방간|밀크씨슬|실리마린/g, key: '간 건강', big: '간', care: '간 건강 관리', sit: '아침마다', sym: ['피로감', '무거운 몸'], checks: ['절주하기', '충분한 수면', '균형 잡힌 식사'], note: ['가뿐한', '아침'], area: '생활 습관', hook: '아침이 무겁다면' },
  { re: /장\s?건강|변비|유산균|프로바이오틱스|배변|더부룩|장내/g, key: '장 건강', big: '장', care: '편안한 장 관리', sit: '식사 후', sym: ['더부룩함', '불규칙한 배변'], checks: ['식이섬유 챙기기', '충분한 수분', '유산균'], note: ['가벼운 속', '편안한 하루'], area: '식습관', hook: '속이 자주 더부룩하면' },
  { re: /수면|불면|숙면|잠\s?(?:이|을|못)|멜라토닌/g, key: '수면', big: '숙면', care: '꿀잠 습관', sit: '밤마다', sym: ['뒤척임', '새벽에 깸'], checks: ['일정한 기상', '저녁 카페인 줄이기', '가벼운 스트레칭'], note: ['푹 자는', '개운한 아침'], area: '수면 습관', hook: '밤에 자주 깬다면' },
  { re: /기억력|치매|인지\s?기능|두뇌|건망증|깜빡/g, key: '기억력', big: '기억력', care: '두뇌 건강 관리', sit: '요즘 들어', sym: ['깜빡함', '집중 저하'], checks: ['독서·퍼즐', '꾸준한 걷기', '사람 만나기'], note: ['또렷한', '하루'], area: '두뇌 관리', hook: '깜빡하는 일이 잦다면' },
  { re: /전립선|빈뇨|야간뇨|잔뇨|쏘팔메토/g, key: '전립선', big: '전립선', care: '전립선 건강 관리', sit: '밤마다', sym: ['잦은 소변', '잔뇨감'], checks: ['수분 조절', '하체 운동', '규칙적 생활'], note: ['편안한', '밤'], area: '생활 관리', hook: '밤에 화장실이 잦다면' },
  { re: /뼈\s?건강|골다공증|골밀도|칼슘/g, key: '뼈 건강', big: '뼈', care: '뼈 건강 관리', sit: '나이 들수록', sym: ['골밀도 걱정', '허리 불편'], checks: ['칼슘 챙기기', '햇볕 쬐기', '근력 운동'], note: ['튼튼한', '하루'], area: '영양 관리', hook: '골밀도가 걱정되면' },
  { re: /탈모|모발|두피|머리카락/g, key: '모발', big: '두피', care: '두피·모발 관리', sit: '샤워할 때', sym: ['빠지는 모발', '가는 모발'], checks: ['두피 청결', '단백질 섭취', '충분한 수면'], note: ['풍성한', '자신감'], area: '두피 관리', hook: '머리카락이 신경 쓰이면' },
  { re: /뱃살|체중|다이어트|체지방|비만/g, key: '체중', big: '뱃살', care: '건강한 체중 관리', sit: '나이 들수록', sym: ['늘어난 뱃살', '쉽게 지침'], checks: ['저녁 소식', '단백질 챙기기', '꾸준한 걷기'], note: ['가벼운 몸', '활기찬 하루'], area: '식습관', hook: '뱃살이 늘었다면' },
  { re: /갱년기|폐경|안면\s?홍조/g, key: '갱년기', big: '갱년기', care: '갱년기 건강 관리', sit: '요즘 부쩍', sym: ['화끈거림', '잠 못 이룸'], checks: ['규칙적 운동', '충분한 수면', '균형 잡힌 식사'], note: ['나를 위한', '편안한 하루'], area: '생활 관리', hook: '요즘 부쩍 화끈거리면' },
  { re: /피부|주름|기미|콜라겐/g, key: '피부', big: '피부', care: '피부 건강 관리', sit: '세안 후', sym: ['당김', '잔주름'], checks: ['충분한 보습', '자외선 차단', '수분 섭취'], note: ['촉촉한', '하루'], area: '피부 관리', hook: '피부가 건조하다면' },
  { re: /이명|청력|귀\s?울림|난청/g, key: '귀 건강', big: '이명', care: '귀 건강 관리', sit: '조용할 때', sym: ['귀 울림', '답답함'], checks: ['소음 줄이기', '충분한 휴식', '혈액순환 관리'], note: ['편안한', '귀'], area: '생활 관리', hook: '귀가 자주 울린다면' },
  { re: /잇몸|치아|치주|구강/g, key: '잇몸', big: '잇몸', care: '잇몸 건강 관리', sit: '양치할 때', sym: ['잇몸 시림', '잇몸 붓기'], checks: ['꼼꼼한 양치', '치실 사용', '정기 검진'], note: ['건강한', '미소'], area: '구강 관리', hook: '양치할 때 시리다면' },
  { re: /기관지|폐\s?건강|기침|가래|호흡/g, key: '기관지', big: '기관지', care: '기관지 건강 관리', sit: '환절기', sym: ['잦은 기침', '목 칼칼함'], checks: ['실내 습도', '충분한 수분', '미세먼지 피하기'], note: ['시원한', '숨'], area: '생활 관리', hook: '목이 자주 칼칼하면' },
  { re: /피로|활력|기력|무기력/g, key: '활력', big: '피로', care: '활력 관리', sit: '오후만 되면', sym: ['피로감', '무거운 몸'], checks: ['규칙적 식사', '가벼운 운동', '충분한 수면'], note: ['활기찬', '하루'], area: '생활 습관', hook: '오후만 되면 지친다면' },
];
const FOODS = ['양배추','브로콜리','양파','마늘','흑마늘','현미','귀리','보리','콩','두부','낫토','청국장','견과류','호두','아몬드','블루베리','토마토','계피','여주','돼지감자','바나바잎','뽕잎','우엉','연근','미역','다시마','요거트','된장','올리브유','들기름','연어','고등어','달걀','계란','시금치','당근','아로니아','빌베리','결명자','구기자','루테인','지아잔틴','아스타잔틴','오메가3','비타민D','비타민C','마그네슘','아연','유산균','프로바이오틱스','콜라겐','홍삼','녹차','생강','강황','도라지','작두콩','프로폴리스','라이신','크랜베리','쏘팔메토','보스웰리아','글루코사민','칼슘','밀크씨슬','식이섬유','사과','고구마','버섯','미나리','부추','파프리카','레몬','매실','대추','메밀','카카오'];
const KNOWN_BRANDS = ['슬로벨라', '웰리오맥스'];
const STOP = new Set(['오늘','그리고','그래서','하지만','정말','여러분','안녕하세요','채널','이번','우리','이런','저런','많이','가장','때문','정도','바로','이렇게','그런데','생각','경우','사람','시간','내용','영상','구독','좋아요','합니다','있습니다','입니다','드세요','먹고','먹으면','하는','있는','하면','좋은','위해','통해','관련','건강']);

function hasJong(w) {
  const c = (w || '').trim().slice(-1);
  const code = c.charCodeAt(0);
  if (code >= 0xac00 && code <= 0xd7a3) return (code - 0xac00) % 28 !== 0;
  return /[013678lmnr]$/i.test(c);
}
function jong(w) { const code = (w || '').trim().slice(-1).charCodeAt(0); return code >= 0xac00 && code <= 0xd7a3 ? (code - 0xac00) % 28 : -1; }
function j(w, pair) {
  const [a, b] = pair.split('/');
  if (pair === '으로/로') { const jj = jong(w); return w + (jj > 0 && jj !== 8 ? a : b); }
  return w + (hasJong(w) ? a : b);
}
function countRe(text, re) { re.lastIndex = 0; return (text.match(re) || []).length; }
function seasonLabel(d = new Date()) { const m = d.getMonth() + 1; return m <= 2 || m === 12 ? '겨울' : m <= 5 ? '봄' : m <= 8 ? '여름' : '가을'; }

function detectTopic(text) {
  let best = null, score = 0;
  for (const t of TOPICS) { const c = countRe(text, t.re); if (c > score) { score = c; best = t; } }
  if (best) return best;
  const words = (text.match(/[가-힣]{2,4}/g) || []).filter(w => !STOP.has(w) && !/(습니다|합니다|세요|해요|니다|에서|으로|하고)$/.test(w));
  const freq = {}; for (const w of words) freq[w] = (freq[w] || 0) + 1;
  const top = Object.entries(freq).sort((a, b) => b[1] - a[1])[0];
  const key = top ? top[0] : '건강';
  return { key, big: key.slice(0, 3), care: `${key} 관리`, sit: '요즘 들어', sym: ['일상 불편함', '컨디션 저하'], checks: ['생활 습관', '균형 잡힌 식사', '꾸준한 관리'], note: ['건강한', '하루 습관'], area: '생활 습관', hook: `${key}${hasJong(key) ? '이' : '가'} 신경 쓰이면` };
}
function detectAudience(text) {
  const m = text.match(/([4-8]0)\s?대/);
  if (/시니어|어르신|노년|노인/.test(text)) return '시니어';
  if (m) return `${m[1]}대`;
  if (/중장년|중년/.test(text)) return '중장년';
  return '시니어';
}
function detectCount(text) {
  const m = text.match(/(\d|세|두|네|다섯)\s?가지/);
  if (!m) return 3;
  return ({ '세': 3, '두': 2, '네': 4, '다섯': 5 })[m[1]] || Math.min(7, Math.max(2, +m[1] || 3));
}
function detectFoods(text) {
  return FOODS.map(f => [f, countRe(text, new RegExp(f, 'g'))]).filter(x => x[1]).sort((a, b) => b[1] - a[1]).map(x => x[0]).slice(0, 6);
}
function detectBrand(text) {
  for (const b of KNOWN_BRANDS) if (text.includes(b)) return b;
  const m = text.match(/([가-힣A-Za-z0-9]{2,10})\s?(?:®|™)/);
  return m ? m[1] : '';
}
function sentences(text) { return text.replace(/\s+/g, ' ').split(/(?<=[.!?。])\s+/).map(s => s.trim()).filter(Boolean); }

function ruleAnalyze(script, brandIn, topicIn) {
  const text = script || '';
  const t = { ...detectTopic(topicIn ? topicIn + ' ' + topicIn + ' ' + text : text) };
  if (topicIn && !TOPICS.some(x => { x.re.lastIndex = 0; return x.re.test(topicIn); })) { t.key = topicIn.trim().slice(0, 8); t.big = t.key.slice(0, 3); t.care = `${t.key} 관리`; }
  const brand = (brandIn || '').trim() || detectBrand(text);
  const foods = detectFoods(text);
  const audience = detectAudience(text);
  const n = detectCount(text);
  const sents = sentences(text).filter(s => !lint(s).some(i => i.lv === 'bad') && !/^(안녕하세요|구독|좋아요|오늘도|감사합니다)/.test(s));
  const scored = sents.map((s, i) => [s, countRe(s, t.re || /$^/g) * 2 + (foods.some(f => s.includes(f)) ? 1 : 0) + (i < 3 ? 0.5 : 0), i]);
  const pick = scored.filter(x => x[1] > 0).sort((a, b) => b[1] - a[1]).slice(0, 2).sort((a, b) => a[2] - b[2]).map(x => x[0]);
  const summary = (pick.length ? pick : sents.slice(0, 2)).join(' ').slice(0, 200);
  return { topic: t.care, brand, audience, summary, keywords: [...new Set([...foods, ...t.sym])].slice(0, 6), risky: [], _t: t, n, foods };
}

function ruleCopy(an) {
  const t = an._t, b = an.brand, a = an.audience || '시니어', n = an.n || 3, food = an.foods[0] || '';
  const [care1, ...careRest] = t.care.split(' ');
  const year = new Date().getFullYear();
  const thumbs = {
    t1: { l1: `${j(a, '이라면/라면')} 알아둘`, l2a: care1, l2b: careRest.join(' ') || '관리법', l3: b ? `${j(b, '과/와')} 함께 관리!` : `생활 습관 ${n}가지!` },
    t2: { a1: t.sit, a2: t.sym[0], b1: t.key, b2: '때문일까?', c1: '알아두면', c2: '좋은 습관', d1: t.key, d2: '관리법' },
    t3: { banner1: `${year} ${seasonLabel()}`, banner2: `${t.key} 관리 가이드`, big: t.big, green: t.sym.join('·'), white: '원인부터 관리법까지!', cta: b ? `${j(b, '과/와')} 함께!` : '함께 알아봐요!', note1: t.note[0], note2: t.note[1], checks: t.checks.join(' / ') },
    t4: { box: t.hook, y: t.care, g: `습관 ${n}가지!`, r: food ? `식후 ${food} 챙기기!` : b ? `${j(b, '으로/로')} 간편하게!` : '오늘부터 실천해요!', em: food || b || '' },
    t5: { tag: `${a} 건강 노트`, l1: `${j(t.sym[0], '이/가')} 잦다면`, l2: t.key.length <= 3 ? `${t.key} 관리` : t.key, l3: `${t.area}부터 점검!`, band: b ? `${j(b, '과/와')} 함께하는 ${t.care}` : `${j(a, '을/를')} 위한 ${t.care} 가이드` },
  };
  const ads = [
    { headline: `${t.care} 방법`, longHeadline: `${j(a, '을/를')} 위한 ${t.care}, 생활 속 ${n}가지 습관`, description: b ? `${j(b, '으로/로')} 간편하게 시작하는 ${t.key} 건강 관리` : `${t.key} 관리에 도움 되는 생활 습관을 정리했어요`, ytTitle: `${a} ${t.care}에 도움 되는 ${t.area} ${n}가지` },
    { headline: b ? `${b} ${t.key} 케어` : `${t.key} 관리 가이드`, longHeadline: b ? `${j(b, '과/와')} 함께하는 ${a} ${t.care} 가이드` : `${a} ${t.care}, 알아두면 좋은 관리 가이드`, description: `하루 한 번 간편하게, ${a} 맞춤 ${t.key} 건강 관리`, ytTitle: b ? `${j(b, '이/가')} 알려드리는 건강한 ${t.care} 습관` : `알아두면 좋은 ${t.care} 습관 정리` },
    { headline: `${t.sit} ${t.sym[0]} 체크`, longHeadline: `${t.sit} ${t.sym[0]}·${j(t.sym[1], '이/가')} 신경 쓰인다면, ${t.key} 체크리스트`, description: `일상에서 확인하는 ${t.key} 관리 포인트 ${n}가지`, ytTitle: `${t.sit} ${t.sym[0]}, ${t.sym[1]} 신경 쓰일 때 알아두면 좋은 ${t.care}` },
    { headline: `${t.key} 관리 ${n}가지`, longHeadline: food ? `알아두면 좋은 ${t.key} 관리법 & ${food} 활용 식단` : `알아두면 좋은 ${t.key} 관리법 & 추천 습관 ${n}가지`, description: food ? `${j(food, '을/를')} 활용한 ${t.area} 아이디어를 소개해요` : `꾸준히 실천하기 쉬운 ${t.area} 아이디어를 소개해요`, ytTitle: `${t.key} 관리에 도움 되는 ${food ? food + ' 등 ' : ''}식품과 습관 ${n}가지` },
    { headline: `${a} ${t.key} 가이드`, longHeadline: `${a} 맞춤 ${t.care}, 오늘부터 실천하는 생활 습관`, description: b ? `${j(b, '과/와')} 함께 꾸준한 ${t.key} 관리를 시작해 보세요` : `꾸준한 ${t.key} 관리를 생활 습관부터 시작해 보세요`, ytTitle: `${j(a, '을/를')} 위한 ${t.care} 가이드 | ${t.area} 체크포인트` },
  ];
  return { thumbs, ads };
}

/* ───────────── 3. Claude 분석 (가능할 때) ───────────── */
const capSample = (window.claude && window.claude.use) ? window.claude.use('sample').catch(() => null) : Promise.resolve(null);
const capDownloads = (window.claude && window.claude.use) ? window.claude.use('downloads').catch(() => null) : Promise.resolve(null);

const POLICY_PROMPT = `[정책 — 회사 Google Ads 클릭베이트 가이드(PDF), 100% 준수]
비승인 유형
1) 정보 은폐(호기심 자극): '이것', '이걸로', '이거', '이것만' 같은 지시어로 제품·성분·주제를 숨기는 표현. 예) "이것 드시면…", "이걸로 관리하세요!"
2) 효능 단정·과장·긴박감: 질환 완치·정상화 단정, 인위적 긴박감. 예) "당뇨 탈출!", "혈당수치 정상!", "몸이 확 바뀝니다!", "[긴급 조언!]"
3) 자극적·공포 유발: 공포·위험 연출, 압박형 경고 문구. 예) "절대 눈 비비거나 방치하지 마세요!"
승인 복구 3원칙
1) 브랜드·성분·주제 명시: 지시어를 지우고 제품명과 건강 관리 주제를 제목에 직접 표기
2) 일상 건강 케어 문구로 순화: '식후 혈당 케어 식습관', '시니어 눈 건강 영양 관리'처럼 객관적 표현
3) 광고 문구뿐 아니라 연결된 YouTube 영상 제목·썸네일도 함께 심사됨
Before → After
- "혈당에 좋은 음식 '이것' 드시면 당뇨탈출합니다!" → "시니어 식후 혈당 관리에 도움 되는 음식 3가지"
- "이것만 지키면 혈당수치 정상!" → "식후 혈당 케어를 위한 건강한 식습관 3가지"
- "치솟는 혈당 관리하는 방법! / 몸이 확 바뀝니다!" → "꾸준한 식후 혈당 케어 방법 알아보기 / 슬로벨라로 간편하게 건강 관리하세요"
- "절대 눈 비비거나 방치하지 마세요!" → "침침하고 답답한 눈, 일상 속 눈 건강 관리법"
- "이걸로 관리하세요!" → "웰리오맥스와 함께하는 시니어 눈 건강 관리 가이드"
- "이것만 지키면 혈당수치 정상! [긴급 조언!]" → "알아두면 좋은 당뇨 식단 관리법 & 추천 식품 3가지"
쓰면 안 되는 말: 이것, 이거, 이걸, 이게, 그것, 비밀, 완치, 치료, 치유, 낫는/낫습니다, 정상, 탈출, 사라집니다, 없어집니다, 해결, 특효, 기적, 100%, 즉시, 하루만에/N일만에, 저절로, 확 바뀝니다, 뚝, 떨어집니다, 잡는/잡아줍니다, 약 없이, ~안 해도, 효과 보장, 부작용 없는, 개선됩니다, 최고, 무조건, 긴급, 경고, 위험, 절대, 당장, 지금 바로, 큰일, 죽음, 실명, 충격, 방치, 놓치면, 모르면 손해, 숨기는, 아무도 모르는, N%가 모르는, 병원에서, 대유행, 느낌표·물음표 2개 이상.
권장: 제품명(있을 때)·성분·식품·주제를 구체적으로 쓰고 '관리', '케어', '도움', '습관', '알아보기', '가이드', '체크', 'N가지' 같은 객관적 표현을 쓴다. 대본에 실제로 있는 내용만 쓴다(없는 효능·수치·성분을 지어내지 않는다). 대본에 없으면 의사·전문의 같은 자격을 내세우지 않는다.`;

const TEMPLATE_PROMPT = `[썸네일 5종 — 각 칸 글자 수(공백 포함)를 지킬 것. 큰 글씨로 들어가므로 짧고 또렷하게]
t1 (원본 레퍼런스 "한국인 90%가 모르는 / 성병 헤르페스 / 하루만에 낫는 방법!"의 3줄 대형 형식):
  l1 흰색 도입 6~11자 (예 "50대라면 알아둘") · l2a 빨간 키워드 2~4자 (예 "입술") · l2b 노란 키워드 2~5자 (예 "헤르페스") · l3 하늘색 결론 6~10자 (예 "생활 관리 습관!")
t2 (원본 "피곤할때 입술 수포 / 헤르페스라고? / 병원에서 절대숨기는 / 헤르페스 치료법" 형식):
  a1 노란 상황 2~5자 (예 "피곤할 때") · a2 빨간 증상 2~5자 (예 "입술 수포") · b1 빨간 주제어 2~5자 (예 "헤르페스") · b2 노란 물음 2~4자, 물음표 1개로 끝 (예 "일까?") · c1 남색띠1 흰 글씨 2~5자 (예 "알아두면") · c2 남색띠1 강조 2~6자 (예 "좋은 습관") · d1 남색띠2 흰 글씨 2~5자 (예 "입술 건강") · d2 남색띠2 강조 2~4자 (예 "관리법")
t3 (원본 "2026년 비염 대유행? / 비염 / 코막힘·재채기 / 원인부터 관리법까지! / 지금 확인하세요!" + 손글씨 메모 + 체크리스트 형식):
  banner1 빨간 배너 흰 글씨 2~6자 (예 "${new Date().getFullYear()} ${seasonLabel()}") · banner2 빨간 배너 노란 글씨 3~9자, 경고·유행 표현 금지 (예 "비염 관리 가이드") · big 초대형 주제어 1~3자 (예 "비염") · green 초록 증상 4~8자, 가운뎃점 활용 (예 "코막힘·재채기") · white 흰색 설명 6~11자 (예 "원인부터 관리법까지!") · cta 하늘색 부드러운 안내 4~9자, 긴박감 금지 (예 "함께 알아봐요!") · note1, note2 손글씨 메모 각 2~7자 (예 "숨 쉬는", "행복한 일상") · checks 체크리스트 3개 배열, 각 2~8자
t4 (원본 "운동, 단식 안해도 / 당뇨는 저절로 / 사라집니다!! / 저녁 식후 이것 드세요!" 형식):
  box 빨간 박스 흰 글씨 5~9자 (예 "저녁 식사 후에") · y 노란 줄 4~8자 (예 "식후 혈당 케어") · g 초록 줄 3~7자 (예 "습관 3가지!") · r 주황 마무리 6~12자, 지시어 대신 구체적 식품·제품명 (예 "식후 양배추 챙기기!") · em r 안에 그대로 들어 있는 식품·제품명(없으면 "")
t5 (화이트 정보형: 상단 태그 + 3줄 + 하단 띠):
  tag 4~9자 (예 "시니어 건강 노트") · l1 검정 도입 5~10자 (예 "식후 나른함 잦다면") · l2 빨간 대형 주제 2~6자 (예 "혈당 관리") · l3 형광펜 강조 5~10자 (예 "식사 순서부터!") · band 하단 띠 8~18자, 제품명 있으면 포함 (예 "슬로벨라와 함께하는 식후 케어")

[광고 제목 5세트 — Google Ads 동영상 광고 세팅용. 한글은 1자가 2자로 계산되니 한글 글자 수 기준으로 지킬 것]
  headline(주 제목) 한글 15자 이내 · longHeadline(부 제목) 45자 이내 · description(세부 제목) 45자 이내 · ytTitle(연결할 YouTube 영상 제목) 25~45자, 주제·제품명(있으면)·구체적 내용 포함
  5세트는 순서대로 ① 생활 습관형 ② 제품·브랜드 소개형(제품명이 없으면 주제 가이드형) ③ 증상 체크형 ④ N가지 리스트형 ⑤ 시니어 맞춤 가이드형.`;

function buildPrompt(script, brand, topic) {
  return `당신은 Google Ads 정책 검수 담당자이자 시니어 건강 유튜브 썸네일 카피라이터입니다.
아래 [대본]을 분석해서, [정책]에 걸리지 않으면서 대본 내용과 정확히 맞는 썸네일 문구 5종과 광고 제목 5세트를 만드세요.
썸네일은 원본 레퍼런스처럼 짧고 강한 리듬을 살리되, 비승인 표현은 승인 가능한 표현으로 바꿉니다.

${POLICY_PROMPT}

${TEMPLATE_PROMPT}

[입력]
제품·브랜드명(사용자 입력): ${brand || '(없음 — 대본에 나오면 그것을 사용)'}
핵심 주제(사용자 입력): ${topic || '(없음 — 대본에서 추출)'}
[대본]
${script.slice(0, 14000)}

[출력] 아래 모양의 JSON 하나만 출력하세요. 설명 문장 금지.
{"analysis":{"topic":"핵심 건강 주제","brand":"제품·브랜드명 또는 빈 문자열","audience":"주 시청자","summary":"대본 요약 2문장","keywords":["핵심 키워드 최대 6개"],"risky":[{"text":"대본 속 정책 위험 표현(짧게 원문 그대로)","type":"정보 은폐|효능 단정|공포·긴박감","fix":"바꿔 쓸 문구"}]},
"thumbs":{"t1":{"l1":"","l2a":"","l2b":"","l3":""},"t2":{"a1":"","a2":"","b1":"","b2":"","c1":"","c2":"","d1":"","d2":""},"t3":{"banner1":"","banner2":"","big":"","green":"","white":"","cta":"","note1":"","note2":"","checks":["","",""]},"t4":{"box":"","y":"","g":"","r":"","em":""},"t5":{"tag":"","l1":"","l2":"","l3":"","band":""}},
"ads":[{"angle":"생활 습관형","headline":"","longHeadline":"","description":"","ytTitle":""}, …총 5개]}
risky는 대본에서 실제로 찾은 것만 최대 6개. 출력 전에 모든 문구를 [쓰면 안 되는 말]과 대조해 하나도 없게 고치세요.`;
}

function str(v, max = 60) { return typeof v === 'string' ? v.replace(/\s+/g, ' ').trim().slice(0, max) : ''; }
function mergeClaude(data, base) {
  const an = data && data.analysis || {};
  const analysis = {
    topic: str(an.topic, 40) || base.an.topic,
    brand: str(an.brand, 30) || base.an.brand,
    audience: str(an.audience, 30) || base.an.audience,
    summary: str(an.summary, 300) || base.an.summary,
    keywords: Array.isArray(an.keywords) ? an.keywords.map(k => str(k, 20)).filter(Boolean).slice(0, 6) : base.an.keywords,
    risky: Array.isArray(an.risky) ? an.risky.map(r => ({ text: str(r && r.text, 80), type: str(r && r.type, 20), fix: str(r && r.fix, 80) })).filter(r => r.text).slice(0, 6) : [],
  };
  const thumbs = {};
  for (const tp of TPLS) {
    const src = (data && data.thumbs && data.thumbs[tp.id]) || {};
    thumbs[tp.id] = {};
    for (const [k, , max] of tp.fields) {
      let v = src[k];
      if (k === 'checks' && Array.isArray(v)) v = v.map(x => str(x, 14)).filter(Boolean).slice(0, 3).join(' / ');
      v = str(v, Math.max(max * 2, 12));
      thumbs[tp.id][k] = v || (k === 'em' ? '' : base.copy.thumbs[tp.id][k]);
    }
  }
  const ads = [0, 1, 2, 3, 4].map(i => {
    const a = (data && Array.isArray(data.ads) && data.ads[i]) || {};
    const b = base.copy.ads[i];
    return { headline: str(a.headline, 40) || b.headline, longHeadline: str(a.longHeadline, 90) || b.longHeadline, description: str(a.description, 90) || b.description, ytTitle: str(a.ytTitle, 100) || b.ytTitle };
  });
  return { analysis, thumbs, ads };
}

/* ───────────── 4. 썸네일 렌더러 ───────────── */
const FAM = {
  noto: '"Noto Sans KR","Apple SD Gothic Neo","Malgun Gothic",sans-serif',
  bhs: '"Black Han Sans","Noto Sans KR","Apple SD Gothic Neo",sans-serif',
  dohyeon: '"Do Hyeon","Noto Sans KR","Apple SD Gothic Neo",sans-serif',
  jua: '"Jua","Noto Sans KR","Apple SD Gothic Neo",sans-serif',
  pen: '"Nanum Pen Script","Noto Sans KR",cursive',
};
const F = {
  noto9: { fam: FAM.noto, w: 900 }, noto8: { fam: FAM.noto, w: 800 }, noto7: { fam: FAM.noto, w: 700 }, noto5: { fam: FAM.noto, w: 500 },
  bhs: { fam: FAM.bhs, w: 400 }, dohyeon: { fam: FAM.dohyeon, w: 400 }, jua: { fam: FAM.jua, w: 400 }, pen: { fam: FAM.pen, w: 400 },
};
const FALLBACK = '"Noto Sans KR","Apple SD Gothic Neo","Malgun Gothic",sans-serif';
// Fonts the user can pick per thumbnail; `name` is the CSS family, `w` the weight it ships in.
const FONTS = [
  { id: 'noto9', label: 'Noto Sans KR 블랙 (본고딕)', name: 'Noto Sans KR', w: 900 },
  { id: 'noto7', label: 'Noto Sans KR 볼드', name: 'Noto Sans KR', w: 700 },
  { id: 'noto5', label: 'Noto Sans KR 보통', name: 'Noto Sans KR', w: 500 },
  { id: 'gothicA1', label: 'Gothic A1 블랙', name: 'Gothic A1', w: 900 },
  { id: 'nanumGothic', label: '나눔고딕 엑스트라볼드', name: 'Nanum Gothic', w: 800 },
  { id: 'bhs', label: '검은고딕 (Black Han Sans)', name: 'Black Han Sans', w: 400 },
  { id: 'dohyeon', label: '도현 (Do Hyeon)', name: 'Do Hyeon', w: 400 },
  { id: 'jua', label: '주아 (Jua)', name: 'Jua', w: 400 },
  { id: 'bagel', label: '베이글 팻 원 (Bagel Fat One)', name: 'Bagel Fat One', w: 400 },
  { id: 'gasoek', label: '가석 원 (Gasoek One)', name: 'Gasoek One', w: 400 },
  { id: 'sunflower', label: '해바라기 (Sunflower)', name: 'Sunflower', w: 700 },
  { id: 'gugi', label: '구기 (Gugi)', name: 'Gugi', w: 400 },
  { id: 'myeongjo', label: '나눔명조 엑스트라볼드', name: 'Nanum Myeongjo', w: 800 },
  { id: 'pen', label: '나눔손글씨 펜 (손글씨)', name: 'Nanum Pen Script', w: 400 },
  { id: 'gaegu', label: '개구 (손글씨)', name: 'Gaegu', w: 700 },
  { id: 'himelody', label: '하이멜로디 (손글씨)', name: 'Hi Melody', w: 400 },
];
const fontById = id => FONTS.find(f => f.id === id);
// Resolves a template's font role to the user's pick for the thumbnail being drawn.
function R(role, def) {
  const f = fontById(((state.fonts || [])[state.curIdx] || {})[role]);
  return f ? { fam: `"${f.name}",${FALLBACK}`, w: f.w } : def;
}
const FONT_LOADS = ['900 40px "Noto Sans KR"', '800 40px "Noto Sans KR"', '700 40px "Noto Sans KR"', '500 40px "Noto Sans KR"', '40px "Black Han Sans"', '40px "Do Hyeon"', '40px "Jua"', '40px "Nanum Pen Script"'];
async function ensureFonts(text) {
  if (!document.fonts || !document.fonts.load) return;
  const t = (text || '') + '0123456789·!?,.%&가나다';
  const picked = new Set();
  for (const roles of state.fonts || []) for (const id of Object.values(roles)) { const f = fontById(id); if (f) picked.add(`${f.w} 40px "${f.name}"`); }
  await Promise.all([...FONT_LOADS, ...picked].map(f => document.fonts.load(f, t).catch(() => null)));
}
function setFont(ctx, f, size) { ctx.font = `${f.w} ${size}px ${f.fam}`; }
function segWidth(ctx, s) { setFont(ctx, s.f, s.size); return ctx.measureText(s.t).width; }
function fillOf(ctx, s, y, size) {
  if (!s.grad) return s.fill;
  const g = ctx.createLinearGradient(0, y - size * 0.8, 0, y + size * 0.06);
  s.grad.forEach((c, i) => g.addColorStop(i / (s.grad.length - 1), c));
  return g;
}
// Rounded-outline titles (reference ②) have their letter counters filled with the outline
// colour; a plain stroke leaves a dot of background inside wide counters, so those runs are
// drawn offscreen and enclosed transparent pixels are flood-filled.
function drawSegHoles(ctx, s, x, y, size, k) {
  const tr = ctx.getTransform(), sc = Math.hypot(tr.a, tr.b) || 1;
  setFont(ctx, s.f, size);
  const pad = (s.strokes || []).reduce((m, st) => Math.max(m, st[0]), 0) * k + 8;
  const w = ctx.measureText(s.t).width + pad * 2, h = size * 1.5 * (s.sy || 1) + pad * 2;
  const off = document.createElement('canvas');
  off.width = Math.ceil(w * sc); off.height = Math.ceil(h * sc);
  const o = off.getContext('2d', { willReadFrequently: true });
  o.scale(sc, sc);
  const base = pad + size * 1.12 * (s.sy || 1);
  drawSeg(o, { ...s, holes: false }, pad, base, size, k);
  const img = o.getImageData(0, 0, off.width, off.height), d = img.data, ow = off.width, oh = off.height;
  const seen = new Uint8Array(ow * oh), stack = [];
  const push = i => { if (!seen[i] && d[i * 4 + 3] < 40) { seen[i] = 1; stack.push(i); } };
  for (let xx = 0; xx < ow; xx++) { push(xx); push((oh - 1) * ow + xx); }
  for (let yy = 0; yy < oh; yy++) { push(yy * ow); push(yy * ow + ow - 1); }
  while (stack.length) {
    const i = stack.pop(), xx = i % ow;
    if (xx > 0) push(i - 1); if (xx < ow - 1) push(i + 1); if (i >= ow) push(i - ow); if (i < ow * (oh - 1)) push(i + ow);
  }
  const n = parseInt(s.strokes[0][1].slice(1), 16), r = n >> 16 & 255, g = n >> 8 & 255, b = n & 255;
  for (let i = 0; i < seen.length; i++) if (!seen[i] && d[i * 4 + 3] < 250) {
    const a = d[i * 4 + 3] / 255;
    d[i * 4] = d[i * 4] * a + r * (1 - a); d[i * 4 + 1] = d[i * 4 + 1] * a + g * (1 - a); d[i * 4 + 2] = d[i * 4 + 2] * a + b * (1 - a); d[i * 4 + 3] = 255;
  }
  o.putImageData(img, 0, 0);
  ctx.drawImage(off, x - pad, y - base, w, h);
}
function drawSeg(ctx, s, x, y, size, k) {
  if (s.holes) return drawSegHoles(ctx, s, x, y, size, k);
  if (s.sy && s.sy !== 1) { ctx.save(); ctx.translate(x, y); ctx.scale(1, s.sy); drawSeg(ctx, { ...s, sy: 1 }, 0, 0, size, k); ctx.restore(); return; }
  setFont(ctx, s.f, size);
  ctx.textAlign = 'left'; ctx.textBaseline = 'alphabetic'; ctx.lineJoin = 'round'; ctx.miterLimit = 2;
  const strokes = s.strokes || [];
  strokes.forEach((st, i) => {
    ctx.save();
    if (i === 0 && s.shadow) { ctx.shadowColor = s.shadow.c; ctx.shadowBlur = (s.shadow.b || 0) * k; ctx.shadowOffsetX = (s.shadow.x || 0) * k; ctx.shadowOffsetY = (s.shadow.y || 0) * k; }
    ctx.lineWidth = st[0] * k;
    ctx.strokeStyle = st[1] === 'fill' ? fillOf(ctx, s, y, size) : st[1];
    ctx.strokeText(s.t, x, y);
    ctx.restore();
  });
  ctx.save();
  if (!strokes.length && s.shadow) { ctx.shadowColor = s.shadow.c; ctx.shadowBlur = (s.shadow.b || 0) * k; ctx.shadowOffsetX = (s.shadow.x || 0) * k; ctx.shadowOffsetY = (s.shadow.y || 0) * k; }
  ctx.fillStyle = fillOf(ctx, s, y, size);
  ctx.fillText(s.t, x, y);
  ctx.restore();
}
// Lays out coloured runs on one baseline; shrinks the whole line when it would pass maxW.
function drawRun(ctx, segs, x, y, o = {}) {
  segs = segs.filter(s => s.t);
  if (!segs.length) return { x, w: 0, k: 1, end: x };
  const gap = o.gap || 0;
  const widths = segs.map(s => segWidth(ctx, s));
  const total = widths.reduce((a, b) => a + b, 0) + gap * (segs.length - 1);
  const k = o.maxW && total > o.maxW ? o.maxW / total : 1;
  let cx = o.align === 'center' ? x - total * k / 2 : o.align === 'right' ? x - total * k : x;
  const start = cx;
  segs.forEach((s, i) => {
    drawSeg(ctx, s, cx, y + (s.dy || 0) * k, s.size * k, k);
    cx += widths[i] * k + gap * k;
  });
  return { x: start, w: total * k, k, end: start + total * k };
}
function measureRun(ctx, segs, o = {}) {
  segs = segs.filter(s => s.t);
  const total = segs.reduce((a, s) => a + segWidth(ctx, s), 0) + (o.gap || 0) * Math.max(0, segs.length - 1);
  const k = o.maxW && total > o.maxW ? o.maxW / total : 1;
  return { w: total * k, k };
}
function radial(ctx, x, y, r, color, a) {
  const g = ctx.createRadialGradient(x, y, 0, x, y, r);
  g.addColorStop(0, hexA(color, a)); g.addColorStop(1, hexA(color, 0));
  ctx.fillStyle = g; ctx.fillRect(x - r, y - r, r * 2, r * 2);
}
function hexA(hex, a) { const n = parseInt(hex.slice(1), 16); return `rgba(${n >> 16 & 255},${n >> 8 & 255},${n & 255},${a})`; }
function rrect(ctx, x, y, w, h, r) { ctx.beginPath(); ctx.moveTo(x + r, y); ctx.arcTo(x + w, y, x + w, y + h, r); ctx.arcTo(x + w, y + h, x, y + h, r); ctx.arcTo(x, y + h, x, y, r); ctx.arcTo(x, y, x + w, y, r); ctx.closePath(); }
function cover(ctx, img, x, y, w, h) {
  const iw = img.width, ih = img.height, s = Math.max(w / iw, h / ih);
  const sw = w / s, sh = h / s;
  ctx.drawImage(img, (iw - sw) / 2, (ih - sh) / 2, sw, sh, x, y, w, h);
}

// Person placement: the head box (hair top to chin) is scaled to the template's target size
// and centred on its target point; each thumbnail's own size/x/y adjustment is applied on top.
const NO_ADJ = { s: 1, x: 0, y: 0 };
function adjNow() { return (state.adj && state.adj[state.curIdx]) || NO_ADJ; }
function placeAt(P, t, s) {
  const a = adjNow(), hx = P.head.x + P.head.w / 2, hy = P.head.y + P.head.h / 2;
  return { s, dx: t.cx - hx * s + a.x, dy: t.top + t.headH / 2 - hy * s + a.y };
}
function fitPerson(P, t) {
  const base = t.headH / P.head.h, hy = P.head.y + P.head.h / 2;
  // grow a little so the shoulders reach the bottom edge, but never into an oversized face
  const reach = (H + 4 - t.top - t.headH / 2) / Math.max(1, P.H - hy);
  return placeAt(P, t, Math.max(base, Math.min(reach, base * 1.3)) * adjNow().s);
}
function fadedBottom(P) {
  if (P.faded) return P.faded;
  const c = document.createElement('canvas'); c.width = P.W; c.height = P.H;
  const x = c.getContext('2d'); x.drawImage(P.img, 0, 0);
  x.globalCompositeOperation = 'destination-out';
  const y0 = P.H * 0.86, g = x.createLinearGradient(0, y0, 0, P.H);
  g.addColorStop(0, 'rgba(0,0,0,0)'); g.addColorStop(1, 'rgba(0,0,0,1)');
  x.fillStyle = g; x.fillRect(0, y0, P.W, P.H - y0);
  return (P.faded = c);
}
function drawPersonCut(ctx, t) {
  const P = state.person.cut || state.person.placeholder;
  if (!P) return;
  const { s, dx, dy } = fitPerson(P, t);
  // a photo cropped above the waist would end in a hard line mid-frame; soften that edge
  const img = P !== state.person.placeholder && dy + P.H * s < H - 2 ? fadedBottom(P) : P.img;
  const hcx = dx + (P.head.x + P.head.w / 2) * s;
  ctx.save();
  if (state.pFlip) { ctx.translate(2 * hcx, 0); ctx.scale(-1, 1); }
  if (t.shadow) { ctx.shadowColor = 'rgba(0,0,0,.30)'; ctx.shadowBlur = 28; ctx.shadowOffsetY = 10; }
  ctx.imageSmoothingEnabled = true; ctx.imageSmoothingQuality = 'high';
  ctx.drawImage(img, dx, dy, P.W * s, P.H * s);
  ctx.restore();
}
// Draws the person for a template: cut-out when available, otherwise the original photo
// faded in from the left so it still blends.
function drawPerson(ctx, t) {
  const p = state.person;
  if (p.cut || !p.photo) return drawPersonCut(ctx, t);
  drawPhotoFaded(ctx, t, t.fadeX ?? 640, 140);
}
function drawPhotoFaded(ctx, t, x0, fade) {
  const P = state.person.photo;
  const s = Math.max(fitPerson(P, t).s, (W - x0) / P.W, H / P.H);
  let { dx, dy } = placeAt(P, t, s);
  dx = Math.min(dx, x0); dx = Math.max(dx, W - P.W * s);
  dy = Math.min(dy, 0); dy = Math.max(dy, H - P.H * s);
  const tr = ctx.getTransform();
  const scale = Math.hypot(tr.a, tr.b) || 1;
  const off = document.createElement('canvas');
  off.width = Math.round(W * scale); off.height = Math.round(H * scale);
  const o = off.getContext('2d');
  o.scale(scale, scale);
  o.save();
  if (state.pFlip) { o.translate(x0 + W, 0); o.scale(-1, 1); }
  o.imageSmoothingQuality = 'high';
  o.drawImage(P.img, dx, dy, P.W * s, P.H * s);
  o.restore();
  o.globalCompositeOperation = 'destination-in';
  const g = o.createLinearGradient(x0, 0, x0 + fade, 0);
  g.addColorStop(0, 'rgba(0,0,0,0)'); g.addColorStop(1, 'rgba(0,0,0,1)');
  o.fillStyle = g; o.fillRect(x0, 0, W - x0, H);
  ctx.drawImage(off, 0, 0, W, H);
}

const BLACK = '#000000';
const C = { red: '#FE4116', yellowA: '#FBFF26', yellowB: '#FDED51', cyan: '#00FFF8', navyLine: '#0845A9', band: '#0C1489', bandEdge: '#F9DE19', green: '#0FFC04', redBox: '#FF4016', redT4: '#EF3C18' };

/* 시안 1 · 임팩트 3단 (레퍼런스 ①) */
function bgT1(ctx) {
  {
    const g = ctx.createLinearGradient(0, 0, W, H);
    g.addColorStop(0, '#c8a294'); g.addColorStop(.28, '#6d8a8f'); g.addColorStop(.6, '#2f5560'); g.addColorStop(1, '#1b2c37');
    ctx.fillStyle = g; ctx.fillRect(0, 0, W, H);
    radial(ctx, 140, 120, 260, '#f2c1b2', .55);
    radial(ctx, 470, 140, 170, '#ff9a8f', .38);
    radial(ctx, 790, 330, 300, '#ff8e6e', .34);
    radial(ctx, 980, 70, 150, '#ffc0b0', .30);
    radial(ctx, 620, 610, 180, '#7fe0e8', .18);
    // soft molecule motif — science feel without body imagery
    ctx.save(); ctx.strokeStyle = 'rgba(255,255,255,.18)'; ctx.fillStyle = 'rgba(255,255,255,.14)'; ctx.lineWidth = 3;
    const pts = [[560, 70], [650, 120], [740, 80], [820, 150], [700, 200], [610, 190]];
    ctx.beginPath(); pts.forEach((p, i) => { const q = pts[(i + 1) % pts.length]; ctx.moveTo(p[0], p[1]); ctx.lineTo(q[0], q[1]); }); ctx.moveTo(650, 120); ctx.lineTo(700, 200); ctx.stroke();
    pts.forEach((p, i) => { ctx.beginPath(); ctx.arc(p[0], p[1], 9 + (i % 3) * 4, 0, Math.PI * 2); ctx.fill(); });
    ctx.restore();
  }
  const v = ctx.createLinearGradient(0, H, 0, H * .35);
  v.addColorStop(0, 'rgba(0,0,0,.30)'); v.addColorStop(1, 'rgba(0,0,0,0)');
  ctx.fillStyle = v; ctx.fillRect(0, 0, W, H);
}
function drawT1(ctx, d) {
  bgT1(ctx);
  drawPerson(ctx, { cx: 1088, top: 92, headH: 250, fadeX: 780 });
  drawRun(ctx, [{ t: d.l1, f: R('main', F.noto9), size: 106, fill: '#FFFFFF', strokes: [[22, BLACK], [3, 'fill']] }], 32, 318, { maxW: 880 });
  drawRun(ctx, [
    { t: d.l2a, f: R('main', F.noto9), size: 146, fill: C.red, strokes: [[27, BLACK], [4, 'fill']] },
    { t: d.l2b, f: R('main', F.noto9), size: 146, fill: C.yellowA, strokes: [[27, BLACK], [4, 'fill']] },
  ], 38, 500, { maxW: 860, gap: 38 });
  drawRun(ctx, [{ t: d.l3, f: R('main', F.noto9), size: 146, fill: C.cyan, strokes: [[27, BLACK], [4, 'fill']] }], 30, 684, { maxW: 1190 });
}

/* 시안 2 · 블랙 말풍선 (레퍼런스 ②) */
function drawT2(ctx, d) {
  ctx.fillStyle = '#000'; ctx.fillRect(0, 0, W, H);
  drawPerson(ctx, { cx: 1100, top: 28, headH: 395, fadeX: 760 });
  const fb = 3, sy = 1.08; // slight weight and height so Jua matches the reference's tall rounded letters
  drawRun(ctx, [
    { t: d.a1, f: R('top', F.jua), size: 124, sy, holes: true, fill: C.yellowB, strokes: [[34, C.navyLine], [fb, C.yellowB]] },
    { t: d.a2, f: R('top', F.jua), size: 124, sy, holes: true, fill: C.red, strokes: [[34, '#FFFFFF'], [fb, C.red]] },
  ], 24, 150, { maxW: 1070, gap: 30 });
  drawRun(ctx, [
    { t: d.b1, f: R('top', F.jua), size: 142, sy, holes: true, fill: C.red, strokes: [[34, C.yellowB], [fb, C.red]] },
    { t: d.b2, f: R('top', F.jua), size: 142, sy, holes: true, fill: C.yellowB, strokes: [[34, C.navyLine], [fb, C.yellowB]] },
  ], 24, 340, { maxW: 880, gap: /^(라고|이라고|일까|인가|일지|이야|야|죠|이죠|래|이래)/.test(d.b2 || '') ? 4 : 22 });
  const band = (y, h, segsFn, maxBand) => {
    const segs = segsFn();
    const m = measureRun(ctx, segs, { maxW: maxBand - 60 });
    const bw = Math.min(maxBand, m.w + 64);
    ctx.fillStyle = '#000'; ctx.fillRect(0, y - 4, bw + 4, h + 8);
    ctx.fillStyle = C.band; ctx.fillRect(0, y, bw, h);
    drawRun(ctx, segs, 30, y + h * 0.86, { maxW: maxBand - 60 });
  };
  band(374, 148, () => [
    { t: d.c1, f: R('band', F.dohyeon), size: 140, fill: '#FFFFFF', strokes: [[13, BLACK]] },
    { t: d.c2, f: R('band', F.dohyeon), size: 140, fill: C.red, strokes: [[16, C.bandEdge]] },
  ], 930);
  band(548, 156, () => [
    { t: d.d1, f: R('band', F.dohyeon), size: 146, fill: '#FFFFFF', strokes: [[13, BLACK]] },
    { t: d.d2, f: R('band', F.dohyeon), size: 146, fill: C.red, strokes: [[16, C.bandEdge]] },
  ], 760);
}

/* 시안 3 · 클리닉 프리미엄 (레퍼런스 ③) */
function bgT3(ctx) {
  const g = ctx.createLinearGradient(0, 0, 0, H);
  g.addColorStop(0, '#f4f8fd'); g.addColorStop(.6, '#dfe9f4'); g.addColorStop(1, '#c9d6e4');
  ctx.fillStyle = g; ctx.fillRect(0, 0, W, H);
  // window light
  ctx.fillStyle = 'rgba(255,255,255,.55)';
  rrect(ctx, 930, 30, 330, 470, 8); ctx.fill();
  ctx.fillStyle = 'rgba(190,210,232,.45)';
  for (let i = 0; i < 4; i++) ctx.fillRect(950 + i * 80, 40, 6, 450);
  radial(ctx, 1080, 220, 300, '#ffffff', .7);
  // sign board with a blue cross
  ctx.save(); ctx.shadowColor = 'rgba(30,60,100,.18)'; ctx.shadowBlur = 16;
  ctx.fillStyle = 'rgba(255,255,255,.92)'; rrect(ctx, 1132, 160, 128, 230, 8); ctx.fill(); ctx.restore();
  ctx.fillStyle = '#2f73db'; ctx.fillRect(1182, 182, 28, 74); ctx.fillRect(1159, 205, 74, 28);
  // greenery bokeh on the left
  [[40, 230, 70, '#6fa35a', .45], [90, 330, 90, '#86b66c', .4], [20, 430, 80, '#5d8f4c', .4], [130, 180, 50, '#9cc77f', .35], [70, 520, 70, '#7aa864', .35]].forEach(b => radial(ctx, ...b));
  [[60, 200], [120, 260], [40, 300], [150, 340], [95, 420], [30, 480]].forEach(([x, y], i) => radial(ctx, x, y, 16 + (i % 3) * 5, '#fffbe6', .85));
}
function brushBanner(ctx, x0, x1, yTop, yBot, color) {
  ctx.save();
  ctx.fillStyle = color;
  ctx.beginPath();
  ctx.moveTo(x0 + 6, yTop + 22);
  ctx.lineTo(x1 - 4, yTop);
  const rj = [[x1 + 10, yTop + 14], [x1 - 6, yTop + 30], [x1 + 8, yTop + 52], [x1 - 4, yTop + 74], [x1 + 6, yBot - 18], [x1 - 10, yBot]];
  rj.forEach(p => ctx.lineTo(p[0], p[1]));
  ctx.lineTo(x0 + 18, yBot + 20);
  const lj = [[x0 - 4, yBot + 6], [x0 + 10, yBot - 16], [x0 - 8, yTop + 70], [x0 + 6, yTop + 48], [x0 - 6, yTop + 32]];
  lj.forEach(p => ctx.lineTo(p[0], p[1]));
  ctx.closePath(); ctx.fill();
  ctx.globalAlpha = .22; ctx.strokeStyle = '#5c0508'; ctx.lineCap = 'round';
  [[yTop + 30, 3], [yTop + 58, 2], [yBot - 6, 3]].forEach(([y, w], i) => { ctx.lineWidth = w; ctx.beginPath(); ctx.moveTo(x0 + 40 + i * 30, y + 12 - i * 2); ctx.lineTo(x1 - 60, y - 6); ctx.stroke(); });
  ctx.restore();
}
function drawT3(ctx, d) {
  bgT3(ctx);
  // attention ticks beside the person, as in the reference
  ctx.save(); ctx.strokeStyle = '#1f6fe0'; ctx.lineWidth = 7; ctx.lineCap = 'round';
  [[742, 352, 768, 372], [762, 320, 778, 350], [790, 318, 792, 346]].forEach(([a, b, c2, e]) => { ctx.beginPath(); ctx.moveTo(a, b); ctx.lineTo(c2, e); ctx.stroke(); });
  ctx.restore();
  drawPerson(ctx, { cx: 928, top: 40, headH: 262, shadow: true, fadeX: 700 });
  // banner
  const bSegs = [
    { t: d.banner1, f: R('banner', R('body', F.noto9)), size: 80, fill: '#FFFFFF', strokes: [[14, BLACK]] },
    { t: d.banner2, f: R('banner', R('body', F.noto9)), size: 80, fill: '#FCF911', strokes: [[14, BLACK]] },
  ];
  const bm = measureRun(ctx, bSegs, { maxW: 740, gap: 20 });
  brushBanner(ctx, 22, Math.min(830, 42 + bm.w + 46), 28, 128, '#CD1B1E');
  drawRun(ctx, bSegs, 44, 122, { maxW: 740, gap: 20 });
  // stacked headline
  drawRun(ctx, [{ t: d.big, f: R('big', F.bhs), size: 228, grad: ['#FFFDA8', '#FDFC04', '#FDD501'], strokes: [[30, BLACK]], shadow: { c: 'rgba(0,0,0,.55)', x: 7, y: 9, b: 0 } }], 330, 346, { maxW: 600, align: 'center' });
  drawRun(ctx, [{ t: d.green, f: R('big', F.bhs), size: 102, grad: ['#D2FF6A', '#7CF925', '#38BE2A'], strokes: [[22, '#081B04']], shadow: { c: 'rgba(0,0,0,.35)', x: 4, y: 5, b: 0 } }], 40, 454, { maxW: 610 });
  drawRun(ctx, [{ t: d.white, f: R('body', F.noto9), size: 84, fill: '#FFFFFF', strokes: [[18, BLACK]] }], 40, 543, { maxW: 680 });
  const cta = drawRun(ctx, [{ t: d.cta, f: R('body', F.noto9), size: 92, grad: ['#FFFFFF', '#3BF9FC', '#1FD3F2'], strokes: [[20, '#071F3E']] }], 40, 638, { maxW: 640 });
  // red brush underline
  ctx.save(); ctx.fillStyle = '#FD3E37';
  const ux0 = 44, ux1 = Math.max(260, cta.end);
  ctx.beginPath(); ctx.moveTo(ux0, 664); ctx.quadraticCurveTo((ux0 + ux1) / 2, 650, ux1, 652); ctx.lineTo(ux1 - 8, 668); ctx.quadraticCurveTo((ux0 + ux1) / 2, 676, ux0 + 20, 686); ctx.closePath(); ctx.fill();
  ctx.restore();
  // handwritten note
  ctx.save(); ctx.translate(1160, 92); ctx.rotate(-0.07);
  ctx.fillStyle = '#0F2E5D'; setFont(ctx, R('hand', F.pen), 46); ctx.textAlign = 'center'; ctx.textBaseline = 'alphabetic';
  ctx.fillText(d.note1, -6, -6, 230); ctx.fillText(d.note2, 6, 38, 230);
  ctx.strokeStyle = '#0F2E5D'; ctx.lineWidth = 2.5; ctx.lineCap = 'round';
  ctx.beginPath(); ctx.moveTo(-96, 64); ctx.quadraticCurveTo(0, 46, 84, 50); ctx.stroke();
  ctx.beginPath(); ctx.moveTo(84, 50); ctx.lineTo(76, 44); ctx.moveTo(84, 50); ctx.lineTo(76, 58); ctx.stroke();
  ctx.restore();
  // checklist card
  const items = (d.checks || '').split('/').map(s => s.trim()).filter(Boolean).slice(0, 3);
  if (items.length) {
    setFont(ctx, R('check', F.noto5), 23);
    const tw = Math.min(170, Math.max(...items.map(s => ctx.measureText(s).width)));
    const cw = tw + 84, ch = 20 + items.length * 32, cx = W - 22 - cw, cy = H - 26 - ch;
    ctx.save(); ctx.shadowColor = 'rgba(20,40,70,.18)'; ctx.shadowBlur = 14;
    ctx.fillStyle = 'rgba(255,255,255,.9)'; rrect(ctx, cx, cy, cw, ch, 10); ctx.fill(); ctx.restore();
    ctx.strokeStyle = 'rgba(15,46,93,.18)'; ctx.lineWidth = 1.5; rrect(ctx, cx, cy, cw, ch, 10); ctx.stroke();
    ctx.strokeStyle = '#0F2E5D'; ctx.lineWidth = 2.5; ctx.beginPath(); ctx.arc(cx + 28, cy + 30, 13, 0, Math.PI * 2); ctx.stroke();
    ctx.strokeStyle = '#1f6fe0'; ctx.lineWidth = 4; ctx.lineCap = 'round'; ctx.beginPath(); ctx.moveTo(cx + 21, cy + 30); ctx.lineTo(cx + 27, cy + 37); ctx.lineTo(cx + 40, cy + 20); ctx.stroke();
    ctx.fillStyle = '#1d2a44'; setFont(ctx, R('check', F.noto5), 23);
    items.forEach((s, i) => ctx.fillText(s, cx + 56, cy + 38 + i * 32, tw));
  }
  // yellow frame
  ctx.strokeStyle = '#FFFB04'; ctx.lineWidth = 22; ctx.strokeRect(0, 0, W, H);
}

/* 시안 4 · 다크 스튜디오 (레퍼런스 ④) */
function drawT4(ctx, d) {
  ctx.fillStyle = '#000'; ctx.fillRect(0, 0, W, H);
  const head = { cx: 1062, top: 46, headH: 250 };
  const ph = state.person.photo;
  let usePhoto = !!ph && !state.person.isPng;
  if (usePhoto && state.person.cut) {
    const fit = fitPerson(ph, head);
    if (Math.max((W - 470) / ph.W, H / ph.H) > fit.s * 1.25) usePhoto = false;
  }
  if (usePhoto) {
    drawPhotoFaded(ctx, head, 470, 50);
  } else {
    const g = ctx.createLinearGradient(480, 0, W, H);
    g.addColorStop(0, '#2b2219'); g.addColorStop(1, '#100c09');
    ctx.fillStyle = g; ctx.fillRect(480, 0, W - 480, H);
    ctx.fillStyle = 'rgba(92,70,50,.35)';
    [130, 290, 450].forEach(y => ctx.fillRect(500, y, 760, 10));
    [[620, 200, '#ffcf8a', .16], [860, 90, '#ffd9a0', .12], [700, 420, '#f6b36b', .10], [1180, 260, '#ffe2b5', .12]].forEach(([x, y, c, a]) => radial(ctx, x, y, 120, c, a));
    const fade = ctx.createLinearGradient(480, 0, 560, 0); fade.addColorStop(0, 'rgba(0,0,0,1)'); fade.addColorStop(1, 'rgba(0,0,0,0)');
    ctx.fillStyle = fade; ctx.fillRect(480, 0, 80, H);
    drawPersonCut(ctx, head);
  }
  const boxSeg = [{ t: d.box, f: R('main', F.noto7), size: 112, fill: '#FFFFFF' }];
  const bm = measureRun(ctx, boxSeg, { maxW: 960 });
  ctx.fillStyle = C.redBox; ctx.fillRect(0, 60, Math.min(1010, bm.w + 44), 166);
  drawRun(ctx, boxSeg, 20, 194, { maxW: 960 });
  drawRun(ctx, [{ t: d.y, f: R('main', F.noto7), size: 116, fill: C.yellowA, strokes: [[14, BLACK]] }], 18, 352, { maxW: 900 });
  drawRun(ctx, [{ t: d.g, f: R('main', F.noto7), size: 116, fill: C.green, strokes: [[14, BLACK]] }], 18, 508, { maxW: 900 });
  const r = d.r || '', em = (d.em || '').trim();
  let segs = [{ t: r, f: R('main', F.noto7), size: 114, fill: C.redT4, strokes: [[16, BLACK]] }];
  const at = em ? r.indexOf(em) : -1;
  if (at >= 0) {
    segs = [
      { t: r.slice(0, at), f: R('main', F.noto7), size: 114, fill: C.redT4, strokes: [[16, BLACK]] },
      { t: em, f: R('main', F.noto7), size: 124, fill: C.yellowA, strokes: [[16, BLACK]] },
      { t: r.slice(at + em.length), f: R('main', F.noto7), size: 114, fill: C.redT4, strokes: [[16, BLACK]] },
    ];
  }
  drawRun(ctx, segs, 18, 664, { maxW: 1200 });
}

/* 시안 5 · 화이트 정보형 */
function drawT5(ctx, d) {
  const g = ctx.createLinearGradient(0, 0, 0, H);
  g.addColorStop(0, '#ffffff'); g.addColorStop(1, '#eef1f6');
  ctx.fillStyle = g; ctx.fillRect(0, 0, W, H);
  ctx.fillStyle = '#d6dde8';
  for (let y = 40; y < 300; y += 26) for (let x = 760; x < 1260; x += 26) { ctx.beginPath(); ctx.arc(x, y, 2.4, 0, Math.PI * 2); ctx.fill(); }
  ctx.fillStyle = '#dbe7fb'; ctx.beginPath(); ctx.arc(1040, 400, 330, 0, Math.PI * 2); ctx.fill();
  drawPerson(ctx, { cx: 1040, top: 78, headH: 262, shadow: true, fadeX: 760 });
  // tag pill
  setFont(ctx, R('body', F.noto8), 40);
  const tw = Math.min(520, ctx.measureText(d.tag || '').width);
  if (d.tag) {
    ctx.fillStyle = C.band; rrect(ctx, 36, 36, tw + 48, 66, 33); ctx.fill();
    ctx.fillStyle = '#fff'; ctx.textBaseline = 'alphabetic'; ctx.fillText(d.tag, 60, 83, 520);
  }
  drawRun(ctx, [{ t: d.l1, f: R('body', F.noto9), size: 92, fill: '#111111', strokes: [[12, '#FFFFFF']] }], 36, 214, { maxW: 780 });
  drawRun(ctx, [{ t: d.l2, f: R('big', F.bhs), size: 182, fill: C.red, strokes: [[18, '#111111']], shadow: { c: 'rgba(120,20,0,.45)', x: 0, y: 8, b: 0 } }], 32, 404, { maxW: 800 });
  const l3 = [{ t: d.l3, f: R('body', F.noto9), size: 88, fill: '#111111' }];
  const m = measureRun(ctx, l3, { maxW: 780 });
  ctx.save(); ctx.fillStyle = '#FFF200';
  ctx.beginPath(); ctx.moveTo(28, 478); ctx.lineTo(36 + m.w + 26, 470); ctx.lineTo(36 + m.w + 18, 548); ctx.lineTo(24, 552); ctx.closePath(); ctx.fill(); ctx.restore();
  drawRun(ctx, l3, 36, 534, { maxW: 780 });
  ctx.fillStyle = C.band; ctx.fillRect(0, 600, W, 120);
  ctx.fillStyle = '#FFE600'; ctx.fillRect(0, 600, W, 8);
  drawRun(ctx, [{ t: d.band, f: R('body', F.noto8), size: 66, fill: '#FFFFFF' }], 40, 685, { maxW: 1200 });
}

const TPLS = [
  { id: 't1', name: '임팩트 3단', ref: '레퍼런스 ① 스타일', draw: drawT1, roles: [['main', '글자 전체', 'noto9']], fields: [['l1', '1줄 · 흰색', 11], ['l2a', '2줄 · 빨강', 4], ['l2b', '2줄 · 노랑', 5], ['l3', '3줄 · 하늘색', 10]] },
  { id: 't2', name: '블랙 말풍선', ref: '레퍼런스 ② 스타일', draw: drawT2, roles: [['top', '위 두 줄', 'jua'], ['band', '남색 띠', 'dohyeon']], fields: [['a1', '1줄 · 노랑', 5], ['a2', '1줄 · 빨강', 5], ['b1', '2줄 · 빨강', 5], ['b2', '2줄 · 노랑 물음', 4], ['c1', '띠1 · 흰색', 5], ['c2', '띠1 · 강조', 6], ['d1', '띠2 · 흰색', 5], ['d2', '띠2 · 강조', 4]] },
  { id: 't3', name: '클리닉 프리미엄', ref: '레퍼런스 ③ 스타일', draw: drawT3, roles: [['banner', '빨간 배너', 'noto9'], ['big', '큰 제목·초록 줄', 'bhs'], ['body', '흰색·하늘색 줄', 'noto9'], ['hand', '손글씨 메모', 'pen'], ['check', '체크리스트', 'noto5']], fields: [['banner1', '배너 · 흰색', 6], ['banner2', '배너 · 노랑', 9], ['big', '메인 키워드', 3], ['green', '초록 줄', 8], ['white', '흰색 줄', 11], ['cta', '하늘색 줄', 9], ['note1', '손글씨 1', 7], ['note2', '손글씨 2', 7], ['checks', '체크리스트 (/로 구분)', 26]] },
  { id: 't4', name: '다크 스튜디오', ref: '레퍼런스 ④ 스타일', draw: drawT4, roles: [['main', '글자 전체', 'noto7']], fields: [['box', '빨간 박스', 9], ['y', '노랑 줄', 8], ['g', '초록 줄', 7], ['r', '주황 줄', 12], ['em', '주황 줄 강조 단어', 6]] },
  { id: 't5', name: '화이트 정보형', ref: '같은 계열 응용', draw: drawT5, roles: [['body', '태그·본문·띠', 'noto9'], ['big', '빨강 대형', 'bhs']], fields: [['tag', '상단 태그', 9], ['l1', '검정 줄', 10], ['l2', '빨강 대형', 6], ['l3', '형광펜 줄', 10], ['band', '하단 띠', 18]] },
];
const AD_FIELDS = [['headline', '주 제목', '광고 제목', 30], ['longHeadline', '부 제목', '긴 광고 제목', 90], ['description', '세부 제목', '설명', 90], ['ytTitle', '유튜브 제목', '영상 제목 권장', 100]];
const ANGLES = ['생활 습관형', '제품·브랜드 소개형', '증상 체크형', 'N가지 리스트형', '시니어 맞춤 가이드형'];

/* ───────────── 5. 인물 사진: 자동 누끼 (MediaPipe, Apache-2.0) ───────────── */
const MP_CDN = 'https://cdn.jsdelivr.net/npm/@mediapipe/tasks-vision@0.10.14';
const MODEL_CDN = 'https://storage.googleapis.com/mediapipe-models/image_segmenter/selfie_multiclass_256x256/float32/1/selfie_multiclass_256x256.tflite';
let segPromise = null;
function getSegmenter() {
  if (!segPromise) {
    segPromise = (async () => {
      const vision = await import(`${MP_CDN}/vision_bundle.mjs`);
      // Files published next to the page (mp/) are used when present; the model ships there as
      // two base64 text parts because artifact hosting serves text, not raw binaries. A page
      // hosted elsewhere without that folder loads the same files from the official CDNs.
      let model, wasmBinaryPath;
      try {
        const parts = await Promise.all(['mp/seg-1.txt', 'mp/seg-2.txt'].map(async u => {
          const r = await fetch(new URL(u, document.baseURI));
          if (!r.ok) throw new Error('model ' + r.status);
          const bin = atob((await r.text()).trim());
          const arr = new Uint8Array(bin.length);
          for (let i = 0; i < bin.length; i++) arr[i] = bin.charCodeAt(i);
          return arr;
        }));
        model = new Uint8Array(parts[0].length + parts[1].length);
        model.set(parts[0]); model.set(parts[1], parts[0].length);
        wasmBinaryPath = new URL('mp/vision_wasm_internal.wasm', document.baseURI).href;
      } catch (e) {
        const r = await fetch(MODEL_CDN);
        if (!r.ok) throw new Error('model ' + r.status);
        model = new Uint8Array(await r.arrayBuffer());
        wasmBinaryPath = `${MP_CDN}/wasm/vision_wasm_internal.wasm`;
      }
      const fileset = { wasmLoaderPath: `${MP_CDN}/wasm/vision_wasm_internal.js`, wasmBinaryPath };
      return vision.ImageSegmenter.createFromOptions(fileset, {
        baseOptions: { modelAssetBuffer: model, delegate: 'CPU' },
        runningMode: 'IMAGE', outputConfidenceMasks: true, outputCategoryMask: false,
      });
    })();
    segPromise.catch(() => { segPromise = null; });
  }
  return segPromise;
}
function canvasFrom(src, maxSide) {
  const w0 = src.width, h0 = src.height, s = Math.min(1, maxSide / Math.max(w0, h0));
  const c = document.createElement('canvas');
  c.width = Math.max(1, Math.round(w0 * s)); c.height = Math.max(1, Math.round(h0 * s));
  const x = c.getContext('2d', { willReadFrequently: true });
  x.imageSmoothingQuality = 'high';
  x.drawImage(src, 0, 0, c.width, c.height);
  return c;
}
async function decodeImage(file) {
  try { return await createImageBitmap(file, { imageOrientation: 'from-image' }); } catch (e) { /* fall through */ }
  return await new Promise((res, rej) => { const u = URL.createObjectURL(file); const i = new Image(); i.onload = () => { res(i); }; i.onerror = () => rej(new Error('decode')); i.src = u; });
}
function alphaInfo(c) {
  const d = c.getContext('2d', { willReadFrequently: true }).getImageData(0, 0, c.width, c.height).data;
  let clear = 0; for (let i = 3; i < d.length; i += 16) if (d[i] < 200) clear++;
  return clear / (d.length / 16) > 0.03;
}
function bboxOf(mask, w, h, thr) {
  let x0 = w, y0 = h, x1 = -1, y1 = -1;
  for (let y = 0; y < h; y++) for (let x = 0; x < w; x++) if (mask[y * w + x] > thr) { if (x < x0) x0 = x; if (x > x1) x1 = x; if (y < y0) y0 = y; if (y > y1) y1 = y; }
  return x1 < 0 ? null : { x: x0, y: y0, w: x1 - x0 + 1, h: y1 - y0 + 1 };
}
function boxBlur(src, w, h, r) {
  const tmp = new Float32Array(w * h), out = new Float32Array(w * h), n = 2 * r + 1;
  for (let y = 0; y < h; y++) {
    const row = y * w; let acc = 0;
    for (let x = -r; x <= r; x++) acc += src[row + Math.min(w - 1, Math.max(0, x))];
    for (let x = 0; x < w; x++) { tmp[row + x] = acc / n; acc += src[row + Math.min(w - 1, x + r + 1)] - src[row + Math.max(0, x - r)]; }
  }
  for (let x = 0; x < w; x++) {
    let acc = 0;
    for (let y = -r; y <= r; y++) acc += tmp[Math.min(h - 1, Math.max(0, y)) * w + x];
    for (let y = 0; y < h; y++) { out[y * w + x] = acc / n; acc += tmp[Math.min(h - 1, y + r + 1) * w + x] - tmp[Math.max(0, y - r) * w + x]; }
  }
  return out;
}
function grayOf(c) {
  const d = c.getContext('2d', { willReadFrequently: true }).getImageData(0, 0, c.width, c.height).data;
  const g = new Float32Array(c.width * c.height);
  for (let i = 0, p = 0; i < g.length; i++, p += 4) g[i] = (0.299 * d[p] + 0.587 * d[p + 1] + 0.114 * d[p + 2]) / 255;
  return g;
}
function bilinear(src, sw, sh, dw, dh) {
  const out = new Float32Array(dw * dh), fx = sw / dw, fy = sh / dh;
  for (let y = 0; y < dh; y++) {
    const sy = Math.min(sh - 1, Math.max(0, (y + 0.5) * fy - 0.5)), y0 = Math.floor(sy), y1 = Math.min(sh - 1, y0 + 1), ty = sy - y0;
    for (let x = 0; x < dw; x++) {
      const sx = Math.min(sw - 1, Math.max(0, (x + 0.5) * fx - 0.5)), x0 = Math.floor(sx), x1 = Math.min(sw - 1, x0 + 1), tx = sx - x0;
      const a = src[y0 * sw + x0] * (1 - tx) + src[y0 * sw + x1] * tx, b = src[y1 * sw + x0] * (1 - tx) + src[y1 * sw + x1] * tx;
      out[y * dw + x] = a * (1 - ty) + b * ty;
    }
  }
  return out;
}
// Fast guided filter: coefficients solved at mask resolution, applied at full resolution,
// so hair and shoulder edges follow the photo instead of the coarse 256px model mask.
function refineAlpha(pLow, lowCanvas, fullCanvas) {
  const lw = lowCanvas.width, lh = lowCanvas.height, fw = fullCanvas.width, fh = fullCanvas.height;
  const I = grayOf(lowCanvas), r = Math.max(3, Math.round(Math.max(lw, lh) / 160)), eps = 0.0025;
  const mI = boxBlur(I, lw, lh, r), mP = boxBlur(pLow, lw, lh, r);
  const II = new Float32Array(I.length), IP = new Float32Array(I.length);
  for (let i = 0; i < I.length; i++) { II[i] = I[i] * I[i]; IP[i] = I[i] * pLow[i]; }
  const mII = boxBlur(II, lw, lh, r), mIP = boxBlur(IP, lw, lh, r);
  const A = new Float32Array(I.length), B = new Float32Array(I.length);
  for (let i = 0; i < I.length; i++) { const v = mII[i] - mI[i] * mI[i], cv = mIP[i] - mI[i] * mP[i]; A[i] = cv / (v + eps); B[i] = mP[i] - A[i] * mI[i]; }
  const mA = boxBlur(A, lw, lh, r), mB = boxBlur(B, lw, lh, r);
  const Af = bilinear(mA, lw, lh, fw, fh), Bf = bilinear(mB, lw, lh, fw, fh), If = grayOf(fullCanvas), pF = bilinear(pLow, lw, lh, fw, fh);
  const out = new Float32Array(fw * fh);
  for (let i = 0; i < out.length; i++) {
    let q = Af[i] * If[i] + Bf[i];
    q = 0.75 * q + 0.25 * pF[i];
    q = Math.min(1, Math.max(0, (q - 0.12) / 0.76));
    out[i] = q * q * (3 - 2 * q);
  }
  return out;
}
function headFromAlpha(alpha, w, h) {
  const bb = bboxOf(alpha, w, h, 0.5);
  if (!bb) return { x: w * 0.3, y: h * 0.08, w: w * 0.4, h: h * 0.4 };
  const widths = [];
  for (let y = bb.y; y < bb.y + bb.h; y++) { let x0 = -1, x1 = -1; for (let x = bb.x; x < bb.x + bb.w; x++) if (alpha[y * w + x] > 0.5) { if (x0 < 0) x0 = x; x1 = x; } widths.push([x0, x1]); }
  let neck = Math.round(bb.h * 0.42), best = Infinity;
  for (let i = Math.round(bb.h * 0.15); i < Math.round(bb.h * 0.55); i++) { const [a, b] = widths[i] || [-1, -1]; const ww = a < 0 ? Infinity : b - a; if (ww < best) { best = ww; neck = i; } }
  let x0 = Infinity, x1 = -Infinity;
  for (let i = 0; i < neck; i++) { const [a, b] = widths[i]; if (a >= 0) { x0 = Math.min(x0, a); x1 = Math.max(x1, b); } }
  const hw = Math.max(10, x1 - x0);
  return { x: x0, y: bb.y, w: hw, h: Math.max(neck, hw * 1.15) };
}
// Pulls soft-edge colours toward nearby solid foreground so the old background does not
// leave a halo once the person sits on a new backdrop.
function decontaminate(d, alpha, w, h) {
  const n = w * h, r = Math.max(2, Math.round(Math.max(w, h) / 320));
  const wt = new Float32Array(n), R = new Float32Array(n), G = new Float32Array(n), B = new Float32Array(n);
  for (let i = 0; i < n; i++) { const k = alpha[i] > 0.92 ? 1 : 0; wt[i] = k; R[i] = d[i * 4] * k; G[i] = d[i * 4 + 1] * k; B[i] = d[i * 4 + 2] * k; }
  const bw = boxBlur(wt, w, h, r), bR = boxBlur(R, w, h, r), bG = boxBlur(G, w, h, r), bB = boxBlur(B, w, h, r);
  for (let i = 0; i < n; i++) {
    const a = alpha[i];
    if (a <= 0.01 || a >= 0.92 || bw[i] < 0.02) continue;
    let t = Math.min(1, Math.max(0, (a - 0.3) / 0.62)); t *= t;
    d[i * 4] = bR[i] / bw[i] * (1 - t) + d[i * 4] * t;
    d[i * 4 + 1] = bG[i] / bw[i] * (1 - t) + d[i * 4 + 1] * t;
    d[i * 4 + 2] = bB[i] / bw[i] * (1 - t) + d[i * 4 + 2] * t;
  }
}
function makeCut(src, alpha, head, clean) {
  const w = src.width, h = src.height;
  const id = src.getContext('2d', { willReadFrequently: true }).getImageData(0, 0, w, h);
  if (clean) decontaminate(id.data, alpha, w, h);
  for (let i = 0; i < alpha.length; i++) id.data[i * 4 + 3] = Math.round(alpha[i] * id.data[i * 4 + 3]);
  const bb = bboxOf(alpha, w, h, 0.04) || { x: 0, y: 0, w, h };
  const m = 4, x0 = Math.max(0, bb.x - m), y0 = Math.max(0, bb.y - m), x1 = Math.min(w, bb.x + bb.w + m), y1 = Math.min(h, bb.y + bb.h + m);
  const tmp = document.createElement('canvas'); tmp.width = w; tmp.height = h; tmp.getContext('2d').putImageData(id, 0, 0);
  const c = document.createElement('canvas'); c.width = x1 - x0; c.height = y1 - y0;
  c.getContext('2d').drawImage(tmp, x0, y0, c.width, c.height, 0, 0, c.width, c.height);
  return { img: c, W: c.width, H: c.height, head: { x: head.x - x0, y: head.y - y0, w: head.w, h: head.h } };
}
function runSeg(seg, canvas) {
  const res = seg.segment(canvas);
  const ms = res.confidenceMasks;
  const w = ms[0].width, h = ms[0].height;
  const bg = ms[0].getAsFloat32Array(), hairM = ms[1].getAsFloat32Array(), faceM = ms[3].getAsFloat32Array();
  const p = new Float32Array(w * h), hair = new Float32Array(w * h), face = new Float32Array(w * h);
  for (let i = 0; i < p.length; i++) { p[i] = 1 - bg[i]; hair[i] = hairM[i]; face[i] = faceM[i]; }
  if (res.close) res.close(); else ms.forEach(m => m.close && m.close());
  return { w, h, p, hair, face };
}
function largestComponent(mask, w, h, thr) {
  const lab = new Int32Array(w * h), stack = [];
  let id = 0, best = 0, bestId = 0;
  for (let i = 0; i < w * h; i++) {
    if (mask[i] <= thr || lab[i]) continue;
    id++; let n = 0; lab[i] = id; stack.push(i);
    while (stack.length) {
      const j = stack.pop(), x = j % w; n++;
      if (x > 0 && !lab[j - 1] && mask[j - 1] > thr) { lab[j - 1] = id; stack.push(j - 1); }
      if (x < w - 1 && !lab[j + 1] && mask[j + 1] > thr) { lab[j + 1] = id; stack.push(j + 1); }
      if (j >= w && !lab[j - w] && mask[j - w] > thr) { lab[j - w] = id; stack.push(j - w); }
      if (j < w * (h - 1) && !lab[j + w] && mask[j + w] > thr) { lab[j + w] = id; stack.push(j + w); }
    }
    if (n > best) { best = n; bestId = id; }
  }
  const keep = new Float32Array(w * h);
  if (bestId) for (let i = 0; i < keep.length; i++) keep[i] = lab[i] === bestId ? 1 : 0;
  return { keep, size: best };
}
// Objects held in front of the body (a microphone, a cup) are classed as background and
// would punch a hole in the chest. Background is flooded in from the top and side edges only,
// so any smaller transparent pocket left inside the person is filled back in.
function fillHoles(p, w, h, maxFrac) {
  const n = w * h, outside = new Uint8Array(n), stack = [];
  const push = i => { if (!outside[i] && p[i] < 0.5) { outside[i] = 1; stack.push(i); } };
  for (let x = 0; x < w; x++) push(x);
  for (let y = 0; y < h; y++) { push(y * w); push(y * w + w - 1); }
  const flood = (mark, test) => { while (stack.length) { const j = stack.pop(), x = j % w; if (x > 0) test(j - 1); if (x < w - 1) test(j + 1); if (j >= w) test(j - w); if (j < n - w) test(j + w); } };
  flood(outside, push);
  let fg = 0; for (let i = 0; i < n; i++) if (p[i] >= 0.5) fg++;
  const holes = new Float32Array(n), seen = new Uint8Array(n);
  for (let i = 0; i < n; i++) {
    if (outside[i] || seen[i] || p[i] >= 0.5) continue;
    const comp = [i]; seen[i] = 1; stack.push(i);
    flood(seen, j => { if (!seen[j] && !outside[j] && p[j] < 0.5) { seen[j] = 1; stack.push(j); comp.push(j); } });
    if (comp.length <= fg * maxFrac) for (const j of comp) holes[j] = 1;
  }
  for (let i = 0; i < n; i++) if (holes[i]) p[i] = 1;
  return holes;
}
function onBackdrop(c) {
  const o = document.createElement('canvas'); o.width = c.width; o.height = c.height;
  const x = o.getContext('2d', { willReadFrequently: true }); x.fillStyle = '#7f8a96'; x.fillRect(0, 0, o.width, o.height); x.drawImage(c, 0, 0);
  return o;
}
// Two passes: find the main person in the whole photo, then segment a crop around them so
// the 256px model spends its resolution on the person. Stray blobs (other people, objects)
// are dropped, and the head box is built from the face so long hair does not shrink it.
async function segmentPerson(full, hasAlpha) {
  const seg = await getSegmenter();
  const prep = c => hasAlpha ? onBackdrop(c) : c;
  const low = prep(canvasFrom(full, 640));
  const r1 = runSeg(seg, low);
  const main = largestComponent(r1.p, r1.w, r1.h, 0.5);
  if (main.size < r1.w * r1.h * 0.008) throw new Error('no-person');
  const bb = bboxOf(main.keep, r1.w, r1.h, 0.5);
  const fx = full.width / r1.w, fy = full.height / r1.h, padX = bb.w * 0.12, padY = bb.h * 0.08;
  const x0 = Math.max(0, Math.floor((bb.x - padX) * fx)), y0 = Math.max(0, Math.floor((bb.y - padY) * fy));
  const x1 = Math.min(full.width, Math.ceil((bb.x + bb.w + padX) * fx)), y1 = Math.min(full.height, Math.ceil((bb.y + bb.h + padY) * fy));
  const cs = Math.min(1, 2000 / Math.max(x1 - x0, y1 - y0));
  const crop = document.createElement('canvas');
  crop.width = Math.max(1, Math.round((x1 - x0) * cs)); crop.height = Math.max(1, Math.round((y1 - y0) * cs));
  const cx = crop.getContext('2d', { willReadFrequently: true });
  cx.imageSmoothingQuality = 'high'; cx.drawImage(full, x0, y0, x1 - x0, y1 - y0, 0, 0, crop.width, crop.height);
  const cropLow = prep(canvasFrom(crop, 768));
  const r2 = runSeg(seg, cropLow);
  const comp = largestComponent(r2.p, r2.w, r2.h, 0.5);
  const gate = boxBlur(comp.keep, r2.w, r2.h, Math.max(2, Math.round(Math.max(r2.w, r2.h) / 90)));
  for (let i = 0; i < r2.p.length; i++) { const g = Math.min(1, gate[i] * 2.5); r2.p[i] *= g; r2.hair[i] *= g; r2.face[i] *= g; }
  const holes = fillHoles(r2.p, r2.w, r2.h, 0.12);
  const kx = crop.width / r2.w, ky = crop.height / r2.h;
  const fc = largestComponent(r2.face, r2.w, r2.h, 0.5);
  const hf = new Float32Array(r2.p.length); for (let i = 0; i < hf.length; i++) hf[i] = r2.hair[i] + r2.face[i];
  const hc = largestComponent(hf, r2.w, r2.h, 0.5);
  const fb = fc.size > r2.w * r2.h * 0.002 ? bboxOf(fc.keep, r2.w, r2.h, 0.5) : null;
  const hb = hc.size > r2.w * r2.h * 0.002 ? bboxOf(hc.keep, r2.w, r2.h, 0.5) : null;
  let head = null;
  if (fb) {
    const top = hb ? Math.max(hb.y, fb.y - fb.h * 0.6) : fb.y - fb.h * 0.35;
    head = { x: (fb.x - fb.w * 0.12) * kx, y: top * ky, w: fb.w * 1.24 * kx, h: (fb.y + fb.h - top) * ky };
  } else if (hb && hb.h < r2.h * 0.6) {
    head = { x: hb.x * kx, y: hb.y * ky, w: hb.w * kx, h: hb.h * ky };
  }
  let lowC = cropLow;
  if (r2.w !== cropLow.width || r2.h !== cropLow.height) lowC = canvasFrom(cropLow, Math.max(r2.w, r2.h));
  const alpha = hasAlpha ? null : refineAlpha(r2.p, lowC, crop);
  if (alpha) {
    // keep the body solid: only the outer edge is left to the soft matte
    const solid = new Float32Array(r2.p.length);
    for (let i = 0; i < solid.length; i++) solid[i] = r2.p[i] >= 0.5 || holes[i] ? 1 : 0;
    const sb = boxBlur(solid, r2.w, r2.h, 3);
    for (let i = 0; i < sb.length; i++) sb[i] = sb[i] > 0.97 ? 1 : 0;
    const iu = bilinear(sb, r2.w, r2.h, crop.width, crop.height);
    for (let i = 0; i < alpha.length; i++) if (iu[i] > 0.5) alpha[i] = Math.max(alpha[i], Math.min(1, (iu[i] - 0.5) * 2.2));
  }
  return { crop, alpha, head, ox: x0, oy: y0, cs };
}
function makePlaceholder() {
  const c = document.createElement('canvas'); c.width = 900; c.height = 1100;
  const x = c.getContext('2d');
  const g = x.createLinearGradient(0, 120, 0, 1100); g.addColorStop(0, '#b3bcc8'); g.addColorStop(1, '#5f6976');
  x.fillStyle = g;
  x.beginPath(); x.moveTo(30, 1100); x.bezierCurveTo(30, 780, 180, 700, 330, 680); x.lineTo(570, 680); x.bezierCurveTo(720, 700, 870, 780, 870, 1100); x.closePath(); x.fill();
  x.beginPath(); x.moveTo(372, 520); x.lineTo(528, 520); x.lineTo(540, 700); x.lineTo(360, 700); x.closePath(); x.fill();
  x.beginPath(); x.ellipse(450, 370, 162, 198, 0, 0, Math.PI * 2); x.fill();
  x.fillStyle = 'rgba(255,255,255,.10)'; x.beginPath(); x.ellipse(400, 300, 70, 110, -0.3, 0, Math.PI * 2); x.fill();
  return { img: c, W: 900, H: 1100, head: { x: 288, y: 172, w: 324, h: 396 } };
}

/* ───────────── 6. 상태 & UI ───────────── */
const state = {
  person: { placeholder: makePlaceholder(), cut: null, photo: null, isPng: false },
  pFlip: false, curIdx: 0,
  adj: [0, 1, 2, 3, 4].map(() => ({ s: 1, x: 0, y: 0 })),
  fonts: [0, 1, 2, 3, 4].map(() => ({})),
  analysis: null, thumbs: null, ads: null, source: 'rule',
};
const canvases = [];
let toastTimer = 0;
function toast(msg) { const t = $('#toast'); t.textContent = msg; t.hidden = false; clearTimeout(toastTimer); toastTimer = setTimeout(() => { t.hidden = true; }, 3200); }
function el(tag, attrs = {}, ...kids) {
  const e = document.createElement(tag);
  for (const [k, v] of Object.entries(attrs)) { if (k === 'class') e.className = v; else if (k === 'text') e.textContent = v; else if (k.startsWith('on')) e.addEventListener(k.slice(2), v); else e.setAttribute(k, v); }
  for (const k of kids) if (k != null) e.append(k);
  return e;
}
function charLen(s) { return [...(s || '')].length; }
function adsLen(s) { let n = 0; for (const ch of s || '') n += /[ᄀ-ᇿ　-〿㄰-㆏가-힣一-鿿＀-￯]/.test(ch) ? 2 : 1; return n; }

function issuesFor(texts) { return texts.flatMap(t => lint(t).map(i => ({ ...i, src: t }))); }
function renderIssues(box, issues) {
  box.textContent = '';
  for (const i of issues.slice(0, 6)) {
    box.append(el('div', { class: 'it' }, el('span', { class: 'pill ' + (i.lv === 'bad' ? 'bad' : 'warn'), text: TYPE_LABEL[i.t] }), el('span', {}, el('b', { text: `“${i.text}”` }), ` → ${i.fix}`)));
  }
}
function thumbTexts(id) { const d = state.thumbs[id]; return Object.values(d).filter(Boolean); }

function buildThumbCards() {
  const wrap = $('#thumbs'); wrap.textContent = ''; canvases.length = 0;
  TPLS.forEach((tp, idx) => {
    const cv = el('canvas', { width: String(W), height: String(H), role: 'img', 'aria-label': `시안 ${idx + 1} ${tp.name} 미리보기` });
    canvases.push(cv);
    const pill = el('span', { class: 'pill ok', text: '정책 검수 통과' });
    const issues = el('div', { class: 'issues' });
    const fields = el('div', { class: 'fields' });
    for (const [k, label, max] of tp.fields) {
      const id = `f-${tp.id}-${k}`;
      const n = el('span', { class: 'n' });
      const inp = el('input', { type: 'text', id });
      inp.value = state.thumbs[tp.id][k] || '';
      const upd = () => { const c = charLen(inp.value); n.textContent = `${c}/${max}`; n.classList.toggle('over', c > max); };
      upd();
      inp.addEventListener('input', () => { state.thumbs[tp.id][k] = inp.value; upd(); scheduleRender(idx); });
      fields.append(el('div', { class: 'f' + (k === 'checks' || k === 'band' || k === 'r' ? ' wide' : '') }, el('label', { for: id }, el('span', { text: label }), n), inp));
    }
    const adj = state.adj[idx];
    const sliders = {};
    const pc = el('div', { class: 'pctl-row' });
    const sign = v => (v > 0 ? '+' : '') + v;
    for (const [k, label, min, max, step, fmt] of [['s', '인물 크기', 40, 200, 1, v => `${v}%`], ['x', '좌우 위치', -900, 900, 2, sign], ['y', '상하 위치', -500, 500, 2, sign]]) {
      const id = `adj-${idx}-${k}`;
      const inp = el('input', { type: 'range', id, min: String(min), max: String(max), step: String(step) });
      const out = el('output', { for: id });
      inp.addEventListener('input', () => { adj[k] = k === 's' ? +inp.value / 100 : +inp.value; out.textContent = fmt(+inp.value); liveRender(idx); });
      sliders[k] = { inp, out, fmt };
      pc.append(el('div', { class: 'pc' }, el('label', { for: id, text: label }), out, inp));
    }
    const sync = () => { for (const k in sliders) { const v = k === 's' ? Math.round(adj.s * 100) : Math.round(adj[k]); sliders[k].inp.value = String(v); sliders[k].out.textContent = sliders[k].fmt(v); } };
    sync();
    pc.append(el('button', { class: 'btn small', type: 'button', text: '초기화', onclick: () => { Object.assign(adj, NO_ADJ); sync(); liveRender(idx); } }));
    const pctl = el('div', { class: 'pctl' }, el('div', { class: 'pctl-head' }, el('b', { text: '인물 위치·크기' }), el('span', { text: '미리보기를 마우스로 끌어도 옮겨져요' })), pc);
    cv.addEventListener('pointerdown', e => {
      if (e.pointerType === 'touch' || e.button !== 0) return;
      e.preventDefault(); try { cv.setPointerCapture(e.pointerId); } catch (err) { /* synthetic events */ } cv.classList.add('dragging');
      const r = cv.getBoundingClientRect(), k = W / r.width, sx = e.clientX, sy = e.clientY, ax = adj.x, ay = adj.y;
      const clamp = (v, a) => Math.max(-a, Math.min(a, Math.round(v)));
      const move = ev => { adj.x = clamp(ax + (ev.clientX - sx) * k, 900); adj.y = clamp(ay + (ev.clientY - sy) * k, 500); sync(); liveRender(idx); };
      const up = () => { cv.removeEventListener('pointermove', move); cv.removeEventListener('pointerup', up); cv.removeEventListener('pointercancel', up); cv.classList.remove('dragging'); };
      cv.addEventListener('pointermove', move); cv.addEventListener('pointerup', up); cv.addEventListener('pointercancel', up);
    });
    const fontBox = el('div', { class: 'fields' });
    const fontSelects = [];
    for (const [role, label, defId] of tp.roles) {
      const id = `font-${idx}-${role}`;
      const sel = el('select', { id });
      const fill = () => {
        sel.textContent = '';
        sel.append(el('option', { value: '', text: `기본 · ${fontById(defId).label}` }));
        for (const f of FONTS) sel.append(el('option', { value: f.id, text: f.label }));
        sel.value = state.fonts[idx][role] || '';
      };
      fill();
      sel.addEventListener('change', () => { if (sel.value) state.fonts[idx][role] = sel.value; else delete state.fonts[idx][role]; liveRender(idx); });
      fontSelects.push(fill);
      fontBox.append(el('div', { class: 'f' }, el('label', { for: id }, el('span', { text: label })), sel));
    }
    const card = el('article', { class: 'card tcard', 'data-i': String(idx) },
      el('div', { class: 'tc-head' }, el('span', { class: 'num', text: `시안 ${idx + 1}` }), el('span', { class: 'tname', text: tp.name }), el('span', { class: 'ref', text: tp.ref }), pill),
      cv, pctl, issues,
      el('div', { class: 'imgchk', text: '이미지 요소: 채혈·신체 클로즈업·붉은 X·공포 합성 없음' }),
      el('details', { class: 'edit' }, el('summary', { text: '문구 수정' }), fields),
      el('details', { class: 'edit' }, el('summary', { text: '글씨체 바꾸기' }), fontBox),
      el('div', { class: 'dl' },
        el('button', { class: 'btn small', type: 'button', text: '4K PNG 받기', onclick: () => exportOne(idx, 'png') }),
        el('button', { class: 'btn small', type: 'button', text: '유튜브용 JPG 받기', onclick: () => exportOne(idx, 'jpg') })));
    card._pill = pill; card._issues = issues; card._sync = sync; card._fonts = () => fontSelects.forEach(fn => fn());
    wrap.append(card);
  });
  wrap.append(el('aside', { class: 'card tcard tips' },
    el('h3', { text: '광고 올리기 전 체크' }),
    el('ol', {},
      el('li', { text: 'YouTube 스튜디오에서 영상 썸네일과 제목을 먼저 바꾸세요. 광고 문구가 승인이어도 연결된 영상 때문에 비승인돼요.' }),
      el('li', { text: '영상 제목은 Step 4의 ‘유튜브 제목’처럼 제품명·주제를 직접 쓰세요.' }),
      el('li', { text: '썸네일·제목을 고치지 않고 캠페인만 다시 올리면 같은 이유로 다시 비승인돼요. 고친 뒤 새로 올리세요.' }),
      el('li', { text: '직접 넣는 사진에도 채혈(핏방울)·신체 클로즈업·붉은 X·경고 배너가 없어야 해요.' }),
      el('li', { text: '‘수정 필요’ 표시가 남은 시안은 문구를 고친 뒤 받으세요.' }))));
}
function updateThumbCheck(idx) {
  const card = $(`#thumbs [data-i="${idx}"]`); if (!card) return;
  const iss = issuesFor(thumbTexts(TPLS[idx].id));
  const v = verdict(iss);
  card._pill.className = 'pill ' + v.cls; card._pill.textContent = v.label;
  renderIssues(card._issues, iss);
}
const renderTimers = {};
function scheduleRender(idx) { clearTimeout(renderTimers[idx]); renderTimers[idx] = setTimeout(() => renderThumb(idx), 140); updateThumbCheck(idx); }
async function drawTemplate(ctx, idx, fontsReady) {
  const tp = TPLS[idx];
  if (!fontsReady) await ensureFonts(thumbTexts(tp.id).join(''));
  state.curIdx = idx;
  tp.draw(ctx, state.thumbs[tp.id]);
}
async function renderThumb(idx) {
  const cv = canvases[idx]; if (!cv) return;
  await ensureFonts(thumbTexts(TPLS[idx].id).join(''));
  const ctx = cv.getContext('2d');
  ctx.setTransform(1, 0, 0, 1, 0, 0); ctx.clearRect(0, 0, W, H);
  await drawTemplate(ctx, idx, true);
}
// Coalesces rapid slider/drag updates into one redraw at a time per thumbnail.
const rendering = {}, dirty = {};
async function liveRender(idx) {
  if (rendering[idx]) { dirty[idx] = true; return; }
  rendering[idx] = true;
  try { await renderThumb(idx); } finally { rendering[idx] = false; if (dirty[idx]) { dirty[idx] = false; liveRender(idx); } }
}
async function renderAll() { for (let i = 0; i < TPLS.length; i++) { await renderThumb(i); updateThumbCheck(i); } }

function buildAds() {
  const wrap = $('#ads'); wrap.textContent = '';
  state.ads.forEach((ad, i) => {
    const pill = el('span', { class: 'pill ok', text: '정책 검수 통과' });
    const issues = el('div', { class: 'issues' });
    const refresh = () => { const iss = issuesFor(Object.values(ad)); const v = verdict(iss); pill.className = 'pill ' + v.cls; pill.textContent = v.label; renderIssues(issues, iss); };
    const card = el('article', { class: 'card adcard' }, el('h3', {}, `시안 ${i + 1}`, el('span', { class: 'angle', text: ANGLES[i] }), pill));
    for (const [k, label, sub, max] of AD_FIELDS) {
      const id = `ad-${i}-${k}`;
      const inp = el('input', { type: 'text', id }); inp.value = ad[k] || '';
      const cnt = el('span', { class: 'cnt' });
      const upd = () => { const n = k === 'ytTitle' ? charLen(inp.value) : adsLen(inp.value); cnt.textContent = `${n}/${max}`; cnt.classList.toggle('over', n > max); };
      upd();
      inp.addEventListener('input', () => { ad[k] = inp.value; upd(); refresh(); });
      const copyBtn = el('button', { class: 'btn small', type: 'button', text: '복사', onclick: () => copyText(inp.value, inp) });
      card.append(el('div', { class: 'adrow' }, el('label', { class: 'k', for: id }, label, el('small', { text: sub })), inp, cnt, copyBtn));
    }
    card.append(issues);
    wrap.append(card);
    refresh();
  });
}
async function copyText(text, inp) {
  try { await navigator.clipboard.writeText(text); toast('복사했어요'); }
  catch (e) { if (inp) { inp.focus(); inp.select(); } toast('복사가 막혀 있어요. 선택된 글자를 직접 복사하세요.'); }
}
function adsAsText() {
  return state.ads.map((a, i) => `[시안 ${i + 1} · ${ANGLES[i]}]\n주 제목: ${a.headline}\n부 제목: ${a.longHeadline}\n세부 제목: ${a.description}\n유튜브 제목: ${a.ytTitle}`).join('\n\n');
}

function renderAnalysis() {
  const a = state.analysis, box = $('#analysis'); box.textContent = '';
  const facts = el('dl', { class: 'facts' },
    el('div', { class: 'fact' }, el('dt', { text: '핵심 주제' }), el('dd', { text: a.topic || '—' })),
    el('div', { class: 'fact' }, el('dt', { text: '제품·브랜드' }), el('dd', { text: a.brand || '대본에 없음' })),
    el('div', { class: 'fact' }, el('dt', { text: '주 시청자' }), el('dd', { text: a.audience || '—' })),
    el('div', { class: 'fact' }, el('dt', { text: '대본 속 정책 위험 문장' }), el('dd', { text: `${a.riskList.count}건` })));
  box.append(facts);
  if (a.keywords && a.keywords.length) box.append(el('div', { class: 'chips' }, ...a.keywords.map(k => el('span', { class: 'chip', text: k }))));
  if (a.summary) box.append(el('p', { class: 'summary', text: a.summary }));
  if (a.riskList.count) {
    const tb = el('tbody');
    for (const r of a.riskList.rows) {
      const types = [...new Map(r.iss.map(i => [i.t, i.lv])).entries()];
      const fixes = [...new Set(r.iss.map(i => `‘${i.text}’ ${i.fix}`))].join(' · ');
      tb.append(el('tr', {}, el('td', {}, highlighted(r.sent, r.iss)), el('td', {}, el('div', { class: 'chips' }, ...types.map(([t, lv]) => el('span', { class: 'pill ' + (lv === 'warn' ? 'warn' : 'bad'), text: TYPE_LABEL[t] })))), el('td', { text: fixes })));
    }
    for (const r of a.riskList.extra) tb.append(el('tr', {}, el('td', {}, el('mark', { class: 'hl', text: r.text })), el('td', {}, el('span', { class: 'pill bad', text: r.type || '정책 위험' })), el('td', { text: r.fix || '' })));
    box.append(el('div', { class: 'risk-wrap' }, el('table', { class: 'risk' }, el('thead', {}, el('tr', {}, el('th', { text: '대본 속 표현' }), el('th', { text: '정책 유형' }), el('th', { text: '이렇게 바꿔요' }))), tb)));
    box.append(el('div', { class: 'hint', text: '이 표현들은 썸네일·광고 제목에 쓰지 않았어요. 영상 본문 자막에 같은 문구가 크게 나온다면 함께 고치는 걸 권장해요.' }));
  } else {
    box.append(el('div', { class: 'status good', text: '대본에서 클릭베이트 위험 표현을 찾지 못했어요.' }));
  }
  $('#anSrc').textContent = state.source === 'claude' ? 'Claude 분석 결과' : '기본 분석(규칙 기반) 결과';
}
function riskListFrom(script, claudeRisky) {
  const rows = [];
  for (const sent of sentences(script)) {
    const iss = lint(sent);
    if (!iss.length) continue;
    rows.push({ sent, iss, lv: iss.some(i => i.lv === 'bad') ? 'bad' : 'warn' });
    if (rows.length >= 8) break;
  }
  const extra = (claudeRisky || []).filter(r => r.text && !rows.some(x => x.sent.includes(r.text)));
  return { rows, extra, count: rows.length + extra.length };
}
function highlighted(sent, iss) {
  let a = 0, b = sent.length;
  if (sent.length > 80) { a = Math.max(0, iss[0].s - 24); b = Math.min(sent.length, iss[iss.length - 1].e + 24); }
  const frag = document.createDocumentFragment();
  if (a > 0) frag.append('…');
  let cur = a;
  for (const i of iss) {
    if (i.s < a || i.e > b) continue;
    frag.append(sent.slice(cur, i.s), el('mark', { class: 'hl' + (i.lv === 'warn' ? ' w' : ''), text: sent.slice(i.s, i.e) }));
    cur = i.e;
  }
  frag.append(sent.slice(cur, b));
  if (b < sent.length) frag.append('…');
  return frag;
}

function applyResult({ analysis, thumbs, ads }, script) {
  state.analysis = { ...analysis, riskList: riskListFrom(script, analysis.risky) };
  state.thumbs = thumbs; state.ads = ads.map(a => ({ ...a }));
  renderAnalysis(); buildThumbCards(); buildAds(); renderAll();
}
function ruleResult(script, brand, topic) {
  const an = ruleAnalyze(script, brand, topic);
  const copy = ruleCopy(an);
  return { an, copy, result: { analysis: { topic: an.topic, brand: an.brand, audience: an.audience, summary: an.summary, keywords: an.keywords, risky: [] }, thumbs: copy.thumbs, ads: copy.ads } };
}

let ctl = null;
async function generate() {
  const script = $('#script').value.trim(), brand = $('#brand').value.trim(), topic = $('#topic').value.trim();
  if (!script) { toast('대본을 먼저 넣어주세요'); $('#script').focus(); return; }
  const base = ruleResult(script, brand, topic);
  const go = $('#go'), stop = $('#stop'), prog = $('#progress');
  go.disabled = true; document.body.classList.add('busy');
  try {
    const sample = await Promise.race([capSample, new Promise(r => setTimeout(() => r(null), 1500))]);
    if (!sample) {
      state.source = 'rule'; applyResult(base.result, script);
      prog.textContent = '기본 분석으로 만들었어요.';
      return;
    }
    ctl = new AbortController(); stop.hidden = false;
    prog.innerHTML = '<b>Claude가 대본을 분석하고 있어요</b> · 보통 20~60초 걸려요';
    const data = await sample.json(buildPrompt(script, brand, topic), {
      signal: ctl.signal, cache: false,
      onText: ({ text }) => { prog.innerHTML = `<b>Claude가 시안을 쓰고 있어요</b> · ${text.length.toLocaleString()}자 작성됨`; },
    });
    state.source = 'claude';
    applyResult(mergeClaude(data, base), script);
    prog.textContent = 'Claude 분석으로 시안 5개를 만들었어요. 빨간 표시가 있으면 문구를 고쳐주세요.';
  } catch (e) {
    const code = e && e.code;
    state.source = 'rule'; applyResult(base.result, script);
    const why = code === 'cancelled' ? '분석을 멈춰서' : code === 'not_granted' || code === 'sampling_disabled' ? 'Claude 사용이 허용되지 않아' : code === 'rate_limited' ? '사용량 한도에 걸려' : 'Claude 응답을 받지 못해';
    prog.textContent = `${why} 기본 분석으로 만들었어요. ${code === 'rate_limited' || code === 'upstream_error' || code === 'invalid_json' ? '잠시 뒤 다시 눌러보세요.' : ''}`;
  } finally {
    go.disabled = false; stop.hidden = true; ctl = null; document.body.classList.remove('busy');
  }
}

/* person & background inputs */
function setStatus(msg, cls = '') { const s = $('#personStatus'); s.textContent = msg; s.className = 'status ' + cls; }
function previewInto(box, canvas) { box.textContent = ''; const c = canvasFrom(canvas, 160); box.append(c); }
let personJob = 0;
function resetAdjustments() {
  state.adj.forEach(a => Object.assign(a, NO_ADJ));
  document.querySelectorAll('#thumbs .tcard').forEach(c => c._sync && c._sync());
}
async function handlePerson(file) {
  if (!file) return;
  const job = ++personJob;
  $('#personRetry').hidden = true;
  setStatus('사진을 불러오는 중…', 'busy');
  let bmp;
  try { bmp = await decodeImage(file); } catch (e) { setStatus('이 사진 형식은 열 수 없어요. JPG나 PNG로 넣어주세요.', 'warn'); return; }
  const full = canvasFrom(bmp, 2400);
  const isPng = alphaInfo(full);
  previewInto($('#personThumb'), full);
  resetAdjustments();
  toast('넣은 사진을 시안 5개의 인물로 바꾸는 중이에요');
  if (isPng) {
    const d = full.getContext('2d', { willReadFrequently: true }).getImageData(0, 0, full.width, full.height).data;
    const a = new Float32Array(full.width * full.height); for (let i = 0; i < a.length; i++) a[i] = d[i * 4 + 3] / 255;
    state.person = { ...state.person, cut: makeCut(full, a, headFromAlpha(a, full.width, full.height), false), photo: null, isPng: true };
    setStatus('투명 배경 PNG라서 그대로 썼어요.', 'good');
    renderAll();
    try {
      const r = await segmentPerson(full, true);
      if (job === personJob && r.head) {
        state.person.cut = makeCut(full, a, { x: r.ox + r.head.x / r.cs, y: r.oy + r.head.y / r.cs, w: r.head.w / r.cs, h: r.head.h / r.cs }, false);
        renderAll();
      }
    } catch (e) { /* the alpha-based head box stays */ }
    return;
  }
  const guess = { x: full.width * 0.3, y: full.height * 0.07, w: full.width * 0.4, h: full.height * 0.4 };
  state.person = { ...state.person, cut: null, photo: { img: full, W: full.width, H: full.height, head: guess }, isPng: false };
  renderAll();
  await cutout(job, full);
}
async function cutout(job, full) {
  $('#personRetry').hidden = true;
  setStatus('배경을 지우는 중… 처음 한 번은 AI 모델(약 30MB)을 받느라 10~30초 걸려요.', 'busy');
  await new Promise(r => setTimeout(r, 30));
  try {
    const r = await segmentPerson(full, false);
    if (job !== personJob) return;
    const head = r.head || headFromAlpha(r.alpha, r.crop.width, r.crop.height);
    state.person.cut = makeCut(r.crop, r.alpha, head, true);
    state.person.photo.head = { x: r.ox + head.x / r.cs, y: r.oy + head.y / r.cs, w: head.w / r.cs, h: head.h / r.cs };
    setStatus('배경을 지웠어요. 얼굴 크기에 맞춰 시안마다 자동 배치했고, 시안 4는 레퍼런스처럼 원본 배경을 살렸어요.', 'good');
    previewInto($('#personThumb'), state.person.cut.img);
  } catch (e) {
    if (job !== personJob) return;
    console.warn('segmentation failed', e);
    const why = String((e && e.message) || e || '').slice(0, 80);
    if (why === 'no-person') setStatus('사진에서 사람을 찾지 못했어요. 얼굴과 어깨가 보이는 사진을 넣어주세요.', 'warn');
    else {
      setStatus(`자동 누끼에 실패해 원본 사진을 합성했어요. 다시 시도하거나, 배경을 지운 PNG를 넣으면 레퍼런스처럼 들어가요. (원인: ${why || '알 수 없음'})`, 'warn');
      $('#personRetry').hidden = false;
    }
  }
  renderAll();
}
function refreshFontLists() {
  const all = $('#fontAll');
  all.textContent = '';
  all.append(el('option', { value: '', text: '글씨체 선택…' }));
  for (const f of FONTS) all.append(el('option', { value: f.id, text: f.label }));
  document.querySelectorAll('#thumbs .tcard').forEach(c => c._fonts && c._fonts());
}
function wireFonts() {
  refreshFontLists();
  $('#fontAll').addEventListener('change', e => {
    const id = e.target.value; if (!id) return;
    // handwriting stays handwriting unless a handwriting font was picked
    const hand = /손글씨/.test(fontById(id).label);
    TPLS.forEach((tp, i) => tp.roles.forEach(([role]) => { if (role !== 'hand' || hand) state.fonts[i][role] = id; }));
    e.target.value = '';
    refreshFontLists(); renderAll();
    toast(`시안 5개에 ‘${fontById(id).label}’을 적용했어요`);
  });
  $('#fontReset').addEventListener('click', () => { state.fonts.forEach(r => { for (const k in r) delete r[k]; }); refreshFontLists(); renderAll(); });
  $('#fontFile').addEventListener('change', async e => {
    const file = e.target.files[0]; e.target.value = '';
    if (!file) return;
    try {
      const name = 'UserFont' + (FONTS.filter(f => f.custom).length + 1);
      const face = new FontFace(name, await file.arrayBuffer());
      await face.load(); document.fonts.add(face);
      const id = 'custom-' + name;
      FONTS.push({ id, label: `내 글꼴 · ${file.name.replace(/\.(ttf|otf|woff2?)$/i, '')}`, name, w: 400, custom: true });
      refreshFontLists();
      toast('글꼴을 추가했어요. ‘글씨체 한 번에 바꾸기’나 시안별 목록에서 고르세요.');
    } catch (err) { toast('이 글꼴 파일은 열 수 없어요. TTF·OTF·WOFF 파일을 넣어주세요.'); }
  });
}
function wirePersonInput() {
  const d = $('#personDrop'), f = $('#personFile');
  f.addEventListener('change', () => { handlePerson(f.files[0]); f.value = ''; });
  // an image dropped or pasted anywhere on the page becomes the person photo
  const isFileDrag = e => e.dataTransfer && [...e.dataTransfer.types].includes('Files');
  document.addEventListener('dragover', e => { if (!isFileDrag(e)) return; e.preventDefault(); d.classList.add('over'); });
  document.addEventListener('dragleave', e => { if (!e.relatedTarget) d.classList.remove('over'); });
  document.addEventListener('drop', e => {
    if (!isFileDrag(e)) return;
    e.preventDefault(); d.classList.remove('over');
    const files = [...e.dataTransfer.files];
    const file = files.find(x => x.type.startsWith('image/')) || files[0];
    if (file) handlePerson(file);
  });
  document.addEventListener('paste', e => {
    const item = [...((e.clipboardData && e.clipboardData.items) || [])].find(i => i.kind === 'file' && i.type.startsWith('image/'));
    if (!item) return;
    e.preventDefault(); handlePerson(item.getAsFile());
  });
}

/* export */
async function renderExport(idx, scale) {
  const c = document.createElement('canvas'); c.width = W * scale; c.height = H * scale;
  const ctx = c.getContext('2d'); ctx.scale(scale, scale);
  await drawTemplate(ctx, idx);
  return c;
}
const toBlob = (c, type, q) => new Promise(r => c.toBlob(r, type, q));
async function exportBlob(idx, kind) {
  if (kind === 'png') return { blob: await toBlob(await renderExport(idx, 3), 'image/png'), name: `시안${idx + 1}_${TPLS[idx].name.replace(/\s/g, '')}_3840x2160.png` };
  const c = await renderExport(idx, 1);
  let q = 0.95, blob = await toBlob(c, 'image/jpeg', q);
  while (blob && blob.size > 1.95 * 1024 * 1024 && q > 0.6) { q -= 0.07; blob = await toBlob(c, 'image/jpeg', q); }
  return { blob, name: `시안${idx + 1}_${TPLS[idx].name.replace(/\s/g, '')}_유튜브_1280x720.jpg` };
}
async function saveFile(blob, filename) {
  const dl = await Promise.race([capDownloads, new Promise(r => setTimeout(() => r(null), 1500))]);
  if (dl) {
    try { await dl.save({ filename, data: blob }); toast('저장했어요'); }
    catch (e) { toast(e && e.code === 'declined' ? '저장을 취소했어요' : e && e.code === 'rate_limited' ? '저장 창이 이미 열려 있어요. 닫고 다시 눌러주세요.' : '이 화면에서는 파일을 저장할 수 없어요.'); }
    return;
  }
  const url = URL.createObjectURL(blob);
  const a = el('a', { href: url, download: filename }); document.body.append(a); a.click(); a.remove();
  setTimeout(() => URL.revokeObjectURL(url), 5000);
}
async function exportOne(idx, kind) {
  toast(kind === 'png' ? '4K 이미지를 만드는 중…' : 'JPG를 만드는 중…');
  const { blob, name } = await exportBlob(idx, kind);
  if (blob) await saveFile(blob, name);
}
async function exportZip() {
  if (!window.JSZip) { toast('ZIP 도구를 불러오지 못했어요. 시안별 버튼으로 받아주세요.'); return; }
  const btn = $('#zipAll'); btn.disabled = true;
  try {
    const zip = new window.JSZip();
    for (let i = 0; i < TPLS.length; i++) {
      toast(`ZIP 만드는 중… ${i + 1}/${TPLS.length}`);
      for (const kind of ['png', 'jpg']) { const { blob, name } = await exportBlob(i, kind); zip.file(name, blob); }
    }
    zip.file('광고제목_5세트.txt', adsAsText());
    const blob = await zip.generateAsync({ type: 'blob' });
    await saveFile(blob, `승인썸네일_시안5개_${new Date().toISOString().slice(0, 10)}.zip`);
  } finally { btn.disabled = false; }
}

/* boot */
async function boot() {
  $('#script').value = EXAMPLE_SCRIPT;
  $('#brand').value = '슬로벨라';
  $('#script').addEventListener('input', () => { $('#scriptHint').hidden = true; });
  wirePersonInput();
  wireFonts();
  $('#personRetry').addEventListener('click', () => { if (state.person.photo) cutout(++personJob, state.person.photo.img); });
  $('#pFlip').addEventListener('change', e => { state.pFlip = e.target.checked; renderAll(); });
  $('#go').addEventListener('click', generate);
  $('#stop').addEventListener('click', () => ctl && ctl.abort());
  $('#zipAll').addEventListener('click', exportZip);
  $('#copyAllAds').addEventListener('click', () => copyText(adsAsText()));
  const base = ruleResult(EXAMPLE_SCRIPT, '슬로벨라', '');
  applyResult(base.result, EXAMPLE_SCRIPT);
  $('#progress').textContent = '예시 대본으로 만든 시안이에요. 실제 대본을 넣고 버튼을 눌러주세요.';
  if (document.fonts && document.fonts.ready) document.fonts.ready.then(() => renderAll());
  capSample.then(s => {
    const e = $('#engine');
    if (s) { e.classList.add('on'); e.lastElementChild.textContent = 'Claude 정밀 분석 사용 가능'; }
    else e.lastElementChild.textContent = '기본 분석 모드 (규칙 기반)';
  });
}
boot();
</script>
</body>
</html>
