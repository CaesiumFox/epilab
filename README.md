# ЭПИ Лаб 1

https://coolors.co

## Возможности сайта

- [x] Регистрация и вход
  - [x] по почте и паролю
  - [x] через аккаунт Google или Apple
- [x] Оформление платной подписки
  - [x] ежемесячные списания платы
- [ ] Инструменты
  - [x] Подбор цвета (Color picker)
    - [x] Picker (квадрат и полоска)
    - [x] HSB
    - [x] HSL
    - [x] RGB
    - [x] CMYK
    - [x] Lab
    - [x] по имени в базе данных сайта
    - [x] выбор среди сохранённых цветов
    - [x] плашечные цвета (премиум)
      - [x] RAL
      - [x] HKS
      - [x] Copic
      - [x] Prismacolor
  - [x] Редактор цветов (Color picker)
    - [x] Подбор цвета (описано выше)
    - [x] Перевод в цветовые модели:
      - [x] HEX
      - [x] RGB
      - [x] CMYK
      - [x] HSB
      - [x] HSL
      - [x] Lab
      - [x] XYZ
      - [x] LCH
      - [x] LUV
      - [x] HWB
    - [x] Демонстрация смежных цветов в виде градиента:
      - [x] Shades
      - [x] Tints
      - [x] Tones
      - [x] Hues
      - [x] Temperatures
    - [x] Гармоники:
      - [x] Analogous
      - [x] Complementary
      - [x] Split complementary
      - [x] Triadic
      - [x] Tetradic
      - [x] Square
    - [x] Симулятор дальтонизма (преобразование цвета и сравнение с изначалным)
      - [x] Protanopia
      - [x] Protanomaly
      - [x] Deuteranopia
      - [x] Deuteranomaly
      - [x] Tritanopia
      - [x] Tritanomaly
      - [x] Achromatopsia
      - [x] Achromatomaly
    - [x] Проверка контраста
      - [x] На белом фоне
      - [x] На чёрном фоне
    - [x] Поиск соответствий среди плашечных цветов (и сравнение):
      - [x] по собственной базе данных
      - [x] RAL
      - [x] HKS
      - [x] Copic
      - [x] Prismacolor
    - [x] Список сохранённых палитр, которые содержат этот цвет
  - [x] Генерировать палитры (Generate your palettes)
    - [x] удаление и добавление слотов для цветов
    - [x] случайная генерация нескольких цветов, сочетающихся друг с другом
    - [x] возможность изменеиня цветов в палитре
    - [x] возможность блокировки цветов
    - [x] возможность сохранения цветов в понравившиеся
    - [x] отображение в виде HEX
    - [x] название близкого цвета из базы данных
    - [x] перемещение панелей с цветами на другие места
    - [x] Для обычных пользователей: до 5 цветов
    - [x] Для премиум пользователей: больше 5 цветов
  - [ ] Сохранать палитры на аккаунт
  - [x] Смотреть сохранённые палитры по популярности и текущим трендам (Explore popular palettes)
  - [ ] Извлекать палитру из изображения (Extract palette from image)
  - [ ] Подбирать контрастные цвета для текста и фона (Contrast checker)
  - [x] Предпросмотр палитры на макете (Preview palette on designs)
  - [x] Менять цвета на векторных изображениях (Change image colors)
  - [ ] Подборка бесплатных шрифтов (Browse free fonts)
- [ ] More
  - [x] Библиотека цветов (List of colors)
  - [ ] Просмотр градиентов (Browse gradients)
  - [x] Создание градиентов (Create a gradient)
    - [x] установка нескольких направляющих точек на оси
      - [x] через перетаскивание
      - [x] через поле ввода
    - [x] усановка цветя для управляющей точки
      - [x] использование инструмента для подбора цвета
    - [x] переключение между линейным и радиальным градиентом
    - [x] рандомизация
    - [x] сохранение (для премиум пользователей)
    - [x] экспорт в CSS
    - [x] просмотр в полный экран
    - [x] переход в генератор палитр
    - [x] загрузка градиента как изображения
  - [ ] Создание градиентных палитр (Make a gradient palette)
    - [ ] установка первого цвета
    - [ ] установка второго цвета
    - [ ] установка количества цветов (от 2 до 30)
    - [ ] рандомизация
    - [ ] переход в обычный редактор палитр
    - [ ] переход в редактор градиентов
  - [ ] Image converter
  - [ ] Create a collage
  - [ ] Font Generator
  - [ ] Find your next jobs
  - [ ] Post a job
  - [x] App download
    - [x] iOS
    - [x] Android
    - [x] Figma
    - [x] Adobe
    - [x] Chrome
  - [x] Document view:
    - [x] Pricing
    - [x] License
    - [x] Terms of service
    - [x] Privacy policy
    - [x] Cookie policy
    - [x] Help center
    - [x] Advertise
    - [x] Affiliate
    - [x] Contact
  - [ ] Manage cookies

