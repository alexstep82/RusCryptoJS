# [RusCryptoJS](https://aleksandr-ru.github.io/RusCryptoJS/)
JS для Российской криптографии (ГОСТ).

### Общие требования
- Окружение с поддержкой ES2015

## Крипто-ПРО
Для работы с Крипто-ПРО 4.x и Browser Plugin 2.x (cades plugin)

### Возможности
- Электронная подпись
- Совместная подпись двумя сертификатами (CoSign)
- Добавление подписи к существующей
- Проверка подписи
- Шифрование/дешифрование данных
- Получение списка всех сертификатов
- Выпуск сертификата (ГОСТ Р 34.10-2001, ГОСТ Р 34.10-2012)
- Получение информации об установленном сертифкате
- Экспорт установленного сертификата

Примеры использования см. в [документации](https://aleksandr-ru.github.io/RusCryptoJS/cryptopro.html).

### Известные проблемы
- Тестирование функций в синхронном режиме (IE) производилось по остаточному принципу, поэтому возможны неожиданные проблемы;
- В синхронном режиме (IE) не поддерживается задание пин-кода при выпуске сертификата и создании подписей, всегда выдается диалог крипто-про для ввода;
- В синхронном режиме (IE) моежет не работать режим кеширования ПИН-кодов при подписании (bind);
- Дешифрование может не работаь при использовании сертификатов ГОСТ Р 34.10-2012 под macOS.

## JaCarta ГОСТ
Для работы с JaCarta Web Client 3.x

**Считается устаревшим и не рекомендуется к использованию, вместо него используйте JaCarta-2 ГОСТ**

### Возможности
- Электронная подпись
- Получение списка всех сертификатов
- Выпуск сертификата (ГОСТ Р 34.10-2001)
- Получение информации об установленном сертифкате
- Экспорт установленного сертификата
- Очистка токена от контейнеров

Примеры использования см. в [документации](https://aleksandr-ru.github.io/RusCryptoJS/jacarta.html).

## JaCarta-2 ГОСТ
Для работы с JaCarta Web Client 4.x

### Возможности
- Электронная подпись
- Шифрование/дешифрование данных
- Получение списка всех сертификатов
- Выпуск сертификата (ГОСТ Р 34.10-2001, ГОСТ Р 34.10-2012)
- Получение информации об установленном сертифкате
- Экспорт установленного сертификата
- Очистка токена от контейнеров

Примеры использования см. в [документации](https://aleksandr-ru.github.io/RusCryptoJS/jacarta2.html).

## RuToken
Для работы с RuToken ЭЦП (не путать с RuToken Lite и др.)

### Возможности
- Электронная подпись
- Добавление подписи к существующей
- Шифрование/дешифрование данных
- Получение списка всех сертификатов
- Выпуск сертификата (ГОСТ Р 34.10-2001, ГОСТ Р 34.10-2012)
- Получение информации об установленном сертифкате
- Экспорт установленного сертификата
- Очистка токена

Примеры использования см. в [документации](https://aleksandr-ru.github.io/RusCryptoJS/rutoken.html).

### Известные проблемы
- В Linux старые версии рутокен плагин работает только в Firefox 52 (тк использует устаревший NPAPI), информацию о том, как установить и совместно использовать старый FF вместе с новым см. [здесь](http://aleksandr.ru/blog/neskolko_versiy_firefox_v_linux_odnovremenno/);
- В Linux свежие версии рутокен плагин не работают в Сhrome (но работают в Opera).

## Помогите развивать проект

<a href="https://www.buymeacoffee.com/aleksandr.ru" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

В отличие от ведущих производителей СКЗИ, которые требуют покупать лицензии для использования своего софта, библиотека **RusCryptoJS всегда будет бесплатной и открытой**. Поскольку проект развивается на общественных началах и не приносит прибыли, то не всегда есть достаточно времени на его разработку. Благодаря вашей поддержке сил на развитие будет больше, спасибо!

## Благодарности

[![JetBrains](docs/images/jetbrains.png?raw=true)](https://www.jetbrains.com/?from=RusCryptoJS "Проект разрабатывается при поддержке JetBrains")
