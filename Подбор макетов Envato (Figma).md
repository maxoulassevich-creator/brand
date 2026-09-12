# Шорт-лист Figma-макетов с Envato Elements для FOODBEER

Подбор макетов под интернет-каталог гастромаркета FOODBEER (Волгоград, ул. Комсомольская, 10, foodwine.store)
по ТЗ «Интернет-каталог на WordPress + WooCommerce», редакция 2.3.

**Интерактивная версия с кликабельными ссылками:** https://claude.ai/code/artifact/7b900b92-7def-47c9-ba43-eb5f0fa47abf

---

## Фирменные вводные (из репозитория)

Взято из `FOODBEER фирменный стиль/`:

| Параметр | Значение |
| --- | --- |
| Тёмно-зелёный | `#112A1D` |
| Терракота | `#DD5835` |
| Айвори | `#FFFEE9` |
| Шрифт заголовков | TT Wellingtons Medium |
| Шрифт основного набора | TT Tricks Regular |
| Символ | корова / барашек / бутылка, силуэтная графика |
| Паттерны | диагональная решётка с иконками (сыр, рыба, банка, скот) |

Логотип — ретро-гротеск с характерной буквенной пластикой. Это важно при выборе:
макеты, построенные на типографике, подхватят фирменный стиль лучше, чем макеты,
построенные на фотосетке.

Структура сайта — раздел 11 ТЗ, 19 страниц. Категории — п. 12.1: сыры, мясные деликатесы,
рыбные деликатесы, закуски и антипасти, десерты, чай/кофе/бакалея, безалкогольные напитки,
подарки и наборы, алкогольная витрина.

---

## Как проверялось — и чего проверить не удалось

Сессия работает в закрытом сетевом контуре: **прямой доступ к `elements.envato.com` заблокирован
политикой egress-прокси** (CONNECT → 403), открыть страницы товаров и посмотреть превью-картинки
было невозможно. Отсюда два уровня достоверности:

- **Подтверждено** — ссылка и точное название найдены в поисковом индексе Envato. Товар
  существует, лежит по этому адресу, формат Figma указан в названии карточки.
- **Оценочно** — описания «как выглядит» собраны из официальных текстов карточек Envato,
  а не из просмотра превью.

Всё, что не удалось подтвердить адресом, вынесено в отдельный раздел «Ищите по названию».
URL-ы не додумывались.

---

## Топ-6: самые «не как у всех»

Ранжировано по совокупности: заметная нестандартность вида + полнота структуры из ТЗ +
близость гастрономической темы.

### 01. LuxDin — Restaurant Website
https://elements.envato.com/restaurant-website-QS6J6TP

Премиальный ресторанный макет в сочетании **тёмного изумруда и тёмно-коричневого**,
заявлен как «luxury, classy, elegant» под fine dining.

*Почему первый:* единственная находка, где базовая палитра практически совпадает с фирменной —
тёмный зелёный как основа. Перекрашивать почти не придётся: достаточно ввести терракоту как
акцент и айвори как светлый фон. Тёмно-изумрудный фон сразу читается как «дорого и эксклюзивно»,
а не как «продуктовый магазин».

*Учтите:* ресторанный макет — готовых экранов корзины, чекаута и личного кабинета, скорее всего,
нет. Брать как источник визуального языка, недостающие экраны достраивать из № 05/06.

### 02. Eline — Wine Shop & Vineyard
https://elements.envato.com/eline-wine-shop-vineyard-figma-template-2S9KM92

Магазин вина и винодельня. Автор Th3s заявляет «изысканные цветовые сочетания» и подачу
как «чистого холста» под собственную айдентику.

*Почему второй:* винная эстетика — самый короткий путь к ощущению эксклюзива в еде, и она
напрямую ложится на «Алкогольную витрину» (п. 12.1). Жанр «vineyard» даёт готовые блоки под
сторителлинг: происхождение, регион, производитель — ровно те поля карточки товара из п. 12.2.

*Учтите:* заточен под вино, мясные и сырные категории придётся адаптировать.

### 03. O Brand — Ecommerce Figma Template
https://elements.envato.com/o-brand-ecommerce-figma-template-S92JN2W

В официальном описании отдельно подчёркнуто: «уникальная главная страница, построенная
на разных стилях и типографике».

