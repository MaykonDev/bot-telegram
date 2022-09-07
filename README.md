<h1 align="center">Telegram-Bot</h1>

<p align="center">Esse repositório foi criado para pessoas que desejam criar seu primeiro bot para Telegram, com facilidade e rapidez!</b>


<div>
<p align="center"><img src="https://img.shields.io/badge/-python-white?style=for-the-badge&logo=Python&logoColor=default">
<img src="https://img.shields.io/badge/-telegram-white?style=for-the-badge&logo=Telegram&logoColor=default">
<img src="https://img.shields.io/badge/-pypi-white?style=for-the-badge&logo=pypi&logoColor=default">
</p>
</div>
</br>
<h2 align="center">Primeiros passos: </h2>

<p>baixando a biblioteca necessária para criar o bot: </p>

    pip install pytelegrambotapi

<p>1° Criando a estrutura do bot:</p>

    nvim pybot.py   #Demonstrei usando o nvim pois é o editor de texto que eu uso
    
<p>2° Mão na massa: </p>

    import telebot
    token = "TOKEN"
    bot = telebot.TeleBot(token)

    @bot.message_handler(command=["/start"])
    def mensagem(comando):
        bot.reply_to(mensagem, "Estou ativado!")

<p>3° Pegando o token com o BotFather: </p>
<p align="center"><a href="https://t.me/BotFather"><img src="https://img.shields.io/badge/-BotFather-white?style=for-the-badge&logo=Telegram&logoColor=default"></p>

<i>Toque na caixa acima escrito "BotFather", você será redirecionado ao bot do Telegram responsável pela criação de Tokens para os bots de terceiros!</i>
<i>Após isso, digite <b>/newbot</b> e em seguida, envie o nome que deseja dar ao seu bot</i>
