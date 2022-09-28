
# FreeStyle Libre 3 patch

этот текст переведен автоматически. вы должны прочитать английскую или немецкую версию для получения последних обновлений.

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> readme на английском</a>.

Публичное репо для разработки Libre 3. Этот репозиторий должен использоваться для обмена информацией о Libre 3. Возможные цели - расшифровка и создание интерфейса для Xdrip.

## отказ от ответственности

использование информации и приложений с github.com осуществляется на свой страх и риск, без гарантий и официальной поддержки любого рода. данный проект не связан и не поддерживается компанией Abbott.

## решение Juggluco

огромная благодарность [jkaltes](http://jkaltes.byethost16.com/) за проделанную работу. С [новым патчем FSTL3](http://jkaltes.byethost16.com/Juggluco/libre3/), 
наконец-то появилось автономное решение, которое не требует root-доступа и полностью интегрировано с Xdrip. вы можете найти инструкции здесь: [Инструкции для Libre3 патча с Juggluco](./Juggluco-solution/instructions/en/instructions.md). Или вы можете воспользоваться [ссылкой для скачивания](./Juggluco-solution/versions/latest/Libre-3-patch.apk?raw=1).Пожалуйста, обратите внимание: это решение выполняется на ваш страх и риск, без гарантии или официальной поддержки любого рода. Этот проект не связан с компанией Abbott и не поддерживается ею.

Обратите внимание: я не участвовал в разработке Juggluco и финального патча для Libre 3, но я люблю делиться всеми разработками, которые ведутся.

## Другие решения для FSL 3 (требующие root или онлайн-соединения)

- Free 3: Оффлайн решение -> требует root и некоторых знаний, также поддерживает только приложения libre 3 до версии 3.3.1. [Link (German)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->Последняя загрузка: [Ссылка](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink для Nightscout с боковой загрузкой: [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- Приложение (LLU Client) для загрузки данных Linkup и обмена с Xdrip (источник: Libre 2): [Link (German)](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- [LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): альтернатива LLU Client, которая может показывать BG как уведомления через Xdrip+
- [Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): функция в Nightly сборке Xdrip+ (калибровка невозможна).
- В разработке для iOS: DiaBLE -> пытается использовать возможности FSTL3. [Github repo](https://github.com/gui-dos/DiaBLE)

## Текущее состояние

Расшифровка только что была сломана :smiley:. Наконец-то появилось решение для не рутированных телефонов, работающее с Android & Xdrip.

## Как внести свой вклад

Если у вас есть полезная информация о Libre 3, поделитесь ею во вкладке [обсуждения](https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

## Информация о шифровании

О приложении libre 3 известно следующее: После запуска приложение проверяется на наличие модификаций. Там используется защита кода WhiteCryption.

### #WeAreNotWaiting
