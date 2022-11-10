Предметная область: Универсальный компьютерный магазин
<h2>1. Введение</h2>

В современном мире почти у каждого есть компьютер, поэтому существует большой спрос на их покупку, а также на комплектующие для них. Для этого создаются компьютерные магазины, и в них возникает проблема организации заказов, для этого придумываются программы, работающие с базами данных, для удобной сортировки и работы с заказами людей.
<h2>1.1 Анализ предметной области</h2>

Универсальный компьютерный магазин предоставляет различные услуги для его клиентов от обычной продажи комплектующих для системного блока, до сборки компьютера под заказ. Также есть услуга по ремонту компьютеров.

В магазине можно купить как готовый собранный компьютер, так и отдельные комплектующие. Под комплектующими подразумеваются все возможные виды деталей: материнский платы, процессоры, видеокарты, ssd, жесткие диски, оперативная память, блоки питания. Комплектующие представляются от слабых до самых мощных на данный момент. Эти операции можно произвести онлайн через сайт, либо непосредственно в самом магазине. Для того, чтобы покупать через сайт клиенту необходимо выбрать интересующий его товар в каталоге, затем заказать его, указав данные своей банковской карты и мобильный номер, затем произвести оплату. После оплаты товар будет зарезервирован на складе, а когда в один из рабочих дней его привезут в магазин, клиенту придёт смс оповещение, что товар можно забрать, а также код подтверждения для получения покупки. Очно в самом магазине клиент может выбрать интересующую его вещь из уже представленного ассортимента и сразу оплатить её на кассе, либо заказать её через сотрудника, и также ждать товар со склада.

Магазин предоставляет услуги ремонта комплектующих и системных блоков, для этого клиент приносит неработающие детали в магазин, сотрудник на кассе оформляет договор по ремонту, после чего передаёт заказ в ремонтный центр, где мастер чинит комплектующие, после чего обратно отправляет их в магазин. После их получения в магазине клиенту приходит смс, и при получении он оплачивает ремонт. 

На сайте есть раздел сборки компьютера, в этом разделе находятся ячейки под все возможные комплектующие. Клиент может выбирать из каталога товаров нужные ему комплектующие и вставлять их в ячейки. Подобрать правильно комплектующие статистический человек вряд ли сможет, очень много деталей нужно учесть: например, видеокарта может просто не влезть в корпус, оперативная память может не подходить к материнской плате или блок питания не обеспечит достаточное питание остальных комплектующих. Для этого в этом разделе сайта предусмотрена проверка на совместимость комплектующих, если они не подходят друг к другу сайт оповестит об этом клиента. После того как клиент создаст свою сборку, он может заказать её. Для этого он производит аналогичные действия по оплате из второго абзаца, за исключением того, что товар не просто резервируется в магазине, а мастер забирает его и собирает компьютер, после чего клиент может забрать его в магазине.

<h2>1.2 Use case модель</h2>

Анализ предметной области и проектирование являются первыми этапами в жизненном цикле создания программного решения. Одним из результатов этого этапа является диаграмма вариантов использования (Use Case), описывающая основные группы пользователей системы и варианты ее использования.

Каждая группа пользователей на диаграмме вариантов использования обозначается человечком (актером), под которым записывается имя группы людей, которую он обозначает.

Группы пользователей используют определённые функции системы. На диаграмме вариантов использования функция системы изображается эллипсом, внутри которого записывается имя функции в форме глагола с пояснительными словами.

На диаграмме для связывания элементов используются различные соединительные линии, которые называются отношениями. Каждое такое отношение имеет собственное название и используется для достижения определённой цели.

![image](https://user-images.githubusercontent.com/105597943/201216502-212591d4-8cdc-4597-8291-a0acf320f288.png)



<h2>1.3 BPMN модель</h2>

BPMN — это метод составления блок-схем, отображающий этапы выполнения бизнес-процесса от начала до конца. BPMN-схемы наглядно и подробно демонстрируют последовательность рабочих действий и перемещение информационных потоков, необходимых для выполнения процесса, а потому являются одним из ключевых инструментов управления бизнесом.

Цель применения метода BPMN — смоделировать способы адаптации под новые условия, а также пути повышения эффективности и конкурентоспособности.


BPMN содержит следующие базовые графические элементы: Пул и Дорожки, Действия, Шлюзы, События и Потоки

![image](https://user-images.githubusercontent.com/105597943/201213177-2f4a8487-c5e6-4db3-af19-8259bab43216.png)

Рисунок 2 - BPMN модель компьютерного интернет магазина
<h2>1.4 ER-диаграмма</h2>

![image](https://user-images.githubusercontent.com/105597943/201203631-577c9ad7-1ed2-45a8-82d3-44af4356e440.png)

<h2>1.5 Проблематика предметной области</h2>

Работа магазинов должна быть хорошо организована для того, чтобы клиентам было удобно заказывать товары, как из дома, так и в самом магазине, также это нужно для того, чтобы поставки товаров в магазины приходили вовремя и организации рабочих процессов. Таких причин очень много. Для этого используются веб приложения.

<h2>2. Сравнительный анализ существующих решений</h2>

Лучше всего хранить информацию в веб приложении, оно намного лучше, чем бумажные носители.
1. Хранение информации в приложении даёт возможность заказывать товары из дома.
2. Легко передавать информацию между сотрудниками разных отделов.
3. Более надежное хранение данных.
4. Разгружает работников.
5. Информация хорошо структурирована.
