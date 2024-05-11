# SCI-AI: Sistema de Checagem de Informação por Inteligência Artficial

![image](https://github.com/tiagobnoronha/SCI-AI/assets/4812185/9fdf4009-27ce-4d95-bcdd-d6a6998a227d)


Este projeto foi criado para o Desafio da Imersão DEV da Alura+Google a fim de explorar a capacidade do Google Gemini. 

## Tema

A desinformação é um grande problema da nossa sociedade. Tal problema se tornou evidente nas últimas semanas, 
em que o estado do Rio Grande do Sul está enfrentando um estado de calamidade pública. Em meio aos problemas
enfrentados pela maior enchente de todos os tempos, os cidadãos e as autoridades precisam lutar por uma onda
de desinformação. As notícias falsas que, em momentos de tranquilidade, podem ter menor potencial ofensivo
em tempos difíceis podem custar vidas (uma vez que ocupam força de trabalho e tempo daqueles que deveriam
estar atendendo a emergência).

Ao longo dos últimos anos, surgiram diversas empresas de checagem que tem como função verificar se as
informações que circulam na rede são verídicas ou não. 

O objetivo dessa aplicação é permitir que o usuário checar a veracidade das informações que podem vir de
de diversos tipos diferentes de fontes:
- Texto
- URL
- Imagem
- Áudio

## Como Utilizar?

Para utilizar esse Notebook, é necessário criar uma chave secreta do Google Colab com o nome SECRET_API_KEY com o valor de sua API KEY do Google AI Studio. 

Então, podem ser executadas todas as células do Notebook (Ctrl+F9).

Na última célula, será montada a interface gráfica do sistema de Checagem. É possível checar a informação nos seguintes formatos:

- Texto: se você possuir a informação no formato textual (e.g. mensagem em rede social, e-mail, etc.)
- URL: se você possui a URL da página que contém a informação que você quer validar. 
- Imagem: se você recebeu a informação de forma textual, mas em uma imagem. O propósito dessa aba não é verificar se uma fotografia é verídica ou não, mas é voltada para imagens que possuam texto. São aceitos diversos formatos de imagem: jpg, png, bmp, gif, etc.
- Áudio: caso possua a informação em áudio. São aceitos diversos formatos de áudio: m4a, mp3, wav, etc.

Uma vez preenchido o formulário, basta clicar no botão **"Checar Fatos"**.

Nota: Dependendo do tipo de informação, o tratamento e análise da informação pode demorar um pouco. As etapas intermediárias são exibidas no widget de Output. Aguarde a análise aparecer. 

## Aviso Importante

O sistema pode ainda apresentar uma análise equivocada para fatos muito recentes. Devido ao tempo exíguo para o desenvolvimento do Desafio o sistema carece de validação para verificar seu índice de acerto. Essa é uma versão beta do sistema que será ajustada a posteriori, sendo assim, utilize-se com cautela. Todavia, pode-se observar que este protótipo apresentou um índice de acertos razoável provando que o conceito pode ser explorado. 

## Como o sistema funciona?

A seguir é apresentado o fluxograma da aplicação.

<img width="774" alt="fluxograma" src="https://github.com/tiagobnoronha/SCI-AI/assets/4812185/d15e4b19-c282-4f45-9917-ee63b4153daa">



