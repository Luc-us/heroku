Pra poder hospedar o Bot/Site na Heroku só seguir os passos:

        --= APP's =--

<1> heroku cli <https://devcenter.heroku.com/articles/heroku-cli#download-and-install>
<2> git <https://git-scm.com/download/win>

        --= VSC =--
    
(1) Criar um arquivo chamado ( Procfile ) <com o "P" maísculo> e coloque dentro dele: ( worker: node (seu arquivo principal) )

(2) Criar um arquivo chamado ( .gitignore ) e coloque detro dele: ( node_modules/ )

        --= Site =--

\1/ - Criar uma conta na Heroku <https://heroku.com>

        --= Terminal =--

\2/ - heroku login

\3/ - git init

\4/ - git add .

\5/ - git commit -am "qualquer coisa"

( Se aparecer uma mensagem pra configurar o heroku coloque: 

<1> = git config --global user.name "seu username na heroku"

<2> = git config --global user.email "seuemail@exemplo.com" )


\6/ - git status e verifique se o (Procfile) ficou com o "P" maísculo
        
        
\7/ - heroku create <nome do app que você quer>

\8/ - heroku git:remote -a <nome do app que você criou>

\9/ - git push heroku master

\10/ - vá no site da heroku, abra seu APP e depois abra a aba resoucers. Quando abrir desative o "web" e ative o "worker"

( Pronto seu BOT/Site está hospedado )

By: <Diluc#6020> <https://github.com/Diluc-san>
