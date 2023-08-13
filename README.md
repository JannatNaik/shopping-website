# shopping-website
<html>
<head>
    <meta charset="utf-8">
	<title>shopping cart</title>
	<style type="text/css">
	    @import url("https://stackpath.bootsrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css");
		.{
		   padding: 0;
		   margin: 0;
		   color: #454545;
		}
		h1{
		   width: 3%;
		   position: relative;
		   top: 60px;
		   left; 90%;
		   cursor: pointer;
		}
		h1:before{
		   content: attr(data-count);
		   position: absolute;
		   color: white;
		   right: 16px;
		   font-size: 15px;
		   text-align: center;
		   top: -12px;
		   width: 20px;
		   height: 20px;
		   background:red;
		   border-radius: 50px;
		   opacity: 0;
		}
		section{
		   width: 90%;
		   height: 400px;
		   display: flex;
		   justify-content: space-around;
		   margin: 100px auto;
		}
		section div{
		   width: 22%;
		   height: 93%;
		   background: #f5f5f5;
		   padding: 1%;
		   position: relative;
		}
		img{
		   width: 300px;
		   height: 186px;
		}
		p{
		   margin: 5px;
		}
		h6{
		   width: 50px;
		   padding: 50px;
		   margin: 10px;
		   font-size: 15px;
		}
		button{
		   padding: 5px;
		   background: red;
		   border: none;
		   outline: none;
		   font-weight: bold;
           color: #fafafa;
		   cursor: pointer;
		   transition: 1s;
		}
		section div span{
		   position: absolute;
		   top: 14px;
		   left: 13px;
		   width: 300px;
		   height: 186px;
		   display: none;
		   
		}
		section div span img{
		   width: 100px;
		   height: 100px;
		}
		.select{
		   width: 60%;
		   height: 580px;
		   background: #222;
		   position: absolute;
		   top: -100px;
		   left: 20px;
		   transition: 0.5s;
		   overflow-y: auto;;
		   margin: auto;
		}
		.select div{
		   width: 100%;
		   height: 200px;
		   display: flex;
		   padding: 5px;
		   border: 1px solid white;
		   position: relative;
		   margin: 5px auto;
		}
		.select div img{
		   width: 300px;
		   height: 100px;
		}
		.select div p{
		   padding: 35px;
		   color: white;
		}
		.select div h6,
		.select div button{
		   position: absolute;
		   left: 45%;
		   top: 50%;
		   color: white;
		}
		.select
	</style>	
</head>
<body>
    <h1><i class="fa fa-shopping-cart"></i></h1>
	<section>
	    <div>
		    <img src="043.jpg">
			<p>srdyugfuihoiji yuyi8 dyguhiu arcyoij stdytui iijoijkihj iuygiuihuhi uguiuuhomljoij</p>
			<h6>390</h6>
			<span></span>
			<button>add-cart</button>
		</div>
		<div>
		      <img src="043.jpg">
			<p>srdyugfuihoiji yuyi8 dyguhiu arcyoij stdytui iijoijkihj iuygiuihuhi uguiuuhomljoij</p>
			<h6>390</h6>
			<span></span>
			<button>add-cart</button>
		</div>
		<div>
		      <img src="043.jpg">
			<p>srdyugfuihoiji yuyi8 dyguhiu arcyoij stdytui iijoijkihj iuygiuihuhi uguiuuhomljoij</p>
			<h6>390</h6>
			<span></span>
			<button>add-cart</button>
		</div>
		<div>
		      <img src="043.jpg">
			<p>srdyugfuihoiji yuyi8 dyguhiu arcyoij stdytui iijoijkihj iuygiuihuhi uguiuuhomljoij</p>
			<h6>390</h6>
			<span></span>
			<button>add-cart</button>
		</div>
	</section>
</body>
</html>
