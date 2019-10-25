# 成功電研33rd網管資格測驗 網頁組 筆試題 #
規則請看[說明](../README.md)  
## 題目開始 ##
1. 請解釋`function`和`arrow function`的差異
2. 請說明至少3個HTML5和以往版本的差異
3. 請解釋`class`和`object`的關係
4. 請說明至少三個變數轉型的例子(例如物件轉字串)
5. 請舉例一種HTML5的Web API
6. 接上題，請說明此API的使用方法
7. 請比較瀏覽器環境以及node環境的差異(至少三項)
8. 請比較`var const let`差異及使用時機
9. 狸貓寫了以下程式碼，發現每次執行比對結果不同，請提出解決方法(此題用js程式碼作答):
```js
var regexp = /rac/g
var str = 'raccoon is cute';
console.log(regexp.test(str));	//true
console.log(regexp.test(str));	//false
console.log(regexp.test(str));	//true
console.log(regexp.test(str));	//false
```
10. 以下是一個網頁，請問如何以jQuery改變序號(此題用js程式碼作答)：
```html
<html>
	<head>
		<title>喜來登生日餐券</title>
		<style>
			.coupon{
				margin: 30px;
				padding: 10px;
				background-color: rgba(240,240,240,240);
			}
			
			.row{
				display: grid;
				grid-template-columns: 50% 50%;
			}
		</style>
	</head>
	<body>
	 	<div class="coupon">
			<div class="title">
				<a href="http://www.sheratongrandtaipei.com/restaurant.php"<h1>喜來登</h1></a>
				<h2>SHERATON</h2>
			</div>
			<div class="row">
				<div class="content col">
					<img class="icon" src="https://upload.wikimedia.org/wikipedia/zh/8/8a/Sheraton.gif">
					<h3>喜來登生日餐券</h3>
					<p>限當天生日者有效</p>
				</div>
				<div class="content col">
					<p>序號：<span>212070707</span></p>
					<p>有效日期:<span>2020/07/07</span></p>
				</div>
			</div>
		</div>

	</body>
</html>
```
11. 請舉例兩個將網頁內容水平、垂直置中的方法(此題用程式碼作答)
12. 請問JS是非同步程式語言還是同步程式語言？請解釋兩者差異
13. 請問列出HTML tag 中 <a> 的三種用法
14. 請舉例一個JS前端框架

---

筆試題到此結束，請繼續作答實作題
