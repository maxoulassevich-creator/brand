# Шорт-лист Figma-макетов с Envato Elements для FOODBEER

Редакция 2 — **после просмотра превью**. Первая редакция собиралась вслепую: сеть не пускала
на Envato, и оценки «как выглядит» брались из описаний карточек. Теперь превью просмотрены,
и рейтинг пересобран по фактическому виду. Часть прежнего топа вылетела.

Подбор под интернет-каталог гастромаркета FOODBEER (Волгоград, ул. Комсомольская, 10,
foodwine.store) по ТЗ «Интернет-каталог на WordPress + WooCommerce», редакция 2.3.

**Интерактивная версия с превью-картинками:** https://claude.ai/code/artifact/7b900b92-7def-47c9-ba43-eb5f0fa47abf

---

## Что изменилось после просмотра

| Макет | Было | Стало | Почему |
| --- | --- | --- | --- |
| LuxDin | 1 место | **4 место, остаётся в топе** | Подтвердилось: тёмно-зелёный + айвори + золото, 12 экранов, есть квази-карточка товара и листинг с фильтрами. Но держится на тёмной фуд-фотографии |
| Eline | 2 место | **вон** | Тёмно-сливовый винный лендинг, банальный. «Изысканные цветовые сочетания» — маркетинговый текст |
| O Brand | 3 место | **вон** | Пастельный fashion-магазин. Обещанной «уникальной типографики» в макете нет |
| Vinoteca | 4 место | **вон** | Красно-чёрный лендинг на Bebas Neue. Выглядит дёшево |
| Anvogue | 5 место | **скелет, не топ** | Подтвердилось: 85+ страниц, всё есть. Но это типовой маркетплейс, характера ноль |
| Boskery | 6 место | **вон** | Красно-чёрная мясная лавка со стоковыми мясниками, вёрстка уровня 2015 |
| Goodmeat | 2-й эшелон | **вон** | То же самое: тёмный + красный стейкхаус с гербом |
| EcoSen | 2-й эшелон | **донор карточки товара** | Ярко-зелёный супермаркет — визуально вон. Но карточка с «Product Specifications», табами и отзывами закрывает п. 12.2 лучше всех |
| Grecory | 2-й эшелон | **вон** | Это **мобильное приложение**, а не сайт. В первой редакции описано ошибочно |
| Yourbeer | 2-й эшелон, «пивная тема» | **донор, вверх** | Оказался светлым редакционным макетом с крупной типографикой — под пиво и второй этаж годится |
| Luxfod | «ищите по названию» | **адрес подтверждён** | https://elements.envato.com/luxfod-luxury-food-restaurant-website-JXY58EL |
| Elatea, BaCha | «ищите по названию» | **не найдены** | В разделе Matcha · Figma их сейчас нет. Не выдумываю |
| — | — | **+ Aurelle Atelier, Valente, Knead, Savoria, Aurelian** | Новые находки, три из них выше прежнего топа |

---

## Как смотрели

Прямой `curl` на `elements.envato.com` упирается в Cloudflare-челлендж (403). Страницы товаров
читались через веб-фетч, превью скачивались с CDN Envato по подписанным ссылкам и собирались
в контактные листы, которые уже можно смотреть глазами. Просмотрено около 60 макетов.

Два уровня достоверности — они разные, и это важно:

- **Видел галерею превью** — у товара на Envato есть отдельные превью-картинки (632 px):
  LuxDin, Anvogue, EcoSen, Boskery, O Brand, Vinoteca, Savoria, Cheese Brand, Aurelle Atelier,
  Knead, Yourbeer, Swarna, Handmade & Crafts.
- **Видел только обложку** — у части товаров галереи нет вообще, есть одна обложка 433 px,
  на которой автор коллажем выложил несколько экранов: Valente, Aurelian, Elegencia, SavorLuxe,
  Luxfod, Savora, Modave, Dapur Resto и др. Общий характер по ней виден, мелкие детали — нет.

Количество экранов везде взято из описания автора, а не пересчитано по превью.

---

## Критерий, который вылез при просмотре