*Почему третий:* редкая для Envato формулировка — обычно пишут «clean and modern». Здесь автор
продаёт именно типографическую подачу, а это то, что делает сайт «диковинным». Гарнитуры FOODBEER
характерные, логотип с ретро-гротескной пластикой — типографический макет подхватит это лучше
любого «органик-шопа».

*Учтите:* тема нейтральная, не еда. Фуд-контент полностью свой.

### 04. Vinoteca — Wine Shop Landing Page
https://elements.envato.com/vinoteca-wine-shop-landing-page-figma-PZYXZ2J

Винотека. Всё в векторе, слои названы и сгруппированы, pixel perfect — по описанию это аккуратно
собранный файл, а не «картинка в Figma».

*Почему четвёртый:* «винотека» как жанр ближе всего к формату гастромаркета — небольшой авторский
магазин с отобранным ассортиментом. Чистота файла критична: перекраска под фирменные цвета быстра
только если цвета заведены стилями.

*Учтите:* это landing page, а не полный набор экранов каталога.

### 05. Anvogue — Multipurpose eCommerce
https://elements.envato.com/anvogue-multipurpose-ecommerce-figma-template-L67G9SG

Большой многоцелевой e-commerce: списки товаров, карточка товара, корзина, чекаут, поиск,
фильтры, сортировка.

*Почему пятый:* это «скелет». Ни один винный лендинг не закроет 19 страниц раздела 11 ТЗ —
Anvogue закрывает большую часть. Главный практический бонус: есть HTML- и React/Next.js-версии
того же дизайна:
- HTML: https://elements.envato.com/anvogue-multipurpose-ecommerce-html-template-9SREDU5
- React/Next.js: https://elements.envato.com/anvogue-multipurpose-ecommerce-react-nextjs-SE5KKVU

Разработчику под WooCommerce это экономит недели — есть живая вёрстка, а не только статичный макет.

*Учтите:* по духу fashion-магазин, «чисто и профессионально» — безопасно, но не диковинно.
Структура отсюда, характер — из № 01–03.

### 06. Boskery — Butcher & Meat Shop
https://elements.envato.com/boskery-butcher-meat-shop-figma-template-VAQEML8

Мясная лавка: по описанию покрывает мясо, птицу, рыбу и морепродукты, стейк-хаус и овощи.

*Почему шестой:* из всех «мясных» макетов на Envato заявлен самым широким по ассортименту —
а в п. 12.1 ТЗ ровно такой разброс. Единственный кандидат, где готовая структура категорий
совпадает почти один в один.

*Учтите:* «мясная лавка» на Envato почти всегда = красно-чёрная гриль-эстетика. Под зелёно-терракотовую
палитру перекрашивать придётся всерьёз.

---

## Сильный второй эшелон

