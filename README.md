# wmdk
はさか
<!DOCTYPE html>
<html lang="ja">


<head>

<meta name="viewport" content="width=device-width">
<div class="header"><center>#ITはこちらで#</center></div>
<p></p>
</head>
    <title>テクニック</title>
    <div class="fade">
  <a href="テクニック.html"><h1><ins><i><center>MIRAIコンサル</center></i></ins></h1></div></a>
    <hr>

    <style type="text/css"media="screen"> 
    
    .fade{
         font-size: 15px;
         font-weight: bold;
       animation-name: fadein;
       animation-duration: 3s;  }

							
							@keyframes fadein { 
									from {
        opacity: 0;
  transform: translateY(20px);
            }
    to {
         opacity: 1;
    transform: translateY(0);
         }


							 }
    
    body { animation: fadeIn 15s ease 0s 1 normal; -webkit-animation: fadeIn 2s ease 0s 1 normal; } @keyframes fadeIn { 0% {opacity: 0} 100% {opacity: 1} } @-webkit-keyframes fadeIn { 0% {opacity: 0} 100% {opacity: 1} }

h1{
				color:white;
				}
			.header{
							background-color:#9400d3;
							color:white;
				}
			
				</style>
				
				<input id="menu-cb" type="checkbox" value="off"> <label id="menu-icon" for="menu-cb">←</label> <label id="menu-background" for="menu-cb"></label> 

<div id="ham-menu"> 
<ul>
<li><a href="スロット2.html">スロットゲーム</a></li> 
<br>
<li><a href="らーめん.html">ラーメンタイマー🍜🍥</a></li>
<br> 
<li><a href="クイズ.html">クイズ</a></li> 
</ul> 
</div>
</head>

<style>

body{background-color:#dda0dd;}
 li{color: white;}
    
    #ham-menu { background-color:pink;
    /*メニュー背景色*/ box-sizing: border-box; height: 80%; padding: 70px 40px; /*メニュー内左右上下余白*/ position: fixed; right: -250px; /*メニュー横幅 width と合わせる*/ top: 0; transition: transform 0.3s linear 0s; /*0.3s はアニメーションにかかる時間*/ width: 250px; /*メニュー横幅*/ z-index: 1000; } #menu-background { background-color: pink; /*黒背景*/ display: block; height: 100%; opacity: 0; position: fixed; right: 0; top: 0; transition: all 0.3s linear 0s; /*0.3s はアニメーションにかかる時間*/ width: 100%; z-index: -1; } #menu-icon { background-color: blue; /*アイコン部分背景色*/ border-radius: 0 0 0 10px; /*左下角丸*/ color: red; /*アイコン（フォント）色*/ cursor: pointer; display: block; font-size: 50px; /*アイコン（フォント）サイズ*/ height: 70px; /*アイコン縦高さ*/ line-height: 50px; /*縦位置中央化*/ position: fixed; right: 0; text-align: center; top: 0; width: 50px; /*アイコン横幅*/ transition: all 0.3s linear 0s; /*0.3s はアニメーションにかかる時間*/ z-index: 1000; } #menu-cb { display: none; /*チェックボックス本体は消しておく*/ } #menu-cb:checked ~ #ham-menu, #menu-cb:checked ~ #menu-icon { transform: translate(-250px); /*メニュー本体横幅 width と合わせる*/ } #menu-cb:checked ~ #menu-background { opacity: 0.5; z-index: 999; }
    .button{color:blue;}
    
    p{color:white;
   background-color:#9400d3;
   border-radius:7px;
   }
    
    </style>
<body>
<script type="text/javascript">

	function msg1(){
					alert("7月の特別メニューは、鴨南蛮950円です。そば、うどん、どちらも御用意しております。学生さんは100円引きで提供致します。");
				}
				
			function msg2(){
　　	alert("ようこそ。埼玉にあるおそばの名店《椿》をご紹介します。")
					}
					
					
</script>

<body onload="alert('いらっしゃい')">　
<body ondblclick="msg1()">
<div class="fade">
<center>
<a href="https://hirogurupu.wordpress.com/"><img src="https://file7-d.kuku.lu/files/20200818-0255_be7922946376d2ac313f6783d54ce093.jpg"width="300
" height="120"></a>
</center>
</div>

<input type="button" value="タップ"
onclick="i=0; msg='ようこそ。わたしのホームページへ。こちらの入り口からお入り下さい。いまはいろいろ実験中です。これからどんどん、良くしていきますので、どうぞよろしくお願いいたします。。。。。。。。ちな、趣味は料理です。メールアドレスは、walkerjpjp@gmail.com ↓↓↓↓↓';
 timerID=setInterval('if(i<=msg.length){document.all.div1.innerText=msg.substring(0,i); i++;}if(i>msg.length){clearInterval(timerID);}',70);">　

