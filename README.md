1. Tải về  files và giải nén ra Desktop, đổi tên thành awbot
2. Tải xuống và cài đặt Python mới nhất (xem youtube cách cài)
3. Đăng ký anti-captcha link này ủng hộ mình nha http://getcaptchasolution.com/viymgn7pbz
Sau khi đăng ký vào phần nạp tiền chọn "tín dụng demo" để nhận $ free, sau đó vào phần Cài Đặt -> thiết lập API -> Copy key -> Quay lại files code đã tải về, chuột phải vô config.py, chọn edit with Pycharm thay thế chữ YOUKEY bằng key vừa copy, ấn CTRL+S hoặc FILE -> SAVE để lưu lại.
4. Mở cmd nhập vào 
pip install selenium-requests       (ấn enter)
cd desktop        (ấn Enter)
cd awbot           (ấn Enter)
pip install -r requirements.txt    (ấn Enter)
5. Cài Mozilla Firefox mới nhất, cài Node JS 14.17 LTS mới nhất

Ok, xong phần cài đặt, bây giờ lấy Cookies để chạy
Tạo hồ sơ chrome mới, cài tiện ích editthiscookie, đặng nhập vô wallet.wax.io, lúc vừa đăng nhập trang wallet đang chạy 3...2...1 nhanh tay ấn chuột phải, chọn editthiscookie, chọn cái muổi tên (xuất dữ liệu) để copy cookies, sau đó vào thư mục awbot giải nén lúc đầu -mở tiếp thư mục cookies, chuột phải lên files 1.json chọn edit with Pycharm, paste cookies mới lấy lúc nãy vô (CTRL+P) sau đó lưu lại (CTRL+S)
Thêm tài khoản thứ 2 làm y như vậy, lúc lưu lưu vô 2.json, nhớ là tạo hồ  sơ chrome mới, ko sử dụng hồ sơ cũ.


Khởi chạy, mở CMD, nhập lần lượt:
cd desktop   (ấn enter)
cd awbot     (ấn enter)
Writing python main.py    (ấn enter)    .

Captcha xử lý bằng anti-captcha mỗi lượt tốn khoảng 0,002usd
Donate : vo5dy.wam



This bot automatically mines TLM and solves the captcha through the Anti-Captha service

The first working bot for the game Alien Worlds. You will never be banned. The bot always mines with a different delay, so the game thinks that you are a real person.

English/Russian

English: Download: Code => download zip

And so let's proceed with the installation.

Bot setup:

