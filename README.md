<!DOCTYPE html>
<html lang="ko">
<head>
	<meta charset="UTF-8";
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="id=ddge">
	<title>국내 코로나 바이러스 확진자 정리</title>
	<link href="https://fonts.googleapis.com/css?family=Jua&display=swap" rel="stylesheet">
</head>
<body style="
    display: inline-block;
    margin: 0;
">
	<style>
		.Jua {
			font-size: 45px;
			font-family: 'Jua', sans-serif;
		}
		.box_1 {
			background: black;
			opacity: 0.9;
			color: #F2F2F2;
			display: flex;
			justify-content: center;
			padding: 10px 80px;
			align-items: center
		}
		.box_2 {
			background: black;
			opacity: 0.9;
			color: #F2F2F2;
			display: flex;
			justify-content: center;
			padding: 10px 10px;
			align-items: center
		}
		.box_3 {
			background: black;
			opacity: 0.9;
			position: fixed;
			justify-content: center;
			height: 200px;
			width: 150px;
			align-items: center;
			border-radius: 15px;
			right: 20px;
			top: 100px;
		}
		.line {
			width: 100px;
			height: 2000px;
			margin-left: 800px;
			border-left: 3px solid black;
		}
		.time {
			list-style: none;
		}
		.grid {
			display: grid;
			grid-template-columns: 800px 720px 200px 200px;
		}
		#c{
			text-decoration: none;
			color: white;
			font-family: 'Jua', sans-serif;
			font-size: 30px;
			position: relative;
		}
		#b {
			text-decoration: none;
			color: black;
			font-family: 'Jua', sans-serif;
			font-size: 30px;
			position: relative;
		}
	</style>
	<div class="grid">
		<div class="title box_1">
			<span class="Jua title">국내 코로나 바이러스 확진자 정리</span>
		</div>
		<div class="box_2" id="a"></div>
		<div class="box_2 b" style="background-color: #F2F2F2">
			<a href="./coronavirus_1.html" id="b"><span>확진순서</span></a>
		</div>
		<div class="box_2 c" onmouseover="
		document.querySelector('.c').style.backgroundColor = '#F2F2F2'
		document.querySelector('#c').style.color = 'black'" onmouseout="
		document.querySelector('.c').style.backgroundColor = 'black'
		document.querySelector('#c').style.color = 'white'">
			<a href="./coronavirus_2.html" id="c"><span>감염상황</span></a>
		</div>
	</div>
	<div class="line" style="position: relative; top: 20px; z-index: 0;"></div>
	<div style="position: absolute; top: 40px; z-index: 1;">
		<ul style="width: 300px; margin-left: 800px; margin-top: 100px;">
			<li style="color: red; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp1차 확진자<br><br><br></span></li>
			<li style="color: red; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp2차 확진자<br><br></span></li>
			<li style="color: red; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp3차 확진자<br><br></span></li>
			<li style="color: red; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp4차 확진자<br><br></span></li>
			<li style="color: red; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp5차 확진자<br></span></li>
			<li style="color: #FFC000; font-size: 60px; width: 300px; margin: 0;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp6차 확진자<br></span></li>
			<li style="color: red; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp7차 확진자<br><br></span></li>
			<li style="color: red; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp8차 확진자<br></span></li>
			<li style="color: #FFC000; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp9차 확진자<br></span></li>
			<li style="color: skyblue; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp10차 확진자<br></span></li>
			<li style="color: skyblue; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp11차 확진자<br><br></span></li>
			<li style="color: #FFC000; font-size: 60px; width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">&nbsp12차 확진자<br></span></li>
		</ul>
	</div>
	<div style="position: absolute; top: 30px; z-index: 1;">
		<ul style="width: 600px; margin-left: 1000px; margin-top: 130px;">
			<li class="time" style="width: 1200px;"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8; line-height: 2.1em">&nbsp중국인 女 36세 우한에서 감염<br><br><br></span></li>
			<li class="time" style="width: 1200px;"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 男 55세 우한에서 감염<br><br><br></span></li>
			<li class="time" style="width: 1200px;"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 男 54세 우한에서 감염<br><br><br></span></li>
			<li class="time" style="width: 1200px;"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 男 55세 우한에서 감염<br><br><br></span></li>
			<li class="time" style="width: 1200px; line-height: 4.7em"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 男 33세 우한에서 감염<br></span></li>
			<li class="time" style="width: 1200px; line-height: 4.7em"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 男 55세 3차 확진자와 접촉<br></span></li>
			<li class="time" style="width: 1200px;"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 男 28세 우한에서 감염<br><br><br></span></li>
			<li class="time" style="width: 1200px; line-height: 4.7em"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 女 62세 우한에서 감염<br></span></li>
			<li class="time" style="width: 1200px; line-height: 4.7em"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 女 28세 5차 확진자의 지인<br></span></li>
			<li class="time" style="width: 1200px; line-height: 5.5em"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 女 52세 6차 확진자의 아내<br></span></li>
			<li class="time" style="width: 1200px; line-height: 2.9em"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp한국인 男 25세 6차 확진자의 아들<br><br><br></span></li>
			<li class="time" style="width: 1200px;"><span class="Jua" style="font-size: 40px; color: gray; opacity: 0.8;">&nbsp중국인 男 49세 일본인 확진자와 접촉<br><br><br></span></li>
		</ul>
	</div>
	<div style="position: absolute; top: 30px; z-index: 1;">
		<ul style="width: 300px; margin-left: 450px; margin-top: 125px; line-height: 4.7em;">
			<li class="time" style="width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">2020.01.08<br><br><br></span></li>
			<li class="time" style="width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">2020.01.24<br><br></span></li>
			<li class="time" style="width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">2020.01.26<br><br></span></li>
			<li class="time" style="width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">2020.01.27<br><br></span></li>
			<li class="time" style="width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">2020.01.30<br><br><br><br></span></li>
			<li class="time" style="width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">2020.01.31<br><br><br><br><br></span></li>
			<li class="time" style="width: 300px;"><span class="Jua" style="font-size: 40px; color: black;">2020.02.01<br><br></span></li>
		</ul>
	</div>
	<div class="box_3">
		<ul>
			<li style="color: red; font-size: xx-large;"><span class="Jua" style="font-size: 25px; color: white;">1차 감염</span></li>
			<li style="color: #FFC000; font-size: xx-large;"><span class="Jua" style="font-size: 25px; color: white;">2차 감염</span></li>
			<li style="color: skyblue; font-size: xx-large;"><span class="Jua" style="font-size: 25px; color: white;">3차 감염</span></li>
			<li style="color: green; font-size: xx-large;"><span class="Jua" style="font-size: 25px; color: white;">4차 감염</span></li>
		</ul>
	</div>
	<div style="margin-left: 20px; margin-bottom: 20px">
		<span>Last-Update : 2020.02.01 10시<br>자료 출처 : 질병관리본부<br>아직 모바일은 지원이 안됩니다... 빠른 시일내에 추가하겠습니다.<br>추가하고 싶으신 기능들을 아래 이메일로 보내주시면 제가 할 수 있는 한도에서 추가해드립니다.<br>yuhanbae061@gmail.com</span>
	</div>
</body>
</html>
