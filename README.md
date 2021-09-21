# Noise-mashine
## [Discord] бот для прослушивания музыки

### Цели проекта:
- Получение новых знаний
- Упрощение жизни
- Богатство и слава ~~но это не точно~~

### Наша миссия 
Дать пользователям простой инструмент для совместного прослушивания музыки в Discord, в то время когда подобные крупные проекты блокируются. 

Этот же проект может быть развернут на личном ПК пользователя (или на арендованном сервере, почему бы и нет) и грозные дядьки из _Google_ не узнают об этом.

### Техническое задание
Необходимо написать реализацию бота для [Discord] с использованием языка .Net. При создании нужно сделать возможным обращение к боту (который выступает сервером) через веб-интерфейс.

Веб-интерфейс необходим для альтернативного способа управления аудио-источниками и будет отображать больше информации пользователю в удобном виде.

##### Требования к серверу
- Реализацию необходимо написать на языке .Net
- Возможность воспроизведения аудио в голосовом канале Discord-сервера
- Наличие очереди из аудио-источников, возможность ими управлять:
    - добавление источника
    - переход к следующему источнику
    - очистка очереди
- Отображение информации о текущем источнике по запросу пользователя

##### Требования к веб-интерфейсу
- Реализацию необходимо написать с использованием HTML, CSS и JavaScript
- Дать аналогичные возможности по управлению ботом, как и при обращении с Discord-сервера
- Удобное отображение информации
- Дружественный интерфейс, понятный большинству пользователей

##### Стек инструментов
- [Discord Bot API] для языка .Net
- [Victoria] (API LavaLink для .Net)
- [LavaLink]
- [React.js]

### Контрольные точки, промежуточные результаты
Пока что контрольные точки отсутствуют.

### Команда проекта
- Пронюк Андрей: Full-Stack Developer
- Жулай Владислав: .Net Developer

### Риски и меры избежания
Единственный риск - пандемия, которая присутствует в нашей повседневной жизни.

Ну и лень, куда же без нее.

### Стейкхолдер (заинтересованные люди)
- Мы (разработчики)
- Люди, которым нужен личный бот для музыки
- Преподаватель Проектного практикума, которой нужно сдать эту работу

### Бюджет
Как и у большинства OpenSource-проектов, бюджета нет, все делается на голом энтузиазме.

[Discord Bot API]: <https://github.com/discord-net/Discord.Net>
[Victoria]: <https://github.com/Yucked/Victoria>
[LavaLink]: <https://github.com/freyacodes/Lavalink>
[React.js]: <https://github.com/facebook/react>