Фирменный стиль FOODBEER — **светлый**: айвори-фон, тёмно-зелёные формы, терракота акцентом,
ретро-гротеск с характерной буквенной пластикой, силуэтные иконки (сыр, корова, банка, бутылка)
на диагональной решётке, ироничный дескриптор «от Нанта до Киото».

Это регистр **типографический и графический**, а не «тёмный ресторан с макросъёмкой стейка».
На Envato весь премиум-фуд сегмент — это второе: чёрно-коричневый фон, золотой акцент,
курсивная антиква, дорогая фотография. Такие макеты выглядят солидно, но фирменный стиль
на них ложится плохо: логотип FOODBEER на тёмном фото теряет всю свою пластику.

Отсюда пересборка: **светлые макеты на айвори с крупной типографикой поднялись,
тёмные фуд-фотографические опустились, красно-чёрные мясные вылетели**.

---

## Топ-6

### 01. Aurelle Atelier — Fine Jewelry Ecommerce
https://elements.envato.com/aurelle-atelier-fine-jewelry-ecommerce-website-8Q3G7BT
Автор Pitchlook · видел галерею превью

Ювелирный магазин, но смотреть надо не на тему, а на дизайн-систему. В превью автор выложил
палитру токенами, и там буквально: `ivory #F9F4EA`, `emerald #123D36`, `blush #DBA08D`,
`ink #1D1A17`, `line #E4D7C5`. Изумруд `#123D36` против фирменного `#112A1D` — соседние оттенки;
айвори и «blush» — фактически ваши айвори и приглушённая терракота.

*Почему первый:* это единственный из всех просмотренных макетов, где **фирменная палитра уже
заложена как система токенов**, а не набита по слоям. Перекраска в `#112A1D / #DD5835 / #FFFEE9` —
это правка трёх значений, а не неделя работы (п. 3 чек-листа). Плюс заявлены сетка 1440,
64 px колонок, ритм секций 78–82 px, радиус карточек 22–30 px, auto layout, светлые и тёмные
секции. И главный приём: **«Browse by occasion instead of repeating a plain product grid»** —
подборки вместо сетки товаров. Для гастромаркета это готовый ответ на «Подарки и наборы»
и на «с чем сочетается» из п. 12.2.

*Учтите:* тема — ювелирка, весь фуд-контент ваш. Это лендинг + UI-kit, а не 19 страниц:
структуру достраивать из скелета.

### 02. Valente — Wine Shop & Vineyard Website
https://elements.envato.com/valente-wine-shop-vineyard-website-GTKKF2J
Автор onelinerdesign · видел только обложку

Кремовый фон, огромный узкий гротеск «WINES», бутылки заходят на буквы, карточки в редакционной
сетке, блоки «THE CONTROGUERRA REGION», «DISCOVER THE ESSENCE OF OUR CRAFT», рейтинг 4.9/5.

*Почему второй:* из всего винного сегмента Envato это единственный макет, который держится
на типографике, а не на фотографии бутылки в темноте. Крупный шрифт на айвори — ровно то, как
устроен логотип FOODBEER. Плюс жанр «vineyard» даёт готовые блоки под регион, производителя
и происхождение — поля из п. 12.2.

*Учтите:* количество экранов автор не указал, судя по всему один длинный лендинг. И оценка
сделана по обложке — детали карточек не проверены. Смотреть первым делом.

### 03. Knead — Bread eCommerce Store
https://elements.envato.com/knead-bread-ecommerce-store-R6X9P6G
Автор sansdesign · видел галерею превью

Ремесленная пекарня: кремовый фон, крупное строчное «knead» + курсивное «breads», строка
категорий (sourdough, croissant, pain au chocolat, seasonal pastries, daily breads), корзина
в шапке, «artisan best seller», фраза «Not all breads belongs in a plastic bag».

*Почему третий:* это единственный просмотренный **светлый ремесленный фуд-магазин** —
не супермаркет и не ресторан, а именно лавка с отобранным ассортиментом. Тон голоса совпадает
с «от Нанта до Киото». Строка категорий сверху — готовое решение под 9 категорий п. 12.1.