## Функциональные требования

1. [x] У пользователя должна быть возможность зарегистрироваться и входить в приложение
   по почте и паролю, или стороннему аккаунту Google или Apple
1. [x] Пользователь должен иметь возможность оформить платную подписку,
   при этом ежемесячно долно происходить списание платы за подписку.
1. [x] Должна быть возможность выбрать цвет в нескольких цветовых моделях:
   HSB, HSL, RGB, CMYK, Lab;
   среди плашечных цветов (для пользователей с подпиской):
   RAL, HKS, Copic, Prismacolor;
   а также по имени в базе данных сайта и среди сохранённых цветов.
1. [x] Редактор цветов, аггрегирующий в себе:
   выбор цвета, перевод цветов между цветовыми моделми,
   демонстрацию похожих и смежных цветов,
   симулятор дальтонизма,
   проверку контрастности цветов,
   сопоставление с плашечными цветами,
   поиск палитр с этим цветом
1. [x] Перевод цветов между представлениями:
   HEX, RGB, CMYK, HSB, HSL, Lab, XYZ, LCH, LUV, HWB.
1. [x] Демонстрация смежных цветов и оттенков в виде градиента
1. [x] Демонстрация гармоничных цветов
1. [x] Симулятор дальтонизма с оценкой соответствия изначального цвета
   преобразованному, при этом должна
   вычисляться метрика соответствия.
1. [x] Проверка контраста цвета в виде проверки читаемости текста.
   Цвета выбираются вручную.
   Должна быть вычислена соответствующая метрика.
   Должна быть возможность автоматического
   корректирования цветов для улучшения читаемости.
1. [x] Поиск соответствий среди плашечных цветов, при этом должна
   вычисляться метрика соответствия.
1. [x] Список сохранённых палитр, которые содержат этот цвет.
   Должен быть реализован и как часть редактора цвета,
   и как отдельная страница.
1. [x] Генератор палитр. Должна быть возможность сгенерировать сочетающиеся цвета,
   при этом получившиеся цвета можно вручную заменять, добавлять, удалять, перемещать, а также
   блокировать. Заблокированные цвета не меняются при перегенерации палитры.
1. [x] Сбор статистики популярных палитр.
   Просмотр палитр по популярности и текущим трендам.
1. [ ] Извлечение палитры из изображения.
1. [x] Предпросмотр палитры на заранее закоговленных макетах.
1. [x] Изменение цветов на векторных изображениях.
   Цвета на изначальном изображении должны определяться автоматически.
1. [ ] Список шрифтов с возможностью фильтрации
1. [ ] Предпросмотр шрифта на тексте разных размеров с текстовым редактором
   и возможностью скачивания шрифта.
1. [x] Библиотека цветов из базы данных сайта
1. [x] Редактор градиентов с рандомизацией и
   возможностью указания нескольких опорных точек
1. [ ] Просмотр популярных градиентов
1. [ ] Создание градиентных палитр
1. [ ] Перевод файлов изображений из одного формата в другой.
1. [ ] Создание изображения с палитрой сбоку (Create collage)
1. [ ] Преобразователь текста, который преобразовывает символы латиницы
   в визуально похожие на них символы или последовательности символов
   в одном стиле.
1. [ ] Размещение и просмотр вакансий на рботу в области дизайна.
1. [x] Загрузка приложений и расширений
1. [x] Просмотр документации
