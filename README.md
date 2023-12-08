# LB-1
Выполнил студент группы: ББМО-02-23 Костомахин Антон Александрович
# Цель: #
Создать и настроить две виртуальные машины на базе ОС Debian 12 в среде VirtualBox, установить и настроить Keycloak, развернуть тестовое приложение и включить двухфакторную аутентификацию OTP через Keycloak.

# Для выполнения лабораторной работы нам потребуется 
1. Создание виртуальных машин
Скачан образ ОС Debian 12.1.0 AMD64 Netinst с сайта Debian.
Установлен VirtualBox версии 6.0 с официального сайта.
Созданы две виртуальные машины в VirtualBox с установленной ОС Debian 12.
2. Обеспечение сетевого обмена
Настроен сетевой обмен между двумя виртуальными машинами в соответствии с инструкцией VirtualBox Manual.
3. Установка и настройка Keycloak на ВМ 1
Установлен Keycloak на первой виртуальной машине в соответствии с документацией Keycloak Server Administration.
Выполнена первоначальная настройка Keycloak.
Создан Realm.
Добавлены пользователи "appadmin" и "user" в созданный Realm.
4. Начальная настройка
Развернуто тестовое приложение на второй виртуальной машине согласно инструкции Introduction to IAM with Keycloak.
Настроено подключение тестового приложения к Keycloak для аутентификации и авторизации.

![image](https://github.com/KOSTILET/LB-1/assets/64083435/04f10238-fcda-45a2-9771-bc370f454a6c)

![image](https://github.com/KOSTILET/LB-1/assets/64083435/7b28a873-58fb-4cf0-9448-9dc0674baadc)

![image](https://github.com/KOSTILET/LB-1/assets/64083435/5d0873e0-2552-4185-8975-90695dcc7c54)

![image](https://github.com/KOSTILET/LB-1/assets/64083435/62aae47a-79f2-4eeb-a15f-b3bb8fae489f)

![image](https://github.com/KOSTILET/LB-1/assets/64083435/196b1d09-0356-481a-8d73-2abf0332845a)

![image](https://github.com/KOSTILET/LB-1/assets/64083435/fbdd900d-cdd7-4513-8c99-96160d61254d)

5. Настройка Jupyter Hub

![image](https://github.com/KOSTILET/LB-1/assets/64083435/138375eb-47ae-47a2-b4cf-32b2adf2b7f5)

![image](https://github.com/KOSTILET/LB-1/assets/64083435/701e40f4-58fe-4251-8956-863ba1edd453)

![image](https://github.com/KOSTILET/LB-1/assets/64083435/2e2ca7f0-7671-40e7-b8f2-ceb5d5c43930)

6. Включение двухфакторной аутентификации OTP
Включена двухфакторная аутентификация OTP через Keycloak для защищаемого приложения, согласно инструкциям Ultimate Security и MasterTheBoss.

![image](https://github.com/KOSTILET/LB-1/assets/64083435/b5f4e800-8494-4d88-b7d0-af9a9f103976)

![image](https://github.com/KOSTILET/LB-1/assets/64083435/e87e1666-6567-4e2f-8c2b-55dd2fd5d46d)
