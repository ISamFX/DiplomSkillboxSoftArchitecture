
## Вводная 
Вы работаете ведущим архитектором в большой транснациональной компании, производящей спортивные товары (одежда, обувь) и инвентарь. Для популяризации и продвижения своей продукции менеджмент решает, что необходимо освоить новые каналы для информирования покупателей о выходе новых товаров и стимулировать спрос на новые вещи. 

## Задание
Наша компания стремится предоставить каждому спортсмену — от профессиональных спортсменов и любителей бега и йоги до детей на детской площадке — возможность, продукцию и вдохновение для достижения спортивных целей, на которые каждый способен. У любого человека есть потенциал для великих свершений. Если у вас есть тело — вы спортсмен. 

Наше приложение должно стимулировать людей по всему миру соревноваться с собой и другими, повышая вовлечённость в здоровый образ жизни и повышая качество жизни. 

## Контекст, окружение
В компании уже разработаны приложения для покупки товаров, а также узкоспециализированные приложения для некоторых видов спорта. Компания имеет большой штат разработчиков, говорящих на различных языках, и охотно адаптирует новые технологии для экспериментальных приложений. 90% всех систем, используемых в компании, расположены у облачных провайдеров, при этом нет одного выбранного провайдера — используется то, что больше подходит под конкретную задачу. 

## Требования 


    1. Реализация социальных компонентов в приложении. Оно должно формировать социальные группы по интересам, которые будут самоподдерживаться и в которых участники будут общаться и влиять друг на друга. Одна из целей — формирование такого образа бренда в глазах участников, который позволит нашим товарам оставаться в фаворитах при выборе из прочих равных. 
    2. Предоставление информации о характеристиках тренировки, сравнение с прошлыми тренировками, сравнение с людьми в регионе, с профессиональными спортсменами. Основное сравнение — с самим собой для стимулирования результатов. 
    3. Возможность поиска людей по схожим интересам, поиск людей, которые тренируются в том же месте, имеют те же маршруты или которые тренируются прямо сейчас, для формирования групп для совместных занятий. 
    4. Возможность указания своего спортивного инвентаря (обувь, снаряды) для подсказок по составлению тренировок или своевременного обновления обуви. 
    5. Формирование и подсказки по составлению тренировок и их расписания. 
    6. Уведомление друзей о ваших новых успехах.
    7. Геймификация. 
    8. Внедрение промоакций и новостей спорта в зависимости от характера тренировок для вовлечённости.
    9. Возможность подключения сторонних устройств для отслеживания тренировок (датчик сердцебиения, кислорода и так далее). 
    10. Лёгкая интеграция существующих приложений компании для облегчения продаж. 
    11. Возможность вставки региональных промоакций.



## Особенности приложения, которые надо иметь в виду 
1. Пользователи по всему миру. Даже если в каком-то регионе нет нативных пользователей, туда может приехать группа, которая хочет потренироваться в «диких» местах. 
2. Возможное проведение соревнований с большим количеством участвующих.
3. Подключение дополнительных устройств, которые помогают следить за состоянием организма, для продвинутых спортсменов. 
4. Интеграция с фитнес-функциями телефона. 
5. Особое внимание охране пользовательских данных.
6. Не все требования могут быть одинаково важны и вообще необходимы.



## Требуемые артефакты 
1. Детализация и чёткое прописывание бизнес-целей. 
2. Анализ и список функциональных требований.
3. Анализ стейкхолдеров и их интересов.
4. Разработка концептуальной архитектуры.
5. Описание рисков реализации (бизнес и технические).
6. План поэтапной разработки и расширения системы, анализ критически важных компонентов. 
7. Выделение критических бизнес-сценариев.
8. Атрибуты качества (выделить основные, например: наблюдаемость и ).
9. Анализ и список нефункциональных требований.
10. Анализ и описание архитектурных опций и обоснование выбора. 
11. Список ADR. 
12. Описание сценариев использования приложения. 
13. Базовая архитектура с учётом ограничений бизнес-требований, НФТ, выбранной архитектуры, адресация атрибутов качества.
14. Основные представления: 
- a. Функциональное. 
- b. Информационное.
- c. Многозадачность (concurrency).
- d. Инфраструктурное.
- e. Безопасность. 
15. Анализ рисков созданной архитектуры, компромиссов.
16. Стоимость владения системой в первый, второй и пятый годы с учётом роста данных и базы пользователей. 

## Процесс приёмки архитектурного решения
Любая новая система проходит через три основные стадии согласования с архитектурным комитетом компании: 
1. Утверждение концепта архитектурного решения:
- a. Артефакты, необходимые для прохождения этого этапа, — 1–10.
- b. В пункте 5 описываются риски, видимые на начальном этапе. Впоследствии этот пункт должен дополняться и расширяться. 
- c. В пункте 6 требуется показать очерёдность реализации основных бизнес-требований и как это будет соотноситься с концептуальной схемой решения. 
2. Защита плана реализации:
- a. Артефакты, необходимые для прохождения этого этапа, — 11–14.
3. Анализ рисков реализации и стоимости содержания системы, защита всего проекта архитектуры и принятие окончательного решения по реализации: 
- a. Артефакты, необходимые для прохождения этого этапа, — 15 и 16.
- b. За основу следует принять результаты пункта 5 и рассмотреть, насколько они важны, трудозатраты на решение, последствия принятия рисков, вероятности наступления описанных рисков. 



 











