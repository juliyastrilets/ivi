# ТЗ тестового задания:
Здесь не будет зеплинов, скетчей и псд'шек.Это не проверка точности и умения пользоваться пипеткой или линейкой. Цвета, размеры, соотношения сторон и отступы на ваше усмотрение. Это проверка подхода и отношения к своей работе. Покажите возможный максимум из того, что вы умеете.

Видео для задания доступно по ссылке: https://www.dropbox.com/s/5gswtwmzto8810y/tz.mov?dl=0

Минимум, который мы ожидаем:
Gulp;
LESS или Stylus;
Pug;
Автоматическую расстановку вендорных префиксов;
Автоматическое развёртывание http сервера разработки;
Минификация и обфускация боевого кода;
Результат в виде двух ссылок:
На репозиторий GitHub или GitLab, в котором находятся: исходный код, сборщик, результат сборки;
На рабочее демо, опубликованное, например, с помощью GitHub Pages;

P.S.: Можно SASS, можно Grunt, можно хоть RoR или ванильный код, но в README.MD обоснуйте ваш выбор чем-либо, кроме личных предпочтений.


## обоснование выбора:

**webpack:**
У меня полностью настроенное под себя окружение webpack. gulp - таск раннер, а вебпак сборщик. Очевидно что сборщик, тем более современный, лучше старого gulp у которого пакеты по 3 года не обновляются.

**sass:**
Просто для красоты проекта, так как в pug нет скобок, почему бы и не sass. Мое личное предпочтение я бы отдавала scss.

**PS:**
Технологии не важны. Важны люди и ценности компании.


## установка зависимостей:
```
npm i
```

## запуск проекта:
```
npm run serve
```

## сборка проекта:
```
npm run build
```

## сборка проекта с минификацией файлов:
```
npm run build:min
```

## особенности сброки:
```
Webpack 5
EditorConfig
Нативный JS: Babel
Разметка: Pug
Стили: Sass / Scss / Autoprefixer
```

## псевдонимы:
```
путь к папке images: ~img
путь к папке fonts: ~fonts
```
