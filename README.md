# Sublime-Website-
Just a basic website, need to add a background image.
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>Mobile First</title>
		<link href='http://fonts.googleapis.com/css?family=Roboto' rel='stylesheet' type='text/css'>
		<style type="text/css">
		body{
		background-image: url("../Pictures/img/codeinstitute.jpg"); /*to set the background image*/
		background-size: cover;
		}
			#container
			{
				margin-right:auto; 
				margin-left:auto;
				position: relative;		
				width:960px;	
				border-radius: 10px;
				padding: 10px;
				font-size: 0; 
				
			}
			.box{
				position: relative;		
				width: 100%;
				background-color: #81BBC9;
				margin-bottom: 10px;
				border-radius: 10px;
				font-family: Roboto;
				font-size: 20px;
				text-align: center;
				padding: 30px 0;
			}
								
			.sidebar{
				box-sizing:border-box;
				display: inline-block;
				width:470px;
				margin-right: 10px;
				padding-left: 10px;
				padding-right: 10px;
			}
			.content{
				box-sizing:border-box;
				display: inline-block;
				width:470px;
				margin-left: 10px;
				padding-left: 10px;
				padding-right: 10px;
			}
			#toTopRight{
				position: absolute; 	/* Absolute Link */
				bottom:0;				/* Offset however we wish*/
				right:-80px;
			}
			#toTopLeft{
				position: absolute; 	/* Absolute Link */
				bottom:0;				/* Offset however we wish*/
				left:-80px;
			}
			p{
				padding-bottom: 50px;
			}
		
				 @media screen and (max-width: 600px){   /* width for screen less than 600px */
        			
           			 .box{
		                   text-align: left;
		          		   background-color:#eee;
		          		   border-color: white;
 
		              
           			 }
           			}
           			@media screen and (min-width: 1000px){   /* width for screen over 1000px */
        			
           			 .box{
		                   
		          		  color: black;
		          		  border-color: white;
 
		              
           			 }
           			}
  			 	
			
		</style>
	</head>
	<body>
		<div id="container">
			
			<div id="header" class="box"> <h1>Header</h1>
			</div>
			<div class="box sidebar">
				<h2>Sidebar</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed dolor esse cumque unde, explicabo totam, in sequi iste recusandae ipsa laudantium, neque excepturi molestias modi velit animi asperiores suscipit? Voluptas.</p><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed dolor esse cumque unde, explicabo totam, in sequi iste recusandae ipsa laudantium, neque excepturi molestias modi velit animi asperiores suscipit? Voluptas.</p>
			
			</div>
			<div class="box content">
				<h2>Content</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed dolor esse cumque unde, explicabo totam, in sequi iste recusandae ipsa laudantium, neque excepturi molestias modi velit animi asperiores suscipit? Voluptas.</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed dolor esse cumque unde, explicabo totam, in sequi iste recusandae ipsa laudantium, neque excepturi molestias modi velit animi asperiores suscipit? Voluptas.</p>
				
			</div>
			<div class="box sidebar">
				<h2>Sidebar</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed dolor esse cumque unde, explicabo totam, in sequi iste recusandae ipsa laudantium, neque excepturi molestias modi velit animi asperiores suscipit? Voluptas.</p><p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed dolor esse cumque unde, explicabo totam, in sequi iste recusandae ipsa laudantium, neque excepturi molestias modi velit animi asperiores suscipit? Voluptas.</p>
				<a href="#" alt="Link to top"><img id="toTopLeft" src="img/arrow.png"></a>
			
			</div>
			<div  class="box content">
				<h2>Content</h2>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed dolor esse cumque unde, explicabo totam, in sequi iste recusandae ipsa laudantium, neque excepturi molestias modi velit animi asperiores suscipit? Voluptas.</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed dolor esse cumque unde, explicabo totam, in sequi iste recusandae ipsa laudantium, neque excepturi molestias modi velit animi asperiores suscipit? Voluptas.</p>
				<a href="#" alt="Link to top"><img id="toTopRight" src="file:///C:/Users/Byron C-S/Pictures/arrow.png"></a>
			</div>
			<div id="footer" class="box"><h2>Footer</h2>
			</div>

		</div>
	</body>
</html>
