# tugas-website
Desain sebuah website
<!DOCTYPE>
<html lang="en">
<head>
	<title>CSS Website layout</title>
	<meta charset="utf_8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
	
<style>

	.topnav {
		overflow :hidden;
		background-color: black;
		}
	.topnav a{
		float: left;
		display: block;
		position:relative;
		color: white;
		text-align: center;
		padding: 16px 16px;
		text-decoration: none;
		margin-top: 15px;
		margin-bottom : 10px;
		}
	.topnav a:hover{
		background-color: gray;
		color: white;
		}

	* {
		box-sizing: border-box;
		}
	.caption {
			font-size: 13px;
			margin-top: 5px;
			font-weight: bold;
			}
	*	
	{
		margin: 0;
		padding: 0;
		box-sizing: border-box;
		font-family: Arial, Helvetica, sans-serif;
		}
 
body
		{
		background-color: pink;
	}
 
.badan
	{
		width: 100%;
		margin: 15px auto;
		background-color: white;
		padding: 20px;
		overflow: hidden;
	}
 
.badan h2
	{
		color: crimson;
		border-bottom: 1px solid gainsboro;
		margin: 5px;
		margin-bottom: 13px;
	}
 
.list-produk
	{
		border: 1px solid gainsboro;
		padding: 10px;
		float: left;
		width: 200px;
		margin: 5px;
	}
 
.list-produk:hover
	{
		transition-duration: 700ms;
		box-shadow: 5px 5px gainsboro;
	}
 
.list-produk img
	{
		width: 100%;
		height: 180px;
		display: block;
		margin-bottom: 5px;
	}
 
.list-produk h4, .list-produk h5
	{
		color: crimson;
		text-align: center;
		margin-bottom: 5px;
	}
 
.tombol
	{
		text-decoration: none;
		border-radius: 7px;
		padding: 7px;
		display: block;
		float: center;
		width: 45%;
		margin: 5px;
		text-align: center;
		color: white;
	}
 
.tombol:hover
	{
		background-color: black;
		transition-duration: 700ms;
	}
 
.tombol-detail
	{
		background-color: green;
	}
 
/* begin Footer */
.art-footer
{
   position: relative;
   margin-top:0px;
   margin-bottom:0px;
   width: 100%;
}

.art-footer-body
{
   position:relative;
   padding: 25px;
   color: white;
 background:black;
}

.art-footer-text
{
   min-height: 16px;
   padding-left: 10px;
   padding-right: 10px;
   text-align: center;
}

/*input search*/
.search {
    padding:12px 15px;
    background:white;
    border:0px solid #dbdbdb;
}
.button {
    position:relative;
    padding:10px 30px;
    left:-5px;
    border:2px solid #53bd84;
    background-color:#53bd84;
    color:#fafafa;
}
.button:hover  {
    background-color:#fafafa;
    color:#207cca;
}
/*retting*/
.bintang {
width: 100px;
border: none;
font-weight: bold;
font-size: 12px;
}
.starImg {
width: 100px;
height: 21px;
display: block;
background: url(http://1.bp.blogspot.com/-Sp-iHFztZdc/UVD89O9oM1I/AAAAAAAAEU0/Xh-FBDaWyJY/s1600/star.png) 0 0 no-repeat;
}
.star-0 {background-position: -100px -0;}
.star-5 {background-position: -81px -21px;}
.star-10 {background-position: -81px 0;}
.star-15 {background-position: -61px -21px;}
.star-20 {background-position: -60px 0;}
.star-25 {background-position: -40px -21px;}
.star-30 {background-position: -40px 0;}
.star-35 {background-position: -21px -21px;}
.star-40 {background-position: -21px 0;}
.star-45 {background-position: 0 -21px;}
.star-50 {background-position: 0 0;}


/*testimoni*/
body {
    font-family: 'Lucida Grande', 'Helvetica Neue', sans-serif;
    font-size: 13px;
}

#comment_form input, #comment_form textarea {
    border: 2px solid rgba(0,0,0,0.1);
    padding: 8px 10px;
    outline: 0;
}
#comment_form input {
    width: 250px;
}
#comment_form textarea {
    width: 450px;
}

