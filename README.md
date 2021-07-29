<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>演習7-1(おみくじ) 学籍番号:M19W7128</title>
</head>
<body>
	<h3>おみくじ</h3>
<div id="ss">あなたの運勢は？</div><br>
	<button onclick="bb()">占い</button>
	
	<script>
  
 function bb(){
  let nn=["大吉","中吉","吉","凶"];
    let index = Math.floor((Math.random()*nn.length));

document.querySelector("#ss").textContent="あなたの運勢は:"+nn[index];
}
	</script>

</body>
</html>
