# Минимальные системные требования и установка ОС

## Минимальные системные требования

Каждая ОС имеет минимальные требования к оборудованию, на котором она может работать. 
Хоть это и минимальные на самом деле для запуска прикладного ПО может потребоваться большее ресурсов. 
ПО определяет оборудование, которое будет использоваться для установки ОС.

## Windows 10

- **Процессор** с частотой не менее 1ГГц. Microsoft не указывает конкретных требований к поддержке определённых инструкций. Предполагается, что все процессоры с этой частотой их уже имеют.
- **Количество оперативной памяти** минимум 1Гб для 32-х разрядной версии и 2Гб для 64-х.
- **Место на устройстве** хранения - 16Гб для 32-х разрядной версии и 20Гб для 64-х. Больший размер для 64-х разрядной версии объясняется включением компонентов из 32-х разрядной для возможности запуска имеющихся  приложений.
- **Видеокарта** с разрешением 800х600 и драйвером стандарта WDDM 1.0 (с поддержкой Direct X 9.0). Основная сложность будет с наличием драйвера WDDM, потому что не для всех старых видеокарт такие драйверы существуют.

Соответствие этим требованиям позволит ОС работать, но некоторые компоненты могут потребовать дополнительного оборудования.

## Windows Server 2012 

- **Процессор** 64-х разрядный с частотой 1.4 ГГц
- **ОЗУ** минимум  512 Мб.
- **Место на устройстве** хранения 32 GB. Это абсолютный минимум, при наличии более 16Гб оперативной памяти потребуется больше для размещения файлов подкачки и сна. Так же дополнительное место потребуется при проведении установки по сети. Как и с настольными версиями в последствии потребуется ещё место для скачивания и установки обновлений.
- **Видеокарта и монитор** с разрешением не менее 800х600.Требования к драйверам, как у настольных версий здесь нет.
- **Клавиатура и мышь**.
- **Доступ к сети Интернет**.

Стоит отметить отсутствие поддержки 32-х разрядных процессоров. Считается, что ОС будет ставится только на достаточно свежее оборудование, где их не будет.

## Windows Server 2016

Добавляется требования поддержки процессором инструкций NX, DEP, CMPXCHG16b, LAHF/SAHF и PrefetchW. 

А так же второго уровня трансляции адресов с использованием EPT or NPT. 

Для памяти добавляется требование наличия коррекции ошибок (ECC).

## Debian GNU/Linux 9

Существуют минимальные и рекомендованные требования для стандартной установки:

* Интерфейс командной строки
  - ОЗУ (минимум) - 128Мб
  - ОЗУ (рекомендуемое) - 512Мб
  - Место на устройстве хранения - 2Гб
* Графический интерфейс
  - ОЗУ (минимум) - 256Мб
  - ОЗУ (рекомендуемое) - 1Гб
  - Место на устройстве хранения - 10Гб
  
Явных требований к поддержке определённых инструкций у Linux нет.

Требований к видеокартам у Linux в явном виде также нет.