
# Практическая работа 0
## Выполнил Яковлев Александр, группы БИСО-03-20

```
@startuml "Практическая работа 0"
left to right direction 
skinparam packageStyle rect
actor Студент 
actor библиотекарь

rectangle библиотека{
Студент -- (поиск каталога)
Студент -- (заказ книг) 
Студент -- (работа в читальном зале)

библиотекарь -- (проверить остаток наличных) 
библиотекарь -- (консультации)
note right of (консультации): включая рекомендации книг по теме и обучение использованию поисковой системы и заполнение бланков заказа
}
@enduml
```

