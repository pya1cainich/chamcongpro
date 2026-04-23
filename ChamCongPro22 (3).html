<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
<meta name="mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#0D9E75">
<title>Chấm Công Pro</title>
<link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800;900&family=Quicksand:wght@500;600;700&display=swap" rel="stylesheet">
<style>
:root{
  --ac:#0D9E75;--ac2:#0a7d5c;--ac-lt:#E0F5EE;
  --red:#E8433A;--blue:#2D7DD2;--orange:#F5A623;--purple:#7B5EA7;
  --bg:#F4F7F6;--card:#ffffff;--text:#1A2332;--text2:#6B7B8D;--text3:#A0ADB8;
  --border:#E8ECF0;--shadow:0 4px 20px rgba(0,0,0,.08);
  --r:16px;--r-lg:24px;
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
body{font-family:'Nunito',sans-serif;background:var(--bg);color:var(--text);min-height:100vh;display:flex;justify-content:center}
.app{width:100%;max-width:420px;min-height:100vh;background:var(--bg);position:relative;overflow:hidden}

/* ========== RGB ANIMATION ========== */
@keyframes rgb{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}
.rgb-text{background:linear-gradient(90deg,#FF0080,#FF8C00,#40E0D0,#7B2FBE,#FF0080);background-size:300% auto;-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;animation:rgb 4s linear infinite}

/* ========== SCREENS ========== */
.screen{display:none;flex-direction:column;min-height:100vh}
.screen.active{display:flex}

/* ========== ONBOARDING ========== */
.ob-wrap{flex:1;display:flex;flex-direction:column}
.ob-header{padding:20px 20px 0;display:flex;align-items:center;justify-content:space-between}
.ob-logo{font-family:'Quicksand',sans-serif;font-weight:700;font-size:20px}
.ob-skip{font-size:13px;color:var(--text3);cursor:pointer;padding:6px 12px;border:1px solid var(--border);border-radius:20px;background:white}
.ob-progress{display:flex;gap:6px;padding:16px 20px 0}
.ob-dot{flex:1;height:4px;border-radius:2px;background:var(--border);transition:background .3s}
.ob-dot.done{background:var(--ac)}
.ob-dot.active{background:var(--ac);opacity:.6}
.ob-body{flex:1;padding:20px;display:flex;flex-direction:column;gap:16px;overflow-y:auto}
.ob-title{font-size:26px;font-weight:900;line-height:1.2;color:var(--text)}
.ob-sub{font-size:14px;color:var(--text2);line-height:1.6}
.ob-footer{padding:20px;display:flex;gap:10px}
.ob-btn-back{flex:0 0 auto;width:52px;height:52px;border-radius:50%;border:1.5px solid var(--border);background:white;display:flex;align-items:center;justify-content:center;cursor:pointer;font-size:20px}
.ob-btn-next{flex:1;height:52px;border-radius:26px;background:var(--ac);border:none;color:white;font-size:16px;font-weight:800;cursor:pointer;font-family:'Nunito',sans-serif;transition:all .2s;box-shadow:0 8px 24px rgba(13,158,117,.35)}
.ob-btn-next:active{transform:scale(.97)}

/* ========== LANG/COUNTRY GRID ========== */
.lang-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
.lang-item{border:2px solid var(--border);border-radius:14px;padding:14px 8px;text-align:center;cursor:pointer;background:white;transition:all .15s}
.lang-item.sel{border-color:var(--ac);background:var(--ac-lt)}
.lang-item .flag{font-size:28px;display:block;margin-bottom:4px}
.lang-item .lname{font-size:12px;font-weight:700;color:var(--text2)}
.lang-item.sel .lname{color:var(--ac2)}

.country-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:10px}
.country-item{border:2px solid var(--border);border-radius:14px;padding:12px;display:flex;align-items:center;gap:10px;cursor:pointer;background:white;transition:all .15s}
.country-item.sel{border-color:var(--ac);background:var(--ac-lt)}
.country-item .cflag{font-size:24px}
.country-item .cname{font-size:13px;font-weight:700;color:var(--text)}
.country-item .crule{font-size:10px;color:var(--text3);margin-top:1px}

/* ========== FORM FIELDS ========== */
.field-group{display:flex;flex-direction:column;gap:12px}
.field-label{font-size:12px;font-weight:700;color:var(--text2);text-transform:uppercase;letter-spacing:.06em;margin-bottom:4px}
.field-input{width:100%;border:2px solid var(--border);border-radius:12px;padding:14px 16px;font-size:15px;font-family:'Nunito',sans-serif;color:var(--text);background:white;outline:none;transition:border .2s}
.field-input:focus{border-color:var(--ac)}
.field-input::placeholder{color:var(--text3)}

/* ========== SHIFT SELECTORS ========== */
.num-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px}
.num-btn{border:2px solid var(--border);border-radius:12px;padding:14px 0;text-align:center;font-size:18px;font-weight:800;cursor:pointer;background:white;color:var(--text);transition:all .15s;font-family:'Nunito',sans-serif}
.num-btn.sel{border-color:var(--ac);background:var(--ac);color:white}
.week-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:16px}
.week-btn{border:2px solid var(--border);border-radius:12px;padding:10px 0;text-align:center;font-size:13px;font-weight:700;cursor:pointer;background:white;color:var(--text);transition:all .15s;font-family:'Nunito',sans-serif}
.week-btn.sel{border-color:var(--blue);background:var(--blue);color:white}
.shift-card{border:2px solid var(--border);border-radius:14px;padding:14px;background:white;margin-bottom:10px}
.shift-card-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:10px}
.shift-label{font-size:14px;font-weight:700;color:var(--text)}
.shift-night{font-size:11px;padding:3px 8px;border-radius:10px;background:#EEF;color:#534AB7;font-weight:700}
.time-row{display:flex;gap:8px;align-items:center}
.time-inp{flex:1;border:1.5px solid var(--border);border-radius:10px;padding:8px 10px;font-size:15px;font-weight:700;text-align:center;font-family:'Nunito',sans-serif;color:var(--text);background:white;outline:none}
.time-inp:focus{border-color:var(--ac)}
.time-sep{color:var(--text3);font-size:18px;font-weight:700}

/* ========== HOME SCREEN ========== */
.home-header{background:linear-gradient(135deg,#0D9E75 0%,#0a7d5c 50%,#085C42 100%);padding:20px 16px 80px;position:relative;overflow:hidden}
.home-header::before{content:'';position:absolute;top:-30px;right:-30px;width:180px;height:180px;border-radius:50%;background:rgba(255,255,255,.07)}
.home-header::after{content:'';position:absolute;bottom:-50px;left:-20px;width:140px;height:140px;border-radius:50%;background:rgba(255,255,255,.05)}
.home-top{display:flex;align-items:center;justify-content:space-between;position:relative;z-index:1}
.user-info{display:flex;align-items:center;gap:10px}
.user-avatar{width:44px;height:44px;border-radius:50%;background:rgba(255,255,255,.25);border:2px solid rgba(255,255,255,.5);overflow:hidden;display:flex;align-items:center;justify-content:center;font-size:18px;font-weight:800;color:white;cursor:pointer;flex-shrink:0}
.user-avatar img{width:100%;height:100%;object-fit:cover}
.user-text .uname{font-size:15px;font-weight:800;color:white}
.user-text .ujob{font-size:11px;color:rgba(255,255,255,.75)}
.app-title-wrap{display:flex;align-items:center;gap:10px}
.app-title{font-family:'Quicksand',sans-serif;font-size:20px;font-weight:700;letter-spacing:.5px}
.notif-btn{width:40px;height:40px;border-radius:50%;background:rgba(255,255,255,.15);border:1.5px solid rgba(255,255,255,.3);display:flex;align-items:center;justify-content:center;cursor:pointer;position:relative;flex-shrink:0}
.notif-dot{position:absolute;top:6px;right:6px;width:8px;height:8px;border-radius:50%;background:#FF4757;border:2px solid white}
.date-time-card{margin:0 16px;margin-top:-54px;background:white;border-radius:20px;padding:16px 20px;box-shadow:var(--shadow);position:relative;z-index:2;display:flex;justify-content:space-between;align-items:center}
.dt-left .dt-time{font-size:32px;font-weight:900;color:var(--text);line-height:1}
.dt-left .dt-date{font-size:13px;color:var(--text2);margin-top:4px}
.dt-right{text-align:right}
.dt-right .dt-day{font-size:18px;font-weight:800;color:var(--ac)}
.dt-right .dt-month{font-size:12px;color:var(--text3)}

/* ========== FUNCTION BUTTONS ========== */
.func-section{padding:16px 16px 0}
.func-title{font-size:12px;font-weight:700;color:var(--text3);text-transform:uppercase;letter-spacing:.06em;margin-bottom:12px}
.func-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:16px}
.func-item{display:flex;flex-direction:column;align-items:center;gap:6px;cursor:pointer}
.func-circle{width:60px;height:60px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:24px;position:relative;transition:all .2s;box-shadow:0 4px 14px rgba(0,0,0,.12)}
.func-circle:active{transform:scale(.92)}
@keyframes glow{0%,100%{box-shadow:0 4px 14px rgba(0,0,0,.12),0 0 0 0 transparent}50%{box-shadow:0 4px 14px rgba(0,0,0,.12),0 0 20px 6px rgba(255,255,255,.4)}}
.func-circle.glowing{animation:glow 1.5s ease infinite}
.func-label{font-size:10px;font-weight:700;color:var(--text2);text-align:center;line-height:1.3}

/* Attendance big buttons */
.att-row{display:flex;gap:12px;padding:0 16px 16px}
.att-btn{flex:1;border:none;border-radius:20px;padding:18px 12px;display:flex;flex-direction:column;align-items:center;gap:6px;cursor:pointer;font-family:'Nunito',sans-serif;transition:all .2s;position:relative;overflow:hidden}
.att-btn::before{content:'';position:absolute;inset:0;opacity:0;transition:opacity .2s;background:rgba(255,255,255,.15)}
.att-btn:active::before{opacity:1}
.att-btn:active{transform:scale(.97)}
.att-btn.in{background:linear-gradient(135deg,#2D7DD2,#1a5fa8);box-shadow:0 8px 24px rgba(45,125,210,.4)}
.att-btn.out{background:linear-gradient(135deg,#E8433A,#c42d25);box-shadow:0 8px 24px rgba(232,67,58,.4)}
.att-btn .att-icon{font-size:28px}
.att-btn .att-label{font-size:13px;font-weight:800;color:white}
.att-btn .att-sub{font-size:10px;color:rgba(255,255,255,.8)}

/* ========== WORK METER ========== */
.meter-card{margin:0 16px 16px;background:white;border-radius:var(--r);padding:16px;box-shadow:0 2px 12px rgba(0,0,0,.06)}
.meter-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px}
.meter-ttl{font-size:13px;font-weight:700;color:var(--text2)}
.meter-val{font-size:18px;font-weight:900;color:var(--text)}
.meter-badge{font-size:11px;padding:3px 10px;border-radius:10px;font-weight:700}
.meter-track{height:10px;background:#F0F0F0;border-radius:5px;overflow:hidden;margin-bottom:8px}
.meter-fill{height:100%;border-radius:5px;transition:width .6s cubic-bezier(.4,0,.2,1)}
.meter-marks{display:flex;justify-content:space-between;font-size:10px;color:var(--text3)}

/* ========== STATS ROW ========== */
.stats-row{display:flex;gap:10px;padding:0 16px 16px}
.stat-card{flex:1;background:white;border-radius:14px;padding:12px;text-align:center;box-shadow:0 2px 10px rgba(0,0,0,.05)}
.stat-num{font-size:22px;font-weight:900}
.stat-lbl{font-size:10px;color:var(--text3);font-weight:600;margin-top:2px}

/* ========== CALENDAR MINI ========== */
.cal-card{margin:0 16px 16px;background:white;border-radius:var(--r);padding:16px;box-shadow:0 2px 12px rgba(0,0,0,.06)}
.cal-nav{display:flex;align-items:center;justify-content:space-between;margin-bottom:12px}
.cal-nav-btn{width:32px;height:32px;border-radius:50%;border:1.5px solid var(--border);background:white;display:flex;align-items:center;justify-content:center;cursor:pointer;font-size:16px;font-weight:700;color:var(--text2)}
.cal-month{font-size:15px;font-weight:800;color:var(--text)}
.cal-dow{display:grid;grid-template-columns:repeat(7,1fr);margin-bottom:6px}
.cal-dow span{text-align:center;font-size:11px;font-weight:700;color:var(--text3);padding:4px 0}
.cal-dow .sun{color:#E8433A}.cal-dow .sat{color:var(--blue)}
.cal-days{display:grid;grid-template-columns:repeat(7,1fr);gap:3px}
.cal-day{aspect-ratio:1;border-radius:8px;display:flex;flex-direction:column;align-items:center;justify-content:center;font-size:12px;font-weight:700;cursor:pointer;position:relative;transition:all .12s}
.cal-day.empty{pointer-events:none}
.cal-day.today{background:var(--ac)!important;color:white!important}
.cal-day.cm{background:#E0F5EE;color:var(--ac2)}
.cal-day.vang{background:#FFF0EF;color:#E8433A}
.cal-day.np{background:#FFF8E8;color:#F5A623}
.cal-day.ll{background:#EEF4FF;color:var(--blue)}
.cal-day.ct{background:#F8F9FA;color:var(--text3)}.cal-day.le{background:#FFF0EF;color:#E8433A}
.cal-day.sun{color:#E8433A}.cal-day.sat{color:var(--blue)}
.cal-day .day-dot{width:4px;height:4px;border-radius:50%;background:currentColor;position:absolute;bottom:3px;opacity:.6}

/* ========== BOTTOM NAV ========== */
.bottom-nav{position:sticky;bottom:0;background:white;border-top:1px solid var(--border);display:flex;align-items:center;justify-content:space-around;padding:8px 0 max(8px,env(safe-area-inset-bottom));z-index:10}
.nav-item{display:flex;flex-direction:column;align-items:center;gap:3px;padding:6px 16px;cursor:pointer;border-radius:12px;transition:all .15s}
.nav-item.active .nav-icon{color:var(--ac)}
.nav-item.active .nav-lbl{color:var(--ac);font-weight:700}
.nav-icon{font-size:22px;color:var(--text3);transition:color .15s}
.nav-lbl{font-size:10px;font-weight:600;color:var(--text3);transition:color .15s}
.home-nav-btn{width:56px;height:56px;border-radius:50%;background:var(--ac);border:none;display:flex;align-items:center;justify-content:center;font-size:26px;cursor:pointer;box-shadow:0 6px 20px rgba(13,158,117,.4);margin-top:-16px;transition:all .2s}
.home-nav-btn:active{transform:scale(.93)}

/* ========== PANELS ========== */
.panel-overlay{display:none;position:fixed;inset:0;background:rgba(0,0,0,.4);z-index:50;align-items:flex-end;justify-content:center}
.panel-overlay.open{display:flex}
.panel-sheet{background:white;border-radius:24px 24px 0 0;width:100%;max-width:420px;max-height:90vh;overflow-y:auto;padding:0 0 32px}
.panel-handle{width:40px;height:4px;border-radius:2px;background:var(--border);margin:12px auto 0}
.panel-head{display:flex;align-items:center;justify-content:space-between;padding:16px 20px;border-bottom:1px solid var(--border)}
.panel-title{font-size:17px;font-weight:800}
.panel-close{width:32px;height:32px;border-radius:50%;background:var(--bg);border:none;cursor:pointer;font-size:18px;display:flex;align-items:center;justify-content:center;color:var(--text2)}
.panel-body{padding:16px 20px}

/* ========== APPEARANCE PANEL ========== */
.color-grid{display:flex;gap:10px;flex-wrap:wrap;margin-bottom:16px}
.color-dot{width:44px;height:44px;border-radius:50%;cursor:pointer;border:3px solid transparent;transition:all .15s;position:relative}
.color-dot.sel{border-color:var(--text);transform:scale(1.12)}
.color-dot::after{content:'✓';position:absolute;inset:0;display:flex;align-items:center;justify-content:center;color:white;font-size:16px;font-weight:900;opacity:0}
.color-dot.sel::after{opacity:1}
.ap-section-title{font-size:13px;font-weight:700;color:var(--text2);text-transform:uppercase;letter-spacing:.05em;margin-bottom:10px}
.avatar-picker{display:flex;align-items:center;gap:14px;padding:14px;background:var(--bg);border-radius:14px;margin-bottom:16px}
.avatar-preview{width:64px;height:64px;border-radius:50%;background:var(--ac-lt);display:flex;align-items:center;justify-content:center;font-size:28px;overflow:hidden;border:3px solid var(--ac);flex-shrink:0}
.avatar-preview img{width:100%;height:100%;object-fit:cover}
.upload-btn{padding:10px 16px;background:white;border:1.5px solid var(--border);border-radius:10px;font-size:13px;font-weight:700;cursor:pointer;color:var(--text);font-family:'Nunito',sans-serif}

/* ========== NOTIF SETTINGS ========== */
.notif-row{display:flex;justify-content:space-between;align-items:center;padding:14px 0;border-bottom:1px solid var(--border)}
.notif-row:last-child{border-bottom:none}
.notif-info .notif-name{font-size:14px;font-weight:700;color:var(--text)}
.notif-info .notif-desc{font-size:12px;color:var(--text3);margin-top:2px}
.toggle-sw{width:48px;height:28px;border-radius:14px;background:var(--border);position:relative;cursor:pointer;transition:background .2s;border:none;flex-shrink:0}
.toggle-sw.on{background:var(--ac)}
.toggle-sw::after{content:'';position:absolute;width:22px;height:22px;border-radius:50%;background:white;top:3px;left:3px;transition:left .2s;box-shadow:0 2px 4px rgba(0,0,0,.2)}
.toggle-sw.on::after{left:23px}

/* ========== SETTINGS SCREEN ========== */
.settings-list{padding:0 16px}
.settings-item{display:flex;align-items:center;gap:14px;padding:16px 16px;background:white;border-radius:14px;margin-bottom:10px;cursor:pointer;box-shadow:0 2px 8px rgba(0,0,0,.04)}
.si-icon{width:44px;height:44px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:22px;flex-shrink:0}
.si-body{flex:1}
.si-name{font-size:14px;font-weight:700;color:var(--text)}
.si-sub{font-size:12px;color:var(--text3);margin-top:2px}
.si-arrow{font-size:16px;color:var(--text3)}

/* ========== CALENDAR SCREEN ========== */
.cal-screen-header{background:linear-gradient(135deg,#2D7DD2,#1a5fa8);padding:20px 16px 70px;position:relative}
.cal-screen-title{font-size:22px;font-weight:900;color:white;margin-bottom:4px}
.cal-screen-sub{font-size:13px;color:rgba(255,255,255,.75)}
.cal-big-card{margin:0 16px;margin-top:-54px;background:white;border-radius:20px;padding:16px;box-shadow:var(--shadow);position:relative;z-index:2}

/* ========== ANIMATIONS ========== */
@keyframes fadeUp{from{opacity:0;transform:translateY(16px)}to{opacity:1;transform:translateY(0)}}
@keyframes popIn{from{opacity:0;transform:scale(.85)}to{opacity:1;transform:scale(1)}}
.fade-up{animation:fadeUp .35s ease both}
.pop-in{animation:popIn .3s cubic-bezier(.34,1.56,.64,1) both}

/* ========== CHECKIN ANIM ========== */
@keyframes ripple{0%{transform:scale(1);opacity:.6}100%{transform:scale(2.5);opacity:0}}
.ripple-wrap{position:absolute;inset:0;border-radius:inherit;overflow:hidden;pointer-events:none}
.ripple-circle{position:absolute;top:50%;left:50%;width:60px;height:60px;margin:-30px 0 0 -30px;border-radius:50%;background:white;animation:ripple .6s ease-out}

/* ========== EXCEL PREVIEW ========== */
.excel-preview{border:1.5px solid var(--border);border-radius:12px;overflow:hidden;margin-bottom:16px}
.excel-row{display:flex;border-bottom:1px solid var(--border)}
.excel-row:last-child{border-bottom:none}
.excel-row.head{background:#217346}
.excel-cell{flex:1;padding:8px 10px;font-size:12px;font-weight:600;color:var(--text);border-right:1px solid var(--border)}
.excel-cell:last-child{border-right:none}
.excel-row.head .excel-cell{color:white}
.excel-cell.cm{color:var(--ac2);background:var(--ac-lt)}
.excel-cell.vg{color:#E8433A;background:#FFF0EF}
.export-btn{width:100%;padding:16px;border-radius:14px;background:#217346;border:none;color:white;font-size:15px;font-weight:800;cursor:pointer;font-family:'Nunito',sans-serif;display:flex;align-items:center;justify-content:center;gap:8px}

/* ========== CHECKIN STATUS PILL ========== */
.status-pill{display:inline-flex;align-items:center;gap:6px;padding:6px 14px;border-radius:20px;font-size:12px;font-weight:700;margin-top:8px}
.status-pill.in{background:#E0F5EE;color:var(--ac2)}
.status-pill.out{background:#FFF0EF;color:#E8433A}
.status-pill.none{background:#F0F0F0;color:var(--text3)}

/* Misc */
.section-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px}
.see-all{font-size:12px;color:var(--ac);font-weight:700;cursor:pointer}
.chip{display:inline-flex;align-items:center;gap:4px;padding:4px 10px;border-radius:10px;font-size:11px;font-weight:700}
.empty-state{text-align:center;padding:32px 20px;color:var(--text3)}
.empty-icon{font-size:48px;margin-bottom:8px}
.empty-txt{font-size:14px}
.salary-card{margin:0 16px 16px;background:linear-gradient(135deg,#7B5EA7,#5a3e8a);border-radius:var(--r);padding:20px;box-shadow:0 8px 24px rgba(123,94,167,.3)}
.salary-lbl{font-size:12px;color:rgba(255,255,255,.75);font-weight:600;margin-bottom:4px}
.salary-amount{font-size:28px;font-weight:900;color:white}
.salary-detail{font-size:11px;color:rgba(255,255,255,.6);margin-top:6px}

/* SPLASH SCREEN */
@keyframes pop-in{from{opacity:0;transform:scale(.86) translateY(14px)}to{opacity:1;transform:scale(1) translateY(0)}}
@keyframes burst{0%{opacity:0;transform:scale(0)}25%{opacity:1}100%{opacity:0;transform:scale(1)}}
.splash-ov{display:none;position:fixed;inset:0;background:rgba(0,0,0,.28);z-index:999;align-items:center;justify-content:center;padding:24px}
.splash-ov.mo{display:flex}
.splash-box{background:white;border-radius:24px;border:1px solid var(--border);padding:28px 22px 22px;width:100%;max-width:320px;position:relative;text-align:center;animation:pop-in .38s cubic-bezier(.34,1.56,.64,1) both}
.sp-pf{position:absolute;pointer-events:none}
.sp-icon{width:56px;height:56px;border-radius:16px;display:flex;align-items:center;justify-content:center;margin:0 auto 14px;background:var(--ac-lt)}
.sp-badge{display:inline-flex;align-items:center;gap:6px;border-radius:20px;padding:4px 13px 4px 9px;margin-bottom:12px;background:var(--ac-lt)}
.sp-dot{width:8px;height:8px;border-radius:50%;background:var(--ac)}
.sp-badge-txt{font-size:12px;font-weight:700;color:var(--ac2)}
.sp-so{font-size:42px;font-weight:900;line-height:1;margin-bottom:4px;color:var(--ac)}
.sp-dv{font-size:13px;color:var(--text2);margin-bottom:14px}
.sp-cau{font-size:15px;font-weight:600;color:var(--text);line-height:1.5;margin-bottom:20px}
.sp-nut{width:100%;padding:15px;border-radius:14px;border:none;font-size:15px;font-weight:800;cursor:pointer;color:white;font-family:Nunito,sans-serif;background:var(--ac)}
.pf-bc{animation:burst 1.4s ease-out both}
</style>
</head>
<body>
<div class="app" id="mainApp">

<!-- ===================== ONBOARDING ===================== -->
<div class="screen active" id="screenOB">
  <div class="ob-wrap">
    <div class="ob-header">
      <div class="ob-logo">
        <span class="rgb-text" id="obAppName">Chấm Công Pro</span>
      </div>
      <div class="ob-skip" id="obSkipBtn" onclick="skipOB()">Bỏ qua</div>
    </div>
    <div class="ob-progress" id="obProgress">
      <div class="ob-dot active"></div>
      <div class="ob-dot"></div>
      <div class="ob-dot"></div>
      <div class="ob-dot"></div>
    </div>
    <div class="ob-body" id="obBody">
      <!-- Filled by JS -->
    </div>
    <div class="ob-footer">
      <div class="ob-btn-back" id="obBtnBack" onclick="obBack()">←</div>
      <button class="ob-btn-next" id="obBtnNext" onclick="obNext()">Tiếp theo →</button>
    </div>
  </div>
</div>

<!-- ===================== HOME SCREEN ===================== -->
<div class="screen" id="screenHome">
  <!-- Header -->
  <div class="home-header">
    <div class="home-top">
      <div class="user-info">
        <div class="user-avatar" id="homeAvt" onclick="openPanel('panelAppearance')">👤</div>
        <div class="user-text">
          <div class="uname" id="homeUname">Người dùng</div>
          <div class="ujob" id="homeUjob">Nhân viên</div>
        </div>
      </div>
      <div class="app-title-wrap">
        <div class="app-title rgb-text" id="homeAppTitle">Chấm Công Pro</div>
        <div class="notif-btn" onclick="openPanel('panelNotif')">
          🔔<div class="notif-dot" id="notifDot"></div>
        </div>
      </div>
    </div>
  </div>

  <!-- Date-time card -->
  <div class="date-time-card fade-up" id="dtCard">
    <div class="dt-left">
      <div class="dt-time" id="clockTime">00:00</div>
      <div class="dt-date" id="clockDate">Thứ 2, 01/01/2025</div>
    </div>
    <div class="dt-right">
      <div class="dt-day" id="clockDay">1</div>
      <div class="dt-month" id="clockMonth">Tháng 1, 2025</div>
      <div class="status-pill none" id="todayStatus">Chưa chấm công</div>
    </div>
  </div>

  <!-- Big checkin buttons -->
  <div class="att-row fade-up" style="animation-delay:.1s">
    <button class="att-btn in" onclick="doCheckin()">
      <div class="ripple-wrap" id="rippleIn"></div>
      <div class="att-icon">▶️</div>
      <div class="att-label" id="lblVaoCA">VÀO CA</div>
      <div class="att-sub" id="lastIn">Nhấn để bắt đầu ca</div>
    </button>
    <button class="att-btn out" onclick="doCheckout()">
      <div class="ripple-wrap" id="rippleOut"></div>
      <div class="att-icon">⏹️</div>
      <div class="att-label" id="lblHetCA">HẾT CA</div>
      <div class="att-sub" id="lastOut">Nhấn khi kết thúc ca</div>
    </button>
  </div>

  <!-- Work meter -->
  <div class="meter-card fade-up" style="animation-delay:.15s">
    <div class="meter-head">
      <span class="meter-ttl" id="meterTitle">Giờ làm tháng này</span>
      <div style="display:flex;align-items:center;gap:8px">
        <span class="meter-val" id="meterHours">0h</span>
        <span class="meter-badge" id="meterBadge" style="background:#E0F5EE;color:#0a7d5c">Bình thường</span>
      </div>
    </div>
    <div class="meter-track">
      <div class="meter-fill" id="meterFill" style="width:2%;background:linear-gradient(90deg,#0D9E75,#40E0D0)"></div>
    </div>
    <div class="meter-marks">
      <span>0h</span><span style="color:#0D9E75" id="meterMark1">176h ✓</span><span style="color:#F5A623" id="meterMark2">220h ⚡</span><span style="color:#E8433A" id="meterMark3">260h+ 🔥</span>
    </div>
  </div>

  <!-- Stats -->
  <div class="stats-row fade-up" style="animation-delay:.2s">
    <div class="stat-card">
      <div class="stat-num" style="color:#0D9E75" id="statCM">0</div>
      <div class="stat-lbl" id="lblCM">Có mặt</div>
    </div>
    <div class="stat-card">
      <div class="stat-num" style="color:#E8433A" id="statV">0</div>
      <div class="stat-lbl" id="lblV">Vắng</div>
    </div>
    <div class="stat-card">
      <div class="stat-num" style="color:#F5A623" id="statNP">0</div>
      <div class="stat-lbl" id="lblNP">Nghỉ phép</div>
    </div>
    <div class="stat-card">
      <div class="stat-num" style="color:#7B5EA7" id="statOT">0h</div>
      <div class="stat-lbl" id="lblOT">Tăng ca</div>
    </div>
  </div>

  <!-- Function buttons -->
  <div class="func-section fade-up" style="animation-delay:.25s">
    <div class="func-title" id="lblFuncTitle">Chức năng</div>
    <div class="func-grid">
      <div class="func-item" onclick="goScreen('screenCal')">
        <div class="func-circle" style="background:#EEF4FF;color:#2D7DD2">📅</div>
        <div class="func-label" id="flLich">Lịch</div>
      </div>
      <div class="func-item" onclick="openPanel('panelSetup')">
        <div class="func-circle" style="background:#FFF0EF;color:#E8433A">📝</div>
        <div class="func-label" id="flThietLap">Thiết lập</div>
      </div>
      <div class="func-item" onclick="openPanel('panelAppearance')">
        <div class="func-circle" style="background:#FFFBE8;color:#F5A623">⭐</div>
        <div class="func-label" id="flGiaoDien">Giao diện</div>
      </div>
      <div class="func-item" onclick="goScreen('screenSettings')">
        <div class="func-circle" style="background:#F5F0FF;color:#7B5EA7">⚙️</div>
        <div class="func-label" id="flCaiDat">Cài đặt</div>
      </div>
      <div class="func-item" onclick="openPanel('panelSalary')">
        <div class="func-circle" style="background:#E0F5EE;color:#0D9E75">💰</div>
        <div class="func-label" id="flLuong">Lương</div>
      </div>
      <div class="func-item" onclick="openPanel('panelExcel')">
        <div class="func-circle" style="background:#E8F5E9;color:#217346">📊</div>
        <div class="func-label" id="flExcel">Xuất Excel</div>
      </div>
      <div class="func-item" onclick="openPanel('panelNotif')">
        <div class="func-circle" style="background:#FFF8E8;color:#F5A623">🔔</div>
        <div class="func-label" id="flThongBao">Thông báo</div>
      </div>
      <div class="func-item" onclick="openPanel('panelHelp')">
        <div class="func-circle" style="background:#F0F0F0;color:#6B7B8D">❓</div>
        <div class="func-label" id="flHuongDan">Hướng dẫn</div>
      </div>
    </div>
  </div>

  <!-- Salary card -->
  <div class="salary-card fade-up" style="animation-delay:.3s" id="salaryCard">
    <div class="salary-lbl" id="lblSalaryCard">💼 Lương ước tính tháng này</div>
    <div class="salary-amount" id="salaryAmount">0 ₫</div>
    <div class="salary-detail" id="salaryDetail">Nhập thông tin lương để tính tự động</div>
  </div>

  <!-- Bottom nav -->
  <div class="bottom-nav">
    <div class="nav-item active" onclick="goScreen('screenHome')">
      <div class="nav-icon">🏠</div>
      <div class="nav-lbl">Trang chủ</div>
    </div>
    <div class="nav-item" onclick="goScreen('screenCal')">
      <div class="nav-icon">📅</div>
      <div class="nav-lbl">Lịch</div>
    </div>
    <button class="home-nav-btn" onclick="goScreen('screenHome')">🏠</button>
    <div class="nav-item" onclick="openPanel('panelSalary')">
      <div class="nav-icon">💰</div>
      <div class="nav-lbl">Lương</div>
    </div>
    <div class="nav-item" onclick="goScreen('screenSettings')">
      <div class="nav-icon">⚙️</div>
      <div class="nav-lbl">Cài đặt</div>
    </div>
  </div>
</div>

<!-- ===================== CALENDAR SCREEN ===================== -->
<div class="screen" id="screenCal">
  <div class="cal-screen-header">
    <div style="display:flex;align-items:center;gap:10px;margin-bottom:6px">
      <div onclick="goScreen('screenHome')" style="color:rgba(255,255,255,.8);cursor:pointer;font-size:20px">←</div>
      <div class="cal-screen-title" id="calScreenTitle" style="margin:0">Lịch chấm công</div>
    </div>
    <div class="cal-screen-sub" id="calScreenSub">Tháng 4, 2026</div>
  </div>

  <!-- Calendar card with background image support -->
  <div id="calBigWrap" style="margin:0 16px;margin-top:-54px;border-radius:20px;overflow:hidden;box-shadow:var(--shadow);position:relative;z-index:2;background:white;transition:all .4s">
    <!-- Calendar content -->
    <div style="position:relative;padding:16px">
      <div class="cal-nav">
        <div class="cal-nav-btn" id="calNavPrev" onclick="calChange(-1)" style="transition:all .3s">‹</div>
        <div class="cal-month" id="calBigMonth" style="transition:color .3s">Tháng 4 2026</div>
        <div class="cal-nav-btn" id="calNavNext" onclick="calChange(1)" style="transition:all .3s">›</div>
      </div>
      <div class="cal-dow" id="calDow" style="transition:all .3s">
        <span class="sun">CN</span><span>T2</span><span>T3</span><span>T4</span><span>T5</span><span>T6</span><span class="sat">T7</span>
      </div>
      <div class="cal-days" id="calBigDays"></div>
    </div>
  </div>
  <!-- Legend -->
  <div style="display:flex;flex-wrap:wrap;gap:8px;padding:12px 16px">
    <div class="chip" style="background:#E0F5EE;color:#0a7d5c" id="chipCM">✓ Có mặt</div>
    <div class="chip" style="background:#FFF0EF;color:#E8433A" id="chipV">✕ Vắng</div>
    <div class="chip" style="background:#FFF8E8;color:#F5A623" id="chipNP">☀ Nghỉ phép</div>
    <div class="chip" style="background:#EEF4FF;color:#2D7DD2" id="chipLL">★ Làm lễ</div>
  </div>
  <!-- List of days -->
  <div style="padding:0 16px 16px" id="calDayList"></div>
  <div class="bottom-nav">
    <div class="nav-item" onclick="goScreen('screenHome')"><div class="nav-icon">🏠</div><div class="nav-lbl">Trang chủ</div></div>
    <div class="nav-item active"><div class="nav-icon">📅</div><div class="nav-lbl">Lịch</div></div>
    <button class="home-nav-btn" onclick="goScreen('screenHome')">🏠</button>
    <div class="nav-item" onclick="openPanel('panelSalary')"><div class="nav-icon">💰</div><div class="nav-lbl">Lương</div></div>
    <div class="nav-item" onclick="goScreen('screenSettings')"><div class="nav-icon">⚙️</div><div class="nav-lbl">Cài đặt</div></div>
  </div>
</div>

<!-- ===================== SETTINGS SCREEN ===================== -->
<div class="screen" id="screenSettings">
  <div class="home-header" style="padding-bottom:20px">
    <div class="home-top">
      <div style="color:rgba(255,255,255,.8);cursor:pointer;font-size:20px" onclick="goScreen('screenHome')">←</div>
      <div style="font-size:20px;font-weight:900;color:white" id="settingsTitle">Cài đặt</div>
      <div style="width:24px"></div>
    </div>
  </div>
  <div class="settings-list" style="padding-top:16px">
    <div class="settings-item" onclick="openPanel('panelLang')">
      <div class="si-icon" style="background:#EEF4FF">🌐</div>
      <div class="si-body"><div class="si-name">Ngôn ngữ</div><div class="si-sub" id="siLangSub">Tiếng Việt</div></div>
      <div class="si-arrow">›</div>
    </div>
    <div class="settings-item" onclick="openPanel('panelCountry')">
      <div class="si-icon" style="background:#E0F5EE">🗺️</div>
      <div class="si-body"><div class="si-name">Quốc gia làm việc</div><div class="si-sub" id="siCountrySub">Việt Nam</div></div>
      <div class="si-arrow">›</div>
    </div>
    <div class="settings-item" onclick="openPanel('panelSetup')">
      <div class="si-icon" style="background:#FFF0EF">📝</div>
      <div class="si-body"><div class="si-name">Thiết lập thông tin</div><div class="si-sub">Tên, chức vụ, ca làm việc</div></div>
      <div class="si-arrow">›</div>
    </div>
    <div class="settings-item" onclick="openPanel('panelNotif')">
      <div class="si-icon" style="background:#FFF8E8">🔔</div>
      <div class="si-body"><div class="si-name">Cài đặt thông báo</div><div class="si-sub">Nhắc giờ làm, tự động chấm công</div></div>
      <div class="si-arrow">›</div>
    </div>
    <div class="settings-item" onclick="openPanel('panelAppearance')">
      <div class="si-icon" style="background:#FFFBE8">⭐</div>
      <div class="si-body"><div class="si-name">Chỉnh sửa giao diện</div><div class="si-sub">Màu sắc, ảnh đại diện, ảnh nền</div></div>
      <div class="si-arrow">›</div>
    </div>
    <div class="settings-item" onclick="openPanel('panelAbout')">
      <div class="si-icon" style="background:#F5F0FF">ℹ️</div>
      <div class="si-body"><div class="si-name">Thông tin về app</div><div class="si-sub">Phiên bản 2.2.0</div></div>
      <div class="si-arrow">›</div>
    </div>
    <div class="settings-item" onclick="openPanel('panelHelp')">
      <div class="si-icon" style="background:#F0F0F0">📖</div>
      <div class="si-body"><div class="si-name">Hướng dẫn sử dụng</div><div class="si-sub">Cách dùng app hiệu quả</div></div>
      <div class="si-arrow">›</div>
    </div>
    <div class="settings-item" style="border:1.5px solid #FFE0DE" onclick="confirmReset()">
      <div class="si-icon" style="background:#FFF0EF">🗑️</div>
      <div class="si-body"><div class="si-name" id="siDeleteName" style="color:#E8433A">Xóa toàn bộ dữ liệu</div><div class="si-sub">Không thể khôi phục</div></div>
      <div class="si-arrow" style="color:#E8433A">›</div>
    </div>
  </div>
  <div class="bottom-nav">
    <div class="nav-item" onclick="goScreen('screenHome')"><div class="nav-icon">🏠</div><div class="nav-lbl">Trang chủ</div></div>
    <div class="nav-item" onclick="goScreen('screenCal')"><div class="nav-icon">📅</div><div class="nav-lbl">Lịch</div></div>
    <button class="home-nav-btn" onclick="goScreen('screenHome')">🏠</button>
    <div class="nav-item" onclick="openPanel('panelSalary')"><div class="nav-icon">💰</div><div class="nav-lbl">Lương</div></div>
    <div class="nav-item active"><div class="nav-icon">⚙️</div><div class="nav-lbl">Cài đặt</div></div>
  </div>
</div>

<!-- ===================== PANELS ===================== -->

<!-- Appearance Panel -->
<div class="panel-overlay" id="panelAppearance">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">⭐ Chỉnh sửa giao diện</div>
      <button class="panel-close" onclick="closePanel('panelAppearance')">✕</button>
    </div>
    <div class="panel-body">
      <div class="ap-section-title" id="apSecAvt">Ảnh đại diện</div>
      <div class="avatar-picker">
        <div class="avatar-preview" id="apAvtPrev">👤</div>
        <div>
          <div id="apAvtDesc" style="font-size:13px;color:var(--text2);margin-bottom:8px">Ảnh hiển thị trên trang chủ</div>
          <button class="upload-btn" id="btnChooseAvt" onclick="document.getElementById('fileAvt').click()">📷 Chọn ảnh</button>
          <input type="file" id="fileAvt" accept="image/*" style="display:none" onchange="uploadAvt(this)">
        </div>
      </div>
      <div class="ap-section-title" id="apSecColor">Màu chủ đạo</div>
      <div class="color-grid" id="colorGrid"></div>
      <div class="ap-section-title" id="apSecBg">Ảnh nền lịch</div>
      <!-- Preview -->
      <div id="apBgPreview" style="width:100%;height:100px;border-radius:14px;border:2px dashed var(--border);display:flex;align-items:center;justify-content:center;font-size:13px;color:var(--text3);overflow:hidden;margin-bottom:10px;position:relative;background:#F4F7F6">
        <span id="apBgPreviewTxt">Chưa có ảnh nền</span>
      </div>
      <div style="display:flex;gap:8px;flex-wrap:wrap;margin-bottom:10px">
        <button class="upload-btn" onclick="document.getElementById('fileBg').click()" id="btnChooseImg">📷 Chọn ảnh từ máy</button>
        <input type="file" id="fileBg" accept="image/*" style="display:none" onchange="uploadBg(this)">
        <button class="upload-btn" style="color:#E8433A;border-color:#FFE0DE" id="btnClearBg" onclick="clearBg()">✕ Xóa ảnh</button>
      </div>
      <!-- Gradient presets -->
      <div id="apSecGradient" style="font-size:11px;font-weight:700;color:var(--text3);text-transform:uppercase;letter-spacing:.05em;margin-bottom:8px">Màu nền gradient</div>
      <div style="display:flex;gap:8px;flex-wrap:wrap;margin-bottom:16px" id="gradientGrid"></div>

      <!-- Calendar text colors -->
      <div class="ap-section-title" id="apSecCalColor">🎨 Màu chữ trong lịch</div>
      <div style="background:#F4F7F6;border-radius:14px;padding:14px;margin-bottom:16px">
        <!-- Preview row -->
        <div style="display:flex;gap:6px;margin-bottom:14px;justify-content:center">
          <div style="width:36px;height:36px;border-radius:8px;background:rgba(0,0,0,.06);display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700" id="previewSun">CN</div>
          <div style="width:36px;height:36px;border-radius:8px;background:rgba(0,0,0,.06);display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700">T2</div>
          <div style="width:36px;height:36px;border-radius:8px;background:rgba(0,0,0,.06);display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700">T3</div>
          <div style="width:36px;height:36px;border-radius:8px;background:rgba(0,0,0,.06);display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700">T4</div>
          <div style="width:36px;height:36px;border-radius:8px;background:rgba(0,0,0,.06);display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700">T5</div>
          <div style="width:36px;height:36px;border-radius:8px;background:rgba(0,0,0,.06);display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700">T6</div>
          <div style="width:36px;height:36px;border-radius:8px;background:rgba(0,0,0,.06);display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700" id="previewSat">T7</div>
        </div>
        <!-- Sunday color -->
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px">
          <div>
            <div id="calColorSunLbl" style="font-size:13px;font-weight:700;color:var(--text)">Chủ nhật (CN)</div>
            <div id="calColorSunSub" style="font-size:11px;color:var(--text3);margin-top:2px">Màu chữ ngày Chủ nhật</div>
          </div>
          <div style="display:flex;align-items:center;gap:8px">
            <div id="sunColorDot" style="width:28px;height:28px;border-radius:50%;border:2px solid var(--border);cursor:pointer;overflow:hidden;position:relative">
              <input type="color" id="sunColorPick" value="#E8433A" style="position:absolute;inset:-4px;width:calc(100%+8px);height:calc(100%+8px);border:none;cursor:pointer;opacity:0" oninput="onCalColorChange()">
              <div id="sunColorShow" style="width:100%;height:100%;background:#E8433A;pointer-events:none"></div>
            </div>
            <span id="sunColorHex" style="font-size:12px;font-weight:700;color:var(--text2)">#E8433A</span>
          </div>
        </div>
        <!-- Saturday color -->
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px">
          <div>
            <div id="calColorSatLbl" style="font-size:13px;font-weight:700;color:var(--text)">Thứ 7 (T7)</div>
            <div id="calColorSatSub" style="font-size:11px;color:var(--text3);margin-top:2px">Màu chữ ngày Thứ 7</div>
          </div>
          <div style="display:flex;align-items:center;gap:8px">
            <div style="width:28px;height:28px;border-radius:50%;border:2px solid var(--border);cursor:pointer;overflow:hidden;position:relative">
              <input type="color" id="satColorPick" value="#2D7DD2" style="position:absolute;inset:-4px;width:calc(100%+8px);height:calc(100%+8px);border:none;cursor:pointer;opacity:0" oninput="onCalColorChange()">
              <div id="satColorShow" style="width:100%;height:100%;background:#2D7DD2;pointer-events:none"></div>
            </div>
            <span id="satColorHex" style="font-size:12px;font-weight:700;color:var(--text2)">#2D7DD2</span>
          </div>
        </div>
        <!-- Normal day color -->
        <div style="display:flex;justify-content:space-between;align-items:center">
          <div>
            <div id="calColorNormLbl" style="font-size:13px;font-weight:700;color:var(--text)">Ngày thường (T2–T6)</div>
            <div id="calColorNormSub" style="font-size:11px;color:var(--text3);margin-top:2px">Màu chữ ngày trong tuần</div>
          </div>
          <div style="display:flex;align-items:center;gap:8px">
            <div style="width:28px;height:28px;border-radius:50%;border:2px solid var(--border);cursor:pointer;overflow:hidden;position:relative">
              <input type="color" id="normColorPick" value="#1A2332" style="position:absolute;inset:-4px;width:calc(100%+8px);height:calc(100%+8px);border:none;cursor:pointer;opacity:0" oninput="onCalColorChange()">
              <div id="normColorShow" style="width:100%;height:100%;background:#1A2332;pointer-events:none"></div>
            </div>
            <span id="normColorHex" style="font-size:12px;font-weight:700;color:var(--text2)">#1A2332</span>
          </div>
        </div>
        <!-- Reset button -->
        <button id="btnResetColors" onclick="resetCalColors()" style="margin-top:12px;width:100%;padding:8px;border-radius:10px;border:1.5px solid var(--border);background:white;font-size:13px;font-weight:700;cursor:pointer;color:var(--text2);font-family:Nunito,sans-serif">↺ Đặt lại màu mặc định</button>
      </div>

      <button class="export-btn" id="btnSaveAppear" style="background:var(--ac)" onclick="saveAppearance()">✓ Lưu giao diện</button>
    </div>
  </div>
</div>

<!-- Notification Panel -->
<div class="panel-overlay" id="panelNotif">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">🔔 Cài đặt thông báo</div>
      <button class="panel-close" onclick="closePanel('panelNotif')">✕</button>
    </div>
    <div class="panel-body">
      <div class="notif-row">
        <div class="notif-info">
          <div class="notif-name">Nhắc trước giờ làm 30 phút</div>
          <div class="notif-desc">Thông báo nhắc nhở trước ca bắt đầu</div>
        </div>
        <button class="toggle-sw on" id="togN1" onclick="togNotif('togN1')"></button>
      </div>
      <div class="notif-row">
        <div class="notif-info">
          <div class="notif-name">Xác nhận giờ nghỉ sau 30 phút</div>
          <div class="notif-desc">Hỏi giờ tan ca thực tế sau khi hết ca</div>
        </div>
        <button class="toggle-sw on" id="togN2" onclick="togNotif('togN2')"></button>
      </div>
      <div class="notif-row">
        <div class="notif-info">
          <div class="notif-name" id="n3Name">Chấm công tự động (GPS)</div>
          <div class="notif-desc" id="n3Desc">Tự động ghi nhận khi vào/ra khu vực công ty</div>
        </div>
        <button class="toggle-sw" id="togN3" onclick="togGPS(this)"></button>
      </div>
      <!-- GPS Setup Card -->
      <div id="gpsSetupCard" style="display:none;background:#F4F7F6;border-radius:14px;padding:14px;margin-top:4px">
        <div style="font-size:12px;font-weight:700;color:var(--text2);margin-bottom:10px">📍 VỊ TRÍ CÔNG TY</div>
        <!-- Status indicator -->
        <div id="gpsStatusBox" style="display:flex;align-items:center;gap:8px;background:white;border-radius:10px;padding:10px 12px;margin-bottom:10px;border:1.5px solid var(--border)">
          <div id="gpsStatusDot" style="width:10px;height:10px;border-radius:50%;background:#ccc;flex-shrink:0"></div>
          <div id="gpsStatusTxt" style="font-size:13px;color:var(--text2)">Chưa thiết lập vị trí công ty</div>
        </div>
        <!-- Coords display -->
        <div id="gpsCoordsBox" style="display:none;background:white;border-radius:10px;padding:10px 12px;margin-bottom:10px;font-size:12px;color:var(--text3)">
          <div id="gpsCoordsText"></div>
        </div>
        <!-- Radius -->
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px">
          <span style="font-size:13px;font-weight:600;color:var(--text)">Bán kính phát hiện</span>
          <div style="display:flex;align-items:center;gap:6px">
            <input type="range" id="gpsRadius" min="50" max="500" step="50" value="100" oninput="document.getElementById('gpsRadiusVal').textContent=this.value+'m'" style="width:100px">
            <span id="gpsRadiusVal" style="font-size:13px;font-weight:700;color:var(--ac);min-width:40px">100m</span>
          </div>
        </div>
        <!-- Buttons -->
        <div style="display:flex;gap:8px">
          <button onclick="gpsRequestPermission()" id="gpsBtnReq" style="flex:1;padding:10px;border-radius:10px;background:var(--ac);border:none;color:white;font-size:13px;font-weight:700;cursor:pointer;font-family:Nunito,sans-serif">📍 Lấy vị trí hiện tại</button>
          <button onclick="gpsClear()" style="flex:0 0 auto;padding:10px 14px;border-radius:10px;background:white;border:1.5px solid #FFE0DE;color:#E8433A;font-size:13px;font-weight:700;cursor:pointer;font-family:Nunito,sans-serif">✕</button>
        </div>
        <!-- Permission guide - shown on error -->
        <div id="gpsPermGuide" style="display:none;margin-top:10px;background:#FFF8E8;border-radius:10px;padding:12px;border:1.5px solid #F5A623">
          <div style="font-size:12px;font-weight:800;color:#cc8800;margin-bottom:8px">⚠️ Chrome chặn GPS với file cục bộ</div>
          <div style="font-size:12px;color:#854F0B;line-height:1.7">
            Chrome trên điện thoại không cho phép GPS khi mở file .html trực tiếp.<br><br>
            <b>Giải pháp nhanh:</b> Nhập tọa độ công ty thủ công 👇
          </div>
        </div>
        <!-- Manual coordinate input -->
        <div id="gpsManualBox" style="margin-top:10px;background:white;border-radius:10px;padding:12px;border:1.5px solid var(--border)">
          <div style="font-size:12px;font-weight:800;color:var(--text2);margin-bottom:8px">🗺️ NHẬP TỌA ĐỘ THỦ CÔNG</div>
          <div style="font-size:11px;color:var(--text3);margin-bottom:8px">Mở <b>Google Maps</b> → nhấn giữ vị trí công ty → copy tọa độ</div>
          <div style="display:flex;gap:8px;margin-bottom:8px">
            <div style="flex:1">
              <div style="font-size:11px;font-weight:700;color:var(--text2);margin-bottom:4px">Vĩ độ (Latitude)</div>
              <input type="number" id="gpsManualLat" placeholder="VD: 10.762622" step="any" style="width:100%;border:1.5px solid var(--border);border-radius:8px;padding:8px 10px;font-size:13px;font-family:Nunito,sans-serif;color:var(--text);outline:none" onfocus="this.style.borderColor='var(--ac)'" onblur="this.style.borderColor='var(--border)'">
            </div>
            <div style="flex:1">
              <div style="font-size:11px;font-weight:700;color:var(--text2);margin-bottom:4px">Kinh độ (Longitude)</div>
              <input type="number" id="gpsManualLng" placeholder="VD: 106.682739" step="any" style="width:100%;border:1.5px solid var(--border);border-radius:8px;padding:8px 10px;font-size:13px;font-family:Nunito,sans-serif;color:var(--text);outline:none" onfocus="this.style.borderColor='var(--ac)'" onblur="this.style.borderColor='var(--border)'">
            </div>
          </div>
          <button onclick="gpsSaveManual()" style="width:100%;padding:10px;border-radius:10px;background:var(--ac);border:none;color:white;font-size:13px;font-weight:700;cursor:pointer;font-family:Nunito,sans-serif">✓ Lưu vị trí công ty</button>
          <div style="margin-top:8px;font-size:11px;color:var(--text3)">
            📌 Cách lấy tọa độ: Mở <b>Google Maps</b> → tìm công ty → nhấn giữ → copy 2 số xuất hiện
          </div>
        </div>
        <!-- Host guide -->
        <div id="gpsHostGuide" style="display:none;margin-top:8px;background:#EEF4FF;border-radius:10px;padding:12px;border:1.5px solid #2D7DD2">
          <div style="font-size:12px;font-weight:800;color:#185FA5;margin-bottom:6px">🌐 Cấp quyền GPS tự động</div>
          <div style="font-size:12px;color:#185FA5;line-height:1.7">
            Upload file lên <b>GitHub Pages</b> hoặc <b>Netlify Drop</b> (miễn phí) → mở link HTTPS → GPS hoạt động tự động
          </div>
        </div>
        <div style="margin-top:8px;font-size:11px;color:var(--text3);line-height:1.5">💡 Sau khi lưu vị trí, app dùng GPS điện thoại để kiểm tra khoảng cách và tự chấm công.</div>
      </div>
      <div class="notif-row">
        <div class="notif-info">
          <div class="notif-name">Nhắc cuối tuần tổng kết</div>
          <div class="notif-desc">Xem tổng hợp tuần vào thứ 6 hàng tuần</div>
        </div>
        <button class="toggle-sw" id="togN4" onclick="togNotif('togN4')"></button>
      </div>
    </div>
  </div>
</div>

<!-- Salary Panel -->
<div class="panel-overlay" id="panelSalary">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">💰 Bảng lương</div>
      <button class="panel-close" onclick="closePanel('panelSalary')">✕</button>
    </div>
    <div class="panel-body">
      <div class="field-label">Lương hợp đồng / tháng (₫)</div>
      <input class="field-input" type="number" id="salaryInput" placeholder="10,000,000" oninput="calcSalary()">
      <div style="height:12px"></div>
      <div class="field-label">Ngày công chuẩn / tháng</div>
      <div class="num-grid" style="grid-template-columns:repeat(3,1fr);margin-bottom:12px" id="ngcGrid">
        <div class="num-btn sel" onclick="selNgc(22,this)">22</div>
        <div class="num-btn" onclick="selNgc(26,this)">26</div>
        <div class="num-btn" onclick="selNgc(30,this)">30</div>
      </div>
      <div style="background:var(--ac-lt);border-radius:14px;padding:16px;margin-bottom:16px">
        <div style="font-size:12px;color:var(--ac2);font-weight:700;margin-bottom:8px">Lương ước tính tháng này</div>
        <div id="salaryBreakdown" style="font-size:13px;color:var(--text2);line-height:2"></div>
        <div style="border-top:1px solid rgba(13,158,117,.2);margin-top:10px;padding-top:10px;display:flex;justify-content:space-between">
          <span style="font-size:14px;font-weight:700;color:var(--text)">Thực nhận ước tính</span>
          <span style="font-size:18px;font-weight:900;color:var(--ac)" id="salaryNet">0 ₫</span>
        </div>
      </div>
      <button class="export-btn" style="background:var(--ac)" onclick="closePanel('panelSalary')">✓ Lưu thông tin lương</button>
    </div>
  </div>
</div>

<!-- Excel Preview Panel -->
<div class="panel-overlay" id="panelExcel">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">📊 Xuất Excel</div>
      <button class="panel-close" onclick="closePanel('panelExcel')">✕</button>
    </div>
    <div class="panel-body">
      <div style="font-size:13px;color:var(--text2);margin-bottom:12px">Xem trước dữ liệu xuất ra:</div>
      <div class="excel-preview" id="excelPreview">
        <div class="excel-row head">
          <div class="excel-cell">Ngày</div>
          <div class="excel-cell">Thứ</div>
          <div class="excel-cell">Trạng thái</div>
          <div class="excel-cell">Giờ vào</div>
          <div class="excel-cell">Giờ ra</div>
        </div>
      </div>
      <button class="export-btn" onclick="doExport()">📊 Xuất file Excel (.csv)</button>
    </div>
  </div>
</div>

<!-- Lang Panel -->
<div class="panel-overlay" id="panelLang">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">🌐 Chọn ngôn ngữ</div>
      <button class="panel-close" onclick="closePanel('panelLang')">✕</button>
    </div>
    <div class="panel-body">
      <div class="lang-grid" id="settingsLangGrid"></div>
    </div>
  </div>
</div>

<!-- Country Panel -->
<div class="panel-overlay" id="panelCountry">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">🗺️ Quốc gia làm việc</div>
      <button class="panel-close" onclick="closePanel('panelCountry')">✕</button>
    </div>
    <div class="panel-body">
      <div class="country-grid" id="settingsCountryGrid"></div>
    </div>
  </div>
</div>

<!-- Setup Panel -->
<div class="panel-overlay" id="panelSetup">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">📝 Thiết lập thông tin</div>
      <button class="panel-close" onclick="closePanel('panelSetup')">✕</button>
    </div>
    <div class="panel-body">
      <div class="field-label" id="setupLblName">Họ và tên</div>
      <input class="field-input" id="setupName" placeholder="Nguyễn Văn A" style="margin-bottom:12px">
      <div class="field-label" id="setupLblJob">Chức vụ</div>
      <input class="field-input" id="setupJob" placeholder="Nhân viên / Công nhân..." style="margin-bottom:12px">
      <div class="field-label" id="setupLblCo">Công ty</div>
      <input class="field-input" id="setupCo" placeholder="Công ty ABC" style="margin-bottom:12px">
      <div class="field-label" id="setupLblShift">Số ca làm việc</div>
      <div class="num-grid" style="margin-bottom:12px" id="setupShiftGrid">
        <div class="num-btn sel" onclick="selShift(1,this)">1</div>
        <div class="num-btn" onclick="selShift(2,this)">2</div>
        <div class="num-btn" onclick="selShift(3,this)">3</div>
        <div class="num-btn" onclick="selShift(4,this)">4</div>
      </div>
      <div class="field-label" id="setupLblHours">Số giờ / ca</div>
      <div class="num-grid" style="grid-template-columns:repeat(5,1fr);margin-bottom:16px" id="setupHoursGrid">
        <div class="num-btn" onclick="selHours(6,this)">6h</div>
        <div class="num-btn" onclick="selHours(7,this)">7h</div>
        <div class="num-btn sel" onclick="selHours(8,this)">8h</div>
        <div class="num-btn" onclick="selHours(10,this)">10h</div>
        <div class="num-btn" onclick="selHours(12,this)">12h</div>
      </div>
      <button class="export-btn" id="btnSaveSetup" style="background:var(--ac)" onclick="saveSetup()">✓ Lưu thông tin</button>
    </div>
  </div>
</div>

<!-- Help Panel -->
<div class="panel-overlay" id="panelHelp">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">📖 Hướng dẫn sử dụng</div>
      <button class="panel-close" onclick="closePanel('panelHelp')">✕</button>
    </div>
    <div class="panel-body" style="font-size:14px;color:var(--text2);line-height:1.8">
      <p style="font-weight:800;color:var(--text);margin-bottom:8px">🟢 Cách chấm công</p>
      <p>1. Bấm <strong>VÀO CA</strong> (xanh) khi bắt đầu ca làm việc</p>
      <p style="margin-bottom:12px">2. Bấm <strong>HẾT CA</strong> (đỏ) khi kết thúc</p>
      <p style="font-weight:800;color:var(--text);margin-bottom:8px">📅 Xem lịch</p>
      <p style="margin-bottom:12px">Bấm vào tab Lịch để xem chi tiết từng ngày. Bấm vào ngày để chỉnh sửa.</p>
      <p style="font-weight:800;color:var(--text);margin-bottom:8px">💰 Tính lương</p>
      <p style="margin-bottom:12px">Vào mục Lương → nhập lương hợp đồng → app tự tính theo ngày làm việc và luật quốc gia.</p>
      <p style="font-weight:800;color:var(--text);margin-bottom:8px">📊 Xuất Excel</p>
      <p>Vào Xuất Excel → xem trước dữ liệu → bấm xuất. File CSV mở được bằng Excel.</p>
    </div>
  </div>
</div>

<!-- About Panel -->
<div class="panel-overlay" id="panelAbout">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div class="panel-head">
      <div class="panel-title">ℹ️ Về ứng dụng</div>
      <button class="panel-close" onclick="closePanel('panelAbout')">✕</button>
    </div>
    <div class="panel-body" style="text-align:center">
      <div style="font-size:60px;margin-bottom:12px">📋</div>
      <div class="rgb-text" style="font-size:24px;font-weight:900;font-family:Quicksand;margin-bottom:4px">Chấm Công Pro</div>
      <div style="font-size:13px;color:var(--text3);margin-bottom:20px">Phiên bản 2.2.0</div>
      <div style="font-size:14px;color:var(--text2);line-height:1.8">
        App chấm công thông minh hỗ trợ đa ngôn ngữ, tính lương theo luật lao động 6 quốc gia. Dữ liệu lưu trên thiết bị, bảo mật tuyệt đối.
      </div>
    </div>
  </div>
</div>


<!-- DAY DETAIL PANEL (từ v21) -->
<div class="panel-overlay" id="panelDay">
  <div class="panel-sheet" style="border-radius:20px 20px 0 0">
    <div class="panel-handle"></div>
    <div style="padding:16px 20px 0">
      <div style="font-size:17px;font-weight:800;color:var(--text)" id="dayPanelTitle">Thứ 5, ngày 23/4/2026</div>
      <div id="dayPanelCa" style="display:none;font-size:12px;background:#EEF4FF;color:#2D7DD2;border-radius:8px;padding:5px 10px;margin-top:8px;font-weight:700"></div>
    </div>
    <div style="padding:12px 20px 0">
      <div id="dpStatusLbl" style="font-size:11px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:.06em;margin-bottom:10px">TRẠNG THÁI</div>
      <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-bottom:14px" id="dayStatusGrid"></div>
      <!-- Giờ vào ra -->
      <div id="dayTimeBlock" style="display:none;background:#F4F7F6;border-radius:12px;padding:12px;margin-bottom:12px">
        <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:10px">
          <span id="dpActualLbl" style="font-size:12px;font-weight:700;color:var(--text2)">GIỜ THỰC TẾ</span>
          <span style="font-size:12px;color:var(--ac);font-weight:700;cursor:pointer" onclick="dayResetTime()">Đặt lại theo ca</span>
        </div>
        <div style="display:flex;gap:10px;align-items:center">
          <div style="flex:1">
            <div style="font-size:11px;font-weight:700;color:var(--text3);margin-bottom:4px">Giờ vào</div>
            <input type="time" id="dayTimeIn" style="width:100%;border:1.5px solid var(--border);border-radius:10px;padding:8px;font-size:16px;font-weight:700;text-align:center;font-family:Nunito,sans-serif;color:var(--text);background:white;outline:none" oninput="dayCalcHours()">
          </div>
          <div style="font-size:20px;color:var(--text3);font-weight:700;padding-top:16px">→</div>
          <div style="flex:1">
            <div style="font-size:11px;font-weight:700;color:var(--text3);margin-bottom:4px">Giờ ra</div>
            <input type="time" id="dayTimeOut" style="width:100%;border:1.5px solid var(--border);border-radius:10px;padding:8px;font-size:16px;font-weight:700;text-align:center;font-family:Nunito,sans-serif;color:var(--text);background:white;outline:none" oninput="dayCalcHours()">
          </div>
        </div>
        <div id="dayHoursSummary" style="margin-top:8px;font-size:13px;color:var(--text2);text-align:center"></div>
      </div>
      <!-- Ghi chú -->
      <div id="dpNoteLbl" style="font-size:11px;font-weight:800;color:var(--text3);text-transform:uppercase;letter-spacing:.06em;margin-bottom:6px">GHI CHÚ</div>
      <textarea id="dayNote" placeholder="Thêm ghi chú cho ngày này..." rows="2" style="width:100%;border:1.5px solid var(--border);border-radius:12px;padding:10px 12px;font-size:13px;font-family:Nunito,sans-serif;color:var(--text);background:white;outline:none;resize:none;margin-bottom:14px"></textarea>
      <!-- Buttons -->
      <div style="display:flex;gap:10px;padding-bottom:8px">
        <button id="dayCancelBtn" onclick="closeDayPanel()" style="flex:1;padding:14px;border-radius:12px;border:1.5px solid var(--border);background:white;font-size:14px;font-weight:700;cursor:pointer;font-family:Nunito,sans-serif;color:var(--text2)">Hủy bỏ</button>
        <button id="daySaveBtn" onclick="saveDayPanel()" style="flex:2;padding:14px;border-radius:12px;border:none;background:var(--ac);font-size:14px;font-weight:800;cursor:pointer;font-family:Nunito,sans-serif;color:white">Lưu lại</button>
      </div>
    </div>
  </div>
</div>

<!-- SPLASH SCREEN -->
<div class="splash-ov" id="splashOv" onclick="dongSplash()">
<div class="splash-box" id="splashBox" onclick="event.stopPropagation()">
  <!-- Particle effects -->
  <svg class="sp-pf" style="left:-8px;top:-8px;width:50px;height:50px" viewBox="0 0 50 50">
    <g class="pf-bc" style="animation-delay:.1s;transform-origin:25px 25px">
      <line x1="25" y1="25" x2="25" y2="7" stroke="#1D9E75" stroke-width="2" stroke-linecap="round"/>
    </g>
    <g class="pf-bc" style="animation-delay:.3s;transform-origin:25px 25px">
      <line x1="25" y1="25" x2="38" y2="12" stroke="#F5A623" stroke-width="2" stroke-linecap="round"/>
    </g>
    <g class="pf-bc" style="animation-delay:.2s;transform-origin:25px 25px">
      <line x1="25" y1="25" x2="8" y2="15" stroke="#2D7DD2" stroke-width="2" stroke-linecap="round"/>
    </g>
  </svg>
  <svg class="sp-pf" style="right:-8px;bottom:30px;width:50px;height:50px" viewBox="0 0 50 50">
    <g class="pf-bc" style="animation-delay:.5s;transform-origin:25px 25px">
      <line x1="25" y1="25" x2="25" y2="7" stroke="#7B5EA7" stroke-width="2" stroke-linecap="round"/>
    </g>
    <g class="pf-bc" style="animation-delay:.7s;transform-origin:25px 25px">
      <line x1="25" y1="25" x2="42" y2="30" stroke="#E8433A" stroke-width="2" stroke-linecap="round"/>
    </g>
  </svg>
  <!-- Icon -->
  <div class="sp-icon">
    <svg viewBox="0 0 24 24" fill="none" stroke="var(--ac)" stroke-width="1.5" width="26" height="26">
      <path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/>
    </svg>
  </div>
  <!-- Month badge -->
  <div class="sp-badge" id="spBadge">
    <div class="sp-dot" id="spDot"></div>
    <span class="sp-badge-txt" id="spBadgeTxt">Tháng 4 · 2026</span>
  </div>
  <!-- Number -->
  <div class="sp-so" id="spSo">0</div>
  <div class="sp-dv" id="spDv">ngày có mặt tháng này</div>
  <!-- Quote -->
  <div class="sp-cau" id="spCau">Chào buổi sáng! Chăm chỉ hôm nay, thanh thản ngày mai.</div>
  <!-- Button -->
  <button class="sp-nut" id="spNut" onclick="dongSplash()">Bắt đầu ngày làm việc</button>
</div>
</div>
<!-- Confirm Reset Panel -->
<div class="panel-overlay" id="panelConfirmReset">
  <div class="panel-sheet">
    <div class="panel-handle"></div>
    <div style="padding:24px 20px;text-align:center">
      <div style="font-size:52px;margin-bottom:12px">🗑️</div>
      <div style="font-size:18px;font-weight:900;color:#E8433A;margin-bottom:8px">Xóa toàn bộ dữ liệu?</div>
      <div style="font-size:14px;color:var(--text2);line-height:1.6;margin-bottom:24px">Tất cả dữ liệu chấm công, cài đặt và thông tin cá nhân sẽ bị xóa vĩnh viễn.<br><strong>Không thể khôi phục!</strong></div>
      <div style="display:flex;gap:10px">
        <button onclick="closePanel('panelConfirmReset')" style="flex:1;padding:14px;border-radius:14px;border:1.5px solid var(--border);background:white;font-size:14px;font-weight:700;cursor:pointer;font-family:Nunito,sans-serif;color:var(--text2)">Hủy bỏ</button>
        <button onclick="doReset()" style="flex:1;padding:14px;border-radius:14px;border:none;background:#E8433A;font-size:14px;font-weight:800;cursor:pointer;font-family:Nunito,sans-serif;color:white">🗑 Xóa hết</button>
      </div>
    </div>
  </div>
</div>

</div><!-- end app -->

<script>
// === HOLIDAY DATA ===
const NL={'2025-0-1':'Tết Dương lịch','2025-1-25':'Nghỉ Tết (25 Chạp)','2025-1-26':'Nghỉ Tết (26 Chạp)','2025-1-27':'Nghỉ Tết (27 Chạp)','2025-1-28':'Giao thừa Ất Tỵ','2025-1-29':'Mùng 1 Tết Ất Tỵ','2025-1-30':'Mùng 2 Tết Ất Tỵ','2025-1-31':'Mùng 3 Tết Ất Tỵ','2025-2-1':'Mùng 4 Tết Ất Tỵ','2025-2-2':'Mùng 5 Tết Ất Tỵ','2025-3-18':'Giỗ Tổ Hùng Vương','2025-4-30':'Ngày Giải phóng 30/4','2025-4-1':'Quốc tế Lao động 1/5','2025-8-1':'Nghỉ bù Quốc khánh','2025-8-2':'Quốc khánh 2/9','2026-0-1':'Tết Dương lịch','2026-1-14':'Nghỉ Tết (27 Chạp)','2026-1-15':'Nghỉ Tết (28 Chạp)','2026-1-16':'Mùng 1 Tết Bính Ngọ','2026-1-17':'Mùng 2 Tết Bính Ngọ','2026-1-18':'Mùng 3 Tết Bính Ngọ','2026-1-19':'Mùng 4 Tết Bính Ngọ','2026-1-20':'Mùng 5 Tết Bính Ngọ','2026-3-26':'Giỗ Tổ Hùng Vương','2026-3-30':'Nghỉ bù 30/4','2026-4-1':'Ngày Giải phóng 30/4','2026-4-2':'Quốc tế Lao động 1/5','2026-4-3':'Nghỉ bù Quốc tế Lao động','2026-7-31':'Nghỉ bù Quốc khánh','2026-8-1':'Nghỉ Quốc khánh','2026-8-2':'Quốc khánh 2/9','2026-10-24':'Ngày Văn hóa Việt Nam'};
function gNL(n,t,g){return NL[n+"-"+t+"-"+g]||null;}

// === PAYROLL RULES ===
const PAYROLL_RULES = {
  VN:{
    name:'Việt Nam', flag:'🇻🇳', currency:'₫', currencyCode:'VND',
    normalFactor:1.0,
    otFactor:1.5,          // Tăng ca ngày thường: +50% (Điều 98 BLLĐ)
    weekendOtFactor:2.0,   // Tăng ca ngày nghỉ hàng tuần: +100%
    nightFactor:1.3,       // Ca đêm (22h-6h): +30% (Điều 98 khoản 3)
    nightOtExtra:0.2,      // Tăng ca ban đêm: thêm +20% nữa (tổng đêm+OT = +50%)
    nightStart:22, nightEnd:6,
    holidayFactor:4.0,     // Làm ngày lễ: 100% lễ + 300% = ×4.0 (Điều 112)
    weeklyHours:48, dailyOtThreshold:8,
    basis:'Điều 98–112 BLLĐ 2019',
    tags:['×1.5 tăng ca ngày thường','×2.0 tăng ca CN','×4.0 làm ngày lễ','+30% ca đêm (22h–6h)','+50% tăng ca đêm'],
  },
  KR:{
    name:'한국 (Korea)', flag:'🇰🇷', currency:'₩', currencyCode:'KRW',
    normalFactor:1.0,
    otFactor:1.5,          // Tăng ca (>40h/tuần hoặc >8h/ngày): +50%
    nightFactor:0.5,       // Ca đêm (22h-6h): +50% CỘNG THÊM vào bất kỳ loại giờ nào
    nightIsAdditive:true,  // Night premium là cộng thêm, không thay thế
    nightStart:22, nightEnd:6,
    holidayFactor:1.5,     // Ngày lễ ≤8h: +50% = ×1.5
    holidayOtFactor:2.0,   // Ngày lễ >8h: +100% = ×2.0
    weeklyHours:40, dailyOtThreshold:8,
    maxWeeklyHours:52,     // Tối đa 52h/tuần (40h thường + 12h OT)
    basis:'근로기준법 제56조 (Labor Standards Act Art.56)',
    tags:['×1.5 초과근무 (>40h/주)','×1.5 야간 cộng thêm (22h–6h)','×1.5 휴일 ≤8h','×2.0 휴일 >8h','최대 52h/주'],
  },
  JP:{
    name:'日本 (Japan)', flag:'🇯🇵', currency:'¥', currencyCode:'JPY',
    normalFactor:1.0,
    otFactor:1.25,         // Tăng ca (>8h/ngày hoặc >40h/tuần): +25%
    otOver60Factor:1.5,    // Tăng ca >60h/tháng: +50%
    nightFactor:0.25,      // Ca đêm (22h-5h): +25% CỘNG THÊM
    nightIsAdditive:true,
    nightStart:22, nightEnd:5,
    holidayFactor:1.35,    // Ngày lễ statutory holiday: +35%
    holidayNightFactor:1.60, // Ngày lễ + đêm: +60%
    weeklyHours:40, dailyOtThreshold:8,
    monthlyOtLimit:45, monthlyOtSpecialLimit:100,
    basis:'労働基準法 第37条 (Labor Standards Act Art.37)',
    tags:['×1.25 残業 (>40h/週 or >8h/日)','×1.5 残業 >60h/月','+25% 深夜 22h–5h','×1.35 法定休日','×1.5 残業+深夜'],
  },
  TW:{
    name:'台灣 (Taiwan)', flag:'🇹🇼', currency:'NT$', currencyCode:'TWD',
    normalFactor:1.0,
    ot1Factor:1.33,        // OT 2h đầu ngày thường: ×1.33 (Điều 24 LSA) — sửa từ 1.34
    ot1Hours:2,
    ot2Factor:1.67,        // OT 2h tiếp theo: ×1.67
    ot2Hours:2,
    ot3Factor:2.0,         // OT >4h: ×2.0
    flexRestFactor1:1.33,  // Ngày nghỉ linh hoạt 2h đầu: ×1.33
    flexRestFactor2:1.67,  // Ngày nghỉ linh hoạt tiếp: ×1.67
    fixedRestFactor:2.66,  // Ngày nghỉ cố định / Ngày lễ quốc gia: ×2.66
    nightFactor:1.0,       // Không có mức bắt buộc theo luật (10h-6h)
    nightStart:22, nightEnd:6,
    weeklyHours:40, dailyOtThreshold:8,
    basis:'勞動基準法 第24條 (Labor Standards Act Art.24)',
    tags:['×1.33 加班前2h','×1.67 加班後2h','×2.66 固定休假日/國定假日','×1.33/1.67 彈性休假日','夜間無法定加給'],
  },
  US:{
    name:'United States', flag:'🇺🇸', currency:'$', currencyCode:'USD',
    normalFactor:1.0,
    otFactor:1.5,          // OT >40h/tuần: ×1.5 (FLSA)
    nightFactor:1.0,       // Không có mức liên bang (varies by state/contract)
    nightStart:23, nightEnd:6,
    holidayFactor:1.0,     // Không bắt buộc theo liên bang (tùy employer)
    weeklyHours:40, dailyOtThreshold:999,
    basis:'FLSA (Fair Labor Standards Act)',
    tags:['×1.5 OT (>40h/week)','No federal night premium','No federal holiday rate','Varies by state/contract'],
  },
  MY:{
    name:'မြန်မာ (Myanmar)', flag:'🇲🇲', currency:'MMK', currencyCode:'MMK',
    normalFactor:1.0,
    otFactor:2.0,          // OT: ×2.0 (gấp đôi) — Factories Act 1951
    nightFactor:1.0,       // Không có mức cụ thể theo luật (theo hợp đồng)
    nightStart:22, nightEnd:6,
    holidayFactor:2.0,     // Làm ngày lễ: ×2.0
    weeklyHours:44,        // 44h/tuần (8h × 5 ngày + 4h thứ 7)
    dailyOtThreshold:8,
    basis:'Factories Act 1951 / Shops & Establishments Act 1989',
    tags:['×2.0 ကျော်ချိန် (OT)','44h/week ပုံမှန်','×2.0 ရုံးပိတ်ကြားနေ့','ည: ကန့်သတ်ချက်မရှိ (contract)'],
  },
  CUSTOM:{
    name:'Tùy chỉnh', flag:'⚙️', currency:'', currencyCode:'',
    normalFactor:1.0, otFactor:1.5,
    nightFactor:1.3, nightStart:22, nightEnd:6,
    holidayFactor:2.0, weeklyHours:40, dailyOtThreshold:8,
    basis:'Tùy chỉnh theo hợp đồng',
    tags:['Tùy chỉnh tất cả hệ số','Nhập theo thực tế công ty'],
  }
};

// langCfg shim for payroll
let langCfg={lang:"vi",payrollCountry:"VN",overrides:{}};
try{const _lc=JSON.parse(localStorage.getItem("cp22_lang")||"null");if(_lc)langCfg=Object.assign(langCfg,_lc);}catch(e){}

// === pGio ===
function pGio(s){if(!s)return 0;const[h,m]=s.split(':').map(Number);return h*60+m;}

// === soGio ===
function soGio(v,r){if(!v||!r)return null;const d=(pGio(r)-pGio(v)+1440)%1440;return d/60;}

// === calcNightHours ===
function calcNightHours(vao, ra, nightStart, nightEnd){
  const v = pGio(vao), r = pGio(ra);
  const dur = ((r - v + 1440) % 1440);
  const ns = nightStart * 60, ne = (nightEnd + 24) * 60; // normalize
  // Simple approximation: count overlap with night window
  let nightMin = 0;
  for(let m = 0; m < dur; m++){
    const cur = (v + m) % 1440;
    const inNight = (cur >= ns) || (cur < nightEnd*60);
    if(inNight) nightMin++;
  }
  return Math.min(nightMin / 60, dur / 60);
}

// === getPayrollRule ===
function getPayrollRule(){
  const base = PAYROLL_RULES[langCfg.payrollCountry] || PAYROLL_RULES.VN;
  const ov = langCfg.overrides || {};
  return {
    ...base,
    normalFactor: parseFloat(ov.normal)||base.normalFactor,
    otFactor: parseFloat(ov.ot)||base.otFactor,
    nightFactor: parseFloat(ov.night)||base.nightFactor,
    nightStart: parseInt(ov.nightStart)||base.nightStart,
  };
}

// === calcDaySalaryFull ===
function calcDaySalaryFull(tt,ca,gd,rule,otGio,nightGio){
const isDem=ca&&ca.laDem;
const lN=ldN(),lG=lgN(),gioCA=(_cfg_shim&&_cfg_shim.gioNgay)||8;
const nightPct=(rule.nightFactor||1.3)-1.0;
let nightTien=0;
if(rule.nightIsAdditive){nightTien=nightGio*lG*rule.nightFactor;}
else{nightTien=nightGio*lG*nightPct;}
let otTien=0;
if(langCfg.payrollCountry==='TW'){
  const ot1=Math.min(otGio,rule.ot1Hours||2);
  const ot2=Math.min(Math.max(0,otGio-(rule.ot1Hours||2)),rule.ot2Hours||2);
  otTien=(ot1*lG*(rule.ot1Factor||1.33))+(ot2*lG*(rule.ot2Factor||1.67));
}else{
  otTien=otGio*lG*(rule.otFactor||1.5);
}
if(tt==='ll') return lN*(rule.holidayFactor||4.0)+nightTien+otTien;
if(tt==='vang') return -lN;
return lN+nightTien+otTien;
}

// === tinhBH ===
const TRAN_BH = 46800000;
function tinhBH(b,v){const bb=Math.min(b,TRAN_BH);const bt=Math.min(b,20*v);return{bhxh:bb*.08,bhyt:bb*.015,bhtn:bt*.01,tong:bb*.08+bb*.015+bt*.01};}

// === tinhTNCN ===
function tinhTNCN(t){if(t<=0)return 0;let thue=0,con=t;for(const[s,r]of[[10e6,.05],[30e6,.10],[40e6,.20],[20e6,.30],[Infinity,.35]]){const c=Math.min(con,s);thue+=c*r;con-=c;if(con<=0)break;}return Math.max(0,thue);}


// Sync langCfg with userData country selection
function syncLangCfg(){
  langCfg.payrollCountry = userData.country || 'VN';
  langCfg.lang = userData.lang || 'vi';
  try{localStorage.setItem('cp22_lang', JSON.stringify(langCfg));}catch(e){}
}

// cfg shim so v21 functions work
function buildCfgShim(){
  return {
    luong: userData.salary || 0,
    luongNgay: 0,
    kieu: 'thang',
    ngayCong: userData.ngc || 26,
    gioNgay: userData.hoursPerShift || 8,
    npt: 0,
    vung: 5310000,
    dsCa: [],
  };
}

// Shims so calcDaySalaryFull can call ldN/lgN/cfg
let _cfg_shim = {luong:0,ngayCong:26,gioNgay:8,kieu:'thang'};
function ldN(){return (_cfg_shim.luong||0)/(_cfg_shim.ngayCong||26);}
function lgN(){return ldN()/(_cfg_shim.gioNgay||8);}
function fmtFull(n){return Math.round(n).toLocaleString('vi-VN')+' ₫';}
/* ==================== DATA ==================== */
let userData={name:'',job:'',company:'',shifts:1,hoursPerShift:8,lang:'vi',country:'VN',salary:0,ngc:26};
let attData={};// key: 'YYYY-M-D' → {type:'cm'|'vang'|'np'|'ll', in:'HH:MM', out:'HH:MM'}
let apCfg={color:0,avtB64:'',bgB64:'',bgGrad:'',calSun:'#E8433A',calSat:'#2D7DD2',calNorm:'#1A2332'};
let notifCfg={n1:true,n2:true,n3:false,n4:false};
let calView={y:new Date().getFullYear(),m:new Date().getMonth()};
let setupShifts=1,setupHours=8,ngcVal=22;
let obPage=1;
let obLang='vi',obCountry='VN';

const LANGS=[
  {id:'vi',flag:'🇻🇳',name:'Tiếng Việt'},
  {id:'en',flag:'🇺🇸',name:'English'},
  {id:'ko',flag:'🇰🇷',name:'한국어'},
  {id:'ja',flag:'🇯🇵',name:'日本語'},
  {id:'zh',flag:'🇨🇳',name:'中文'},
  {id:'my',flag:'🇲🇲',name:'မြန်မာ'},
];
const COUNTRIES=[
  {id:'VN',flag:'🇻🇳',name:'Việt Nam',rule:'OT ×1.5, Đêm +30%'},
  {id:'KR',flag:'🇰🇷',name:'한국',rule:'OT ×1.5, 야간 +50%'},
  {id:'JP',flag:'🇯🇵',name:'日本',rule:'OT ×1.25, 深夜 +25%'},
  {id:'TW',flag:'🇹🇼',name:'台灣',rule:'OT ×1.33/1.67'},
  {id:'US',flag:'🇺🇸',name:'United States',rule:'OT ×1.5 (FLSA)'},
  {id:'MY',flag:'🇲🇲',name:'Myanmar',rule:'OT ×2.0'},
];
const THEMES=[
  {bg:'#0D9E75',lt:'#E0F5EE',name:'Xanh lá'},
  {bg:'#2D7DD2',lt:'#EEF4FF',name:'Xanh dương'},
  {bg:'#7B5EA7',lt:'#F5F0FF',name:'Tím'},
  {bg:'#E8433A',lt:'#FFF0EF',name:'Đỏ'},
  {bg:'#F5A623',lt:'#FFF8E8',name:'Vàng'},
  {bg:'#1A2332',lt:'#F0F2F5',name:'Đen'},
];
let DAYS=window._DAYS_SHORT||['CN','T2','T3','T4','T5','T6','T7'];
let MONTHS=window._MONTHS||['Tháng 1','Tháng 2','Tháng 3','Tháng 4','Tháng 5','Tháng 6','Tháng 7','Tháng 8','Tháng 9','Tháng 10','Tháng 11','Tháng 12'];

/* ==================== LOAD/SAVE ==================== */
function loadData(){
  try{
    const u=localStorage.getItem('cp22_user');if(u)userData=Object.assign(userData,JSON.parse(u));
    const a=localStorage.getItem('cp22_att');if(a)attData=JSON.parse(a);
    const ap=localStorage.getItem('cp22_ap');if(ap)apCfg=Object.assign(apCfg,JSON.parse(ap));
    const n=localStorage.getItem('cp22_notif');if(n)notifCfg=Object.assign(notifCfg,JSON.parse(n));
  }catch(e){}
}
function saveUser(){try{localStorage.setItem('cp22_user',JSON.stringify(userData));}catch(e){}}
function saveAtt(){try{localStorage.setItem('cp22_att',JSON.stringify(attData));}catch(e){}}
function saveAp(){try{localStorage.setItem('cp22_ap',JSON.stringify(apCfg));}catch(e){}}
function saveNotif(){try{localStorage.setItem('cp22_notif',JSON.stringify(notifCfg));}catch(e){}}

/* ==================== ONBOARDING ==================== */
function renderOB(){
  const progress=document.getElementById('obProgress');
  const dots=progress.children;
  for(let i=0;i<4;i++){
    dots[i].className='ob-dot'+(i<obPage-1?' done':i===obPage-1?' active':'');
  }
  document.getElementById('obBtnBack').style.opacity=obPage===1?'0.3':'1';
  // Use lang selected in onboarding (obLang), fallback to TRAN.vi
  const t=TRAN[obLang]||TRAN.vi;
  // Update onboarding header with selected language
  const obAppNameEl=document.getElementById('obAppName');
  if(obAppNameEl)obAppNameEl.textContent=t.appName||'Chấm Công Pro';
  const obSkipEl=document.getElementById('obSkipBtn');
  if(obSkipEl)obSkipEl.textContent=({vi:'Bỏ qua',en:'Skip',ko:'건너뛰기',ja:'スキップ',zh:'跳过',my:'ကျော်'}[obLang]||'Bỏ qua');
  const body=document.getElementById('obBody');
  const nextBtn=document.getElementById('obBtnNext');
  if(obPage===1){
    const [titleLine1,titleLine2]=(t.obLang||'Chào mừng! 👋\nChọn ngôn ngữ').split('\n');
    body.innerHTML=`
      <div class="ob-title">${titleLine1}<br>${titleLine2||''}</div>
      <div class="ob-sub">${t.obLangSub||''}</div>
      <div class="lang-grid" id="obLangGrid"></div>
      <div style="height:8px"></div>
      <div class="ob-title" style="font-size:20px;margin-top:8px">${t.obShiftCountry||'Quốc gia làm việc'}</div>
      <div class="country-grid" id="obCountryGrid"></div>
    `;
    renderLangGrid('obLangGrid',obLang,id=>{obLang=id;renderOB();});
    renderCountryGrid('obCountryGrid',obCountry,id=>{obCountry=id;renderOB();});
    if(nextBtn)nextBtn.textContent=(t.obNext||'Tiếp theo →');
  }else if(obPage===2){
    body.innerHTML=`
      <div class="ob-title">${t.obUser||'Thông tin của bạn 👤'}</div>
      <div class="ob-sub">${t.obUserSub||''}</div>
      <div class="field-group">
        <div>
          <div class="field-label">${t.obName||'Họ và tên'}</div>
          <input class="field-input" id="ob2Name" placeholder="${t.obNameP||'Nguyễn Văn A'}" value="${userData.name||''}">
        </div>
        <div>
          <div class="field-label">${t.obJob||'Chức vụ / Công việc'}</div>
          <input class="field-input" id="ob2Job" placeholder="${t.obJobP||'Nhân viên...'}" value="${userData.job||''}">
        </div>
        <div>
          <div class="field-label">${t.obCo||'Tên công ty'}</div>
          <input class="field-input" id="ob2Co" placeholder="${t.obCoP||'Công ty ABC'}" value="${userData.company||''}">
        </div>
      </div>
    `;
    if(nextBtn)nextBtn.textContent=(t.obNext||'Tiếp theo →');
  }else if(obPage===3){
    body.innerHTML=`
      <div class="ob-title">${t.obShift||'Lịch làm việc ⏰'}</div>
      <div class="ob-sub">${t.obShiftSub||''}</div>
      <div class="field-label">${t.obShiftNum||'Số ca làm việc'}</div>
      <div class="num-grid" id="ob3ShiftGrid" style="margin-bottom:16px">
        <div class="num-btn${setupShifts===1?' sel':''}" onclick="selShift(1,this)">1</div>
        <div class="num-btn${setupShifts===2?' sel':''}" onclick="selShift(2,this)">2</div>
        <div class="num-btn${setupShifts===3?' sel':''}" onclick="selShift(3,this)">3</div>
        <div class="num-btn${setupShifts===4?' sel':''}" onclick="selShift(4,this)">4</div>
      </div>
      <div class="field-label">${t.obHours||'Số giờ mỗi ca'}</div>
      <div class="num-grid" style="grid-template-columns:repeat(5,1fr);margin-bottom:16px" id="ob3HoursGrid">
        <div class="num-btn${setupHours===6?' sel':''}" onclick="selHours(6,this)">6h</div>
        <div class="num-btn${setupHours===7?' sel':''}" onclick="selHours(7,this)">7h</div>
        <div class="num-btn${setupHours===8?' sel':''}" onclick="selHours(8,this)">8h</div>
        <div class="num-btn${setupHours===10?' sel':''}" onclick="selHours(10,this)">10h</div>
        <div class="num-btn${setupHours===12?' sel':''}" onclick="selHours(12,this)">12h</div>
      </div>
    `;
    if(nextBtn)nextBtn.textContent=(t.obNext||'Tiếp theo →');
  }else if(obPage===4){
    const shifts=setupShifts;
    const defaultTimes=[{in:'06:00',out:'14:00'},{in:'14:00',out:'22:00'},{in:'22:00',out:'06:00'},{in:'00:00',out:'08:00'}];
    const nightLbl={vi:'Ca đêm',en:'Night shift',ko:'야간',ja:'夜勤',zh:'夜班',my:'ညဆင်း'}[obLang]||'Ca đêm';
    const shiftLbl={vi:'Ca',en:'Shift',ko:'교대',ja:'シフト',zh:'班',my:'ဆင်း'}[obLang]||'Ca';
    const inLbl=t.dpInTime||'Vào ca'; const outLbl=t.dpOutTime||'Hết ca';
    let shiftCards='';
    for(let i=0;i<shifts;i++){
      const ti=defaultTimes[i]||{in:'08:00',out:'17:00'};
      shiftCards+=`
        <div class="shift-card">
          <div class="shift-card-head">
            <div class="shift-label">${shiftLbl} ${i+1}</div>
            <div class="shift-night" style="${i>=2?'':'opacity:.4'}">🌙 ${nightLbl}</div>
          </div>
          <div class="time-row">
            <div><div class="field-label">${inLbl}</div><input class="time-inp" id="sIn${i}" type="time" value="${ti.in}"></div>
            <div class="time-sep">→</div>
            <div><div class="field-label">${outLbl}</div><input class="time-inp" id="sOut${i}" type="time" value="${ti.out}"></div>
          </div>
        </div>`;
    }
    const weekLbl=t.obWeeks||'Số tuần một vòng';
    const weekNames=['1','2','3','4'].map(w=>{
      const wLabels={vi:'tuần',en:'wk',ko:'주',ja:'週',zh:'周',my:'ပတ်'};
      return w+' '+(wLabels[obLang]||'tuần');
    });
    body.innerHTML=`
      <div class="ob-title">${t.obTime||'Giờ giấc ca làm 🕐'}</div>
      <div class="ob-sub">${t.obTimeSub||''}</div>
      <div class="field-label">${weekLbl}</div>
      <div class="week-grid" style="margin-bottom:16px" id="ob4WeekGrid">
        ${weekNames.map((w,i)=>`<div class="week-btn${i===0?' sel':''}" onclick="this.parentElement.querySelectorAll('.week-btn').forEach(b=>b.classList.remove('sel'));this.classList.add('sel')">${w}</div>`).join('')}
      </div>
      ${shiftCards}
    `;
    if(nextBtn)nextBtn.textContent=(t.obStart||'Bắt đầu dùng app ✓');
  }
  // Also update Back button
  const backBtn=document.getElementById('obBtnBack');
  if(backBtn)backBtn.textContent=(t.obBack||'←');
}

function renderLangGrid(elId,selLang,onSel){
  const el=document.getElementById(elId);if(!el)return;
  el.innerHTML=LANGS.map(l=>`
    <div class="lang-item${l.id===selLang?' sel':''}" onclick="(${onSel.toString()})('${l.id}')">
      <span class="flag">${l.flag}</span>
      <span class="lname">${l.name}</span>
    </div>`).join('');
}
function renderCountryGrid(elId,selC,onSel){
  const el=document.getElementById(elId);if(!el)return;
  el.innerHTML=COUNTRIES.map(c=>`
    <div class="country-item${c.id===selC?' sel':''}" onclick="(${onSel.toString()})('${c.id}')">
      <span class="cflag">${c.flag}</span>
      <div><div class="cname">${c.name}</div><div class="crule">${c.rule}</div></div>
    </div>`).join('');
}

function obNext(){
  if(obPage===1){
    userData.lang=obLang;userData.country=obCountry;syncLangCfg();
  }else if(obPage===2){
    const n=document.getElementById('ob2Name')?.value.trim();
    const j=document.getElementById('ob2Job')?.value.trim();
    const c=document.getElementById('ob2Co')?.value.trim();
    if(!n){alert('Vui lòng nhập họ và tên!');return;}
    userData.name=n;userData.job=j;userData.company=c;
  }else if(obPage===3){
    userData.shifts=setupShifts;userData.hoursPerShift=setupHours;
  }else if(obPage===4){
    saveUser();
    goScreen('screenHome');
    initHome();
    applyI18n();
    setTimeout(moSplash, 600);
    return;
  }
  obPage=Math.min(4,obPage+1);
  renderOB();
}
function obBack(){
  if(obPage===1)return;
  obPage=Math.max(1,obPage-1);
  renderOB();
}
function skipOB(){
  userData.name='Người dùng';userData.job='Nhân viên';
  saveUser();goScreen('screenHome');initHome();
}

function selShift(n,el){
  setupShifts=n;
  el.parentElement.querySelectorAll('.num-btn').forEach(b=>b.classList.remove('sel'));
  el.classList.add('sel');
}
function selHours(h,el){
  setupHours=h;userData.hoursPerShift=h;
  el.parentElement.querySelectorAll('.num-btn').forEach(b=>b.classList.remove('sel'));
  el.classList.add('sel');
}
function selNgc(n,el){
  ngcVal=n;userData.ngc=n;
  el.parentElement.querySelectorAll('.num-btn').forEach(b=>b.classList.remove('sel'));
  el.classList.add('sel');
}

/* ==================== SCREEN NAV ==================== */
function goScreen(id){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  if(id==='screenHome')renderHomeStats();
  if(id==='screenCal'){renderCalBig();setTimeout(applyCalBg,50);}
}

/* ==================== PANELS ==================== */
function openPanel(id){
  document.getElementById(id).classList.add('open');
  if(id==='panelAppearance'){renderColorGrid();renderGradientGrid();updateBgPreview();syncAppearancePickers();}
  if(id==='panelExcel')renderExcelPreview();
  if(id==='panelSalary'){calcSalary();}
  if(id==='panelLang'){
    renderLangGrid('settingsLangGrid',userData.lang,selLangSetting);
  }
  if(id==='panelCountry'){
    renderCountryGrid('settingsCountryGrid',userData.country,selCountrySetting);
  }
  if(id==='panelSetup'){
    document.getElementById('setupName').value=userData.name||'';
    document.getElementById('setupJob').value=userData.job||'';
    document.getElementById('setupCo').value=userData.company||'';
  }
}
function closePanel(id){
  document.getElementById(id).classList.remove('open');
}
document.querySelectorAll('.panel-overlay').forEach(p=>{
  p.addEventListener('click',e=>{if(e.target===p)p.classList.remove('open');});
});

function selLangSetting(id){
  userData.lang=id;saveUser();syncLangCfg();
  document.getElementById('siLangSub').textContent=LANGS.find(l=>l.id===id)?.name||id;
  renderLangGrid('settingsLangGrid',id,selLangSetting);
  applyI18n();
  closePanel('panelLang');
}
function selCountrySetting(id){
  userData.country=id;saveUser();syncLangCfg();
  document.getElementById('siCountrySub').textContent=COUNTRIES.find(c=>c.id===id)?.name||id;
  renderCountryGrid('settingsCountryGrid',id,selCountrySetting);
  renderHomeStats();
}

function saveSetup(){
  userData.name=document.getElementById('setupName').value.trim()||userData.name;
  userData.job=document.getElementById('setupJob').value.trim()||userData.job;
  userData.company=document.getElementById('setupCo').value.trim()||userData.company;
  saveUser();initHome();closePanel('panelSetup');
}

/* ==================== CLOCK ==================== */
function updateClock(){
  const now=new Date();
  const h=String(now.getHours()).padStart(2,'0');
  const min=String(now.getMinutes()).padStart(2,'0');
  document.getElementById('clockTime').textContent=`${h}:${min}`;
  const days=(window._DAYS&&window._DAYS.length===7)?[...window._DAYS]:['Chủ nhật','Thứ 2','Thứ 3','Thứ 4','Thứ 5','Thứ 6','Thứ 7'];
  document.getElementById('clockDate').textContent=`${days[now.getDay()]}, ${now.getDate()}/${now.getMonth()+1}/${now.getFullYear()}`;
  document.getElementById('clockDay').textContent=now.getDate();
  document.getElementById('clockMonth').textContent=`${MONTHS[now.getMonth()]}, ${now.getFullYear()}`;
}
setInterval(updateClock,1000);

/* ==================== CHECKIN ==================== */
function todayKey(){const n=new Date();return`${n.getFullYear()}-${n.getMonth()}-${n.getDate()}`;}
function fmtTime(d){return`${String(d.getHours()).padStart(2,'0')}:${String(d.getMinutes()).padStart(2,'0')}`;}

function doCheckin(){
  const k=todayKey();
  const t=fmtTime(new Date());
  if(!attData[k])attData[k]={type:'cm'};
  attData[k].in=t;attData[k].type='cm';
  saveAtt();
  // Ripple
  addRipple('rippleIn');
  document.getElementById('lastIn').textContent=`Vào lúc ${t}`;
  document.getElementById('todayStatus').textContent=`✓ Vào ca ${t}`;
  document.getElementById('todayStatus').className='status-pill in';
  renderHomeStats();
}
function doCheckout(){
  const k=todayKey();
  const t=fmtTime(new Date());
  if(!attData[k])attData[k]={type:'cm'};
  attData[k].out=t;
  saveAtt();
  addRipple('rippleOut');
  document.getElementById('lastOut').textContent=`Ra lúc ${t}`;
  if(attData[k].in){
    const inP=timeToMin(attData[k].in),outP=timeToMin(t);
    const dur=((outP-inP+1440)%1440)/60;
    document.getElementById('todayStatus').textContent=`⏱ ${dur.toFixed(1)}h làm việc`;
  }
  document.getElementById('todayStatus').className='status-pill out';
  renderHomeStats();
}
function timeToMin(s){const[h,m]=s.split(':').map(Number);return h*60+m;}
function addRipple(id){
  const el=document.getElementById(id);
  if(!el)return;
  const c=document.createElement('div');
  c.className='ripple-circle';
  el.appendChild(c);
  setTimeout(()=>c.remove(),700);
}

/* ==================== HOME STATS ==================== */
function initHome(){
  applyI18n();
  document.getElementById('homeUname').textContent=userData.name||'Người dùng';
  document.getElementById('homeUjob').textContent=(userData.job||'Nhân viên')+(userData.company?` · ${userData.company}`:'');
  if(apCfg.avtB64){
    document.getElementById('homeAvt').innerHTML=`<img src="${apCfg.avtB64}">`;
  }
  applyTheme(apCfg.color||0);
  applyCalColors();
  renderHomeStats();
  updateClock();
  // restore today status
  const k=todayKey();
  if(attData[k]){
    if(attData[k].in)document.getElementById('lastIn').textContent=`Vào lúc ${attData[k].in}`;
    if(attData[k].out)document.getElementById('lastOut').textContent=`Ra lúc ${attData[k].out}`;
    const lbl=attData[k].in?`✓ Vào ca ${attData[k].in}`:'Đã ghi nhận';
    document.getElementById('todayStatus').textContent=lbl;
    document.getElementById('todayStatus').className='status-pill in';
  }
  // salary
  if(userData.salary){
    document.getElementById('salaryInput').value=userData.salary;
    calcSalary();
  }
}

function renderHomeStats(){
  const _tl=TRAN[userData.lang||'vi']||TRAN.vi;
  const now=new Date();
  const y=now.getFullYear(),m=now.getMonth();
  let cm=0,v=0,np=0,totalH=0;
  const daysInMonth=new Date(y,m+1,0).getDate();
  for(let d=1;d<=daysInMonth;d++){
    const k=`${y}-${m}-${d}`;
    const rec=attData[k];
    if(!rec)continue;
    if(rec.type==='cm')cm++;
    else if(rec.type==='vang')v++;
    else if(rec.type==='np')np++;
    if(rec.in&&rec.out){
      const h=soGio(rec.in,rec.out)||0;
      totalH+=h;
    }else if(rec.type==='cm'){
      totalH+=userData.hoursPerShift||8;
    }
  }
  const ot=Math.max(0,totalH-176);
  document.getElementById('statCM').textContent=cm;
  document.getElementById('statV').textContent=v;
  document.getElementById('statNP').textContent=np;
  document.getElementById('statOT').textContent=ot>0?`${ot.toFixed(0)}h`:'0h';
  // meter
  document.getElementById('meterHours').textContent=`${totalH.toFixed(0)}h`;
  const maxH=260;
  const pct=Math.min(100,totalH/maxH*100);
  const fill=document.getElementById('meterFill');
  let fillColor='linear-gradient(90deg,#0D9E75,#40E0D0)';
  let badgeTxt=_tl.binhThuong||'Bình thường',badgeBg='#E0F5EE',badgeFg='#0a7d5c';
  if(totalH>220){fillColor='linear-gradient(90deg,#0D9E75,#F5A623,#E8433A)';badgeTxt=_tl.quaSuc||'Quá sức 🔥';badgeBg='#FFF0EF';badgeFg='#E8433A';}
  else if(totalH>176){fillColor='linear-gradient(90deg,#0D9E75,#F5A623)';badgeTxt=_tl.chamChi||'Chăm chỉ ⚡';badgeBg='#FFF8E8';badgeFg='#cc8800';}
  fill.style.width=`${Math.max(2,pct)}%`;
  fill.style.background=fillColor;
  const mb=document.getElementById('meterBadge');
  if(mb){mb.textContent=badgeTxt;mb.style.background=badgeBg;mb.style.color=badgeFg;}
  // salary
  calcSalary();
}

/* ==================== SALARY ==================== */
function calcSalary(){
  const raw=parseFloat(document.getElementById('salaryInput')?.value)||userData.salary||0;
  userData.salary=raw;
  // Update cfg shim for v21 engine
  _cfg_shim={luong:raw,ngayCong:userData.ngc||26,gioNgay:userData.hoursPerShift||8,kieu:'thang',vung:5310000};
  syncLangCfg();
  const rule=getPayrollRule();
  const now=new Date();const y=now.getFullYear(),m=now.getMonth();
  const daysInMonth=new Date(y,m+1,0).getDate();
  const lN=ldN();const lG=lgN();const gioCA=userData.hoursPerShift||8;
  let cm=0,np=0,v=0,ll=0,nightDays=0,tongGop=0,tongOT=0;
  for(let d=1;d<=daysInMonth;d++){
    const rec=attData[`${y}-${m}-${d}`];
    if(!rec)continue;
    const nl=gNL(y,m,d);
    const sg=rec.in&&rec.out?soGio(rec.in,rec.out):gioCA;
    const otGio=Math.max(0,(sg||gioCA)-gioCA);
    let nightGio=0;
    if(rec.in&&rec.out)nightGio=calcNightHours(rec.in,rec.out,rule.nightStart,rule.nightEnd);
    const nightPct=(rule.nightFactor||1.3)-1.0;
    const nightTien=rule.nightIsAdditive?nightGio*lG*rule.nightFactor:nightGio*lG*nightPct;
    let otTien=0;
    if(langCfg.payrollCountry==='TW'){
      const ot1=Math.min(otGio,rule.ot1Hours||2);
      const ot2=Math.min(Math.max(0,otGio-(rule.ot1Hours||2)),rule.ot2Hours||2);
      otTien=(ot1*lG*(rule.ot1Factor||1.33))+(ot2*lG*(rule.ot2Factor||1.67));
    }else{otTien=otGio*lG*(rule.otFactor||1.5);}
    if(rec.type==='cm'){cm++;tongGop+=lN+nightTien+otTien;tongOT+=otTien;if(nightGio>1)nightDays++;}
    else if(rec.type==='np'){np++;tongGop+=lN;}
    else if(rec.type==='vang'){v++;tongGop-=lN;}
    else if(rec.type==='ll'){ll++;tongGop+=lN*(rule.holidayFactor||4.0)+nightTien+otTien;}
  }
  const bh=tinhBH(raw,_cfg_shim.vung||5310000);
  const tntt=Math.max(0,tongGop-bh.tong-15500000);
  const thue=tinhTNCN(tntt);
  const pr=PAYROLL_RULES[langCfg.payrollCountry]||PAYROLL_RULES.VN;
  const isVN=langCfg.payrollCountry==='VN';

  // Insurance & tax only applies fully to VN; other countries use simplified rates
  let bhTong=0,thueTong=0;
  if(isVN){
    bhTong=bh.tong;
    thueTong=thue;
  } else {
    // Simplified: social insurance ~10% of gross (generic), no local tax calc
    bhTong=tongGop*0.1;
    thueTong=0; // Local tax varies, not computed here
  }
  const net=Math.max(0,tongGop-bhTong-thueTong);
  const cur=pr.currency||'₫';
  const fmtN=n=>{
    if(isVN) return Math.round(n).toLocaleString('vi-VN')+'₫';
    const sym=pr.currency||'';
    return sym+(Math.round(n)).toLocaleString();
  };
  const bd=document.getElementById('salaryBreakdown');
  if(bd){
    bd.innerHTML=
      `<strong>${pr.flag} ${pr.name}</strong> · ${pr.basis}<br>`+
      `Có mặt: ${cm} ngày × ${fmtN(lN)} = <strong>${fmtN(cm*lN)}</strong><br>`+
      (nightDays>0?`Ca đêm (${nightDays} ngày, +${Math.round((rule.nightFactor-1)*100)}%) = <strong style="color:#7B5EA7">+${fmtN(nightDays*lG*gioCA*(rule.nightFactor-1))}</strong><br>`:'')+ 
      (tongOT>0?`Tăng ca (×${rule.otFactor||1.5}): <strong style="color:#F5A623">+${fmtN(tongOT)}</strong><br>`:'')+ 
      (np>0?`Nghỉ phép: ${np} ngày = <strong>${fmtN(np*lN)}</strong><br>`:'')+ 
      (v>0?`Vắng: -${v} ngày = <strong style="color:#E8433A">-${fmtN(v*lN)}</strong><br>`:'')+ 
      (ll>0?`Làm ngày lễ: ${ll} ngày × ${rule.holidayFactor||4} = <strong style="color:#2D7DD2">${fmtN(ll*lN*(rule.holidayFactor||4))}</strong><br>`:'')+
      (isVN
        ? `Bảo hiểm (BHXH+BHYT+BHTN): <strong style="color:#E8433A">-${fmtN(bhTong)}</strong>`+
          (thueTong>0?`<br>Thuế TNCN: <strong style="color:#E8433A">-${fmtN(thueTong)}</strong>`:'')
        : `Bảo hiểm xã hội (≈10%): <strong style="color:#E8433A">-${fmtN(bhTong)}</strong><br><span style="font-size:11px;color:var(--text3)">Thuế thu nhập: tính theo quy định địa phương</span>`);
  }
  const netEl=document.getElementById('salaryNet');
  if(netEl)netEl.textContent=fmtN(net);
  const amtEl=document.getElementById('salaryAmount');
  if(amtEl)amtEl.textContent=fmtN(tongGop>0?tongGop:0);
  const detEl=document.getElementById('salaryDetail');
  if(detEl)detEl.textContent=raw?`${cm} ngày có mặt | ${pr.flag} ${pr.name} | Thực nhận ≈ ${fmtN(net)}`:'Nhập thông tin lương để tính tự động';
  saveUser();
}

/* ==================== CALENDAR BIG ==================== */
function renderCalBig(){
  const {y,m}=calView;
  document.getElementById('calBigMonth').textContent=`${MONTHS[m]} ${y}`;
  document.getElementById('calScreenSub').textContent=`${MONTHS[m]}, ${y}`;
  const grid=document.getElementById('calBigDays');
  grid.innerHTML='';
  const fd=new Date(y,m,1).getDay();
  const nd=new Date(y,m+1,0).getDate();
  const hn=new Date();
  for(let i=0;i<fd;i++){const d=document.createElement('div');d.className='cal-day empty';grid.appendChild(d);}
  for(let g=1;g<=nd;g++){
    const thu=(fd+g-1)%7;
    const k=`${y}-${m}-${g}`;
    const rec=attData[k];
    const isToday=g===hn.getDate()&&m===hn.getMonth()&&y===hn.getFullYear();
    const nl=gNL(y,m,g);
    let cls='cal-day';
    if(thu===0)cls+=' sun';if(thu===6)cls+=' sat';
    if(isToday)cls+=' today';
    else if(rec){
      if(rec.type==='cm')cls+=' cm';
      else if(rec.type==='vang')cls+=' vang';
      else if(rec.type==='np')cls+=' np';
      else if(rec.type==='ll')cls+=' ll';
    }else if(nl&&!rec){cls+=' le';}
    else if(thu===0||thu===6){cls+=' ct';}
    const d=document.createElement('div');
    d.className=cls;
    d.innerHTML=`${g}${(rec||nl)?'<div class="day-dot"></div>':''}`;
    d.onclick=()=>dayTap(g);
    grid.appendChild(d);
  }
  // Day list
  renderCalDayList();
  // Re-apply background after days rendered
  requestAnimationFrame(()=>requestAnimationFrame(applyCalBg));
}
function calChange(dir){calView.m+=dir;if(calView.m>11){calView.m=0;calView.y++;}if(calView.m<0){calView.m=11;calView.y--;}renderCalBig();}
function renderCalDayList(){
  const {y,m}=calView;const nd=new Date(y,m+1,0).getDate();
  const hn=new Date();const list=document.getElementById('calDayList');
  list.innerHTML='';
  const STATUS={cm:{label:'Có mặt',color:'#0a7d5c',bg:'#E0F5EE'},vang:{label:'Vắng mặt',color:'#E8433A',bg:'#FFF0EF'},np:{label:'Nghỉ phép',color:'#cc8800',bg:'#FFF8E8'},ll:{label:'Làm ngày lễ',color:'#2D7DD2',bg:'#EEF4FF'}};
  let count=0;
  for(let g=nd;g>=1&&count<10;g--){
    const k=`${y}-${m}-${g}`;const rec=attData[k];
    if(!rec)continue;count++;
    const s=STATUS[rec.type]||{label:'?',color:'#999',bg:'#F0F0F0'};
    const dur=rec.in&&rec.out?`${rec.in}–${rec.out}`:rec.in?`Vào ${rec.in}`:'';
    const el=document.createElement('div');
    el.style.cssText='display:flex;align-items:center;justify-content:space-between;background:white;border-radius:12px;padding:12px 14px;margin-bottom:8px;box-shadow:0 2px 8px rgba(0,0,0,.05)';
    el.innerHTML=`<div><div style="font-size:14px;font-weight:700">${DAYS[(new Date(y,m,g).getDay())]} ${g}/${m+1}</div><div style="font-size:12px;color:var(--text3);margin-top:2px">${dur}</div></div><div style="padding:5px 12px;border-radius:10px;background:${s.bg};color:${s.color};font-size:12px;font-weight:700">${s.label}</div>`;
    list.appendChild(el);
  }
  if(count===0){list.innerHTML='<div class="empty-state"><div class="empty-icon">📅</div><div class="empty-txt">Chưa có dữ liệu tháng này</div></div>';}
}
function dayTap(g){const {y,m}=calView;openDayPanel(g,y,m);}

/* ==================== EXCEL ==================== */
function renderExcelPreview(){
  const {y,m}=calView;
  const nd=new Date(y,m+1,0).getDate();
  const STATUS={cm:'Có mặt',vang:'Vắng mặt',np:'Nghỉ phép',ll:'Làm ngày lễ'};
  const CLS={cm:'cm',vang:'vg',np:'',ll:''};
  let rows='<div class="excel-row head"><div class="excel-cell">Ngày</div><div class="excel-cell">Thứ</div><div class="excel-cell">Trạng thái</div><div class="excel-cell">Vào</div><div class="excel-cell">Ra</div></div>';
  let count=0;
  for(let g=1;g<=nd&&count<8;g++){
    const k=`${y}-${m}-${g}`;const rec=attData[k];if(!rec)continue;count++;
    const thu=DAYS[new Date(y,m,g).getDay()];
    const lbl=STATUS[rec.type]||rec.type;
    const cls=CLS[rec.type]||'';
    rows+=`<div class="excel-row"><div class="excel-cell">${g}/${m+1}</div><div class="excel-cell">${thu}</div><div class="excel-cell ${cls}">${lbl}</div><div class="excel-cell">${rec.in||''}</div><div class="excel-cell">${rec.out||''}</div></div>`;
  }
  if(count===0)rows+='<div style="padding:16px;text-align:center;color:var(--text3);font-size:13px">Chưa có dữ liệu</div>';
  document.getElementById('excelPreview').innerHTML=rows;
}
function doExport(){
  const {y,m}=calView;const nd=new Date(y,m+1,0).getDate();
  const STATUS={cm:'Có mặt',vang:'Vắng mặt',np:'Nghỉ phép',ll:'Làm ngày lễ'};
  let csv='Ngày,Thứ,Trạng thái,Giờ vào,Giờ ra,Số giờ\n';
  for(let g=1;g<=nd;g++){
    const k=`${y}-${m}-${g}`;const rec=attData[k];
    const thu=DAYS[new Date(y,m,g).getDay()];
    const lbl=rec?STATUS[rec.type]||'':'';
    const ins=rec?.in||'',outs=rec?.out||'';
    let dur='';
    if(ins&&outs)dur=(((timeToMin(outs)-timeToMin(ins)+1440)%1440)/60).toFixed(1);
    csv+=`${g}/${m+1}/${y},${thu},${lbl},${ins},${outs},${dur}\n`;
  }
  const blob=new Blob(['\uFEFF'+csv],{type:'text/csv;charset=utf-8'});
  const url=URL.createObjectURL(blob);
  const a=document.createElement('a');a.href=url;
  a.download=`ChamCong_${MONTHS[m]}_${y}.csv`;
  document.body.appendChild(a);a.click();
  setTimeout(()=>{document.body.removeChild(a);URL.revokeObjectURL(url);},300);
  closePanel('panelExcel');
}

/* ==================== APPEARANCE ==================== */
function renderColorGrid(){
  const grid=document.getElementById('colorGrid');
  grid.innerHTML=THEMES.map((t,i)=>`
    <div class="color-dot${apCfg.color===i?' sel':''}" style="background:${t.bg}" onclick="selColor(${i})" title="${t.name}"></div>
  `).join('');
}
function selColor(i){
  apCfg.color=i;saveAp();applyTheme(i);renderColorGrid();
}
function applyTheme(i){
  const t=THEMES[i]||THEMES[0];
  let st=document.getElementById('dynTheme');
  if(!st){st=document.createElement('style');st.id='dynTheme';document.head.appendChild(st);}
  st.textContent=`:root{--ac:${t.bg};--ac2:${t.bg};--ac-lt:${t.lt};}`;
}
async function uploadAvt(inp){
  if(!inp.files[0])return;
  const fr=new FileReader();
  fr.onload=e=>{
    apCfg.avtB64=e.target.result;saveAp();
    document.getElementById('apAvtPrev').innerHTML=`<img src="${e.target.result}">`;
    document.getElementById('homeAvt').innerHTML=`<img src="${e.target.result}">`;
  };
  fr.readAsDataURL(inp.files[0]);
}
const GRADIENTS=[
  {id:'none',label:'Không',css:'',preview:'#F4F7F6'},
  {id:'g1',label:'Bình minh',css:'linear-gradient(135deg,#f9a825,#e91e63)'},
  {id:'g2',label:'Biển',css:'linear-gradient(135deg,#0288d1,#26c6da)'},
  {id:'g3',label:'Rừng',css:'linear-gradient(135deg,#1b5e20,#66bb6a)'},
  {id:'g4',label:'Hoàng hôn',css:'linear-gradient(135deg,#ff6f00,#ad1457)'},
  {id:'g5',label:'Tím',css:'linear-gradient(135deg,#4a148c,#e91e63)'},
  {id:'g6',label:'Mint',css:'linear-gradient(135deg,#00695c,#80cbc4)'},
  {id:'g7',label:'Đêm',css:'linear-gradient(135deg,#1a1a2e,#16213e,#0f3460)'},
  {id:'g8',label:'Hồng',css:'linear-gradient(135deg,#f06292,#fff9c4)'},
];

function renderGradientGrid(){
  const grid=document.getElementById('gradientGrid');
  if(!grid)return;
  grid.innerHTML=GRADIENTS.map(g=>{
    const isSel=(!apCfg.bgB64&&apCfg.bgGrad===g.css)||(g.id==='none'&&!apCfg.bgB64&&!apCfg.bgGrad);
    const preview=g.css||g.preview;
    return`<div onclick="selectGradient('${g.id}','${g.css.replace(/'/g,"\\'")}')" style="width:52px;height:40px;border-radius:10px;cursor:pointer;border:3px solid ${isSel?'var(--text)':'transparent'};background:${preview};transition:all .15s;position:relative;overflow:hidden;display:flex;align-items:center;justify-content:center" title="${g.label}">${g.id==='none'?'<span style="font-size:16px">✕</span>':''}</div>`;
  }).join('');
}

function selectGradient(id,css){
  apCfg.bgGrad=css;
  if(id==='none'){apCfg.bgGrad='';apCfg.bgB64='';}
  saveAp();applyCalBg();renderGradientGrid();updateBgPreview();
}

function applyCalBg(){
  const wrap=document.getElementById('calBigWrap');
  if(!wrap) return; // not on calendar screen yet

  if(apCfg.bgB64){
    // Photo background
    wrap.setAttribute('style',
      `margin:0 16px;margin-top:-54px;border-radius:20px;overflow:hidden;` +
      `box-shadow:var(--shadow);position:relative;z-index:2;` +
      `background-image:url(${apCfg.bgB64});` +
      `background-size:cover;background-position:center top;` +
      `background-color:#333`
    );
    _applyCalTextWhite(true);
  } else if(apCfg.bgGrad){
    // Gradient background
    wrap.setAttribute('style',
      `margin:0 16px;margin-top:-54px;border-radius:20px;overflow:hidden;` +
      `box-shadow:var(--shadow);position:relative;z-index:2;` +
      `background:${apCfg.bgGrad}`
    );
    _applyCalTextWhite(true);
  } else {
    // Default white
    wrap.setAttribute('style',
      `margin:0 16px;margin-top:-54px;border-radius:20px;overflow:hidden;` +
      `box-shadow:var(--shadow);position:relative;z-index:2;background:white`
    );
    _applyCalTextWhite(false);
  }
}

function _applyCalTextWhite(white){
  const month=document.getElementById('calBigMonth');
  const dow=document.getElementById('calDow');
  const prev=document.getElementById('calNavPrev');
  const next=document.getElementById('calNavNext');
  if(!month&&!dow)return; // calendar not rendered yet, skip
  if(white){
    if(month) month.style.cssText='color:white;text-shadow:0 1px 6px rgba(0,0,0,.5)';
    if(dow) dow.querySelectorAll('span').forEach(s=>{
      s.style.color='rgba(255,255,255,.9)';s.style.textShadow='0 1px 4px rgba(0,0,0,.6)';
    });
    if(prev) prev.style.cssText='width:32px;height:32px;border-radius:50%;border:1.5px solid rgba(255,255,255,.5);background:rgba(255,255,255,.2);display:flex;align-items:center;justify-content:center;cursor:pointer;font-size:16px;font-weight:700;color:white;backdrop-filter:blur(4px)';
    if(next) next.style.cssText='width:32px;height:32px;border-radius:50%;border:1.5px solid rgba(255,255,255,.5);background:rgba(255,255,255,.2);display:flex;align-items:center;justify-content:center;cursor:pointer;font-size:16px;font-weight:700;color:white;backdrop-filter:blur(4px)';
    document.querySelectorAll('#calBigDays .cal-day').forEach(d=>{
      if(!d.classList.contains('today')&&!d.classList.contains('cm')&&
         !d.classList.contains('vang')&&!d.classList.contains('np')&&
         !d.classList.contains('ll')&&!d.classList.contains('empty')){
        d.style.background='rgba(255,255,255,.2)';
        d.style.color='white';
        d.style.textShadow='0 1px 3px rgba(0,0,0,.5)';
      }
    });
  } else {
    if(month) month.style.cssText='';
    if(dow) dow.querySelectorAll('span').forEach(s=>{s.style.cssText='';});
    if(prev) prev.style.cssText='';
    if(next) next.style.cssText='';
    document.querySelectorAll('#calBigDays .cal-day').forEach(d=>{
      d.style.background='';d.style.color='';d.style.textShadow='';
    });
  }
}

function updateBgPreview(){
  const prev=document.getElementById('apBgPreview');
  const txt=document.getElementById('apBgPreviewTxt');
  if(!prev)return;
  if(apCfg.bgB64){
    prev.style.backgroundImage=`url(${apCfg.bgB64})`;
    prev.style.backgroundSize='cover';prev.style.backgroundPosition='center';
    if(txt)txt.style.display='none';
  }else if(apCfg.bgGrad){
    prev.style.backgroundImage='';prev.style.background=apCfg.bgGrad;
    if(txt){txt.style.display='';txt.textContent='Màu gradient';txt.style.color='white';}
  }else{
    prev.style.backgroundImage='';prev.style.background='#F4F7F6';
    if(txt){txt.style.display='';txt.textContent='Chưa có ảnh nền';txt.style.color='var(--text3)';}
  }
}

async function uploadBg(inp){
  if(!inp.files[0])return;
  const fr=new FileReader();
  fr.onload=e=>{
    apCfg.bgB64=e.target.result;apCfg.bgGrad='';
    saveAp();applyCalBg();updateBgPreview();renderGradientGrid();
  };
  fr.readAsDataURL(inp.files[0]);
}
function clearBg(){apCfg.bgB64='';apCfg.bgGrad='';saveAp();applyCalBg();updateBgPreview();renderGradientGrid();}

/* ========== CALENDAR TEXT COLORS ========== */
function onCalColorChange(){
  const sun=document.getElementById('sunColorPick')?.value||'#E8433A';
  const sat=document.getElementById('satColorPick')?.value||'#2D7DD2';
  const norm=document.getElementById('normColorPick')?.value||'#1A2332';
  const sd=document.getElementById('sunColorShow');if(sd)sd.style.background=sun;
  const satd=document.getElementById('satColorShow');if(satd)satd.style.background=sat;
  const nd=document.getElementById('normColorShow');if(nd)nd.style.background=norm;
  const she=document.getElementById('sunColorHex');if(she)she.textContent=sun;
  const sathe=document.getElementById('satColorHex');if(sathe)sathe.textContent=sat;
  const nhe=document.getElementById('normColorHex');if(nhe)nhe.textContent=norm;
  const ps=document.getElementById('previewSun');if(ps)ps.style.color=sun;
  const psat=document.getElementById('previewSat');if(psat)psat.style.color=sat;
}
function resetCalColors(){
  const sp=document.getElementById('sunColorPick');if(sp)sp.value='#E8433A';
  const satp=document.getElementById('satColorPick');if(satp)satp.value='#2D7DD2';
  const np=document.getElementById('normColorPick');if(np)np.value='#1A2332';
  onCalColorChange();
}
function saveAppearance(){
  apCfg.calSun=document.getElementById('sunColorPick')?.value||'#E8433A';
  apCfg.calSat=document.getElementById('satColorPick')?.value||'#2D7DD2';
  apCfg.calNorm=document.getElementById('normColorPick')?.value||'#1A2332';
  saveAp();applyCalColors();renderCalBig();closePanel('panelAppearance');
}
function applyCalColors(){
  let st=document.getElementById('dynCalColors');
  if(!st){st=document.createElement('style');st.id='dynCalColors';document.head.appendChild(st);}
  const sun=apCfg.calSun||'#E8433A';
  const sat=apCfg.calSat||'#2D7DD2';
  const norm=apCfg.calNorm||'#1A2332';
  st.textContent=`
    .cal-dow .sun{color:${sun}!important}
    .cal-dow .sat{color:${sat}!important}
    .cal-day.sun:not(.today):not(.cm):not(.vang):not(.np):not(.ll):not(.le){color:${sun}!important}
    .cal-day.sat:not(.today):not(.cm):not(.vang):not(.np):not(.ll):not(.le){color:${sat}!important}
    .cal-day:not(.sun):not(.sat):not(.today):not(.cm):not(.vang):not(.np):not(.ll):not(.empty):not(.ct):not(.le){color:${norm}!important}
  `;
}
function syncAppearancePickers(){
  const sp=document.getElementById('sunColorPick');if(sp)sp.value=apCfg.calSun||'#E8433A';
  const satp=document.getElementById('satColorPick');if(satp)satp.value=apCfg.calSat||'#2D7DD2';
  const np=document.getElementById('normColorPick');if(np)np.value=apCfg.calNorm||'#1A2332';
  onCalColorChange();
}

/* ==================== NOTIFICATIONS ==================== */
function togNotif(id){
  const el=document.getElementById(id);
  el.classList.toggle('on');
  const key=id.replace('togN','n');
  notifCfg[key]=el.classList.contains('on');
  saveNotif();
}

/* ==================== GPS GEOFENCING ==================== */
let _gpsWatch=null;
let _gpsData={lat:null,lng:null,radius:100,enabled:false};
let _gpsWasInside=null;

function loadGpsData(){
  try{const g=JSON.parse(localStorage.getItem('cp22_gps')||'null');if(g)_gpsData=Object.assign(_gpsData,g);}catch(e){}
}
function saveGpsData(){
  try{localStorage.setItem('cp22_gps',JSON.stringify(_gpsData));}catch(e){}
}

function togGPS(btn){
  btn.classList.toggle('on');
  _gpsData.enabled=btn.classList.contains('on');
  notifCfg.n3=_gpsData.enabled;
  saveNotif();saveGpsData();
  const card=document.getElementById('gpsSetupCard');
  card.style.display=_gpsData.enabled?'block':'none';
  if(_gpsData.enabled){
    updateGpsStatus();
    if(_gpsData.lat)startGeofencing();
  } else {
    stopGeofencing();
  }
}

function gpsRequestPermission(){
  const permGuide=document.getElementById('gpsPermGuide');
  const manualBox=document.getElementById('gpsManualBox');
  if(!navigator.geolocation){
    if(permGuide)permGuide.style.display='block';
    if(manualBox)manualBox.style.display='block';
    return;
  }
  // Try GPS first
  if(navigator.permissions){
    navigator.permissions.query({name:'geolocation'}).then(result=>{
      if(result.state==='denied'){
        if(permGuide)permGuide.style.display='block';
        if(manualBox)manualBox.style.display='block';
      } else {
        gpsGetCurrentPos();
      }
    }).catch(()=>gpsGetCurrentPos());
  } else {
    gpsGetCurrentPos();
  }
}

function gpsShowHostGuide(){
  const g=document.getElementById('gpsHostGuide');
  if(g)g.style.display=g.style.display==='none'?'block':'none';
  return false;
}

function gpsSaveManual(){
  const lat=parseFloat(document.getElementById('gpsManualLat')?.value);
  const lng=parseFloat(document.getElementById('gpsManualLng')?.value);
  if(isNaN(lat)||isNaN(lng)||lat<-90||lat>90||lng<-180||lng>180){
    showGpsBanner('Tọa độ không hợp lệ. Kiểm tra lại.','#E8433A');
    return;
  }
  _gpsData.lat=lat;
  _gpsData.lng=lng;
  _gpsData.radius=parseInt(document.getElementById('gpsRadius')?.value)||100;
  saveGpsData();
  updateGpsStatus();
  // Now try to start geofencing with GPS
  startGeofencing();
  showGpsBanner('✅ Đã lưu vị trí công ty!','#0D9E75');
  document.getElementById('gpsPermGuide').style.display='none';
}

function gpsGetCurrentPos(){
  const statusTxt=document.getElementById('gpsStatusTxt');
  const statusDot=document.getElementById('gpsStatusDot');
  const permGuide=document.getElementById('gpsPermGuide');
  if(!navigator.geolocation){
    if(statusTxt)statusTxt.textContent='Thiết bị không hỗ trợ GPS';
    if(statusDot)statusDot.style.background='#E8433A';
    return;
  }
  if(statusTxt)statusTxt.textContent='⏳ Đang lấy vị trí...';
  if(statusDot)statusDot.style.background='#F5A623';
  navigator.geolocation.getCurrentPosition(
    pos=>{
      _gpsData.lat=pos.coords.latitude;
      _gpsData.lng=pos.coords.longitude;
      _gpsData.radius=parseInt(document.getElementById('gpsRadius')?.value)||100;
      saveGpsData();
      updateGpsStatus();
      startGeofencing();
      if(permGuide)permGuide.style.display='none';
    },
    err=>{
      const msgs={
        1:'GPS bị từ chối. Vui lòng cấp quyền trong trình duyệt.',
        2:'Không xác định được vị trí. Thử lại ở nơi thoáng hơn.',
        3:'Hết thời gian. Thử lại.'
      };
      if(statusTxt)statusTxt.textContent=msgs[err.code]||'Lỗi GPS';
      if(statusDot)statusDot.style.background='#E8433A';
      if(err.code===1&&permGuide){
        permGuide.style.display='block';
        const mb=document.getElementById('gpsManualBox');
        if(mb)mb.style.display='block';
      }
    },
    {enableHighAccuracy:true,timeout:15000,maximumAge:0}
  );
}

function gpsClear(){
  stopGeofencing();
  _gpsData.lat=null;_gpsData.lng=null;
  _gpsData.enabled=false;
  saveGpsData();
  const btn=document.getElementById('togN3');
  if(btn)btn.classList.remove('on');
  notifCfg.n3=false;saveNotif();
  document.getElementById('gpsSetupCard').style.display='none';
  updateGpsStatus();
}

function updateGpsStatus(){
  const statusTxt=document.getElementById('gpsStatusTxt');
  const statusDot=document.getElementById('gpsStatusDot');
  const coordsBox=document.getElementById('gpsCoordsBox');
  const coordsTxt=document.getElementById('gpsCoordsText');
  if(!statusTxt)return;
  if(_gpsData.lat&&_gpsData.lng){
    statusTxt.textContent=_gpsWasInside===true?'🟢 Đang trong khu vực công ty':_gpsWasInside===false?'🔴 Ngoài khu vực công ty':'✅ Đã lưu vị trí công ty';
    statusDot.style.background=_gpsWasInside===true?'#0D9E75':_gpsWasInside===false?'#E8433A':'#F5A623';
    coordsBox.style.display='block';
    coordsTxt.innerHTML=`Lat: ${_gpsData.lat.toFixed(6)}<br>Lng: ${_gpsData.lng.toFixed(6)}<br>Bán kính: ${_gpsData.radius}m`;
  } else {
    statusTxt.textContent='Chưa thiết lập vị trí công ty';
    statusDot.style.background='#ccc';
    coordsBox.style.display='none';
  }
}

function gpsDistance(lat1,lng1,lat2,lng2){
  const R=6371000;
  const dLat=(lat2-lat1)*Math.PI/180;
  const dLng=(lng2-lng1)*Math.PI/180;
  const a=Math.sin(dLat/2)*Math.sin(dLat/2)+
    Math.cos(lat1*Math.PI/180)*Math.cos(lat2*Math.PI/180)*
    Math.sin(dLng/2)*Math.sin(dLng/2);
  return R*2*Math.atan2(Math.sqrt(a),Math.sqrt(1-a));
}

function startGeofencing(){
  stopGeofencing();
  if(!navigator.geolocation||!_gpsData.lat)return;
  _gpsWatch=navigator.geolocation.watchPosition(
    pos=>{
      if(!_gpsData.lat)return;
      const dist=gpsDistance(pos.coords.latitude,pos.coords.longitude,_gpsData.lat,_gpsData.lng);
      const inside=dist<=_gpsData.radius;
      // Trigger on state change
      if(_gpsWasInside===null){_gpsWasInside=inside;updateGpsStatus();return;}
      if(inside&&!_gpsWasInside){
        // Entered zone → check in
        _gpsWasInside=true;
        updateGpsStatus();
        gpsAutoCheckin();
      } else if(!inside&&_gpsWasInside){
        // Left zone → check out
        _gpsWasInside=false;
        updateGpsStatus();
        gpsAutoCheckout();
      }
    },
    err=>console.log('GPS watch error:',err.code),
    {enableHighAccuracy:true,maximumAge:30000,timeout:15000}
  );
}

function stopGeofencing(){
  if(_gpsWatch!==null){
    navigator.geolocation.clearWatch(_gpsWatch);
    _gpsWatch=null;
  }
  _gpsWasInside=null;
}

function gpsAutoCheckin(){
  const t=new Date();
  const k=`${t.getFullYear()}-${t.getMonth()}-${t.getDate()}`;
  if(!attData[k])attData[k]={};
  if(!attData[k].in){
    const hm=`${String(t.getHours()).padStart(2,'0')}:${String(t.getMinutes()).padStart(2,'0')}`;
    attData[k].type='cm';
    attData[k].in=hm;
    saveAtt();
    renderHomeStats();
    const el=document.getElementById('lastIn');if(el)el.textContent='GPS: Vào lúc '+hm;
    const sd=document.getElementById('todayStatus');if(sd){sd.textContent='📍 GPS vào ca '+hm;sd.className='status-pill in';}
    // Show notification banner
    showGpsBanner('📍 Chấm công vào ca tự động: '+hm,'#0D9E75');
  }
}

function gpsAutoCheckout(){
  const t=new Date();
  const k=`${t.getFullYear()}-${t.getMonth()}-${t.getDate()}`;
  if(attData[k]&&attData[k].in&&!attData[k].out){
    const hm=`${String(t.getHours()).padStart(2,'0')}:${String(t.getMinutes()).padStart(2,'0')}`;
    attData[k].out=hm;
    saveAtt();
    renderHomeStats();
    const el=document.getElementById('lastOut');if(el)el.textContent='GPS: Ra lúc '+hm;
    showGpsBanner('📍 Kết thúc ca tự động: '+hm,'#E8433A');
  }
}

function showGpsBanner(msg,color){
  let banner=document.getElementById('gpsBanner');
  if(!banner){
    banner=document.createElement('div');
    banner.id='gpsBanner';
    banner.style.cssText='position:fixed;top:16px;left:50%;transform:translateX(-50%);z-index:9999;padding:12px 20px;border-radius:12px;font-size:13px;font-weight:700;font-family:Nunito,sans-serif;color:white;box-shadow:0 4px 20px rgba(0,0,0,.25);transition:opacity .4s;max-width:320px;text-align:center;pointer-events:none';
    document.body.appendChild(banner);
  }
  banner.textContent=msg;
  banner.style.background=color||'#0D9E75';
  banner.style.opacity='1';
  setTimeout(()=>{banner.style.opacity='0';},4000);
}

/* ==================== CONFIRM RESET ==================== */
function confirmReset(){
  openPanel('panelConfirmReset');
}
function doReset(){
  ['cp22_user','cp22_att','cp22_ap','cp22_notif','cp22_lang'].forEach(k=>localStorage.removeItem(k));
  location.reload();
}

/* ========== DAY DETAIL PANEL ========== */
const TT_CFG=[{id:'cm',ten:'Có mặt',sub:'Đi làm đúng ca',bg:'#1D9E75',svgC:'#0F6E56',bgI:'#E1F5EE',sel:'s-cm'},{id:'np',ten:'Nghỉ phép',sub:'Có hưởng lương',bg:'#EF9F27',svgC:'#633806',bgI:'#FAEEDA',sel:'s-np'},{id:'vang',ten:'Vắng mặt',sub:'Không phép — trừ lương',bg:'#E24B4A',svgC:'#791F1F',bgI:'#FCEBEB',sel:'s-vang'},{id:'ll',ten:'Làm ngày lễ',sub:'Tính 400%',bg:'#378ADD',svgC:'#0C447C',bgI:'#E6F1FB',sel:'s-ll'}];
const ICONS={cm:`<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" width="13" height="13"><path d="M5 13l4 4L19 7"/></svg>`,np:`<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" width="13" height="13"><path d="M3 12h4M17 12h4M12 3v4M12 17v4M6.3 6.3l2.8 2.8M14.9 14.9l2.8 2.8M6.3 17.7l2.8-2.8M14.9 9.1l2.8-2.8"/></svg>`,vang:`<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" width="13" height="13"><path d="M18 6L6 18M6 6l12 12"/></svg>`,ll:`<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" width="13" height="13"><path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"/></svg>`,dem:`<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" width="13" height="13"><path d="M12 3a6 6 0 009 9 9 9 0 11-9-9z"/></svg>`};

// Map v22 attData keys to v21 format
let _dayKey='', _daySelType=null, _dayCa=null;

const TT_COLORS={cm:'#0D9E75',np:'#F5A623',vang:'#E8433A',ll:'#2D7DD2'};
const TT_BG={cm:'#E0F5EE',np:'#FFF8E8',vang:'#FFF0EF',ll:'#EEF4FF'};
const TT_ICON={cm:'✓',np:'☀',vang:'✕',ll:'★'};
const DAY_STATUS_I18N={
  vi:{cm:{n:'Có mặt',s:'Đi làm đúng ca'},np:{n:'Nghỉ phép',s:'Có hưởng lương'},vang:{n:'Vắng mặt',s:'Không phép — trừ lương'},ll:{n:'Làm ngày lễ',s:'Tính theo luật'}},
  en:{cm:{n:'Present',s:'Worked the shift'},np:{n:'Leave',s:'Paid leave'},vang:{n:'Absent',s:'Unpaid absence'},ll:{n:'Holiday work',s:'By law'}},
  ko:{cm:{n:'출근',s:'정상 출근'},np:{n:'연차',s:'유급 휴가'},vang:{n:'결근',s:'무단 결근'},ll:{n:'휴일 근무',s:'법적 기준'}},
  ja:{cm:{n:'出勤',s:'通常出勤'},np:{n:'有給',s:'有給休暇'},vang:{n:'欠勤',s:'無断欠勤'},ll:{n:'休日出勤',s:'法定'}},
  zh:{cm:{n:'出勤',s:'正常出勤'},np:{n:'请假',s:'带薪假'},vang:{n:'缺勤',s:'无故缺勤'},ll:{n:'节假日',s:'按法律'}},
  my:{cm:{n:'တက်',s:'ပုံမှန်'},np:{n:'ခွင့်',s:'လစာပါ'},vang:{n:'ပျက်',s:'ခွင့်မဲ့'},ll:{n:'ရုံးပိတ်',s:'ဥပဒေ'}},
};
function getDayStatus(){return DAY_STATUS_I18N[userData.lang||'vi']||DAY_STATUS_I18N.vi;}

function openDayPanel(g, y, m) {
  const k = `${y}-${m}-${g}`;
  _dayKey = k;
  const rec = attData[k] || {};
  _daySelType = rec.type || null;

  // Title
  const now = new Date(y,m,g);
  const dayNames=['Chủ nhật','Thứ 2','Thứ 3','Thứ 4','Thứ 5','Thứ 6','Thứ 7'];
  document.getElementById('dayPanelTitle').textContent = `${dayNames[now.getDay()]}, ngày ${g}/${m+1}/${y}`;
  
  // Ca info (simple - show default if userData.shifts=1)
  const caEl = document.getElementById('dayPanelCa');
  if(userData.shifts >= 1) {
    caEl.textContent = `Ca: Ca hành chính (08:00 – 17:00)`;
    caEl.style.display = 'block';
    _dayCa = {vao:'08:00', ra:'17:00'};
  } else {
    caEl.style.display = 'none';
    _dayCa = null;
  }

  // Time inputs
  document.getElementById('dayTimeIn').value = rec.in || (userData.shifts >= 1 ? '08:00' : '');
  document.getElementById('dayTimeOut').value = rec.out || (userData.shifts >= 1 ? '17:00' : '');
  
  // Note
  document.getElementById('dayNote').value = rec.note || '';
  
  // Status grid
  renderDayStatusGrid();
  
  // Show panel
  document.getElementById('panelDay').classList.add('open');
}

function renderDayStatusGrid() {
  const types = ['cm','np','vang','ll'];
  const grid = document.getElementById('dayStatusGrid');
  const _dst=getDayStatus();
  grid.innerHTML = types.map(id => {
    const sel = _daySelType === id;
    return `<button onclick="selectDayType('${id}')" style="border:2px solid ${sel?TT_COLORS[id]:'var(--border)'};border-radius:14px;padding:14px 8px;text-align:center;cursor:pointer;background:${sel?TT_BG[id]:'white'};transition:all .15s;font-family:Nunito,sans-serif">
      <div style="font-size:22px;width:32px;height:32px;border-radius:50%;background:${sel?TT_COLORS[id]:'#F0F0F0'};display:flex;align-items:center;justify-content:center;margin:0 auto 6px;color:${sel?'white':TT_COLORS[id]};font-weight:900">${TT_ICON[id]}</div>
      <div style="font-size:12px;font-weight:800;color:${sel?TT_COLORS[id]:'var(--text)'}">${_dst[id].n}</div>
      <div style="font-size:10px;color:var(--text3);margin-top:2px;line-height:1.3">${_dst[id].s}</div>
    </button>`;
  }).join('');
  
  // Show time block only for cm or ll
  const showTime = _daySelType === 'cm' || _daySelType === 'll';
  document.getElementById('dayTimeBlock').style.display = showTime ? 'block' : 'none';
  dayCalcHours();
}

function selectDayType(id) {
  _daySelType = _daySelType === id ? null : id;
  renderDayStatusGrid();
}

function dayResetTime() {
  if(_dayCa) {
    document.getElementById('dayTimeIn').value = _dayCa.vao;
    document.getElementById('dayTimeOut').value = _dayCa.ra;
    dayCalcHours();
  }
}

function dayCalcHours() {
  const inv = document.getElementById('dayTimeIn').value;
  const outv = document.getElementById('dayTimeOut').value;
  const el = document.getElementById('dayHoursSummary');
  if(inv && outv) {
    const dur = ((pGio(outv)-pGio(inv)+1440)%1440)/60;
    const gioCA = userData.hoursPerShift||8;
    const ot = Math.max(0,dur-gioCA);
    el.textContent = `Tổng: ${dur.toFixed(1)}h${ot>0?' | Tăng ca: +'+ot.toFixed(1)+'h':''}`;
    el.style.color = ot>0?'#F5A623':'var(--ac)';
  } else {
    el.textContent = '';
  }
}

function closeDayPanel() {
  document.getElementById('panelDay').classList.remove('open');
}

function saveDayPanel() {
  if(!_daySelType) {
    delete attData[_dayKey];
  } else {
    if(!attData[_dayKey]) attData[_dayKey] = {};
    attData[_dayKey].type = _daySelType;
    const inv = document.getElementById('dayTimeIn').value;
    const outv = document.getElementById('dayTimeOut').value;
    if((_daySelType==='cm'||_daySelType==='ll') && inv && outv) {
      attData[_dayKey].in = inv;
      attData[_dayKey].out = outv;
    } else {
      delete attData[_dayKey].in;
      delete attData[_dayKey].out;
    }
    const note = document.getElementById('dayNote').value.trim();
    if(note) attData[_dayKey].note = note;
    else delete attData[_dayKey].note;
  }
  saveAtt();
  closeDayPanel();
  renderCalBig();
  renderHomeStats();
}


/* ==================== SPLASH SCREEN (từ v21) ==================== */
const TEN_THANG=['Tháng 1','Tháng 2','Tháng 3','Tháng 4','Tháng 5','Tháng 6','Tháng 7','Tháng 8','Tháng 9','Tháng 10','Tháng 11','Tháng 12'];
const cauGD1=[
"Hành trình vạn dặm bắt đầu từ một bước chân nhỏ.",
"Cần cù bù thông minh — tục ngữ Việt Nam.",
"Bắt đầu là đã thành công một nửa rồi!",
"Siêng năng là cha của may mắn.",
"Chăm chỉ hôm nay, thanh thản ngày mai.",
"Đầu xuôi đuôi lọt — bắt đầu tốt, cả tháng tốt!",
"Gieo hạt hôm nay, gặt quả ngày mai.",
"Mỗi ngày đến làm là thêm một viên gạch xây tương lai.",
"Không gì khó, chỉ cần có quyết tâm từ bước đầu.",
"Mưa dầm thấm lâu — chăm chỉ ắt thành công.",
"Người siêng năng sẽ đứng trên người lười biếng.",
"Thắng không kiêu, bại không nản — ngày đầu cứ bền.",
"Tháng mới — trang mới — năng lượng mới — tiến thôi!",
"Đã bắt đầu thì phải bền, bền thì mới thắng.",
"Mỗi buổi sáng là một cơ hội mới để thay đổi cuộc đời.",
"Người không làm thì không ăn — tục ngữ.",
"Ngày hôm nay bạn làm là nền móng cho thành công tháng này!"
];
const cauGD2=[
"Công mài sắt có ngày nên kim — tục ngữ.",
"Nước chảy đá mòn — bạn đang thắng từng ngày!",
"Không có gì khó, chỉ sợ lòng không bền — Hồ Chí Minh.",
"Sự xuất sắc không phải là hành động mà là thói quen — Aristotle.",
"Tài năng không bằng sự kiên trì — Calvin Coolidge.",
"Kiên trì và nhẫn nại là hai người thầy vĩ đại nhất — Dickens.",
"Người chăm chỉ thắng người thông minh mà lười biếng.",
"Một tuần làm đầy đủ — ví đã ấm hơn rồi đấy!",
"Thất bại là mẹ thành công — nhưng bạn đang thành công rồi!",
"Ai ơi đã quyết thì hành, đã đi thì đến, đã làm thì xong.",
"Bạn đang chứng minh mình không phải người bỏ cuộc!",
"Bền gan vững chí mới thành, dao cùn mài mãi cũng sắc đi.",
"Nửa tháng rồi — tiếp tục phát huy nhé!",
"Hãy nhớ lý do bạn bắt đầu — nó vẫn còn nguyên vẹn!",
"Bạn đang xây dựng thói quen kỷ luật — thứ quý giá nhất!",
"Chí lớn ai cũng có, khó ở chỗ giữ được lâu dài.",
"Giữa chặng đường là lúc thử thách — bạn đang vượt qua tốt lắm!"
];
const cauGD3=[
"Sắp về đích rồi — bứt tốc nào!",
"Cuối tháng là lúc thành quả được quy ra tiền!",
"Người dũng cảm vẫn tiến dù mệt — Nelson Mandela.",
"Nước về biển lớn — lương về túi ta!",
"Dẻo dai mới thắng, bền chí mới nên — tục ngữ.",
"Bạn đã đi quá xa để dừng lại bây giờ!",
"Thành công là tổng những nỗ lực nhỏ mỗi ngày — R.Collier.",
"Sắp ngày lương — mồ hôi hôm nay thành nụ cười ngày mai!",
"Người làm đến cùng mới nếm hương vị của thành công.",
"Khi mệt nhất, hãy nhớ: cuối tháng là tài khoản rạng rỡ!",
"Mỗi giờ làm những ngày cuối đều đang tính thêm tiền!",
"Bạn đã chứng minh sự kiên trì suốt tháng này — tuyệt vời!",
"Vài ngày nữa thôi — đừng để nước rút mà nhụt chí!",
"Kết thúc tháng trong vinh quang, tháng sau bắt đầu mạnh hơn!",
"Tự hào về bản thân đi — bạn xứng đáng được như vậy!",
"Bạn đã làm điều tuyệt vời tháng này — hãy tự hào lên!"
];

const quotesI18N={
  en:['Hard work beats talent when talent does not work hard.','Every day is a new opportunity.','Success is the sum of small efforts repeated daily.','The secret of getting ahead is getting started.'],
  ko:['오늘도 최선을 다하세요!','작은 노력이 쌓여 큰 성과를 만듭니다.','시작이 반입니다. 잘하고 있어요!','꾸준함이 재능을 이깁니다.'],
  ja:['継続は力なり。今日も頑張りましょう！','小さな努力が大きな成果を生みます。','始めることが最初の一歩です。'],
  zh:['坚持就是胜利，今天也要加油！','积少成多，每天进步一点点。','今天的努力是明天成果的种子。'],
  my:['ကြိုးစားမှုသည်အောင်မြင်မှု၏သော့ချက်','တစ်နေ့တစ်နေ့တိုးတက်မှု','ကြိုးပမ်းသမျှ ရလဒ်ရမည်'],
};

function moSplash(){
  const now=new Date();
  const y=now.getFullYear(),m=now.getMonth();
  const nd=new Date(y,m,1).getDay();
  let tCM=0;
  for(let g=1;g<=now.getDate();g++){
    const thu=(nd+g-1)%7;
    if(thu===0||thu===6)continue;
    const rec=attData[y+'-'+m+'-'+g];
    if(rec&&(rec.type==='cm'||rec.type==='ll'))tCM++;
  }
  const isCL=false;
  const h=now.getHours();
  const L=userData.lang||'vi';
  const chaoMap={vi:h<12?'Chào buổi sáng':h<18?'Chào buổi chiều':'Chào buổi tối',en:h<12?'Good morning':h<18?'Good afternoon':'Good evening',ko:h<12?'좋은 아침이에요':h<18?'안녕하세요':'좋은 저녁이에요',ja:h<12?'おはようございます':h<18?'こんにちは':'こんばんは',zh:h<12?'早上好':h<18?'下午好':'晚上好',my:h<12?'မင်္ဂလာနံနက်ခင်း':h<18?'မင်္ဂလာနေ့ခင်း':'မင်္ဂလာညနေ'};
  const chao=chaoMap[L]||chaoMap.vi;
  const dvMap={vi:'ngày có mặt tháng này',en:'days present this month',ko:'이달 출근일',ja:'今月の出勤日数',zh:'本月出勤天数',my:'ဤလ တက်ရောက်ရက်'};
  const startMap={vi:'Bắt đầu ngày làm việc',en:'Start the workday',ko:'오늘 업무 시작',ja:'今日の業務を開始',zh:'开始今天的工作',my:'ယနေ့အလုပ်စတင်'};
  const _mths=(TRAN[obLang]||TRAN[userData.lang||'vi']||TRAN.vi).months||TEN_THANG;
  const monthLbl=(_mths[m]||('Tháng '+(m+1)))+' · '+y;
  const L2=userData.lang||'vi';
  const pool=L2!=='vi'&&quotesI18N[L2]?quotesI18N[L2]:(tCM<=7?cauGD1:tCM<=14?cauGD2:cauGD3);
  const cau=pool[Math.floor(Math.random()*pool.length)];

  // Fill splash content - with null guards
  const _s=(id,txt)=>{const el=document.getElementById(id);if(el)el.textContent=txt;};
  const _st=(id,prop,val)=>{const el=document.getElementById(id);if(el)el.style[prop]=val;};
  _s('spBadgeTxt',monthLbl);
  _s('spSo',String(tCM));
  _s('spDv',dvMap[L]||dvMap.vi);
  _s('spCau',chao+', '+(userData.name||'bạn')+'! '+cau);
  _s('spNut',startMap[L]||startMap.vi);
  _st('spNut','background','var(--ac)');
  _st('spDot','background','var(--ac)');
  _st('spBadge','background','var(--ac-lt)');
  _st('spBadgeTxt','color','var(--ac2)');
  _st('spSo','color','var(--ac)');

  const p=document.getElementById('splashBox');
  p.style.animation='none';p.offsetHeight;p.style.animation='pop-in .38s cubic-bezier(.34,1.56,.64,1) both';
  document.getElementById('splashOv').className='splash-ov mo';
}

function dongSplash(){
  document.getElementById('splashOv').className='splash-ov';
}

/* ==================== FULL i18n SYSTEM ==================== */
const TRAN = {
  vi:{
    appName:'Chấm Công Pro', appSub:'Chấm công thông minh · Lương đúng luật',
    vaoCA:'VÀO CA', hetCA:'HẾT CA',
    batDauCa:'Nhấn để bắt đầu ca', ketThucCa:'Nhấn khi kết thúc ca',
    chuaChamCong:'Chưa chấm công',
    gioLam:'Giờ làm tháng này',
    binhThuong:'Bình thường', chamChi:'Chăm chỉ ⚡', quaSuc:'Quá sức 🔥',
    coMat:'Có mặt', vang:'Vắng', nghiPhep:'Nghỉ phép', tangCa:'Tăng ca',
    chucNang:'Chức năng',
    lich:'Lịch', thietLap:'Thiết lập', giaoDien:'Giao diện', caiDat:'Cài đặt',
    luong:'Lương', xuatExcel:'Xuất Excel', thongBao:'Thông báo', huongDan:'Hướng dẫn',
    luongUocTinh:'💼 Lương ước tính tháng này',
    lichChamCong:'Lịch chấm công',
    chipCM:'✓ Có mặt', chipV:'✕ Vắng', chipNP:'☀ Nghỉ phép', chipLL:'★ Làm lễ',
    navHome:'Trang chủ', navLich:'Lịch', navLuong:'Lương', navCaiDat:'Cài đặt',
    // Settings screen
    settingsTitle:'Cài đặt',
    siLang:'Ngôn ngữ', siCountry:'Quốc gia làm việc',
    siSetup:'Thiết lập thông tin', siSetupSub:'Tên, chức vụ, ca làm việc',
    siNotif:'Cài đặt thông báo', siNotifSub:'Nhắc giờ làm, tự động chấm công',
    siAppear:'Chỉnh sửa giao diện', siAppearSub:'Màu sắc, ảnh đại diện, ảnh nền',
    siAbout:'Thông tin về app', siAboutSub:'Phiên bản 2.2.0',
    siHelp:'Hướng dẫn sử dụng', siHelpSub:'Cách dùng app hiệu quả',
    siDelete:'Xóa toàn bộ dữ liệu', siDeleteSub:'Không thể khôi phục',
    // Panels
    panelAppear:'⭐ Chỉnh sửa giao diện', panelNotif:'🔔 Cài đặt thông báo',
    panelSalary:'💰 Bảng lương', panelExcel:'📊 Xuất Excel',
    panelSetup:'📝 Thiết lập thông tin', panelHelp:'📖 Hướng dẫn sử dụng',
    panelAbout:'ℹ️ Về ứng dụng', panelLang:'🌐 Chọn ngôn ngữ',
    panelCountry:'🗺️ Quốc gia làm việc',
    closeBtn:'Đóng',
    // Onboarding
    obLang:'Chào mừng! 👋\nChọn ngôn ngữ', obLangSub:'Chọn ngôn ngữ và quốc gia bạn đang làm việc.',
    obUser:'Thông tin của bạn 👤', obUserSub:'Nhập thông tin cá nhân để cá nhân hóa app.',
    obShift:'Lịch làm việc ⏰', obShiftSub:'Bạn làm mấy ca? Mỗi ca mấy tiếng?',
    obTime:'Giờ giấc ca làm 🕐', obTimeSub:'Thiết lập giờ vào và hết ca cho từng ca.',
    obNext:'Tiếp theo →', obBack:'←', obStart:'Bắt đầu dùng app ✓',
    obName:'Họ và tên', obNameP:'Nguyễn Văn A',
    obJob:'Chức vụ / Công việc', obJobP:'Nhân viên / Công nhân...',
    obCo:'Tên công ty', obCoP:'Công ty ABC',
    obShiftNum:'Số ca làm việc', obHours:'Số giờ mỗi ca',
    obWeeks:'Số tuần một vòng',
    obShiftCountry:'Quốc gia làm việc',
    // Days and months
    days:['Chủ nhật','Thứ 2','Thứ 3','Thứ 4','Thứ 5','Thứ 6','Thứ 7'],
    daysShort:['CN','T2','T3','T4','T5','T6','T7'],
    months:['Tháng 1','Tháng 2','Tháng 3','Tháng 4','Tháng 5','Tháng 6','Tháng 7','Tháng 8','Tháng 9','Tháng 10','Tháng 11','Tháng 12'],
    // Salary panel
    salaryContract:'Lương hợp đồng / tháng', salaryDays:'Ngày công chuẩn / tháng',
    salaryEst:'Lương ước tính tháng này', salaryNet:'Thực nhận ước tính',
    salarySave:'✓ Lưu thông tin lương',
    // Day panel
    dpStatus:'TRẠNG THÁI', dpActual:'GIỜ THỰC TẾ', dpNote:'GHI CHÚ',
    dpReset:'Đặt lại theo ca', dpCancel:'Hủy bỏ', dpSave:'Lưu lại',
    dpTotalHours:'Tổng:', dpOT:'Tăng ca:',
    dpInTime:'Giờ vào', dpOutTime:'Giờ ra',
    dpNoteP:'Thêm ghi chú cho ngày này...',
    // Status labels
    stCM:'Có mặt', stCMSub:'Đi làm đúng ca',
    stNP:'Nghỉ phép', stNPSub:'Có hưởng lương',
    stV:'Vắng mặt', stVSub:'Không phép — trừ lương',
    stLL:'Làm ngày lễ', stLLSub:'Tính theo luật',
    // Splash
    spPresent:'ngày có mặt tháng này', spStart:'Bắt đầu ngày làm việc',
    // Reset
    resetTitle:'Xóa toàn bộ dữ liệu?',
    resetDesc:'Tất cả dữ liệu sẽ bị xóa vĩnh viễn. Không thể khôi phục!',
    resetCancel:'Hủy bỏ', resetOk:'🗑 Xóa hết',
    // Export
    exportPreview:'Xem trước dữ liệu xuất ra:',
    exportBtn:'📊 Xuất file Excel (.csv)',
    // Notif panel
    n1Name:'Nhắc trước giờ làm 30 phút', n1Desc:'Thông báo nhắc nhở trước ca bắt đầu',
    n2Name:'Xác nhận giờ nghỉ sau 30 phút', n2Desc:'Hỏi giờ tan ca thực tế sau khi hết ca',
    n3Name:'Chấm công tự động (GPS)', n3Desc:'Tự động ghi nhận khi vào/ra khu vực công ty',
    n4Name:'Nhắc cuối tuần tổng kết', n4Desc:'Xem tổng hợp tuần vào thứ 6 hàng tuần',
  },
  en:{
    appName:'Work Tracker Pro', appSub:'Smart attendance · Legal payroll',
    vaoCA:'CLOCK IN', hetCA:'CLOCK OUT',
    batDauCa:'Tap to start shift', ketThucCa:'Tap when shift ends',
    chuaChamCong:'Not checked in',
    gioLam:'Work hours this month',
    binhThuong:'Normal', chamChi:'Diligent ⚡', quaSuc:'Overworked 🔥',
    coMat:'Present', vang:'Absent', nghiPhep:'Leave', tangCa:'Overtime',
    chucNang:'Functions',
    lich:'Calendar', thietLap:'Setup', giaoDien:'Appearance', caiDat:'Settings',
    luong:'Salary', xuatExcel:'Export Excel', thongBao:'Notifications', huongDan:'Help',
    luongUocTinh:'💼 Estimated salary this month',
    lichChamCong:'Attendance Calendar',
    chipCM:'✓ Present', chipV:'✕ Absent', chipNP:'☀ Leave', chipLL:'★ Holiday work',
    navHome:'Home', navLich:'Calendar', navLuong:'Salary', navCaiDat:'Settings',
    settingsTitle:'Settings',
    siLang:'Language', siCountry:'Working country',
    siSetup:'Setup Info', siSetupSub:'Name, job, work shifts',
    siNotif:'Notifications', siNotifSub:'Work reminders, auto check-in',
    siAppear:'Appearance', siAppearSub:'Colors, avatar, background',
    siAbout:'About App', siAboutSub:'Version 2.2.0',
    siHelp:'User Guide', siHelpSub:'How to use the app effectively',
    siDelete:'Delete All Data', siDeleteSub:'Cannot be recovered',
    panelAppear:'⭐ Appearance', panelNotif:'🔔 Notifications',
    panelSalary:'💰 Salary', panelExcel:'📊 Export Excel',
    panelSetup:'📝 Setup Info', panelHelp:'📖 User Guide',
    panelAbout:'ℹ️ About App', panelLang:'🌐 Language',
    panelCountry:'🗺️ Working Country',
    closeBtn:'Close',
    obLang:'Welcome! 👋\nChoose Language', obLangSub:'Select your display language and working country.',
    obUser:'Your Info 👤', obUserSub:'Enter your info to personalize the app.',
    obShift:'Work Schedule ⏰', obShiftSub:'How many shifts? Hours per shift?',
    obTime:'Shift Hours 🕐', obTimeSub:'Set check-in and check-out times for each shift.',
    obNext:'Next →', obBack:'←', obStart:'Start Using App ✓',
    obName:'Full Name', obNameP:'John Smith',
    obJob:'Job Title', obJobP:'Employee / Worker...',
    obCo:'Company', obCoP:'Company ABC',
    obShiftNum:'Number of shifts', obHours:'Hours per shift',
    obWeeks:'Weeks per cycle',
    obShiftCountry:'Working country',
    days:['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday'],
    daysShort:['Sun','Mon','Tue','Wed','Thu','Fri','Sat'],
    months:['January','February','March','April','May','June','July','August','September','October','November','December'],
    salaryContract:'Contract salary / month', salaryDays:'Standard working days / month',
    salaryEst:'Estimated salary this month', salaryNet:'Estimated take-home pay',
    salarySave:'✓ Save salary info',
    dpStatus:'STATUS', dpActual:'ACTUAL HOURS', dpNote:'NOTE',
    dpReset:'Reset to shift', dpCancel:'Cancel', dpSave:'Save',
    dpTotalHours:'Total:', dpOT:'Overtime:',
    dpInTime:'Check-in', dpOutTime:'Check-out',
    dpNoteP:'Add a note for this day...',
    stCM:'Present', stCMSub:'Worked the full shift',
    stNP:'Leave', stNPSub:'Paid leave',
    stV:'Absent', stVSub:'Unpaid absence',
    stLL:'Holiday work', stLLSub:'By law',
    spPresent:'days present this month', spStart:'Start the workday',
    resetTitle:'Delete all data?',
    resetDesc:'All data will be permanently deleted. Cannot be recovered!',
    resetCancel:'Cancel', resetOk:'🗑 Delete All',
    exportPreview:'Preview data to export:',
    exportBtn:'📊 Export Excel (.csv)',
    n1Name:'Remind 30min before shift', n1Desc:'Notification before shift starts',
    n2Name:'Confirm break after 30min', n2Desc:'Ask for actual clock-out time',
    n3Name:'Auto check-in (GPS)', n3Desc:'Auto record when entering/leaving workplace',
    n4Name:'Weekly summary reminder', n4Desc:'View weekly summary every Friday',
  },
  ko:{
    appName:'근태관리 Pro', appSub:'스마트 출퇴근 · 법정 급여 계산',
    vaoCA:'출근', hetCA:'퇴근',
    batDauCa:'탭하여 출근 시작', ketThucCa:'퇴근 시 탭하세요',
    chuaChamCong:'미출근',
    gioLam:'이달 근무시간',
    binhThuong:'정상', chamChi:'열심히 ⚡', quaSuc:'과로 🔥',
    coMat:'출근', vang:'결근', nghiPhep:'연차', tangCa:'초과근무',
    chucNang:'기능',
    lich:'달력', thietLap:'설정', giaoDien:'테마', caiDat:'환경설정',
    luong:'급여', xuatExcel:'Excel 내보내기', thongBao:'알림', huongDan:'도움말',
    luongUocTinh:'💼 이달 예상 급여',
    lichChamCong:'근태 달력',
    chipCM:'✓ 출근', chipV:'✕ 결근', chipNP:'☀ 연차', chipLL:'★ 휴일근무',
    navHome:'홈', navLich:'달력', navLuong:'급여', navCaiDat:'설정',
    settingsTitle:'설정',
    siLang:'언어', siCountry:'근무 국가',
    siSetup:'정보 설정', siSetupSub:'이름, 직책, 교대근무',
    siNotif:'알림 설정', siNotifSub:'출근 알림, 자동 체크인',
    siAppear:'화면 꾸미기', siAppearSub:'색상, 아바타, 배경',
    siAbout:'앱 정보', siAboutSub:'버전 2.2.0',
    siHelp:'사용 가이드', siHelpSub:'앱을 효과적으로 사용하는 방법',
    siDelete:'모든 데이터 삭제', siDeleteSub:'복구 불가',
    panelAppear:'⭐ 화면 꾸미기', panelNotif:'🔔 알림 설정',
    panelSalary:'💰 급여 계산', panelExcel:'📊 Excel 내보내기',
    panelSetup:'📝 정보 설정', panelHelp:'📖 사용 가이드',
    panelAbout:'ℹ️ 앱 정보', panelLang:'🌐 언어 선택',
    panelCountry:'🗺️ 근무 국가',
    closeBtn:'닫기',
    obLang:'환영합니다! 👋\n언어 선택', obLangSub:'표시 언어와 근무 국가를 선택하세요.',
    obUser:'내 정보 👤', obUserSub:'앱 개인화를 위해 정보를 입력하세요.',
    obShift:'근무 일정 ⏰', obShiftSub:'몇 교대 근무? 한 교대당 시간은?',
    obTime:'교대 시간 🕐', obTimeSub:'각 교대의 출퇴근 시간을 설정하세요.',
    obNext:'다음 →', obBack:'←', obStart:'앱 사용 시작 ✓',
    obName:'성명', obNameP:'홍길동',
    obJob:'직책', obJobP:'직원 / 근로자...',
    obCo:'회사명', obCoP:'ABC 회사',
    obShiftNum:'교대 수', obHours:'교대당 시간',
    obWeeks:'주기당 주 수',
    obShiftCountry:'근무 국가',
    days:['일요일','월요일','화요일','수요일','목요일','금요일','토요일'],
    daysShort:['일','월','화','수','목','금','토'],
    months:['1월','2월','3월','4월','5월','6월','7월','8월','9월','10월','11월','12월'],
    salaryContract:'계약 급여 / 월', salaryDays:'월 기준 근무일수',
    salaryEst:'이달 예상 급여', salaryNet:'예상 실수령액',
    salarySave:'✓ 급여 정보 저장',
    dpStatus:'상태', dpActual:'실제 시간', dpNote:'메모',
    dpReset:'교대로 초기화', dpCancel:'취소', dpSave:'저장',
    dpTotalHours:'합계:', dpOT:'초과근무:',
    dpInTime:'출근 시간', dpOutTime:'퇴근 시간',
    dpNoteP:'이날의 메모를 추가하세요...',
    stCM:'출근', stCMSub:'정상 출근',
    stNP:'연차', stNPSub:'유급 휴가',
    stV:'결근', stVSub:'무단 결근',
    stLL:'휴일 근무', stLLSub:'법적 기준 적용',
    spPresent:'이달 출근일', spStart:'오늘 업무 시작',
    resetTitle:'모든 데이터를 삭제할까요?',
    resetDesc:'모든 데이터가 영구 삭제됩니다. 복구할 수 없습니다!',
    resetCancel:'취소', resetOk:'🗑 모두 삭제',
    exportPreview:'내보낼 데이터 미리보기:',
    exportBtn:'📊 Excel 파일 내보내기 (.csv)',
    n1Name:'출근 30분 전 알림', n1Desc:'교대 시작 전 알림',
    n2Name:'30분 후 퇴근 확인', n2Desc:'실제 퇴근 시간 확인',
    n3Name:'자동 체크인 (GPS)', n3Desc:'회사 구역 진입/이탈 시 자동 기록',
    n4Name:'주간 요약 알림', n4Desc:'매주 금요일 주간 요약 보기',
  },
  ja:{
    appName:'勤怠管理 Pro', appSub:'スマート出退勤 · 法定給与計算',
    vaoCA:'出勤', hetCA:'退勤',
    batDauCa:'タップして出勤', ketThucCa:'退勤時にタップ',
    chuaChamCong:'未打刻',
    gioLam:'今月の勤務時間',
    binhThuong:'通常', chamChi:'勤勉 ⚡', quaSuc:'過労 🔥',
    coMat:'出勤', vang:'欠勤', nghiPhep:'有給', tangCa:'残業',
    chucNang:'機能',
    lich:'カレンダー', thietLap:'設定', giaoDien:'外観', caiDat:'設定',
    luong:'給与', xuatExcel:'Excel出力', thongBao:'通知', huongDan:'ヘルプ',
    luongUocTinh:'💼 今月の給与見込み',
    lichChamCong:'勤怠カレンダー',
    chipCM:'✓ 出勤', chipV:'✕ 欠勤', chipNP:'☀ 有給', chipLL:'★ 休日出勤',
    navHome:'ホーム', navLich:'カレンダー', navLuong:'給与', navCaiDat:'設定',
    settingsTitle:'設定',
    siLang:'言語', siCountry:'勤務国',
    siSetup:'情報設定', siSetupSub:'氏名、職種、シフト',
    siNotif:'通知設定', siNotifSub:'出勤リマインダー、自動打刻',
    siAppear:'外観設定', siAppearSub:'色、アバター、背景',
    siAbout:'アプリ情報', siAboutSub:'バージョン 2.2.0',
    siHelp:'使用ガイド', siHelpSub:'アプリの効果的な使い方',
    siDelete:'全データ削除', siDeleteSub:'元に戻せません',
    panelAppear:'⭐ 外観設定', panelNotif:'🔔 通知設定',
    panelSalary:'💰 給与計算', panelExcel:'📊 Excel出力',
    panelSetup:'📝 情報設定', panelHelp:'📖 使用ガイド',
    panelAbout:'ℹ️ アプリ情報', panelLang:'🌐 言語選択',
    panelCountry:'🗺️ 勤務国',
    closeBtn:'閉じる',
    obLang:'ようこそ！ 👋\n言語選択', obLangSub:'表示言語と勤務国を選択してください。',
    obUser:'あなたの情報 👤', obUserSub:'アプリをパーソナライズするために情報を入力してください。',
    obShift:'勤務スケジュール ⏰', obShiftSub:'シフト数は？1シフトの時間は？',
    obTime:'シフト時間 🕐', obTimeSub:'各シフトの出退勤時間を設定してください。',
    obNext:'次へ →', obBack:'←', obStart:'アプリを開始 ✓',
    obName:'氏名', obNameP:'山田太郎',
    obJob:'職種', obJobP:'社員 / 作業員...',
    obCo:'会社名', obCoP:'ABC株式会社',
    obShiftNum:'シフト数', obHours:'1シフトの時間',
    obWeeks:'サイクル週数',
    obShiftCountry:'勤務国',
    days:['日曜日','月曜日','火曜日','水曜日','木曜日','金曜日','土曜日'],
    daysShort:['日','月','火','水','木','金','土'],
    months:['1月','2月','3月','4月','5月','6月','7月','8月','9月','10月','11月','12月'],
    salaryContract:'契約給与 / 月', salaryDays:'月間基準勤務日数',
    salaryEst:'今月の給与見込み', salaryNet:'手取り見込み',
    salarySave:'✓ 給与情報を保存',
    dpStatus:'状態', dpActual:'実際の時間', dpNote:'メモ',
    dpReset:'シフトに戻す', dpCancel:'キャンセル', dpSave:'保存',
    dpTotalHours:'合計:', dpOT:'残業:',
    dpInTime:'出勤時間', dpOutTime:'退勤時間',
    dpNoteP:'この日のメモを追加...',
    stCM:'出勤', stCMSub:'通常出勤',
    stNP:'有給', stNPSub:'有給休暇',
    stV:'欠勤', stVSub:'無断欠勤',
    stLL:'休日出勤', stLLSub:'法定基準適用',
    spPresent:'今月の出勤日数', spStart:'今日の業務を開始',
    resetTitle:'全データを削除しますか？',
    resetDesc:'全データが永久に削除されます。元に戻せません！',
    resetCancel:'キャンセル', resetOk:'🗑 全て削除',
    exportPreview:'エクスポートデータのプレビュー:',
    exportBtn:'📊 Excelファイルを出力 (.csv)',
    n1Name:'30分前出勤リマインダー', n1Desc:'シフト開始前の通知',
    n2Name:'30分後退勤確認', n2Desc:'実際の退勤時間を確認',
    n3Name:'自動打刻 (GPS)', n3Desc:'職場エリア入退場時に自動記録',
    n4Name:'週次サマリーリマインダー', n4Desc:'毎週金曜日に週次サマリーを表示',
  },
  zh:{
    appName:'考勤管理 Pro', appSub:'智能打卡 · 合规薪资计算',
    vaoCA:'上班打卡', hetCA:'下班打卡',
    batDauCa:'点击开始上班', ketThucCa:'下班时点击',
    chuaChamCong:'未打卡',
    gioLam:'本月工作时长',
    binhThuong:'正常', chamChi:'勤奋 ⚡', quaSuc:'过劳 🔥',
    coMat:'出勤', vang:'缺勤', nghiPhep:'请假', tangCa:'加班',
    chucNang:'功能',
    lich:'日历', thietLap:'设置', giaoDien:'外观', caiDat:'设置',
    luong:'薪资', xuatExcel:'导出Excel', thongBao:'通知', huongDan:'帮助',
    luongUocTinh:'💼 本月预计薪资',
    lichChamCong:'考勤日历',
    chipCM:'✓ 出勤', chipV:'✕ 缺勤', chipNP:'☀ 请假', chipLL:'★ 节假日工作',
    navHome:'主页', navLich:'日历', navLuong:'薪资', navCaiDat:'设置',
    settingsTitle:'设置',
    siLang:'语言', siCountry:'工作国家',
    siSetup:'信息设置', siSetupSub:'姓名、职位、班次',
    siNotif:'通知设置', siNotifSub:'上班提醒、自动打卡',
    siAppear:'外观设置', siAppearSub:'颜色、头像、背景',
    siAbout:'关于应用', siAboutSub:'版本 2.2.0',
    siHelp:'使用指南', siHelpSub:'如何高效使用应用',
    siDelete:'删除所有数据', siDeleteSub:'无法恢复',
    panelAppear:'⭐ 外观设置', panelNotif:'🔔 通知设置',
    panelSalary:'💰 薪资计算', panelExcel:'📊 导出Excel',
    panelSetup:'📝 信息设置', panelHelp:'📖 使用指南',
    panelAbout:'ℹ️ 关于应用', panelLang:'🌐 选择语言',
    panelCountry:'🗺️ 工作国家',
    closeBtn:'关闭',
    obLang:'欢迎！ 👋\n选择语言', obLangSub:'请选择显示语言和工作国家。',
    obUser:'您的信息 👤', obUserSub:'请输入个人信息以个性化应用。',
    obShift:'工作安排 ⏰', obShiftSub:'几个班次？每班多少小时？',
    obTime:'班次时间 🕐', obTimeSub:'为每个班次设置上下班时间。',
    obNext:'下一步 →', obBack:'←', obStart:'开始使用 ✓',
    obName:'姓名', obNameP:'张伟',
    obJob:'职位', obJobP:'员工 / 工人...',
    obCo:'公司名称', obCoP:'ABC公司',
    obShiftNum:'班次数量', obHours:'每班时长',
    obWeeks:'周期周数',
    obShiftCountry:'工作国家',
    days:['星期日','星期一','星期二','星期三','星期四','星期五','星期六'],
    daysShort:['日','一','二','三','四','五','六'],
    months:['1月','2月','3月','4月','5月','6月','7月','8月','9月','10月','11月','12月'],
    salaryContract:'合同工资 / 月', salaryDays:'月基准工作天数',
    salaryEst:'本月预计薪资', salaryNet:'预计实到手薪资',
    salarySave:'✓ 保存薪资信息',
    dpStatus:'状态', dpActual:'实际时间', dpNote:'备注',
    dpReset:'重置为班次', dpCancel:'取消', dpSave:'保存',
    dpTotalHours:'合计:', dpOT:'加班:',
    dpInTime:'上班时间', dpOutTime:'下班时间',
    dpNoteP:'为这天添加备注...',
    stCM:'出勤', stCMSub:'正常出勤',
    stNP:'请假', stNPSub:'带薪假',
    stV:'缺勤', stVSub:'无故缺勤',
    stLL:'节假日工作', stLLSub:'按法律计算',
    spPresent:'本月出勤天数', spStart:'开始今天的工作',
    resetTitle:'删除所有数据？',
    resetDesc:'所有数据将被永久删除，无法恢复！',
    resetCancel:'取消', resetOk:'🗑 全部删除',
    exportPreview:'预览导出数据：',
    exportBtn:'📊 导出Excel文件 (.csv)',
    n1Name:'上班前30分钟提醒', n1Desc:'班次开始前通知',
    n2Name:'30分钟后确认下班', n2Desc:'确认实际下班时间',
    n3Name:'自动打卡 (GPS)', n3Desc:'进入/离开公司区域时自动记录',
    n4Name:'每周总结提醒', n4Desc:'每周五查看每周总结',
  },
  my:{
    appName:'လုပ်ငန်း Pro', appSub:'အလုပ်မှတ်တမ်း · လစာတွက်ချက်မှု',
    vaoCA:'တက်မှတ်', hetCA:'ဆင်းမှတ်',
    batDauCa:'နှိပ်ပြီးစတင်ပါ', ketThucCa:'ဆင်းချိန် နှိပ်ပါ',
    chuaChamCong:'မမှတ်ရသေး',
    gioLam:'ဤလ အလုပ်ချိန်',
    binhThuong:'ပုံမှန်', chamChi:'ကြိုးစား ⚡', quaSuc:'အလွန်အကျွံ 🔥',
    coMat:'တက်ရောက်', vang:'ပျက်ကွက်', nghiPhep:'ခွင့်', tangCa:'ချိန်ပို',
    chucNang:'လုပ်ဆောင်ချက်',
    lich:'ပြက္ခဒိန်', thietLap:'သတ်မှတ်', giaoDien:'ဒီဇိုင်း', caiDat:'ဆက်တင်',
    luong:'လစာ', xuatExcel:'Excel ထုတ်ယူ', thongBao:'အသိပေး', huongDan:'အကူအညီ',
    luongUocTinh:'💼 ဤလ ခန့်မှန်းလစာ',
    lichChamCong:'တက်ရောက်မှု ပြက္ခဒိန်',
    chipCM:'✓ တက်', chipV:'✕ ပျက်', chipNP:'☀ ခွင့်', chipLL:'★ အားလပ်ရက်',
    navHome:'မူလ', navLich:'ပြက္ခဒိန်', navLuong:'လစာ', navCaiDat:'ဆက်တင်',
    settingsTitle:'ဆက်တင်',
    siLang:'ဘာသာစကား', siCountry:'အလုပ်လုပ်သောနိုင်ငံ',
    siSetup:'အချက်အလက်', siSetupSub:'အမည်၊ ရာထူး၊ Shift',
    siNotif:'အသိပေး', siNotifSub:'အချိန်သတိပေး',
    siAppear:'ဒီဇိုင်း', siAppearSub:'အရောင်၊ ဓာတ်ပုံ',
    siAbout:'အပ်အကြောင်း', siAboutSub:'ဗားရှင်း 2.2.0',
    siHelp:'အသုံးပြုနည်း', siHelpSub:'ထိရောက်စွာ အသုံးပြုနည်း',
    siDelete:'ဒေတာအားလုံးဖျက်', siDeleteSub:'ပြန်ရမည်မဟုတ်',
    panelAppear:'⭐ ဒီဇိုင်း', panelNotif:'🔔 အသိပေးချိန်',
    panelSalary:'💰 လစာ', panelExcel:'📊 Excel ထုတ်ယူ',
    panelSetup:'📝 အချက်အလက်', panelHelp:'📖 အသုံးပြုနည်း',
    panelAbout:'ℹ️ အပ်အကြောင်း', panelLang:'🌐 ဘာသာ',
    panelCountry:'🗺️ နိုင်ငံ',
    closeBtn:'ပိတ်',
    obLang:'ကြိုဆိုပါသည်! 👋\nဘာသာရွေးချယ်', obLangSub:'ဘာသာစကားနှင့်နိုင်ငံကိုရွေးချယ်ပါ',
    obUser:'သင့်အချက်အလက် 👤', obUserSub:'အပ်ကိုပုဂ္ဂိုလ်ဆိုင်ရာပြုလုပ်ရန်',
    obShift:'အလုပ်ချိန် ⏰', obShiftSub:'ဘယ်နှစ်ဆင်း? တစ်ဆင်းဘယ်နှစ်နာရီ?',
    obTime:'Shift အချိန် 🕐', obTimeSub:'တစ်ဆင်းချင်းအချိန်သတ်မှတ်ပါ',
    obNext:'ရှေ့ →', obBack:'←', obStart:'အပ်စတင် ✓',
    obName:'အမည်', obNameP:'ကိုစိုး',
    obJob:'ရာထူး', obJobP:'ဝန်ထမ်း...',
    obCo:'ကုမ္ပဏီ', obCoP:'ABC ကုမ္ပဏီ',
    obShiftNum:'Shift အရေ', obHours:'တစ်ဆင်းနာရီ',
    obWeeks:'Cycle ပတ်',
    obShiftCountry:'အလုပ်နိုင်ငံ',
    days:['တနင်္ဂနွေ','တနင်္လာ','အင်္ဂါ','ဗုဒ္ဓဟူး','ကြာသပတေး','သောကြာ','စနေ'],
    daysShort:['တ','တ','အ','ဗ','က','သ','စ'],
    months:['ဇန်နဝါရီ','ဖေဖော်ဝါရီ','မတ်','ဧပြီ','မေ','ဇွန်','ဇူလိုင်','သြဂုတ်','စက်တင်ဘာ','အောက်တိုဘာ','နိုဝင်ဘာ','ဒီဇင်ဘာ'],
    salaryContract:'စာချုပ်လစာ / လ', salaryDays:'လ ပုံမှန်အလုပ်ရက်',
    salaryEst:'ဤလ ခန့်မှန်းလစာ', salaryNet:'ခန့်မှန်းလက်ခံ',
    salarySave:'✓ လစာသိမ်း',
    dpStatus:'အခြေအနေ', dpActual:'အချိန်တိတိ', dpNote:'မှတ်ချက်',
    dpReset:'Shift အချိန်ပြန်', dpCancel:'ပယ်ဖျက်', dpSave:'သိမ်း',
    dpTotalHours:'စုစုပေါင်း:', dpOT:'ချိန်ပို:',
    dpInTime:'တက်ချိန်', dpOutTime:'ဆင်းချိန်',
    dpNoteP:'ဤနေ့အတွက်မှတ်ချက်ထည့်ပါ...',
    stCM:'တက်ရောက်', stCMSub:'ပုံမှန်တက်',
    stNP:'ခွင့်', stNPSub:'လစာပါ ခွင့်',
    stV:'ပျက်ကွက်', stVSub:'ခွင့်မဲ့',
    stLL:'အားလပ်ရက်', stLLSub:'ဥပဒေအတိုင်း',
    spPresent:'ဤလ တက်ရောက်ရက်', spStart:'ယနေ့အလုပ်စတင်',
    resetTitle:'ဒေတာအားလုံးဖျက်မလား?',
    resetDesc:'ဒေတာအားလုံး ပြန်မရနိုင်ဘဲ ဖျက်မည်!',
    resetCancel:'ပယ်ဖျက်', resetOk:'🗑 အားလုံးဖျက်',
    exportPreview:'ထုတ်ယူမည့်ဒေတာကြိုကြည့်:',
    exportBtn:'📊 Excel ထုတ်ယူ (.csv)',
    n1Name:'30မိနစ်ကြိုသတိပေး', n1Desc:'Shift မစမီ အသိပေး',
    n2Name:'30မိနစ်ပြီး ဆင်းအချိန်အတည်ပြု', n2Desc:'တိတိကျကျ ဆင်းချိန်မေးမြန်း',
    n3Name:'အလိုအလျောက် (GPS)', n3Desc:'ကုမ္ပဏီဝင်/ထွက်သောအခါ မှတ်တမ်း',
    n4Name:'အပတ်စဉ်နောင်',n4Desc:'သောကြာတိုင်းအပတ်ချုပ်',
  }
};

function T(key){ return (TRAN[userData.lang||'vi']||TRAN.vi)[key]||(TRAN.vi)[key]||key; }


/* ===== GLOBAL i18n HELPERS ===== */
function _s(id,txt){const el=document.getElementById(id);if(el&&txt!==undefined)el.textContent=txt;}
function _h(id,html){const el=document.getElementById(id);if(el&&html!==undefined)el.innerHTML=html;}
function applyI18n(){
  const L=userData.lang||'vi';
  const t=TRAN[L]||TRAN.vi;
  const s=_s; // global helper
  const h=_h; // global helper

  // App names
  document.querySelectorAll('.rgb-text').forEach(el=>el.textContent=t.appName);
  document.querySelectorAll('#homeAppTitle').forEach(el=>el.textContent=t.appName);
  document.title=t.appName;
  // Onboarding skip button
  const skipLbl={vi:'Bỏ qua',en:'Skip',ko:'건너뛰기',ja:'スキップ',zh:'跳过',my:'ကျော်'};
  s('obSkipBtn',skipLbl[L]||skipLbl.vi);
  // About panel app name (not rgb-text)
  const aboutName=document.querySelector('#panelAbout .rgb-text');
  if(aboutName)aboutName.textContent=t.appName;

  // Home screen
  s('lblVaoCA',t.vaoCA); s('lblHetCA',t.hetCA);
  s('lastIn',t.batDauCa); s('lastOut',t.ketThucCa);
  s('todayStatus',t.chuaChamCong);
  s('meterTitle',t.gioLam);
  s('lblCM',t.coMat); s('lblV',t.vang); s('lblNP',t.nghiPhep); s('lblOT',t.tangCa);
  s('lblFuncTitle',t.chucNang);
  s('flLich',t.lich); s('flThietLap',t.thietLap); s('flGiaoDien',t.giaoDien);
  s('flCaiDat',t.caiDat); s('flLuong',t.luong); s('flExcel',t.xuatExcel);
  s('flThongBao',t.thongBao); s('flHuongDan',t.huongDan);
  s('lblSalaryCard',t.luongUocTinh);

  // Bottom nav labels
  document.querySelectorAll('.nav-lbl').forEach((el,i)=>{
    const lbls=[t.navHome,t.navLich,t.navLuong,t.navCaiDat];
    // Find which nav this is by sibling icon
    const icon=el.previousElementSibling?.textContent;
    if(icon==='🏠')el.textContent=t.navHome;
    else if(icon==='📅')el.textContent=t.navLich;
    else if(icon==='💰')el.textContent=t.navLuong;
    else if(icon==='⚙️')el.textContent=t.navCaiDat;
  });

  // Calendar screen
  s('calScreenTitle',t.lichChamCong);
  s('chipCM',t.chipCM); s('chipV',t.chipV); s('chipNP',t.chipNP); s('chipLL',t.chipLL);

  // Calendar day headers
  const dow=document.getElementById('calDow');
  if(dow){
    const spans=dow.querySelectorAll('span');
    t.daysShort.forEach((d,i)=>{if(spans[i])spans[i].textContent=d;});
  }

  // Settings screen
  s('settingsTitle',t.settingsTitle);
  // Settings items - find by structure
  document.querySelectorAll('.settings-item').forEach(item=>{
    const icon=item.querySelector('.si-icon')?.textContent?.trim();
    const name=item.querySelector('.si-name');
    const sub=item.querySelector('.si-sub');
    if(!name)return;
    if(icon==='🌐'){name.textContent=t.siLang;}
    else if(icon==='🗺️'){name.textContent=t.siCountry;}
    else if(icon==='📝'){name.textContent=t.siSetup;if(sub)sub.textContent=t.siSetupSub;}
    else if(icon==='🔔'){name.textContent=t.siNotif;if(sub)sub.textContent=t.siNotifSub;}
    else if(icon==='⭐'){name.textContent=t.siAppear;if(sub)sub.textContent=t.siAppearSub;}
    else if(icon==='ℹ️'){name.textContent=t.siAbout;if(sub)sub.textContent=t.siAboutSub;}
    else if(icon==='📖'){name.textContent=t.siHelp;if(sub)sub.textContent=t.siHelpSub;}
    else if(icon==='🗑️'){if(sub)sub.textContent=t.siDeleteSub;}
  });

  // Panel titles
  document.querySelectorAll('.panel-title').forEach(el=>{
    const txt=el.textContent.trim();
    if(txt.includes('Giao diện')||txt.includes('Appearance')||txt.includes('화면')||txt.includes('外観')||txt.includes('外观')||txt.includes('ဒီဇိုင်း'))el.textContent=t.panelAppear;
    else if(txt.includes('Thông báo')||txt.includes('Notif')||txt.includes('알림')||txt.includes('通知'))el.textContent=t.panelNotif;
    else if(txt.includes('Bảng lương')||txt.includes('Salary')||txt.includes('급여')||txt.includes('給与')||txt.includes('薪资')||txt.includes('လစာ'))el.textContent=t.panelSalary;
    else if(txt.includes('Excel'))el.textContent=t.panelExcel;
    else if(txt.includes('Thiết lập')||txt.includes('Setup')||txt.includes('정보 설정')||txt.includes('情報設定')||txt.includes('信息设置'))el.textContent=t.panelSetup;
    else if(txt.includes('Hướng dẫn')||txt.includes('Guide')||txt.includes('사용 가이드')||txt.includes('使用'))el.textContent=t.panelHelp;
    else if(txt.includes('Về ứng')||txt.includes('About')||txt.includes('앱 정보')||txt.includes('アプリ情報')||txt.includes('关于')||txt.includes('အပ်'))el.textContent=t.panelAbout;
    else if(txt.includes('ngôn ngữ')||txt.includes('Language')||txt.includes('언어')||txt.includes('言語')||txt.includes('语言')||txt.includes('ဘာသာ'))el.textContent=t.panelLang;
    else if(txt.includes('Quốc gia')||txt.includes('Country')||txt.includes('국가')||txt.includes('勤務国')||txt.includes('国家')||txt.includes('နိုင်ငံ'))el.textContent=t.panelCountry;
  });

  // Panel close buttons
  document.querySelectorAll('.panel-close').forEach(btn=>{if(btn.textContent==='✕'||btn.textContent===t.closeBtn)btn.textContent='✕';});

  // Notif panel rows
  document.querySelectorAll('.notif-name').forEach((el,i)=>{
    const keys=['n1Name','n2Name','n3Name','n4Name'];
    if(t[keys[i]])el.textContent=t[keys[i]];
  });
  document.querySelectorAll('.notif-desc').forEach((el,i)=>{
    const keys=['n1Desc','n2Desc','n3Desc','n4Desc'];
    if(t[keys[i]])el.textContent=t[keys[i]];
  });

  // Salary panel
  document.querySelectorAll('.field-label').forEach(el=>{
    const txt=el.textContent;
    if(txt.includes('Lương hợp đồng')||txt.includes('Contract')||txt.includes('계약')||txt.includes('契約')||txt.includes('合同'))el.textContent=t.salaryContract;
    else if(txt.includes('Ngày công')||txt.includes('working day')||txt.includes('근무일')||txt.includes('勤務日')||txt.includes('工作天'))el.textContent=t.salaryDays;
  });

  // Reset confirm panel
  const rTitle=document.querySelector('#panelConfirmReset [style*="E8433A"]');
  if(rTitle)rTitle.textContent=t.resetTitle;
  const rDesc=document.querySelector('#panelConfirmReset [style*="text2"]');

  // Day panel labels
  s('dpStatusLbl',t.dpStatus); s('dpActualLbl',t.dpActual); s('dpNoteLbl',t.dpNote);
  const dayNote=document.getElementById('dayNote');if(dayNote)dayNote.placeholder=t.dpNoteP;
  const dayReset=document.getElementById('dayResetBtn');if(dayReset)dayReset.textContent=t.dpReset;
  const dayCancel=document.getElementById('dayCancelBtn');if(dayCancel)dayCancel.textContent=t.dpCancel;
  const daySave=document.getElementById('daySaveBtn');if(daySave)daySave.textContent=t.dpSave;

  // Update days/months arrays used by updateClock and renderCalBig
  window._DAYS=t.days;
  window._MONTHS=t.months;
  window._DAYS_SHORT=t.daysShort;
  // Also update the let variables directly so renderCalBig uses them immediately
  if(typeof DAYS!=='undefined')DAYS.splice(0,7,...t.daysShort);
  if(typeof MONTHS!=='undefined')MONTHS.splice(0,12,...t.months);

  // Appearance panel section titles
  const apSec={
    vi:{avt:'Ảnh đại diện',avtDesc:'Ảnh hiển thị trên trang chủ',avtBtn:'📷 Chọn ảnh',color:'Màu chủ đạo',bg:'Ảnh nền lịch',bgBtn:'📷 Chọn ảnh từ máy',bgClear:'✕ Xóa ảnh',gradient:'Màu nền gradient',calColor:'🎨 Màu chữ trong lịch',sunLbl:'Chủ nhật (CN)',sunSub:'Màu chữ ngày Chủ nhật',satLbl:'Thứ 7 (T7)',satSub:'Màu chữ ngày Thứ 7',normLbl:'Ngày thường (T2–T6)',normSub:'Màu chữ ngày trong tuần',reset:'↺ Đặt lại màu mặc định',save:'✓ Lưu giao diện'},
    en:{avt:'Avatar',avtDesc:'Photo shown on home screen',avtBtn:'📷 Choose photo',color:'Theme color',bg:'Calendar background',bgBtn:'📷 Choose from device',bgClear:'✕ Remove',gradient:'Gradient presets',calColor:'🎨 Calendar text colors',sunLbl:'Sunday (Sun)',sunSub:'Sunday text color',satLbl:'Saturday (Sat)',satSub:'Saturday text color',normLbl:'Weekdays (Mon–Fri)',normSub:'Weekday text color',reset:'↺ Reset to default',save:'✓ Save appearance'},
    ko:{avt:'아바타',avtDesc:'홈 화면에 표시되는 사진',avtBtn:'📷 사진 선택',color:'테마 색상',bg:'달력 배경',bgBtn:'📷 기기에서 선택',bgClear:'✕ 제거',gradient:'그라데이션 프리셋',calColor:'🎨 달력 텍스트 색상',sunLbl:'일요일 (일)',sunSub:'일요일 글자색',satLbl:'토요일 (토)',satSub:'토요일 글자색',normLbl:'평일 (월–금)',normSub:'평일 글자색',reset:'↺ 기본값으로',save:'✓ 저장'},
    ja:{avt:'アバター',avtDesc:'ホーム画面に表示する写真',avtBtn:'📷 写真を選択',color:'テーマカラー',bg:'カレンダー背景',bgBtn:'📷 端末から選択',bgClear:'✕ 削除',gradient:'グラデーション',calColor:'🎨 カレンダー文字色',sunLbl:'日曜日（日）',sunSub:'日曜の文字色',satLbl:'土曜日（土）',satSub:'土曜の文字色',normLbl:'平日（月〜金）',normSub:'平日の文字色',reset:'↺ デフォルトに戻す',save:'✓ 外観を保存'},
    zh:{avt:'头像',avtDesc:'显示在主页的照片',avtBtn:'📷 选择照片',color:'主题颜色',bg:'日历背景',bgBtn:'📷 从设备选择',bgClear:'✕ 删除',gradient:'渐变预设',calColor:'🎨 日历文字颜色',sunLbl:'周日（日）',sunSub:'周日文字颜色',satLbl:'周六（六）',satSub:'周六文字颜色',normLbl:'工作日（一–五）',normSub:'工作日文字颜色',reset:'↺ 重置为默认',save:'✓ 保存外观'},
    my:{avt:'ဓာတ်ပုံ',avtDesc:'မူလစာမျက်နှာတွင်ပြသ',avtBtn:'📷 ဓာတ်ပုံရွေး',color:'အရောင်',bg:'ပြက္ခဒိန်နောက်ခံ',bgBtn:'📷 ထည့်သွင်း',bgClear:'✕ ဖျက်',gradient:'Gradient',calColor:'🎨 ပြက္ခဒိန်အရောင်',sunLbl:'တနင်္ဂနွေ',sunSub:'တနင်္ဂနွေ',satLbl:'စနေ',satSub:'စနေ',normLbl:'ပုံမှန်ရက်',normSub:'ပုံမှန်',reset:'↺ မူရင်းပြန်',save:'✓ သိမ်း'},
  };
  const av=apSec[L]||apSec.vi;
  s('apSecAvt',av.avt); s('apSecColor',av.color); s('apSecBg',av.bg);
  s('apSecGradient',av.gradient); s('apSecCalColor',av.calColor);
  s('apAvtDesc',av.avtDesc); s('btnChooseAvt',av.avtBtn);
  s('btnChooseImg',av.bgBtn); s('btnClearBg',av.bgClear);
  s('calColorSunLbl',av.sunLbl); s('calColorSunSub',av.sunSub);
  s('calColorSatLbl',av.satLbl); s('calColorSatSub',av.satSub);
  s('calColorNormLbl',av.normLbl); s('calColorNormSub',av.normSub);
  s('btnResetColors',av.reset); s('btnSaveAppear',av.save);

  // Setup panel labels
  const sp2={
    vi:{name:'Họ và tên',nameP:'Nguyễn Văn A',job:'Chức vụ',jobP:'Nhân viên...',co:'Công ty',coP:'Công ty ABC',shift:'Số ca làm việc',hours:'Số giờ / ca',save:'✓ Lưu thông tin'},
    en:{name:'Full Name',nameP:'John Smith',job:'Job Title',jobP:'Employee...',co:'Company',coP:'ABC Company',shift:'Number of shifts',hours:'Hours / shift',save:'✓ Save Info'},
    ko:{name:'성명',nameP:'홍길동',job:'직책',jobP:'직원...',co:'회사',coP:'ABC 회사',shift:'교대 수',hours:'교대당 시간',save:'✓ 저장'},
    ja:{name:'氏名',nameP:'山田太郎',job:'職種',jobP:'社員...',co:'会社名',coP:'ABC株式会社',shift:'シフト数',hours:'時間/シフト',save:'✓ 保存'},
    zh:{name:'姓名',nameP:'张伟',job:'职位',jobP:'员工...',co:'公司',coP:'ABC公司',shift:'班次数量',hours:'每班时长',save:'✓ 保存信息'},
    my:{name:'အမည်',nameP:'ကိုစိုး',job:'ရာထူး',jobP:'ဝန်ထမ်း...',co:'ကုမ္ပဏီ',coP:'ABC',shift:'Shift',hours:'နာရီ',save:'✓ သိမ်း'},
  };
  const sv2=sp2[L]||sp2.vi;
  s('setupLblName',sv2.name); s('setupLblJob',sv2.job); s('setupLblCo',sv2.co);
  s('setupLblShift',sv2.shift); s('setupLblHours',sv2.hours); s('btnSaveSetup',sv2.save);
  const sn=document.getElementById('setupName');if(sn)sn.placeholder=sv2.nameP;
  const sj=document.getElementById('setupJob');if(sj)sj.placeholder=sv2.jobP;
  const sc=document.getElementById('setupCo');if(sc)sc.placeholder=sv2.coP;

  // Delete row in settings
  const delName={vi:'Xóa toàn bộ dữ liệu',en:'Delete All Data',ko:'모든 데이터 삭제',ja:'全データ削除',zh:'删除所有数据',my:'ဒေတာဖျက်'};
  s('siDeleteName',delName[L]||delName.vi);

  // Reset confirm panel buttons
  const resetBox=document.querySelector('#panelConfirmReset');
  if(resetBox){
    const rBtns=resetBox.querySelectorAll('button');
    const rCancel={vi:'Hủy bỏ',en:'Cancel',ko:'취소',ja:'キャンセル',zh:'取消',my:'ပယ်ဖျက်'};
    const rOk={vi:'🗑 Xóa hết',en:'🗑 Delete All',ko:'🗑 모두 삭제',ja:'🗑 全て削除',zh:'🗑 全部删除',my:'🗑 ဖျက်'};
    if(rBtns[0])rBtns[0].textContent=rCancel[L]||rCancel.vi;
    if(rBtns[1])rBtns[1].textContent=rOk[L]||rOk.vi;
    const rTitle=resetBox.querySelector('[style*="E8433A"][style*="font-size:18px"]');
    const rTitleMap={vi:'Xóa toàn bộ dữ liệu?',en:'Delete all data?',ko:'모든 데이터를 삭제할까요?',ja:'全データを削除しますか？',zh:'删除所有数据？',my:'ဒေတာဖျက်မလား?'};
    if(rTitle)rTitle.textContent=rTitleMap[L]||rTitleMap.vi;
  }

  // Re-render if on cal screen
  if(document.getElementById('screenCal')?.classList.contains('active')){
    renderCalBig();
  }
  updateClock();
}

/* ==================== INIT ==================== */
function init(){
  loadData();
  loadGpsData();
  // Restore GPS toggle
  if(_gpsData.enabled){
    const btn=document.getElementById('togN3');
    if(btn)btn.classList.add('on');
    const card=document.getElementById('gpsSetupCard');
    if(card)card.style.display='block';
    if(_gpsData.lat)startGeofencing();
  }
  // Check if first time
  if(!userData.name){
    goScreen('screenOB');
    renderOB();
  }else{
    goScreen('screenHome');
    initHome();
    setTimeout(moSplash, 600);
  }
  // notif toggles
  ['n1','n2','n3','n4'].forEach((k,i)=>{
    const el=document.getElementById(`togN${i+1}`);
    if(el){el.className='toggle-sw'+(notifCfg[k]?' on':'');}
  });
  // settings subs
  document.getElementById('siLangSub').textContent=LANGS.find(l=>l.id===userData.lang)?.name||'Tiếng Việt';
  document.getElementById('siCountrySub').textContent=COUNTRIES.find(c=>c.id===userData.country)?.name||'Việt Nam';
}

init();
</script>
</body>
</html>
