## Git удаленный

# -v
Показывает URL-адреса удаленных репозиториев при перечислении текущих удаленных подключений. 

### Примеры использования
Вы можете запросить список всех удаленных репозиториев, которые в данный момент подключены к вашему локальному репозиторию:
```bash

$ git remote -v
  origin  https://test@github.com/test/example.git (fetch)
  origin  https://test@github.com/test/example.git (push)
  ```
Используйте параметр «add», если вы хотите подключить новый удаленный репозиторий, в этом примере названный «production»:
```
$ git remote add production https://test@github.com/test/example.git

```