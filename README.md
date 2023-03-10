<h1>Shrelog</h1>

<h2>Введение</h2>

<p>Этот скрипт используется для удаления конфиденциальных файлов журнала и чтения конфиденциальных строк в журналах безопасности.</p>
<h2>Удаляет безвозвратно следующие логи, файлы и директории:</h2>

```
~/.bash_history     ~/.viminfo            ~/.mysql_history
~/.zsh_history      ~/.python_history     ~/.psql_history
~/.nano_history     ~/.node_repl_history  ~/.wget-hsts
~/.cache/chromium   ~/.mozilla/firefox    ~/.mozilla/firefox

/var/log/secure
/var/log/syslog
/var/log/apache2/access.log
/var/log/apache/error.log
/var/log/nginx/access.log
/var/log/nginx/error.log
/var/log/httpd/access_log
/var/log/httpd/error_log
```

<h2>Требования</h2>

<p>Для этого скрипта требуется, чтобы в вашей системе была установлена команда <a href="https://phoenixnap.com/kb/shred-linux">shred</a>. Если он не установлен, скрипт отобразит сообщение об ошибке и завершит работу.</p>

<h2>Установка</h2>

```
sudo apt-get install git shred -y
git clone https://github.com/r3x08/shrelog
cd shrelog
sudo bash shrelog.sh
```

<h2>Использование</h2>

<p>Когда вы запустите скрипт, вам будет представлено меню для выбора опции:</p>

<ul>
<li>Удалить файлы журнала</li>
<li>Считывать конфиденциальные строки в журналах безопасности (сырая функция)</li>
<li>О компании</li>
<li>Выход</li>
</ul>

<p>Затем вы можете выбрать желаемый вариант, введя соответствующий номер (1-4).</p>

<h2>Контакт</h2>

<p>Для получения дополнительной информации или для того, чтобы связаться с создателем, вы можете перейти по следующей ссылке: <a href="https://github.com/r3x08 ">https://github.com/r3x08 </a></p>

<h2>Отказ от ответственности</h2>

<p>Пожалуйста, используйте этот скрипт на свой страх и риск. Создатель не несет ответственности за любой ущерб или потерю данных, которые могут произойти в результате использования этого скрипта.</p>
