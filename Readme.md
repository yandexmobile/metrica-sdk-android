AppMetrica SDK
===========

This repository contains various versions of **AppMetrica SDK**, **java-docs** and additional libraries that are necessary for it to work.

Documentation
---------------------------
* You can register your app at [AppMetrica SDK homepage](http://appmetrica.yandex.ru/).
* [Documentation in Russian](https://tech.yandex.ru/metrica-mobile-sdk/doc/mobile-sdk-dg/concepts/android-initialize-docpage/) and [Documentation in English](https://tech.yandex.com/metrica-mobile-sdk/doc/mobile-sdk-dg/concepts/android-initialize-docpage/) are available. You can find some additional information about **mobmetricalib** there.
* Test example for **mobmetricalib** is available at [https://github.com/yandexmobile/metrica-sample-android](https://github.com/yandexmobile/metrica-sample-android). It demonstrates several library use-cases.  

Latest version
--------------

`Mobmetricalib-2.71`, `VERSION 2.71`, `API LEVEL 56`
----------------------------------------------------
* **mobmetricalib-2.71.jar** - jar file version.
* **mobmetricalib-2.71.aar** - aar file version.
* **mobmetricalib-2.71-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.71

Version 2.71, Changelog
-----------------------
* Added method YandexMetrica#reportAppOpen(java.lang.String) for reporting deeplink app opening
* Fixed error in deferred deeplink parameters retrieving

`Mobmetricalib-2.70`, `VERSION 2.70`, `API LEVEL 55`
----------------------------------------------------
* **mobmetricalib-2.70.jar** - jar file version.
* **mobmetricalib-2.70.aar** - aar file version.
* **mobmetricalib-2.70-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.70

Version 2.70, Changelog
-----------------------
* Added deferred deeplink support
* Improved crash collecting on application launch
* Added logging events attributes
* Minor improvements and stabilization

`Mobmetricalib-2.62`, `VERSION 2.62`, `API LEVEL 52`
----------------------------------------------------
* **mobmetricalib-2.62.jar** - jar file version.
* **mobmetricalib-2.62.aar** - aar file version.
* **mobmetricalib-2.62-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.62

Version 2.62, Changelog
-----------------------
* Minor improvements and stabilization

`Mobmetricalib-2.60`, `VERSION 2.60`, `API LEVEL 50`
----------------------------------------------------
* **mobmetricalib-2.60.jar** - jar file version.
* **mobmetricalib-2.60.aar** - aar file version.
* **mobmetricalib-2.60-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.60

Version 2.60, Changelog
-----------------------
* Added method YandexMetrica#reportAppOpen(android.app.Activity) for reporting deeplink app opening  
* To YandexMetricaConfig.Builder added method handleFirstActivationAsUpdate(boolean). It allows library to consider first activation as app update (not new app install). It can be useful when new app version with appmetrica updates old version without library. 
* Events database size limited to 5 MB 
* other improvements and optimizations

`Mobmetricalib-2.51`, `VERSION 2.51`, `API LEVEL 48`
----------------------------------------------------
* **mobmetricalib-2.51.jar** - jar file version.
* **mobmetricalib-2.51.aar** - aar file version.
* **mobmetricalib-2.51-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.51

Version 2.51, Changelog
-----------------------
* Improved the stability of the library.
* Added support for Android 7.
* Prohibited using a Google account for making backup copies of AppMetrica SDK data.

`Mobmetricalib-2.42`, `VERSION 2.42`, `API LEVEL 45`
----------------------------------------------------
* **mobmetricalib-2.42.jar** - jar file version.
* **mobmetricalib-2.42.aar** - aar file version.
* **mobmetricalib-2.42-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.42

Version 2.42, Changelog
-----------------------
* Minor bug fixes and optimizations.

`Mobmetricalib-2.41`, `VERSION 2.41`, `API LEVEL 44`
----------------------------------------------------
* **mobmetricalib-2.41.jar** - jar file version.
* **mobmetricalib-2.41.aar** - aar file version.
* **mobmetricalib-2.41-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.41

Version 2.41, Changelog
-----------------------
* Performance optimizations of sending data to server.

`Mobmetricalib-2.40`, `VERSION 2.40`, `API LEVEL 43`
----------------------------------------------------
* **mobmetricalib-2.40.jar** - jar file version.
* **mobmetricalib-2.40.aar** - aar file version.
* **mobmetricalib-2.40-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.40

Version 2.40, Changelog
-----------------------
* Added the ability to send statistics using an API key that differs from the app's API key.

`Mobmetricalib-2.32`, `VERSION 2.32`, `API LEVEL 41`
---------------------------------------------------
* **mobmetricalib-2.32.jar** - jar file version.
* **mobmetricalib-2.32.aar** - aar file version.
* **mobmetricalib-2.32-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.32

Version 2.32, Changelog
-----------------------
* Improved the stability of the library and the quality of statistical data.

`Mobmetricalib-2.30`, `VERSION 2.30`, `API LEVEL 39`
--------------------------------------------
* **mobmetricalib-2.30.jar** - jar file version.
* **mobmetricalib-2.30.aar** - aar file version.
* **mobmetricalib-2.30-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.30

Version 2.30, Changelog
---------------------------
* Extended configuration of AppMetrica was added. Extended configuration guarantees that configuration parameters will be applied as soon as sdk will be initialized.
* Tracking of preloaded apps was added.
* Minor improvements and optimizations.

`Mobmetricalib-2.21`, `VERSION 2.21`, `API LEVEL 36`
--------------------------------------------
* **mobmetricalib-2.21.jar** - jar file version.
* **mobmetricalib-2.21.aar** - aar file version.
* **mobmetricalib-2.21-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.21

Version 2.21, Changelog
---------------------------
* Method YandexMetrica.isMetricaProcess() was removed.
* By default sending list of installed packages (method boolean setCollectInstalledApps(boolean collect)) was turned off .
* Method isCollectInstalledApps() was added.
* Method enableActivityAutoTracking(final Application application), which enables activity lifecycle auto tracking for Android 4+, was added.
* Method registerReferrerBroadcastReceivers(BroadcastReceiver...anotherReferrerReceivers), which gives possibility to register INSTALL_REFERRER trackers from another tracking systems, was added.
* Method setLogEnabled for turning on AppMetrica SDK logging was added.
* Aar version of AppMetrica SDK is default now in MavenCentral. To include Jar version via Gradle use com.yandex.android:mobmetricalib-internal:2.21:jar.
* Error which crashed application with exception java.lang.NullPointerException at com.yandex.metrica.impl.ob.f.b was fixed.

`Mobmetricalib-2.00`, `VERSION 2.00`, `API LEVEL 32`
--------------------------------------------
* **mobmetricalib-2.00.jar** - jar file version.
* **mobmetricalib-2.00.aar** - aar file version.
* **mobmetricalib-2.00-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.00

Version 2.00, Changelog
------------------------------
* The API_KEY format has been changed. The app ID in a new format is available in the [AppMetrica web interface](http://appmetrika.yandex.ru/) when the app editing mode is engaged.
* The method of initializing the library in the app has been renamed from **initialize(android.content.Context, java.lang.String)** to **activate(android.content.Context, java.lang.String)**.
* The session length has been changed. Now it is 10 seconds, by default.
* The library has been adapted for Android M.
* We have significantly improved performance and reduced the power consumption.
* Removed obsolete method **setReportsEnabled(boolean enabled)** — lets you enable and disable sending reports.
* Removed obsolete method **setDispatchPeriod(int dispatchPeriodSeconds)** — allows you to set the interval in seconds between sending accumulated events to the server.
* Removed obsolete method **setMaxReportsCount(int maxReportsCount)** — allows you to set the maximum number of events that can be stored up before sending all accumulated events to the server.
* Removed obsolete method **startNewSessionManually()** — allows you to start a new session manually.
* Removed obsolete method **sendEventsBuffer()** — allows you to send all accumulated events without waiting for them to automatically be sent to the server.

`Mobmetricalib-1.82`, `VERSION 1.82`, `API LEVEL 31`
--------------------------------------------

* **mobmetricalib-android-1.82.jar** - jar file version.
* **mobmetricalib-android-1.82.aar** - aar file version.
* **mobmetricalib-android-1.82-javadoc.jar** - **Java**-doc for library.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.82

Version 1.82, Changelog
------------------------------

* Increased **API-level** to **31**.
* Improved quality of calculating statistics for sessions and installs.
* Migrated to protobuf-nano — the overall size of the library is smaller and it works faster. If you were using the protobuf-2.5.0 library with the AppMetrica SDK, delete it.
* The AndroidManifest.xml file does not specify
  provider:
  ```
  <provider
      android:name="FULL_PACKAGE_PATH_TO_YOUR_PROVIDER.MetricaContentProvider"
      android:authorities="ROOT_PACKAGE_PATH.MetricaContentProvider"
      android:enabled="true"
      android:exported="true"/>
  ```
  the following intent-filter for com.yandex.metrica.MetricaEventHandler:
  ```
  <intent-filter>
      <action android:name="com.yandex.metrica.intent.action.SYNC"/>
  </intent-filter>

  <intent-filter>
      <action android:name="android.intent.action.PACKAGE_ADDED"/>
      <action android:name="android.intent.action.PACKAGE_DATA_CLEARED"/>
      <data android:scheme="package"/>
  </intent-filter>
  ```
* To use the AppMetrica SDK, you do not need to create a custom provider class in the application package with the name MetricaContentProvider that inherits from com.yandex.metrica.MetricaContentProvider. Delete it from your application.
* Added the ability to transmit [additional crash data.](https://tech.yandex.com/metrica-mobile-sdk/doc/mobile-sdk-dg/concepts/android-operations-docpage/#environment-value)

`Mobmetricalib-1.65`, `VERSION 1.65`, `API LEVEL 21`
--------------------------------------------

* **mobmetricalib-android-1.65-nolibs.jar** - Without **protobuf** within itself.
* **mobmetricalib-android-1.65-wlibs.jar** - With **protobuf-2.5.0** within itself.
* **mobmetricalib-android-1.65-javadoc.jar** - **Java**-doc for library.
* **protobuf-java-2.5.0.jar** - **protobuf** library for **mobmetricalib-android-1.65-nolibs.jar**, version **2.5.0**.
* **native** - native libraries.

Alternatively you can get AppMetrica SDK to your project as maven artifact.
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

Alternatively you can get AppMetrica SDK to your project as maven artifact. 
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

Alternatively you can get AppMetrica SDK to your project as maven artifact. 
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

Alternatively you can get AppMetrica SDK to your project as maven artifact. 
Maven central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.0

License
---------

License agreement on use of AppMetrica SDK is available at: [http://legal.yandex.ru/metrica_termsofuse/](http://legal.yandex.ru/metrica_termsofuse/).



---------------


AppMetrica SDK
===============


В этом репозитории находятся различные версии **AppMetrica SDK**. Тут вы сможете найти **java-docs** к ним и дополнительные библиотеки, которые нужны для ее работы.

Документация
---------------------------
* Вы можете зарегистрировать свое приложение на [домашней странице AppMetrica SDK](http://appmetrica.yandex.ru/).
* Доступна [документация на русском](https://tech.yandex.ru/metrica-mobile-sdk/doc/mobile-sdk-dg/concepts/android-initialize-docpage/) и [на английском](https://tech.yandex.com/metrica-mobile-sdk/doc/mobile-sdk-dg/concepts/android-initialize-docpage/), в которой содержится полная документация по **mobmetricalib** и описание подключения библиотеки к вашему проекту, а также инструкции по использованию.
* Доступен тестовый пример, демонстрирующий различные возможности библиотеки. Вы можете найти его в другом репозитории [здесь](https://github.com/yandexmobile/metrica-sample-android).

Последняя версия
----------------

`Mobmetricalib-2.71`, `VERSION 2.71`, `API LEVEL 56`
----------------------------------------------------
* **mobmetricalib-2.71.jar** - jar версия.
* **mobmetricalib-2.71.aar** - aar версия.
* **mobmetricalib-2.71-javadoc.jar** - **Java** - документация.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.71

Version 2.71, Changelog
-----------------------
* Добавлен метод для трекинга открытий приложения диплинками: YandexMetrica#reportAppOpen(java.lang.String)
* Исправлена ошибка при получении параметров отложенных диплинков

`Mobmetricalib-2.70`, `VERSION 2.70`, `API LEVEL 55`
----------------------------------------------------
* **mobmetricalib-2.70.jar** - jar версия.
* **mobmetricalib-2.70.aar** - aar версия.
* **mobmetricalib-2.70-javadoc.jar** - **Java** - документация.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.70

Version 2.70, Changelog
-----------------------
* Добавлена поддержка отложенных диплинков
* Улучшен сбор крешей, возникающих во время запуска приложения
* Добавлен вывод в лог атрибутов событий
* Другие незначительные улучшения, исправления и повышение стабильности

`Mobmetricalib-2.62`, `VERSION 2.62`, `API LEVEL 52`
----------------------------------------------------
* **mobmetricalib-2.62.jar** - jar версия.
* **mobmetricalib-2.62.aar** - aar версия.
* **mobmetricalib-2.62-javadoc.jar** - **Java** - документация.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.62

Version 2.62, Changelog
-----------------------
* Незначительные улучшения, исправления и повышение стабильности

`Mobmetricalib-2.60`, `VERSION 2.60`, `API LEVEL 50`
----------------------------------------------------
* **mobmetricalib-2.60.jar** - jar версия.
* **mobmetricalib-2.60.aar** - aar версия.
* **mobmetricalib-2.60-javadoc.jar** - **Java** - документация.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.60

Version 2.60, Changelog
-----------------------
* Добавлен метод для трекинга открытий приложения диплинками: YandexMetrica#reportAppOpen(android.app.Activity)
* Добавлен метод, который сообщает метрике, что метрика активируется в установленном ранее приложении и первый запуск этой версии приложения стоит трактовать как запуск обновленной, а не впервые установленной версии приложения (актуально для случаев, когда appmetrica встраивается в приложение, у которого уже есть несколько релизных версий): YandexMetricaConfig.Builder#handleFirstActivationAsUpdate(boolean)
* Размер бд событий ограничен 5MB
* другие улучшения и оптимизации

`Mobmetricalib-2.51`, `VERSION 2.51`, `API LEVEL 48`
----------------------------------------------------
* **mobmetricalib-2.51.jar** - jar версия.
* **mobmetricalib-2.51.aar** - aar версия.
* **mobmetricalib-2.51-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.51

Version 2.51, Changelog
-----------------------
* Повышена стабильность работы библиотеки.
* Добавлена поддержка Android 7.
* Добавлен запрет на резервное копирование данных AppMetrica SDK в Google-аккаунт.

`Mobmetricalib-2.42`, `VERSION 2.42`, `API LEVEL 45`
----------------------------------------------------
* **mobmetricalib-2.42.jar** - ar версия.
* **mobmetricalib-2.42.aar** - aar версия.
* **mobmetricalib-2.42-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.42

Version 2.42, Changelog
-----------------------
* Незначительные исправления и улучшения.

`Mobmetricalib-2.41`, `VERSION 2.41`, `API LEVEL 44`
----------------------------------------------------
* **mobmetricalib-2.41.jar** -  jar версия.
* **mobmetricalib-2.41.aar** - aar версия.
* **mobmetricalib-2.41-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.41

Version 2.41, Changelog
-----------------------
* Оптимизации отправки данных на сервер.

`Mobmetricalib-2.40`, `VERSION 2.40`, `API LEVEL 43`
----------------------------------------------------
* **mobmetricalib-2.40.jar** - jar версия.
* **mobmetricalib-2.40.aar** - aar версия.
* **mobmetricalib-2.40-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.40

Version 2.40, Changelog
-----------------------
* Добавлена возможность отправки данных статистики на API key, отличный от API key приложения.

`Mobmetricalib-2.32`, `VERSION 2.32`, `API LEVEL 41`
---------------------------------------------------
* **mobmetricalib-2.32.jar** - jar версия.
* **mobmetricalib-2.32.aar** - aar версия.
* **mobmetricalib-2.32-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.32

Version 2.32, Changelog
-----------------------
* Повышена стабильность библиотеки и качество статистических данных.

`Mobmetricalib-2.30`, `VERSION 2.30`, `API LEVEL 39`
--------------------------------------------
* **mobmetricalib-2.30.jar** - jar версия.
* **mobmetricalib-2.30.aar** - aar версия.
* **mobmetricalib-2.30-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.30

Version 2.30, Changelog
---------------------------
* Добавлена возможность инициализация метрики с использованием расширенной конфигурации, которая гарантирует, что все конфигурационные параметры будут применены с момента инициализации при попытке отправки самого первого события.
* Добавлен трекинг предустановленных на устройстве приложений.
* Незначительские оптимизации и улучшения.

`Mobmetricalib-2.21`, `VERSION 2.21`, `API LEVEL 36`
---------------------------
* **mobmetricalib-2.21.jar** - jar версия.
* **mobmetricalib-2.21.aar** - aar версия.
* **mobmetricalib-2.21-javadoc.jar**  - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.21

Версия 2.21, Список изменений
---------------------------
* Удален метод YandexMetrica.isMetricaProcess().
* По умолчанию, отключен сбор и отправка сведений об установленных на устройстве приложениях(method boolean setCollectInstalledApps(boolean collect)).
* Добавлен метод isCollectInstalledApps(), который показывает, включены ли сбор и отправка сведений об установленных на устройстве приложениях.
* Добавлен метод enableActivityAutoTracking(final Application application), который автоматически отслеживает активность пользователей, начиная с Android 4+ (является альтернативой методам YandexMetrica.onResumeActivity(Activity activity) и YandexMetrica.onPauseActivity(Activity activity)).
* Добавлен метод registerReferrerBroadcastReceivers(BroadcastReceiver...anotherReferrerReceivers), который дает возможность зарегистрировать GooglePlay INSTALL_REFERRER трекеры других систем аналитики.
* Добавлен метод setLogEnabled, который позволяет включить логирование работы AppMetrica SDK.
* Aar версия библиотеки теперь отдается по умолчанию из MavenCentral. Для использования jar версии через Gradle необходимо указать com.yandex.android:mobmetricalib-internal:2.21:jar.
* Исправлена ошибка, приводившая к падению с креш-логом java.lang.NullPointerException at com.yandex.metrica.impl.ob.f.b.

`Mobmetricalib-2.00`, `VERSION 2.00`, `API LEVEL 32`
--------------------------------------------
* **mobmetricalib-2.00.jar** - jar версия.
* **mobmetricalib-2.00.aar** - aar версия.
* **mobmetricalib-2.00-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 2.00

Версия 2.00, Список изменений
------------------------------
* Изменен формат API_KEY. Идентификатор приложения в новом формате доступен в веб-интерфейсе AppMetrica в режиме редактирования приложения.
* Метод инициализации библиотеки в приложении переименован c **initialize(android.content.Context, java.lang.String)** на **activate(android.content.Context, java.lang.String)**.
* Изменено время продолжительности сессии. По умолчанию значение составляет 10 секунд.
* Библиотека адаптирована к Android M.
* Повышена производительность и снижено энергопотребление.
* Удален устаревший метод **setReportsEnabled(boolean enabled)** — позволяет включить и отключить отправку отчетов.
* Удален устаревший метод **setDispatchPeriod(int dispatchPeriodSeconds)** — позволяет задать интервал в секундах между отправками накопившихся событий на сервер.
* Удален устаревший метод **setMaxReportsCount(int maxReportsCount)** — позволяет задать число событий в хранилище, при достижении которого происходит отправка всех накопившихся событий на сервер.
* Удален устаревший метод **startNewSessionManually()** — позволяет запустить новую сессию вручную.
* Удален устаревший метод **sendEventsBuffer()** — позволяет отправить все накопившиеся события, не дожидаясь автоматической отправки на сервер.

`Mobmetricalib-1.82`, `VERSION 1.82`, `API LEVEL 31`
--------------------------------------------

* **mobmetricalib-android-1.82.jar** - jar версия.
* **mobmetricalib-android-1.82.aar** - aar версия.
* **mobmetricalib-android-1.82-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.82

Версия 1.82, Список изменений
------------------------------

* Увеличен **metrica:api:level** до **31**. Обновите его значение в **AndroidManifest.xml**.
* Повышено качество подсчета статистики сессий и установок.
* Осуществлен переход на protobuf-nano — увеличена скорость работы и сокращен общий размер библиотеки. Если вы использовали библиотеку protobuf-2.5.0 для работы с библиотекой AppMetrica SDK, удалите ее.
* В файле AndroidManifest.xml не указываются
  provider:
  ```
  <provider
      android:name="FULL_PACKAGE_PATH_TO_YOUR_PROVIDER.MetricaContentProvider"
      android:authorities="ROOT_PACKAGE_PATH.MetricaContentProvider"
      android:enabled="true"
      android:exported="true"/>
  ```
  следующие intent-filter для com.yandex.metrica.MetricaEventHandler:
  ```
  <intent-filter>
      <action android:name="com.yandex.metrica.intent.action.SYNC"/>
  </intent-filter>

  <intent-filter>
      <action android:name="android.intent.action.PACKAGE_ADDED"/>
      <action android:name="android.intent.action.PACKAGE_DATA_CLEARED"/>
      <data android:scheme="package"/>
  </intent-filter>
  ```
* Для работы библиотеки AppMetrica SDK не требуется создавать в пакете приложения собственный класс провайдера с названием MetricaContentProvider, наследующий класс com.yandex.metrica.MetricaContentProvider. Удалите его из своего приложения.
* Добавлена возможность [передавать дополнительные данные](https://tech.yandex.ru/metrica-mobile-sdk/doc/mobile-sdk-dg/concepts/android-operations-docpage/#environment-value) об аварийных остановках приложения.


`Mobmetricalib-1.65`, `VERSION 1.65`, `API LEVEL 21`
--------------------------------------------

* **mobmetricalib-android-1.65-nolibs.jar** - Версия без **protobuf** внутри.
* **mobmetricalib-android-1.65-wlibs.jar** - Версия с **protobuf-2.5.0** внутри.
* **mobmetricalib-android-1.65-javadoc.jar** - **Java**-документация, которую вы можете подключить к библиотеке.
* **protobuf-java-2.5.0.jar** - **protobuf** библиотека для **mobmetricalib-android-1.65-nolibs.jar**, версия **2.5.0**.
* **native** - нативные библиотеки.

AppMetrica SDK доступна и как maven-артефакт на maven-central:

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

AppMetrica SDK доступна и как maven-артефакт на maven-central:

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

AppMetrica SDK доступна и как maven-артефакт на maven-central:

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

AppMetrica SDK доступна и как maven-артефакт на maven-central:

* **groupId**: com.yandex.android
* **artifactId**: mobmetricalib
* **version**: 1.0

Лицензия
---------

Лицензионное соглашение по использованию **AppMetrica SDK** доступно по следующей ссылке [http://legal.yandex.ru/metrica_termsofuse/](http://legal.yandex.ru/metrica_termsofuse/).

