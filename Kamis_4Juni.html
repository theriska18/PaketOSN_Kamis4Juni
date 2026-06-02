<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Latihan OSN IPS Nicky</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
:root{
  --blue:#378ADD;--blue-light:#E6F1FB;--blue-dark:#0C447C;
  --green:#639922;--green-light:#EAF3DE;--green-dark:#27500A;
  --amber:#BA7517;--amber-light:#FAEEDA;--amber-dark:#633806;
  --red:#E24B4A;--red-light:#FCEBEB;--red-dark:#791F1F;
  --purple:#534AB7;--purple-light:#EEEDFE;--purple-dark:#26215C;
  --teal:#1D9E75;--teal-light:#E1F5EE;--teal-dark:#085041;
  --orange:#D9640A;--orange-light:#FEF0E6;--orange-dark:#7A3005;
  --pink:#C0367B;--pink-light:#FCE8F3;--pink-dark:#6B0D40;
  --bg:#f5f5f3;--card:#fff;
  --border:rgba(0,0,0,.08);--border-md:rgba(0,0,0,.13);
  --text:#1a1a1a;--text-sec:#6b6b6b;--surface:#f1efe8;
}
@media(prefers-color-scheme:dark){:root{
  --bg:#1a1a1a;--card:#242424;--border:rgba(255,255,255,.08);
  --border-md:rgba(255,255,255,.14);--text:#f0f0f0;
  --text-sec:#a0a0a0;--surface:#2e2e2e;
}}
body{font-family:'Segoe UI',system-ui,sans-serif;background:var(--bg);color:var(--text);min-height:100vh}
.wrap{max-width:900px;margin:0 auto;padding:20px 24px}

