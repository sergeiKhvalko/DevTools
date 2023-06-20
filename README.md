# Домашняя работа

## Network

**1. На вкладке Network**

- [Записать и сохранить в HAR архив профиль загрузки ресурсов при открытии страницы](./Network/www.gd.ru.har)

### Найти неоптимальные места

1. Дублирование ресурсов
   <img src="./Network/duplicate.png" width=90%>
   <img src="./Network/duplicate_2.png" width=90%>
   <img src="./Network/duplicate_3.png" width=90%>
   <img src="./Network/duplicate_4.png" width=90%>
   <img src="./Network/duplicate_5.png" width=90%>
2. Лишний размер ресурса. Были выбраны файлы с лишними комментариями/большими отступами
   <img src="./Network/overweight.png" width=90%>
   <img src="./Network/overweight_2.png" width=90%>
   <img src="./Network/overweight_3.png" width=90%>
   <img src="./Network/overweight_4.png" width=90%>
   <img src="./Network/overweight_5.png" width=90%>
   <img src="./Network/overweight_6.png" width=90%>
3. Медленно загружающиеся ресурсы
   <img src="./Network/slow.png" width=90%>
4. Ресурсы, блокирующие загрузку
   <img src="./Network/block.png" width=90%>
5. Что-то ещё (ресурсы которые упали с ошибкой)
   <img src="./Network/errors.png" width=90%>

### На вкладке Performance

1. [Записать и сохранить в файл профиль загрузки страницы](./Perfomance/Trace-20230618T015119.json)
2. Измерить время в миллисекундах от начала навигации до событий First Paint (FP), First Contentful Paint (FCP), Largest Contentful Paint (LCP), DOM Content Loaded (DCL), Load
   <img src="./Perfomance/stage_1.png" width=90%>
   <img src="./Perfomance/stage_2.png" width=90%>
   <img src="./Perfomance/stage_3.png" width=90%>
   <img src="./Perfomance/stage_4.png" width=90%>
   <img src="./Perfomance/stage_5.png" width=90%>
3. Определить, на каком DOM-элементе происходит LCP
   <img src="./Perfomance/stage_6_source.png" width=90%>
4. Измерить, сколько времени в миллисекундах тратится на разные этапы обработки документа (Loading, Scripting, Rendering, Painting)
   <img src="./Perfomance/processing.png" width=90%>

### На вкладке Coverage

1. Cохранить скриншот вкладки после загрузки страницы
   <img src="./Coverage/cov.png" width=90%>
2. Измерить в килобайтах объём неиспользованного CSS в ходе загрузки страницы (198kB)
   <img src="./Coverage/cov_css.png" width=90%>
3. Измерить в килобайтах объём неиспользованного JS в ходе загрузки страницы (1.4MB)
   <img src="./Coverage/cov_js.png" width=90%>

## Дополнительное задание

### Найти неоптимальные места

Slow полностью совпадает с анализом неоптимальных мест выше по тексту
<img src="./Slow/networking.png" width=90%>

1. [Записать и сохранить в HAR архив профиль загрузки ресурсов при открытии страницы](./Slow/www.gd.ru.har)

### На вкладке Performance

1. [Записать и сохранить в файл профиль загрузки страницы](./Slow/Trace-20230618T020748.json)
2. Измерить время в миллисекундах от начала навигации до событий First Paint (FP), First Contentful Paint (FCP), Largest Contentful Paint (LCP), DOM Content Loaded (DCL), Load
   <img src="./Slow/stage_1.png" width=90%>
   <img src="./Slow/stage_2.png" width=90%>
   <img src="./Slow/stage_3.png" width=90%>
   <img src="./Slow/stage_4.png" width=90%>
   <img src="./Slow/stage_5.png" width=90%>
3. Определить, на каком DOM-элементе происходит LCP
   <img src="./Slow/stage_4_source.png" width=90%>
4. Измерить, сколько времени в миллисекундах тратится на разные этапы обработки документа (Loading, Scripting, Rendering, Painting)
   <img src="./Slow/all.png" width=90%>

### На вкладке Coverage

1. Cохранить скриншот вкладки после загрузки страницы
   <img src="./Slow/all_usage.png" width=90%>
2. Измерить в килобайтах объём неиспользованного CSS в ходе загрузки страницы(211kB)
   <img src="./Slow/css_usage.png" width=90%>
3. Измерить в килобайтах объём неиспользованного JS в ходе загрузки страницы(1.6MB)
   <img src="./Slow/js_usage.png" width=90%>
