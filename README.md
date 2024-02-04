# ashortridge.github.io
<!doctype html>

<html lang="en">
<head>

	echo "# ashortridge.github.io" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git branch -M main
	git remote add origin https://github.com/ashortridge/ashortridge.github.io.git
	git push -u origin main

	<meta charset="utf-8">
	
	<title>My Final Webpage</title>
	
		<style type="text/css">
			
			/* http://meyerweb.com/eric/tools/css/reset/ 
	   v2.0 | 20110126
	   License: none (public domain)
	*/

		html, body, div, span, applet, object, iframe,
		h1, h2, h3, h4, h5, h6, p, blockquote, pre,
		a, abbr, acronym, address, big, cite, code,
		del, dfn, em, img, ins, kbd, q, s, samp,
		small, strike, strong, sub, sup, tt, var,
		b, u, i, center,
		dl, dt, dd, ol, ul, li,
		fieldset, form, label, legend,
		table, caption, tbody, tfoot, thead, tr, th, td,
		article, aside, canvas, details, embed, 
		figure, figcaption, footer, header, hgroup, 
		menu, nav, output, ruby, section, summary,
		time, mark, audio, video {
			margin: 0;
			padding: 0;
			border: 0;
			font-size: 100%;
			font: inherit;
			vertical-align: baseline;
		}
		/* HTML5 display-role reset for older browsers */
		article, aside, details, figcaption, figure, 
		footer, header, hgroup, menu, nav, section {
			display: block;
		}
		
		/*
			font-family: 'Cardo', serif;
			font-family: 'Josefin Sans', sans-serif;
			font-family: 'Josefin Slab', serif;
			*/

		body {
			line-height: 1;
			font-family: 'Cardo', serif;
		}
		
		article>p{
			line-height: 130%;
		}
		
		h1,h2, h3, h4, h5, h6{
			font-family: 'Josefin Sans', sans-serif;
			color: #3B6400;
			letter-spacing: .025em;
		}
		
		h1{
			font-size: 2em;
			font-weight: bold;
		}
		
		h2{
			font-size: 1.7em;
			font-weight: bold;
		}
		
		ol, ul {
			list-style: none;
		}
		blockquote, q {
			quotes: none;
		}
		blockquote:before, blockquote:after,
		q:before, q:after {
			content: '';
			content: none;
		}
		table {
			border-collapse: collapse;
			border-spacing: 0;
		}
		
			#wrapper{
				width: 80.56640625%;
				margin: 0 auto;
				background-color: #A1BA7C
			}
			
			nav{
				margin: 0 auto;
				background-color: #598679;
				padding: 1% 0;
			}
			
			nav ul{
				width: 85.57575757575758%;
				margin: 0 auto;
			}
			
			nav ul li{
				display: inline;
				margin-right: 2%;
			}	
			
			body{
				background-color: #003122;
			}
			header{
				background-color: white;
				padding: 3%;
			}
			
			#feature{
				width: 81.32575757575758%;
				margin: 3% auto 4% auto;
				background-color: white;
				overflow: hidden;
				padding: 1.5% 2.25% 3.5% 2.25%;
			}
			
			.feature-img{
				float: left;
				width: 40%;
			}
			.feature-text{
				float: left;
				width: 58%;
				margin-left: 2%;
				font-family: 'Josefin Slab', serif;
				font-size: 1.65em;
				font-weight: bold;
				line-height: 115%;
				letter-spacing: .025em;
			}
			
			#main-content{
				width: 59.39393939393939%;
				float: left;
				margin: 2%;
			}
			
			.main-figure{
				width: 32.50478011472275%;
				margin-right: 9.56022944540669%;
				float: right;
			}
			
			#sidebar{
				width: 32.60606060606061%;
				float: left;
				margin: 2%;
			}	
			
			.side-figure{
				width: 88.0794701986755%;
				margin: 0 auto;
				padding: bottom: 2%;
			}
			
			figure img{
				max-width: 100%;
			}
			
			figure{
				background-color: #EAEBE9;
			}
			footer{
				clear: left;
				padding: 2%;
			}
			
			footer p{
				margin: 0;
			}
			
			/*type styles*/
			#feature h2{
				margin-bottom: 2%;
			}
			
			p{
				margin: 2.5% 0;
			}
			
			figcaption{
				font-family: 'Josefin Slab', serif;
				margin: 3%;
			}
			
			#sidebar figcaption{
				margin-bottom: 6%;
			}
			
			.nav-item{
				display: inline-block;
				margin-left: 2%;
				background-color: white;
			}
			
			li.nav-item a:hover{
				color: white;
				background-color: #003122;
			}
			
			li.nav-item a:link{
				color: red;
			}
			
		</style>
		
		
		<!--[if lt IE 9]>
		<script src="
		https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.js"></script>
	<![endif]-->
	
