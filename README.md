# shri-2020-home-task-DevTools

### Network

- HAR архив лежит в репозитории - `lifehacker.ru.har`

- дублирование ресурсов

  Реклама

  <details>
  <summary>Дублирование 1</summary>

  ![](img/repeated_1.png)
  </details>

  <details>
  <summary>Дублирование 2</summary>

  ![](img/repeated_2.png)
  </details>

  <details>
  <summary>Дублирование 3</summary>

  ![](img/repeated_3.png)
  </details>

  <details>
  <summary>Дублирование 4</summary>

  ![](img/repeated_4.png)
  </details>

  <details>

  <summary>Дублирование 5</summary>

  ![](img/repeated_5.png)
  </details>


- лишний размер ресурса

  Есть несколько несжатых jpeg картинок и большие скрипты, значительная часть кода которых не используется. Некоторые скрипты и стили грузятся в нескольких версиях.

  <details>
  <summary>Лишний размер</summary>

  ![](img/big_size.png)
  </details>


- медленно загружающиеся ресурсы

  Дольше всего грузятся несжатые картинки и некоторые скрипты.

  <details>
  <summary>Медленная загрузка</summary>

  ![](img/slow_loading.png)
  </details>

- ресурсы, блокирующие загрузку

  

### Performance

- профиль загрузки страницы лежит в репозитории - `performance-profile.json`

- время в миллисекундах от начала навигации до событий
  - **First Paint:** 671.9 ms
  - **First Meaningful Paint:** 1405.4 ms
  - **DOM Content Loaded:** 2935.8 ms
  - **Load:** 6250.3 ms

- сколько времени в миллисекундах тратится на разные этапы обработки документа
  - **Loading:** 104 ms
  - **Scripting:** 2578 ms
  - **Rendering:** 1412 ms
  - **Painting:** 257 ms

### Coverage

- скриншот вкладки после загрузки страницы
![](img/coverage.png)

- объём неиспользованного CSS: 387 KB

- объём неиспользованного JS: 1.4 MB