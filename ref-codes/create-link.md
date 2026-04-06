# Створення реф-посилання

Бот допоможе створити чисте реферальне посилання з будь-якої промо-сторінки BingX.

## Як створити

**Головне меню → «🔗 Створити реф-посилання»**

1. Якщо у вас кілька рефкодів — оберіть потрібний
2. Вставте посилання на акцію або промо BingX
3. Бот поверне чисте посилання з вашим `?ref=CODE`

## Приклад

**Ви вставляєте:**
```
https://bingx.com/ru-ru/act/ferrari/future/?ch=bingx_topbar&utm_source=app
```

**Бот повертає:**
```
https://bingx.com/ru-ru/act/ferrari/future/?ref=CryptaBingX
```

{% hint style="success" %}
Бот автоматично прибирає зайві параметри (`ch=`, `utm_source=` тощо) і залишає тільки ваш рефкод.
{% endhint %}

## Підтримувані формати URL

Бот працює з будь-якими посиланнями `bingx.com`:
- `bingx.com/ru-ru/act/...`
- `bingx.com/en-us/act/task/...`
- `bingx.com/invite/...`
- `bingx.com/partner/...`
- `bingxdao.com/...`
