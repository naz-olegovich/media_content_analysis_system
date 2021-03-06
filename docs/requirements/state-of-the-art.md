# Anasis. Аналіз предметної області

## Вступ
Наша мета - створити інструмент Anasis для моніторингу та аналізу ЗМІ.  <em> Для чого це потрібно?</em>
<br>
Для економії Вашого часу та зусиль! Немає більше необхідності переглядати сотні статтей, постів та коментарів для того, щоб дізнатись думку соціуму про Ваш продукт, адже за Вас все зробить наша майбутня система!
<br>
<br>
В цьому документі коротко описані [основні визначення](#Основні-визначення), [необхідні інструменти](#Підходи-та-способи-вирішення-завдання) для роботи майбутньої системи та [порівняльна характиристика існуючих засобів](#Порівняльна-характеристика-існуючих-засобів-вирішення-завдання).

## Основні визначення

**[Мас-медіа](https://uk.wikipedia.org/wiki/%D0%97%D0%B0%D1%81%D0%BE%D0%B1%D0%B8_%D0%BC%D0%B0%D1%81%D0%BE%D0%B2%D0%BE%D1%97_%D1%96%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D1%96%D1%97)** — засоби передавання, зберігання та відтворення інформації, призначені для її донесення крізь просторові, часові чи інші перепони. Наприклад технічні засоби та канали комунікації, такі як радіо, телебачення, інтернет, поширення знімних носіїв інформації, що формують особливе середовище комунікації.

**[Соціальні медіа](https://uk.wikipedia.org/wiki/%D0%A1%D0%BE%D1%86%D1%96%D0%B0%D0%BB%D1%8C%D0%BD%D1%96_%D0%BC%D0%B5%D0%B4%D1%96%D0%B0)** — вид мас-медіа, ряд онлайнових технологій на, завдяки яким споживачі контенту через свої дописи стають його співавторами і можуть взаємодіяти, співпрацювати, спілкуватися, ділитися інформацією або брати участь у будь-якій інший соціальній активності із теоретично усіма іншими користувачами певного сервісу.

**[Цифрові медіа](https://uk.wikipedia.org/wiki/%D0%A6%D0%B8%D1%84%D1%80%D0%BE%D0%B2%D1%96_%D0%BC%D0%B5%D0%B4%D1%96%D0%B0)** — це будь-які носії, які закодовані в машиночитаючих форматах. Цифрові медіа можуть бути створені, переглянуті, поширені, змінені і збережені на цифрових електронних пристроях. Приклади цифрових медіа включають програмне забезпечення, цифрові зображення, цифрове відео, відеогру, веб-сторінки і вебсайти, в тому числі соціальні медіа, дані і бази даних, цифрові аудіо, як наприклад MP3 і електронні книги.

**[Broadcast media](https://www.openpr.com/wiki/broadcast-media)** — це ті, які здійснюють електронну передачу звуку і зображення, наприклад радіо і телебачення.

**[Контент-аналіз](https://uk.wikipedia.org/wiki/%D0%9A%D0%BE%D0%BD%D1%82%D0%B5%D0%BD%D1%82-%D0%B0%D0%BD%D0%B0%D0%BB%D1%96%D0%B7#:~:text=%D0%9A%D0%BE%D0%BD%D1%82%D0%B5%D0%BD%D1%82-%D0%B0%D0%BD%D0%B0%D0%BB%D1%96%D0%B7%20%E2%80%94%20%D1%8F%D0%BA%D1%96%D1%81%D0%BD%D0%BE-%D0%BA%D1%96%D0%BB%D1%8C%D0%BA%D1%96%D1%81%D0%BD%D0%B8%D0%B9,%D1%82%D0%B5%D0%BA%D1%81%D1%82%D1%83%20%D0%B7%20%D0%BF%D0%BE%D0%B4%D0%B0%D0%BB%D1%8C%D1%88%D0%BE%D1%8E%20%D1%96%D0%BD%D1%82%D0%B5%D1%80%D0%BF%D1%80%D0%B5%D1%82%D0%B0%D1%86%D1%96%D1%94%D1%8E%20%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%96%D0%B2)** — якісно-кількісний метод вивчення документів, який характеризується об'єктивністю висновків і строгістю процедури та полягає у квантифікаційній обробці тексту з подальшою інтерпретацією результатів.

**[Квантифікація](https://uk.wikipedia.org/wiki/%D0%9A%D0%B2%D0%B0%D0%BD%D1%82%D0%B8%D1%84%D1%96%D0%BA%D0%B0%D1%86%D1%96%D1%8F)** — кількісне вираження якісних ознак.

**Предметом контент-аналізу** можуть бути як проблеми соціальної дійсності, котрі висловлюються чи навпаки приховуються у документах, так і внутрішні закономірності самого об'єкта дослідження.

Виділяють два основних типи контент-аналізу: **кількісний і якісний**. Якщо кількісний аналіз націлений на виявлення частоти окремих тем, слів або символів, що містяться у тексті, то якісний аналіз пов'язаний з фіксуванням нетривіальних висловлювань, мовних інтонацій з розумінням цінності змісту повідомлення.

## Підходи та способи вирішення завдання

Для реалізації даного завдання нам необхідні пошукові рішення, за допомогою яких можливе завантаження публічного веб-контенту, статей, коментарів, публікацій та їхній подальший аналіз. Для моніторингу ЗМІ, в основому використовується social listening. Процес обробки великого обсягу текстового матеріалу займає багато часу, але якщо ми використовуємо інструмент social listening, це більше не є проблемою. З його  допомогою ми можемо створювати прості та змістовні аналізи з публічного доступних інтернет-даних . Для цього нам потрібний ряд новітніх методів та процесів таких які описані нижче.
<br>
<br>
**[Data mining](https://www.datasciencecentral.com/profiles/blogs/the-7-most-important-data-mining-techniques)** - процес напівавтоматичного аналізу великих баз даних з метою пошуку корисних фактів, який зазвичай поділяють на задачі класифікації, моделювання та прогнозування. Цікавим є те, що для цього процесу не є обов'язковою наявність новітніх технології машинного навчання, щоб застосовувати методи аналізу,так як є можливість виконати передовий інтелектуальний аналіз даних за допомогою відносно скромних систем баз даних і простих інструментів, які є майже у будь-якій компанії.
<br>
<br>
**[Text mining](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D0%BB%D0%BB%D0%B5%D0%BA%D1%82%D1%83%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9_%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7_%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%B0)** (Інтелектуальний аналіз текстів) - напрям в штучному інтелекті, метою якого є отримання інформації з колекцій текстових документів, грунтуючись на застосуванні ефективних в практичному плані методів машинного навчання і обробки природної мови. Строго кажучи, text mining - це окремий випадок data mining для текстової інформації. Різниця проявляється лише в кінцевих методах, а також в тому, що Text mining має справу зі сховищами і базами даних, а не електронними бібліотеками та корпусами текстів. Основною метою інтелектуального аналізу текстів є перетворення неструктурованих текстових даних в придатний для подальшої роботи набір структурованих даних в зручному для машинної обробки вигляді. Тобто, за допомогою методів text mining ми можемо витягувати потрібну інформацію з величезного масиву інформації.
<br>
<br>
**[Full Text Search](https://ru.wikipedia.org/wiki/%D0%9F%D0%BE%D0%BB%D0%BD%D0%BE%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9_%D0%BF%D0%BE%D0%B8%D1%81%D0%BA)** - автоматизований пошук документів, при якому пошук ведеться не по іменах документів, а по їх вмісту, всьому або істотної частини. 
Повнотекстовий пошук в базах даних є одним із затребуваних механізмів доступу до вмісту будь-якої сучасної інформаційної системи, які зберігають метаінформацію, а найчастіше, і самі документи, в базі даних. Сучасні веб-сайти, по суті, є  способом організації доступу до баз даних.
<br>
<br>
**[TensorFlow](https://uk.wikipedia.org/wiki/TensorFlow)** - відкрита програмна бібліотека для машинного навчання, розроблена компанією Google для вирішення завдань побудови і тренування нейронної мережі з метою автоматичного знаходження та класифікації образів, досягаючи якості людського сприйняття . Основний API для роботи з бібліотекою реалізований для Python.
<br>
<br>
**[Deep learning](https://uk.wikipedia.org/wiki/%D0%93%D0%BB%D0%B8%D0%B1%D0%B8%D0%BD%D0%BD%D0%B5_%D0%BD%D0%B0%D0%B2%D1%87%D0%B0%D0%BD%D0%BD%D1%8F)** - це галузь машинного навчання, що ґрунтується на наборі алгоритмів, які намагаються моделювати високорівневі абстракції в даних, застосовуючи глибинний граф із декількома обробними шарами, що побудовано з кількох лінійних або нелінійних перетворень.
<br>
<br>
**[Word2vec](https://code.google.com/archive/p/word2vec/)** - цей інструмент забезпечує ефективну реалізацію архітектур безперервного набору слів і скіп-грам для обчислення векторних уявлень слів. Ці уявлення можуть згодом використовуватися в багатьох додатках обробки природної мови і для подальших досліджень.
<br>
<br>
**[Elasticsearch](https://uk.wikipedia.org/wiki/Elasticsearch)** - пошуковий сервер, розроблений на базі Lucene. Надає розподілений, повнотекстовий пошуковий рушій з HTTP веб-інтерфейсом і підтримкою безсхемних JSON документів.Є найбільш популярним пошуковим рішенням, може використовуватись для індексування та пошуку будь-яких типів документів. Він надає масштабовний пошук, має пошук близький до реального часу і підтримку мультиарендності.
<br>
<br>
**[Sphinx](https://uk.wikipedia.org/wiki/Sphinx_(%D0%BF%D0%BE%D1%88%D1%83%D0%BA%D0%BE%D0%B2%D0%B0_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0))** - система повнотекстового пошуку. Відмінною особливістю є висока швидкість індексації та пошуку, а також інтеграція з існуючими СУБД (MySQL, PostgreSQL) та наявність API для поширених мов веб-програмування (офіційно підтримуються PHP, Python, Java.
<br>
<br>
**[ELK Stack](https://www.guru99.com/elk-stack-tutorial.html#:~:text=The%20ELK%20Stack%20is%20a,as%20processing%20and%20storing%20logs)** - являє собою набір з трьох продуктів з відкритим вихідним кодом - Elasticsearch, Logstash і Kibana. Всі вони розробляються, управляються і обслуговуються компанією Elastic. ELK Stack розроблений, щоб дозволити користувачам отримувати дані з будь-якого джерела в будь-якому форматі, а також шукати, аналізувати і візуалізувати ці дані в реальному часі.
<br>

![Діаграма роботи сервісу](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/naz-olegovich/media_content_analysis_system/master/src/uml/main_scene.plum)

<em>Шляхом поєднання цих технологій ми можемо досягнути нашої мети - розробити веб-сайт для професійнийного аналізу медіа контенту та забезпечити автоматичну обробку інформації.</em>

## Порівняльна характеристика існуючих засобів вирішення завдання

|Вимоги| Критерії | Semantrum | Neticle | YouScan |
|:----:| :--------------: | :----------: |  :----------: | :----------: |
| **Functionality (функциональність)** | Кількість тем моніторингу | 2-60 | 3-15 | 5-25 |
|  | Алерти (розсилки) про нові публікації, щоденні та щотижневі звіти | ✓ | ✓ | ✓ |
|  | Базовий аналіз публікацій | ✓ | ✕ | ✓ |
|  | Визначення тональності публікацій | ✓ | ✓ | ✓ |
|  | Експорт в Word/Excel/Pdf | ✓ | ✓ | ✕ |
|  | Наявність унікальних алгоритмів | ✓ | ✓ | ✓ |
|  | Тегування публікацій | 10-200 правил | ✕ | 5-100+ правил |
|  | Додавання нових користувачів | ✓ | ✓ | ✓ |
| **Usability (зручність роботи)** | Зручний онлайн-доступ | ✓ | ✓ | ✓ |
|  | Підтримка мобільних платформ | ✓ | ✓ | ✓ |
|  | Вартість користування | 2000-35000/міс | ? | 14500-217500/міс |
|  | Наявність Demo-версії | ✓ | ✓ | ✓ |
|  | Зручний інтерфейс | ✓ | ✕ | ✓ |
|  | Візуалізована аналітика | ✓ | ✓ | ✓ |
|  | Наявність FAQ/довідки | ✓ | ✕ | ✓ |
|  | Багатомовність | ✓ | ✓ | ✓ |
| **Reliability (надійність)** | Захист персональних даних | ✓ | ✓ | ✓ |
|  | Резервне копіювання | ✓ | ✓ | ✕ |
| **Performance (продуктивність)** | Своєчасне оновлення даних | ✓ | ✓ | ✓ |
|  | Інтервал вибірки даних  | Щодня | 10-30 хвилин | 1-5 хвилин |
| **Supportability (підтримка)** | Можливість зв’язку у соцмережах | ✓ | ✓ | ✓ |
|  | Зворотній зв’язок | ✓ | ✓ | ✓ |
|  | Допомога у роботі з програмою | ✕ | ✓ | ✓ |

## Висновки
Проаналізувавши існуючі засоби та ринок, можемо зробити висновок, що доцільніше буде взяти за основу існуючу систему та модифікувати її, прибравши всі її недоліки. 

## Посилання
[Засоби масової інформації](https://uk.wikipedia.org/wiki/%D0%97%D0%B0%D1%81%D0%BE%D0%B1%D0%B8_%D0%BC%D0%B0%D1%81%D0%BE%D0%B2%D0%BE%D1%97_%D1%96%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D1%96%D1%97)

[Соціальні медіа](https://uk.wikipedia.org/wiki/%D0%A1%D0%BE%D1%86%D1%96%D0%B0%D0%BB%D1%8C%D0%BD%D1%96_%D0%BC%D0%B5%D0%B4%D1%96%D0%B0)

[Цифрові медіа](https://uk.wikipedia.org/wiki/%D0%A6%D0%B8%D1%84%D1%80%D0%BE%D0%B2%D1%96_%D0%BC%D0%B5%D0%B4%D1%96%D0%B0)

[Broadcast media](https://www.openpr.com/wiki/broadcast-media)

[Контент-аналіз](https://uk.wikipedia.org/wiki/%D0%9A%D0%BE%D0%BD%D1%82%D0%B5%D0%BD%D1%82-%D0%B0%D0%BD%D0%B0%D0%BB%D1%96%D0%B7#:~:text=%D0%9A%D0%BE%D0%BD%D1%82%D0%B5%D0%BD%D1%82-%D0%B0%D0%BD%D0%B0%D0%BB%D1%96%D0%B7%20%E2%80%94%20%D1%8F%D0%BA%D1%96%D1%81%D0%BD%D0%BE-%D0%BA%D1%96%D0%BB%D1%8C%D0%BA%D1%96%D1%81%D0%BD%D0%B8%D0%B9,%D1%82%D0%B5%D0%BA%D1%81%D1%82%D1%83%20%D0%B7%20%D0%BF%D0%BE%D0%B4%D0%B0%D0%BB%D1%8C%D1%88%D0%BE%D1%8E%20%D1%96%D0%BD%D1%82%D0%B5%D1%80%D0%BF%D1%80%D0%B5%D1%82%D0%B0%D1%86%D1%96%D1%94%D1%8E%20%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%96%D0%B2)

[Text mining](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D0%BB%D0%BB%D0%B5%D0%BA%D1%82%D1%83%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9_%D0%B0%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7_%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%B0)

[Data mining](https://www.datasciencecentral.com/profiles/blogs/the-7-most-important-data-mining-techniques)

[Full Text Search](https://ru.wikipedia.org/wiki/%D0%9F%D0%BE%D0%BB%D0%BD%D0%BE%D1%82%D0%B5%D0%BA%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B9_%D0%BF%D0%BE%D0%B8%D1%81%D0%BA)

[TensorFlow](https://uk.wikipedia.org/wiki/TensorFlow)

[Deep learning](https://uk.wikipedia.org/wiki/%D0%93%D0%BB%D0%B8%D0%B1%D0%B8%D0%BD%D0%BD%D0%B5_%D0%BD%D0%B0%D0%B2%D1%87%D0%B0%D0%BD%D0%BD%D1%8F)

[Word2vec](https://code.google.com/archive/p/word2vec/)

[Elasticsearch](https://uk.wikipedia.org/wiki/Elasticsearch)

[Sphinx](https://uk.wikipedia.org/wiki/Sphinx_(%D0%BF%D0%BE%D1%88%D1%83%D0%BA%D0%BE%D0%B2%D0%B0_%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0))

[ELK Stack](https://www.guru99.com/elk-stack-tutorial.html#:~:text=The%20ELK%20Stack%20is%20a,as%20processing%20and%20storing%20logs)
