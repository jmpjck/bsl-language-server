# Подряд идущие пустые строки (ConsecutiveEmptyLines)

| Тип | Поддерживаются<br/>языки | Важность | Включена<br/>по умолчанию | Время на<br/>исправление (мин) | Тэги |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `Дефект кода` | `BSL`<br/>`OS` | `Информационный` | `Да` | `1` | `badpractice` |

## Параметры 

| Имя | Тип | Описание | Значение по умолчанию |
| :-: | :-: | :-- | :-: |
| `maxEmptyLineCount` | `Целое` | ```Домустимое количество пустых строк подряд``` | ```2``` |

<!-- Блоки выше заполняются автоматически, не трогать -->
## Описание диагностики
Для разделения блоков кода между собой используется вставка пустой строки. 
Вставка нескольких пустых строк не несет данной ценности и приводит к бессмысленному увеличению длины метода.

## Примеры
<!-- В данном разделе приводятся примеры, на которые диагностика срабатывает, а также можно привести пример, как можно исправить ситуацию -->

## Источники

## Сниппеты

<!-- Блоки ниже заполняются автоматически, не трогать -->
### Экранирование кода

```bsl
// BSLLS:ConsecutiveEmptyLines-off
// BSLLS:ConsecutiveEmptyLines-on
```

### Параметр конфигурационного файла

```json
"ConsecutiveEmptyLines": {
    "maxEmptyLineCount": 2
}
```