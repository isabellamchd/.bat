## Oque aprendi?

 Hoje a nossa aula foi prática e tivemos ótimos avanços em relação aos comandos solicitados pelos nossos instrutores, eu aprendi muitos comandos novos, e tirei todas as minhas dúvidas, a minha dificuldade foi fazer meu script rodar e dar certo da forma que queria, tentei muitas formas diferentes e além de pedir ajuda para o professor, também chamei alguns amigos para me ajudar a solucionar o problema, mas no fim o resultado ficou ótimo.

![gatinho](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExbzZhOXNoYnNxZm1zejV3bG43eHhkYTluOHZwbXk1YXY4OXQybXZiZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ES4Vcv8zWfIt2/giphy.gif)

## Meu script: 

Meu script foi criado para organizar um calendario, contendo meses dias e um ano, no começo utilizei echo para criar um nome. Depois utilizei mkdir para criar uma pasta e cd para ir para o meu diretório. 

```markdown
@echo off

if not exist "%1" (
    mkdir "%1"
)
cd "%1"
if not exist "%2" (
    mkdir "%2"
)
cd "%2"
set mes=%2
echo oi
if %mes%==1 set dias=31
if %mes%==2 set dias=28
if %mes%==3 set dias=31
if %mes%==4 set dias=30
if %mes%==5 set dias=31
if %mes%==6 set dias=30
if %mes%==7 set dias=31
if %mes%==8 set dias=31
if %mes%==9 set dias=30
if %mes%==10 set dias=31
if %mes%==11 set dias=30
if %mes%==12 set dias=31

echo o numero de dias %dias% no mes %mes%
cd ..
cd ..
```