| Макет | Ссылка | Чем полезен |
| --- | --- | --- |
| Goodmeat — Meat Shop & Butcher | https://elements.envato.com/goodmeat-meat-shop-butcher-figma-template-RQTP8G2 | Мясная лавка и стейк-хаус. **Есть готовый Elementor Template Kit для WordPress:** https://elements.envato.com/goodmeat-meat-shop-butcher-elementor-template-kit-GYCJL4Z |
| OnkyKari — Butcher, Food Shop | https://elements.envato.com/onkykari-butcher-food-shop-figma-template-3L9P669 | Стейк и рыба в одном макете — под «Мясные» и «Рыбные деликатесы» сразу |
| Arg — Coffee Shop | https://elements.envato.com/arg-coffee-shop-figma-template-Q2MEQ6M | «Изысканные цветовые сочетания», тёплая крафтовая подача. Близко к зоне второго этажа (раздел 20) |
| Coffeera — Coffee Shop | https://elements.envato.com/coffeera-figma-coffee-shop-template-YYDEDHR | «Clean, modern & creative». Донор для «О гастромаркете» |
| EcoSen — Organic Store | https://elements.envato.com/ecosen-organic-store-ecommerce-figma-template-A29PKGP | Самый креативный в органик-сегменте. Земляная палитра, в которую `#112A1D` встаёт без боли |
| Torganic — Organic Grocery | https://elements.envato.com/torganic-organic-grocery-ecommerce-figma-temp-KYP4WZY | Полный набор магазинных экранов, теплее Anvogue |
| Modave — Multipurpose eCommerce | https://elements.envato.com/modave-multipurpose-ecommerce-figma-template-U6Y7PPK | Второй «скелет»: листинги, карточка, корзина, чекаут, фильтры |
| Handmade and Crafts Shop | https://elements.envato.com/handmade-and-crafts-shop-design-figma-template-6YVMPKM | Тёплая авторская подача — уход от «магазинности» в сторону «лавки с характером» |
| HandMade — Artisan & Handcraft | https://elements.envato.com/handmade-artisan-handcraft-and-handmade-figma-t-LYBMVVA | Подача «штучного товара» — тон для трюфельного сыра и хамона |
| Farmorice — Organic Farm UI Kit | https://elements.envato.com/farmorice-organic-farm-figma-ui-kit-H29PRMU | Земляные тона, farm-to-table. Блоки о происхождении и производителе |
| Wine Town — Wine Store Header | https://elements.envato.com/wine-town-wine-store-header-design-figma-UAMQGLQ | Только шапка и первый экран, но быстрые идеи для алкогольной витрины |
| Yourbeer — Website Template | https://elements.envato.com/yourbeer-website-template-252SNXF | Пивная тема, совместим с Figma. Перекличка с FOODBEER и вторым этажом |
| Sweeny — Cake & Icecream Store | https://elements.envato.com/sweeny-cake-icecream-store-figma-template-7UZQH2X | Категория «Десерты и сладости», подарочные наборы |
| Grecory — Resident Market & Grocery | https://elements.envato.com/grecory-resident-market-grocery-figma-template-NVF39SV | Shop, Product Detail, Cart, Checkout, Blog, Contact — почти раздел 11 ТЗ |
| Cabbage — Organic Food eCommerce | https://elements.envato.com/cabbage-organic-food-ecommerce-figma-template-HFXMDZN | Крепкий середняк, запасной вариант структуры |
| Halal Meat & Butcher Shop UI Kit v.2 | https://elements.envato.com/halal-meat-butcher-shop-website-ui-kit-v-2-PUUWP65 | Нишевый мясной UI-kit, «feature-rich» — много готовых компонентов |

---

## Доноры для отдельных страниц

Не как основа целиком, а как источник решений для конкретных экранов. Тема другая — берётся уровень подачи.

| Макет | Ссылка | Для чего |
| --- | --- | --- |
| Swarna — Jewelry Store | https://elements.envato.com/swarna-jewelry-store-figma-template-5GBAQBG | Эталон подачи дорогого штучного товара. Карточка товара, «Подарочные наборы» |
| Jewelry eCommerce Figma Template | https://elements.envato.com/jewelry-ecommerce-figma-template-YFGLKZU | Листинг и фильтры в премиум-сегменте |
| FoodHill — Restaurant Website | https://elements.envato.com/foodhill-restaurant-figma-website-template-74RSRP6 | Страница «Зона второго этажа» (раздел 20): атмосфера, фото, режим, правила |
| Dapur Resto — Restaurant Website UI | https://elements.envato.com/dapur-resto-restaurant-website-ui-for-figma-GXPSVLY | Заявлен с фуд-брендингом внутри — полезно при переносе готового фирстиля |
| Restaurant Cafe Website Template | https://elements.envato.com/restaurant-cafe-website-template-RHD5RQT | «О гастромаркете», «Контакты» |
| Foodera — Food Landing Page | https://elements.envato.com/foodera-figma-food-landing-page-template-RQ7RNEY | Страницы «Акции» и «Новинки» |
| Foodezza — Food Landing Page | https://elements.envato.com/foodezza-figma-food-landing-page-template-KLF9Y4S | То же, второй вариант того же автора |
| Gradify — Retro Landing Page | https://elements.envato.com/gradify-university-retro-landing-page-figma-2B2J5W9 | Тема (университет) не нужна, но это редкая **настоящая ретро-подача**: тёплая палитра, ностальгические шрифты, текстуры. Логотип FOODBEER ровно из этой оперы. Строго источник приёмов |
| Honey Template UI | https://elements.envato.com/honey-template-ui-figma-3XT9YEX | Монопродуктовая подача «одного благородного продукта» — приём под трюфельный сыр или хамон |

---

## Ищите по названию — адрес не подтверждён