</head>

<body>
	<div id="wrapper">
		<header>
			<h1>Traveling soccer<h1>
		</header>
		
		<nav>
			<ul>
				<li class="nav-item"><a href="FinalMultiColumn.html">page 1</a></li>
				<li class="nav-item"><a href="MultiColumn2.html">page 2</a></li>
				<li class="nav-item"><a href="MultiColumn4.html">page 4</a></li>
				<li class="nav-item"><a href="MultiColumn5.html">page 5</a></li>

			</ul>
		</nav>
		
		<div id="feature">
			<h2>Traveling</h2>
			
			<img src="
			https://www.publicdomainpictures.net/pictures/310000/velka/airplane-flying-1567519936cAo.jpg" class="feature-img"/> 
			
			<p class="feature-text">Most soccer players that want to play competitive
			soccer will join a club that travels to different states to play different levels of 
			competition. Most of these soccer players will then go off to play some kind of 
			level of soccer in college.
				</p>
		</div>
		
		<div id="main-content">
			<article>
				<h2>Traveling costs</h2>
				<figure class="main-figure">
					<img src="
					https://thedestinyformula.com/wp-content/uploads/2017/11/hith-8-things-you-may-not-know-about-american-money-2.jpg" />
					<figcaption>
						<p>Money</p>
					</figcaption>
				</figure>
				<p>
				Most people know that traveling almost anywhere is not cheap at all. When you add
				a sport into the mix makes if so much more. Most players if flying with their team
				are aloud one carry on or checked bag and one personal iteam to prevent uniforms
				and equipment from potentially getting lost.
				</p>
				<p>
				I would probably say most famlies when traveling for a sport look for the cheapiest option 
				even if it means driving 6-8 hours for a weekend tounrament. This can create losts of family bonding 
				that some famlies amy not want and opt to spend the money to fly and save the time. A lot of familes
				like to rent one big car and share if they are planning on flying and split the cost per person.
				</p>
				<p>
				Another thing you have to consider when flying to a tournament is the
				cost of things you will not be able to bring with you. For example the cost of renting a car, food,
				fun activities or team bonding, ect.
				</p>
			</article>
		</div>
		<div id="sidebar">
			<article>
				<h2>Offsetting the costs</h2>
				<figure class="side-figure">
					<img src="
					https://lh3.googleusercontent.com/t5jGxZKRYy7l-YzC5s8YlvZfqIkCUZxLJksHTM75YLYiKg3OtN-EwsH22yRb59vuoZtmYXYM6qXupx1ZE-QARh1qnyq_HRWioYUfdcKaUSkSO6KqYEMmY8NkDCTs4zop2E_TXFVHoT6mmMJ9ABQ2l5uNwfYNJI9qp8SSRtOELLiAO-OdI16e2KPlYno--srRRoSj3Jy4HGD6akicHCtsUyseUbVGpG8a0_CG3bnVa1MZDW2Ez8eHcYKKMh38gxfiVti8qIcj6ET41l8-7WUQYILMAx0NxPJuNKfZgLwDA6zrDscOH6GBmAHpxWrGeaYBWMzBEZj-zfLt2b7Rdidb-JYy_WYuyen6mqYZgiTc-ZIyHX9vVaZZb008PSUmUt_Aus6PurjY6VxCdRbYEI4NplhZ_mfigglfsYopeiWGhv3yeHlgLiEMrJdEOCkh2nT0cVltnOza43-uTa_YwF80rmpKcYXV0iX033X5VDKFyCnx_ew9hataxtMx61AzABZ4Yic6-vTEjD9SvZiNL5-y7K6-MvPYMMBL1QNMS-fu-WBv4NB5iFPYFQShOJSEf3dM174DjDVfyRbnyGBlQsVwG88atpVMXLGuJHFLoA0ygV1_V-12h80vJO899VN2rNBDceyKhi0Tt5VOg42e7PremgUp_2wJUYfXkA=w1102-h826-no" />
					<figcaption>
						<p>Bagging at Cub foods</p>
					</figcaption>
				</figure>
				<p>
				My team likes to do Cub food bagging as a way of offset our travel fees.
				This is also a nice way of getting in some team bonding throught the season.
				Some other things that can be done to offset the cost are selling
				Bettys pies, football cards, or butter braids. The most common one 
				that makes a lot of money for us in the Cub food bagging and selling 
				the football cards since with the cards there is a chance at winning some money
				each week during the NFL season.
				</p>
			</article>
		</div>
	<div>
		<footer>
			<p><small>Aleah Shortridge, Febuary 2024</small></p>
		</footer>
	</div><!--Close wrapper-->

</body>
</html>