<div id=div1></div>
<hr>

<div class="fade">
<center><p id="RealtimeClockArea"></p></center></div>
   
<script>
function showClock1() {
var nowdate = new Date();
     
   var nowTime = new Date();

   var nowHour = nowTime.getHours();

   var nowMin  = nowTime.getMinutes();

   var nowSec  = nowTime.getSeconds();

   var msg = "Now Time is " + nowHour + ":" + nowMin + ":   " + nowSec + " 秒";

   document.getElementById("RealtimeClockArea").innerHTML = msg;

}

setInterval('showClock1()',1000);


</script>


    
    <hr>
    <h4>右上のメニューから、ゲームコーナーにも行けるよ。たっぷり遊んでください。</h4>
    <hr>
<iframe src="おみくじ.html" width="300" height="70" frameborder="3"></iframe>
<p></p>
<marquee><お知らせ>画面を２回タップするとメッセージが表れるよ。</marquee>

<div id="clock"> <div id="hour-hand"></div> <div id="minute-hand"></div> <div id="second-hand"></div> </div>


<style>


/* 時計本体 */ #clock { height: 700px; /* 高さは固定 */ margin: 40px auto; max-width: 700px; /* 幅のレスポンシブ対応 */ position: relative; } /* 秒針 */ #second-hand { animation: rotation-s 60s linear infinite; /* 60秒かけて一周 */ background-color: orange; border-radius: 2px; height: 4px; /* 線幅 */ position: absolute; right: calc(50% - 2px); /* 位置調整 線幅の半分ずらす */ top: calc(50% - 2px); /* 位置調整 線幅の半分ずらす */ transform-origin: calc(100% - 2px) center; /* アニメーションの中心軸 線幅の半分ずらす */ width: 50%; } /* 分針 */ #minute-hand { animation: rotation-m 3600s linear infinite; /* 3600秒、1時間かけて一周 */ background-color: pink; border-radius: 5px; height: 10px; /* 線幅 */ position: absolute; right: calc(50% - 5px); /* 位置調整 線幅の半分ずらす */ top: calc(50% - 5px); /* 位置調整 線幅の半分ずらす */ transform-origin: calc(100% - 5px) center; /* アニメーションの中心軸 線幅の半分ずらす */ width: 40%; } /* 時針 */ #hour-hand { animation: rotation-h 86400s linear infinite; /* 86400秒、12時間かけて一周 */ background-color:red; border-radius: 5px; height: 10px; /* 線幅 */ position: absolute; right: calc(50% - 5px); /* 位置調整 線幅の半分ずらす */ top: calc(50% - 5px); /* 位置調整 線幅の半分ずらす */ transform-origin: calc(100% - 5px) center; /* アニメーションの中心軸 線幅の半分ずらす */ width: 25%; } /* 秒針の回転アニメーション */ @keyframes rotation-s { 0% {transform: rotate(90deg)} /* 初期位置 0秒の位置 */ 100% {transform: rotate(450deg)} /* 初期位置 + 360deg で一周 */ } /* 分針の回転アニメーション */ @keyframes rotation-m { 0% {transform: rotate(90deg)} /* 初期位置 0分の位置 */ 100% {transform: rotate(450deg)} /* 初期位置 + 360deg で一周 */ } /* 時針の回転アニメーション */ @keyframes rotation-h { 0% {transform: rotate(150deg)} /* 初期位置 2時の位置 */ 100% {transform: rotate(510deg)} /* 初期位置 + 360deg で一周 */ }
.buruburu { display: inline-block; animation: hurueru .10s infinite ; }

@keyframes hurueru { 0% {transform: translate(0px, 0px) rotateZ(0deg)} 25% {transform: translate(2px, 2px) rotateZ(1deg)} 50% {transform: translate(0px, 2px) rotateZ(0deg)} 75% {transform: translate(2px, 0px) rotateZ(-1deg)} 100% {transform: translate(0px, 0px) rotateZ(0deg)} }


.uneCircle{ 
				border: 5px solid #87CCA1; animation: uneune 5s linear infinite; /* 5秒アニメーションをループ */ width: 280px;
				 height: 280px;
				  margin: 50px auto; 
				  } 
				  
				  @keyframes uneune { 0% { border-radius: 60% 50% 70% 80% / 50% 60% 50% 70%; } 25% { border-radius: 70% 60% 60% 90% / 70% 80% 40% 90%; } 50% { border-radius: 60% 40% 70% 60% / 40% 60% 50% 60%; } 75% { border-radius: 90% 60% 40% 70% / 70% 50% 80% 40%; } 100% { border-radius: 60% 50% 70% 80% / 50% 60% 50% 70%; } }



</style>
    
</body>
</html>

</body></html>
