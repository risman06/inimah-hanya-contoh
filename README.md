<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/>
<link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;700&display=swap" rel="stylesheet"><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
<!--<link href="https://heiyou.feeldream.repl.co/style.css" rel="stylesheet" type="text/css" /><script src="https://heiyou.feeldream.repl.co/script.js"></script>-->
<head>
<!-- 
This code was made by Risman AF
Instagram: rafath_99
-->
</head>
<style>
:root 
  {--warna-bg: rgba(0, 0, 0, .99); --warna-teks: #ffffff;}
  
body{background-color:#181C14;font-family: 'Ubuntu', sans-serif;padding: 25px} a{text-decoration:none;}
body::before{content:"\00A9  create by risman";color:white;opacity:.3;font-size:2vw;position:fixed;bottom:25px;left:25px;}
#bodyblur{opacity:0;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,.3);z-index:-1;transition:all 1s ease;}
@keyframes jj{0%  {transform: scale(1.1);} 50% {transform: scale(1.2);} 100% {transform: scale(1.1);}}
#bodyblur img{animation-name:none;animation-duration: 3s;animation-iteration-count: infinite;}

@keyframes leaves {0% {transform: scale(1.0);} 100% {transform: scale(.8);}}
#lope, .lopdeg{animation: leaves 1s ease-in-out infinite alternate;-webkit-animation: leaves 1s ease-in-out infinite alternate;}
.lovein:hover{transform: scale(1.3);}

@keyframes kont{0%  {left:-1px; top:-3px;} 50% {left:1px; top:3px;} 100% {left:-1px; top:-3px;}}
blockquote{opacity:0;visibility:hidden;transition:all 1s ease;position:relative;margin-top:120px;margin-left:0;margin-right:0;}
blockquote{width:400px;background:var(--warna-bg);color:var(--warna-teks);font-size:16px;font-weight:700;text-align:center;line-height:1.4em;padding:16px 30px 16px 30px;border: 1px solid var(--warna-teks);border-radius:10px;}
blockquote p:first-child{font-size:18px;font-weight:700;text-align:center;}
p{margin:1.5em 0;transition:all .5s ease;}
#bq img{display:none;padding:10px;background:rgba(255,255,255, 1);border-radius:10px;width:100px;height:100px;margin:20px 0 0 0;}
#bq img:first-child{display:inline-flex}
#akhiran{cursor:pointer;display:none;color:#FFC700;font-size:14px;text-align:center;transition:all .3s ease;} #akhiran:hover{opacity:.4}

#pergeseran{opacity:0;visibility:hidden;transition:all 1s ease;display:flex;flex-wrap:nowrap;align-items:flex-start;justify-content:flex-start;position:relative;max-width:500px;padding:0 20px; overflow-y:hidden;overflow-x:scroll;scroll-behavior:smooth;scroll-snap-type:x mandatory; -ms-overflow-style:none;-webkit-overflow-scrolling:touch}
#pergeseran p{background:#003A76;color:white;border: 1px dashed #fff;border-radius:8px;padding:8px;display:flex;flex-wrap:nowrap;text-align:center;font-size:16px;font-weight:700;align-items:center;justify-content:center;flex-shrink:0; width:90%; min-height:130px;margin:0 15px 0 0; scroll-snap-align:center} #pergeseran > *:last-child{margin-right:0} #pergeseran:after{content:'';display:block;flex-shrink:0; align-self:stretch;padding-left:20px}
#pergeseran p b{display:block;} #pergeseran p b img{width:80px;height:80px;margin:20px 0;}
/*#pergeseran p b span{display:flex;}*/
#tm{color:#FFB400;transition:all .5s ease;} #tm:hover{transform: scale(.7);}
#idgeser{position:relative;top:30vh;font-size:17px;color:white}

#contTom{margin:0;display:flex;align-items:left;list-style:none}
.button{display:inline-flex;align-items:center; margin:0;margin:12px 8px 12px 0;transition:all .3s ease;padding:10px 15px;outline:0;border:1px solid var(--warna-teks); border-radius:8px;line-height:20px;background:var(--warna-bg);color:var(--warna-teks);font-size:13px;font-weight:700;white-space:nowrap;overflow:hidden;z-index:1} 
.button:hover{transform: scale(.90);opacity:.98;}
#buttonv2{position:absolute;font-size:15px;color:white;background:var(--warna-bg);padding:10px;border-radius:8px;line-height:10px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);opacity:0}

.lovein{font-size:50px;display:flex;align-items:center;justify-content:center;transition:all .3s ease;}
.lovein svg{width:80px;height:80px;fill:#fefefe}

.content2{display:block;text-align:center;width:100%;height:180px;margin-top:50px;}
.content2 > *{display:flex;align-items:center;justify-content:center;margin-top:15px;font-size:17px;color:white}
.image img{border-radius:10%;transform:scale(.1);transition:all .8s ease;}
#k2 .image > *{margin-bottom:40px;} #k2{font-weight:700;font-size:17px;color:white;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);} #final1{transition:all 3s ease;}

#idkirim{font-size:13px;text-shadow: 0px 2px 2px rgba(0, 0, 0, .8);color:white;transition:all .5s ease;}
#idkirim{opacity:0;visibility:hidden;margin-top:100px} #idkirim:hover{transform:scale(.8);}

.content2{display:none;}
#Content, #k2{animation-name:none;animation-duration: 3s;animation-iteration-count: infinite;position:relative;opacity:0;margin-top:50px;width:100%;height:180px;transition:all 1.8s ease;}
#Content > *, #k2 > *{display:flex;align-items:center;text-align:center;justify-content:center;margin-top:15px;}
#k2, #final1{transform:scale(.1);}

.swal2-modal > *{font-size:16px}
.swal2-title{line-height:1.3em;margin-right:20px;margin-left:20px;font-size:18px;text-align:center;padding:15px 30px 0 30px;}
.swal2-timer-progress-bar-container > *{opacity:.3;background:#007AFF;margin:0 5px}
.swal2-modal{background:rgba(255,255,255,1);border: .7px solid #fff;border-radius:10px;top:-50px;}

.fa-heart {opacity:.4;color:white;font-size: 30px;position: absolute;animation:  heartMove linear 1;top: -10vh;z-index: 0;}
@keyframes heartMove {0%{transform: translateY(-10vh) ;} 100%{transform: translateY(100vh) ;}}
</style>
<body><div id="bodyblur"><img src="https://iili.io/d4au7nV.jpg" width="100%" height="100%"/></div>
  
<div id='Content'><p id="idgeser"></p>

  <div><blockquote id='bq'>
    <img id="foto1" src="https://media.tenor.com/wkzCX9s5kxQAAAAj/0906-peacegoma.gif"/>
    <img id="foto2" src="https://media.tenor.com/gtCplcXtC58AAAAM/milk-mocha.gif"/>
    <img id="foto3" src="https://s11.gifyu.com/images/S1vUB.gif"/>

    <p id="katakata"></p><p id="katabawah"></p>
  </blockquote></div>

  <div id="contTom" style="display:none;"><a id="By" class='button' onClick="terima()">Sayang</a><b id='buttonv2'></b><a id="Bn" class='button' onClick="tolak()">Engga</a></div>
</div>

<script>
  const swals = Swal.mixin({allowOutsideClick: false, cancelButtonColor: '#FF0040',}); const swalsy = Swal.mixin({confirmButtonText: 'Iya', allowOutsideClick: false,}); const swalst = Swal.mixin({allowOutsideClick: false, showConfirmButton: false, timer: 1700, timerProgressBar: true,}); var today = new Date();var dd = String(today.getDate()).padStart(2, '0');var mm = String(today.getMonth() + 1).padStart(2, '0');var yyyy = today.getFullYear(); const monthNames = ["Januari", "Februari", "Maret", "April", "Mei", "Juni", "Juli", "Agustus", "September", "Oktober", "November", "Desember"]; today = dd + ' ' + monthNames[today.getMonth()] + ' ' + yyyy;
  function nonFo() {document.getElementById('idfoto').style.display = "none";} function showFo() {document.getElementById('idfoto').style.display = "block";}
  function nonDiv() {document.getElementById('Content').style = "opacity:0;visibility:hidden;margin-top:30vh;";} 
  function showDiv() {audio.play();setTimeout(kpemb,100);document.getElementById('Content').style = "opacity:1;margin-top:4vh;animation:kont 3s infinite;";document.getElementById("katakata").innerHTML = kata1;}
  function showAkhir() {setInterval(createHeart,200);document.getElementById('k2').style = "opacity:1;transform:scale(1);margin:0;";document.getElementById('ftdua').style = "transform:scale(1);";document.getElementById('final1').style = "transform:scale(1);";document.getElementById('Content').style.display = "none";}
  function mulaiakhir() {nonDiv();setTimeout(showAkhir,1400);setTimeout(finalis,2400);}
  function showTom() {document.getElementById('idkirim').style = "opacity:1;visibility:visible;margin-top:140px;";} function tombol(){contTom.style="display:flex";if(fungsi==3){Bn.style="display:none";}} function akhiran(){document.getElementById("akhiran").style = "display:inline-flex";}
  function befanimkata(){katakata.style="transform:scale(.01);";katabawah.style="transform:scale(.01);";} function animkata() {katakata.style="transform:scale(1);";katabawah.style="transform:scale(1);";}

  async function terimateks(){katakata.innerHTML = kata2;By.innerHTML = "Iya";setTimeout(animkata,300);setTimeout(kbwh,1000);foto1.style="display:none";foto2.style="display:inline-flex";fungsi=2}
  async function tolakteks(){await swalst.fire('' + teksnolak);}

  var aa=0,pemb;pemb = "";var i=0,katab2;katab2 = "";var u=0,text2;text2 = "";var o=0,text3;text3 = "";var a=0,final1;final1 = "";var ab=0,final2;final2 = "";

  function kpemb() {setTimeout(tombol,1800);document.getElementById("idgeser").style = "display:none";document.getElementById("bq").style = "opacity:1;visibility:visible;margin-top:0";document.getElementById('bodyblur').style = "opacity:1;";}

  function kbwh() {if(i<katab2.length){document.getElementById("katabawah").innerHTML += katab2.charAt(i);i++;setTimeout(kbwh,70);}
    if(i==katab2.length){katabawah.innerHTML = katab2 + emotsenyum;setTimeout(tombol,700);}
  }

  flag=1;flagg=1;
  function tolak(){
    if(fungsi==1){
    if(flagg==1){Bn.style="margin-left:90px;transform: rotate(45deg)";buttonv2.style="opacity:1;";By.style="opacity:0";document.getElementById("buttonv2").innerHTML = tekstolak1;flagg=2}
        else if(flagg==2){Bn.style="margin-left:95px;transform: rotate(135deg)";document.getElementById("buttonv2").innerHTML = tekstolak2;flagg=3}
      else if(flagg==3){Bn.style="margin:12px 8px 12px 0;transform: rotate(360deg)";buttonv2.style="opacity:0;";By.style="opacity:1";flagg=1}
        }
      else if(fungsi==2){
        if(flag==1){Bn.style="margin-left:90px;";buttonv2.style="opacity:1;";By.style="opacity:0";document.getElementById("buttonv2").innerHTML = tekstolak11;flag=2}
        else if(flag==2){Bn.style="margin-left:95px;transform: rotate(90deg)";document.getElementById("buttonv2").innerHTML = tekstolak22;flag=3}
        else if(flag==3){Bn.style="margin:12px 8px 12px 0";buttonv2.style="opacity:0;";By.style="opacity:1";tolakteks();flag=1}
         }
   }

    tekstolak1 = "Eits &#129315;";tekstolak11 = "Yakin? &#128541;";
    tekstolak2 = "Gabisa &#129322;";tekstolak22 = "Ihhh! &#128545;";

    fungsi=1;
    async function terima(){
    if(fungsi==1){terimateks();befanimkata();contTom.style="display:none";}
    else if(fungsi==2){document.getElementById("katakata").innerHTML = kata3;document.getElementById("katabawah").innerHTML = katab3;befanimkata();setTimeout(animkata,300);foto1.style="display:none";foto2.style="display:none";foto3.style="display:inline-flex";contTom.style="display:none";setInterval(createHeart,200);By.innerHTML = "Kirim Pesan";setTimeout(tombol,3000);fungsi=3}
    else if(fungsi==3){menuju();}
    }
  </script>

<script type="text/javascript">
      async function menuju(){await swals.fire('OK!', 'Kirim pesan ke aa, ya! kan klo ke WA mah bilih diraziaa', 'success');window.location = "https://www.instagram.com/rafth_99/" + pesanwhatsapp;setTimeout(maubucin,3500);}

            async function mulaitanya(){
              var { isConfirmed: tanyawal } = await swals.fire({title: `Mau isi nama dulu atau langsung aja?`, imageUrl: 'https://i.postimg.cc/0j2LDLxP/heart-happy.gif', imageWidth: 120, imageHeight: 120, confirmButtonText: 'Isi Nama', cancelButtonText: 'Langsung Aja', allowOutsideClick: false, showCancelButton: true,
                });if(tanyawal){mulai();} else {nama = 'Kamu';lanjut();play();}
            }

            async function mulai(){
                var { value: nama } = await swals.fire({
                    title: 'Masukin nama kamu', input: 'text',
                    imageUrl: 'https://media.tenor.com/c1nfF4muxggAAAAi/te-amo.gif', imageWidth: 90, imageHeight: 90, allowOutsideClick: false, showCancelButton: false,
                });
                if(nama && nama.length < 11){
                  window.nama = nama;lanjut();
                } else {
                    await swals.fire('Ups!', 'Nama tidak boleh kosong atau lebih dari 10 karakter, ya!');mulai();
                }
            }

            async function tanpanama(){
                nama = "Kamu";window.nama = nama;lanjut();
             }

            //GANTI SEMUA TEKS, PESAN WHATSAPP, DAN AUDIO DI SINI

             async function lanjut() {
              audio = new Audio('audio.mp3');

              kata1 = nama + " sayang gak sama AA? 🥺";
          kata2 = "Kalo " + nama + " SAYANG...";
           katab2 = "AA juga SAYANG " + nama + " "; emotsenyum = "&#129392;";
           kata3 = "Yeaayy! makasih syangku cintaku cintana AA &#128518;&#128157;";
           katab3 = "AA sayaaaaaanggg tteh selamalamalamalamalamaaaa nyahh ❤❤😘";
                 teksnolak = "Harus iya!!! &#129402;";

                 pesanwhatsapp = "makasih AA, sayangg aa ><";

                 showDiv();
             }

             mulai();
</script>
<script>
const body = document.querySelector("body");function createHeart() {const heart = document.createElement("div"); heart.className = "fas fa-heart"; heart.style.left = (Math.random() * 90)+"vw"; heart.style.animationDuration = (Math.random()*3)+2+"s"; body.appendChild(heart);} setInterval(function name(params) {var heartArr = document.querySelectorAll(".fa-heart"); if (heartArr.length > 100) {heartArr[0].remove()}},100);
</script>
</body>
</html>
