# jandj.html
j&amp;j merch
<!DOCTYPE html>
<html>
<title>J&J© | Merch</title>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

		*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Verdana', sans-serif;
}

body {
margin:0;
  height: 100vh;
  background: linear-gradient(to right, #0EC8D6, #F0F74E);
  display: flex;
  justify-content: center;
  align-items: center;

}

.navbar {
  overflow: hidden;
  background-color: #333;
  position: fixed;
  top: 0;
  width: 100%;
}

.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.navbar a:hover {
  background: #ddd;
  color: black;
}

.main {
  padding: 16px;
  margin-top: 30px;
  height: 3500px; /* Used in this example to enable scrolling */
}


.container{
  width: 65%;
  height: 400px;
  max-width: 960px;
  margin: 0 auto;
  padding: 30px;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 1540px;
  border-radius: 20px;
  opacity: 1;
}
.ye{
  font-size: 90px;
  font-weight: bold;
  background: linear-gradient(to bottom, #0EC8D6, #F0F74E);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  max-width: 350px;
  text-transform: uppercase;
  line-height: 1;
  text-align: center;
}

.containerYE {
  width: 70%;
  height: 150px;
  max-width: 960px;
  margin: 0 auto;
  padding: 30px;
  background: #FFFFFF;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 400px;
  border-radius: 20px;
  
}

.yeYE{
  font-size: 50px;
  font-weight: bold;
  background: linear-gradient(to right, #0EC8D6, #F0F74E);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  max-width: 350px;
  text-transform: uppercase;
  line-height: 1;
  text-align: center;
}

#pro {
	opacity: 1;
}

#picone {
	margin-top: 50px;
	margin-left: -20px;
	width: 280px;
}

#pictwo {
	margin-top: 50px;
	margin-left: 50px;
	width: 280px;
}

.footer {
	position: absolute;
	background: white;
	width: 100%;
	height: 50px;
	margin-top: 1800px;
	
}

</style>
<link rel="shortcut icon" href="https://img.icons8.com/cotton/64/000000/shopping.png" type="image/x-icon">
</head>
<body>

<div class="navbar">
  <a href="#home">Home</a>
  <a href="#products">Products</a>
  <a href="#contact">Contact</a>
</div>

<div class="main" id="home">

  
  <div class="container" id="top">
    <p class = "ye">
      J&J MERCH
    </p>
	</div>
	<div class="containerYE" id="pro">
    <p class="yeYE" id="products">
      products
    </p>
	</div>
	<img src="https://mms-images.out.customink.com/mms/images/catalog/colors/295002/views/alt/front_large_extended.png?design=cue0-00c4-8b20&pblegacy=1&pblegacysize=big&pblegacywm=1" class = "pic" id = "picone"></img>
	<img src="https://mms-images.out.customink.com/mms/images/catalog/colors/295002/views/alt/back_large_extended.png?design=cue0-00c4-8b20&pblegacy=1&pblegacysize=big&pblegacywm=1" class = "pic" id = "pictwo"></img> 
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>

<script>
$(window).scroll(function(){
    $("#top").css("opacity", 1 - $(window).scrollTop() / 250);
  });
</script>
</body>
</html>
