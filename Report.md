# Отчёт о тестировании **приложения "Credit Card Number Validator"**

## Краткое описание

01.09.2020 было проведено функциональное позитивное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1,5 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/MariaPlotnikova03/Credit-Card-Number-Validator/issues/3

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Документация: "[Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)";
* Исполняемый код приложения: [Задача №2 - Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro).
* В качестве тестовых данных использовались данные с сайта [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):

Валидные значения номеров карт:

    VISA:
    * 4916820183259346 - OK
    * 4716009983075571 - OK
    * 4167573470239826683 - FAIL

    MasterCard:
    * 5561219936964648 - OK
    * 5274693599258761 - OK
    * 5171984274392429 - OK

    American Express (AMEX):
    * 375110866463023 - FAIL
    * 371334873135234 - FAIL
    * 377557775788999 - FAIL

    Discover:
    * 6011141856978339 - OK
    * 6011457807610031 - OK
    * 6011557720720039701 - FAIL

    JCB:
    * 3545879360166725 - OK
    * 3589963586809214 - OK
    * 3544412200672435270 - FAIL

    Diners Club - North America:
    * 5584489859594242 - OK
    * 5491168797548583 - OK
    * 5483335677445772 - OK

    Diners Club - Carte Blanche:
    * 30093903032620 - FAIL
    * 30081960052946 - FAIL
    * 30438745539631 - FAIL

    Diners Club - International:
    * 36333775148375 - FAIL
    * 36059561012703 - FAIL
    * 36722790634239 - FAIL

    Maestro:
    * 0604468790028442 - OK
    * 6304565797733062 - OK
    * 6761366293210580 - OK

    Visa Electron:
    * 4844302196750188 - OK
    * 4508808796298680 - OK
    * 4844526755013196 - OK

    InstaPayment:
    * 6374903121377519 - OK
    * 6378293439528714 - OK
    * 6395943746198077 - OK

Тестирование производилось в следующем окружении:
* Компьютер на базе х64
* Windows 10 Pro версия 1909 (Сборка ОС 18363.1016)
* openjdk version "11.0.8" 2020-07-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* IntelliJ IDEA Community 2020.2.1.IC-202.6948.69 
