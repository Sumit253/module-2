<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>
		Module 2 Solutions 
	</title>
	<link rel="stylesheet" href="mod2.css">
</head>
<style>
	*{
	box-sizing: border-box;
}
p {
	 border: none;
	 margin-left: 0;
}

h1{
	font-family: Helvetica;
	color: black;
	text-align: center;
	margin-bottom: 15px;
}
.container {
	border: none;
	margin-left: auto;
	margin-right: auto;
	margin-top: 10px;
	margin-bottom: 10px;
	padding: 10px;
}

section {
	border:	1px solid black;
	background-color: grey;
	width: 100%;
	height: 200px;
	font-family: Helvetica;
	color: black;
	position: relative;
	overflow: auto;
}
#Sweet {
	border: 1px solid black;
	text-align: center;
	width: 30%;
	margin-left: 70%;
	font-family: Georgia,sans-serif;
	font-weight: bold;
	font-size: 125%;
	margin-bottom: 0;
	margin-top: 0;
	padding: 5px;
	background-color: blue;
}

#Lorem {
	border: 1px solid black;
	text-align: center;
	width: 30%;
	margin-left: 70%;
	font-family: Georgia,sans-serif;
	font-weight: bold;
	font-size: 125%;
	margin-bottom: 0;
	margin-top: 0;
	padding: 5px;
	background-color: green;
}

#Life {
	border: 1px solid black;
	text-align: center;
	width: 30%;
	margin-left: 70%;
	font-family: Georgia,sans-serif;
	font-weight: bold;
	font-size: 125%;
	margin-bottom: 0;
	margin-top: 0;
	background-color: pink;
	color: white;
	padding: 5px;
}

.row{
	width: 100%
}
@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
   
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}

@media (min-width:768px ) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
   
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}
@media (max-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
 	float: left;
  }

  .col-sm-1 {
    width: 8.33%;
  }
  .col-sm-2 {
    width: 16.66%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-4 {
    width: 33.33%;
  }
  .col-sm-5 {
    width: 41.66%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-7 {
    width: 58.33%;
  }
  .col-sm-8 {
    width: 66.66%;
  }
  .col-sm-9 {
    width: 74.99%;
  }
  .col-sm-10 {
    width: 83.33%;
  }
  .col-sm-11 {
    width: 91.66%;
  }
  .col-sm-12 {
    width: 100%;
  }
}
</style>
<body>
<h1>Something Interesting</h1>
	<div class="row">
		<div class="container col-lg-4 col-md-6">
		<section>
		<div id="Sweet">
		Sweet
		</div>
		<p> An extension for Sublime Text 2 and 3! It allows you to Insert Lorem Ipsum in the editor via menu items or keyboard shortcut. Select how much text you want from the menu item in Edit->Text->Lorem Ipsum or on the right click menu in Lorem Ipsum . Just press the shortcut key (Alt+Shift+L) to add Lorem Ipsum text.</p>
		</section>
	 </div>	
		<div class="container col-lg-4 col-md-6">
		<section>
			<div id="Lorem">
				Lorem
			</div>
		<p> An extension for Sublime Text 2 and 3! It allows you to Insert Lorem Ipsum in the editor via menu items or keyboard shortcut. Select how much text you want from the menu item in Edit->Text->Lorem Ipsum or on the right click menu in Lorem Ipsum . Just press the shortcut key (Alt+Shift+L) to add Lorem Ipsum text.</p>
		</section>
		</div>
		<div class="container col-lg-4 col-md-6">
			<section>
			<div id="Life">
				Life
			</div>
		<p> An extension for Sublime Text 2 and 3! It allows you to Insert Lorem Ipsum in the editor via menu items or keyboard shortcut. Select how much text you want from the menu item in Edit->Text->Lorem Ipsum or on the right click menu in Lorem Ipsum . Just press the shortcut key (Alt+Shift+L) to add Lorem Ipsum text.</p>
	</section>
	</div>

	</div>
</body>
</html>
