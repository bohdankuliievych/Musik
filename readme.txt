This is a regular template compatible with GULP.

For regular usage:
	index.html
	scss/style.scss
	js/script.js
(you need Dart Sass installed and must execute
sass --watch src/scss:src/css
at every start of your work before you run live server).

Робота з файлами в GULP:
- Картинки в HTML вставляємо src='@img/'
- gulp буде запускати browser-sync в Google Chrome, за потреби редагуйте gulp/tasks/server.js.
- Файли шрифтів .otf кладемо в src/fonts , видаляємо src/scss/globals/_fonts.scss якщо він є.