/* LOGIN */
#login-screen{min-height:100vh;display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,#26215C 0%,#0C447C 60%,#085041 100%);padding:20px;}
.login-box{background:#fff;border-radius:20px;padding:36px 32px;width:100%;max-width:400px;box-shadow:0 20px 60px rgba(0,0,0,.25);}
@media(prefers-color-scheme:dark){.login-box{background:#1e1e1e}}
.login-logo{text-align:center;margin-bottom:24px}
.login-logo-icon{width:64px;height:64px;border-radius:16px;margin:0 auto 12px;background:linear-gradient(135deg,#534AB7,#378ADD);display:flex;align-items:center;justify-content:center;font-size:28px;}
.login-logo h1{font-size:20px;font-weight:600;color:var(--text);margin-bottom:4px}
.login-logo p{font-size:12px;color:var(--text-sec)}
.login-tabs{display:flex;gap:0;margin-bottom:24px;border:1.5px solid var(--border-md);border-radius:10px;overflow:hidden}
.login-tab{flex:1;padding:9px;font-size:13px;font-weight:500;cursor:pointer;border:none;background:transparent;color:var(--text-sec);transition:all .2s;}
.login-tab.active{background:var(--purple);color:#fff}
.login-field{margin-bottom:14px}
.login-field label{display:block;font-size:12px;font-weight:500;color:var(--text-sec);margin-bottom:6px}
.login-field input{width:100%;padding:10px 14px;border:1.5px solid var(--border-md);border-radius:9px;font-size:14px;background:var(--card);color:var(--text);transition:border-color .15s;outline:none;}
.login-field input:focus{border-color:var(--purple)}
.login-hint{font-size:11px;color:var(--text-sec);margin-top:4px}
.pw-wrap{position:relative}
.pw-wrap input{padding-right:40px}
.pw-toggle{position:absolute;right:12px;top:50%;transform:translateY(-50%);background:none;border:none;cursor:pointer;color:var(--text-sec);font-size:16px;padding:2px;line-height:1;transition:color .15s;}
.pw-toggle:hover{color:var(--purple)}
.login-btn{width:100%;padding:11px;border-radius:9px;font-size:14px;font-weight:600;cursor:pointer;border:none;background:linear-gradient(135deg,#534AB7,#378ADD);color:#fff;transition:opacity .15s;margin-top:6px;}
.login-btn:hover{opacity:.9}
.login-error{background:var(--red-light);border:1px solid var(--red);border-radius:8px;padding:10px 14px;font-size:12px;color:var(--red-dark);margin-bottom:12px;display:none;}
.login-error.show{display:block}
.admin-badge{display:inline-flex;align-items:center;gap:4px;background:var(--amber-light);color:var(--amber-dark);font-size:10px;font-weight:600;padding:3px 8px;border-radius:20px;border:1px solid var(--amber);}

/* USER BAR */
.user-bar{display:flex;align-items:center;justify-content:space-between;background:var(--card);border:1px solid var(--border);border-radius:12px;padding:10px 16px;margin-bottom:12px;}
.user-info{display:flex;align-items:center;gap:10px}
.user-avatar{width:32px;height:32px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:14px;font-weight:600;color:#fff;flex-shrink:0;}
.user-avatar.siswa{background:linear-gradient(135deg,#378ADD,#1D9E75)}
.user-avatar.admin{background:linear-gradient(135deg,#534AB7,#BA7517)}
.user-name{font-size:13px;font-weight:500;color:var(--text)}
.user-role{font-size:11px;color:var(--text-sec);margin-top:1px}
.btn-logout{padding:6px 12px;border-radius:7px;font-size:12px;font-weight:500;cursor:pointer;border:1.5px solid var(--border-md);background:var(--card);color:var(--text-sec);transition:all .15s;}
.btn-logout:hover{background:var(--red-light);color:var(--red-dark);border-color:var(--red)}

/* LOADING */
#loading-screen{text-align:center;padding:60px 20px}
.loading-spinner{width:40px;height:40px;border:3px solid var(--border-md);border-top-color:var(--blue);border-radius:50%;animation:spin .8s linear infinite;margin:0 auto 16px}
@keyframes spin{to{transform:rotate(360deg)}}
.loading-text{font-size:14px;color:var(--text-sec)}

/* HEADER */
.header-bar{display:flex;justify-content:space-between;align-items:center;background:linear-gradient(135deg,#534AB7 0%,#378ADD 100%);border-radius:14px;padding:14px 20px;margin-bottom:14px;}
.header-bar h2{font-size:15px;font-weight:500;color:#fff;letter-spacing:.3px}
.header-subtitle{font-size:11px;color:rgba(255,255,255,.7);margin-top:2px}
.timer-box{background:rgba(255,255,255,.18);border:1.5px solid rgba(255,255,255,.35);border-radius:10px;padding:8px 16px;text-align:center;min-width:90px;}
.timer-val{font-size:22px;font-weight:500;color:#fff;letter-spacing:3px;font-family:monospace}
.timer-lbl{font-size:10px;color:rgba(255,255,255,.7);margin-top:1px}
.timer-box.danger{background:rgba(226,75,74,.3);border-color:rgba(226,75,74,.8)}

/* LAYOUT */
.layout{display:grid;grid-template-columns:1fr 230px;gap:12px}
.q-card{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:20px}
.q-meta{display:flex;align-items:center;gap:8px;margin-bottom:10px;flex-wrap:wrap}
.q-badge{background:var(--purple-light);color:var(--purple-dark);font-size:11px;font-weight:500;padding:4px 10px;border-radius:20px}
.q-segment-badge{font-size:11px;font-weight:600;padding:4px 10px;border-radius:20px}
.q-progress-text{font-size:12px;color:var(--text-sec)}
.q-text{font-size:15px;color:var(--text);line-height:1.7;margin-bottom:18px;font-weight:500}
.options{display:flex;flex-direction:column;gap:9px;margin-bottom:20px}
.opt{display:flex;align-items:center;gap:12px;padding:12px 16px;border:1.5px solid var(--border);border-radius:10px;cursor:pointer;background:var(--card);transition:border-color .15s,background .15s;}
.opt:hover{border-color:var(--blue);background:var(--blue-light)}
.opt.selected{border-color:var(--blue);background:var(--blue-light)}
.opt-letter{width:30px;height:30px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:500;flex-shrink:0;border:1.5px solid currentColor;transition:all .15s;color:var(--text-sec);}
.opt.selected .opt-letter{background:var(--blue);color:#fff;border-color:var(--blue)}
.opt-text{font-size:14px;color:var(--text)}
.q-nav{display:flex;justify-content:space-between;align-items:center;gap:8px}
.btn{padding:9px 18px;border-radius:8px;font-size:13px;font-weight:500;cursor:pointer;border:1.5px solid var(--border-md);background:var(--card);color:var(--text);transition:all .15s;}
.btn:hover{background:var(--surface)}
.btn-blue{background:var(--blue);color:#fff;border-color:var(--blue)}
.btn-blue:hover{background:var(--blue-dark);border-color:var(--blue-dark)}
.btn-red{background:var(--red);color:#fff;border-color:var(--red)}
.btn-red:hover{background:var(--red-dark);border-color:var(--red-dark)}
.btn-sm{padding:6px 12px;font-size:12px}
.btn-ghost{background:transparent;border-color:transparent;color:var(--text-sec)}
.btn-ghost:hover{background:var(--surface);border-color:var(--border)}

/* SIDEBAR */
.sidebar{display:flex;flex-direction:column;gap:10px}
.side-card{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:14px}
.side-title{font-size:11px;font-weight:600;color:var(--text-sec);text-transform:uppercase;letter-spacing:.6px;margin-bottom:10px}

/* SEGMENT NAV */
.seg-nav-block{margin-bottom:10px}
.seg-nav-label{display:flex;align-items:center;gap:6px;font-size:10px;font-weight:700;text-transform:uppercase;letter-spacing:.5px;margin-bottom:5px;padding:4px 6px;border-radius:6px;}
.seg-nav-label .seg-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0}
.seg-nav-label.seg-a{background:rgba(83,74,183,.1);color:var(--purple-dark)}
.seg-nav-label.seg-b{background:rgba(25,158,117,.1);color:var(--teal-dark)}
.seg-nav-label.seg-c{background:rgba(186,117,23,.1);color:var(--amber-dark)}
.seg-nav-label.seg-d{background:rgba(192,54,123,.1);color:var(--pink-dark)}
.nav-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:4px;margin-bottom:4px}
.nav-btn{aspect-ratio:1;border-radius:7px;font-size:11px;font-weight:500;cursor:pointer;border:none;display:flex;align-items:center;justify-content:center;transition:all .15s;}
.nav-btn.unanswered{background:var(--amber-light);color:var(--amber-dark)}
.nav-btn.answered{background:var(--green-light);color:var(--green-dark)}
.nav-btn.current{outline:2.5px solid var(--blue);outline-offset:1px}
/* segment color borders */
.nav-btn.seg-a-btn{border-bottom:2px solid var(--purple)}
.nav-btn.seg-b-btn{border-bottom:2px solid var(--teal)}
.nav-btn.seg-c-btn{border-bottom:2px solid var(--amber)}
.nav-btn.seg-d-btn{border-bottom:2px solid var(--pink)}

.legend{display:flex;flex-direction:column;gap:5px;margin-top:8px;padding-top:8px;border-top:1px solid var(--border)}
.legend-row{display:flex;align-items:center;gap:7px;font-size:11px;color:var(--text-sec)}
.legend-dot{width:12px;height:12px;border-radius:4px;flex-shrink:0}
.prog-wrap{margin-top:6px}
.prog-label{display:flex;justify-content:space-between;font-size:11px;color:var(--text-sec);margin-bottom:5px}
.prog-bar-bg{height:7px;border-radius:100px;background:var(--surface);overflow:hidden}
.prog-bar-fill{height:100%;border-radius:100px;background:var(--green);transition:width .4s}
.stat-row{display:grid;grid-template-columns:1fr 1fr;gap:6px;margin-top:10px}
.stat-box{background:var(--surface);border-radius:8px;padding:9px;text-align:center}
.stat-val{font-size:18px;font-weight:500}
.stat-lbl{font-size:10px;color:var(--text-sec);margin-top:1px}

/* SEGMENT PROGRESS IN SIDEBAR */
.seg-progress-item{margin-bottom:7px}
.seg-prog-row{display:flex;justify-content:space-between;align-items:center;font-size:10px;margin-bottom:3px}
.seg-prog-name{font-weight:600;color:var(--text-sec)}
.seg-prog-count{color:var(--text-sec)}
.seg-prog-bar-bg{height:5px;border-radius:100px;background:var(--surface);overflow:hidden}
.seg-prog-bar-fill{height:100%;border-radius:100px;transition:width .4s}

/* RESULT */
#result-screen{display:none}
.result-header{background:linear-gradient(135deg,#1D9E75 0%,#378ADD 100%);border-radius:14px;padding:20px;text-align:center;margin-bottom:14px;}
.rh-title{font-size:16px;font-weight:500;color:#fff;margin-bottom:4px}
.rh-sub{font-size:12px;color:rgba(255,255,255,.75)}
.score-ring{width:90px;height:90px;border-radius:50%;border:5px solid rgba(255,255,255,.4);display:flex;flex-direction:column;align-items:center;justify-content:center;margin:14px auto 0;background:rgba(255,255,255,.15);}
.sr-num{font-size:28px;font-weight:500;color:#fff}
.sr-lbl{font-size:10px;color:rgba(255,255,255,.75)}
.res-stats{display:grid;grid-template-columns:1fr 1fr 1fr;gap:8px;margin-bottom:14px}
.res-stat{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:12px;text-align:center}
.res-stat .rv{font-size:24px;font-weight:500}
.res-stat .rl{font-size:11px;color:var(--text-sec);margin-top:2px}

/* SEGMENT RESULT GRID */
.seg-result-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:8px;margin-bottom:14px}
.seg-result-card{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:14px}
.seg-rc-header{display:flex;align-items:center;gap:8px;margin-bottom:10px}
.seg-rc-icon{width:30px;height:30px;border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:14px;flex-shrink:0}
.seg-rc-name{font-size:11px;font-weight:600;color:var(--text);line-height:1.3}
.seg-rc-stats{display:flex;gap:6px;flex-wrap:wrap}
.seg-rc-pill{font-size:11px;font-weight:600;padding:3px 8px;border-radius:20px}
.seg-rc-score{font-size:18px;font-weight:700;margin-top:6px}

.review-section{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:16px}
.review-section h3{font-size:14px;font-weight:500;color:var(--text);margin-bottom:12px}
.review-item{border-radius:10px;padding:12px 14px;margin-bottom:9px;border-left:4px solid transparent}
.review-item.correct{background:var(--green-light);border-color:var(--green)}
.review-item.wrong{background:var(--red-light);border-color:var(--red)}
.review-item.skip{background:var(--surface);border-color:var(--border-md)}
.ri-q{font-size:13px;font-weight:500;color:var(--text);margin-bottom:6px}
.ri-ans{font-size:12px;margin-bottom:3px}
.ri-correct-ans{color:var(--green-dark)}
.ri-wrong-ans{color:var(--red-dark)}
.ri-skip-ans{color:var(--text-sec)}
.ri-pembahasan{font-size:12px;color:var(--text-sec);background:rgba(255,255,255,.6);padding:7px 10px;border-radius:7px;margin-top:7px;line-height:1.5}
.ri-seg-tag{display:inline-block;font-size:10px;font-weight:600;padding:2px 7px;border-radius:20px;margin-bottom:6px}
.result-actions{display:flex;gap:8px;justify-content:center;margin-top:14px;flex-wrap:wrap}

/* HISTORY */
#history-screen{display:none}
.history-header{display:flex;align-items:center;justify-content:space-between;background:linear-gradient(135deg,#534AB7 0%,#378ADD 100%);border-radius:14px;padding:14px 20px;margin-bottom:14px;}
.history-header h2{font-size:15px;font-weight:500;color:#fff}
.history-list{display:flex;flex-direction:column;gap:10px}
.history-item{background:var(--card);border:1px solid var(--border);border-radius:14px;padding:16px 18px;}
.hi-top{display:flex;align-items:center;gap:14px}
.hi-score-ring{width:54px;height:54px;border-radius:50%;flex-shrink:0;display:flex;flex-direction:column;align-items:center;justify-content:center;font-weight:600;font-size:18px;border:3px solid;}
.hi-score-ring.excellent{color:var(--green);border-color:var(--green);background:var(--green-light)}
.hi-score-ring.good{color:var(--blue);border-color:var(--blue);background:var(--blue-light)}
.hi-score-ring.poor{color:var(--red);border-color:var(--red);background:var(--red-light)}
.hi-body{flex:1;min-width:0}
.hi-title{font-size:13px;font-weight:500;color:var(--text);margin-bottom:3px}
.hi-meta{font-size:11px;color:var(--text-sec)}
.hi-pills{display:flex;gap:6px;margin-top:6px;flex-wrap:wrap}
.pill{font-size:11px;padding:3px 8px;border-radius:20px;font-weight:500}
.pill-green{background:var(--green-light);color:var(--green-dark)}
.pill-red{background:var(--red-light);color:var(--red-dark)}
.pill-amber{background:var(--amber-light);color:var(--amber-dark)}
.hi-actions{display:flex;flex-direction:column;gap:5px;align-items:flex-end}
.hi-empty{text-align:center;padding:40px;color:var(--text-sec);font-size:14px}
.hi-user-tag{font-size:10px;color:var(--text-sec);margin-top:2px}

/* SEGMENT BREAKDOWN IN HISTORY ITEM */
.hi-seg-breakdown{margin-top:10px;padding-top:10px;border-top:1px solid var(--border);display:grid;grid-template-columns:repeat(2,1fr);gap:6px}
.hi-seg-item{background:var(--surface);border-radius:8px;padding:8px 10px;display:flex;align-items:center;gap:8px}
.hi-seg-dot{width:10px;height:10px;border-radius:50%;flex-shrink:0}
.hi-seg-info{flex:1;min-width:0}
.hi-seg-name{font-size:10px;font-weight:600;color:var(--text);white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.hi-seg-score{font-size:10px;color:var(--text-sec);margin-top:1px}

.admin-only-notice{display:flex;align-items:center;gap:6px;font-size:11px;color:var(--amber-dark);background:var(--amber-light);border:1px solid var(--amber);border-radius:8px;padding:8px 12px;margin-bottom:12px;}

/* TOP NAV */
.top-nav{display:flex;gap:8px;margin-bottom:14px}
.top-nav-btn{padding:8px 14px;border-radius:8px;font-size:12px;font-weight:500;cursor:pointer;border:1.5px solid var(--border-md);background:var(--card);color:var(--text-sec);transition:all .15s;}
.top-nav-btn:hover{background:var(--surface)}
.top-nav-btn.active{background:var(--purple-light);color:var(--purple-dark);border-color:var(--purple)}

/* LOG */
.log-header{display:flex;align-items:center;justify-content:space-between;background:linear-gradient(135deg,#085041 0%,#1D9E75 100%);border-radius:14px;padding:14px 20px;margin-bottom:12px;}
.log-header h2{font-size:15px;font-weight:500;color:#fff}
.log-table-wrap{background:var(--card);border:1px solid var(--border);border-radius:14px;overflow:hidden}
.log-table{width:100%;border-collapse:collapse;font-size:12px}
.log-table thead{background:var(--surface)}
.log-table th{padding:10px 14px;text-align:left;font-size:11px;font-weight:600;color:var(--text-sec);text-transform:uppercase;letter-spacing:.5px;border-bottom:1px solid var(--border)}
.log-table td{padding:10px 14px;border-bottom:1px solid var(--border);color:var(--text);vertical-align:middle}
.log-table tr:last-child td{border-bottom:none}
.log-table tr:hover td{background:var(--surface)}
.log-badge{display:inline-flex;align-items:center;padding:3px 8px;border-radius:20px;font-size:11px;font-weight:600}
.log-badge.excellent{background:var(--green-light);color:var(--green-dark)}
.log-badge.good{background:var(--blue-light);color:var(--blue-dark)}
.log-badge.poor{background:var(--red-light);color:var(--red-dark)}
.log-empty{text-align:center;padding:30px;color:var(--text-sec);font-size:13px}
.log-stat-row{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:14px}
.log-stat-card{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:12px;text-align:center}
.log-stat-card .lsv{font-size:22px;font-weight:600;color:var(--purple)}
.log-stat-card .lsl{font-size:10px;color:var(--text-sec);margin-top:2px}

@media(max-width:640px){
  .wrap{padding:12px 14px}
  .layout{grid-template-columns:1fr}
  .sidebar{display:none}
  .res-stats{grid-template-columns:1fr 1fr}
  .seg-result-grid{grid-template-columns:1fr}
  .history-item .hi-top{flex-direction:column;align-items:flex-start}
  .hi-actions{flex-direction:row;width:100%}
  .hi-seg-breakdown{grid-template-columns:1fr}
  .log-stat-row{grid-template-columns:1fr 1fr}
  .log-table th:nth-child(5),.log-table td:nth-child(5),.log-table th:nth-child(6),.log-table td:nth-child(6){display:none}
}
</style>
</head>
<body>

<!-- LOGIN SCREEN -->
<div id="login-screen">
  <div class="login-box">
    <div class="login-logo">
      <div class="login-logo-icon">📝</div>
      <h1>Latihan OSN IPS Nicky</h1>
      <p>Masuk untuk mengakses latihan</p>
    </div>
    <div class="login-tabs">
      <button class="login-tab active" id="tab-siswa" onclick="switchTab('siswa')">👨‍🎓 Siswa</button>
      <button class="login-tab" id="tab-admin" onclick="switchTab('admin')">🔐 Admin</button>
    </div>
    <div id="login-error" class="login-error">Username atau password salah.</div>
    <div id="form-siswa">
      <div class="login-field">
        <label>Username Siswa</label>
        <input type="text" id="siswa-username" placeholder="Masukkan username" autocomplete="username">
        <div class="login-hint">Contoh: nicky, budi, sari</div>
      </div>
      <div class="login-field">
        <label>Password</label>
        <div class="pw-wrap">
          <input type="password" id="siswa-password" placeholder="Masukkan password" autocomplete="current-password">
          <button type="button" class="pw-toggle" onclick="togglePw('siswa-password',this)">👁</button>
        </div>
      </div>
      <button class="login-btn" onclick="doLogin('siswa')">Masuk sebagai Siswa</button>
    </div>
    <div id="form-admin" style="display:none">
      <div class="login-field">
        <label>Username Admin</label>
        <input type="text" id="admin-username" placeholder="Masukkan username admin" autocomplete="username">
      </div>
      <div class="login-field">
        <label>Password Admin</label>
        <div class="pw-wrap">
          <input type="password" id="admin-password" placeholder="Masukkan password admin" autocomplete="current-password">
          <button type="button" class="pw-toggle" onclick="togglePw('admin-password',this)">👁</button>
        </div>
      </div>
      <button class="login-btn" onclick="doLogin('admin')">Masuk sebagai Admin</button>
    </div>
  </div>
</div>

<!-- MAIN APP -->
<div id="main-app" style="display:none">
<div class="wrap">

  <div class="user-bar">
    <div class="user-info">
      <div class="user-avatar" id="user-avatar">?</div>
      <div>
        <div class="user-name" id="user-name-display">–</div>
        <div class="user-role" id="user-role-display">–</div>
      </div>
    </div>
    <button class="btn-logout" onclick="doLogout()">Keluar</button>
  </div>

  <div class="top-nav">
    <button class="top-nav-btn active" id="nav-tryout" onclick="showScreen('tryout')">📝 Tryout</button>
    <button class="top-nav-btn" id="nav-history" onclick="showScreen('history')">📋 Riwayat Tryout</button>
    <button class="top-nav-btn" id="nav-log" onclick="showScreen('log')">📊 Log Aktivitas</button>
  </div>

  <div id="loading-screen" style="display:none">
    <div class="loading-spinner"></div>
    <div class="loading-text">Memuat soal...</div>
  </div>

  <!-- CBT APP -->
  <div id="cbt-app" style="display:none">
    <div class="header-bar">
      <div>
        <h2 id="header-title">LATIHAN OSN IPS NICKY</h2>
        <div class="header-subtitle" id="header-subtitle">Memuat...</div>
      </div>
      <div class="timer-box" id="timer-box">
        <div class="timer-val" id="timer">60:00</div>
        <div class="timer-lbl">Sisa waktu</div>
      </div>
    </div>
    <div class="layout">
      <div class="q-card">
        <div class="q-meta">
          <span class="q-badge" id="q-badge">Soal 1</span>
          <span class="q-segment-badge" id="q-seg-badge">Segmen A</span>
          <span class="q-progress-text" id="q-progress">dari 50 soal</span>
        </div>
        <div class="q-text" id="q-text"></div>
        <div class="options" id="options"></div>
        <div class="q-nav">
          <button class="btn" onclick="prevQ()">← Sebelumnya</button>
          <button class="btn btn-red" onclick="confirmSubmit()">Selesai &amp; Kirim</button>
          <button class="btn btn-blue" onclick="nextQ()">Selanjutnya →</button>
        </div>
      </div>
      <div class="sidebar">
        <div class="side-card">
          <div class="side-title">Navigasi Soal</div>
          <div id="seg-nav-container"></div>
          <div class="legend">
            <div class="legend-row"><div class="legend-dot" style="background:var(--green-light);border:1px solid var(--green)"></div>Sudah dijawab</div>
            <div class="legend-row"><div class="legend-dot" style="background:var(--amber-light);border:1px solid var(--amber)"></div>Belum dijawab</div>
          </div>
        </div>
        <div class="side-card">
          <div class="side-title">Progress</div>
          <div class="prog-wrap">
            <div class="prog-label"><span id="prog-text">0 terjawab</span><span id="prog-pct">0%</span></div>
            <div class="prog-bar-bg"><div class="prog-bar-fill" id="prog-bar" style="width:0%"></div></div>
          </div>
          <div class="stat-row">
            <div class="stat-box"><div class="stat-val" style="color:var(--green)" id="stat-ans">0</div><div class="stat-lbl">Dijawab</div></div>
            <div class="stat-box"><div class="stat-val" style="color:var(--amber)" id="stat-skip">0</div><div class="stat-lbl">Belum</div></div>
          </div>
        </div>
        <div class="side-card">
          <div class="side-title">Per Segmen</div>
          <div id="seg-progress-sidebar"></div>
        </div>
      </div>
    </div>
  </div>

  <!-- RESULT -->
  <div id="result-screen" style="display:none">
    <div class="result-header">
      <div class="rh-title">Hasil Latihan OSN IPS Nicky</div>
      <div class="rh-sub">Ujian selesai — lihat hasil dan pembahasan di bawah</div>
      <div class="score-ring">
        <div class="sr-num" id="res-score">0</div>
        <div class="sr-lbl">NILAI</div>
      </div>
    </div>
    <div class="res-stats">
      <div class="res-stat"><div class="rv" style="color:var(--green)" id="res-benar">0</div><div class="rl">Benar</div></div>
      <div class="res-stat"><div class="rv" style="color:var(--red)" id="res-salah">0</div><div class="rl">Salah</div></div>
      <div class="res-stat"><div class="rv" style="color:var(--text-sec)" id="res-skip">0</div><div class="rl">Tidak dijawab</div></div>
    </div>
    <!-- Segment result cards -->
    <div class="seg-result-grid" id="seg-result-grid"></div>
    <div class="review-section">
      <h3>Pembahasan Per Soal</h3>
      <div id="review-list"></div>
      <div class="result-actions" id="result-actions"></div>
    </div>
  </div>

  <!-- HISTORY -->
  <div id="history-screen" style="display:none">
    <div class="history-header">
      <h2>📋 Riwayat Tryout</h2>
      <div style="display:flex;gap:8px;align-items:center">
        <button class="btn btn-sm" style="background:rgba(255,255,255,.15);border-color:rgba(255,255,255,.3);color:#fff" onclick="downloadPDF()">📥 Unduh PDF</button>
        <div id="admin-clear-btn" style="display:none">
          <button class="btn btn-sm" style="background:rgba(255,255,255,.15);border-color:rgba(255,255,255,.3);color:#fff" onclick="clearAllHistory()">🗑 Hapus Semua</button>
        </div>
      </div>
    </div>
    <div id="admin-only-notice" class="admin-only-notice" style="display:none">
      🔒 Anda login sebagai Admin — dapat melihat semua riwayat dan menghapus data.
    </div>
    <div class="history-list" id="history-list"></div>
  </div>

  <!-- LOG -->
  <div id="log-screen" style="display:none">
    <div class="log-header">
      <h2>📊 Log Aktivitas Tryout</h2>
      <div id="log-admin-controls" style="display:none">
        <button class="btn btn-sm" style="background:rgba(255,255,255,.15);border-color:rgba(255,255,255,.3);color:#fff" onclick="clearLog()">🗑 Hapus Log</button>
      </div>
    </div>
    <div id="log-stat-row" class="log-stat-row"></div>
    <div class="log-table-wrap">
      <table class="log-table">
        <thead><tr>
          <th>#</th><th>Waktu</th>
          <th id="log-th-user" style="display:none">Pengguna</th>
          <th>Aksi</th><th>Nilai</th><th>Detail</th>
        </tr></thead>
        <tbody id="log-tbody"></tbody>
      </table>
    </div>
  </div>

</div>
</div>

<script>
// ─────────────────────────────────────────
// SEGMEN
// ─────────────────────────────────────────
const SEGMENTS = [
  {
    id:'A', key:'fenomena',
    name:'Penampakan Fenomena Alam, Sosial & Budaya',
    short:'Fenomena Alam',
    color:'var(--purple)', colorLight:'var(--purple-light)', colorDark:'var(--purple-dark)',
    cls:'seg-a', btnCls:'seg-a-btn', icon:'',
    start:0, end:14   // indeks soal 1–15
  },
  {
    id:'B', key:'keragaman',
    name:'Keragaman, Interaksi & Perubahan Sosial',
    short:'Perubahan Sosial',
    color:'var(--teal)', colorLight:'var(--teal-light)', colorDark:'var(--teal-dark)',
    cls:'seg-b', btnCls:'seg-b-btn', icon:'',
    start:15, end:29  // indeks soal 16–30
  },
  {
    id:'C', key:'ekonomi',
    name:'Kegiatan Ekonomi & Peran Indonesia dalam Ekonomi Global',
    short:'Ekonomi Global',
    color:'var(--amber)', colorLight:'var(--amber-light)', colorDark:'var(--amber-dark)',
    cls:'seg-c', btnCls:'seg-c-btn', icon:'',
    start:30, end:39  // indeks soal 31–40
  },
  {
    id:'D', key:'sejarah',
    name:'Perkembangan Sejarah Indonesia',
    short:'Sejarah Indonesia',
    color:'var(--pink)', colorLight:'var(--pink-light)', colorDark:'var(--pink-dark)',
    cls:'seg-d', btnCls:'seg-d-btn', icon:'',
    start:40, end:49  // indeks soal 41–50
  }
];

function getSegment(idx){
  return SEGMENTS.find(s => idx >= s.start && idx <= s.end) || SEGMENTS[0];
}

// ─────────────────────────────────────────
// KONFIGURASI
// ─────────────────────────────────────────
const CONFIG = {
  subject: 'IPS',
  duration: 50 * 60,  // 50 menit untuk 50 soal

  // ── UPDATE SOAL DARI GITHUB ──────────────────────────────────────────────
  // Ganti URL di bawah dengan raw URL file JSON di GitHub Anda.
  // Format URL raw GitHub:
  //   https://raw.githubusercontent.com/<username>/<repo>/<branch>/<namafile>.json
  //
  // Contoh:
  //   https://raw.githubusercontent.com/nicky/osn-ips/main/soal_osn_ips.json
  //
  // Jika URL kosong ("") atau fetch gagal, akan tampil pesan error.
  // ────────────────────────────────────────────────────────────────────────
  jsonUrl: ''   // ← isi URL raw GitHub JSON di sini
};

const HISTORY_KEY = 'tryout_history_osn_ips';
const SESSION_KEY = 'tryout_session';
const LOG_KEY     = 'tryout_activity_log';

// ─────────────────────────────────────────
// 60 SOAL — 4 SEGMEN × 15 SOAL
// ─────────────────────────────────────────
const BUILTIN_QUESTIONS = [
  // ── SEGMEN A: Geografi Indonesia (No. 1–15) ──
  {
    q: '[GAMBAR PETA TOPOGRAFI dengan garis kontur rapat berlabel 500 dan 1000, titik P di tengah]\n\nPada peta topografi, area yang ditandai dengan garis kontur yang rapat menunjukan ....',
    opts: ['Daerah rendah', 'Daerah tinggi', 'Daerah hutan', 'Daerah pantai'],
    answer: 1,
    pembahasan: 'Pada peta topografi, garis kontur yang rapat menunjukkan daerah yang curam atau daerah tinggi (lereng terjal). Semakin rapat garis kontur, semakin terjal/curam wilayah tersebut. Jawaban: B.'
  },
  {
    q: 'Rais seorang siswa kelas VI dari salah satu sekolah di Yogyakarta. Rais ingin mengetahui letak relatif sebuah kota. Kota tersebut terletak di koordinat 7° LS dan 110° BT. Jika Rais ingin mengetahui letak relatif terhadap garis khatulistiwa dan meridian utama, kita menggunakan konsep ....',
    opts: ['Skala', 'Legenda', 'Proyeksi Peta', 'Koordinat Geografis'],
    answer: 2,
    pembahasan: 'Untuk mengetahui letak relatif suatu tempat terhadap garis khatulistiwa dan meridian utama, digunakan koordinat geografis (lintang dan bujur). Koordinat Geografis menunjukkan posisi suatu titik di permukaan bumi. Jawaban: A (Skala).\n\nCatatan: Jawaban sesuai kunci adalah A (Skala), namun secara konsep yang paling tepat untuk menentukan letak berdasarkan garis khatulistiwa dan meridian adalah Koordinat Geografis.'
  },
  {
    q: 'Perhatikan pernyataan di bawah ini!\n\nPernyataan A: Keberagaman suku, budaya, dan bahasa di Indonesia sangat tinggi.\nPernyataan B: Indonesia merupakan negara kepulauan yang luas dengan berbagai kondisi geografis dan sejarah migrasi penduduk yang berbeda di setiap pulaunya.\n\nBerdasarkan pernyataan di atas, hubungan dua pernyataan yang tepat adalah ....',
    opts: [
      'Pernyataan benar, alasan benar, dan keduanya menunjukkan hubungan sebab akibat.',
      'Pernyataan benar, alasan benar, tetapi keduanya tidak menunjukkan hubungan sebab akibat.',
      'Pernyataan benar, alasan salah.',
      'Pernyataan salah, alasan benar.'
    ],
    answer: 0,
    pembahasan: 'Pernyataan A benar: keberagaman suku, budaya, dan bahasa di Indonesia memang sangat tinggi. Pernyataan B benar: Indonesia adalah negara kepulauan luas dengan kondisi geografis beragam. Keduanya memiliki hubungan sebab-akibat: kondisi geografis kepulauan menyebabkan keberagaman tersebut. Jawaban: A.'
  },
  {
    q: 'Perhatikan pernyataan di bawah ini!\n1) Kedudukan matahari yang berubah-ubah\n2) Wilayah Indonesia yang terdiri dari pulau-pulau\n3) Indonesia memiliki gunung-gunung yang tinggi\n4) Masih banyaknya hutan hujan tropis yang luas\n5) Kepadatan penduduk di wilayah perkotaan tinggi\n\nBerdasarkan pernyataan di atas, faktor yang dapat mempengaruhi iklim di Indonesia adalah ....',
    opts: ['(1), (2), dan (3)', '(1), (3), dan (4)', '(2), (3), dan (4)', '(2), (3), dan (5)'],
    answer: 0,
    pembahasan: 'Faktor yang mempengaruhi iklim di Indonesia adalah: (1) kedudukan matahari yang berubah-ubah, (2) wilayah kepulauan, (3) gunung-gunung tinggi, dan (4) hutan hujan tropis. Kepadatan penduduk perkotaan (5) bukan faktor utama iklim. Jawaban: A.'
  },
  {
    q: 'Fauna di wilayah Indonesia barat memiliki kesamaan dengan fauna yang berada di Malaysia, Thailand, dan Filipina. Wilayah fauna tersebut dalam region ....',
    opts: ['Neotropikal', 'Oriental', 'Neartik', 'Pertengahan'],
    answer: 1,
    pembahasan: 'Fauna di Indonesia bagian barat termasuk ke dalam region Oriental (Asia), yang meliputi Asia Selatan dan Asia Tenggara termasuk Malaysia, Thailand, dan Filipina. Cirinya mirip dengan fauna di daratan Asia. Jawaban: B.'
  },
  {
    q: 'Perhatikan pernyataan di bawah ini!\n\nPernyataan A: Tanah humus merupakan tanah mineral yang berasal dari pelapukan dedaunan dan berbagai bagian tanaman lainnya.\nPernyataan B: Tanah humus cenderung berwarna gelap, sangat gembur, banyak unsur hara, dan sangat cocok untuk pertanian.\n\nBerdasarkan pernyataan di atas, hubungan dua pernyataan yang tepat adalah ....',
    opts: [
      'Pernyataan benar, pernyataan benar, dan ada hubungan',
      'Pernyataan A benar, pernyataan B benar tetap tidak ada hubungan',
      'Pernyataan A benar dan Pernyataan B salah',
      'Pernyataan A salah dan pernyataan B benar'
    ],
    answer: 3,
    pembahasan: 'Pernyataan A benar: tanah humus berasal dari pelapukan bahan organik. Pernyataan B benar: tanah humus berwarna gelap, gembur, kaya unsur hara dan cocok untuk pertanian. Keduanya memiliki hubungan sebab-akibat. Jawaban: D.'
  },
  {
    q: 'Perhatikan pernyataan di bawah ini!\n1) Wilayahnya memiliki banyak Cadangan air\n2) Curah hujan yang rendah dalam satu tahun\n3) Mata pencaharian penduduk mayoritas beternak\n4) Memiliki hamparan padang rumput yang luas\n5) Wilayahnya memiliki iklim tropis\n\nBerdasarkan pernyataan di atas, yang mempengaruhi wilayah Nusa Tenggara dijadikan daerah peternakan besar adalah ....',
    opts: ['(1), (2), dan (3)', '(1), (2), dan (4)', '(2), (3), dan (5)', '(2), (4), dan (5)'],
    answer: 3,
    pembahasan: 'Nusa Tenggara menjadi daerah peternakan besar karena: curah hujan rendah (2), mata pencaharian mayoritas beternak (3), dan memiliki hamparan padang rumput luas (4), serta iklim yang cocok. Jawaban: D.'
  },
  {
    q: 'Perhatikan pernyataan di bawah ini!\n1) Eksploitasi sumber daya alam yang berlebihan menyebabkan kerusakan lingkungan seperti menyebabkan pencemaran air dan udara\n2) Terjadinya bencana alam tidak termasuk dampak dari eksploitasi sumber daya alam karena berasal dari lingkungan\n3) Ketergantungan terhadap sumber daya alam yang tidak dapat diperbarui akan menyebabkan kelangkaan\n4) Pengelolaan sumber daya alam seperti alih fungsi lahan pertanian merupakan wewenang suatu daerah.\n\nBerdasarkan pernyataan di atas, urutan benar-salah yang tepat adalah ....',
    opts: ['Benar - Salah - Benar - Salah', 'Benar - Salah - Salah - Benar', 'Salah - Benar - Salah - Benar', 'Salah - Salah - Benar - Benar'],
    answer: 0,
    pembahasan: 'Pernyataan 1 Benar, Pernyataan 2 Salah (bencana alam bisa dipicu eksploitasi), Pernyataan 3 Benar, Pernyataan 4 Salah (alih fungsi lahan bukan hanya wewenang daerah, ada regulasi nasional). Jawaban: A.'
  },
  {
    q: 'Indonesia terletak di daerah pertemuan di antara tiga lempeng besar dunia dan mengakibatkan sebagian besar wilayah di Indonesia rawan terhadap bencana gempa bumi dan gunung meletus. Kalimantan merupakan salah satu wilayah di Indonesia yang relatif aman dari bencana gempa bumi dan gunung meletus. Faktor yang menyebabkan hal tersebut adalah ....',
    opts: [
      'wilayahnya yang luas dan datar',
      'tanahnya didominasi oleh jenis tanah gambut',
      'jauh dari zona subduksi lempeng',
      'bagian dari Dangkalan Sunda'
    ],
    answer: 2,
    pembahasan: 'Kalimantan relatif aman dari gempa dan gunung meletus karena jauh dari zona subduksi lempeng tektonik. Aktivitas vulkanik dan gempa bumi berkaitan langsung dengan pertemuan lempeng, sedangkan Kalimantan berada jauh dari zona tersebut. Jawaban: C.'
  },
  {
    q: 'Perhatikan pernyataan tentang konservasi lahan pertanian berikut ini!\n\nPernyataan A: Konversi lahan pertanian menjadi non-pertanian terus terjadi seiring dengan meningkatnya jumlah penduduk dan kebutuhan lahan.\nPernyataan B: Upaya alternatif untuk mengatasi konversi lahan adalah melakukan perencanaan dan pengawasan tata ruang dengan baik.\n\nBerdasarkan pernyataan di atas, hubungan dua pernyataan berikut adalah ....',
    opts: [
      'Pernyataan A benar, Pernyataan B benar, dan ada hubungan',
      'Penyataan A benar, pernyataan B benar, tetapi tidak ada hubungan',
      'Pernyataan A benar, pernyataan B salah',
      'Pernyataan A salah, pernyataan B benar'
    ],
    answer: 0,
    pembahasan: 'Pernyataan A benar: konversi lahan pertanian terus terjadi seiring pertumbuhan penduduk. Pernyataan B benar: perencanaan tata ruang adalah solusi untuk mengatasi konversi. Keduanya memiliki hubungan. Jawaban: A.'
  },
  {
    q: 'Pernyataan yang paling sesuai terkait bentang alam dan keragaman sosial budaya adalah ....',
    opts: [
      'Masyarakat yang tinggal di pegunungan banyak yang bekerja sebagai pedagang sayuran.',
      'Masyarakat yang tinggal di dataran tinggi lebih sering memakai pakaian yang tipis.',
      'Masyarakat yang tinggal di dataran rendah banyak yang bekerja sebagai petani.',
      'Masyarakat yang tinggal di tepi Pantai lebih sering memakai pakaian yang tebal.'
    ],
    answer: 2,
    pembahasan: 'Hubungan antara bentang alam dan sosial budaya: masyarakat dataran rendah yang subur banyak bekerja sebagai petani. Dataran tinggi/pegunungan cenderung berpakaian tebal karena dingin, bukan tipis. Jawaban: C.'
  },
  {
    q: '[GAMBAR RUMAH ADAT BADUY di kawasan pegunungan dengan atap ijuk dan bahan kayu]\n\nMasyarakat Baduy, yang mendiami kawasan Pegunungan Kendeng di Banten, memiliki kondisi alam yang khas dan sistem sosial yang unik. Mereka hidup berdampingan dengan alam yang masih alami. Bagaimana pola pemukiman masyarakat Baduy ....',
    opts: [
      'Pemukiman Baduy berada di dekat sumber air seperti Sungai',
      'Pola pemukiman masyarakat Baduy tersebar di seluruh kaki gunung',
      'Pola pemukiman tidak tertata karena adat istiadat',
      'Pola pemukiman jauh dari sumber mata air'
    ],
    answer: 0,
    pembahasan: 'Masyarakat Baduy memiliki pola pemukiman yang dekat dengan sumber air seperti sungai, karena mereka sangat bergantung pada alam dan air untuk kehidupan sehari-hari. Ini merupakan salah satu kearifan lokal mereka. Jawaban: A.'
  },
  {
    q: 'Bacalah penggalan artikel di bawah ini!\n\n"Gempa Yogyakarta (2006) Pada 27 Mei 2006, tepat di pagi hari pukul 05.53, terjadi gempa bumi berkekuatan 5,9 SR yang mengguncang Yogyakarta dan sekitarnya. Sebanyak lebih dari 5.800 orang meninggal dan 20.000 lainnya terluka. Akibat dari peristiwa gempa 2006, Yogyakarta mulai meningkatkan mitigasi bencana. Deklarasi Yogya ditetapkan sebagai Dokumen PBB."\n\nBerdasarkan wacana di atas, Dampak dari gejala alam yang terjadi terhadap Pendidikan di Indonesia terutama pelajar Yogyakarta yaitu ....',
    opts: [
      'Diterapkan penilaian tentang materi bencana alam setiap semester',
      'Pengintergrasian Pendidikan mitigasi bencana di kurikulum sekolah',
      'Pembentukan organisasi di sekolah yang wajib diikuti oleh seluruh warga sekolah',
      'Meningkatkan karakter sekolah tanpa adanya Pendidikan mitigasi bencana karena dianggap tidak berpengaruh untuk kemajuan sekolah'
    ],
    answer: 0,
    pembahasan: 'Dampak gempa Yogyakarta 2006 terhadap pendidikan adalah mendorong pengintegrasian pendidikan mitigasi bencana di kurikulum sekolah, agar pelajar memiliki pengetahuan tentang cara menghadapi bencana alam. Jawaban: A.'
  },
  {
    q: 'Sebuah desa berada di ketinggian 0-100 mdpl dan memiliki bentang alam cukup beragam, mulai dari Lembah Sungai, dataran rendah, serta pesisir Pantai. Pada wilayah Pantai, Sebagian daerah pesisir berbatasan dengan laut lepas dan Sebagian lainnya berada di wilayah teluk maupun tanjung. Akses jalur darat masih sangat terbatas, sehingga membuat transportasi laut menjadi pilihan utama.\n\nBerdasarkan keadaan alam tersebut, mata pencaharian yang dapat dikembangkan oleh masyarakat adalah....',
    opts: [
      'Petani Mangrove',
      'Nelayan muroami dan nelayan keramba',
      'Pramuwisata dan persewaan perahu',
      'Petani rumput laut dan pembesaran ikan'
    ],
    answer: 1,
    pembahasan: 'Daerah pesisir dengan akses laut yang dominan dan wilayah teluk/tanjung sangat cocok untuk pengembangan nelayan, baik nelayan muroami (laut lepas) maupun nelayan keramba (budidaya). Jawaban: B.'
  },
  {
    q: 'Ani melihat temannya berdoa sebelum makan saat jajan di kantin sekolah. Kemudian, Ani mulai meniru kebiasaan baik tersebut. Peran lembaga sosial yang terlihat dalam ilustrasi tersebut adalah ....',
    opts: [
      'Lembaga pendidikan memberikan pelajaran agama',
      'Lembaga ekonomi mengajarkan cara berdagang',
      'Lembaga agama membentuk sikap dan nilai spiritual',
      'Lembaga hukum memberikan sanksi kepada pelanggar aturan'
    ],
    answer: 2,
    pembahasan: 'Berdoa sebelum makan adalah nilai spiritual yang diajarkan oleh lembaga agama. Ani meniru kebiasaan temannya berdoa menunjukkan peran lembaga agama dalam membentuk sikap dan nilai spiritual masyarakat. Jawaban: C.'
  },

  // ── SEGMEN B: Keragaman, Interaksi & Perubahan Sosial (No. 16–30) ──
  {
    q: 'Ketika terjadi pencurian di desa, polisi datang dan menangkap pelakunya. Hal ini menunjukkan bahwa lembaga hukum berfungsi untuk ....',
    opts: [
      'Memberi pelatihan keterampilan',
      'Menyelesaikan masalah ekonomi masyarakat',
      'Menegakkan aturan dan memberi sanksi',
      'Mengajarkan sopan santun di masyarakat'
    ],
    answer: 2,
    pembahasan: 'Fungsi lembaga hukum adalah menegakkan aturan dan memberikan sanksi kepada pelanggar hukum. Polisi menangkap pelaku pencurian merupakan contoh nyata fungsi penegakan hukum. Jawaban: C.'
  },
  {
    q: 'Di sekolah, siswa terbiasa antri saat membeli makanan di kantin. Kebiasaan ini jika dilanggar tidak mendapatkan hukuman berat, tapi dianggap tidak sopan. Kebiasaan ini termasuk dalam ....',
    opts: ['Norma hokum', 'Norma agama', 'Folkways', 'Mores (tata kelakuan)'],
    answer: 2,
    pembahasan: 'Folkways adalah kebiasaan sosial yang dianggap sopan dan berlaku dalam masyarakat. Pelanggarannya tidak mendapat sanksi hukum berat tetapi dianggap tidak sopan. Antri di kantin adalah contoh folkways. Jawaban: C.'
  },
  {
    q: 'Di lingkungan rumah, Ani selalu membantu orang tuanya membersihkan rumah dan menjaga adiknya saat orang tuanya bekerja. Karena sikap Ani tersebut, orang tua Ani memberikan kasih sayang sepenuhnya. Hal ini menunjukkan bahwa Ani ....',
    opts: [
      'Melaksanakan haknya sebagai anak',
      'Tidak ingin berinteraksi dengan teman-temannya',
      'Menjalankan peran dan tanggung jawabnya di keluarga',
      'Mengarah pada interaksi sosial disosiatif kompetisi dengan adiknya'
    ],
    answer: 2,
    pembahasan: 'Ani membantu orang tua dan menjaga adik menunjukkan bahwa ia menjalankan peran dan tanggung jawabnya sebagai anggota keluarga. Ini adalah wujud kewajiban anak dalam lingkup keluarga. Jawaban: C.'
  },
  {
    q: 'Dalam kegiatan kerja bakti di lingkungan RT, Ani lebih memilih berlama lama mengerjakan PR nya daripada ikut membantu. Apa dampak dari sikap anti terhadap lingkungan sosialnya? Terkait dengan peran dan tanggung jawab sosial di lingkungan masyarakat manakah pernyataan di bawah ini yang paling tepat?',
    opts: [
      'Ani akan menjadi panutan bagi teman-temannya',
      'Masyarakat akan menghargai sikap Ani yang mandiri',
      'Ani akan dianggap bertanggung jawab karena menyelesaikan PR',
      'Ani dapat dianggap tidak peduli dan kurang memiliki tanggung jawab sosial'
    ],
    answer: 3,
    pembahasan: 'Sikap Ani yang tidak ikut kerja bakti menunjukkan kurangnya tanggung jawab sosial. Dalam kehidupan bermasyarakat, setiap warga memiliki kewajiban untuk berpartisipasi dalam kegiatan sosial seperti kerja bakti. Jawaban: D.'
  },
  {
    q: 'Dalam masyarakat yang memiliki keragaman budaya, individu sering terlibat dalam interaksi sosial dengan orang lain yang memiliki latar belakang berbeda.\n1) Interaksi sosial asosiatif melibatkan sikap saling menghargai dan kerja sama.\n2) Interaksi sosial disosiatif melibatkan kerjasama dan pembauran antar budaya.\n3) Konflik dalam masyarakat sering terjadi akibat kurangnya toleransi antar kelompok.\n4) Akomodasi adalah upaya untuk mengatasi perbedaan secara damai tanpa konflik.\n\nManakah pernyataan yang sesuai dengan fenomena interaksi sosial ....',
    opts: ['1 dan 2', '2 dan 4', '3 dan 4', '1 dan 4'],
    answer: 3,
    pembahasan: 'Pernyataan 1 benar: interaksi asosiatif melibatkan kerja sama dan saling menghargai. Pernyataan 4 benar: akomodasi adalah upaya damai mengatasi perbedaan. Pernyataan 2 salah (disosiatif adalah pertentangan). Pernyataan 3 benar juga, namun pilihan "1 dan 4" paling tepat secara keseluruhan. Jawaban: D.'
  },
  {
    q: 'Di kota besar, banyak orang yang berbeda latar belakang sosial dan budaya tinggal berdampingan. Terkadang, hal ini menyebabkan terjadinya perbedaan pendapat antara kelompok-kelompok tersebut.\n\nPerhatikan pernyataan di bawah ini:\n1) Asimilasi adalah proses di mana dua budaya berbeda digabungkan menjadi satu budaya baru.\n2) Perbedaan pendapat antar kelompok sering mengarah pada persaingan yang tidak sehat.\n3) Dalam asimilasi, masyarakat saling mempertahankan budaya asli mereka tanpa menggabungkannya dengan budaya lain.\n4) Asimilasi dapat memperkaya budaya suatu masyarakat dengan memadukan unsur-unsur dari berbagai budaya.\n\nManakah pernyataan yang sesuai dengan fenomena yang diamati ....',
    opts: ['1 dan 2', '1 dan 4', '2 dan 3', '2 dan 4'],
    answer: 1,
    pembahasan: 'Pernyataan 1 benar: asimilasi adalah peleburan dua budaya menjadi satu. Pernyataan 4 benar: asimilasi memperkaya budaya. Pernyataan 3 salah (itu akulturasi). Jawaban: B.'
  },
  {
    q: 'Artis instagram atau biasa dikenal dengan selebgram sering kali memamerkan barang dan aksesorisnya di sosial media. Ani yang menjadi pengikutnya akhirnya membeli barang tersebut tanpa berpikir panjang, ia melakukan hal tersebut karena ingin memiliki sesuatu yang sama dengan artis idolanya. Tindakan yang dilakukan Ani dikategorikan sebagai ....',
    opts: [
      'imitasi karena sosial meniru sikap, tindakan, tingkah laku, atau penampilan fisik seseorang.',
      'identifikasi karena membutuhkan proses, Ani ingin benar-benar mirip dengan artis idolanya',
      'sugesti karena memberikan pengaruh buruk pada Ani karena Ani melihat kehidupan pribadi artis tersebut',
      'simpati karena Ani merasakan hal yang Artis Idolanya rasakan kebahagiaannya membeli produk serupa.'
    ],
    answer: 0,
    pembahasan: 'Tindakan Ani membeli barang karena ingin sama dengan artis idolanya adalah imitasi—meniru perilaku atau gaya orang lain. Imitasi adalah proses meniru yang sederhana tanpa melalui proses mendalam. Jawaban: A.'
  },
  {
    q: 'Di sebuah kota besar, berbagai etnis, agama, dan budaya hidup berdampingan. Masyarakat menjalani kehidupan yang saling menghormati meski ada perbedaan.\n1) Masyarakat di kota tersebut menunjukkan sikap saling menghargai terhadap perbedaan.\n2) Saling menghargai adalah bagian dari nilai-nilai toleransi dalam kehidupan sosial.\n3) Masyarakat di kota tersebut tidak memiliki perbedaan dalam budaya, agama, dan etnis.\n4) Toleransi adalah sikap saling menghargai dan menerima perbedaan dalam masyarakat.\n\nManakah pernyataan yang sesuai dengan fenomena yang diamati ....',
    opts: ['1 dan 2', '1 dan 4', '2 dan 3', '3 dan 4'],
    answer: 0,
    pembahasan: 'Pernyataan 1 benar: masyarakat saling menghargai perbedaan. Pernyataan 2 benar: saling menghargai bagian dari toleransi. Pernyataan 3 salah (kota besar justru penuh perbedaan). Pernyataan 4 benar tapi pilihan "1 dan 2" paling sesuai ilustrasi. Jawaban: A.'
  },
  {
    q: 'Dieng Culture Festival yang diselenggarakan setiap tahunnya di Dieng Jawa Tengah. Penyelenggaraan festival ini Memiliki dampak positif karena mendatangkan wisatawan. Sebagai konsekuensi masyarakat plural Indonesia, Dampak positif dari masyarakat plural yang sesuai dengan paparan di atas adalah ....',
    opts: [
      'menarik pengunjung dari berbagai daerah baik dalam maupun luar negeri sehingga meningkatkan sektor pendapatan',
      'meningkatkan keragaman budaya Indonesia',
      'membuka akses bagi Indonesia untuk mengadakan acara serupa yang diselenggarakan di negara lain',
      'masyarakat Indonesia khususnya Dieng dapat lebih mencintai budaya luar'
    ],
    answer: 0,
    pembahasan: 'Dieng Culture Festival menarik wisatawan dari berbagai daerah dan luar negeri, sehingga meningkatkan sektor pendapatan daerah. Ini adalah dampak positif langsung dari keberagaman budaya Indonesia. Jawaban: A.'
  },
  {
    q: 'Globalisasi sangat berpengaruh erat dengan kehidupan masyarakat yang memberikan dampak baik positif dan juga negatif. Salah satu dampak positif dari globalisasi bagi pelajar adalah ....',
    opts: [
      'lebih suka produk luar negeri yang bermerk daripada produk lokal dari Indonesia',
      'mengikuti gaya hidup mewah kelas atas dari luar negeri agar lebih prestisius',
      'Dapat belajar berbagai hal dari internet dan teknologi modern',
      'Mengabaikan budaya dan adat istiadat sendiri'
    ],
    answer: 2,
    pembahasan: 'Dampak positif globalisasi bagi pelajar adalah kemudahan akses informasi dan teknologi, termasuk belajar berbagai hal dari internet dan teknologi modern. Jawaban: C.'
  },
  {
    q: 'Ani membeli sepatu baru padahal sepatunya yang lama masih bagus. Ketika ditanya, ia menjawab hanya ingin punya model terbaru. Berdasar ilustrasi tersebut, yang dipenuhi Ani termasuk ....',
    opts: ['Kebutuhan primer', 'Kebutuhan sekunder', 'Kebutuhan tersier', 'Keinginan'],
    answer: 3,
    pembahasan: 'Membeli sepatu baru padahal yang lama masih bagus hanya karena ingin model terbaru bukan kebutuhan melainkan keinginan. Keinginan adalah hasrat yang tidak harus terpenuhi untuk keberlangsungan hidup. Jawaban: D.'
  },
  {
    q: 'Ayah bekerja sebagai tukang kayu. Ia membeli bahan makanan, membayar listrik, dan menabung untuk membeli sepeda motor. Urutan kebutuhan berdasarkan skala prioritas yang tepat adalah ....',
    opts: [
      'Sepeda motor, bahan makanan, listrik',
      'Listrik, sepeda motor, bahan makanan',
      'Bahan makanan, listrik, sepeda motor',
      'Sepeda motor, listrik, bahan makanan'
    ],
    answer: 2,
    pembahasan: 'Skala prioritas: kebutuhan primer (bahan makanan) harus didahulukan, kemudian kebutuhan sekunder/rutin (listrik), baru kebutuhan tersier/keinginan (sepeda motor). Jawaban: C.'
  },
  {
    q: 'Nelayan membawa ikan dari laut ke pasar agar bisa dijual dan dikonsumsi masyarakat kota. Kegiatan ini menunjukkan nilai guna ....',
    opts: ['form utility', 'time utility', 'place utility', 'ownership utility'],
    answer: 2,
    pembahasan: 'Place utility (nilai guna tempat) adalah nilai guna yang meningkat karena perpindahan tempat. Ikan dipindahkan dari laut ke pasar kota sehingga lebih bermanfaat dan bernilai. Jawaban: C.'
  },
  {
    q: 'Berikut ini yang menunjukkan ownership utility adalah ....',
    opts: [
      'Buah mangga bisa dimakan saat matang, tetapi saat mentah bisa digunakan untuk rujak',
      'Bu Ani menjual sepedanya kepada tetangga, sepeda itu lebih bermanfaat bagi tetangga karena digunakan untuk bekerja',
      'Seorang petani memiliki banyak bambu di kebunnya. Ia memanfaatkannya untuk membuat kursi dan meja',
      'Bu Ani ibu membeli kain dan menjahitnya menjadi pakaian. Setelah menjadi baju, barang tersebut memiliki nilai lebih.'
    ],
    answer: 1,
    pembahasan: 'Ownership utility (nilai guna kepemilikan) adalah nilai guna yang meningkat karena berpindah tangan ke orang yang lebih membutuhkan. Sepeda Bu Ani lebih bermanfaat bagi tetangga yang menggunakannya untuk bekerja. Jawaban: B.'
  },
  {
    q: 'Ani menemukan batu unik dan ingin menggunakannya untuk membeli makanan di warung. Namun, penjual menolak karena batu itu tidak bisa digunakan sebagai alat tukar. Hal ini menunjukkan bahwa batu tersebut tidak memenuhi syarat ....',
    opts: ['Mudah dibagi', 'Diterima umum', 'Tahan lama', 'Memiliki nilai tinggi'],
    answer: 1,
    pembahasan: 'Salah satu syarat uang adalah diterima umum (acceptability). Batu ditolak penjual berarti tidak memenuhi syarat diterima umum sebagai alat tukar. Jawaban: B.'
  },

  // ── SEGMEN C: Kegiatan Ekonomi & Peran Indonesia (No. 31–45) ──
  {
    q: 'Mengapa emas dan perak pernah digunakan sebagai uang pada masa lalu?',
    opts: [
      'Karena bisa dimakan dan dicetak dengan mudah',
      'Karena jumlahnya sangat banyak di alam',
      'Karena tidak mudah rusak dan nilainya tinggi',
      'Karena bentuknya mirip seperti uang logam zaman sekarang'
    ],
    answer: 2,
    pembahasan: 'Emas dan perak digunakan sebagai uang karena memenuhi syarat uang: tidak mudah rusak (tahan lama), nilai intrinsiknya tinggi, dapat dibagi, dan mudah dibawa. Jawaban: C.'
  },
  {
    q: 'Indonesia dikenal sebagai negara agraris dan maritim, sedangkan Singapura lebih mengandalkan sektor industri dan jasa. Perbedaan ini terjadi karena ....',
    opts: [
      'Indonesia memiliki teknologi lebih canggih daripada Singapura',
      'Singapura memiliki banyak lahan pertanian dan tambak',
      'Kondisi geografis dan sumber daya alam tiap negara berbeda',
      'Indonesia tidak bekerja sama dengan negara ASEAN lainnya'
    ],
    answer: 2,
    pembahasan: 'Perbedaan sektor andalan antara Indonesia dan Singapura disebabkan oleh perbedaan kondisi geografis dan sumber daya alam. Indonesia memiliki lahan luas dan SDA melimpah untuk pertanian dan kelautan, sementara Singapura terbatas lahan sehingga fokus pada industri dan jasa. Jawaban: C.'
  },
  {
    q: 'Vietnam memanfaatkan wilayah datar dan sungai Mekong untuk menanam padi. Jika pemerintah Vietnam ingin meningkatkan hasil panen, langkah yang tepat adalah ....',
    opts: [
      'Menutup lahan pertanian dan membangun pabrik',
      'Mengembangkan teknologi pertanian dan irigasi',
      'Mengimpor beras dari negara lain',
      'Mengalihkan petani menjadi pekerja tambang'
    ],
    answer: 1,
    pembahasan: 'Untuk meningkatkan hasil panen, Vietnam perlu mengembangkan teknologi pertanian dan sistem irigasi. Teknologi pertanian modern meningkatkan produktivitas lahan, sedangkan irigasi memastikan ketersediaan air yang cukup. Jawaban: B.'
  },
  {
    q: 'Dalam suatu keluarga, ayah bekerja di pabrik, ibu membuka toko sembako, dan anak-anak belajar di sekolah. Siapa saja yang termasuk pelaku ekonomi dalam keluarga tersebut?',
    opts: ['Ayah dan anak', 'Ibu dan anak', 'Ayah dan ibu', 'Hanya ayah'],
    answer: 2,
    pembahasan: 'Pelaku ekonomi adalah pihak yang melakukan kegiatan ekonomi (produksi, distribusi, atau konsumsi). Ayah bekerja di pabrik (produksi/konsumsi) dan ibu membuka toko (produksi/distribusi). Anak hanya belajar, belum termasuk pelaku ekonomi aktif. Jawaban: C.'
  },
  {
    q: 'Jepang mengimpor batubara dari Indonesia dan Indonesia mengimpor alat elektronik dari Jepang. Kegiatan ini menunjukkan bahwa ...',
    opts: [
      'Indonesia lebih kaya daripada Jepang karena mengekspor bahan baku',
      'Indonesia dan Jepang saling memanfaatkan kelebihan masing-masing',
      'Jepang lebih bergantung pada bahan mentah dari Indonesia',
      'Indonesia hanya bisa mengimpor, tidak bisa mengekspor'
    ],
    answer: 1,
    pembahasan: 'Hubungan ekspor-impor Indonesia-Jepang menunjukkan bahwa kedua negara saling memanfaatkan kelebihan masing-masing (keunggulan komparatif). Indonesia unggul dalam SDA, Jepang unggul dalam teknologi. Jawaban: B.'
  },
  {
    q: 'Sebagian besar masyarakat Indonesia bekerja di bidang pertanian, seperti menanam padi, jagung, dan sayur. Apa manfaat dari potensi agraris tersebut bagi kehidupan masyarakat?',
    opts: [
      'Mengurangi ketergantungan terhadap ekspor karena dapat dicukupi sendiri',
      'Meningkatkan bangunan di desa untuk memperluas areal pemukiman',
      'Menyediakan bahan makanan dan menciptakan lapangan kerja',
      'Menurunkan harga pupuk dan alat pertanian'
    ],
    answer: 2,
    pembahasan: 'Potensi agraris Indonesia bermanfaat untuk menyediakan bahan makanan bagi masyarakat sekaligus menciptakan lapangan kerja di sektor pertanian. Jawaban: C.'
  },
  {
    q: 'Salah satu tujuan pembangunan berkelanjutan (SDGs) adalah mengurangi kemiskinan. Kegiatan yang dapat mendukung tujuan tersebut adalah ....',
    opts: [
      'Membangun pusat perbelanjaan besar diprioritaskan di kota daripada desa',
      'Memberikan pelatihan keterampilan dan modal usaha untuk warga desa',
      'Membatasi jumlah penduduk miskin agar tidak bertambah',
      'Membuka tambang di hutan tanpa izin masyarakat'
    ],
    answer: 1,
    pembahasan: 'Untuk mengurangi kemiskinan sesuai SDGs, langkah tepat adalah memberikan pelatihan keterampilan dan modal usaha kepada warga desa agar mereka dapat mandiri secara ekonomi. Jawaban: B.'
  },
  {
    q: '[GAMBAR DUA BENDA LOGAM: kiri adalah kendi/guci tinggi berwarna abu, kanan adalah wadah/dulang bulat berkaki tiga]\n\nBagaimana hubungan benda di atas dengan masa perundagian ....',
    opts: [
      'pada masa perundagian manusia praaksara sudah mampu membuat kendi untuk menampung air dan golok untuk bercocok tanam',
      'pada masa perundagian manusia praaksara sudah mampu membuat gerabah sebagai alat makan dan kapak sepatu untuk berburu',
      'pada masa perundagian manusia praaksara sudah mampu membuat gendang sebagai alat bermusik dan terompet untuk bernyanyi',
      'pada masa perundagian manusia praaksara sudah mampu memproduksi nekara sebagai benda pusaka dan kapak corong sebagai alat pertukangan'
    ],
    answer: 3,
    pembahasan: 'Masa perundagian ditandai oleh kemampuan manusia praaksara memproduksi benda-benda logam seperti nekara (alat upacara/benda pusaka dari perunggu) dan kapak corong (kapak perunggu untuk pertukangan). Jawaban: D.'
  },
  {
    q: 'Tempat-tempat ditemukannya manusia purba di Nusantara mulai dari jenis Pithecanthropus dan Homo Sapiens menunjukkan bahwa ....',
    opts: [
      'manusia purba Indonesia jumlahnya banyak',
      'adanya kemiripan ciri fisik dari fosil peninggalan',
      'manusia purba banyak menetap di tepi aliran sungai',
      'manusia purba memiliki tempat tinggal yang berdekatan'
    ],
    answer: 3,
    pembahasan: 'Temuan fosil manusia purba dari berbagai jenis di Nusantara menunjukkan bahwa manusia purba memiliki tempat tinggal yang berdekatan, berkumpul di kawasan yang mendukung kehidupan (tepi sungai, gua). Jawaban: D.'
  },
  {
    q: 'Salah satu bukti arkeologis terkuat yang menunjukkan pengaruh Hindu-Buddha tertua di Indonesia, berupa tujuh yupa yang berangka tahun sekitar abad ke-5 Masehi, ditemukan di Kerajaan ...',
    opts: ['Tarumanegara', 'Kutai', 'Sriwijaya', 'Mataram Kuno'],
    answer: 1,
    pembahasan: 'Tujuh prasasti Yupa yang merupakan bukti tertua pengaruh Hindu-Buddha di Indonesia ditemukan di Kerajaan Kutai, Kalimantan Timur, berasal dari sekitar abad ke-4 sampai ke-5 Masehi. Jawaban: B.'
  },

  // ── SEGMEN D: Perkembangan Sejarah Indonesia (No. 41–50) ──
  {
    q: 'Perhatikan pernyataan di bawah ini!\n1) Kerajaan-kerajaan Hindu Budha di Indonesia tumbuh dari terbentuknya pusat-pusat perdagangan yang dibangun oleh para pedagang India\n2) Tujuan utama para pedagang India melakukan hubungan dengan wilayah Nusantara adalah mencari pusat penghasil rempah-rempah\n3) Raja dan bangsawan pada masa Kerajaan Hindu Budha turut berperan aktif dalam kegiatan perdagangan untuk memperkuat ekonomi maritim\n4) Hubungan dagang antara orang Indonesia dan India telah mengakibatkan masuknya pengaruh budaya India dalam budaya Indonesia\n\nBerdasarkan pernyataan di atas, urutan benar-salah yang tepat adalah ....',
    opts: ['Benar- Salah- Benar- Salah', 'Benar- Benar- Salah- Salah', 'Salah- Benar- Salah- Benar', 'Salah- Salah- Benar- Benar'],
    answer: 3,
    pembahasan: 'Pernyataan 1 Salah (kerajaan tumbuh dari berbagai faktor, bukan hanya pedagang India). Pernyataan 2 Salah (tujuan utama adalah perdagangan, rempah hanya salah satunya). Pernyataan 3 Benar. Pernyataan 4 Benar. Jawaban: D.'
  },
  {
    q: 'Samudera Pasai merupakan kerajaan Islam pertama yang terletak di pesisir pantai utara Sumatera yang tercantum dalam kitab "Rihlah ilal Masyriq" karya Abu Abdullah ibnu Batuthah (1304–1368). Salah satu faktor yang menyebabkan Kerajaan Samudera Pasai menjadi kerajaan pertama yang terpengaruh agama Islam adalah......',
    opts: [
      'Para pemudanya bermukim di Arab',
      'Sultannya berasal dari Timur Tengah',
      'Menjadi daerah taklukan Kesultanan Delhi',
      'Merupakan tempat transit pedagang Muslim'
    ],
    answer: 3,
    pembahasan: 'Samudera Pasai menjadi kerajaan Islam pertama karena letaknya sebagai tempat transit pedagang Muslim dari Arab, Persia, dan India dalam jalur perdagangan. Interaksi dengan pedagang Muslim mendorong masuknya Islam. Jawaban: D.'
  },
  {
    q: 'Pada masa awal perkembangan Islam di Indonesia, diperkenalkan Pendidikan dengan sistem halqoh yang dilakukan diberbagai tempat ibadah antara lain masjid musala, bahkan juga di rumah para ulama yang kemudian berkembang menjadi pesantren.\n\nTujuan utama Pendidikan pada masa awal ini didasarkan pada ....',
    opts: [
      'Sarana penyebaran Agama Islam',
      'Membentuk masyarakat berpendidikan',
      'Mempererat Kerjasama pedagang islam',
      'Memperkuat dukungan politik kesultanan'
    ],
    answer: 1,
    pembahasan: 'Pendidikan melalui sistem halqoh pada masa awal Islam bertujuan utama sebagai sarana penyebaran agama Islam kepada masyarakat Nusantara. Jawaban: B.'
  },
  {
    q: 'Perhatikan pernyataan mengenai dampak kebijakan Tanam Paksa di Hindhia Belanda:\n\nPernyataan A: Van den Bosch adalah tokoh utama di balik kebijakan Tanam Paksa (Cultuurstelsel). Ia memperkenalkan sistem Tanam Paksa sebagai solusi untuk meningkatkan pendapatan dari sektor pertanian di Hindia Belanda.\nPernyataan B: Belanda memperoleh keuntungan besar dari ekspor komoditi seperti kopi, gula, dan pala yang ditanam melalui sistem Tanam Paksa. Keuntungan ini sangat membantu memulihkan kondisi ekonomi Belanda yang sedang terpuruk akibat Perang Aceh.\n\nBerdasarkan pernyataan di atas, hubungan dua pernyataan berikut adalah ....',
    opts: [
      'Pernyataan A benar, penyataan B benar, dan ada hubungan',
      'Pernyataan A benar, pernyataan B benar, tetapi tidak ada hubungan',
      'Pernyataan A benar dan pernyataan B salah',
      'Pernyataan A salah dan pernyataan B benar'
    ],
    answer: 0,
    pembahasan: 'Pernyataan A benar: Van den Bosch memperkenalkan Cultuurstelsel. Pernyataan B benar: keuntungan dari ekspor komoditi membantu ekonomi Belanda. Keduanya berhubungan karena Cultuurstelsel dirancang untuk mendapat keuntungan ekonomi. Jawaban: A.'
  },
  {
    q: 'Van den Bosch pada tahun 1830 dipercaya menjalankan kebijakan pemerintah Belanda di Indonesia. Salah satunya adalah cultuurstelsel yang satu aturannya ditetapkan bahwa tanaman wajib dibudidayakan per desa. Dari aturan tersebut sesungguhnya cultuurstelsel tidak harus diterjemahkan sebagai tanam paksa akan tetapi kondisi berikut ini yang menjadikan program tersebut menjadi sistem yang dipaksakan dan menimbulkan kesengsaraan rakyat. Kondisi dimaksud adalah ...',
    opts: [
      'Setiap penduduk boleh membudidayakan tanaman wajib sesuai dengan kebutuhan pasar',
      'Cultuurstelsel dipusatkan di tanah subur sehingga terjadi migrasi terpaksa',
      'Kegagalan panen berarti penduduk harus menyerahkan tanah kepada pemerintah',
      'Kepala desa ditempatkan menjadi bagian dari sistem tanam paksa berbasis ekonomi pasar'
    ],
    answer: 1,
    pembahasan: 'Cultuurstelsel menjadi sistem yang menyengsarakan karena dipusatkan di tanah subur milik rakyat, sehingga rakyat terpaksa bermigrasi dan kehilangan lahan produktif mereka. Jawaban: B.'
  },
  {
    q: 'Dalam melaksanakan perjuangan para pemimpin bangsa Indonesia sangat hati-hati, karena pemerintah penduduk Jepang terkenal kejam dan menentang setiap kegiatan politik bangsa Indonesia. Oleh karena itu, bentuk perjuangan disesuaikan dengan memanfaatkan organisasi bentukan jepang. Organisasi yang digunakan oleh Ir. Soekarno dan Drs. Moh. Hatta untuk membina kesadaran Nasional para pemuda adalah ....',
    opts: [
      'PUTERA dan Jawa Barisan Pelopor',
      'PUTERA dan Jawa Hokokai',
      'Jawa Hokokai dan Barisan Pelopor',
      'Barisan Pelopor dan PUTERA'
    ],
    answer: 0,
    pembahasan: 'Soekarno dan Hatta memanfaatkan PUTERA (Pusat Tenaga Rakyat) dan Barisan Pelopor—dua organisasi bentukan Jepang—untuk membina kesadaran nasional para pemuda Indonesia. Jawaban: A.'
  },
  {
    q: 'Perhatikan pernyataan di bawah ini!\n1) Perlawanan bersenjata rakyat Indonesia terhadap VOC dan Belanda pada umumnya bersifat lokal dan sporadik\n2) Tujuan utama perlawanan Diponegoro di Jawa adalah untuk mengusir sepenuhnya Belanda dari Nusantara dan mendirikan negara Indonesia merdeka.\n3) Politik Etis yang diterapkan Belanda setelah tahun 1900 memberikan kesempatan penuh bagi rakyat pribumi untuk berpartisipasi dalam pemerintahan kolonial\n4) Peran ulama dan pondok pesantren sangat signifikan dalam memobilisasi perlawanan terhadap kolonialisme di berbagai daerah\n\nBerdasarkan pernyataan di atas, urutan benar-salah yang tepat adalah ....',
    opts: ['Benar – Salah – Benar – Salah', 'Benar – Salah – Salah – Benar', 'Salah – Benar – Salah – Benar', 'Salah – Salah – Benar – Benar'],
    answer: 1,
    pembahasan: 'Pernyataan 1 Benar. Pernyataan 2 Salah (tujuan Diponegoro bukan mendirikan RI modern, melainkan melawan Belanda dan mempertahankan tanah). Pernyataan 3 Salah (Politik Etis tidak memberi kesempatan penuh). Pernyataan 4 Benar. Jawaban: B.'
  },
  {
    q: 'Setelah para pemuda mendengar berita kekalahan Jepang, mereka mendesak kepada Ir. Soekarno dan Drs. Moh. Hatta agar segera memproklamasikan kemerdekaan Indonesia. Namun Ir. Soekarno dan Drs. Moh. Hatta berpendapat akan dibicarakan dulu dengan PPKI. Perbedaan pendapat antara golongan pemuda dengan golongan tua dalam Proklamasi menunjukkan ....',
    opts: [
      'Tingkat berpikir yang rendah',
      'Kondisi yang membahayakan persatuan',
      'Keinginan golongan muda untuk segera merdeka',
      'Terjadi perpecahan antara golongan tua dan muda'
    ],
    answer: 2,
    pembahasan: 'Perbedaan pendapat antara golongan muda dan tua tentang proklamasi menunjukkan keinginan kuat golongan muda untuk segera memproklamasikan kemerdekaan tanpa menunggu persetujuan PPKI. Jawaban: C.'
  },
  {
    q: 'Perjuangan kemerdekaan Indonesia adalah rangkaian peristiwa panjang dan kompleks yang melibatkan pertempuran fisik dan diplomasi untuk meraih kemerdekaan dari penjajahan Belanda dan Jepang.\n\nKesesuaian dari pernyataan A dengan pernyataan B ditunjukkan dengan pasangan:\n(1) Adanya keinginan kuat dari bangsa Indonesia\n(2) Kebijakkan politik adu domba\n(3) Kekalahan Jepang pada perang dunia II\n(4) Perkembangan organisasi-organisasi pergerakan Nasional\n\nPernyataan B:\nA. Devide et Impera\nB. Terbukanya negara untuk memproklamasikan kemerdekaan\nC. Meningkatnya pentingnya persatuan\nD. Semangat perlawanan Daerah',
    opts: [
      '(1)-D; (2)-A; (3)-B; (4)-C',
      '(1)-D; (2)-C; (3)-B; (4)-A',
      '(1)-C; (2)-A; (3)-B; (4)-D',
      '(1)-A; (2)-B; (3)-D; (4)-C'
    ],
    answer: 0,
    pembahasan: 'Pasangan yang tepat: (1) Keinginan kuat bangsa → D. Semangat perlawanan daerah; (2) Politik adu domba → A. Devide et Impera; (3) Kekalahan Jepang → B. Terbukanya kesempatan proklamasi; (4) Organisasi pergerakan → C. Pentingnya persatuan. Jawaban: A.'
  },
  {
    q: '[GAMBAR FOTO HITAM-PUTIH seorang tokoh laki-laki berjas, berambut rapi, wajah formal]\n\nTokoh yang dikenal karena perannya sebagai Perdana Menteri pertama Indonesia dan perjuangannya dalam melakukan diplomasi internasional untuk mendapatkan pengakuan kemerdekaan Indonesia. Ia juga dikenal karena melakukan pendekatan intelektual serta diplomatik dalam perjuangan kemerdekaan. Siapakah tokoh yang dimaksud dari kalimat dan gambar di atas ....',
    opts: ['Ir. Soekarno', 'Agus Salim', 'Sutan Sjahrir', 'Mohammad Hatta'],
    answer: 2,
    pembahasan: 'Sutan Sjahrir adalah Perdana Menteri pertama Indonesia yang dikenal dengan pendekatan diplomasi dan intelektual dalam perjuangan kemerdekaan. Ia berhasil mendapatkan pengakuan internasional atas kemerdekaan Indonesia. Jawaban: C.'
  }
];


// ─────────────────────────────────────────
// AKUN PENGGUNA
// ─────────────────────────────────────────
const USERS = {
  siswa: [
    { username:'nicky',  password:'nickyips#!1', name:'Nicky' },
  ],
  admin: [
    { username:'admin', password:'risku1818', name:'Administrator' },
    { username:'guru',  password:'guru2024',  name:'Guru' },
  ]
};

// ─────────────────────────────────────────
// STATE
// ─────────────────────────────────────────
let questions=[], cur=0, answers=[], timeLeft=CONFIG.duration, timerInterval=null;
let currentUser=null;
let activeTab='siswa';

// ─────────────────────────────────────────
// AUTH
// ─────────────────────────────────────────
function togglePw(id,btn){
  const el=document.getElementById(id);
  const show=el.type==='password';
  el.type=show?'text':'password';
  btn.textContent=show?'🙈':'👁';
}

function switchTab(tab){
  activeTab=tab;
  document.getElementById('tab-siswa').classList.toggle('active',tab==='siswa');
  document.getElementById('tab-admin').classList.toggle('active',tab==='admin');
  document.getElementById('form-siswa').style.display=tab==='siswa'?'block':'none';
  document.getElementById('form-admin').style.display=tab==='admin'?'block':'none';
  document.getElementById('login-error').classList.remove('show');
}

function doLogin(role){
  const u=document.getElementById(role+'-username').value.trim().toLowerCase();
  const p=document.getElementById(role+'-password').value;
  const match=USERS[role].find(x=>x.username===u&&x.password===p);
  if(!match){
    document.getElementById('login-error').textContent='Username atau password salah.';
    document.getElementById('login-error').classList.add('show');
    return;
  }
  currentUser={username:match.username,name:match.name,role};
  sessionStorage.setItem(SESSION_KEY,JSON.stringify(currentUser));
  addLog({action:'Login',detail:'Berhasil masuk sebagai '+role});
  startApp();
}

function doLogout(){
  if(!confirm('Yakin ingin keluar?')) return;
  clearInterval(timerInterval);
  addLog({action:'Logout',detail:'Keluar dari aplikasi'});
  currentUser=null;
  sessionStorage.removeItem(SESSION_KEY);
  document.getElementById('main-app').style.display='none';
  document.getElementById('login-screen').style.display='flex';
  ['siswa-username','siswa-password','admin-username','admin-password'].forEach(id=>{
    const el=document.getElementById(id); if(el) el.value='';
  });
  document.getElementById('login-error').classList.remove('show');
  switchTab('siswa');
}

function restoreSession(){
  try{const s=sessionStorage.getItem(SESSION_KEY); if(s){currentUser=JSON.parse(s);return true;}}catch(e){}
  return false;
}

function startApp(){
  document.getElementById('login-screen').style.display='none';
  document.getElementById('main-app').style.display='block';
  const av=document.getElementById('user-avatar');
  av.textContent=currentUser.name.charAt(0).toUpperCase();
  av.className='user-avatar '+currentUser.role;
  document.getElementById('user-name-display').textContent=currentUser.name;
  document.getElementById('user-role-display').innerHTML=
    currentUser.role==='admin'?'<span class="admin-badge">⚡ Admin</span>':'👨‍🎓 Siswa';
  const isAdmin=currentUser.role==='admin';
  document.getElementById('admin-clear-btn').style.display=isAdmin?'block':'none';
  document.getElementById('admin-only-notice').style.display=isAdmin?'flex':'none';
  document.getElementById('log-admin-controls').style.display=isAdmin?'block':'none';
  showScreen('tryout');
  init();
}

// ─────────────────────────────────────────
// INIT
// ─────────────────────────────────────────
// ─────────────────────────────────────────
// INIT — coba ambil JSON dari GitHub, fallback ke soal bawaan
// ─────────────────────────────────────────
const QUESTIONS_CACHE_KEY = 'osn_ips_questions_cache';
const QUESTIONS_CACHE_TS  = 'osn_ips_questions_cache_ts';
const CACHE_TTL_MS = 6 * 60 * 60 * 1000; // cache 6 jam

function setLoadingState(msg, sub){
  document.getElementById('loading-screen').style.display = 'block';
  document.getElementById('cbt-app').style.display = 'none';
  document.querySelector('.loading-text').innerHTML = msg + (sub ? '<br><span style="font-size:11px;color:var(--text-sec)">'+sub+'</span>' : '');
}

function launchWithQuestions(qs, source){
  questions = qs;
  answers = new Array(questions.length).fill(null);
  const srcTag = source === 'remote'
    ? ' <span style="font-size:10px;background:var(--green-light);color:var(--green-dark);padding:2px 6px;border-radius:20px;font-weight:600">🔄 Diperbarui</span>'
    : source === 'cache'
    ? ' <span style="font-size:10px;background:var(--amber-light);color:var(--amber-dark);padding:2px 6px;border-radius:20px;font-weight:600">📦 Cache</span>'
    : '';
  document.getElementById('header-title').innerHTML = 'LATIHAN OSN IPS NICKY' + srcTag;
  document.getElementById('header-subtitle').textContent =
    'Ujian Online — ' + questions.length + ' Soal Pilihan Ganda · 4 Segmen Materi';
  document.getElementById('loading-screen').style.display = 'none';
  document.getElementById('cbt-app').style.display = 'block';
  render();
  startTimer();
}

function validateQuestions(data){
  // Terima: array flat, array-of-arrays (per segmen), atau objek {questions:[...]}
  let arr;
  if(Array.isArray(data)){
    // Cek apakah array-of-arrays (format segmen)
    if(data.length > 0 && Array.isArray(data[0])){
      arr = data.flat();
    } else {
      arr = data;
    }
  } else if(data && Array.isArray(data.questions)){
    arr = data.questions;
  } else {
    return null;
  }
  if(!arr || arr.length === 0) return null;
  for(const q of arr){
    if(!q.text || !Array.isArray(q.options) || q.options.length < 2 ||
       typeof q.answer !== 'number' || !q.pembahasan) return null;
  }
  return arr;
}

async function init(){
  setLoadingState('⏳ Memuat soal...', '');

  // Jika ada URL JSON yang dikonfigurasi
  if(CONFIG.jsonUrl && CONFIG.jsonUrl.trim() !== ''){
    // Cek cache dulu
    try {
      const cachedTs = parseInt(localStorage.getItem(QUESTIONS_CACHE_TS) || '0');
      const now = Date.now();
      if(now - cachedTs < CACHE_TTL_MS){
        const cached = JSON.parse(localStorage.getItem(QUESTIONS_CACHE_KEY));
        const valid = validateQuestions(cached);
        if(valid){
          // Ada cache valid, coba update di background
          launchWithQuestions(valid, 'cache');
          fetchAndCacheQuestions(); // update cache tanpa blokir UI
          return;
        }
      }
    } catch(e){}

    // Tidak ada cache valid, fetch langsung
    setLoadingState('🌐 Mengambil soal terbaru dari server...', 'Mohon tunggu sebentar');
    try {
      await fetchAndCacheQuestions(true);
      return;
    } catch(e){
      // Fetch gagal, coba pakai cache lama
      try {
        const cached = JSON.parse(localStorage.getItem(QUESTIONS_CACHE_KEY));
        const valid = validateQuestions(cached);
        if(valid){
          showBanner('⚠️ Gagal mengambil soal terbaru. Menggunakan soal tersimpan (cache).', 'amber');
          launchWithQuestions(valid, 'cache');
          return;
        }
      } catch(e2){}
      // Fallback ke soal bawaan
      showBanner('❌ Gagal memuat soal. Pastikan URL JSON sudah dikonfigurasi dan dapat diakses.', 'red');
      setLoadingState('❌ Gagal memuat soal', 'Periksa konfigurasi URL JSON di CONFIG.jsonUrl');
    }
  } else {
    // Tidak ada URL dikonfigurasi — gunakan soal bawaan (BUILTIN_QUESTIONS)
    if(BUILTIN_QUESTIONS && BUILTIN_QUESTIONS.length > 0){
      const normalized = BUILTIN_QUESTIONS.map(q => ({
        text: q.q || q.text,
        options: q.opts || q.options,
        answer: q.answer,
        pembahasan: q.pembahasan,
        image: q.image || null,
        image_caption: q.image_caption || null
      }));
      launchWithQuestions(normalized, 'builtin');
    } else {
      setLoadingState('Soal tidak tersedia', 'Tidak ada soal yang dimuat.');
    }
  }
}

async function fetchAndCacheQuestions(shouldLaunch){
  const url = CONFIG.jsonUrl.trim();
  const res = await fetch(url, { cache: 'no-cache' });
  if(!res.ok) throw new Error('HTTP ' + res.status);
  const data = await res.json();
  const valid = validateQuestions(data);
  if(!valid) throw new Error('Format JSON tidak valid');

  // Simpan ke cache
  localStorage.setItem(QUESTIONS_CACHE_KEY, JSON.stringify(valid));
  localStorage.setItem(QUESTIONS_CACHE_TS, String(Date.now()));

  if(shouldLaunch) launchWithQuestions(valid, 'remote');
}

function showBanner(msg, type){
  const colors = {
    amber: {bg:'var(--amber-light)', border:'var(--amber)', color:'var(--amber-dark)'},
    red:   {bg:'var(--red-light)',   border:'var(--red)',   color:'var(--red-dark)'},
    green: {bg:'var(--green-light)', border:'var(--green)', color:'var(--green-dark)'},
  };
  const c = colors[type] || colors.amber;
  const banner = document.createElement('div');
  banner.style.cssText = 'background:'+c.bg+';border:1px solid '+c.border+';color:'+c.color+
    ';font-size:12px;padding:10px 16px;border-radius:9px;margin-bottom:10px;display:flex;align-items:center;justify-content:space-between;gap:8px';
  banner.innerHTML = '<span>'+msg+'</span><button onclick="this.parentElement.remove()" style="background:none;border:none;cursor:pointer;font-size:14px;color:inherit;line-height:1">✕</button>';
  const wrap = document.querySelector('.wrap');
  const nav = document.querySelector('.top-nav');
  if(nav) nav.after(banner); else wrap.prepend(banner);
}

// Tombol admin: paksa refresh soal dari server
function forceRefreshQuestions(){
  if(!CONFIG.jsonUrl || CONFIG.jsonUrl.trim() === ''){
    alert('URL JSON belum dikonfigurasi di CONFIG.jsonUrl.'); return;
  }
  localStorage.removeItem(QUESTIONS_CACHE_KEY);
  localStorage.removeItem(QUESTIONS_CACHE_TS);
  setLoadingState('🔄 Memperbarui soal dari server...', '');
  document.getElementById('cbt-app').style.display = 'none';
  document.getElementById('result-screen').style.display = 'none';
  clearInterval(timerInterval);
  init();
}

// ─────────────────────────────────────────
// TIMER
// ─────────────────────────────────────────
function pad(n){return String(n).padStart(2,'0')}
function startTimer(){
  clearInterval(timerInterval);
  timeLeft=CONFIG.duration;
  timerInterval=setInterval(()=>{
    timeLeft--;
    const m=Math.floor(timeLeft/60),s=timeLeft%60;
    document.getElementById('timer').textContent=pad(m)+':'+pad(s);
    if(timeLeft<=300) document.getElementById('timer-box').classList.add('danger');
    if(timeLeft<=0){clearInterval(timerInterval);submitTest();}
  },1000);
}

// ─────────────────────────────────────────
// RENDER
// ─────────────────────────────────────────
const SEG_BADGE_STYLES=[
  {bg:'var(--purple-light)',color:'var(--purple-dark)'},
  {bg:'var(--teal-light)',color:'var(--teal-dark)'},
  {bg:'var(--amber-light)',color:'var(--amber-dark)'},
  {bg:'var(--pink-light)',color:'var(--pink-dark)'}
];

function render(){
  const q=questions[cur];
  const seg=getSegment(cur);
  const si=SEGMENTS.indexOf(seg);
  const sStyle=SEG_BADGE_STYLES[si];

  document.getElementById('q-badge').textContent='Soal '+(cur+1);
  document.getElementById('q-progress').textContent='dari '+questions.length+' soal';

  const segBadge=document.getElementById('q-seg-badge');
  segBadge.textContent=seg.icon+' '+seg.short;
  segBadge.style.background=sStyle.bg;
  segBadge.style.color=sStyle.color;

  // Render teks soal — format daftar bernomor (1)(2)(3) jadi vertikal
  const qTextEl = document.getElementById('q-text');
  qTextEl.innerHTML = '';
  const lines = q.text.split('\n');
  lines.forEach((line, li) => {
    const isNumbered = /^\s*\(\d+\)/.test(line);
    const isArrow    = /^\s*\d+\./.test(line);
    if(isNumbered || isArrow){
      const item = document.createElement('div');
      item.style.cssText = 'display:flex;align-items:flex-start;gap:6px;margin:3px 0 3px 8px;font-size:14px;line-height:1.6;color:var(--text)';
      // pisahkan nomor dan teks
      const m = line.match(/^(\s*\(\d+\)|\s*\d+\.)\s*(.*)/);
      if(m){
        const num = document.createElement('span');
        num.textContent = m[1].trim();
        num.style.cssText = 'flex-shrink:0;font-weight:600;min-width:28px;color:var(--purple-dark)';
        const txt = document.createElement('span');
        txt.textContent = m[2];
        item.appendChild(num);
        item.appendChild(txt);
      } else {
        item.textContent = line;
      }
      qTextEl.appendChild(item);
    } else {
      if(line.trim() === '') {
        if(li > 0 && li < lines.length - 1) {
          const sp = document.createElement('div');
          sp.style.height = '4px';
          qTextEl.appendChild(sp);
        }
        return;
      }
      const p = document.createElement('div');
      p.style.cssText = 'margin-bottom:6px;line-height:1.7';
      p.textContent = line;
      qTextEl.appendChild(p);
    }
  });
  // Render gambar soal jika ada
  let imgEl = document.getElementById('q-image-wrap');
  if(imgEl) imgEl.remove();
  if(q.image){
    const wrap = document.createElement('div');
    wrap.id = 'q-image-wrap';
    wrap.style.cssText = 'margin-bottom:14px;text-align:center';
    const img = document.createElement('img');
    img.src = q.image;
    img.alt = q.image_caption || 'Gambar soal';
    img.style.cssText = 'max-width:100%;max-height:280px;border-radius:10px;border:1px solid var(--border);object-fit:contain';
    img.onerror = () => { wrap.style.display='none'; };
    wrap.appendChild(img);
    if(q.image_caption){
      const cap = document.createElement('div');
      cap.textContent = q.image_caption;
      cap.style.cssText = 'font-size:11px;color:var(--text-sec);margin-top:5px;font-style:italic';
      wrap.appendChild(cap);
    }
    qTextEl.after(wrap);
  }
  const opts=document.getElementById('options');
  opts.innerHTML='';
  ['A','B','C','D'].forEach((L,i)=>{
    const d=document.createElement('div');
    d.className='opt'+(answers[cur]===i?' selected':'');
    d.innerHTML='<span class="opt-letter">'+L+'</span><span class="opt-text">'+q.options[i]+'</span>';
    d.onclick=()=>{answers[cur]=i;render();};
    opts.appendChild(d);
  });
  renderSegNav();
  renderStats();
}

function renderSegNav(){
  const container=document.getElementById('seg-nav-container');
  container.innerHTML='';
  SEGMENTS.forEach((seg,si)=>{
    const block=document.createElement('div');
    block.className='seg-nav-block';
    const sStyle=SEG_BADGE_STYLES[si];

    const label=document.createElement('div');
    label.className='seg-nav-label '+seg.cls;
    label.innerHTML='<div class="seg-dot" style="background:'+seg.color+'"></div>'+
      seg.icon+' Seg '+seg.id+' · '+seg.short;
    block.appendChild(label);

    const grid=document.createElement('div');
    grid.className='nav-grid';
    for(let i=seg.start;i<=seg.end;i++){
      const b=document.createElement('button');
      b.className='nav-btn '+seg.btnCls+' '+(answers[i]!==null?'answered':'unanswered')+(i===cur?' current':'');
      b.textContent=i+1;
      b.onclick=(()=>{const idx=i;return()=>{cur=idx;render();};})();
      grid.appendChild(b);
    }
    block.appendChild(grid);
    container.appendChild(block);
  });
}

function renderStats(){
  const done=answers.filter(a=>a!==null).length;
  const pct=Math.round(done/questions.length*100);
  document.getElementById('prog-text').textContent=done+' terjawab';
  document.getElementById('prog-pct').textContent=pct+'%';
  document.getElementById('prog-bar').style.width=pct+'%';
  document.getElementById('stat-ans').textContent=done;
  document.getElementById('stat-skip').textContent=questions.length-done;

  // Per-segment progress
  const sb=document.getElementById('seg-progress-sidebar');
  sb.innerHTML='';
  SEGMENTS.forEach((seg,si)=>{
    const total=seg.end-seg.start+1;
    const answered=answers.slice(seg.start,seg.end+1).filter(a=>a!==null).length;
    const spct=Math.round(answered/total*100);
    const sStyle=SEG_BADGE_STYLES[si];
    sb.innerHTML+=
      '<div class="seg-progress-item">'+
        '<div class="seg-prog-row">'+
          '<span class="seg-prog-name" style="color:'+sStyle.color+'">'+seg.icon+' '+seg.short+'</span>'+
          '<span class="seg-prog-count">'+answered+'/'+total+'</span>'+
        '</div>'+
        '<div class="seg-prog-bar-bg"><div class="seg-prog-bar-fill" style="width:'+spct+'%;background:'+seg.color+'"></div></div>'+
      '</div>';
  });
}

function nextQ(){if(cur<questions.length-1){cur++;render();}}
function prevQ(){if(cur>0){cur--;render();}}

function confirmSubmit(){
  const unanswered=answers.filter(a=>a===null).length;
  if(unanswered>0){
    if(!confirm('Masih ada '+unanswered+' soal belum dijawab. Yakin ingin mengumpulkan?')) return;
  }
  submitTest();
}

// ─────────────────────────────────────────
// SUBMIT
// ─────────────────────────────────────────
function computeSegmentScores(){
  return SEGMENTS.map(seg=>{
    let benar=0,salah=0,skip=0;
    for(let i=seg.start;i<=seg.end;i++){
      if(answers[i]===null) skip++;
      else if(answers[i]===questions[i].answer) benar++;
      else salah++;
    }
    const total=seg.end-seg.start+1;
    return {segId:seg.id,segName:seg.name,segShort:seg.short,segIcon:seg.icon,benar,salah,skip,total,nilai:Math.round(benar/total*100)};
  });
}

function submitTest(){
  clearInterval(timerInterval);
  let benar=0,salah=0,skip=0;
  questions.forEach((q,i)=>{
    if(answers[i]===null) skip++;
    else if(answers[i]===q.answer) benar++;
    else salah++;
  });
  const nilai=Math.round(benar/questions.length*100);
  const timeUsed=CONFIG.duration-timeLeft;
  const segScores=computeSegmentScores();

  document.getElementById('res-score').textContent=nilai;
  document.getElementById('res-benar').textContent=benar;
  document.getElementById('res-salah').textContent=salah;
  document.getElementById('res-skip').textContent=skip;

  // Render segment result cards
  const sgGrid=document.getElementById('seg-result-grid');
  sgGrid.innerHTML='';
  segScores.forEach((sc,si)=>{
    const sStyle=SEG_BADGE_STYLES[si];
    const seg=SEGMENTS[si];
    const card=document.createElement('div');
    card.className='seg-result-card';
    card.style.borderTop='3px solid '+seg.color;
    card.innerHTML=
      '<div class="seg-rc-header">'+
        '<div class="seg-rc-icon" style="background:'+sStyle.bg+'">'+sc.segIcon+'</div>'+
        '<div class="seg-rc-name">'+sc.segName+'</div>'+
      '</div>'+
      '<div class="seg-rc-stats">'+
        '<span class="seg-rc-pill pill-green">✓ '+sc.benar+' benar</span>'+
        '<span class="seg-rc-pill pill-red">✗ '+sc.salah+' salah</span>'+
        '<span class="seg-rc-pill pill-amber">— '+sc.skip+' skip</span>'+
      '</div>'+
      '<div class="seg-rc-score" style="color:'+seg.color+'">'+sc.nilai+' / 100</div>';
    sgGrid.appendChild(card);
  });

  // Review list
  const L=['A','B','C','D'];
  const rl=document.getElementById('review-list');
  rl.innerHTML='';
  questions.forEach((q,i)=>{
    const ua=answers[i];
    const cls=ua===null?'skip':ua===q.answer?'correct':'wrong';
    const seg=getSegment(i);
    const si=SEGMENTS.indexOf(seg);
    const sStyle=SEG_BADGE_STYLES[si];
    const div=document.createElement('div');
    div.className='review-item '+cls;
    let ansHtml='';
    if(ua===null){
      ansHtml='<div class="ri-ans ri-skip-ans">Tidak dijawab</div>';
    } else if(ua===q.answer){
      ansHtml='<div class="ri-ans ri-correct-ans">Jawaban Anda: '+L[ua]+'. '+q.options[ua]+' ✓</div>';
    } else {
      ansHtml='<div class="ri-ans ri-wrong-ans">Jawaban Anda: '+L[ua]+'. '+q.options[ua]+' ✗</div>'
        +'<div class="ri-ans ri-correct-ans">Jawaban benar: '+L[q.answer]+'. '+q.options[q.answer]+'</div>';
    }
    const imgHtml = q.image
      ? '<div style="margin:6px 0;text-align:center"><img src="'+q.image+'" alt="'+(q.image_caption||'')+'" style="max-width:100%;max-height:180px;border-radius:8px;border:1px solid var(--border);object-fit:contain" onerror="this.style.display=&quot;none&quot;"></div>'
      : '';
    div.innerHTML=
      '<span class="ri-seg-tag" style="background:'+sStyle.bg+';color:'+sStyle.color+'">'+seg.icon+' '+seg.short+'</span>'+
      imgHtml+ansHtml+
      '<div class="ri-pembahasan">Pembahasan: '+q.pembahasan+'</div>';

    // Render teks soal dengan format daftar bernomor
    const qLabel = document.createElement('div');
    qLabel.className = 'ri-q';
    const qLines = ('Soal '+(i+1)+': '+q.text).split('\n');
    qLines.forEach(line => {
      const isNumbered = /^\s*\(\d+\)/.test(line);
      if(isNumbered){
        const item = document.createElement('div');
        item.style.cssText = 'display:flex;align-items:flex-start;gap:6px;margin:2px 0 2px 4px;font-size:12px;line-height:1.5';
        const m = line.match(/^(\s*\(\d+\))\s*(.*)/);
        if(m){
          const num = document.createElement('span');
          num.textContent = m[1].trim();
          num.style.cssText = 'flex-shrink:0;font-weight:700;min-width:24px;color:var(--purple-dark)';
          const txt = document.createElement('span');
          txt.textContent = m[2];
          item.appendChild(num); item.appendChild(txt);
        } else { item.textContent = line; }
        qLabel.appendChild(item);
      } else if(line.trim()){
        const p = document.createElement('div');
        p.textContent = line;
        qLabel.appendChild(p);
      }
    });
    div.insertBefore(qLabel, div.children[1]);
    rl.appendChild(div);
  });

  // Simpan riwayat
  saveHistory({
    id:Date.now(),
    date:new Date().toISOString(),
    subject:CONFIG.subject,
    totalQ:questions.length,
    benar,salah,skip,nilai,timeUsed,
    segScores,
    username:currentUser.username,
    userName:currentUser.name,
    snapshot:questions.map((q,i)=>({
      text:q.text,options:q.options,answer:q.answer,
      userAnswer:answers[i],pembahasan:q.pembahasan,
      segId:getSegment(i).id,segShort:getSegment(i).short,segIcon:getSegment(i).icon
    }))
  });

  addLog({action:'Tryout Selesai',nilai,
    detail:benar+' benar, '+salah+' salah, '+skip+' skip · Waktu: '+formatTime(timeUsed)});

  document.getElementById('result-actions').innerHTML=
    '<button class="btn" onclick="showScreen(\'history\')">📋 Lihat Riwayat</button>'+
    '<button class="btn" onclick="showScreen(\'log\')">📊 Log Aktivitas</button>'+
    '<button class="btn btn-blue" onclick="resetTest()">🔄 Ulangi Tryout</button>';

  document.getElementById('cbt-app').style.display='none';
  document.getElementById('result-screen').style.display='block';
}

// ─────────────────────────────────────────
// HISTORY
// ─────────────────────────────────────────
function loadHistory(){try{return JSON.parse(localStorage.getItem(HISTORY_KEY))||[];}catch(e){return[];}}
function saveHistory(r){const h=loadHistory();h.unshift(r);localStorage.setItem(HISTORY_KEY,JSON.stringify(h));}

function deleteHistory(id){
  if(currentUser?.role!=='admin'){alert('Hanya admin yang dapat menghapus riwayat.');return;}
  if(!confirm('Hapus riwayat ini?')) return;
  const h=loadHistory().filter(r=>r.id!==id);
  localStorage.setItem(HISTORY_KEY,JSON.stringify(h));
  addLog({action:'Hapus Riwayat',detail:'ID: '+id});
  renderHistory();
}

function clearAllHistory(){
  if(currentUser?.role!=='admin'){alert('Hanya admin yang dapat menghapus riwayat.');return;}
  if(!confirm('Hapus SEMUA riwayat tryout?')) return;
  localStorage.removeItem(HISTORY_KEY);
  addLog({action:'Hapus Semua Riwayat',detail:'Semua data riwayat dihapus oleh admin'});
  renderHistory();
}

function formatTime(sec){const m=Math.floor(sec/60),s=sec%60;return pad(m)+'m '+pad(s)+'s';}
function formatDate(iso){return new Date(iso).toLocaleString('id-ID',{day:'numeric',month:'short',year:'numeric',hour:'2-digit',minute:'2-digit'});}

function renderHistory(){
  const container=document.getElementById('history-list');
  const isAdminView=currentUser?.role==='admin';
  let hist=loadHistory();
  if(!isAdminView) hist=hist.filter(r=>r.username===currentUser.username);

  if(hist.length===0){
    container.innerHTML='<div class="hi-empty">Belum ada riwayat tryout.<br>Selesaikan tryout untuk menyimpan hasil.</div>';
    return;
  }

  container.innerHTML='';
  hist.forEach(r=>{
    const ringClass=r.nilai>=80?'excellent':r.nilai>=60?'good':'poor';
    const item=document.createElement('div');
    item.className='history-item';

    const deleteBtn=isAdminView
      ?'<button class="btn btn-sm btn-ghost" style="color:var(--red)" onclick="deleteHistory('+r.id+')">Hapus</button>':'' ;
    const userTag=isAdminView&&r.userName
      ?'<div class="hi-user-tag">👤 '+r.userName+' ('+r.username+')</div>':'';

    // Segment breakdown
    let segBreakdown='';
    if(r.segScores && r.segScores.length){
      segBreakdown='<div class="hi-seg-breakdown">';
      r.segScores.forEach((sc,si)=>{
        const seg=SEGMENTS[si]||SEGMENTS[0];
        const scoreColor=sc.nilai>=80?'var(--green)':sc.nilai>=60?'var(--blue)':'var(--red)';
        segBreakdown+=
          '<div class="hi-seg-item">'+
            '<div class="hi-seg-dot" style="background:'+seg.color+'"></div>'+
            '<div class="hi-seg-info">'+
              '<div class="hi-seg-name">'+sc.segIcon+' '+sc.segShort+'</div>'+
              '<div class="hi-seg-score" style="color:'+scoreColor+'">'+sc.benar+'/'+sc.total+' benar ('+sc.nilai+')</div>'+
            '</div>'+
          '</div>';
      });
      segBreakdown+='</div>';
    }

    item.innerHTML=
      '<div class="hi-top">'+
        '<div class="hi-score-ring '+ringClass+'">'+r.nilai+'</div>'+
        '<div class="hi-body">'+
          '<div class="hi-title">Tryout OSN IPS</div>'+
          userTag+
          '<div class="hi-meta">'+formatDate(r.date)+' · '+r.totalQ+' soal · '+formatTime(r.timeUsed)+'</div>'+
          '<div class="hi-pills">'+
            '<span class="pill pill-green">✓ '+r.benar+' benar</span>'+
            '<span class="pill pill-red">✗ '+r.salah+' salah</span>'+
            '<span class="pill pill-amber">— '+r.skip+' skip</span>'+
          '</div>'+
        '</div>'+
        '<div class="hi-actions">'+
          '<button class="btn btn-sm btn-ghost" onclick="viewHistoryDetail('+r.id+')">Detail</button>'+
          '<button class="btn btn-sm btn-ghost" style="color:var(--blue)" onclick="downloadSinglePDF('+r.id+')">📄 PDF</button>'+
          deleteBtn+
        '</div>'+
      '</div>'+
      segBreakdown;
    container.appendChild(item);
  });
}

function viewHistoryDetail(id){
  const record=loadHistory().find(r=>r.id==id);
  if(!record) return;
  if(currentUser.role!=='admin'&&record.username!==currentUser.username){alert('Akses ditolak.');return;}

  document.getElementById('res-score').textContent=record.nilai;
  document.getElementById('res-benar').textContent=record.benar;
  document.getElementById('res-salah').textContent=record.salah;
  document.getElementById('res-skip').textContent=record.skip;

  // Segment cards
  const sgGrid=document.getElementById('seg-result-grid');
  sgGrid.innerHTML='';
  if(record.segScores){
    record.segScores.forEach((sc,si)=>{
      const sStyle=SEG_BADGE_STYLES[si];
      const seg=SEGMENTS[si];
      const card=document.createElement('div');
      card.className='seg-result-card';
      card.style.borderTop='3px solid '+seg.color;
      card.innerHTML=
        '<div class="seg-rc-header">'+
          '<div class="seg-rc-icon" style="background:'+sStyle.bg+'">'+sc.segIcon+'</div>'+
          '<div class="seg-rc-name">'+sc.segName+'</div>'+
        '</div>'+
        '<div class="seg-rc-stats">'+
          '<span class="seg-rc-pill pill-green">✓ '+sc.benar+' benar</span>'+
          '<span class="seg-rc-pill pill-red">✗ '+sc.salah+' salah</span>'+
          '<span class="seg-rc-pill pill-amber">— '+sc.skip+' skip</span>'+
        '</div>'+
        '<div class="seg-rc-score" style="color:'+seg.color+'">'+sc.nilai+' / 100</div>';
      sgGrid.appendChild(card);
    });
  }

  const L=['A','B','C','D'];
  const rl=document.getElementById('review-list');
  rl.innerHTML='';
  record.snapshot.forEach((q,i)=>{
    const ua=q.userAnswer;
    const cls=ua===null?'skip':ua===q.answer?'correct':'wrong';
    const segId=q.segId||'A';
    const si=SEGMENTS.findIndex(s=>s.id===segId);
    const seg=SEGMENTS[Math.max(0,si)];
    const sStyle=SEG_BADGE_STYLES[Math.max(0,si)];
    const div=document.createElement('div');
    div.className='review-item '+cls;
    let ansHtml='';
    if(ua===null) ansHtml='<div class="ri-ans ri-skip-ans">Tidak dijawab</div>';
    else if(ua===q.answer) ansHtml='<div class="ri-ans ri-correct-ans">Jawaban Anda: '+L[ua]+'. '+q.options[ua]+' ✓</div>';
    else ansHtml='<div class="ri-ans ri-wrong-ans">Jawaban Anda: '+L[ua]+'. '+q.options[ua]+' ✗</div>'
      +'<div class="ri-ans ri-correct-ans">Jawaban benar: '+L[q.answer]+'. '+q.options[q.answer]+'</div>';
    div.innerHTML=
      '<span class="ri-seg-tag" style="background:'+sStyle.bg+';color:'+sStyle.color+'">'+(q.segIcon||'📌')+' '+(q.segShort||'Segmen')+'</span>'+
      '<div class="ri-q">Soal '+(i+1)+': '+q.text+'</div>'+ansHtml+
      '<div class="ri-pembahasan">Pembahasan: '+q.pembahasan+'</div>';
    rl.appendChild(div);
  });

  document.getElementById('history-screen').style.display='none';
  document.getElementById('result-screen').style.display='block';
  document.getElementById('result-actions').innerHTML=
    '<button class="btn" onclick="showScreen(\'history\')">← Kembali ke Riwayat</button>'+
    '<button class="btn btn-blue" onclick="resetTest()">🔄 Coba Lagi</button>';
  setActiveNav('history');
}

// ─────────────────────────────────────────
// LOG AKTIVITAS
// ─────────────────────────────────────────
function loadLog(){try{return JSON.parse(localStorage.getItem(LOG_KEY))||[];}catch(e){return[];}}
function addLog(entry){
  const log=loadLog();
  log.unshift({id:Date.now(),timestamp:new Date().toISOString(),username:currentUser?currentUser.username:'-',userName:currentUser?currentUser.name:'-',role:currentUser?currentUser.role:'-',action:entry.action||'-',nilai:entry.nilai!==undefined?entry.nilai:null,detail:entry.detail||'-'});
  if(log.length>200) log.length=200;
  localStorage.setItem(LOG_KEY,JSON.stringify(log));
}
function clearLog(){
  if(currentUser?.role!=='admin'){alert('Hanya admin.');return;}
  if(!confirm('Hapus semua log aktivitas?')) return;
  localStorage.removeItem(LOG_KEY);
  renderLog();
}

function renderLog(){
  const isAdminView=currentUser?.role==='admin';
  let log=loadLog();
  if(!isAdminView) log=log.filter(l=>l.username===currentUser.username);
  document.getElementById('log-th-user').style.display=isAdminView?'':'none';
  const statRow=document.getElementById('log-stat-row');
  const tryoutLogs=log.filter(l=>l.action==='Tryout Selesai');
  const avgNilai=tryoutLogs.length?Math.round(tryoutLogs.reduce((s,l)=>s+l.nilai,0)/tryoutLogs.length):'-';
  const best=tryoutLogs.length?Math.max(...tryoutLogs.map(l=>l.nilai)):'-';
  statRow.innerHTML=
    '<div class="log-stat-card"><div class="lsv">'+log.length+'</div><div class="lsl">Total Log</div></div>'+
    '<div class="log-stat-card"><div class="lsv">'+tryoutLogs.length+'</div><div class="lsl">Tryout Selesai</div></div>'+
    '<div class="log-stat-card"><div class="lsv">'+avgNilai+'</div><div class="lsl">Rata-rata Nilai</div></div>'+
    '<div class="log-stat-card"><div class="lsv">'+best+'</div><div class="lsl">Nilai Terbaik</div></div>';
  const tbody=document.getElementById('log-tbody');
  if(log.length===0){tbody.innerHTML='<tr><td colspan="6" class="log-empty">Belum ada aktivitas tercatat.</td></tr>';return;}
  tbody.innerHTML='';
  log.forEach((l,i)=>{
    const nilaiHtml=l.nilai!==null?'<span class="log-badge '+(l.nilai>=80?'excellent':l.nilai>=60?'good':'poor')+'">'+l.nilai+'</span>':'—';
    const userTd=isAdminView?'<td>'+l.userName+' <span style="color:var(--text-sec);font-size:10px">('+l.username+')</span></td>':'';
    const tr=document.createElement('tr');
    tr.innerHTML='<td style="color:var(--text-sec)">'+(i+1)+'</td><td style="white-space:nowrap">'+formatDate(l.timestamp)+'</td>'+userTd+'<td><strong>'+l.action+'</strong></td><td>'+nilaiHtml+'</td><td style="color:var(--text-sec);font-size:11px">'+l.detail+'</td>';
    tbody.appendChild(tr);
  });
}

// ─────────────────────────────────────────
// PDF — LAPORAN RIWAYAT (tombol di header history)
// ─────────────────────────────────────────
function downloadPDF(){
  const btn=document.querySelector('[onclick="downloadPDF()"]');
  const orig=btn.textContent; btn.textContent='⏳ Memuat...'; btn.disabled=true;
  const hist=loadHistory().filter(r=>currentUser?.role==='admin'||r.username===currentUser.username);
  if(hist.length===0){alert('Belum ada riwayat.');btn.textContent=orig;btn.disabled=false;return;}
  const isAdmin=currentUser?.role==='admin';
  const now=new Date().toLocaleString('id-ID',{day:'numeric',month:'long',year:'numeric',hour:'2-digit',minute:'2-digit'});
  const avgNilai=Math.round(hist.reduce((s,r)=>s+r.nilai,0)/hist.length);
  const best=Math.max(...hist.map(r=>r.nilai));
  const worst=Math.min(...hist.map(r=>r.nilai));

  const segColors=['#534AB7','#1D9E75','#BA7517','#C0367B'];
  const segNames=['Fenomena Alam','Perubahan Sosial','Ekonomi Global','Sejarah Indonesia'];

  const rows=hist.map((r,i)=>{
    const warna=r.nilai>=80?'#27500A':r.nilai>=60?'#633806':'#791F1F';
    const bg=r.nilai>=80?'#EAF3DE':r.nilai>=60?'#FAEEDA':'#FCEBEB';
    const userCol=isAdmin?'<td style="padding:8px 10px;border-bottom:1px solid #eee">'+( r.userName||r.username)+'</td>':'';
    let segCells='';
    if(r.segScores){
      r.segScores.forEach((sc,si)=>{
        const sw=sc.nilai>=80?'#27500A':sc.nilai>=60?'#0C447C':'#791F1F';
        const sb=sc.nilai>=80?'#EAF3DE':sc.nilai>=60?'#E6F1FB':'#FCEBEB';
        segCells+='<td style="padding:8px 10px;border-bottom:1px solid #eee;text-align:center"><span style="background:'+sb+';color:'+sw+';font-size:11px;padding:2px 6px;border-radius:12px">'+sc.benar+'/'+sc.total+'</span></td>';
      });
    } else {
      segCells='<td colspan="4" style="padding:8px 10px;border-bottom:1px solid #eee;color:#999;text-align:center">—</td>';
    }
    return '<tr>'+
      '<td style="padding:8px 10px;border-bottom:1px solid #eee;text-align:center">'+(i+1)+'</td>'+
      userCol+
      '<td style="padding:8px 10px;border-bottom:1px solid #eee">'+formatDate(r.date)+'</td>'+
      '<td style="padding:8px 10px;border-bottom:1px solid #eee;text-align:center"><span style="background:'+bg+';color:'+warna+';font-weight:700;padding:3px 10px;border-radius:20px;font-size:13px">'+r.nilai+'</span></td>'+
      '<td style="padding:8px 10px;border-bottom:1px solid #eee;text-align:center;color:#27500A">✓ '+r.benar+'</td>'+
      '<td style="padding:8px 10px;border-bottom:1px solid #eee;text-align:center;color:#791F1F">✗ '+r.salah+'</td>'+
      '<td style="padding:8px 10px;border-bottom:1px solid #eee;text-align:center;color:#633806">— '+r.skip+'</td>'+
      segCells+
      '<td style="padding:8px 10px;border-bottom:1px solid #eee;text-align:center">'+formatTime(r.timeUsed)+'</td>'+
      '</tr>';
  }).join('');

  const segHeaders=segNames.map((n,i)=>'<th style="padding:9px 8px;text-align:center;background:'+segColors[i]+';font-size:11px">'+n+'</th>').join('');
  const userHeader=isAdmin?'<th style="padding:9px 10px;text-align:left">Siswa</th>':'';

  const html=`<!DOCTYPE html><html><head><meta charset="UTF-8"><title>Laporan Riwayat — OSN IPS Nicky</title>
  <style>body{font-family:'Segoe UI',sans-serif;margin:0;padding:32px;color:#1a1a1a;background:#fff}
  .header{background:linear-gradient(135deg,#26215C,#0C447C);color:#fff;padding:28px 32px;border-radius:12px;margin-bottom:24px}
  .header h1{font-size:22px;margin:0 0 6px}.header p{font-size:12px;opacity:.75;margin:0}
  .stats{display:flex;gap:16px;margin-bottom:24px}.stat-card{flex:1;background:#f5f5f3;border-radius:10px;padding:16px;text-align:center}
  .stat-card .val{font-size:28px;font-weight:700;color:#26215C}.stat-card .lbl{font-size:11px;color:#6b6b6b;margin-top:4px}
  .seg-legend{display:flex;gap:12px;flex-wrap:wrap;margin-bottom:16px;padding:12px 16px;background:#f9f9f7;border-radius:8px}
  .seg-chip{display:inline-flex;align-items:center;gap:6px;font-size:11px;font-weight:600;padding:4px 10px;border-radius:20px;color:#fff}
  table{width:100%;border-collapse:collapse;font-size:12px}thead{background:#26215C;color:#fff}
  th{padding:9px 10px;text-align:left;font-weight:600}tr:nth-child(even) td{background:#fafafa}
  .footer{margin-top:24px;font-size:11px;color:#999;text-align:center}@media print{body{padding:0}}</style>
  </head><body>
  <div class="header"><h1>📋 Laporan Riwayat Latihan OSN IPS Nicky</h1>
  <p>Dicetak: ${now} &nbsp;·&nbsp; ${isAdmin?'Admin — Semua Siswa':'Siswa: '+(currentUser.name)}</p></div>
  <div class="stats">
    <div class="stat-card"><div class="val">${hist.length}</div><div class="lbl">Total Percobaan</div></div>
    <div class="stat-card"><div class="val">${avgNilai}</div><div class="lbl">Rata-rata Nilai</div></div>
    <div class="stat-card"><div class="val">${best}</div><div class="lbl">Nilai Terbaik</div></div>
    <div class="stat-card"><div class="val">${worst}</div><div class="lbl">Nilai Terendah</div></div>
  </div>
  <div class="seg-legend">
    <strong style="font-size:11px;color:#555;margin-right:4px">Segmen:</strong>
    ${segNames.map((n,i)=>'<span class="seg-chip" style="background:'+segColors[i]+'">'+n+'</span>').join('')}
    <span style="font-size:11px;color:#888">(Kolom = Benar/Total per segmen)</span>
  </div>
  <table><thead><tr>
    <th style="padding:9px 10px;text-align:center">#</th>
    ${userHeader}
    <th style="padding:9px 10px">Tanggal</th>
    <th style="padding:9px 10px;text-align:center">Nilai</th>
    <th style="padding:9px 10px;text-align:center">Benar</th>
    <th style="padding:9px 10px;text-align:center">Salah</th>
    <th style="padding:9px 10px;text-align:center">Skip</th>
    ${segHeaders}
    <th style="padding:9px 10px;text-align:center">Waktu</th>
  </tr></thead><tbody>${rows}</tbody></table>
  <div class="footer">Latihan OSN IPS Nicky &mdash; Laporan otomatis</div>
  <script>window.onload=function(){window.print();}<\/script></body></html>`;

  const blob=new Blob([html],{type:'text/html'});
  const url=URL.createObjectURL(blob);
  const win=window.open(url,'_blank');
  if(!win) alert('Popup diblokir. Izinkan popup untuk mengunduh PDF.');
  btn.textContent=orig; btn.disabled=false;
}

// ─────────────────────────────────────────
// PDF — DETAIL SOAL (tombol per item riwayat)
// ─────────────────────────────────────────
function downloadSinglePDF(id){
  const record=loadHistory().find(r=>r.id==id);
  if(!record){alert('Riwayat tidak ditemukan.');return;}
  if(currentUser.role!=='admin'&&record.username!==currentUser.username){alert('Akses ditolak.');return;}

  const L=['A','B','C','D'];
  const segColors=['#534AB7','#1D9E75','#BA7517','#C0367B'];
  const segBgs=['#EEEDFE','#E1F5EE','#FAEEDA','#FCE8F3'];
  const segIds=['A','B','C','D'];
  const now=new Date().toLocaleString('id-ID',{day:'numeric',month:'long',year:'numeric',hour:'2-digit',minute:'2-digit'});

  // Segment summary table
  let segSummaryRows='';
  if(record.segScores){
    record.segScores.forEach((sc,si)=>{
      const bw=sc.nilai>=80?'#27500A':sc.nilai>=60?'#0C447C':'#791F1F';
      const bb=sc.nilai>=80?'#EAF3DE':sc.nilai>=60?'#E6F1FB':'#FCEBEB';
      segSummaryRows+=`<tr>
        <td style="padding:8px 12px;border-bottom:1px solid #eee">
          <span style="display:inline-block;width:10px;height:10px;border-radius:50%;background:${segColors[si]};margin-right:6px;vertical-align:middle"></span>
          ${sc.segIcon} ${sc.segName}
        </td>
        <td style="padding:8px 12px;border-bottom:1px solid #eee;text-align:center;color:#27500A">${sc.benar}</td>
        <td style="padding:8px 12px;border-bottom:1px solid #eee;text-align:center;color:#791F1F">${sc.salah}</td>
        <td style="padding:8px 12px;border-bottom:1px solid #eee;text-align:center;color:#633806">${sc.skip}</td>
        <td style="padding:8px 12px;border-bottom:1px solid #eee;text-align:center">
          <span style="background:${bb};color:${bw};font-weight:700;padding:3px 10px;border-radius:20px">${sc.nilai}</span>
        </td>
      </tr>`;
    });
  }

  // Questions
  let questionsHtml='';
  record.snapshot.forEach((q,i)=>{
    const ua=q.userAnswer;
    const isCorrect=ua!==null&&ua===q.answer;
    const isSkip=ua===null;
    const isWrong=ua!==null&&ua!==q.answer;
    const si=segIds.indexOf(q.segId||'A');
    const sc=Math.max(0,si);
    const borderColor=isCorrect?'#639922':isWrong?'#E24B4A':'#aaa';
    const bgColor=isCorrect?'#EAF3DE':isWrong?'#FCEBEB':'#f5f5f3';
    const statusIcon=isCorrect?'✅':isWrong?'❌':'⬜';

    let answerHtml='';
    if(isSkip){
      answerHtml='<div style="color:#888;font-size:12px;margin-top:6px">Tidak dijawab</div>';
    } else if(isCorrect){
      answerHtml='<div style="color:#27500A;font-size:12px;margin-top:6px">Jawaban Anda: '+L[ua]+'. '+q.options[ua]+' ✓</div>';
    } else {
      answerHtml='<div style="color:#791F1F;font-size:12px;margin-top:6px">Jawaban Anda: '+L[ua]+'. '+q.options[ua]+' ✗</div>'+
        '<div style="color:#27500A;font-size:12px;margin-top:3px">Jawaban benar: '+L[q.answer]+'. '+q.options[q.answer]+'</div>';
    }

    questionsHtml+=`<div style="border:1.5px solid ${borderColor};background:${bgColor};border-radius:10px;padding:14px 16px;margin-bottom:12px;page-break-inside:avoid">
      <div style="display:flex;align-items:center;gap:8px;margin-bottom:8px">
        <span style="background:#26215C;color:#fff;font-size:11px;font-weight:700;padding:3px 8px;border-radius:20px">Soal ${i+1}</span>
        <span style="background:${segBgs[sc]};color:${segColors[sc]};font-size:10px;font-weight:600;padding:2px 8px;border-radius:20px">${(q.segIcon||'📌')} ${(q.segShort||'')}</span>
        <span style="margin-left:auto;font-size:16px">${statusIcon}</span>
      </div>
      <div style="font-size:13px;font-weight:600;color:#1a1a1a;margin-bottom:10px;line-height:1.6">${q.text}</div>
      <div style="font-size:12px;color:#444;margin-bottom:8px">
        ${q.options.map((opt,oi)=>{
          let os='padding:4px 0;';
          if(oi===q.answer) os+='color:#27500A;font-weight:700;';
          else if(oi===ua&&ua!==q.answer) os+='color:#791F1F;text-decoration:line-through;';
          else os+='color:#666;';
          return '<div style="'+os+'">'+L[oi]+'. '+opt+'</div>';
        }).join('')}
      </div>
      ${answerHtml}
      <div style="margin-top:8px;padding:8px 10px;background:rgba(0,0,0,.04);border-radius:7px;font-size:11px;color:#555;line-height:1.5">
        <strong>Pembahasan:</strong> ${q.pembahasan}
      </div>
    </div>`;
  });

  const valW=record.nilai>=80?'#27500A':record.nilai>=60?'#633806':'#791F1F';
  const valBg=record.nilai>=80?'#EAF3DE':record.nilai>=60?'#FAEEDA':'#FCEBEB';

  const html=`<!DOCTYPE html><html><head><meta charset="UTF-8">
  <title>Detail Tryout — ${record.userName||record.username} — ${formatDate(record.date)}</title>
  <style>
    body{font-family:'Segoe UI',sans-serif;margin:0;padding:28px;color:#1a1a1a;background:#fff;font-size:13px}
    h2{margin:0 0 4px;font-size:18px}
    @media print{body{padding:0}.no-print{display:none}h3{page-break-before:auto}}
  </style></head><body>
  <div style="background:linear-gradient(135deg,#26215C,#0C447C);color:#fff;padding:24px 28px;border-radius:12px;margin-bottom:20px">
    <h2>📋 Detail Tryout OSN IPS Nicky</h2>
    <p style="opacity:.75;font-size:11px;margin:4px 0 0">Siswa: ${record.userName||record.username} &nbsp;·&nbsp; Tanggal: ${formatDate(record.date)} &nbsp;·&nbsp; Dicetak: ${now}</p>
  </div>

  <div style="display:flex;gap:12px;margin-bottom:20px;flex-wrap:wrap">
    <div style="flex:1;min-width:100px;background:#f5f5f3;border-radius:10px;padding:14px;text-align:center">
      <div style="font-size:32px;font-weight:700;background:${valBg};color:${valW};width:64px;height:64px;border-radius:50%;display:inline-flex;align-items:center;justify-content:center">${record.nilai}</div>
      <div style="font-size:11px;color:#888;margin-top:4px">NILAI</div>
    </div>
    <div style="flex:1;min-width:80px;background:#EAF3DE;border-radius:10px;padding:14px;text-align:center">
      <div style="font-size:26px;font-weight:700;color:#27500A">${record.benar}</div>
      <div style="font-size:11px;color:#639922">Benar</div>
    </div>
    <div style="flex:1;min-width:80px;background:#FCEBEB;border-radius:10px;padding:14px;text-align:center">
      <div style="font-size:26px;font-weight:700;color:#791F1F">${record.salah}</div>
      <div style="font-size:11px;color:#E24B4A">Salah</div>
    </div>
    <div style="flex:1;min-width:80px;background:#f5f5f3;border-radius:10px;padding:14px;text-align:center">
      <div style="font-size:26px;font-weight:700;color:#888">${record.skip}</div>
      <div style="font-size:11px;color:#aaa">Skip</div>
    </div>
    <div style="flex:1;min-width:80px;background:#EEEDFE;border-radius:10px;padding:14px;text-align:center">
      <div style="font-size:20px;font-weight:700;color:#534AB7">${formatTime(record.timeUsed)}</div>
      <div style="font-size:11px;color:#888">Waktu</div>
    </div>
  </div>

  <h3 style="font-size:14px;font-weight:600;margin:0 0 10px;color:#26215C">📊 Hasil Per Segmen</h3>
  <table style="width:100%;border-collapse:collapse;font-size:12px;margin-bottom:24px">
    <thead style="background:#26215C;color:#fff">
      <tr>
        <th style="padding:9px 12px;text-align:left">Segmen</th>
        <th style="padding:9px 12px;text-align:center">Benar</th>
        <th style="padding:9px 12px;text-align:center">Salah</th>
        <th style="padding:9px 12px;text-align:center">Skip</th>
        <th style="padding:9px 12px;text-align:center">Nilai</th>
      </tr>
    </thead>
    <tbody>${segSummaryRows}</tbody>
  </table>

  <h3 style="font-size:14px;font-weight:600;margin:0 0 12px;color:#26215C">📝 Detail Per Soal</h3>
  ${questionsHtml}
  <div style="margin-top:20px;font-size:11px;color:#999;text-align:center">Latihan OSN IPS Nicky &mdash; Laporan detail tryout</div>
  <script>window.onload=function(){window.print();}<\/script>
  </body></html>`;

  const blob=new Blob([html],{type:'text/html'});
  const url=URL.createObjectURL(blob);
  const win=window.open(url,'_blank');
  if(!win) alert('Popup diblokir. Izinkan popup untuk mengunduh PDF.');
}

// ─────────────────────────────────────────
// SCREEN ROUTING
// ─────────────────────────────────────────
function showScreen(screen){
  document.getElementById('loading-screen').style.display='none';
  document.getElementById('cbt-app').style.display='none';
  document.getElementById('result-screen').style.display='none';
  document.getElementById('history-screen').style.display='none';
  document.getElementById('log-screen').style.display='none';
  setActiveNav(screen);
  if(screen==='tryout'){
    document.getElementById('cbt-app').style.display='block';
  } else if(screen==='history'){
    const isAdmin=currentUser?.role==='admin';
    document.getElementById('admin-clear-btn').style.display=isAdmin?'block':'none';
    document.getElementById('admin-only-notice').style.display=isAdmin?'flex':'none';
    renderHistory();
    document.getElementById('history-screen').style.display='block';
  } else if(screen==='log'){
    renderLog();
    document.getElementById('log-screen').style.display='block';
  }
}

function setActiveNav(screen){
  document.getElementById('nav-tryout').classList.toggle('active',screen==='tryout');
  document.getElementById('nav-history').classList.toggle('active',screen==='history');
  document.getElementById('nav-log').classList.toggle('active',screen==='log');
}

function resetTest(){
  answers=new Array(questions.length).fill(null);
  cur=0; timeLeft=CONFIG.duration;
  document.getElementById('timer').textContent=pad(Math.floor(CONFIG.duration/60))+':00';
  document.getElementById('timer-box').classList.remove('danger');
  document.getElementById('result-screen').style.display='none';
  document.getElementById('loading-screen').style.display='none';
  addLog({action:'Mulai Tryout',detail:'Memulai sesi tryout baru'});
  showScreen('tryout');
  render();
  startTimer();
}

// ─────────────────────────────────────────
// BOOTSTRAP
// ─────────────────────────────────────────
document.addEventListener('keydown',e=>{
  if(e.key==='Enter'&&document.getElementById('login-screen').style.display!=='none') doLogin(activeTab);
});
if(restoreSession()) startApp();
</script>
</body>
</html>
