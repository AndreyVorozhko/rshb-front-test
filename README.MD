Подход к верстке в окружении текущего шаблона.

Что предлагается: 

1. Скачиваем страницу, для которой планируются изменения, например https://www.rshb.ru/natural/cards/

Делать это, как мне кажется через wget:

```
./wget.exe --convert-links --adjust-extension --page-requisites --no-parent --load-cookies=cook  --save-cookies=cook --keep-session-cookies --user-agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/104.0.0.0 Safari/537.36" http://www.rshb.ru/natural/cards/
```

(так я и скачал код, который в данном репозитории лежит)

2. Закидываем под гит

3. Начинаем вносить свои правки

Файл который надо править лежит в /natural/cards/

4. После того, как работа закончена коммитим изменения и пушим в гит.