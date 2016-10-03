<head>

<style>
body {font-family:sans-serif; color:#f5f5f5}
.container{max-width:992px; margin-left:auto; margin-right:auto; padding-left:16px; padding-right:16px;}
nav{background-color:lightcoral; transition: background-color 5s ease;}
nav:hover {background-color:red;}
nav ul{text-align:center}
nav ul li{display:inline-block; padding:8px; transition: 3s ease;}
nav ul li:hover {color: #181818; }
.blog-entry{height:200px;width:65%;background-color:deepskyblue; float:left; margin-bottom:16px; display:inline-block; margin-right: 5%; transition: background-color 5s ease;}
.blog-entry:hover {background-color: orange;}
.blog-entry h2 {text-align:center;}
.sidebar h2 {text-align:center;}
.sidebar{height:640px; width:30%;  transition: background-color 5s ease; background-color:orange;  display:inline-block; }
.sidebar:hover {background-color:greenyellow;}


.clearfix:after {
	visibility: hidden;
	display: block;
	font-size: 0;
	content: " ";
	clear: both;
	height: 0;
	}


</style>
</head>
<body>
<div class="container">
<nav>
<ul>
<li>Home</li>
<li>About</li>
<li>Work</li>
<li>Contact</li>
</ul>
</nav>

<div class="main-content clearfix">
<section class="blog-entry">
<h2>Heading</h2>
</section>
<section class="blog-entry">
<h2>Heading</h2>
</section>
<section class="blog-entry">
<h2>Heading</h2>
</section>
<aside class="sidebar">
<h2>Heading</h2>
</aside>
</div>
</div> <!--end container-->
</body>
