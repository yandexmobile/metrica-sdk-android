This repository contains various versions of **Yandex.Metrica for Android Apps**, **java-docs** and additional libraries that are necessary for it to work.

`Mobmetricalib-1.2`, `VERSION 1.2`, `API LEVEL 4`
--------------------------------------------

* **mobmetricalib-android-1.2-nolibs.jar** - Without **protobuf** within itself.
* **mobmetricalib-android-1.2-wlibs.jar** - With **protobuf-2.5.0** within itself.
* **mobmetricalib-android-1.2-javadoc.jar** - **Java**-doc for library.
* **protobuf-java-2.5.0.jar** - **protobuf** library for **mobmetricalib-android-1.2-nolibs.jar**, version **2.5.0**.

Version 1.2, Changelog
------------------------------

* **Yandex.Metrika for Apps** now uses **[protobuf-2.5.0](http://search.maven.org/#artifactdetails%7Ccom.google.protobuf%7Cprotobuf-java%7C2.5.0%7Cbundle)**.
* **API-level** is now **4**.
* Greatly reduced the size of the library which is supplied with the **protobuf** library (from 360 Kb to 150 Kb).
* Added new methods:
    * `getLibraryVersion()` — returns a version of the library (e.g. **"1.2"**);
    * `getLibraryApiLevel()` — returns the API level of library (e.g. **4**);
    * `isMetricaProcess(android.content.Context)` — specifies whether the Metrica process is running or not.
* Additional statistical parameters:
    * `"Root" status` — you can read about root devices [here](http://en.wikipedia.org/wiki/Android_rooting);
    * `Device type` — the next types of devices such as **Smartphone**, **Phablet**, **Tablet**, and **TV** are now displayed.
* Fixed a large number of bugs:
    * The `metrica:api:key` option can be omitted in the **AndroidManifest.xml** file and this option can be set programmatically without problems.
    * Bugs associated with the database.
    * Bugs associated with **ProGuard**. Now if you build your application with **ProGuard**, you need to keep **Metrica library**. You can use the following lines of code:
        * `-keep class com.yandex.metrica.** { *; }`
        * `-dontwarn com.yandex.metrica.**`
* Fixed **javadocs**.

`Mobmetricalib-1.0`, `VERSION 1.0`, `API LEVEL 1`
--------------------------------------------

* **mobmetricalib-android-1.0-nolibs.jar** - Without **protobuf** within itself.
* **mobmetricalib-android-1.0-wlibs.jar** - With **protobuf-2.4.1** within itself.
* **mobmetricalib-android-1.0-javadoc.jar** - **Java**-doc for library.
* **protobuf-java-2.4.1.jar** - **protobuf** library for **mobmetricalib-android-1.0-nolibs.jar**, version **2.4.1**.

Alternatively you can get Metrica for Apps to your project as maven artifact. 
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.0

Additional information
---------------------------

* [Documentation in Russian](http://api.yandex.ru/metrica-mobile-sdk/) and [Documentation in English](http://api.yandex.com/metrica-mobile-sdk/), where you can find some additional information about **mobmetricalib**.
* Test example for **mobmetricalib** is available at [https://github.com/yandexmobile/metrica-sample-android](https://github.com/yandexmobile/metrica-sample-android). Take a look to it please for more understanding.
* You can register your app at [Yandex.Metrica for Apps homepage](http://appmetrica.yandex.ru/).


License
---------

License agreement on use of Yandex.Metrica for Apps SDK is available at: [http://legal.yandex.ru/metrica_termsofuse/](http://legal.yandex.ru/metrica_termsofuse/).


---------------
---------------


В этом репозитории находятся различные версии **Yandex.Metrica for Android Apps**. Тут вы сможете найти **java-docs** к ним и дополнительные библиотеки, которые нужны для ее работы.

`Mobmetricalib-1.2`, `VERSION 1.2`, `API LEVEL 4`
--------------------------------------------

* **mobmetricalib-android-1.2-nolibs.jar** - Версия без **protobuf** внутри.
* **mobmetricalib-android-1.2-wlibs.jar** - Версия с **protobuf-2.5.0** внутри.
* **mobmetricalib-android-1.2-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **protobuf-java-2.5.0.jar** - **protobuf** библиотека для **mobmetricalib-android-1.2-nolibs.jar**, версия **2.5.0**.

Версия 1.2, Список изменений
------------------------------

* **Метрика для приложений** использует **protobuf-2.5.0**.
* Теперь **metrica:api:level** нужно устанавливать равным 4.
* Значительно уменьшен размер библиотеки, поставляемой с **protobuf** внутри себя (с 360 Кб до 150 Кб).
* Добавлены новые методы:
	* `getLibraryApiLevel()` — возвращает версию билиотеки (например **"1.2"**).
	* `getLibraryVersion()` — возвращает **API-уровень** библиотеки (например **4**).
	* `isMetricaProcess(android.content.Context)` — возвращает булевское значение, показывающее находимся ли мы в процессе Метрики или нет.
* Дополнительные параметры статистики:
	* `"Root" status` — вы можете почитать о root **[здесь](http://ru.wikipedia.org/wiki/Рутинг)**.
	* `Device type` — в статистике будут доступны следующие типы устройств: **Смартфон**, **Фаблет**, **Планшет**, **ТВ**.
* Исправлено большое количество ошибок:
	* Теперь можно опускать `metrica:api:key` опцию в **AndroidManifest.xml** файле и устанавливать ее программно без проблем.
	* Ошибки связанные с базой данных.
	* Ошибки связанные с обфускатором **ProGuard**. Если вы используете **ProGuard** при сборке вашего проекта, то следует не обфусцировать **Metrica**. Вы можете использовать следующие строчки кода ниже:
		* `-keep class com.yandex.metrica.** { *; }`
		* `-dontwarn com.yandex.metrica.**`
* Исправлен **javadocs**.

`Mobmetricalib-1.0`, `VERSION 1.0`, `API LEVEL 1`
--------------------------------------------

* **mobmetricalib-android-1.0-nolibs.jar** - Версия без **protobuf** внутри.
* **mobmetricalib-android-1.0-wlibs.jar** - Версия с **protobuf-2.4.1** внутри.
* **mobmetricalib-android-1.0-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **protobuf-java-2.4.1.jar** - **protobuf** библиотека для **mobmetricalib-android-1.0-nolibs.jar**, версия **2.4.1**.

Метрика для приложений доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.0

Дополнительная информация
---------------------------

Также у этого проекта есть:

* [Документация на русском](http://api.yandex.ru/metrica-mobile-sdk/) и [на английском](http://api.yandex.com/metrica-mobile-sdk/), в которой содержится полная документация по **mobmetricalib** и описание подключения библиотеки к вашему проекту, а также инструкции по использованию.
* Тестовый пример, который использует данную библиотеку. Вы можете найти его в другом репозитории [тут](https://github.com/yandexmobile/metrica-sample-android). Присмотритесь к нему пожалуйста для большего понимания. 

Лицензия
---------

Лицензионное соглашение по использованию **Yandex.Metrica for Apps SDK** доступно по следующей ссылке [http://legal.yandex.ru/metrica_termsofuse/](http://legal.yandex.ru/metrica_termsofuse/).

