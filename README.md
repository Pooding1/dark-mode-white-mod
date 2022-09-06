# dark-mode-white-mod
# 다크모드 만들기
# html코드
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title> dark mode / white mode </title>
<link rel = "stylesheet" type = "text/css" href = "./css/style.css">

<script type = "text/javascript">

	function dark(){
		document.body.style.backgroundColor = "black"; 
		document.body.style.color = "white";
		document.querySelector('h2').style.color = "gold";
	}

	function white(){
		document.body.style.backgroundColor = "white";
		document.body.style.color = "black";
		document.querySelector('h2').style.color ='pink';
	}
	
</script>
<title>다크모드/화이트모드</title>
</head>
<body>

	<h2>다크모드 만들어보기</h2>

	<ol>
		<li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
		<li>Integer ut risus finibus, porttitor eros vel, faucibus nunc.</li>
		<li>Donec suscipit arcu sed interdum tempus.</li>
	</ol>

	<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam
		nunc tellus, convallis eu risus ullamcorper, aliquet laoreet turpis.
		Nam ultrices faucibus malesuada. Vivamus ac augue sed turpis lacinia
		sagittis. Nullam id elit at metus scelerisque ullamcorper.
		Pellentesque ante eros, tincidunt at justo eleifend, tincidunt blandit
		justo. Aenean accumsan dui leo, nec suscipit tortor mollis eget.
		Maecenas at cursus ante, vestibulum ornare nulla. Suspendisse
		vulputate, justo ut auctor convallis, risus elit congue elit,
		ullamcorper fermentum purus nunc id lorem. Sed sed finibus leo. Fusce
		imperdiet dapibus ex, id rhoncus augue congue vitae.
	</p>

	<input type = "button" value = "dark mod" onclick = "dark()">
	<input type = "button" value = "white mod" onclick = "white()">
	<!--  <button onclick = "mode()"> dark mode </button> -->

</body>
</html>
```
# html 코드 설명
버튼을 눌러 웹페이지에서 다크모드와 화이트 모드를 번갈아가며 설정할수있다

function 함수를 활용하여 background 색상과 font 색상을 지정하였습니다

# css코드
```css
@charset "UTF-8";

*{
	font-family : "함초롱바탕"
}

body{
	width :	"500"
}
```
# css코드 설명
css코드로 폰트와 넓이를 설정하였다