*Учтите:* один лендинг. Тема хлеб, но приёмы переносятся на сыр и хамон один в один.

### 04. LuxDin — Restaurant Website
https://elements.envato.com/restaurant-website-QS6J6TP
Автор peterdraw · видел галерею превью

Подтвердилось: тёмно-зелёный + айвори + золотой акцент, курсивная антиква, арочные маски.
12 экранов: главная в трёх версиях, About, Menu, Menu Details, Services, Team, Reservation,
Blog, Blog Details, Contact.

*Почему четвёртый, а не первый:* палитра действительно почти фирменная, и структура лучшая
среди «характерных» — **Menu Details фактически работает как карточка товара** (цена, счётчик,
кнопка, блок Related), а «Popular Delights» — как листинг категории с фильтрами. Но макет
целиком держится на тёмной ресторанной фотографии: замените снимки на свои — и половина
эффекта уйдёт (п. 5 чек-листа). Мобильных экранов нет.

### 05. Savoria — Fine Dining & Upscale Restaurant UI Kit
https://elements.envato.com/savoria-fine-dining-and-upscale-restaurant-ui-kit-N4556UD
Автор CreateBigSupply · видел галерею превью

Тёмно-коричневый с тёплым оранжевым акцентом (близко к терракоте), сдержанная антиква.
Ключевой экран — **«À La Carte & Tasting Menu»**: две колонки позиций с ценами, вкладки
по разделам (Starters, Main Courses, Fromages, Desserts), под каждой позицией короткое описание.

*Почему в топе:* это готовый макет **витрины без кнопки покупки** — ровно то, чего требует
раздел 21 ТЗ для алкоголя в публичном режиме: информация, цена, описание и никакого
«в корзину». Меню ресторана и каталог без корзины устроены одинаково.

*Учтите:* один лендинг. Брать как донор конкретного экрана, а не как основу.

### 06. Aurelian — Whisky Distillery Website
https://elements.envato.com/aurelian-whisky-distillery-website-GFYGY5L
Автор Sanstive · видел только обложку

Тёмный фон, оранжевый акцент, крупная типографика: «Crafted for Those Who Appreciate Timeless
Whisky», «A Legacy Distilled Since 1982», блоки про производство и людей. В тегах автора —
Typographic, Minimal, Ecommerce.

*Почему в топе:* лучший из просмотренных макет под **алкогольную витрину** (п. 12.1) —
крепкий алкоголь подан через историю производителя, а не через полку с бутылками.
Тёмный + оранжевый переводится в тёмно-зелёный + терракоту без потерь.

*Учтите:* обложка, деталей не видел. Количество экранов не указано.

---

## Скелеты: откуда брать структуру 19 страниц

Красивый лендинг не закроет раздел 11 ТЗ. Структуру берём отсюда, характер — из топа.

| Макет | Ссылка | Что внутри |
| --- | --- | --- |
| **Modave — Multipurpose eCommerce** | https://elements.envato.com/modave-multipurpose-ecommerce-figma-template-U6Y7PPK | 33+ демо, 140+ страниц. Листинги, карточка, корзина, чекаут, фильтры. Самый объёмный |
| **Anvogue — Multipurpose eCommerce** | https://elements.envato.com/anvogue-multipurpose-ecommerce-figma-template-L67G9SG | 20+ демо, 85+ страниц, есть grocery-демо. Главный плюс — тот же дизайн есть готовой вёрсткой: [HTML](https://elements.envato.com/anvogue-multipurpose-ecommerce-html-template-9SREDU5) и [React/Next.js](https://elements.envato.com/anvogue-multipurpose-ecommerce-react-nextjs-SE5KKVU). Разработчику под WooCommerce это экономит недели |
| **EcoSen — Organic Store** | https://elements.envato.com/ecosen-organic-store-ecommerce-figma-template-A29PKGP | Визуально не брать. Брать один экран: карточка товара с блоком «Product Specifications» (вес, происхождение, срок), табами «Описание / Отзывы» и листингом с сайдбар-фильтрами. Это прямое попадание в п. 12.2 |

---

## Доноры для отдельных экранов

