# Установка статуса и его настройка

* Чтобы статус корректно работал, необходимо в строке 33 (переменная delta) указать свой часовой пояс (в МСК +3 часа)
* Также вбить в строку 22 данные для входа
* И вписать в строку 39 тот статус, который хотите Вы: 
```python
vk_session.method("status.set", {"text": "ваш_статус" + nowtime})
```
