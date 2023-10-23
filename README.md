### Hexlet tests and linter status:
[![Actions Status](https://github.com/antliubimov/frontend-testing-react-project-67/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/antliubimov/frontend-testing-react-project-67/actions)

# PageLoader

## Description:
PageLoader - утилита командной строки, которая скачивает страницы из 
интернета и 
сохраняет их на компьютере. Вместе со страницей она скачивает все ресурсы (картинки, стили и js) давая возможность открывать страницу без интернета.

Пример использования:
```bash
page-loader --output /var/tmp https://ru.hexlet.io/courses

✔ https://ru.hexlet.io/lessons.rss
✔ https://ru.hexlet.io/assets/application.css
✔ https://ru.hexlet.io/assets/favicon.ico
✔ https://ru.hexlet.io/assets/favicon-196x196.png
✔ https://ru.hexlet.io/assets/favicon-96x96.png
✔ https://ru.hexlet.io/assets/favicon-32x32.png
✔ https://ru.hexlet.io/assets/favicon-16x16.png
✔ https://ru.hexlet.io/assets/favicon-128.png

Page was downloaded as 'ru-hexlet-io-courses.html'
```
Утилита скачивает ресурсы параллельно и показывает прогресс по каждому ресурсу в терминале
