# Домашнее задание: TeamCity

Репозиторий: https://github.com/TrashDokiDoki/example-teamcity

- TeamCity server и agent развёрнуты в Yandex Cloud, агент авторизован.
- Nexus развёрнут и принимает Maven-артефакты.
- В master выполняется `mvn clean deploy`, в других ветках — `mvn clean test`.
- Ветка `feature/add_reply` содержит новый метод Welcomer и тест на слово `hunter`; её сборка прошла успешно, изменения слиты в master.
- Конфигурация TeamCity хранится в `.teamcity`.
- Сборка master #12 завершилась успешно: 5 тестов пройдены, файлы `plaindoll-0.0.4.jar` и `original-plaindoll-0.0.4.jar` доступны во вкладке Artifacts.

# Скрины

<img width="1851" height="1007" alt="Снимок экрана 2026-09-26 172623" src="https://github.com/user-attachments/assets/30969296-f665-44ba-b3f5-ce6cfe1a8618" />

<img width="1851" height="1009" alt="image" src="https://github.com/user-attachments/assets/91e70334-a4df-404b-827e-4b56f40a2afe" />

<img width="1849" height="1008" alt="Снимок экрана 2026-09-26 211339" src="https://github.com/user-attachments/assets/647e26e2-89d5-4b3c-a881-51864cfaabe1" />
