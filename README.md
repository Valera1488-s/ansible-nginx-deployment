# ansible-nginx-deployment
# Автоматизация развертывания Nginx с помощью Ansible

## Описание
Развернул веб-сервер Nginx на виртуальной машине в Яндекс.Облаке с использованием Ansible для автоматизации процесса.

## Цель
Автоматизировать развертывание веб-сервера для обеспечения масштабируемости и упрощения управления инфраструктурой.

## Используемые технологии
- Ansible
- Nginx
- Яндекс.Облако
- Ubuntu

## Шаги выполнения
1. Настройка виртуальной машины в Яндекс.Облаке.
2. Создание и настройка inventory файла для Ansible.
3. Написание playbook для установки и запуска Nginx.
4. Запуск playbook и проверка работы Nginx.

## Результаты
Nginx был успешно установлен и запущен на виртуальной машине. Веб-сервер работает и обслуживает запросы.

## Выводы
Я научился использовать Ansible для автоматизации развертывания сервисов и понял важность инфраструктуры как кода (IaC).
![Screenshot from 2025-01-04 14-01-13](https://github.com/user-attachments/assets/acb26c27-c7ad-49a9-ad99-09c568610190)
![Screenshot from 2025-01-04 14-00-40](https://github.com/user-attachments/assets/c9f14ca7-0969-48ee-8436-211fb5d7bd07)
install_nginx.yml и hosts scrn'shots
![Screenshot from 2025-01-04 14-08-50](https://github.com/user-attachments/assets/de01a40f-ae38-4cd1-95f2-9b7603e681d1)
![Screenshot from 2025-01-04 14-08-32](https://github.com/user-attachments/assets/fcce290c-2f21-4da3-a586-3bf8a1cb2b1a)

Особо важные базовые вещи и команды для девопс ,в моем исполнении..AD-HOC ANSIBLE COMMANDS

Копировать файл с локального сервера на ansible server (controlled service)
![Screenshot from 2025-01-07 12-31-55](https://github.com/user-attachments/assets/ae0ed341-3b9c-4cac-9297-ad866bcdbf44)
IFORMATION ABOUT ALL ENABLE SERVERS.
![Screenshot from 2025-01-07 12-32-28](https://github.com/user-attachments/assets/39f4d090-8fcd-4d0b-8196-2348dab7a473)
Пример выполнения одной из базовых и многочисленных команды, указывая Ansible использовать модуль shell
![Screenshot from 2025-01-07 12-34-00](https://github.com/user-attachments/assets/ab269fa3-3b11-494f-9624-ac0928fad0fb)
Базовый пример перехода управляемого Ansible - controlled service на веб сайт
![Screenshot from 2025-01-07 13-40-28](https://github.com/user-attachments/assets/5cb6c2ca-4a97-4f26-b49f-f73e7c5f9073)
![Screenshot from 2025-01-07 13-42-21](https://github.com/user-attachments/assets/cad35926-1257-4a71-9184-3e45eccc9066)
Запуск с помощью Ansible, веб - сервера Apache, и дальнейшее отображение перехода через строку браузера в качестве успешности подтверждения
![Screenshot from 2025-01-07 13-54-15](https://github.com/user-attachments/assets/f3bc9663-1c2f-4c8f-b6cf-0068465f7985)
![Screenshot from 2025-01-07 14-04-47](https://github.com/user-attachments/assets/4a7948bb-4c7f-435d-9a44-8a5751cc4557)
