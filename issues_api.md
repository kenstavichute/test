### Задание  
С помощью Postman протестируйте работу следующих методов:
  - Создайте issue с названием Issue 1, описанием Something went wrong. Также у этой issue должен быть label — bug — и assignee — вы (текущий логин на GitHub).
  - Получите список issues.
  - Измените название задачи на Issue 2.
  - Удалите Issue 2.*

*`REST API GitHub не позволяет удалять созданные задачи, поэтому в последнем шаге созданная задача переведена в статус "закрыта", что удаляет её из списка задач в работе в репозитории`
  
 **Результаты тест-рана коллекции:**   
 `Перед запуском тест-рана коллекции в параметры коллекции добавлен личный токен`  
 `Для получения токена необходимо залогиниться в свой профиль на Github, затем пройти Профиль-Settings-Developer settings-Personal access tokens-Tokens classic и сгенерировать новый токен`
 <div align="left">
<img height="400" src="https://github.com/kenstavichute/test/blob/main/githud_issues_run_result.png">
 </div>
    
***
[Ссылка на коллекцию](https://github.com/kenstavichute/test/blob/main/GitHub_issues.postman_collection.json)
