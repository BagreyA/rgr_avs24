Для заданий, подразумевающих запуск веб-приложения, терминирует ssl и обрабатывает домены nginx в режиме прокси-сервера или traefik.
Приложения должны быть доступны по стандартному https порту (https://a.example.com, и тп)

### Запуск jenkins и разработка сценариев CD
1. Интерфейс доступен по https (jenkins)
2. В jenkins создан пайплайн/задача/таск, работающий с репозиторием github. При изменении в репозитории автоматически запускается задача обновления docker-контейнера с содержимым репозитория (Либо сборка образа с новым приложением и обновление контейнера)
3. Оформить как docker-compose.yml
4. При пересоздании проекта, все настройки jenkins должны сохраниться
