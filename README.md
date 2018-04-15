# Test
test program
<!DOCTYPE html>
<html>
<head>
    <meta http-equiv="Content-Tape" content="text/html; charset-utf-8" />
	<title>Art Букет</title> 
    <meta name="desoription" content=""/>
	<meta name="keywords" content=""/>
	<link href="favicon.ico" rel= "shortuct ico" type="image/x-icon"/>
	<link type="text/css" rel= "stylesheet" href="styles.css" />
	<script type="text/javascript" src="jquery-3.2.0min.js"></script>
	
</head>
<body>
   
	<div id="container">
	    <div id="topmenu">
		    <table>
			    <tr>
				    <td>
					    <a href="index.html">Главная</a>
					</td>	
		            <td>
					    <a href="about.html">О нас</a>
					</td>	
		            <td>
					    <a href="services.html">Букеты</a>
					</td>	
		            <td>
					    <a href="contacts.html">Контакты</a>
					</td>	
		            <td>
					    <a href="feedback.html">Оформить заказ</a>
					</td>	
		        </tr>
			</table>
		</div>	
		
		<div id="logo">
		    <img src="images/logo.png" alt="Лого"/>
		</div>
		<div id="content">
		    <div id="left">
                <div id="news">			    
				    <h2>Новости</h2>
				    <div class="new">
					    <p class="date">1 апреля 2017</p>
				        <p><b>Мы открылись!</b><br />адрес можно посмотреть на странице контактов.</p>
				    </div>
			        <div class="new">
					    <p class="date">2 апреля 2017</p>
				        <p><b>Теперь мы работаем круглосуточно</b><br />ради Вашего удобства.</p>
				    </div>
				    <div class="new">
					    <p class="date">3 апреля 2017</p>
				        <p><b>Специальное предложение</b><br />на букет из 101 розы!</p>
				    </div> 
				    <div class="new">
					    <p class="date">4 апреля 2017</p>
				        <p><b>Скидка 15% на следующий заказ</b><br />при покупке букета от 2000 руб.</p>
				    </div>
					<div class="new">
					    <p class="date">5 апреля 2017</p>
				        <p><b>Сегодня бесплатная доставка по Саратову!</b></p>
				    </div>
				</div>	
			</div>
			<div id="right">
				<div id="article">
					<h1>Магазин цветов онлайн</h1>
					<p><b>Мы предалагаем цветочную продукцию по доступным ценам и на любой вкус</b></p>
					<p>Мы занимаемся цветами уже более 10 лет и теперь открыли магазин и в интернете.</p>
					<p>Посмотреть все букеты Вы можете <a href="services.html">здесь</a>.</p>
					</div>	
			</div>
				
			<div id="gallery">
                <div id="panel">
                     <img id="largeImage" src="images/image_03_large.jpg" />
                     <div id="description">Букет "Нежность" всего за 1000 руб!</div>
                </div>
                <div id="thumbs">
                <img src="images/image_02_thumb.jpg" alt="Букет из 101 розы всего за 3000 руб!" /><br>
                <img src="images/image_03_thumb.jpg" alt="Букет &laquoНежность&raquo 1000 руб!" /><br>
                <img src="images/image_04_thumb.jpg" alt="Букет &laquoИрисы&raquo 1200 руб" /><br>
                <img src="images/image_05_thumb.jpg" alt="Букет &laquoЛетний&raquo 1500 руб" />
                </div>
            </div>	
	  
    <script>
    $('#thumbs').delegate('img','click', function(){
	$('#largeImage').attr('src',$(this).attr('src').replace('thumb','large'));
	$('#description').html($(this).attr('alt'));
    });
    </script>	
				
			<div class="clear"></div>	
		</div>
   </div>	
   </body>
</html>
    
