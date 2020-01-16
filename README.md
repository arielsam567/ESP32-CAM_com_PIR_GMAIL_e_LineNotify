# ESP32-CAM com PIR GMAIL e LineNotify

ESP32-CAM ao identificar um movimento com o PIR, tira uma foto e manda para o gmail e para LineNotify

O sensor pir esta conectado a porta 13

Você deve adicionar ao Google App Scrip o script envia_imagem_capturada_para_google_drive_e_lineotify.gs 

Link do Google App Scrip:  https://script.google.com/home/

Link do LineNotify: https://notify-bot.line.me/my/

Link do script que deverá ser adicionado: https://github.com/arielsam567/ESP32-CAM_com_PIR_GMAIL_e_LineNotify/blob/master/envia_imagem_capturada_para_google_drive_e_lineotify.gs

Você devera alterar a linha com 
```
String myScript = "/macros/s/xxxxxxxxxxxxxxxxxxxxxxxxx/exec"; // coloque no xxxxxxxxxx, o que aparece na sua tela do google app script

String myLineNotifyToken = "myToken=xxxxxxxxxx";              // coloque no xxxxxxxxxx o seu token do LineNotify, ou deixei como esta, caso não queira receber a noticacao
```

