#  Видеоплеер

Браузерный видеоплеер с минимальным набором функций.




## Запуск

Для запуска, скачайте все файлы из репозитория и запустите `index.html`

Проигрываемое видео подключается в файле `index.html` скриптом с помощью аргумента `src`:
```
  <script type="text/javascript">
    createPlayer({
      elementId: 'player',
      src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4',
    });
  </script>
```

## Демо-версия плеера
Демо-версия плеера доступна по [ссылке](https://0viktory0.github.io/player/).

## Цели проекта

Код написан в учебных целях — это урок в курсе по Python и веб-разработке на сайте [Devman](https://dvmn.org).