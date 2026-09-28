<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>MarCom TSU สื่อสารการตลาด ม.ทักษิณ</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anuphan:wght@400;600;700&display=swap" rel="stylesheet">
<style>
/* Palette: เปลี่ยนสีตามโลโก้จริงที่ตัวแปรชุดนี้ชุดเดียว */
:root{--bg:#FFF8F0;--ink:#241663;--mute:#645C8A;--card:#fff;--line:#E6DBF0;--or:#FF6B2C;--pk:#FF3D81;--sun:#FFC533;--in:#241663;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#150F33;--ink:#FFF3E6;--mute:#B9B0DE;--card:#21184A;--line:#352A66}}
:root[data-theme="dark"]{--bg:#150F33;--ink:#FFF3E6;--mute:#B9B0DE;--card:#21184A;--line:#352A66}
html{background:#241663;scroll-behavior:smooth;scroll-padding-top:calc(60px + env(safe-area-inset-top,0px))}
body{margin:0;background:var(--bg);color:var(--ink);font:400 17px/1.7 "Anuphan","Noto Sans Thai",system-ui,sans-serif;-webkit-font-smoothing:antialiased}
a{color:inherit}a:focus-visible{outline:3px solid var(--sun);outline-offset:3px}
nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:10;height:60px;box-sizing:border-box;display:flex;align-items:center;justify-content:space-between;padding:0 20px;background:rgba(36,22,99,.72);-webkit-backdrop-filter:saturate(180%) blur(16px);backdrop-filter:saturate(180%) blur(16px);color:#FFF3E6}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;text-decoration:none}
nav div{display:flex;gap:18px;font-size:15px;align-items:center}nav div a{text-decoration:none;opacity:.85}
.pill{background:var(--sun);color:#241663;padding:6px 14px;border-radius:99px;font-weight:600;opacity:1!important}
.hero{position:relative;min-height:calc(100svh - 60px);display:grid;align-content:center;padding:48px 24px 72px;color:#FFF3E6;overflow:hidden;background:radial-gradient(90% 60% at 85% 10%,#FF3D81 0,transparent 60%),radial-gradient(80% 60% at 0 100%,#FF6B2C 0,transparent 60%),#241663}
.hero-in{position:relative;z-index:2;max-width:900px;will-change:transform}
h1{margin:0;font-size:clamp(3.3rem,16vw,8.5rem);line-height:1.25;font-weight:700}
.ln{display:block;overflow:hidden;padding:.05em 0}.ln>span{display:block;transform:translateY(110%);animation:up 1s cubic-bezier(.2,.8,.2,1) forwards}.ln:nth-child(2)>span{animation-delay:.15s}
@keyframes up{to{transform:none}}
.sub{margin:20px 0 6px;font-size:clamp(1.2rem,4.5vw,1.9rem);font-weight:600}
.sm{margin:0 0 28px;max-width:34ch;opacity:.8;font-size:15px}
.btns{display:flex;flex-wrap:wrap;gap:12px}
.b{display:inline-block;padding:12px 22px;border-radius:99px;font-weight:600;text-decoration:none;border:2px solid #FFF3E6}
.b.f{background:var(--sun);border-color:var(--sun);color:#241663}
.chip{position:absolute;z-index:1;padding:7px 16px;border-radius:99px;font-size:14px;background:rgba(255,255,255,.14);border:1px solid rgba(255,255,255,.3);-webkit-backdrop-filter:blur(6px);backdrop-filter:blur(6px)}
.stage{height:280vh;background:var(--bg)}
.pin{position:sticky;top:calc(60px + env(safe-area-inset-top,0px));height:calc(100svh - 60px);display:grid;align-content:center;padding:0 24px;overflow:hidden}
h2{margin:0 0 20px;font-size:clamp(2rem,8vw,3.6rem);line-height:1.3}
.panels{display:grid;position:relative}
.pn{grid-area:1/1;position:relative;padding:28px 24px;border-radius:32px;background:linear-gradient(135deg,var(--a),var(--b));color:#241663;min-height:300px}
.pn h3{margin:0 0 10px;font-size:clamp(2rem,9vw,3.4rem);line-height:1.3}.pn p{margin:0 0 18px;max-width:40ch}
.pn:nth-child(2){--a:#FFC533;--b:#FF6B2C}.pn:first-child{--a:#FF6B2C;--b:#FF3D81;color:#fff}
.tags{display:flex;flex-wrap:wrap;gap:8px}.tags i{font-style:normal;font-size:14px;padding:4px 14px;border-radius:99px;border:1.5px solid currentColor}
.dots{display:flex;gap:8px;margin-top:18px}.dots i{width:10px;height:10px;border-radius:9px;background:var(--line);transition:width .3s,background .3s}.dots i.on{width:32px;background:var(--or)}
section.s{padding:72px 24px}
dl{margin:0;max-width:820px}dl div{display:grid;gap:2px;padding:20px 0;border-top:1px solid var(--line)}
dt{color:var(--mute);font-size:15px}dd{margin:0;font-size:clamp(1.5rem,6vw,2.4rem);font-weight:700;line-height:1.4}
.row{display:flex;gap:16px;overflow-x:auto;scroll-snap-type:x mandatory;padding:4px 24px 20px;margin:0 -24px}
.card{flex:0 0 78%;max-width:340px;scroll-snap-align:start;padding:24px;border-radius:24px;background:var(--card);border:1px solid var(--line)}
.card b{display:block;font-size:2rem;line-height:1.3;color:var(--c)}.card h4{margin:8px 0;font-size:1.15rem;line-height:1.5}.card p{margin:0;color:var(--mute);font-size:15px}
.card.e{border-style:dashed;background:transparent}
.end{background:#241663;color:#FFF3E6;padding:72px 24px 40px}.end p{max-width:44ch;opacity:.85}
.end small{display:block;margin-top:40px;opacity:.6;font-size:13px;line-height:1.6}
@media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}.ln>span{animation:none;transform:none}.stage{height:auto}.pin{position:static;height:auto;padding:72px 24px}.panels{gap:16px}.pn{grid-area:auto;opacity:1!important;transform:none!important}.dots{display:none}}
.tl{margin:0 0 20px;padding:0;list-style:none;max-width:820px}
.tl li{position:relative;padding:0 0 26px 34px;margin-left:8px;border-left:2px solid var(--line)}
.tl li:last-child{border-color:transparent;padding-bottom:6px}
.tl li::before{content:"";position:absolute;left:-8px;top:8px;width:14px;height:14px;border-radius:50%;background:var(--or)}
.tl h4{margin:0 0 4px;font-size:1.25rem;line-height:1.5}.tl p{margin:0;color:var(--mute);font-size:15px}
a.card{display:block;text-decoration:none;color:inherit}
</style>
</head>
<body>
<nav>
  <a class="brand" href="#top" aria-label="MarCom TSU">
    <!-- LOGO: แทนที่ svg นี้ด้วยโลโก้จริง -->
    <svg width="32" height="32" viewBox="0 0 32 32" aria-hidden="true"><defs><linearGradient id="g" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#FFC533"/><stop offset="1" stop-color="#FF3D81"/></linearGradient></defs><path d="M4 6h24v16H15l-7 5v-5H4z" fill="url(#g)"/></svg>
    MarCom TSU
  </a>
  <div><a href="#majors">สองเอก</a><a href="#news">ข่าว</a><a href="#contact">ติดต่อ</a><a class="pill" href="https://admission.tsu.ac.th" target="_blank" rel="noopener">สมัคร</a></div>
</nav>

<header class="hero" id="top">
  <span class="chip" data-s=".10" style="top:9%;right:8%">โฆษณา</span>
  <span class="chip" data-s=".18" style="top:24%;right:26%">แบรนด์</span>
  <span class="chip" data-s=".06" style="bottom:22%;right:6%">ประชาสัมพันธ์</span>
  <span class="chip" data-s=".14" style="bottom:10%;right:34%">คอนเทนต์</span>
  <div class="hero-in">
    <h1><span class="ln"><span>ขายไม่ออก</span></span><span class="ln"><span>บอกมาร์คอม</span></span></h1>
    <p class="sub">สื่อสารการตลาด มหาวิทยาลัยทักษิณ</p>
    <p class="sm">นิเทศศาสตรบัณฑิต สาขาวิชาการสื่อสารการตลาดและสื่อดิจิทัล คณะมนุษยศาสตร์และสังคมศาสตร์ วิทยาเขตสงขลา</p>
    <div class="btns">
      <a class="b f" href="https://www.facebook.com/p/%E0%B8%AA%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%AA%E0%B8%B2%E0%B8%A3%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%95%E0%B8%A5%E0%B8%B2%E0%B8%94-%E0%B8%A1%E0%B8%97%E0%B8%B1%E0%B8%81%E0%B8%A9%E0%B8%B4%E0%B8%93-MarCom-61575838418106/" target="_blank" rel="noopener">เปิดเพจ Facebook</a>
      <a class="b" href="#majors">ดูสองเอก</a>
    </div>
  </div>
</header>

<section class="stage" id="majors">
  <div class="pin">
    <h2>หนึ่งสาขา สองเอก</h2>
    <div class="panels">
      <article class="pn">
        <h3>การสื่อสารการตลาด</h3>
        <p>วางกลยุทธ์ สร้างแบรนด์ และสื่อสารให้ถึงคนที่ใช่</p>
        <div class="tags"><i>โฆษณาและประชาสัมพันธ์</i><i>การตลาดดิจิทัล</i><i>สร้างแบรนด์</i><i>วิเคราะห์ผู้รับสาร</i></div>
      </article>
      <article class="pn">
        <h3>สื่อดิจิทัล</h3>
        <p>ผลิตคอนเทนต์และสื่อบนแพลตฟอร์มออนไลน์ ให้เรื่องราวของแบรนด์ไปได้ไกลขึ้น</p>
        <div class="tags"><i>ถ่ายภาพดิจิทัล</i><i>กราฟิก</i><i>ตัดต่อ</i><i>แอนิเมชัน</i><i>สื่อออนไลน์</i></div>
      </article>
    </div>
    <div class="dots" aria-hidden="true"><i class="on"></i><i></i></div>
  </div>
</section>

<section class="s">
  <h2>ข้อมูลเบื้องต้น</h2>
  <dl>
    <div><dt>ปริญญา</dt><dd>นิเทศศาสตรบัณฑิต หลักสูตร พ.ศ. 2567</dd></div>
    <div><dt>คณะ</dt><dd>มนุษยศาสตร์และสังคมศาสตร์</dd></div>
    <div><dt>วิทยาเขต</dt><dd>สงขลา เขารูปช้าง</dd></div>
    <div><dt>มหาวิทยาลัย</dt><dd>ทักษิณ ก่อตั้ง พ.ศ. 2511</dd></div>
  </dl>
</section>

<section class="s" id="plan">
  <h2>เรียนอะไรบ้าง</h2>
  <p style="max-width:44ch;color:var(--mute);margin:0 0 28px">เอกการสื่อสารการตลาด หลักสูตร 4 ปี ไม่น้อยกว่า 120 หน่วยกิต</p>
  <ol class="tl">
    <li><h4>ปี 1 ปูพื้นฐาน</h4><p>หลักนิเทศศาสตร์, หลักการโฆษณาและประชาสัมพันธ์, การสื่อสารการตลาดดิจิทัล, การเขียนและการรายงานข่าว</p></li>
    <li><h4>ปี 2 ทักษะสื่อ</h4><p>นวัตกรรมการสื่อสาร, ทัศนศิลป์เพื่อการสื่อสาร, การบริหารธุรกิจสื่อ, การถ่ายภาพเพื่อการสื่อสารการตลาด</p></li>
    <li><h4>ปี 3 แบรนด์และโครงงาน</h4><p>การวิเคราะห์ผู้รับสาร, การสร้างแบรนด์และการออกแบบอัตลักษณ์, การสร้างสรรค์เนื้อหาและการเล่าเรื่อง, การเป็นผู้ประกอบการสื่อ, การวิจัยและโครงงานนิเทศศาสตร์</p></li>
    <li><h4>ปี 4 สหกิจศึกษา</h4><p>ทำงานจริงกับองค์กรตลอดหนึ่งภาคเรียน 6 หน่วยกิต</p></li>
  </ol>
  <small style="color:var(--mute)">ที่มา: แผนการเรียน ปีการศึกษา 2567 กลุ่มภารกิจทะเบียนนิสิตและบริการการศึกษา ม.ทักษิณ</small>
</section>
<section class="s" id="news" style="padding-right:0">
  <h2>เรื่องล่าสุด</h2>
  <div class="row">
    <a class="card" href="https://entrance.tsu.ac.th/detail.php?id_list=127&aNum=20260923085100" target="_blank" rel="noopener" style="--c:var(--or)"><b>23 ก.ย. 69</b><h4>ประกาศผู้มีสิทธิ์สอบสัมภาษณ์ TCAS70 รอบ 1/1</h4><p>รอบ Portfolio ปีการศึกษา 2570</p></a>
    <a class="card" href="https://entrance.tsu.ac.th/detail.php?id_list=121&aNum=20260826144855" target="_blank" rel="noopener" style="--c:var(--pk)"><b>26 ส.ค. 69</b><h4>เปิดรับ TCAS70 รอบ Portfolio</h4><p>สองวิทยาเขต รวม 1,664 ที่นั่ง สมัครออนไลน์ 1–11 ก.ย. 69</p></a>
    <a class="card" href="https://entrance.tsu.ac.th/detail.php?id_list=115&aNum=20260727170746" target="_blank" rel="noopener" style="--c:var(--or)"><b>27 ก.ค. 69</b><h4>รอบ Portfolio ใช้ TCASFolio 100%</h4><p>เตรียมแฟ้มสะสมผลงานผ่านระบบ myTCAS</p></a>
    <a class="card" href="https://entrance.tsu.ac.th/detail.php?id_list=114&aNum=20260727091745" target="_blank" rel="noopener" style="--c:var(--pk)"><b>27 ก.ค. 69</b><h4>TSU Open House: HOUSE OF MAGIC</h4><p>เปิดบ้านต้อนรับน้อง ๆ ที่วิทยาเขตสงขลา</p></a>
    <div class="card" style="--c:var(--or)"><b>เม.ย. 69</b><h4>TCAS69 รอบ Quota 2/3</h4><p>เปิดรับทั้งสองเอก เอกละ 2 ที่นั่ง</p></div>
    <div class="card" style="--c:var(--pk)"><b>พ.ย. 68</b><h4>TCAS69 รอบ Portfolio 1/4</h4><p>เปิดรับทั้งสองเอก เอกละ 1 ที่นั่ง</p></div>
    <div class="card" style="--c:var(--or)"><b>ต.ค. 68</b><h4>สัมภาษณ์น้อง ๆ รอบ Portfolio 1/1</h4><p>พี่ ๆ MarCom ร่วมสัมภาษณ์ผู้สมัคร TCAS69</p></div>
    <div class="card" style="--c:var(--pk)"><b>จากเพจ</b><h4>แอดมินให้กำลังใจก่อนสอบวันแรก</h4><p>ชวนทุกคนอ่านหนังสือ และแอบไปเชียร์หน้าห้องสอบ</p></div>
    <a class="card e" href="https://www.facebook.com/p/%E0%B8%AA%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%AA%E0%B8%B2%E0%B8%A3%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%95%E0%B8%A5%E0%B8%B2%E0%B8%94-%E0%B8%A1%E0%B8%97%E0%B8%B1%E0%B8%81%E0%B8%A9%E0%B8%B4%E0%B8%93-MarCom-61575838418106/" target="_blank" rel="noopener" style="--c:var(--mute)"><b>ทั้งหมด</b><h4>โพสต์อื่น ๆ อยู่ที่เพจ Facebook</h4><p>แตะเพื่อเปิดเพจ</p></a>
  </div>
</section>

<footer class="end" id="contact">
  <h2>ทักมาถามได้</h2>
  <p>140 หมู่ 4 ต.เขารูปช้าง อ.เมืองสงขลา จ.สงขลา<br>โทร 074-317-605</p>
  <div class="btns">
    <a class="b f" href="tel:+6674317605">โทรหาเรา</a>
    <a class="b" href="https://www.google.com/maps/search/?api=1&query=มหาวิทยาลัยทักษิณ+วิทยาเขตสงขลา" target="_blank" rel="noopener">เปิดแผนที่</a>
    <a class="b" href="https://huso.tsu.ac.th" target="_blank" rel="noopener">เว็บคณะ</a>
    <a class="b" href="https://futurestudent.tsu.ac.th" target="_blank" rel="noopener">ข้อมูลสมัครเรียน</a>
    <a class="b" href="https://www.facebook.com/comartstsu" target="_blank" rel="noopener">เพจนิเทศศาสตร์</a>
  </div>
  <small>ข้อมูล ณ 28 ก.ย. 2569 รวบรวมจากเว็บทางการของ ม.ทักษิณและแหล่งสาธารณะ ยังไม่ใช่เว็บไซต์ทางการของมหาวิทยาลัยทักษิณ</small>
</footer>

<script>
const $=s=>document.querySelector(s),$$=s=>[...document.querySelectorAll(s)];
const rm=matchMedia('(prefers-reduced-motion:reduce)').matches;
const hero=$('.hero-in'),chips=$$('.chip'),st=$('.stage'),pn=$$('.pn'),dots=$$('.dots i');
const cl=(x,a=0,b=1)=>Math.min(b,Math.max(a,x));
let tick=false;
function upd(){
  tick=false;if(rm)return;
  const y=scrollY,h=innerHeight,t=cl(y/h);
  hero.style.transform='scale('+(1-t*.08)+') translateY('+(-t*30)+'px)';
  hero.style.opacity=1-t*.8;
  chips.forEach(c=>c.style.transform='translateY('+(-y*c.dataset.s)+'px)');
  const r=st.getBoundingClientRect(),p=cl(-r.top/(r.height-h)),k=cl((p-.42)/.16);
  pn[0].style.opacity=1-k;pn[0].style.transform='translateY('+(-k*40)+'px)';
  pn[1].style.opacity=k;pn[1].style.transform='translateY('+((1-k)*40)+'px)';
  dots[0].classList.toggle('on',k<.5);dots[1].classList.toggle('on',k>=.5);
}
addEventListener('scroll',()=>{if(!tick){tick=true;requestAnimationFrame(upd)}},{passive:true});
addEventListener('resize',upd);upd();
</script>
</body>
</html>
