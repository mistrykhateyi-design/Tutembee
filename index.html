<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Locate Me – Prototype</title>
<style>
:root{--bg:#F4EFE3;--ink:#14301F;--card:#FBF8F0;--line:#14301F33;--accent:#F2A33A;--mute:#4F5F54;--phone:#14301F;--screen:#E6F0E3;--me:#14301F;--meText:#F4EFE3;--bot:#FFFFFF;--btnText:#14301F;--note:#8A5200;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0E1F15;--ink:#F4EFE3;--card:#1D4029;--line:#F4EFE333;--mute:#B9C7BD;--phone:#050D08;--screen:#17301F;--me:#F2A33A;--meText:#14301F;--bot:#25503C;--note:#F2A33A;color-scheme:dark}}
:root[data-theme="dark"]{--bg:#0E1F15;--ink:#F4EFE3;--card:#1D4029;--line:#F4EFE333;--mute:#B9C7BD;--phone:#050D08;--screen:#17301F;--me:#F2A33A;--meText:#14301F;--bot:#25503C;--note:#F2A33A;color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:Inter,system-ui,sans-serif;line-height:1.5}
main{max-width:980px;margin:0 auto;padding:24px 16px 40px;display:flex;flex-wrap:wrap;gap:32px;justify-content:center;align-items:flex-start}
.stage{display:flex;flex-direction:column;align-items:center;gap:14px}
.tabs{display:flex;gap:8px}
.tabs button{font:inherit;font-weight:600;padding:8px 18px;border-radius:999px;border:2px solid var(--ink);background:transparent;color:var(--ink);cursor:pointer}
.tabs button.on{background:var(--accent);border-color:var(--accent);color:#14301F}
.phone{width:330px;height:620px;background:var(--phone);border-radius:38px;padding:14px;box-shadow:0 12px 30px #0003}
.screen{background:var(--screen);border-radius:26px;height:100%;overflow:hidden;display:flex;flex-direction:column;color:var(--ink)}
.pane{display:flex;flex-direction:column;height:100%;min-height:0}
.pane[hidden],[hidden]{display:none!important}
.idle{margin:auto;text-align:center;display:flex;flex-direction:column;gap:12px;align-items:center}
.code{font-size:44px;font-weight:700;letter-spacing:.04em}
.small{font-size:14px;color:var(--mute);margin:0}
.btn{font:inherit;font-weight:600;padding:10px 20px;border-radius:12px;border:2px solid var(--accent);background:var(--accent);color:#14301F;cursor:pointer}
.btn.ghost{background:transparent;color:var(--ink);border-color:var(--ink)}
.btn:disabled{opacity:.45;cursor:default}
.dlg{margin:auto 14px;background:var(--card);border:2px solid var(--line);border-radius:18px;padding:18px;display:flex;flex-direction:column;gap:10px}
.utext{white-space:pre-wrap;font-size:16px;line-height:1.45;min-height:150px}
.cnt{font-size:12px;color:var(--mute)}
input{font:inherit;width:100%;padding:10px 12px;border-radius:10px;border:2px solid var(--line);background:var(--bg);color:var(--ink)}
.row{display:flex;gap:8px;justify-content:flex-end}
.bar{padding:12px 16px;font-weight:700;border-bottom:2px solid var(--line)}
.msgs{flex:1;min-height:0;overflow-y:auto;padding:12px;display:flex;flex-direction:column;gap:6px}
.b{max-width:85%;padding:9px 12px;border-radius:16px;font-size:15px;white-space:pre-wrap}
.b.bot{background:var(--bot);align-self:flex-start;border-bottom-left-radius:4px}
.b.me{background:var(--me);color:var(--meText);align-self:flex-end;border-bottom-right-radius:4px}
.meta{font-size:11px;color:var(--mute);margin:-2px 4px 4px}
.chips{display:flex;flex-wrap:wrap;gap:6px;padding:0 12px 8px}
.chips button{font:inherit;font-size:13px;padding:5px 10px;border-radius:999px;border:1.5px solid var(--ink);background:transparent;color:var(--ink);cursor:pointer}
.in{padding:8px 12px 12px}
.info{max-width:420px;display:flex;flex-direction:column;gap:14px}
.info h1{font-size:34px;line-height:1.1;margin:0}
.info h2{font-size:18px;margin:0 0 4px}
.info p,.info li{font-size:16px;margin:0}
.info ol,.info ul{margin:0;padding-left:22px}
.note{background:var(--card);border:2px solid var(--line);border-radius:14px;padding:14px 16px}
.note b{color:var(--note)}
</style>
</head>
<body>
<main>
<section class="stage">
<div class="tabs" role="tablist"><button class="on" data-t="ussd" role="tab">USSD</button><button data-t="sms" role="tab">SMS chat</button></div>
<div class="phone"><div class="screen">
<div id="ussd" class="pane">
<div id="idle" class="idle"><div class="code">*123#</div><p class="small">Sample code</p><button id="dial" class="btn">Dial</button></div>
<div id="dlg" class="dlg" hidden>
<div id="utext" class="utext"></div><div id="ucnt" class="cnt"></div>
<input id="uin" inputmode="numeric" autocomplete="off" aria-label="Your reply">
<div class="row"><button id="ucancel" class="btn ghost">Cancel</button><button id="usend" class="btn">Send</button></div>
</div>
</div>
<div id="sms" class="pane" hidden>
<div class="bar">Locate Me · 22XXX</div>
<div id="msgs" class="msgs"></div>
<div id="chips" class="chips"></div>
<div class="row in"><input id="sin" placeholder="Type a message" autocomplete="off" aria-label="Message"><button id="ssend" class="btn">Send</button></div>
</div>
</div></div>
</section>
<aside class="info">
<h1>Locate Me prototype</h1>
<p>Get directions around Eldoret Polytechnic from any phone, with no data bundles.</p>
<div><h2>Try the USSD flow</h2><ol><li>Press Dial</li><li>Reply 1 (Directions), then 2 (Back gate)</li><li>Reply 2 (Library) and read the directions</li><li>Notice the 182-character limit on each screen</li></ol></div>
<div><h2>Try the SMS assistant</h2><ul><li>“Library from back gate”</li><li>“How long?”</li><li>“GUIDE” to request an Usipotee ambassador</li></ul></div>
<div class="note"><b>Sample only.</b> The places, directions, codes and fee are placeholders. The assistant here follows simple rules; the real version would use your verified landmark list and an AI model.</div>
</aside>
</main>
<script>
const $=s=>document.querySelector(s);
const P=[
{n:'Admin block',w:['admin','registrar','fees','admission','office'],m:3,d:{main:'Go straight from the main gate. Admin is the first big building on your left.',back:'From the back gate, follow the path to the roundabout and turn left. Admin is ahead.'}},
{n:'Library',w:['library','books','study'],m:4,d:{main:'Walk past Admin, then turn right at the notice board. The library is the block ahead.',back:'Go straight to the notice board, then turn left. The library is ahead.'}},
{n:'Exam hall',w:['exam','hall','test'],m:6,d:{main:'Pass the library and keep right along the tarmac. The exam hall is the long building at the end.',back:'Take the path past the workshops, then turn right. The exam hall is on your left.'}},
{n:'Cafeteria',w:['cafe','food','canteen','eat','lunch'],m:5,d:{main:'Follow the main road, then turn left at the playing field. The cafeteria is near the trees.',back:'Walk straight past the workshops. The cafeteria is on your right.'}},
{n:'Hostels',w:['hostel','hostels','accommodation'],m:8,d:{main:'Follow the main road to the far end of campus. The hostels are behind the field.',back:'Turn right just inside the gate and follow the fence. The hostels are ahead.'}}
];
const GATES={main:'main gate',back:'back gate'};
const MAIN='LOCATE ME\n1. Directions\n2. Ask a question\n3. Send a guide\n0. Exit';
const FROM='Where are you?\n1. Main gate\n2. Back gate\n3. Not sure\n0. Exit';
const TO='Where to?\n'+P.map((p,i)=>(i+1)+'. '+p.n).join('\n')+'\n0. Exit';
const U={step:'idle',from:'main',menu:''};
const code=()=>1000+Math.floor(Math.random()*9000);

function ushow(t,menu){U.menu=menu||t;$('#utext').textContent=t;$('#ucnt').textContent=t.length+'/182 characters';$('#idle').hidden=true;$('#dlg').hidden=false;const i=$('#uin');i.value='';i.disabled=false;$('#usend').disabled=false;i.focus()}
function uend(t){U.step='idle';$('#utext').textContent=t;$('#ucnt').textContent='Session ended';$('#uin').disabled=true;$('#usend').disabled=true}
function bad(){ushow('Invalid choice.\n'+U.menu,U.menu)}
function usend(){
 const t=$('#uin').value.trim();const s=U.step;if(s==='idle'||!t)return;
 if(t==='0')return uend('Thank you for using Locate Me.');
 if(s==='main'){
  if(t==='1'){U.step='from';ushow(FROM)}
  else if(t==='2'){U.step='info';ushow('Text your question to 22XXX and our assistant will reply.\n(Try the SMS chat tab.)\n1. Menu 0. Exit')}
  else if(t==='3'){U.step='guide';ushow('A student ambassador meets you at the gate and walks you there.\nFee: KES [__]\n1. Confirm 2. Back')}
  else bad();
 }else if(s==='from'){
  if(t==='1'||t==='2'){U.from=t==='1'?'main':'back';U.step='to';ushow(TO)}
  else if(t==='3'){U.step='info';ushow('Text what you can see, like “blue building and a stage”, to 22XXX.\n(Try the SMS chat tab.)\n1. Menu 0. Exit')}
  else bad();
 }else if(s==='to'){
  const p=P[+t-1];
  if(p){U.step='res';ushow(p.n+': '+p.d[U.from]+' ~'+p.m+' min.\n1. Menu 0. Exit')}else bad();
 }else if(s==='res'||s==='info'){
  if(t==='1'){U.step='main';ushow(MAIN)}else bad();
 }else if(s==='guide'){
  if(t==='1')uend('Request sent. An ambassador will meet you at the '+GATES[U.from]+'.\nCode: '+code());
  else if(t==='2'){U.step='main';ushow(MAIN)}else bad();
 }
}
$('#dial').onclick=()=>{U.step='main';ushow(MAIN)};
$('#usend').onclick=usend;
$('#uin').onkeydown=e=>{if(e.key==='Enter')usend()};
$('#ucancel').onclick=()=>{U.step='idle';$('#dlg').hidden=true;$('#idle').hidden=false};

const S={from:'main',last:null,guide:false};
function add(who,t){
 const m=$('#msgs'),d=document.createElement('div');d.className='b '+who;d.textContent=t;m.appendChild(d);
 if(who==='bot'){const c=document.createElement('div');c.className='meta';c.textContent=t.length+' characters · '+Math.ceil(t.length/160)+' SMS';m.appendChild(c)}
 m.scrollTop=m.scrollHeight;
}
function ai(q){
 const l=q.toLowerCase().trim();
 if(S.guide&&/^(yes|y)\b/.test(l)){S.guide=false;return 'Done. An ambassador will meet you at the '+GATES[S.from]+'. Code '+code()+'. Fee KES [__].'}
 S.guide=false;
 if(/back/.test(l))S.from='back';else if(/main|front/.test(l))S.from='main';
 const p=P.find(x=>x.w.some(w=>new RegExp('\\b'+w).test(l)));
 if(/guide|escort|ambassador/.test(l)){S.guide=true;return 'A student ambassador can meet you at the gate and walk you there. Reply YES to confirm (KES [__]).'}
 if(/how long|minutes|how far/.test(l)&&S.last&&!p)return 'About '+S.last.m+' min on foot to the '+S.last.n+'.';
 if(/\bopen\b|\bclose|hours/.test(l))return 'I don’t have opening hours yet, so I won’t guess. Ask at the office, or reply GUIDE for a person to help.';
 if(p){S.last=p;return p.n+' (from the '+GATES[S.from]+'): '+p.d[S.from]+' About '+p.m+' min. Reply HOW LONG, another place, or GUIDE.'}
 if(/\bhi\b|hello|help|lost/.test(l))return 'Welcome to Locate Me. Where are you and where do you want to go? Example: “library from back gate”.';
 return 'I’m not sure yet. Name a place (library, admin, exam hall, cafeteria, hostels) or a landmark near you, or reply GUIDE.';
}
function ssend(t){t=(t||$('#sin').value).trim();if(!t)return;$('#sin').value='';add('me',t);setTimeout(()=>add('bot',ai(t)),450)}
$('#ssend').onclick=()=>ssend();
$('#sin').onkeydown=e=>{if(e.key==='Enter')ssend()};
['Library from back gate','How long?','Is the library open?','GUIDE'].forEach(c=>{const b=document.createElement('button');b.textContent=c;b.onclick=()=>ssend(c);$('#chips').appendChild(b)});
add('bot','Welcome to Locate Me. Where are you and where do you want to go? Example: “library from back gate”.');

document.querySelectorAll('.tabs button').forEach(b=>b.onclick=()=>{
 document.querySelectorAll('.tabs button').forEach(x=>x.classList.toggle('on',x===b));
 $('#ussd').hidden=b.dataset.t!=='ussd';$('#sms').hidden=b.dataset.t!=='sms';
});
</script>
</body>
</html>
