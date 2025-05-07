# SERVERMULTIPLATFORM
загатовка мультиплатформенного сервера между Eaglercraft и Minecraft java edition


# Установка
на моём репозитории жмём Fork
создаём кодспейс на вашем форкнутом репозитории в Github

Для запуска сервера нужно создать порты 8081 и 25565 и 65577 
сделать их публичными
создать 3 консоли
ввести команды
cd server && sudo java -jar server.jar - в первую консоль
cd bungee && sudo java -jar bungee.jar - в вторую консоль
___________________________________________________________________________________________________________________________________________________________________________________________________
после переходим и регаемся на сайте playit.gg

вводим эти команды в третью консоль:

curl -SsL https://playit-cloud.github.io/ppa/key.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/playit.gpg >/dev/null

echo "deb [signed-by=/etc/apt/trusted.gpg.d/playit.gpg] https://playit-cloud.github.io/ppa/data ./" | sudo tee /etc/apt/sources.list.d/playit-cloud.list

sudo apt update

sudo apt install playit

playit

после етого переходим в 3 консоль где мы вводили команды связаные с playit.gg и переходим по сылке которую нам дала командная строка 
пример: playit.gg/claim/#########

создаём тунель на сайте
выбераем тип (TCP+UDP)
вводим порт 65577

вооля копируем айпи который нам дал playit.gg и заходим с Minecraft Java Edition (по стандару стоит версия 1.8.8 , после установки плагина viaversions можно захадить с более высоких версий)

![image](https://github.com/user-attachments/assets/ccec721c-6145-4a66-bea0-2fd1311dac0e)
для Eaglercraft  жмём на выделеную кнопку на изображении
приставку https//: меняем на wss//:
добовляем и заходим
готово а видео гайд я сниму позже на свой ютуб канал.