#comment_form input[type="submit"] {
    cursor: pointer;
    background: -webkit-linear-gradient(top, #efefef, #ddd);
    background: -moz-linear-gradient(top, #efefef, #ddd);
    background: -ms-linear-gradient(top, #efefef, #ddd);
    background: -o-linear-gradient(top, #efefef, #ddd);
    background: linear-gradient(top, #efefef, #ddd);
    color: #333;
    text-shadow: 0px 1px 1px rgba(255,255,255,1);
    border: 1px solid #ccc;
}

#comment_form input[type="submit"]:hover {
    background: -webkit-linear-gradient(top, #eee, #ccc);
    background: -moz-linear-gradient(top, #eee, #ccc);
    background: -ms-linear-gradient(top, #eee, #ccc);
    background: -o-linear-gradient(top, #eee, #ccc);
    background: linear-gradient(top, #eee, #ccc);
    border: 1px solid #bbb;
}

#comment_form input[type="submit"]:active {
    background: -webkit-linear-gradient(top, #ddd, #aaa);
    background: -moz-linear-gradient(top, #ddd, #aaa);
    background: -ms-linear-gradient(top, #ddd, #aaa);
    background: -o-linear-gradient(top, #ddd, #aaa);
    background: linear-gradient(top, #ddd, #aaa);    
    border: 1px solid #999;
}

#comment_form div {
    margin-bottom: 8px;
}
 
</style>
<body>
<img src="featured-futsal.jpg" Width="100%"height="30%">
	<div class="topnav">
	<center>
		<a href="TUGAS SEBELUM UAS.html"><b style="color:green">BANDROS SPORTS</a></b>
		<a href="TUGAS SEBELUM UAS.html">HOME</a>
		<a href="AKSESORIS.html">AKSESORIS</a>
		<a href="TENTANG KAMI.html">TENTANG KAMI</a>
		<a href="Login.html">MASUK GMAIL</a><br>
		<input class="search" type="text" placeholder="Cari Barang...">	
		<input class="button" type="button" value="Cari">
	</center>
	</div>
</div>
	<div class="badan">
        <h2>Produk Baru</h2>
 
        <div class="list-produk">
            <img src="images (1).jpg" alt="Sepatu Futsal">
 
            <h4>Sepatu Futsal Biru</h4>
            <h5>Rp 150.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-35"></span></fieldset></center>
            <center><a href="1.html" class="tombol tombol-detail" href="#">Detail</a></center> 
          
        </div>
 
        <div class="list-produk">
            <img src="images (2).jpg" alt="Bola Mitre">
 
            <h4>Bola Mitre</h4>
            <h5>Rp 210.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-25"></span></fieldset></center>
            <center><a href="2.html" class="tombol tombol-detail" href="#">Detail</a></center>
          
        </div>
 
        <div class="list-produk">
            <img src="images (3).jpg" alt="Raket">
 
            <h4>Raket</h4>
            <h5>Rp 130.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-25"></span></fieldset></center>
            <center><a href="3.html" class="tombol tombol-detail" href="#">Detail</a></center>
          
        </div>
 
        <div class="list-produk">
            <img src="images (4).jpg" alt="Sepatu Futsal Hitam">
 
            <h4>Sepatu Futsal Hitam</h4>
            <h5>Rp 170.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-30"></span></fieldset></center>
            <center><a href="4.html" class="tombol tombol-detail" href="#">Detail</a></center> 
           
        </div>
		
		  <div class="list-produk">
            <img src="images (5).jpg" alt="Raket Tenis">
		
            <h4>Raket Tenis</h4>
            <h5>Rp 170.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-35"></span></fieldset></center>
            <center><a href="5.html" class="tombol tombol-detail" href="#">Detail</a></center> 
           
    </div>
   <div class="list-produk">
            <img src="images (6).jpg" alt="Sepatu Bola Nike">
 
            <h4>Sepatu Bola Nike</h4>
            <h5>Rp 150.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-25"></span></fieldset></center>
            <center><a href="6.html" class="tombol tombol-detail" href="#">Detail</a></center> 
        
    </div>
	</div>
<div class="badan">
        <h2>Produk Terlaris</h2>
   <div class="list-produk">
            <img src="images (7).jpg" alt="Sepatu Bola Specs">
 
            <h4>Sepatu Bola Specs</h4>
            <h5>Rp 165.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-35"></span></fieldset></center>
            <center><a href="7.html" class="tombol tombol-detail" href="#">Detail</a></center> 
           
    </div>
   <div class="list-produk">
            <img src="images (8).jpg" alt="Sepatu Bola Adidas">
 
            <h4>Sepatu Bola Adidas</h4>
            <h5>Rp 175.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-45"></span></fieldset></center>
            <center><a href="8.html" class="tombol tombol-detail" href="#">Detail</a></center> 
          
    </div>
   <div class="list-produk">
            <img src="images (9).jpg" alt="Jersey Barcelona">
 
            <h4>Jersey Barcelona</h4>
            <h5>Rp 150.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-45"></span></fieldset></center>
           <center> <a href="9.html" class="tombol tombol-detail" href="#">Detail</a></center> 
          
    </div>
    <div class="list-produk">
            <img src="images (10).jpg" alt="Sepatu Bola Puma">
 
            <h4>Sepatu Bola Puma</h4>
            <h5>Rp 180.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-30"></span></fieldset></center>
            <center><a href="10.html" class="tombol tombol-detail" href="#">Detail</a></center> 
        
    </div>
	    <div class="list-produk">
            <img src="images (11).jpg" alt="Bola Nike">
 
            <h4>Bola Nike</h4>
            <h5>Rp 186.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-35"></span></fieldset></center>
            <center><a href="11.html" class="tombol tombol-detail" href="#">Detail</a></center> 
          
    </div>
	    <div class="list-produk">
            <img src="images (12).jpg" alt="Bola Adidas">
 
            <h4>Bola Adidas</h4>
            <h5>Rp 180.000,-</h5>
			<center><fieldset class="bintang">
			<span class="starImg star-45"></span></fieldset></center>
            <center><a href="12.html" class="tombol tombol-detail" href="#">Detail</a></center>        
    </div>
	</div>
	
	<div class="badan">
    <h2>Komentar</h2>
	<div id="comment_form">
    
    <div>
        <input type="text" name="name" id="name" value="" placeholder="Name">
    </div>
    <div>
        <input type="email" name="email" id="email" value="" placeholder="Email">
    </div>
    <div>
        <input type="url" name="website" id="website" value="" placeholder="Website URL">
    </div>
    <div>
        <textarea rows="10" name="comment" id="comment" placeholder="Comment"></textarea>
    </div>
    <div>
        <input type="submit" name="submit" value="Add Comment">
    </div>
	
</div>
	</div>
	<div class="art-footer">
           <div class="art-footer-body">

              <div class="art-footer-text">
              <p> Bandros Sport. All rights reserved.</p>
<div class="cleared">
</div>
<p class="art-page-footer">
</p>
</div>
</body>
</html>
