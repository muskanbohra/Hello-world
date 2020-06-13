*{
	margin: 0;
	padding: 0;
	font-family: Century Gothic;
}

header{
	background-image: linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)), url(../21.jpg);
	height: 100vh;
	background-size: cover;
	background-position: center;
}

ul{
	float: right;
	list-style-type: none;
	margin-top: 25px;

}

ul li{
	display: inline-block;
}

ul li a{
	text-decoration: none;
	color: #fff;
	padding: 5px 20px;
	border: 1px solid transparent;
	transition: 0.6s ease;

}

ul li a:hover{
	background-color: #fff;
	color: #000;
}
ul li.active a{
	background-color: #fff;
	color: #000;
}
}
.1 img{
	float: left;
	width: 150px;
	height: auto;
} 

.main{
	max-width: 1200px;
	margin: auto;
}

.title{
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%,-50%);
}

.title h1{
	color: #fff;
	font-size: 70px
}

.button{
	position: absolute;
	top: 63%;
	left: 50%;
	transform: translate(-50%,-50%);
}

.btn{
	border: 1px solid #fff;
	padding: 10px 30px;
	color: #fff;
	text-decoration: none;
	transition: 0.6x ease;

}

.btn:hover{
	background-color: #fff;
	color: #000;
}

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/muskanbohra/Hello-world/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
