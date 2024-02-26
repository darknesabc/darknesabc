<!DOCTYPE html>
<html lang="en-US">
<head>
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>timetableRS</title>
<meta name="generator" content="Jekyll v3.9.3" />
<meta property="og:title" content="timetableRS" />
<meta property="og:locale" content="en_US" />
<link rel="canonical" href="https://darknesabc.github.io/darknesabc/" />
<meta property="og:url" content="https://darknesabc.github.io/darknesabc/" />
<meta property="og:site_name" content="timetableRS" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="timetableRS" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"timetableRS","name":"timetableRS","url":"/"}</script>
<!-- End Jekyll SEO tag -->
<link rel="stylesheet" href="/darknesabc/assets/css/style.css?v=e168cf9de67c87c05680e001aa3bba55edffe645">
<style>
/* Custom CSS styles */
</style>
</head>
<body>
<div class="container-lg px-3 my-5 markdown-body">
<h1><a href="https://darknesabc.github.io/darknesabc/">timetableRS</a></h1>
<p>&lt;!DOCTYPE html&gt;</p>
<html lang="ko">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>러셀 이동일지 작성</title>
<style>
/* Custom CSS styles */
</style>
</head>
<body>
<h1>러셀 이동일지 작성</h1>
<button id="resetButton" onclick="resetTable()">테이블 초기화</button>
<form id="moveForm">
<label for="building">관:</label>
<select id="building" required="">
<option value="7-1관">7-1관</option>
</select><br />
<label for="seatNumber">좌석번호:</label>
<select id="seatNumber" required="">
<option value="">선택하세요</option>
<optgroup label="A~I">
<option value="A">A</option>
<option value="B">B</option>
<option value="C">C</option>
<option value="D">D</option>
<option value="F">F</option>
<option value="G">G</option>
<option value="H">H</option>
<option value="I">I</option>
<option value="J">J</option>
<option value="K">K</option>
<option value="L">L</option>
<option value="M">M</option>
</optgroup>
</select>
<select id="seatNumber2" required="">
<option value="">선택하세요</option>
<optgroup label="1~40">
<option value="01">01</option>
<option value="02">02</option>
<option value="03">03</option>
<!-- Add more options if needed -->
</optgroup>
</select><br />
<label for="returnTime">복귀교시:</label>
<select id="returnTime" required="">
<option value="">선택하세요</option>
<option value="1">1교시</option>
<option value="2">2교시</option>
<option value="3">3교시</option>
<!-- Add more options if needed -->
</select><br />
<label for="reason">이동사유:</label>
<select id="reason" required="">
<option value="">선택하세요</option>
<option value="지각">지각</option>
<option value="입/퇴실 미준수">입/퇴실 미준수</option>
<option value="화장실/정수기">화장실/정수기</option>
<!-- Add more options if needed -->
</select><br />
<button type="submit">제출</button>
</form>
<div id="result">
<table id="moveList" border="1">
<thead>
<tr>
<th>관</th>
<th>좌석번호</th>
<th>복귀교시</th>
<th>이동사유</th>
<th>입력날짜</th>
<th>입력시간</th>
</tr>
</thead>
<tbody>
<!-- Table body content will be dynamically added -->
</tbody>
</table>
</div>
</div>
<script>
// JavaScript code
</script>
</body>
</html>
</div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
<script>anchors.add();</script>
</body>
</html>
