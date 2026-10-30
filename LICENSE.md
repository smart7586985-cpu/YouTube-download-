<!-- YTDownload: "home" page. Paste into Blogger: Pages > New page > HTML view. -->
<div id="ytd" data-page="home">
<style>
#ytd{--bg:#0F172A;--bg2:#1E293B;--ac:#3B82F6;--ac2:#60A5FA;--tx:#E2E8F0;--mu:#94A3B8;--bd:#334155;position:relative;overflow:hidden;background:var(--bg);color:var(--tx);font:16px/1.65 "Inter",system-ui,-apple-system,"Segoe UI",sans-serif;box-sizing:border-box}
#ytd *{box-sizing:border-box}
#ytd h1,#ytd h2,#ytd h3{font-family:"Space Grotesk","Inter",system-ui,sans-serif;line-height:1.15;margin:0 0 .6em;color:#fff;letter-spacing:-.02em}
#ytd h1{font-size:clamp(2rem,6vw,3.4rem)}#ytd h2{font-size:clamp(1.5rem,3.5vw,2rem)}#ytd h3{font-size:1.1rem}
#ytd p,#ytd li{color:var(--mu);max-width:70ch}#ytd a{color:var(--ac2)}
#ytd .w{max-width:1000px;margin:0 auto;padding:0 20px;position:relative;z-index:1}
#ytd .sec{padding:56px 0}
#ytd nav{position:sticky;top:0;z-index:20;background:rgba(15,23,42,.92);backdrop-filter:blur(8px);border-bottom:1px solid var(--bd)}
#ytd nav .w{display:flex;align-items:center;justify-content:space-between;min-height:60px;flex-wrap:wrap}
#ytd .logo{font:700 1.25rem "Space Grotesk",sans-serif;color:#fff;text-decoration:none}#ytd .logo b{color:var(--ac2)}
#ytd .menu{display:flex;gap:4px;list-style:none;margin:0;padding:0}
#ytd .menu a{display:block;padding:8px 12px;border-radius:8px;color:var(--mu);text-decoration:none;font-size:.95rem}
#ytd .menu a:hover,#ytd .menu a.on{color:#fff;background:var(--bg2)}
#ytd .burger{display:none;background:none;border:1px solid var(--bd);color:#fff;border-radius:8px;padding:6px 12px;font:inherit;cursor:pointer}
@media(max-width:720px){#ytd .burger{display:block}#ytd .menu{display:none;width:100%;flex-direction:column;padding-bottom:10px}#ytd .menu.open{display:flex}}
#ytd .hero{position:relative;padding:84px 0 72px;overflow:hidden}
#ytd .orb{position:absolute;border-radius:50%;filter:blur(70px);opacity:.38;pointer-events:none;animation:ytdf 22s ease-in-out infinite alternate}
#ytd .o1{width:380px;height:380px;background:#3B82F6;top:-120px;left:-80px}
#ytd .o2{width:300px;height:300px;background:#6366F1;right:-60px;top:40px;animation-duration:17s;animation-delay:-6s}
#ytd .o3{width:260px;height:260px;background:#0EA5E9;bottom:-120px;left:40%;animation-duration:25s;animation-delay:-11s}
@keyframes ytdf{to{transform:translate(60px,40px) scale(1.15)}}
#ytd .hero .w>*{animation:ytdi .7s cubic-bezier(.2,.7,.2,1) both;animation-delay:calc(var(--i,0)*.12s)}
@keyframes ytdi{from{opacity:0;transform:translateY(18px)}}
#ytd .hero p{font-size:1.1rem}
#ytd .btn{display:inline-block;background:var(--ac);color:#fff;border:0;border-radius:10px;padding:12px 22px;font:600 1rem inherit;font-family:inherit;cursor:pointer;text-decoration:none;transition:background .2s,transform .2s}
#ytd .btn:hover{background:#2563EB;transform:translateY(-1px)}#ytd .btn.sm{padding:6px 14px;font-size:.85rem}
#ytd .btn.ghost{background:transparent;border:1px solid var(--bd);color:var(--tx)}
#ytd :focus-visible{outline:2px solid var(--ac2);outline-offset:2px}
#ytd .bar{display:flex;gap:10px;flex-wrap:wrap;max-width:640px}
#ytd input,#ytd textarea,#ytd select{width:100%;background:var(--bg);border:1px solid var(--bd);color:#fff;border-radius:10px;padding:12px 14px;font:inherit}
#ytd .bar input{flex:1 1 260px;width:auto}
#ytd label{display:block;font-weight:600;font-size:.9rem;margin:14px 0 6px;color:var(--tx)}
#ytd .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
#ytd .card{background:var(--bg2);border:1px solid var(--bd);border-radius:14px;padding:22px}
#ytd .card p{margin:0}#ytd a.card{text-decoration:none;display:block;transition:border-color .2s}#ytd a.card:hover{border-color:var(--ac)}
#ytd .steps{counter-reset:s;list-style:none;padding:0;display:grid;gap:14px}
#ytd .steps li{counter-increment:s;padding-left:48px;position:relative}
#ytd .steps li:before{content:counter(s);position:absolute;left:0;top:0;width:34px;height:34px;border-radius:50%;background:var(--ac);color:#fff;display:grid;place-items:center;font-weight:700}
#ytd .tabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:18px}
#ytd .tabs button{background:var(--bg2);border:1px solid var(--bd);color:var(--mu);border-radius:999px;padding:8px 16px;font:inherit;cursor:pointer}
#ytd .tabs button[aria-selected=true]{background:var(--ac);border-color:var(--ac);color:#fff}
#ytd .panel{background:var(--bg2);border:1px solid var(--bd);border-radius:14px;padding:24px}#ytd .panel[hidden]{display:none}
#ytd .th{margin:0;background:var(--bg);border:1px solid var(--bd);border-radius:12px;overflow:hidden}
#ytd .th img{width:100%;display:block}#ytd .th figcaption{display:flex;justify-content:space-between;align-items:center;gap:8px;padding:10px 12px;font-size:.85rem;color:var(--mu)}
#ytd .row{display:flex;gap:10px;align-items:center;justify-content:space-between;background:var(--bg);border:1px solid var(--bd);border-radius:10px;padding:10px 12px;margin-top:8px}
#ytd .row span{color:var(--tx);overflow-wrap:anywhere}#ytd .row small{color:var(--mu);white-space:nowrap}
#ytd .err{color:#FCA5A5}#ytd .ok{color:#86EFAC}
#ytd details{background:var(--bg2);border:1px solid var(--bd);border-radius:10px;padding:12px 16px;margin-bottom:10px}#ytd summary{cursor:pointer;color:#fff;font-weight:600}
#ytd .note{border-left:3px solid var(--ac);padding:4px 0 4px 14px;margin:18px 0}
#ytd footer{border-top:1px solid var(--bd);background:#0B1222;padding:36px 0 24px;margin-top:20px}
#ytd .fg{display:flex;justify-content:space-between;gap:24px;flex-wrap:wrap}#ytd footer ul{list-style:none;padding:0;margin:0;display:flex;gap:6px 18px;flex-wrap:wrap}
#ytd footer small{display:block;margin-top:22px;color:var(--mu)}
.post-title,.date-header,.post-footer,.post-meta{display:none!important}
@media(prefers-reduced-motion:reduce){#ytd *{animation:none!important;transition:none!important}}
</style>
<header class="hero"><i class="orb o1"></i><i class="orb o2"></i><i class="orb o3"></i><div class="w"><h1 style="--i:0">Free tools for YouTube creators</h1><p style="--i:1">Grab video thumbnails, and generate titles, tags and descriptions in seconds. No sign-up, nothing to install.</p><form id="hf" class="bar" style="--i:2"><input id="hu" type="url" placeholder="Paste a YouTube link to get its thumbnail" aria-label="YouTube link"><button class="btn" type="submit">Get thumbnail</button></form></div></header><section class="sec"><div class="w"><h2>Four tools, one place</h2><div class="grid">
<a class="card" href="/p/tool-generator.html#thumbnail"><h3>Thumbnail downloader</h3><p>Save any public video's thumbnail in up to four sizes.</p></a>
<a class="card" href="/p/tool-generator.html#title"><h3>Title generator</h3><p>Ten title ideas from one keyword, with character counts.</p></a>
<a class="card" href="/p/tool-generator.html#tags"><h3>Tag generator</h3><p>A ready-to-paste tag list that fits YouTube's 500-character limit.</p></a>
<a class="card" href="/p/tool-generator.html#description"><h3>Description generator</h3><p>A structured description with chapters, links and hashtags.</p></a></div></div></section>
<section class="sec"><div class="w"><h2>How it works</h2><ol class="steps"><li><h3>Pick a tool</h3><p>Open the Tool Generator and choose the tab you need.</p></li><li><h3>Enter a link or keyword</h3><p>Everything runs in your browser. We never upload what you type.</p></li><li><h3>Copy or download</h3><p>Use the result in YouTube Studio or in your own design software.</p></li></ol></div></section>
<section class="sec"><div class="w"><h2>Questions</h2><details><summary>Does this download YouTube videos?</summary><p>No. YTDownload only works with thumbnails and text you write. Downloading videos can break YouTube's Terms of Service and copyright law.</p></details><details><summary>Is it free?</summary><p>Yes. The site is supported by advertising.</p></details><details><summary>Can I use a thumbnail I download?</summary><p>Thumbnails belong to their creators. Use them only with permission, or for fair use such as commentary or reference.</p></details></div></section>
<script>
(function(){
var C=window.YTD_CONFIG={
 name:"YTDownload",
 email:"contact@example.com",
 pages:{home:"/",tool:"/p/tool-generator.html",about:"/p/about-us.html",contact:"/p/contact-us.html",privacy:"/p/privacy-policy.html",terms:"/p/terms-of-service.html"}
};
var L=[["home","Home"],["tool","Tool Generator"],["about","About Us"],["contact","Contact Us"]];
var root=document.getElementById("ytd"),cur=root.getAttribute("data-page");
var nav='<div class="w"><a class="logo" href="'+C.pages.home+'">YT<b>Download</b></a><button class="burger" aria-expanded="false" aria-controls="ytd-menu">Menu</button><ul class="menu" id="ytd-menu">'+L.map(function(i){return '<li><a href="'+C.pages[i[0]]+'"'+(i[0]===cur?' class="on" aria-current="page"':'')+'>'+i[1]+'</a></li>'}).join("")+'</ul></div>';
var foot='<div class="w"><div class="fg"><div><a class="logo" href="'+C.pages.home+'">YT<b>Download</b></a><p style="margin:6px 0 0">Free tools for YouTube creators.</p></div><ul>'+[["privacy","Privacy Policy"],["terms","Terms of Service"],["about","About Us"],["contact","Contact Us"]].map(function(i){return '<li><a href="'+C.pages[i[0]]+'">'+i[1]+'</a></li>'}).join("")+'</ul></div><small>&copy; '+new Date().getFullYear()+' '+C.name+'. Not affiliated with or endorsed by YouTube or Google LLC. YouTube is a trademark of Google LLC.</small></div>';
root.insertAdjacentHTML("afterbegin","<nav aria-label=\"Main\">"+nav+"</nav>");
root.insertAdjacentHTML("beforeend","<footer>"+foot+"</footer>");
var b=root.querySelector(".burger"),m=root.querySelector(".menu");
b.onclick=function(){var o=m.classList.toggle("open");b.setAttribute("aria-expanded",o)};
root.querySelectorAll("[data-mail]").forEach(function(e){e.textContent=C.email;e.href="mailto:"+C.email});
root.querySelectorAll("[data-name]").forEach(function(e){e.textContent=C.name});
})();

document.getElementById("hf").onsubmit=function(e){e.preventDefault();var v=document.getElementById("hu").value.trim();location.href=YTD_CONFIG.pages.tool+(v?"?u="+encodeURIComponent(v):"")+"#thumbnail"};
</script>
</div>