Download Python on 3.8 Windows x86–64 executable installer
Install it, do not forget to select the ADD TO PATH checkbox
Transfer the folder with the bot to the desktop for convenience, rename it to AWbot (the path to main.py should be something like this / desktop / AWbot (this is the name of the folder with the bot) /main.py
Go to the console (CMD) and write cd desktop / awbot Or cd desktop, cd awbot
pip install -r requirements.txt
Perhaps he will swear at the version pip, then write a command that will appear in the console
pip install selenium-requests
Install Mozilla Firefox If you already have it, check that the version is 90+
Install Node JS 14.17 LTS (as of 05/13/2021)
Go to config.py and in the CAPTCHA_KEY = 'YOUR KEY' field insert your captcha key https://anti-captcha.com/ (Works only on it) Do not touch the rest in the config, otherwise you will break everything.
Test key - c7222053aa7131e9b09ab2638bb99a15

This key can be used until the balance runs out (100 + $)

The bot is ready, it remains to set up your accounts.
Preparing accounts.

Making a NEW CHROME profile.
Installing the EditThisCookie extension
Go to https://all-access.wax.io/
Log in to your account and be careful
After login, there will be such a window
https://i.ibb.co/LJcsvzM/1-R2g0wpu-K45-VCgzl-ICg-ECk-A.jpg

You will have 3 seconds to left-click on the browser and click on EditThisCookie
If you did everything correctly, you will see such a window. The site must be https://all-access.wax.io/
https://i.ibb.co/9w6sKJY/1-Oq-FEm8-Qm6u1wi-FNLXKLFKw.jpg

Do not change anything and click on the button that is marked (export)
Open the notebook, paste everything from the clipboard there, do not touch anything.
Save it as 1.json (1.json - for the first account, 2 .json - as for the second, etc. FILE TYPE - ALL FILES, not .txt
For the rest of the accounts, do steps 3-10
IMPORTANT!!!! After each save the account, CLEAR history in the browser !!!!

Do not change anything and click on the button that is marked (import)
Open the notebook, paste everything from the clipboard there, do not touch anything.
Save it as 1.json (1.json - for the first account, 2 .json - as for the second, etc. FILE TYPE - ALL FILES, not .txt
For the rest of the accounts, do steps 3-10
IMPORTANT!!!! After each save the account, CLEAR history in the browser !!!!

INCLUDE BOT

We drop all * .json files into the cookies folder (if not, create them) in the bot. The numbering MUST start with 1.json and continue with 2,3,4,5 ... Go to the console (CMD) write cd desktop / awbot Writing python main.py Let's start the bot PS if I forgot to indicate something in the guide, the console will write you what else you need to install. First, it will close all firefox.exe processes, check all the cookies that you have made, if everything goes ok to mine. Sometimes the bot dulls, you just need to restart. If you have a large pool of accounts, then I advise you to run up to 10 accounts first and look at the CPU and RAM load of your Dedicated Server. I hope you will have time to earn at least as much as I do)) All good and cool TLM farming

Russian:

Скачать: Code=> download zip

И так приступим к установке.

Настройка бота:

Качаем Python 3.8 Windows x86–64 executable installer
Инсталим его, не забываем выбрать галочку ADD TO PATH
Переносим папку с ботом на рабочий стол для удобства переименовываем на AWbot (путь до main.py должен быть примерно таким /desktop/AWbot(это название папки с ботом)/main.py
Идем в консоль (CMD) пишем cd desktop/awbot. Или cd desktop , cd awbot
pip install -r requirements.txt
Возможно он ругнется на версию pip, тогда напишите команду, которая будет в консоле.
pip install selenium-requests
Устанавливаем Mozilla Firefox. Если уже есть, проверьте чтобы версия была 90+
Устанавливаем Node JS 14.17 LTS (на 13.05.2021)
Идем в config.py и в поле CAPTCHA_KEY = ‘ВАШ КЛЮЧ’ вставляем свой ключ от капчи https://anti-captcha.com/ (Работает только на ней) Остальное в конфиге не трогайте, а то поламаете все.
Бот готов, осталось настроить Ваши аккаунты.
Подготовка аккаунтов.

Делаем НОВЫЙ профиль в CHROME.
Устанавливаем расширение EditThisCookie
Заходим на https://all-access.wax.io/
Логинимся в аккаунт и будьте внимательны
После логина будет такое вот окно
https://i.ibb.co/LJcsvzM/1-R2g0wpu-K45-VCgzl-ICg-ECk-A.jpg

У Вас будет 3 секунды чтобы нажать левой клавишой мышки по браузеру и нажать на EditThisCookie
Если все сделали правильно у вас откроется такое окно. Сайт должен быть https://all-access.wax.io/
https://i.ibb.co/9w6sKJY/1-Oq-FEm8-Qm6u1wi-FNLXKLFKw.jpg

Ничего не меняйте и нажмите на кнопку что отмечена (export)
Открываем блокнот, вставляем туда все из буффера обмена, ничего не трогаем.
Сохраняем это как 1.json (1.json — для первого акка, 2 .json— как для второго и т.д. ТИП ФАЙЛА — ВСЕ ФАЙЛЫ, не .txt
Для остальных акков проделываем пункты 3–10
ВАЖНО!!!! После каждого сохранения акк, ЧИСТИТЬ историю в браузере!!!!

ВКЛЮЧАЕМ БОТА

Закидываем все *.json файлы в папку cookies (если нет, создаем) в боте. Нумерация ДОЛЖНА начинаться с 1.json и продолжаться 2,3,4,5… Идем в консоль (CMD) пишем cd desktop/awbot Пишем python main.py Пошел запуск бота P.S. если я что-то забыл указать в гайде, то консоль напишет вам что еще надо доинсталить. Сначала он закроет все процессы firefox.exe, проверит все куки что вы наделали, если все ок пойдет майнить. Бывает бот затупливает, надо просто перезапустить. Если у вас большой пул акков, то советую запустить сперва ДО 10 акков и посмотреть на нагрузку CPU и RAM вашего дедика. Надеюсь вы успеете заработать хотя бы столько сколько и я)) Всем добра и крутого фарма ТЛМ
