Инструкция по коммиту в репозиторий
Создайте новую ветку в GitHub: git checkout -b feature/desktop-wrapper
Создайте в корне репозитория папку desktop-app.
Положите туда три файла: index.html, package.json и ваш файл icon.png (512x512).
Добавьте, закоммитьте и отправьте:
git add desktop-app/
git commit -m "feat: добавлен десктопный лаунчер NW.js с защитой пин-кодом. Пин-код для запуска приложения указан в отдельном файле index.html, строчка const CORRECT_PIN."
git push -u origin feature/desktop-wrapper
Создайте Pull Request в основную ветку.
