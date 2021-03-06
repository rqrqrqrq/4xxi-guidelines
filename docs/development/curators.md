# Кураторы

Каждый из нас когда-то был новичком, и, наверное, помнит, как было тяжело разобраться и запомнить весь объем поступающей новой информации.

Куратор — это прежде всего наставник со всеми вытекающими: необходимостью присматривать за работой подопечных, направлять в правильное русло, предостерегать от ошибок, помогать исправлять найденные "шероховатости".
Куратор является эталоном, который обучает подопечного правильной работе, принятым в компании стандартам и следит, чтобы он в процессе ничего не сломал.

## TLDR
- Code Review + Code Style
- Элементы обучения и помощь в развитии
- Git Flow + правила именования коммитов
- Контроль выбора технологий, компонентов и бандлов на проекте подопечного
- Ретроспективы: необходимо быть в курсе дел и эмоционального состояния подопечного
- Помощь с настройкой проекта: CI/CD, системы бэкапов, тесты
- Всегда быть готовым дать развернутый фидбэк о подопечном

## Зона ответственности куратора
- Code Review. Ни коммита без пулл реквеста!
  Наиболее общее правило: количество новых "шероховатостей" должно НЕ увеличиваться с каждым ПРом. Энтропия всегда стремится свести код в хаос, кураторы же должны стараться привести его к порядку.
  Качество пропускаемого кода зависит от срочности задачи, от проекта, от его стадии (разработка, предрелиз или релиз) и должно балансироваться дотошностью проверки. Даже если пропущен код с "шероховатостями", важно проследить, что ПМ поставит задачу на восстановление гармонии (рефакторинг).
- Обучение правильным подходам и инструментам.
  Если вы видите, что подопечный имеет белые пятна в определенных темах, расскажите ему о них. Дайте советы, что и где почитать, а еще лучше — расскажите. Предложите подопечному провести семинар по проблемной теме на компанию (@mk/@et организуют).
- Следить за соблюдением принципов Git Flow, правил код стайла и именования коммитов, пулл реквестов, веток и т.п. Не стоит забывать про теорию разбитого окна: беспорядок в мелочах дает право на еще больший беспорядок.
- Контроль выбора правильной технологии, бандла, любого другого технического решения. Например, деплой-инструмента. Неправильно выбранные технологии — косяк куратора.
- Обучение правильному общению внутри команды.
  Например, если есть задача, требующая участия нескольких людей, нужно показать, как наладить контакт, с кем, в какой последовательности и т.п. Что вопросы/жалобы/предложения по проекту — к ПМу, вопросы по коду, архитектуре, технологиям — к куратору, по офису — к офис-менеджерам.
- Коммуникация, или куратор = психиатр.
  Важно спрашивать о проблемах и помогать с ними. Рекомендуется проводить мини-ретроспективу каждые неделю-две с подведением итогов по наиболее хорошим и плохим моментам (только периодическое повторение приводит к запоминанию). Можно рассмотреть вариант с саморефлексией, вместо созвонов, когда разработчик сам пишет по истечению какого-то срока свои ошибки и успехи.
- Фидбэк о подопечных.
  Это итог предыдущего пункта. В компании уже налажена система фидбэков для новичков, а также планируется введение 360 review, поэтому нужно отслеживать динамику развития подопечных и быть готовым дать общую оценку по каждому из них, качеству кода и т.п.
- Куратор ≠ ПМ, но увидел непорядок на проекте — почини или хотя бы сообщи (ПМу). Куратор должен относиться к проекту подопечного, как к своему.
- Помогать со стандартизацией рабочих процессов.
  К сожалению, в компании не все еще стандартизировано. При работе с подопечными вам неизбежно будут задавать одни и те же вопросы, встречаться одни и те же проблемы. Хорошо запоминать такие ситуации и доносить до СТО, чтобы были выработаны общие практики, которые позволят в будущем не тратить много времени на микро-менеджмент.
- Кураторские созвоны раз в две недели (временно приостановлены).
  Для получения фидбэка о кураторстве, рассказа о проблемных местах, предложения стандартизации процесса. В общем, для обмена опытом.
- Если вы не можете решить какой-то вопрос, то обращайтесь с ним к СТО. Важно сообщить не только о проблеме, но и предложить варианты решения.

Ответственный за документ: @mk / @et
