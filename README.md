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
<a href="https://t.me/BotFather"><img src="https://img.shields.io/badge/-BotFather-white?style=for-the-badge&logo=Telegram&logoColor=default"></a>


<i>• Toque na caixa acima escrito "BotFather", você será redirecionado ao bot do Telegram responsável pela criação de Tokens para os bots de terceiros!</i></br>
<i>• Após isso, digite <b>/newbot</b> e em seguida, envie o nome que deseja dar ao seu bot.</i></br>
<i>• E por fim o Username, que deve conter <b>bot</b> no nome, exemplo: </b>TetrisBot ou tetris_bot</b></i></br>
<i>• Caso o username inserido não exista, ele irá mandar as informações do seu bot, e o token.</i></br>

<p> Após você pegar seu Token, troque o valor da variável Token do código, e execute com <b>python nomeBot.pt</b></i></br></br>

<h3>Para mais informações da biblioteca, acesse:</h3>

https://pypi.org/project/pyTelegramBotAPI/
