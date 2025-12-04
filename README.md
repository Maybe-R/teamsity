# Домашнее задание к занятию 11 «Teamcity»

## Подготовка к выполнению

1. В Yandex Cloud создайте новый инстанс (4CPU4RAM) на основе образа `jetbrains/teamcity-server`.
2. Дождитесь запуска teamcity, выполните первоначальную настройку.

<img width="2078" height="1356" alt="image" src="https://github.com/user-attachments/assets/9997b47b-e615-446c-a244-63a041706eda" />

<img width="2350" height="1358" alt="image" src="https://github.com/user-attachments/assets/9cad75ff-da6c-48c8-9a55-fa41a455c4d8" />
   
3. Создайте ещё один инстанс (2CPU4RAM) на основе образа `jetbrains/teamcity-agent`. Пропишите к нему переменную окружения `SERVER_URL: "http://<teamcity_url>:8111"`.
4. Авторизуйте агент.

<img width="1262" height="774" alt="image" src="https://github.com/user-attachments/assets/58618e9e-c4e5-40d1-aff2-dbc10b69d356" />

   
6. Сделайте fork [репозитория](https://github.com/aragastmatb/example-teamcity).
7. Создайте VM (2CPU4RAM) и запустите [playbook](./infrastructure).

## Основаая часть

1. Создайте новый проект в teamcity на основе fork.

<img width="2490" height="618" alt="image" src="https://github.com/user-attachments/assets/b93fe721-d88f-4722-8a5a-5a6aba349d0f" />

2.Сделайте autodetect конфигурации и сохраните необходимые шаги, запустите первую сборку master.

<img width="2486" height="977" alt="image" src="https://github.com/user-attachments/assets/f6386f59-c7b3-4a9f-bc9d-e7cd8afd3979" />


