<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@900&family=Open+Sans&display=swap"
		rel="stylesheet">
	<link rel="stylesheet" href="s.css">
</head>

<body>
	<header id="header" class="header">
		<div class="container">
			<img src="img/logo.png" alt="wayup" class="logo">
			<div class="wrapper">
			<div class="offer">
				<h1 class="title">
					Я обучаюсь <span>верстке</span> <br>и делаю это феерично
				</h1>
				<p class="intro">
					Я прохожу курс от WAYUP и становлюсь лучше с каждым днем. Просто сказка !Меня ждут дорогие заказы и творчество.
				</p>
				<a href="#" class="btn">Узнать больше</a>
			</div>
			<img src="img/desktop.png" alt="photo" class="desktop">
            </div>
		</div>
	</header>
	<section id="learn" class="learn">
		<div class="container">
			<h2 class="section-title">Зачем я обучаюсь</h2>
			<div class="skills">
			      <div class="skill">
			    	<h3 class="skill-title">
			    		знать код
			    	</h3>
			    	<p class="skill-text">
			    		Меня привлекает написание современного и красивого кода
			    	</p>
			    </div>
			    <div class="skill skill-free">
			    	<h3 class="skill-title">
			    		Стать фрилансером
			    	</h3>
			    	<p class="skill-text">
			    		Путешествоватьб жить свободно и работать над креативными тасками
			    	</p>
			    </div>
			      <div class="skill skill-change">
			    	<h3 class="skill-title">
			    		Изменить жизнь
			    	</h3>
			    	<p class="skill-text">
			    		Я хочу создавать ценность работать на себя и развиваться
			    	</p>
			    </div>
			</div>
		</div>
	</section>
	<section id="mail" class="mail-h1">
		<div class="container">
			<div class="btn-h2"></div>
			<h2 class="section-title">Я буду писать вам</h2>
			<form action="#" class="form">
				<input type="email" placeholder="ведите свой E-mail" name="email" class="input" required>
				<button type="submit" class="btn btn-form">Узнать больше</button>
			</form>
		</div>
	</section>
	<footer id="footer" class="footer">
		<div class="container">
            <p class="credits">
            	все права защищены
            </p>
		</div>
	</footer>
</body>

</html>
body{
	font-family: 'Open Sans', sans-serif;
	color: #201b2d;
	font-size: 15px;
	padding: 0;
	margin: 0;
}
div,p,input,button,form,span,a,ul,li {
	box-sizing: border-box;
}
h1,h2,h3,h4,h5,h6{
	margin: 0;
	font-family: 'Montserrat', sans-serif;
	font-weight: 900;
}
.container{
	width: 1170px;
	margin: 0 auto;

}
.header{
	background: rgb(71,62,95);
background: linear-gradient(90deg, rgba(71,62,95,1) 0%, rgba(71,62,95,1) 18%, rgba(43,34,64,1) 100%);
  padding: 100px;
  padding-bottom: 225px;
}
.wrapper{
	display: flex;
	justify-content: space-between;
}
.offer{
	margin-top: 176px;
	width: 480px;
}
.title{
   font-size: 36px;
}
.title span{
	color: #48ed8e;
}
.intro{
    margin-bottom: 37px;
    width: 380px;
    margin-top: 30px;
}
.btn{
	background: #ed9619;
	color: #fff;
	font-family: 'Montserrat', sans-serif;
	border-radius: 100px;
	display: block;
	width: 205px;
	padding: 15px;
	text-align: center;
	text-decoration: none;
	transition: all 0.5s ease;
}
.btn:hover{
	background: #d9860e;
	color: #fff;
}
p{
	line-height: 1.65em;
}
.besktop{
	margin-top: 72px;
}
.section-title{
	font-size: 30px;

}
.learn{
	padding-top: 108px;
	padding-bottom: 120px;
}
.skills{
	display: flex;
	justify-content: space-between;
	margin-top: 100px;
}
.skill{
	width: 350px;
	background: url('img/icon1.png') no-repeat left top;
	padding-left: 100px;
}
.skill-title{
	font-size: 18px;
}
.skill-text{
	margin-top: 7px;
}
.skill-free {
	width: 380px;
	background: url('img/icon2.png') no-repeat left top;
}
.skill-change{
	background: url('img/icon3.png') no-repeat left top;
}
.mail-h1 {
	background:#d1c7e2;
	padding-top: 173px;
	padding-bottom: 190px;
}
.input{
	width: 474px;
	border: 1px, solid #bfb8d1;
	font-size: 15px;
	font-family: 'Open Sans', sans-serif;
	border-radius: 100px;
	height: 54px;
	padding-left: 38px;
}
.btn-form{
	border: 0;
	cursor: pointer;
	display: inline;
	margin-left: 11px;
}
.btn-h2{
	display: flex;
	justify-content: space-between;
}
.form{
	margin-top: 40px;
}
.credits{
	color: #d4cee3;
	font-size: 14px;
	margin: 0;


}
.footer{
	padding: 33px 0;
	background: #201b2d;
}
