# Отчёт о тестировании приложения KeyValidator

## Краткое описание

21.08.2020 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/dianest/Java1KeyValidator/issues/1
* https://github.com/dianest/Java1KeyValidator/issues/2
* https://github.com/dianest/Java1KeyValidator/issues/3
* https://github.com/dianest/Java1KeyValidator/issues/4

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Тестовая документация: Инструкция по установке OpenJDK11 
* Тестовая документация: Руководство использования KeyValidator
* Тестовая документация: шаблон отчета о тестировании
* Тестовая документация: шаблон составления issue
* Тестовые данные для проверки: валидные и невалидные ключи


В качестве тестовых данных использовались данные из руководства использования https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md:
* Ключ 00000000-0000-0000-0000-000000000000, Result for 00000000-0000-0000-0000-000000000000: OK
* Ключ 00000000-0000-0000-0000-000000000001, Result for 00000000-0000-0000-0000-000000000001: FAIL
* Ключ 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998, Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* Ключ 80b427f8-92cd-3aae-ba04-3927fbe17c6, Result for 80b427f8-92cd-3aae-ba04-3927fbe17c6: OK
* Ключ b295bc63-9f03-3b4b-af80-969b39f8c262, Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* Ключ 387eedc6-12e9-3b32-9881-63b6b5e85317, Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: OK
* Ключ c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180, Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK
* Ключ 18252235-78e0-44a5-8720-556f0c7da17a, Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Ключ e66075b6-ddad-445e-baf6-161b3289522b, Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Ключ b6d53250-f07e-4352-a293-6102ddf7f1ca, Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Ключ c2bc778a-1cb9-46c6-b435-0489649d2a42, Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Ключ 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1, Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL


Тестирование производилось в следующем окружении:
* Устройство: LAPTOP-7I83Q8PM
* OC Windows 10, version 1909 (OC Build 18363.1016)
* Openjdk version "11.0.8" 2020-07-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)