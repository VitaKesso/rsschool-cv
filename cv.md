# Vita Kesso

![avatar](./photo/avatar.jpeg=500X750)

## Use instagram to contact me: __@vitabubochka__

#### Hi, I end up with my tutor career right now to prioritize mental health and self-development first. I have awesome dog Yumi and I like making web-pages about her, using a lot of funny photos. And since june I have become a bride, woohoo! I like my new status as much as my fiance! 

## Skills
* HTML
* CSS
* Git
* Python

## Code examples
```html
<html>
	<head>
		<title>STARBUZZ кафе</title>
		<style type="text/css">
			body {
				  background-color: #d2b48c;
				  margin-left: 20%;
				  margin-right:20%;
				  border:2px dotted black;
				  padding: 10px 10px 10px 10px;
				  font-family:sans-serif;
			}
		</style>
	</head>
	<body>
		<h1>Напитки кафе Starbuzz</h1>
		<h1>Домашняя смесь $1,49</h1>
		<p>
			<h2>Мягкая, нетерпкая смесь различных сортов кофе из Мексики, Боварии</h2>
		</p>
		<h1>Кофе мокко $2,35</h1>
		<p>
			<h2>Эспрессо, кипяченое молоко и шоколадный сироп</h2>
		</p>
		<h1>Капучино $1,89</h1>
		<p>
			<h2>Смесь эспрессо и кипяченого молока с добавлением пены</h2>
		</p>
		<h1>Чай $1,85</h1>
		<p>
			<h2>Ароматный напиток из черного чая, специй, молока и мёда</h2>
		</p>
		<p>
			<a href="mission.html"
				title="Узнайте больше о важной задаче кафе Starbuzz">Наша задача</a>
			<br>
			Читайте <a href="http://wickedlysmart.com/buzz"
				title="Все самое интересное о кофейне">Все о кофейне </a>здесь
		</p>
	</body>
</html>
```
```python
@bot.callback_query_handler(func=lambda callback: True)
def callback_message(callback):
	if callback.data =='select':
		markup = types.InlineKeyboardMarkup()
		markup.add(types.InlineKeyboardButton('МК свитер', callback_data='choose'))
		bot.send_photo(chat_id=callback.message.chat.id, caption="""✨на данный момент доступны эти мастер-классы, но я буду пополнять этот список как платными, так и бесплатными уроками!

💌следи за обновлениями в моих соц. сетях*

ты можешь посмотреть описание и цену МК, нажав на кнопочку с названием!⤵️""", reply_markup=markup, photo=open('photo/2photo.jpg','rb'))
	elif callback.data=='choose':
		markup = types.InlineKeyboardMarkup()
		markup.add(types.InlineKeyboardButton('купить и вязать!!', callback_data='pay'))
		bot.send_photo(chat_id=callback.message.chat.id, caption=sweater_description, reply_markup=markup, photo=open('photo/sweater.jpg','rb'))		
	elif callback.data=='pay':
		bot.send_invoice(chat_id=callback.message.chat.id, title="✨оплата✨", description="🌸после оплаты тебе прилетит видео мастер-класс прямо сюда!", invoice_payload="payload", currency="XTR", prices=[telebot.types.LabeledPrice("500", 500)], provider_token=None)


bot.polling(none_stop=True) 	
```
## Work experience
#### 2021 - 2025: I`ve been working as English tutor
#### 2024 - ... : I fused my regular job with programmer studing

## Education
#### 2016 - 2021: Yanka Kupala State University of Grodno
#### 2021 - ... : ***a lot of courses***

## Languages
#### My English is very bad (I confused that nobody of my students didn\`t notice, they still think I\`m C1)
#### Russian native speacker
#### Japanese a little bit yamete kudasai

