<!DOCTYPE html>
<html>
<style>
	p {
		text-align: center;
		font-size: 200%;
		font-style: bold;
	}
	h3{
		text-align: center;
		font-size: 120%;
		font-style: bold;
	}
	h4 {
		text-align: center;
		font-size: 100%;
		font-style: bold;
	}
	img {
  		display: block;
  		margin-left: auto;
  		margin-right: auto;
	}
	.item1{grid-area: header;}
	.item2{grid-area: menu;}
	.item3{grid-area: image;}
	.grid-container {
 		display: grid;
  		grid-template-areas:
    		'header header header header header header'
    		'menu menu menu image image image'
    		'menu menu menu image image image';
  		grid-gap: 0px;
  		padding: 0px;
	}
	.grid-container > div {
	  	padding: 0;
	  	font-size: 30px;
	}

</style>
<head>
	<script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>
<body>
	<div class="grid-container">
  		<div class="item1"><p text-align: center;><b> Lâm Phước Đạt </b></p></div>
		<div class="item2">
			<h3>About Me</h3>
			<h4>Study</h4>
			<ol>
				<li>Majoring in Computer Science <i class="fas fa-laptop"></i></li>
				<li>Love programming and learning more algorithms <i class="fab fa-python"></i></li>
			</ol>
			<h4>Hobbies</h4>
			<ol>

				<li>Volleyball <i class="fas fa-volleyball-ball"></i></li>
				<li>Swimming <i class="fas fa-swimmer"></i></li>
				<li>Listening <i class="fas fa-headphones-alt"></i></li>
				<li>Reading <i class="fas fa-book"></i></li>
			</ol>
		</div>
		<div class="item3"><img src="https://media.giphy.com/media/hX6zuSyNhaSiOukKUp/giphy.gif" width="300" height="500" /></div>
	</div>

</body>
</html>


