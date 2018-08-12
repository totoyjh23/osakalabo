<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>OSAKA LABO</title>
    
	<style>
		.container{
			/*display: flex;*/
			/*flex-direction: column;*/
		}
		header{
			border-bottom: 1px solid gray;
			padding-left: 35px;
			
		}
		footer{
			border-top: 1px solid gray;
			text-align: center;
			
		}
		
		.content li a:hover{
			color: #000000;
			/*background-color: gray;*/
			/*display: flex;*/
			}
		ul { /*li안에 요소를 중앙배치를 위해서는 li에 디스플레이:인라인블럭을 준후 ul에 텍스트얼라인 센터*/
			
			list-style-type: none;
			/*margin: 0;
			padding: 0;*/
			/*overflow: hidden; 상자안에 "내용"을 자름. 화면이 표시가 안됨*/ 
			background-color: white;
			text-align: center;
			/*display: flex;*/
			
		}
		li{
			display: inline-block;
			
		}
		li a{
			display: block;
			color: gray;
			padding: 14px 16px;
			text-decoration: none;
			/*background-color: black;*/
			/*align-items: center;*/ 
			/*float: left;*/
		}
		nav{
			
		}
		main{
			/*text-align: center;*/
			
		}
		
		div .columns{
			column-width:350px;
			/*column-count: 4;*/
			column-gap: 15px;
			/*padding: 5%;*/
			max-width: 1100px;
			margin: 50px auto; /*피규어의 정중앙에 위치하기 위해서는 옆의 값을 부여.*/
			
		  }
		.columns figure{
			display: inline-block;
			border:1px solid rgba(0,0,0,0.2);
			margin:0;
			margin-bottom: 15px;
			padding:10px;
			box-shadow: 2px 2px 5px rgba(0,0,0,0.5);
			text-align: center;
		  }
		 .columns figure img{
			width:100%;
		  }
		 .columns figure figcaption{
			border-top:1px solid rgba(0,0,0,0.2);
			padding:10px;
			margin-top:11px;
		  }
           /*드롭다운 메뉴*/
				.dropbtn {
					background-color: white;
					color: gray;
					padding: 16px;
					font-size: 16px;
					border: none;
					cursor: pointer;
				}
				.dropdown {
					position: relative;
					display: inline-block;
				}
				.dropdown-content {
					display: none;
					position: absolute;
					background-color: white;
					min-width: 160px;
					box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
					z-index: 1;
				}
				.dropdown-content a {
					color: black;     /*드롭메뉴(하위메뉴 텍스트) 색깔.*/
					padding: 12px 16px;
					text-decoration: none;
					display: block;
				}
				.dropdown-content a:hover {background-color: aquamarine}
				.dropdown:hover .dropdown-content {
					display: block;
				}
				.dropdown:hover .dropbtn {  
					background-color: aquamarine;   /*마우스오버 했을 경우 바뀌는 색*/
					color: black;
				}
		#menu1{
			border-bottom: solid #DD7375;
			color: black;
		}
		/*드롭다운메뉴*/
	</style>
	
</head>
	
<body>
	<div class="container">
		<header>
			<h1><a href="#"></a>OSAKA LABO.</h1>
		</header>
		<section class="content">
			<nav>
				<ul>
					<li> <a id=menu1 href="file:///D:/web/en.osakalabo-index.html">Main</a></li>
					<li> <a id=menu2 href="file:///D:/web/osakalabo-photo.html">Photo</a></li>
					<li> <a id=menu3 href="file:///D:/web/osakalabo-blog.html">Blog</a></li>
					<li> <a id=menu4 href="file:///D:/web/osakalabo-videos.html">Videos</a></li>
					<li> 
						<div class="dropdown">
							<button class="dropbtn" >Language</button>
								  <div class="dropdown-content">
									<a href="file:///D:/web/jp.osakalabo-index.html">JAPAN</a>
									<a href="file:///D:/web/kr.osakalabo-index.html">KOREA</a>
									<a href="file:///D:/web/ch.osakalabo-index.html">CHINA</a>
								  </div>
						</div>
					</li>
					 
				</ul>
			</nav>
			
			<main>
			  	텍스트 시험중.
				<div class="columns">
      
				  <figure>
					<img src="D:\web\img\IMG_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>

				  <figure>
					<img src="D:\web\img\img_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>

				  <figure>
					<img src="D:\web\img\img_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>

				  <figure>
					<img src="D:\web\img\img_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>

				  <figure>
					<img src="D:\web\img\IMG_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>

				  <figure>
					<img src="D:\web\img\img_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>

				  <figure>
					<img src="D:\web\img\img_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>

				  <figure>
					<img src="D:\web\img\img_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>
      
				<figure>
					<img src="D:\web\img\img_1105.jpg">
					<figcaption>test-kr</figcaption>
				  </figure>
   			 </div>
			</main>
			<aside>
			 	광고
			</aside>
		</section>
		<footer>
			<a href="http://www.osakalabo.com">홈페이지</a>
		</footer>
	</div>
</body>
</html>
