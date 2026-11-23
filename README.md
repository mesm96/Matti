# Matti
<!DOCTYPE html>
<html lang="es-CO">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>MATTIAS · Cuidamos lo que más amas</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@600;800&family=Nunito+Sans:wght@400;600;700&display=swap" rel="stylesheet">
<style>
:root{--sage:#718D72;--pale:#DDE8D5;--cream:#F3F0E7;--beige:#D9CBB4;--dark:#405844;--surface:#fff;--ink:#2c3e30;--muted:#6f7f6f;--line:#dfe6d9;--on-sage:#fff;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--cream:#162019;--surface:#1f2d23;--ink:#eaf1e6;--muted:#a3b5a3;--line:#33463a;--pale:#2b3d30;--beige:#5b5240;color-scheme:dark}}
:root[data-theme="dark"]{--cream:#162019;--surface:#1f2d23;--ink:#eaf1e6;--muted:#a3b5a3;--line:#33463a;--pale:#2b3d30;--beige:#5b5240;color-scheme:dark}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--cream);color:var(--ink);font:400 16px/1.55 "Nunito Sans",system-ui,sans-serif}
h1,h2,h3{font-family:"Bricolage Grotesque","Nunito Sans",sans-serif;line-height:1.1;margin:0}
a{color:inherit}
.wrap{max-width:1080px;margin:0 auto;padding:0 20px}
.top{display:flex;align-items:center;justify-content:space-between;padding:16px 0}
.logo{font:800 26px "Bricolage Grotesque",sans-serif;text-decoration:none;color:var(--sage);letter-spacing:.5px}
nav a{margin-left:18px;text-decoration:none;font-weight:600;color:var(--muted)}
nav a:hover{color:var(--ink)}
.hero{background:var(--dark);color:#fff;border-radius:0 0 36px 36px;padding:6px 0 52px}
.hero .logo{color:var(--pale)}.hero nav a{color:#cfdcc9}.hero nav a:hover{color:#fff}
.hero h1{font-size:clamp(34px,6vw,62px);font-weight:800;max-width:15ch;margin-top:34px}
.lead{max-width:52ch;color:#d3dfce;font-size:18px;margin:16px 0 26px}
.search{background:var(--surface);color:var(--ink);border-radius:20px;padding:14px;display:grid;grid-template-columns:1.2fr 1.2fr auto;gap:10px;max-width:760px}
select,input{font:inherit;color:var(--ink);background:var(--cream);border:1.5px solid var(--line);border-radius:12px;padding:12px 14px;width:100%}
select:focus,input:focus,button:focus-visible,a:focus-visible{outline:3px solid var(--beige);outline-offset:2px}
.btn{font:700 16px "Nunito Sans",sans-serif;background:var(--sage);color:#fff;border:0;border-radius:12px;padding:12px 20px;cursor:pointer}
.btn:hover{background:var(--dark)}
.btn.alt{background:var(--beige);color:#3b2f17}.btn.alt:hover{filter:brightness(.95);background:var(--beige)}
.btn.sm{padding:8px 14px;font-size:14px}
.btn.no{background:transparent;color:var(--ink);border:1.5px solid var(--line)}.btn.no:hover{background:var(--pale)}
.trust{display:flex;gap:26px;flex-wrap:wrap;margin-top:26px;color:#d3dfce;font-size:15px}.trust b{color:#fff}
section{padding:46px 0 6px}
h2{font-size:clamp(24px,4vw,36px);font-weight:800}
.sub{color:var(--muted);margin:8px 0 22px}
.row{display:flex;gap:10px;flex-wrap:wrap}
.chip{border:1.5px solid var(--line);background:var(--surface);color:var(--ink);padding:9px 15px;border-radius:999px;font:600 15px "Nunito Sans",sans-serif;cursor:pointer}
.chip[aria-pressed="true"]{background:var(--sage);color:#fff;border-color:var(--sage)}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(250px,1fr));gap:18px;margin-top:20px}
.card{background:var(--surface);border:1px solid var(--line);border-radius:20px;padding:20px;display:flex;flex-direction:column;gap:10px}
.tr{display:flex;gap:12px;align-items:center}
.av{width:56px;height:56px;border-radius:50%;display:grid;place-items:center;font-size:26px;flex:none;background:var(--pale)}
.card h3{font-size:19px}
.meta{color:var(--muted);font-size:14px}
.tag,.badge{font-size:12.5px;font-weight:700;background:var(--pale);color:var(--dark);border-radius:999px;padding:4px 10px;display:inline-block}
:root[data-theme="dark"] .tag,:root[data-theme="dark"] .badge{color:var(--ink)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]) .tag,:root:not([data-theme="light"]) .badge{color:var(--ink)}}
.badge.warn{background:var(--beige);color:#3b2f17}
.price{margin-top:auto;display:flex;justify-content:space-between;align-items:center;padding-top:8px}
.price strong{font:800 20px "Bricolage Grotesque",sans-serif}
.empty{padding:28px;text-align:center;color:var(--muted);border:1.5px dashed var(--line);border-radius:20px;grid-column:1/-1}
.how{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px}
.how div{border-left:4px solid var(--beige);padding:4px 0 4px 16px}
.how h3{font-size:19px;margin-bottom:4px}.how p{margin:0;color:var(--muted)}
.cta{background:var(--pale);border-radius:28px;padding:32px;margin:52px 0;display:flex;justify-content:space-between;gap:20px;align-items:center;flex-wrap:wrap}
.cta h2{max-width:20ch}.cta p{margin:6px 0 0;color:var(--muted)}
footer{border-top:1px solid var(--line);padding:24px 0 40px;color:var(--muted);font-size:14px;text-align:center}
dialog{border:0;border-radius:22px;padding:0;max-width:440px;width:calc(100% - 32px);background:var(--surface);color:var(--ink)}
dialog::backdrop{background:rgba(20,30,22,.6)}
.dlg{padding:24px;display:grid;gap:12px}
.dlg label{font-weight:700;font-size:14px;display:grid;gap:6px}
.sum{background:var(--cream);border-radius:14px;padding:14px;font-size:15px}
.sum div{display:flex;justify-content:space-between;gap:10px}
.sum .tot{font-weight:800;border-top:1px solid var(--line);margin-top:8px;padding-top:8px;font-size:17px}
.r2{display:grid;grid-template-columns:1fr 1fr;gap:10px}
.toast{position:fixed;left:50%;transform:translateX(-50%);bottom:calc(20px + env(safe-area-inset-bottom,0px));background:var(--dark);color:#fff;padding:14px 20px;border-radius:14px;max-width:90%;opacity:0;pointer-events:none;transition:opacity .25s;z-index:20}
.toast.on{opacity:1}
/* admin */
.adm main{padding:30px 0 10px}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:14px;margin:22px 0}
.num{font:800 30px "Bricolage Grotesque",sans-serif;color:var(--sage)}
.lab{color:var(--muted);font-size:13px}
.panel{margin-top:22px}
.item{display:flex;justify-content:space-between;align-items:center;gap:12px;padding:12px 0;border-top:1px solid var(--line);flex-wrap:wrap}
.item:first-of-type{border-top:0}
.split{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px;margin-top:10px}
.split div{background:var(--cream);border-radius:14px;padding:14px}
.split strong{display:block;font:800 20px "Bricolage Grotesque",sans-serif}
@media (max-width:640px){.search{grid-template-columns:1fr}nav a{margin-left:12px}.cta{padding:24px}}
@media (prefers-reduced-motion:reduce){*{transition:none!important}}
</style>
</head>
<body>

<div id="vPub">
<div class="hero"><div class="wrap">
 <header class="top"><a class="logo" href="#">🐾 MATTIAS</a><nav><a href="#cuidadores">Cuidadores</a><a href="#como">Cómo funciona</a><a href="#ser-cuidador">Ser cuidador</a></nav></header>
 <h1>Alguien de confianza para tu peludo, en tu ciudad.</h1>
 <p class="lead">Reserva alojamiento, paseos, guardería y visitas a domicilio con cuidadores verificados en Colombia. Paga en pesos.</p>
 <div class="search" role="search"><select id="hCity" aria-label="Ciudad"></select><select id="hSvc" aria-label="Servicio"></select><button class="btn" id="hGo">Buscar cuidador</button></div>
 <div class="trust"><span><b>Verificación obligatoria</b> de cada cuidador</span><span><b>Fotos y novedades</b> durante el servicio</span><span><b>Pago protegido</b> hasta que termina</span></div>
</div></div>
<main class="wrap">
 <section id="cuidadores"><h2>Cuidadores cerca de ti</h2><p class="sub">Filtra por servicio y ciudad, compara precios y reserva en minutos.</p>
  <div class="row" id="svcChips" role="group" aria-label="Servicios"></div>
  <div class="row" id="cityChips" style="margin-top:10px" role="group" aria-label="Ciudades"></div>
  <div class="grid" id="grid" aria-live="polite"></div></section>
 <section id="como"><h2>Cómo funciona</h2><p class="sub">Tres pasos, sin llamadas ni intermediarios.</p>
  <div class="how"><div><h3>1. Elige</h3><p>Busca por ciudad y servicio. Lee reseñas de otros dueños y mira el perfil completo.</p></div><div><h3>2. Reserva</h3><p>Escoge las fechas y confirma el precio total antes de pagar.</p></div><div><h3>3. Relájate</h3><p>Recibe fotos y novedades de tu mascota mientras estás fuera.</p></div></div></section>
 <div class="cta" id="ser-cuidador"><div><h2>¿Amas a los animales? Gana dinero cuidándolos.</h2><p>Tú pones tu tarifa y recibes el 85 % de cada reserva. Revisamos tu perfil antes de activarlo.</p></div><button class="btn" id="joinBtn">Quiero ser cuidador</button></div>
</main>
<footer><div class="wrap">MATTIAS · Cuidamos lo que más amas. · <a href="#admin">Administración</a><br>Los perfiles de esta página son de ejemplo.</div></footer>
</div>

<div id="vAdm" class="adm" hidden>
<div class="wrap">
 <header class="top"><a class="logo" href="#">🐾 MATTIAS</a><span class="badge">PORTAL ADMINISTRATIVO</span></header>
 <main><h1 style="font-size:32px">Panel de administración</h1><p class="meta" style="margin:6px 0 0">Bienvenido al centro de operaciones MATTIAS. <a href="#">Ver la página pública</a></p>
 <div class="stats" id="stats"></div>
 <section class="card panel" style="padding:20px"><h2 style="font-size:24px">Verificación de cuidadores</h2><p class="meta">Las solicitudes de registro deben revisarse antes de habilitar los servicios. <span class="badge">Verificación obligatoria</span></p><div id="pend"></div></section>
 <section class="card panel" style="padding:20px"><h2 style="font-size:24px">Reservas</h2><div id="books"></div></section>
 <section class="card panel" style="padding:20px"><h2 style="font-size:24px">Buscar usuario</h2><input id="q" placeholder="Correo o nombre del usuario" style="margin:10px 0"><div id="res"></div></section>
 <section class="card panel" style="padding:20px"><h2 style="font-size:24px">Modelo comercial</h2><p class="meta">Comisión MATTIAS: <strong>15 %</strong> · Participación del cuidador: <strong>85 %</strong></p><div class="split" id="split"></div></section>
 </main>
</div>
<footer>MATTIAS · Cuidamos lo que más amas. Datos de ejemplo guardados solo en esta pestaña.</footer>
</div>

<dialog id="dlg"><div class="dlg">
 <h3 id="dName" style="font-size:24px"></h3><div class="meta" id="dMeta"></div>
 <div class="r2"><label>Tu nombre<input id="bn"></label><label>Correo<input id="be" type="email"></label></div>
 <div class="r2"><label>Desde<input type="date" id="d1"></label><label>Hasta<input type="date" id="d2"></label></div>
 <label>Tu mascota<select id="pet"><option>Perro pequeño</option><option>Perro mediano</option><option>Perro grande</option><option>Gato</option></select></label>
 <div class="sum" id="sum"></div>
 <div class="r2"><button class="btn no" id="cancel" type="button">Cancelar</button><button class="btn" id="confirm" type="button">Solicitar reserva</button></div>
</div></dialog>

<dialog id="dlgJoin"><div class="dlg">
 <h3 style="font-size:24px">Sé cuidador en Mattias</h3>
 <label>Nombre<input id="jn" placeholder="Tu nombre"></label>
 <div class="r2"><label>Ciudad<select id="jc"></select></label><label>Servicio<select id="js"></select></label></div>
 <div class="r2"><label>Tarifa (COP)<input id="jp" type="number" min="5000" step="1000" value="30000"></label><label>Correo<input id="je" type="email" placeholder="tu@correo.com"></label></div>
 <p class="meta" style="margin:0">Tu perfil queda en revisión. Lo activamos cuando verifiquemos tu identidad.</p>
 <div class="r2"><button class="btn no" id="jx" type="button">Cerrar</button><button class="btn" id="jsend" type="button">Enviar solicitud</button></div>
</div></dialog>
<div class="toast" id="toast" role="status"></div>

<script>
const FEE=.15,CITIES=["Bogotá","Medellín","Cali","Barranquilla","Cartagena","Bucaramanga"];
const SV={alojamiento:["Alojamiento","noche"],guarderia:["Guardería de día","día"],paseo:["Paseos","paseo"],visita:["Visita a domicilio","visita"],peluqueria:["Peluquería","servicio"]};
const $=id=>document.getElementById(id),cop=n=>"$"+Math.round(n).toLocaleString("es-CO")+" COP";
const esc=s=>String(s).replace(/[&<>"']/g,c=>({"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;","'":"&#39;"}[c]));
const seed=[["Valentina R.","Bogotá","alojamiento",65000,4.9,86,"🐕","Casa con patio en Chapinero. Paseos largos todos los días."],["Andrés M.","Medellín","paseo",25000,4.8,142,"🦮","Paseos por El Poblado y Laureles. Grupos pequeños."],["Camila T.","Cali","guarderia",45000,5,61,"🐶","Guardería con zona de juego y siesta. Cupos limitados."],["Julián P.","Barranquilla","visita",30000,4.7,37,"🐈","Veterinario de formación. Experto en gatos y cachorros."],["Laura G.","Cartagena","alojamiento",70000,4.9,54,"🐩","Apartamento climatizado cerca de Getsemaní."],["Sebastián O.","Bogotá","paseo",28000,4.8,98,"🐕‍🦺","Corredor. Ideal para perros con mucha energía."],["Daniela C.","Medellín","peluqueria",80000,4.9,73,"✂️","Baño, corte y cepillado a domicilio."],["Mateo V.","Bucaramanga","guarderia",40000,4.6,29,"🐾","Finca pequeña a 15 minutos de Cabecera."],["Isabela N.","Cali","visita",32000,4.8,45,"🐱","Visitas de 30 min con comida, juego y fotos."],["Felipe A.","Bogotá","guarderia",50000,4.9,112,"🐶","Chía y Usaquén. Recogida y entrega incluidas."],["Paula S.","Cartagena","paseo",30000,4.7,40,"🦮","Paseos al amanecer o al atardecer, lejos del calor."],["Camilo D.","Barranquilla","alojamiento",60000,4.8,66,"🐕","Casa con jardín en Alto Prado. Máximo 2 perros."]];
let sitters=seed.map((r,i)=>({id:i,name:r[0],city:r[1],svc:r[2],price:r[3],rating:r[4],reviews:r[5],emoji:r[6],bio:r[7],status:"ok",email:r[0].split(" ")[0].toLowerCase()+"@ejemplo.co"}));
sitters.push({id:12,name:"Ricardo F.",city:"Medellín",svc:"alojamiento",price:55000,rating:0,reviews:0,emoji:"🐕",bio:"Casa con terraza en Envigado.",status:"pend",email:"ricardo@ejemplo.co"});
sitters.push({id:13,name:"Sofía B.",city:"Bogotá",svc:"paseo",price:26000,rating:0,reviews:0,emoji:"🦮",bio:"Paseos en Cedritos y Usaquén.",status:"pend",email:"sofia@ejemplo.co"});
let owners=[["Carolina L.","carolina@ejemplo.co"],["Jorge H.","jorge@ejemplo.co"],["Mariana P.","mariana@ejemplo.co"],["Daniel R.","daniel@ejemplo.co"],["Natalia G.","natalia@ejemplo.co"]].map(o=>({name:o[0],email:o[1]}));
let books=[],fS="todos",fC="todas",cur=null,nid=100;
const opt=(a,f)=>(f?`<option value="${f[0]}">${f[1]}</option>`:"")+a.map(x=>`<option value="${x[0]}">${x[1]}</option>`).join("");
$("hCity").innerHTML=opt(CITIES.map(c=>[c,c]),["todas","Todas las ciudades"]);
$("hSvc").innerHTML=opt(Object.entries(SV).map(([k,v])=>[k,v[0]]),["todos","Todos los servicios"]);
$("jc").innerHTML=opt(CITIES.map(c=>[c,c]));$("js").innerHTML=opt(Object.entries(SV).map(([k,v])=>[k,v[0]]));
function toast(m){const t=$("toast");t.textContent=m;t.classList.add("on");clearTimeout(toast.t);toast.t=setTimeout(()=>t.classList.remove("on"),3200)}
/* público */
function renderPub(){
 $("svcChips").innerHTML=[["todos","Todos"],...Object.entries(SV).map(([k,v])=>[k,v[0]])].map(([k,l])=>`<button class="chip" data-s="${k}" aria-pressed="${fS===k}">${l}</button>`).join("");
 $("cityChips").innerHTML=[["todas","Todas"],...CITIES.map(c=>[c,c])].map(([k,l])=>`<button class="chip" data-c="${k}" aria-pressed="${fC===k}">${l}</button>`).join("");
 $("hCity").value=fC;$("hSvc").value=fS;
 const l=sitters.filter(s=>s.status==="ok"&&(fS==="todos"||s.svc===fS)&&(fC==="todas"||s.city===fC));
 $("grid").innerHTML=l.length?l.map(s=>`<article class="card"><div class="tr"><div class="av">${s.emoji}</div><div><h3>${esc(s.name)}</h3><div class="meta">${s.city} · ${s.rating?"★ "+s.rating.toFixed(1)+" ("+s.reviews+")":"Nuevo en Mattias"}</div></div></div><div class="row" style="gap:6px"><span class="tag">${SV[s.svc][0]}</span><span class="tag">Verificado</span></div><p class="meta" style="margin:0">${esc(s.bio)}</p><div class="price"><span><strong>${cop(s.price)}</strong><br><small class="meta">por ${SV[s.svc][1]}</small></span><button class="btn" data-b="${s.id}">Reservar</button></div></article>`).join(""):`<div class="empty">Aún no hay cuidadores con ese filtro. Prueba otra ciudad o servicio.</div>`;
}
document.addEventListener("click",e=>{const t=e.target,d=t.dataset;
 if(d.s){fS=d.s;renderPub()}if(d.c){fC=d.c;renderPub()}if(d.b)openBook(+d.b);
 if(d.ap){sitters.find(s=>s.id==d.ap).status="ok";toast("Cuidador aprobado. Ya aparece en la página pública.");renderAdm()}
 if(d.rj){sitters.find(s=>s.id==d.rj).status="no";toast("Solicitud rechazada.");renderAdm()}
 if(d.cf){books.find(b=>b.id==d.cf).status="Confirmada";renderAdm()}
});
$("hGo").onclick=()=>{fC=$("hCity").value;fS=$("hSvc").value;renderPub();$("cuidadores").scrollIntoView({behavior:"smooth"})};
function days(){const a=new Date($("d1").value),b=new Date($("d2").value);if(isNaN(a)||isNaN(b)||b<a)return 0;return Math.round((b-a)/864e5)+(cur.svc==="alojamiento"?0:1)}
function sum(){const n=days(),t=n*cur.price;$("sum").innerHTML=n?`<div><span>${cop(cur.price)} × ${n}</span><span>${cop(t)}</span></div><div class="tot"><span>Total a pagar</span><span>${cop(t)}</span></div><div class="meta" style="margin-top:6px">El cuidador recibe el 85 %. La comisión de Mattias (15 %) ya está incluida.</div>`:`<span class="meta">Elige las fechas para ver el total.</span>`}
function openBook(id){cur=sitters.find(s=>s.id===id);$("dName").textContent="Reservar con "+cur.name;$("dMeta").textContent=SV[cur.svc][0]+" · "+cur.city;const t=new Date().toISOString().slice(0,10);$("d1").min=$("d2").min=t;$("d1").value=$("d2").value="";sum();$("dlg").showModal()}
["d1","d2"].forEach(i=>$(i).onchange=()=>{if($("d2").value<$("d1").value)$("d2").value=$("d1").value;sum()});
$("cancel").onclick=()=>$("dlg").close();
$("confirm").onclick=()=>{const n=$("bn").value.trim(),e=$("be").value.trim();
 if(!n||!e.includes("@")){toast("Escribe tu nombre y un correo válido.");return}
 if(!days()){toast("Elige las fechas de la reserva.");return}
 if(!owners.some(o=>o.email===e))owners.push({name:n,email:e});
 books.push({id:nid++,sid:cur.id,owner:n,email:e,pet:$("pet").value,d1:$("d1").value,d2:$("d2").value,total:days()*cur.price,status:"Pendiente"});
 $("dlg").close();toast("Solicitud enviada. "+cur.name+" te responderá pronto.")};
$("joinBtn").onclick=()=>$("dlgJoin").showModal();$("jx").onclick=()=>$("dlgJoin").close();
$("jsend").onclick=()=>{const n=$("jn").value.trim(),e=$("je").value.trim(),p=+$("jp").value;
 if(!n||!e.includes("@")||!(p>=5000)){toast("Completa tu nombre, un correo válido y una tarifa desde $5.000.");return}
 sitters.push({id:nid++,name:n,city:$("jc").value,svc:$("js").value,price:p,rating:0,reviews:0,emoji:"🐾",bio:"Cuidador nuevo en Mattias.",status:"pend",email:e});
 $("dlgJoin").close();toast("¡Gracias, "+n+"! Revisaremos tu perfil antes de activarlo.")};
/* admin */
function renderAdm(){
 const ok=sitters.filter(s=>s.status==="ok"),pe=sitters.filter(s=>s.status==="pend"),gross=books.reduce((a,b)=>a+b.total,0);
 $("stats").innerHTML=[["Usuarios registrados",owners.length+ok.length+pe.length],["Cuidadores verificados",ok.length],["Por verificar",pe.length],["Reservas",books.length],["Comisión","15 %"]].map(s=>`<div class="card"><div class="lab">${s[0]}</div><div class="num">${s[1]}</div></div>`).join("");
 $("pend").innerHTML=pe.length?pe.map(s=>`<div class="item"><div><strong>${esc(s.name)}</strong> <span class="meta">· ${s.city} · ${SV[s.svc][0]} · ${cop(s.price)}<br>${esc(s.email)}</span></div><div class="row"><button class="btn sm" data-ap="${s.id}">Aprobar</button><button class="btn sm no" data-rj="${s.id}">Rechazar</button></div></div>`).join(""):`<p class="meta">No hay solicitudes pendientes.</p>`;
 $("books").innerHTML=books.length?books.map(b=>{const s=sitters.find(x=>x.id===b.sid);return `<div class="item"><div><strong>${esc(b.owner)}</strong> → ${esc(s.name)} <span class="meta">· ${b.pet} · ${b.d1} a ${b.d2}<br>${cop(b.total)} · Mattias ${cop(b.total*FEE)} · Cuidador ${cop(b.total*(1-FEE))}</span></div><div class="row"><span class="badge ${b.status==="Pendiente"?"warn":""}">${b.status}</span>${b.status==="Pendiente"?`<button class="btn sm" data-cf="${b.id}">Confirmar</button>`:""}</div></div>`}).join(""):`<p class="meta">Aún no hay reservas. Haz una desde la página pública y aparecerá aquí.</p>`;
 const conf=books.filter(b=>b.status==="Confirmada").reduce((a,b)=>a+b.total,0);
 $("split").innerHTML=`<div><span class="meta">Reservas totales</span><strong>${cop(gross)}</strong></div><div><span class="meta">Ingreso Mattias (15 %)</span><strong>${cop(gross*FEE)}</strong></div><div><span class="meta">Pago a cuidadores (85 %)</span><strong>${cop(gross*(1-FEE))}</strong></div><div><span class="meta">Ya confirmado</span><strong>${cop(conf)}</strong></div>`;
 renderSearch();
}
function renderSearch(){const v=$("q").value.trim().toLowerCase();if(!v){$("res").innerHTML=`<p class="meta">Escribe un nombre o correo.</p>`;return}
 const all=[...owners.map(o=>({n:o.name,e:o.email,r:"Dueño"})),...sitters.filter(s=>s.status!=="no").map(s=>({n:s.name,e:s.email,r:s.status==="ok"?"Cuidador verificado":"Cuidador en revisión"}))].filter(u=>(u.n+u.e).toLowerCase().includes(v));
 $("res").innerHTML=all.length?all.map(u=>`<div class="item"><div><strong>${esc(u.n)}</strong> <span class="meta">· ${esc(u.e)}</span></div><span class="badge">${u.r}</span></div>`).join(""):`<p class="meta">Ningún usuario coincide con “${esc(v)}”.</p>`}
$("q").oninput=renderSearch;
function route(){const a=location.hash==="#admin";$("vAdm").hidden=!a;$("vPub").hidden=a;if(a)renderAdm();else renderPub();window.scrollTo(0,0)}
addEventListener("hashchange",route);route();
</script>
</body>
</html>
