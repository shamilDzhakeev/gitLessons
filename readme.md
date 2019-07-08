# Hello

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

1. Проводник
2. Полупроводник
3. Диэлектрик

***
* Классы
* Объекты
* Списки

[пример](http://example.com/ "Необязательная подсказка")

Пример кода:
```app.get('/array', function(req, res) {
  const delay = Math.floor(Math.random() * 2e3 + 1e3);
  const array = generateArray(10);

  setTimeout(function() {
    const error = requestCount % 3 === 0;
    const status = error ? 500 : 200;
    const result = error ? { error: 'Internal Error' } : { result: array };

    requestCount += 1;
    res.status(status);
    res.send(result);
  }, delay);
});
```