Всплыли в описаниях категорий Envato, по названию выглядят уместно, но точную ссылку
подтвердить не удалось. Вбить название в поиск на Envato Elements.

| Название | Автор | Чем интересен |
| --- | --- | --- |
| Elatea — Artisan Tea Shop Website | lembotstudio_ | «Artisan» в названии — ремесленная лавка. Самый близкий по духу из ненайденных |
| BaCha — Organic Tea Store eCommerce | BZOTheme | Полноценный e-commerce на монопродукте |
| Luxfod — Luxury Food Restaurant Website | Sanstive | Люксовая еда. Прямой конкурент LuxDin за первое место |
| Vellure — Luxury Perfume Brand | creedcreatives | Парфюмерный люкс: эталон эксклюзивности в карточке товара |
| Neucafe — Restaurant & Food Website Design | Analogousstudio | Фуд-макет от студии — обычно выше уровень |
| Bold Streetwear Ecommerce Landing Page | Pitchlook | Крупная типографика и смелая сетка |
| Farmino — Organic Farm Template | — | «Local fresh market» — формат гастромаркета |

---

## Где смотреть самому

Готовые фильтры Envato Elements, уже отфильтровано по Figma:

- E-commerce · Figma — https://elements.envato.com/graphic-templates/websites/ecommerce/compatible-with-figma
- **Editorial · Figma** — https://elements.envato.com/graphic-templates/websites/editorial/compatible-with-figma (журнальные сетки, за креативом сюда)
- Luxury · Figma — https://elements.envato.com/graphic-templates/websites/luxury+website/compatible-with-figma
- Catalogue · Figma — https://elements.envato.com/graphic-templates/websites/catalogue/compatible-with-figma
- Product catalogue · Figma — https://elements.envato.com/graphic-templates/websites/product+catalogue/compatible-with-figma
- B2B · Figma — https://elements.envato.com/graphic-templates/websites/b2b/compatible-with-figma
- **Brutalism · Figma** — https://elements.envato.com/graphic-templates/brutalism/compatible-with-figma (самое небанальное на площадке)
- Neo brutalism — https://elements.envato.com/graphic-templates/neo+brutalism
- Cheese · Figma — https://elements.envato.com/graphic-templates/websites/cheese/compatible-with-figma
- Matcha · Figma — https://elements.envato.com/graphic-templates/websites/matcha/compatible-with-figma (здесь лежат Elatea и BaCha)
- Wine menu · Figma — https://elements.envato.com/graphic-templates/ux-and-ui-kits/wine+menu/compatible-with-figma
- Meat — https://elements.envato.com/web-templates/meat
- Restaurant · Figma — https://elements.envato.com/graphic-templates/websites/restaurant/compatible-with-figma (здесь лежит LuxDin)
- Farming · Figma — https://elements.envato.com/graphic-templates/websites/farming/compatible-with-figma

---

## Что проверить, открыв превью

Порядок важен — первые два пункта отсеивают больше всего.

1. **Сколько экранов внутри.** В разделе 11 ТЗ девятнадцать страниц. Лендинг из трёх экранов
   придётся достраивать почти целиком — знать это надо до покупки.
2. **Есть ли карточка товара и листинг категории.** Два самых трудоёмких экрана. Нет — значит
   макет идёт в «доноры», а не в основу.
3. **Заведены ли цветовые стили и компоненты.** Перекраска в `#112A1D` / `#DD5835` / `#FFFEE9`
   быстра только если цвета заведены стилями. Искать в описании: «color styles», «components»,
   «auto layout», «well organized layers».
4. **Есть ли мобильная версия.** П. 23.2 ТЗ требует корректной работы на смартфоне. Многие
   Figma-макеты на Envato — только десктоп.
5. **Выдержит ли макет замену фотографий.** В шаблонах идеальные фуд-фото. Если красота держится
   на снимках, а не на сетке и типографике, после замены фото макет рассыплется.
6. **Хватит ли места под поля из п. 12.2.** Состав, страна, регион, производитель, хранение,
   срок годности, вкусовое описание и сочетания — это много текста.
7. **Как отработает алкоголь без кнопки покупки.** По разделу 21 в публичном режиме у алкоголя
   нет кнопки «в корзину» — только информация и ссылка на вход для оптовика. Проверить, не
   разваливается ли карточка без главной кнопки.
