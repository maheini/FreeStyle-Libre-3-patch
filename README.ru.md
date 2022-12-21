
# FreeStyle Libre 3 patch

этот текст переведен автоматически. вы должны прочитать английскую или немецкую версию для получения последних обновлений.

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> readme на английском</a>.

Публичный репозиторий для разработки интерфейсов Libre 3 для таких приложений, как xDrip+ или AndroidAPS. Этот репозиторий предназначен для обмена информацией о текущих решениях, а также о Libre 3.

## Отказ от ответственности

Вы используете информацию и приложение с github.com на свой страх и риск и без каких-либо гарантий или поддержки. Этот проект не связан с Abbott и не поддерживается им.

## раствор Juggluco

Большое спасибо [jkaltes](http://jkaltes.byethost16.com/) за всю работу. С помощью приложения Juggluco можно отправлять показания уровня глюкозы в крови с датчика Libre 3 на xDrip+, AndroidAPS и т. д. в автономном режиме и без рута. Подробные инструкции можно найти здесь: [Инструкции по подключению Libre 3 к Juggluco](./Juggluco-solution/juggluco-direct-instructions/en/instructions.md). Или вы можете использовать [Ссылка для скачивания](./Juggluco-solution/versions/latest/Juggluco.apk?raw=1). Обратите внимание: этот проект осуществляется на ваш страх и риск и без каких-либо гарантий или поддержки. Этот проект не связан с Abbott и не поддерживается им.

## Другие решения для FSL 3 (требуется root или подключение к Интернету)

- Free Three: автономное решение -> требуется root и некоторые ноу-хау, и поддерживается только приложение Libre 3 до версии 3.3.1 [Ссылка (немецкий)] (https://insulinclub.de/index.php?thread /33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
       -> Последняя загрузка: [Ссылка] (https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink для загрузки Nightscout: [репозиторий Github] (https://github.com/timoschlueter/nightscout-librelink-up)
- Приложение (клиент LLU) для загрузки данных соединения и обмена ими с Xdrip (источник уровня сахара в крови: Libre 2): [Ссылка (немецкий)] (https://insulinclub.de/index.php?thread/33987-llu- клиент/&postID=654144 #post654144)
- [LinkUpConnect](https://github.com/cmtjk/LinkUpConnect): альтернатива для клиента LLU, который может отображать уровень глюкозы в крови в качестве уведомления (без Xdrip+).
- [Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/): функция в ночной сборке Xdrip+ (калибровка невозможна)
- В разработке для iOS: DiaBLE -> Пытается расширить возможности FSTL3. [Репозиторий Github] (https://github.com/gui-dos/DiaBLE)

## Текущий статус

Расшифровка успешно взломана :smiley:. Теперь есть окончательное решение для нерутированных устройств, работающих с Android и Xdrip.

## Как внести свой вклад

Если у вас есть какая-либо полезная информация о Libre 3, поделитесь ею на [вкладке обсуждений] (https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

### #WeAreNotWaiting