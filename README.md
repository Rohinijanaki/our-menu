<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width,initial scale=1">
	<title> Our Menu</title>
<style>
 
 *{
 	box-sizing: border-box;
 }
h1{
	margin-bottom: 15px;
	text-align: center;
}

p1{
	width: 100px;
	height: 25px;
	background-color: pink;
	border: 1px solid black;
	position: relative ;
	float: right;
	text-align: center; 
}
p2{
	width: 100px;
	height: 25px;
	background-color:  red;
	border: 1px solid black;
	position: relative ;
	float: right;
	text-align: center;
}
p3{
	width: 100px;
	height: 25px;
	background-color: yellow;
	border: 1px solid black;
	position: relative ;
	float: right;
	text-align: center;
}

.chicken{
	margin-bottom: 15px;
	border: 1px solid black;
	background-color: grey;
	width: 95%;
	height:95%;
}
.beef{
	margin-bottom: 15px;
	border: 1px solid black;
	background-color: grey;
	width: 95%;
	height:95%;
}
.sushi{
	margin-bottom: 15px;
	border: 1px solid black;
	background-color: grey;
	width: 95%;
	height:95%;
}
.row{
	width: 100%;
}
/************************ LARGE DEVICES ONLY *******************************/
@media (min-width: 992px){
	.col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8,.col-lg-9,.col-lg-10,.col-lg-11,.col-lg-12{
		float: left;
	}
	.col-lg-1{
		width: 8.33%;
	}
	.col-lg-2{
		width: 16.66%;
	}
	.col-lg-3{
		width: 25%;
	}
	.col-lg-4{
		width: 33%;
	}
	.col-lg-5{
		width: 41.66%;
	}
	.col-lg-6{
		width: 50%;
	}
	.col-lg-7{
		width: 58.33%;
	}
	.col-lg-8{
		width: 66.66%;
	}
	.col-lg-9{
		width: 74.99%;
	}
	.col-lg-10{
		width: 83.33%;
	}
	.col-lg-11{
		width: 91.66%;
	}
	.col-lg-12{
		width: 100%;
	}

}

/************************ MEDIUM DEVICES ONLY ******************************/
@media(min-width: 768px) and (max-width: 991px){
	.col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-md-5,.col-md-6,.col-md-7,.col-md-8,.col-md-9,.col-md-10,.col-md-11,.col-md-12{
		float: left;
	}
	.col-md-1{
		width: 8.33%;
	}
	.col-md-2{
		width: 16.66%;
	}
	.col-md-3{
		width: 25%;
	}
	.col-md-4{
		width: 33%;
	}
	.col-md-5{
		width: 41.66%;
	}
	.col-md-6{
		width: 50%;
	}
	.col-md-7{
		width: 58.33%;
	}
	.col-md-8{
		width: 66.66%;
	}
	.col-md-9{
		width: 74.99%;
	}
	.col-md-10{
		width: 83.33%;
	}
	.col-md-11{
		width: 91.66%;
	}
	.col-md-12{
		width: 100%;
	}
}
</style>
</head>
<body>
<h1>Our Menu</h1>
<div class="row">
	
	<div class="col-lg-4 col-md-6"><p class="chicken"><p1> Chicken </p1>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dignissimos ducimus rerum autem cum error earum deserunt debitis laudantium consectetur, aut temporibus. Totam, ratione odio ullam doloribus quis laudantium a rem nesciunt dolore sequi numquam eveniet, voluptas vitae enim recusandae. Pariatur.</p></div>

	<div class="col-lg-4 col-md-6"><p class="beef"><p2> Beef </p2>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dignissimos ducimus rerum autem cum error earum deserunt debitis laudantium consectetur, aut temporibus. Totam, ratione odio ullam doloribus quis laudantium a rem nesciunt dolore sequi numquam eveniet, voluptas vitae enim recusandae. Pariatur.</p></div>

	<div class="col-lg-4 col-md-12"><p class="sushi"><p3> Sushi </p3>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dignissimos ducimus rerum autem cum error earum deserunt debitis laudantium consectetur, aut temporibus. Totam, ratione odio ullam doloribus quis laudantium a rem nesciunt dolore sequi numquam eveniet, voluptas vitae enim recusandae. Pariatur.</p></div>

	
