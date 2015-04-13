Yandex.Metrica for Apps 
===========

This repository contains various versions of **Yandex.Metrica for Android Apps**, **java-docs** and additional libraries that are necessary for it to work.

Documentation
---------------------------
* You can register your app at [Yandex.Metrica for Apps homepage](http://appmetrica.yandex.ru/).
* [Documentation in Russian](http://api.yandex.ru/metrica-mobile-sdk/) and [Documentation in English](http://api.yandex.com/metrica-mobile-sdk/) are available. You can find some additional information about **mobmetricalib** there.
* Test example for **mobmetricalib** is available at [https://github.com/yandexmobile/metrica-sample-android](https://github.com/yandexmobile/metrica-sample-android). It demonstrates several library use-cases.  

Latest version
---------------------------

`Mobmetricalib-1.65`, `VERSION 1.65`, `API LEVEL 21`
--------------------------------------------

* **mobmetricalib-android-1.65-nolibs.jar** - Without **protobuf** within itself.
* **mobmetricalib-android-1.65-wlibs.jar** - With **protobuf-2.5.0** within itself.
* **mobmetricalib-android-1.65-javadoc.jar** - **Java**-doc for library.
* **protobuf-java-2.5.0.jar** - **protobuf** library for **mobmetricalib-android-1.65-nolibs.jar**, version **2.5.0**.
* **native** - native libraries.

Alternatively you can get Metrica for Apps to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.65

Version 1.65, Changelog
------------------------------

* Increased **API-level** to **21**.
* Improved stability and accuracy.

`Mobmetricalib-1.60`, `VERSION 1.60`, `API LEVEL 16`
--------------------------------------------

* **mobmetricalib-android-1.60-nolibs.jar** - Without **protobuf** within itself.
* **mobmetricalib-android-1.60-wlibs.jar** - With **protobuf-2.5.0** within itself.
* **mobmetricalib-android-1.60-javadoc.jar** - **Java**-doc for library.
* **protobuf-java-2.5.0.jar** - **protobuf** library for **mobmetricalib-android-1.60-nolibs.jar**, version **2.5.0**.
* **native** - native libraries.

Alternatively you can get Metrica for Apps to your project as maven artifact. 
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.60

Version 1.60, Changelog
------------------------------

* Increased **API-level** to **16**.
* Added free application installation tracking.
* Added native crashes support.
* Added events with additional parameters (_Json_, _Attributes_).
* Renamed main **API** class from **Counter** to **YandexMetrica**.
* Changed **API** methods from _non-static_ to _static_. Replace all calls of **Counter.sharedInstance()** with **YandexMetrica**.
* Moved **API-key** definition from **AndroidManifest.xml** to **YandexMetrica** initialization method. Remove **API-key** from **AndroidManifest.xml**.
* Removed **com.yandex.metrica.CampaignReceiver** from **AndroidManifest.xml**. Move the following lines of code to **com.yandex.metrica.MetricaEventHandler**:

        <intent-filter>
             <action android:name="com.android.vending.INSTALL_REFERRER"/>
        </intent-filter>
    
* _Deprecated_ **setLocation(double, double)** method. Use **setLocation(android.location.Location)** instead.
* Improved location handling.
* Improved stability and performance.
* Optimised library start time.

`Mobmetricalib-1.2`, `VERSION 1.2`, `API LEVEL 4`
--------------------------------------------

* **mobmetricalib-android-1.2-nolibs.jar** - Without **protobuf** within itself.
* **mobmetricalib-android-1.2-wlibs.jar** - With **protobuf-2.5.0** within itself.
* **mobmetricalib-android-1.2-javadoc.jar** - **Java**-doc for library.
* **protobuf-java-2.5.0.jar** - **protobuf** library for **mobmetricalib-android-1.2-nolibs.jar**, version **2.5.0**.

Alternatively you can get Metrica for Apps to your project as maven artifact. 
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.2

Version 1.2, Changelog
------------------------------

* Updated protobuf version to **[protobuf-2.5.0](http://search.maven.org/#artifactdetails%7Ccom.google.protobuf%7Cprotobuf-java%7C2.5.0%7Cbundle)**.
* Increased **API-level** to **4**. Update its value in **AndroidManifest.xml**.
* Greatly reduced the size of the library which is supplied with the **protobuf** library (from 360 Kb to 150 Kb).
* Added new methods:
    * `getLibraryVersion()` — returns a version of the library (e.g. **"1.2"**);
    * `getLibraryApiLevel()` — returns the API level of library (e.g. **4**);
    * `isMetricaProcess(android.content.Context)` — specifies whether the Metrica process is running or not.
* Added new statistical parameters:
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

License
---------

License agreement on use of Yandex.Metrica for Apps SDK is available at: [http://legal.yandex.ru/metrica_termsofuse/](http://legal.yandex.ru/metrica_termsofuse/).



---------------
---------------


Yandex.Metrica для приложений
===============


В этом репозитории находятся различные версии **Yandex.Metrica for Android Apps**. Тут вы сможете найти **java-docs** к ним и дополнительные библиотеки, которые нужны для ее работы.

Документация
---------------------------
* Вы можете зарегистрировать свое приложение на [домашней странице Yandex.Metrica for Apps](http://appmetrica.yandex.ru/).
* Доступна [документация на русском](http://api.yandex.ru/metrica-mobile-sdk/) и [на английском](http://api.yandex.com/metrica-mobile-sdk/), в которой содержится полная документация по **mobmetricalib** и описание подключения библиотеки к вашему проекту, а также инструкции по использованию.
* Доступен тестовый пример, демонстрирующий различные возможности библиотеки. Вы можете найти его в другом репозитории [здесь](https://github.com/yandexmobile/metrica-sample-android).

Последняя версия
---------------------------

`Mobmetricalib-1.65`, `VERSION 1.65`, `API LEVEL 21`
--------------------------------------------

* **mobmetricalib-android-1.65-nolibs.jar** - Версия без **protobuf** внутри.
* **mobmetricalib-android-1.65-wlibs.jar** - Версия с **protobuf-2.5.0** внутри.
* **mobmetricalib-android-1.65-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **protobuf-java-2.5.0.jar** - **protobuf** библиотека для **mobmetricalib-android-1.65-nolibs.jar**, версия **2.5.0**.
* **native** - нативные библиотеки.

Метрика для приложений доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.65

Версия 1.65, Список изменений
------------------------------

* Увеличен **metrica:api:level** до **21**. Обновите его значение в **AndroidManifest.xml**.
* Повышена надежность статистики.

`Mobmetricalib-1.60`, `VERSION 1.60`, `API LEVEL 16`
--------------------------------------------

* **mobmetricalib-android-1.60-nolibs.jar** - Версия без **protobuf** внутри.
* **mobmetricalib-android-1.60-wlibs.jar** - Версия с **protobuf-2.5.0** внутри.
* **mobmetricalib-android-1.60-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **protobuf-java-2.5.0.jar** - **protobuf** библиотека для **mobmetricalib-android-1.60-nolibs.jar**, версия **2.5.0**.
* **native** - нативные библиотеки.

Метрика для приложений доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.60

Версия 1.60, Список изменений
------------------------------

* Увеличен **metrica:api:level** до **16**. Обновите его значение в **AndroidManifest.xml**.
* Добавлена бесплатная поддержка трекинга установок приложений.
* Добавлена обработка нативных аварийных остановок приложения.
* Добавлена отправка событий с дополнительными параметрами (_Json_, _Attributes_).
* Переименован главный класс API из **Counter** в **YandexMetrica**.
* Изменен принцип работы с API. Теперь все методы API статические. Замените **Counter.sharedInstance()** на **YandexMetrica**.
* Перемещено определение **API-ключа (metrica:api:key)** из **AndroidManifest.xml** в метод инициализации библиотеки. **API-ключ (metrica:api:key)** в **AndroidManifest.xml** теперь игнорируется
* Удален **receiver** для **com.yandex.metrica.CampaignReceiver** из файла **AndroidManifest.xml**. Теперь его **intent-filter** указывается в **receiver** для **com.yandex.metrica.MetricaEventHandler**:

        <intent-filter> 
             <action android:name="com.android.vending.INSTALL_REFERRER"/>
        </intent-filter>

* Устарел метод **setLocation(double, double)** для установки локации. Используйте метод **setLocation(android.location.Location)**.
* Улучшена работа с локацией.
* Повышена стабильность и улучшено быстродействие.
* Ускорен запуск библиотеки.

`Mobmetricalib-1.2`, `VERSION 1.2`, `API LEVEL 4`
--------------------------------------------

* **mobmetricalib-android-1.2-nolibs.jar** - Версия без **protobuf** внутри.
* **mobmetricalib-android-1.2-wlibs.jar** - Версия с **protobuf-2.5.0** внутри.
* **mobmetricalib-android-1.2-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **protobuf-java-2.5.0.jar** - **protobuf** библиотека для **mobmetricalib-android-1.2-nolibs.jar**, версия **2.5.0**.

Метрика для приложений доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.2

Версия 1.2, Список изменений
------------------------------

* Обновлен protobuf до **[protobuf-2.5.0](http://search.maven.org/#artifactdetails%7Ccom.google.protobuf%7Cprotobuf-java%7C2.5.0%7Cbundle)**.
* Увеличен **metrica:api:level** до 4. Обновите его значение в **AndroidManifest.xml**.
* Значительно уменьшен размер библиотеки, поставляемой с **protobuf** внутри себя (с 360 Кб до 150 Кб).
* Добавлены новые методы:
	* `getLibraryApiLevel()` — возвращает версию билиотеки (например **"1.2"**).
	* `getLibraryVersion()` — возвращает **API-уровень** библиотеки (например **4**).
	* `isMetricaProcess(android.content.Context)` — возвращает булевское значение, показывающее находимся ли мы в процессе Метрики или нет.
* Добавлены новые параметры статистики:
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

Лицензия
---------

Лицензионное соглашение по использованию **Yandex.Metrica for Apps SDK** доступно по следующей ссылке [http://legal.yandex.ru/metrica_termsofuse/](http://legal.yandex.ru/metrica_termsofuse/).

