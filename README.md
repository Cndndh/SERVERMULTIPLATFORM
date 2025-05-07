# SERVERMULTIPLATFORM
загатовка мультиплатформенного сервера между Eaglercraft и Minecraft java edition
![EaglerCraft-Server-Host-07-05-2025 (1)](https://github.com/user-attachments/assets/891a7c89-edb8-4fcd-9ac3-600de6b213bd)


# Установка
на моём репозитории жмём Fork
создаём кодспейс на вашем форкнутом репозитории в Github

Для запуска сервера нужно создать порты 8081 и 25565 и 65577

сделать их публичными

создать 3 консоли и 
ввести команды

cd server && sudo java -jar server.jar - в первую консоль

cd bungee && sudo java -jar run.jar - в вторую консоль
___________________________________________________________________________________________________________________________________________________________________________________________________
после переходим и регаемся на сайте playit.gg

вводим эти команды в третью консоль:

curl -SsL https://playit-cloud.github.io/ppa/key.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/playit.gpg >/dev/null

echo "deb [signed-by=/etc/apt/trusted.gpg.d/playit.gpg] https://playit-cloud.github.io/ppa/data ./" | sudo tee /etc/apt/sources.list.d/playit-cloud.list

sudo apt update

sudo apt install playit

playit

после етого переходим в 3 консоль где мы вводили команды связаные с https://playit.gg и переходим по сылке которую нам дала командная строка 

пример: playit.gg/claim/#########

создаём тунель на сайте

выбераем тип (TCP+UDP)

вводим порт 65577

вооля копируем айпи который нам дал playit.gg и заходим с Minecraft Java Edition (по стандару стоит версия 1.8.8 , после установки плагина viaversions можно захадить с более высоких версий)

![Screenshot 2025-05-07 20 04 54](https://github.com/user-attachments/assets/28b1c954-381f-4abb-845c-0f76f2358df6)

для Eaglercraft  жмём на выделеную кнопку на изображении

в меню добавления сервера меняем приставку https:// на wss://

добовляем сервер и заходим

готово а видео гайд я сниму позже на свой ютуб канал.