| Макет | Ссылка | Для чего |
| --- | --- | --- |
| Cheese Brand Website Landing Page | https://elements.envato.com/cheese-brand-website-landing-page-T223H5X | Коралловый + кремовый, скриптовые акценты, карточки «Soft / Hard / Fresh Cheese». Прямо под категорию «Сыры» |
| Cheese Landing Page | https://elements.envato.com/cheese-landing-page-MEBZHDL | Второй вариант сырной страницы, горчичная палитра |
| Yourbeer | https://elements.envato.com/yourbeer-website-template-252SNXF | Светлая редакционная подача пива: гигантское «BEER», карточки наборов, отзывы, «FIND US». Под пиво (1000+ сортов) и зону второго этажа |
| Swarna — Jewelry Store | https://elements.envato.com/swarna-jewelry-store-figma-template-5GBAQBG | Бежево-коричневая ювелирка, 18 макетов, есть листинг и чекаут. Эталон подачи штучного дорогого товара |
| High Quality Cow — Vintage Web Illustration | https://elements.envato.com/high-quality-cow-vintage-web-illustration-XSHVPDJ | Ретро-иллюстрация со скотом на текстурном кремовом фоне. Не макет, а приём — ближайшая к логотипу FOODBEER графика на всей площадке |
| Wine Town — Wine Store Header | https://elements.envato.com/wine-town-wine-store-header-design-figma-UAMQGLQ | Минималистичная шапка на айвори, «LET THE DRINKS COME TO YOU». Один экран, но точно в тон |
| Arg — Coffee Shop | https://elements.envato.com/arg-coffee-shop-figma-template-Q2MEQ6M | Кремовая крафтовая подача с упаковкой. Под «Чай, кофе, бакалею» |
| Japanese Matcha Ecommerce Landing | https://elements.envato.com/japanese-matcha-ecommerce-landing-page-H5A8X59 | Чайный e-commerce, карточки сортов, «The Ritual of Serenity». Под чайную полку |
| Dapur Resto — Restaurant Website UI | https://elements.envato.com/dapur-resto-restaurant-website-ui-for-figma-GXPSVLY | 14 страниц, светлая палитра, антиква + скрипт. Под «О гастромаркете» и зону второго этажа |
| SavorLuxe / Elegencia / Savora / Luxfod | [SavorLuxe](https://elements.envato.com/savorluxe-luxury-restaurant-website-H2ZCEQJ) · [Elegencia](https://elements.envato.com/elegencia-restaurant-figma-template-GV9XQRW) · [Savora](https://elements.envato.com/savora-food-hospitality-website-figma-CCJ5FLF) · [Luxfod](https://elements.envato.com/luxfod-luxury-food-restaurant-website-JXY58EL) | Тёмный fine-dining кластер. Между собой почти взаимозаменяемы. Смотреть, если захочется тёмного варианта: у Elegencia 15+ страниц, у Savora 10 |

---

## Вычеркнуто и почему

| Макет | Почему |
| --- | --- |
| O Brand | Пастельный fashion-магазин, розово-мятные баннеры. Обещанной типографики нет |
| Vinoteca | Красно-чёрный лендинг на Bebas Neue, эстетика энергетика |
| Boskery | Мясная лавка: красно-чёрный, стоковые мясники, устаревшая вёрстка |
| Goodmeat / Proteina / OnkyKari | То же семейство: тёмный + красный стейкхаус |
| Eline | Тёмно-сливовый винный лендинг без идеи |
| Handmade & Crafts, HandMade Artisan | Бирюзово-белый и оранжевый типовые магазины со стоковыми фото |
| Grecory | **Это мобильное приложение**, не сайт |
| Torganic, Cabbage, Grocex, BigBasket, TazZA, OrgaFresh | Типовые зелёные гроцери с вырезанными овощами |
| Farmorice, Herbit, Brøøth, Highland, Stars Embra | Слабо: фотосток и стандартные сетки |
| Sweeny | Розовая кондитерская для детского сегмента |
| Halal Meat UI Kit | Коралловый, устаревший |
| FoodHill, Foodera, Foodezza, Restaurant Cafe, Coffeera | Фотосток и маджента, ничего своего |
| Gradify | Ретро настоящее, но студенческое (лайм, стикеры, поляроиды). Только как источник приёмов, не в список |
| Honey | Тёплая монопродуктовая подача, но слабее Knead в той же роли |
| Jewelry eCommerce (YFGLKZU) | Полностью перекрыт Aurelle Atelier и Swarna |

---

## Где смотреть самому

Фильтры Envato, уже с `compatible-with-figma`. Первые четыре дали основной улов.

- **Cheese** — https://elements.envato.com/graphic-templates/websites/cheese/compatible-with-figma
- **Gourmet** — https://elements.envato.com/graphic-templates/websites/gourmet/compatible-with-figma
- **Delicatessen** — https://elements.envato.com/graphic-templates/websites/delicatessen/compatible-with-figma
- **Wine shop** — https://elements.envato.com/graphic-templates/websites/wine+shop/compatible-with-figma
- Luxury website — https://elements.envato.com/graphic-templates/websites/luxury+website/compatible-with-figma
- Wine — https://elements.envato.com/graphic-templates/websites/wine/compatible-with-figma
- Matcha — https://elements.envato.com/graphic-templates/websites/matcha/compatible-with-figma
- E-commerce — https://elements.envato.com/graphic-templates/websites/ecommerce/compatible-with-figma
- Catalogue — https://elements.envato.com/graphic-templates/websites/catalogue/compatible-with-figma
- B2B — https://elements.envato.com/graphic-templates/websites/b2b/compatible-with-figma
- Brutalism — https://elements.envato.com/graphic-templates/brutalism/compatible-with-figma
- Restaurant — https://elements.envato.com/graphic-templates/websites/restaurant/compatible-with-figma
- Farming — https://elements.envato.com/graphic-templates/websites/farming/compatible-with-figma

Тег **Editorial** проверен и оказался пустым: там админки, SaaS и портфолио, фуда нет.

---

## Чек-лист проверки макета

Порядок важен — первые два пункта отсеивают больше всего.

1. **Сколько экранов внутри.** В разделе 11 ТЗ девятнадцать страниц. У большинства красивых
   макетов внутри один лендинг — это нормально, но знать надо до скачивания.
2. **Есть ли карточка товара и листинг категории.** Два самых трудоёмких экрана. Нет —
   значит донор, а не основа.
3. **Заведены ли цветовые стили и компоненты.** Перекраска в `#112A1D / #DD5835 / #FFFEE9`
   быстра, только если цвета заведены стилями. Искать: «color styles», «design system»,
   «components», «auto layout», «well organized layers». У Aurelle Atelier это показано в превью.
4. **Есть ли мобильная версия.** П. 23.2 ТЗ. Почти все просмотренные Figma-макеты — только десктоп.
   Мобильные экраны заявлены у Modave, Anvogue и Grecory (последний — приложение).
5. **Выдержит ли макет замену фотографий.** Проверено на LuxDin: красота держится на тёмной
   ресторанной съёмке. Светлые типографические макеты (Valente, Knead, Aurelle) этим не болеют.
6. **Хватит ли места под поля п. 12.2.** Состав, страна, регион, производитель, хранение,
   срок годности, вкусовое описание и сочетания. Из просмотренного это вмещает только карточка EcoSen.
7. **Как отработает алкоголь без кнопки покупки.** Раздел 21. Готовый ответ — экран меню
   из Savoria: цена и описание есть, кнопки нет.

---

## Что осталось непроверенным

- **Valente, Aurelian, Elegencia, SavorLuxe, Luxfod, Savora, Modave, Dapur Resto** — у этих
  товаров на Envato нет галереи превью, только обложка 433 px. Общий вид ясен, внутренние
  экраны — нет. Перед скачиванием открыть страницу и посмотреть в полном размере.
- **Elatea, BaCha, Vellure, Neucafe, Farmino** из первой редакции — по тегам сейчас не находятся.
  Возможно, сняты с публикации или переименованы.
- Число экранов у Valente и Aurelian авторы не указали вовсе.
- Ни один макет не скачан: лицензия Envato Elements требует подписки, её у нас нет.
