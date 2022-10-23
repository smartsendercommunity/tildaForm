# tildaForm
Передача данных из формы на тильде в переменные Smart Sender


Инструкция по использованию
1. Создать формы на тильде (обычные или в zero-блоке, скрипт работает со всеми формами)
2. Загрузить файл tss.min.js на свой хостинг
3. Добавить на странице тилды следующий код:

[code]<script src="https://api.mufiksoft.com/js/tss.min.js"></script>
<script>
    tssDeepLink("ВАШ ДОМЕН", true, {
        variables: {
            referer: "site.com/qwerty",
        },
    })
</script>[/code]
https://image.mufiksoft.com/chrome_Aik1NiKrFn.jpg

4. Добавить в настройки формы глубокую ссылку или ссылку на страницу "Спасибо" (скрипт сам определит тип ссылки)
5. Если используется ссылка на страницу "Спасибо", добавте на ней стандартный код для передачи utm-меток (все данные с формы добавляются в урл-параметры, как метки)
