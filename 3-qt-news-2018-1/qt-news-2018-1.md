Что нового появилось/произошло в Qt за <strike>полгода</strike> почти год с [прошлой статьи](/post/331166). Релизы 5.9 и 5.10, а также новые инструменты, аддоны, платформы и переход на подписочную модель лицензирования.

![Релизы Qt](https://habrastorage.org/webt/pz/cx/xv/pzcxxvrp54-hjf15i0_vixhpcus.png)
<cut />
Я бы хотел писать о новостях чаще, чем раз в <strike>полгода</strike> год, но получается как получается. Эту статью я вообще начинал писать в январе, но закончить удалось только сейчас.

Сегодня содержание такое:

* [Конференции и выставки](#events)
    - [Qt Contributors Summit 2017](#cs)
    - [Qt World Summit 2017](#ws)
    - [Qt на Embedded World 2018](#ew)
* [Что вообще нового](#news)
    - [Изменения в коммерческой лицензии](#license)
    - [Изменения на сайте](#website)
    - [Релизы](#releases)
        + [5.9](#qt59)
        + [5.10](#qt510)
    - [Аддоны](#addons)
        + [Qt for Automation](#automation)
        + [Qt for Medical](#medical)
        + [Qt 3D Studio](#3ds)
        + [Qt Design Studio](#ds)
        + [Safe Renderer](#sr)
* [Roadmap](#roadmap)
    - [Qt на микроконтроллерах (MCU)](#mcu)
* [Вакансии](#job)
* [Заключение](#tehend)
* -
* [Дополнение №1 - Qt Quick Compiler](#add1)
* [Дополнение №2 - Про iOS стиль для Qt Quick Controls 2](#ios)

## <anchor>events</anchor>Конференции и выставки

### <anchor>cs</anchor>Qt Contributors Summit 2017

Это конференция разработчиков Qt. Не только тех, кто работает в The Qt Company (их даже было меньше половины участников), а вообще всех желающих, кто участвует в проекте.

В 2017 году [Qt Contributors Summit](https://wiki.qt.io/Qt_contributors_summit_2017) был совмещён с [Qt World Summit 2017](#ws), и проходил в Берлине. Программа и конспекты сессий опубликованы на [вики](https://wiki.qt.io/Qt_contributors_summit_2017_Program).

В этом году [было решено](http://blog.qt.io/blog/2018/03/09/qt-contributors-summit-2018/) провести конференцию в Осло, то есть World Summit на этот раз пройдёт отдельно.

### <anchor>ws</anchor>Qt World Summit 2017

Мероприятие (конференция), которое организует сама The Qt Company. В 2017 году саммит [прошёл](https://youtu.be/DNlUpyz6Zco) в Берлине. По числу посетителей получился рекорд - около 1000 человек (в прошлом было 800?).

В адресе страницы события (https://www.qtworldsummit.com) год не указан, потому, надо полагать, скоро эта ссылка начнёт указывать на саммит 2018 года (*уже указывает*), а 2017 уедет куда-нибудь в архив (*нет, просто куда-то дели*). Но пока не уехала (*уже уехала*) - можно посмотреть программу конференции и участников выставки. Там же можно было загрузить [мобильное приложение саммита](http://blog.qt.io/blog/2017/09/29/qt-world-summit-app-2017-open-source-live-now/), написанное на Qt (точнее, на [V-Play](https://v-play.net)), и поразиться тому, как оно тормозит и крашится на каждый чих, спасибо партнёрам-разработчикам. Почему мы сами который год не можем написать приложение для собственного саммита - непонятно.

[Все выступления с конференции](https://www.qt.io/qtws17-7409554659) опубликованы на YouTube.

<spoiler title="Список плейлистов">
* [Keynotes](https://www.youtube.com/playlist?list=PLizsthdRd0YwwuwmG-vl8IGtPdo67Hmsq):
    - Qt Design Principles and Roadmap, Lars Knoll, The Qt Company;
    - Modern C++, Herb Sutter;
    - Trends in Software and Business, Igor Beuker;
    - One Hundred Languages, Linda Liukas, Hello Ruby;
    - How Do You Measure What You Can’t See? Steven Goldfarb, ATLAS experiment, CERN;
    - Welcome to Qt World Summit 2017, Juha Varelius, The Qt Company;
    - Game Engine Evolution: From Tech to UX, Alex Montgomery, Amazon Lumberyard;
    - An IDE for Embedded Devices, Justin Howard, Qualcomm;
* [Business](https://www.youtube.com/playlist?list=PLizsthdRd0YydAsecSH8mGwubYiJZQ_tS):
    - Cut development time and cost with Qt and QML, Thomas Boutroue, Independent Qt Expert;
    - The Evolution of the LGPL License Agreement, Paul Criswell, Independent General Counsel;
    - Applying Spatial Analytics to Unlock the Power of your Data, Eric Bader, Esri;
    - Qt vs. Web – Total Cost of Ownership, Burkhard Stubert, Embedded Use;
    - System-on-Modules HMI and M2M solutions development, Rimac Automobili, Toradex;
    - Success with mobile first in a real business, Roland Wienen, caseIC-SYS Informationssysteme;
    - First experience with Qt for Mobile: our journey, Bogdan Ogrean, FORTecH;
    - One developer, Three products, Three platforms, Nuno Filipe Magalhães Santos, Imaginando;
    - Investing into Software Technologies, Petteri Holländer, The Qt Company;
    - Interactive DOOH software with Qt libraries, Ionut Alexandrescu, The Qt Company;
* [App Dev](https://www.youtube.com/playlist?list=PLizsthdRd0YwsE6mU1ZF03gq-JMAfE56N):
    - Take a walk on the PySide, Friedemann Kleint, The Qt Company;
    - A Cute app deserves a Clean architecture, Marco Piccolino, Maply;
    - Improve your productivity with Clang tools. Olivier Goffart, Woboq GmbH;
    - RESTful API description languages, Alexey Rusakov;
    - QtBluetooth on mobile devices - A dragon guide, Mathias Hasselmann, KDAB;
    - Technical Tips and Examples for Development &amp; Testing, Christian Feldbacher, V-Play;
    - Introduction to User Experience Design for Developers, Jeff LeBlanc, ICS;
    - Test coverage of Qt C++ and QML, Harri Porten, froglogic;
    - The Pre-User and the Unified User Experience, Jeffrey Brendecke Software Services;
    - Android &amp; iOS - put your app on a diet, Maciej Węglarczyk, GameDesire;
    - No Limits: HowTo make a more complicated mobile business APP, Ekkehard Gentz;
    - Inside The Qt Object Model, Simon Hausmann, The Qt Company;
    - QML For C++ Developers, Bo Thorsen, Viking Software;
* [Embedded](https://www.youtube.com/playlist?list=PLizsthdRd0YytBFjg4K0rvbcyoALv-NXG):
    - Using Qt to Build Next Generation Intuitive High End Cameras, Richard Röjfors, Hasselblad;
    - Qt Wayland Compositor: Creating multi-process user interface, Johan Helsing, The Qt Company;
    - Accelerating Time to Market for Embedded Device, Jouko Luukas The Qt Company;
    - Gestures Handling in Qt, Bo Thorsen Viking Software;
    - Qt for Embedded Device creation - future direction, Marko Finnig, The Qt Company;
    - KNX in the IoT world, Dries Verbrugge, KNX;
    - Using Virtual Keyboards on Qt Embedded Devices, Jan Arne Petersen, KDAB;
* [Graphics and 3D](https://www.youtube.com/playlist?list=PLizsthdRd0Ywn3mQpszfmnIbDke33NQok):
    - Integrating OpenGL with Qt Quick 2 applications, Giuseppe D'Angelo, KDAB;
    - Integrating out of process graphical content into a QtQuick scene, Giulio Camuffo, KDAB;
    - Creating User Interfaces for Virtual Reality with Qt, Andy Nichols, The Qt Company;
    - Breathing life into your applications: Animation with Qt 3D, Sean Harmer, KDAB;
    - Modern Graphics APIs in Qt: Vulkan and friends, Laszlo Agocs, The Qt Company;
    - Earth rendering with Qt 3D, Paul Lemire - KDAB;
    - Qt in Use in Fortune 500 Companies, V-Play;
    - Qt 3D as a Runtime Enabler, Laszlo Agocs, The Qt Company;
    - What's new in Qt 3D? Sean Harmer, KDAB;
    - Creating 3D User Interfaces with Qt 3D Studio, Sami Makkonen, The Qt Company;
    - [Interacting with 3D content, Mike Krus, KDAB](https://youtu.be/dpj2dZQA63c);
* [Medical](https://www.youtube.com/playlist?list=PLizsthdRd0Ywe1Ivnomkz-R4hILUUJ4xk):
    - Technical Overview of Qt in Medical devices, Ionut Alexandrescu, The Qt Company;
    - Building a Human Machine Interface for the medical IoT, Jereme Givens-Lamothe, DocBox;
    - The Present and Future of Qt in the Medical Industry, Roger Mazzella, The Qt Company;
    - Imaging Tissue Architecture: The Next Frontier in Battling Cancer, Michel Nederlof, QIS;
    - Communicating with Thoughts, Matthias Hohmann, Max Planck Institute;
* [Technical Deep Dive](https://www.youtube.com/playlist?list=PLizsthdRd0YxbiEnZqIQgtQerte6ftahf):
    - QObject Deep Dive, Bo Thorsen, Viking Software;
    - Qbs – Build Systems State of the Union, Jake Petroules, The Qt Company;
    - QtLocation 5.9: from tilted maps to pluggable engines, Paolo Angelelli, The Qt Company;
    - Pointer Handlers for fluid applications in Qt Quick, Shawn Rutledge, The Qt Company;
    - QStringViews, QStringViews everywhere, Marc Mutz, KDAB;
    - Multithreading with Qt - Giuseppe D'Angelo, KDAB;
* [Industrial Automation](https://www.youtube.com/playlist?list=PLizsthdRd0Yx2An9JhYMGrQTFrwrvEtcM):
    - QtWebGL, Jesus Fernandez Prieto, The Qt Company;
    - Securing Qt based Linux Devices, Maciej Halasz, TimeSys;
    - Device Tailored Compositors with QtWayland, Andreas Cord-Landwehr, CLAAS E-Systems;
    - Practical Qt Lite, Frank Meerkötter, basysKom;
    - Boot Time Optimization for Qt-powered Devices, S. Agner, R. Avila, Toradex/The Qt Company;
    - Designing the Internet of Things with Microsoft, Sylvain Ekel, Microsoft;
    - QtKnx: the new Qt module dedicated to home automation, The Qt Company Lucie Gerard;
    - Qt and Mqtt, Maurice Kalinowski, The Qt Company;
    - How CoAP standard makes your IoT talk with Qt, Adrien Leravat, Witekio;
    - LPWAN will make the IoT Revolution Real, Massimo Santoli, Gimasi;
    - ChargePoint EV Charging: One UI to rule them all, Matthew Hungerford, Chargepoint;
    - Qt for Automation, Lars König, The Qt Company;
    - Intro to the WebOS QtWayland Compositor, Florian Haenel, LG Electronics;
* [Automotive](https://www.youtube.com/playlist?list=PLizsthdRd0YzmVTFsKYyN7TwanWt57AkU):
    - Functional safety with Qt and Qt Safe Renderer, Tuukka Turunen, The Qt Company;
    - Plugin-based IVI Architectures with Qt, Krzysztof Krzewniak Vladimir Moolle, ICS;
    - Communication with slave device over CAN bus from embedded, Nazar Babik, Viking Software;
    - QtWS17 - Maximize your creativity and quality for automotive HMIs, Hirotaka Suzuki, sdtech;
    - Automotive navigation with Mapbox GL and QtLocation, Bruno de Oliveira Abinader, Mapbox;
    - QML-driven HMI Architectures for Rolling Embedded Devices, Christoph Sterz, KDAB;
    - GammaRay - Taking a deeper look into your Qt application, Volker Krause, KDAB;
    - Qt for gesture control and body tracking applications, Sascha Klement, Gestion;
    - Modbus with Qt, Morten Winkler Jørgensen, Viking Software;
    - Future of Vehicle HMI Systems, Takayuki Tanabe, Panasonic ITS;
    - Behind the scenes of a show car: Rapid UI/UX prototyping, Alex Hilliger, Daimler;
    - Complex Event Processing of An Electric Car In A Simple Way, Müge Kural, Eteration;
    - QtIVI: Integrating and Testing vehicle functions with Qt Automotive Suite, KDAB;
    - Under the Hood of Qt Automotive Suite After One Year of Hacking, Johan Thelin, Luxoft;
    - Race to digital cockpits – win with Qt, Tero Marjamäki, The Qt Company.
</spoiler>

На выставке в центре зала показывали новые разработки: 

* [Qt KNX](https://youtu.be/o__0e3dnmL8);
* [Qt MQTT](https://youtu.be/0bUaB-X9m50);
* [Qt WebGL streaming](https://youtu.be/Ik_nXZv86lQ);
* [Qt Quick Controls Imagine Style](https://youtu.be/WGmjObx6AkM);
* [Qt Safe Renderer](https://youtu.be/JeMZJrnSfZ0);
* [Qt 3D Studio](https://youtu.be/401nU1ULONE).

Вокруг стояли стенды партнёров и клиентов, которые показывали что-то из своего. Например, Mercedes-Benz прикатили вот такой [концепт-кар](https://youtu.be/gRYtG30yHxo).

Начиная с 2018 года, саммитов теперь несколько и проходить они будут в разное время и разных местах. В этом году будет 2: американский (Бостон) и европейский (Берлин) - оба ближе к концу года. Далее планируется добавить третий для стран Азии (возможно, в Токио).

### <anchor>ew</anchor>Qt на Embedded World 2018

Как и в [прошлом году](/post/325198/#ew), мы [были](https://youtu.be/8Rm0NnLUqiQ) на выставке Embedded World в Нюрнберге.

Из интересных демо можно выделить:

* [AirServer](https://youtu.be/mNCuQcFKIUc);
* [сравнение Qt и JavaFX](https://youtu.be/Kh6K-yEp_JY);
* [создание HMI "на лету"](https://youtu.be/hYyPCO8LXLY);
* [Qt на i.MX6 ULL без аппаратного ускорения](https://youtu.be/HHd-JJ1NPX4);
* [экспериментальный порт Qt на MCU](https://youtu.be/1ySTyBz2F0k) (о нём [ниже](#mcu)).

## <anchor>news</anchor>Что вообще нового

### <anchor>license</anchor>Изменения в коммерческой лицензии

Начиная с января 2018, лицензии Qt для [всех продуктов](/post/331166/#products) перешли на модель подписки (term-based), то есть больше нельзя приобрести "пожизненную" лицензию. Вообще, для тех кто до этого и так "продлял" лицензию каждый год (для обновлений и поддержки) ничего особо не поменялось, потому что фактически это уже и была подписочная модель. Но есть отличие: раньше можно было не продлять лицензию и спокойно продолжать разрабатывать/распространять свой продукт (сама лицензия-то пожизненная), но теперь условия лицензионного соглашения это запрещают - у вас должна быть хотя бы одна активная подписка, иначе нельзя ни вести разработку, ни продавать уже готовый продукт. Вот это поворот!

Я представляю, что вы хотите сказать мне на тему лицензий-подписок, я и сам всё это не раз говорил разработчикам тех или иных приложений ([Ulysses](https://medium.com/building-ulysses/why-were-switching-ulysses-to-subscription-47f80b07a9cd), например), но не я это придумал, я только доставляю новость. Но вообще, для фреймворка подписочная лицензия выглядит более-менее оправданной (по сравнению с подпиской на текстовый редактор).

Из положительных изменений - если вы приобретаете Device Creation, то лицензия Application Development теперь входит в его состав. Кроме того, раньше для RTOS (операционных систем реального времени) была отдельная цена для каждой, а теперь всё включено.

Всё это отражено в новом лицензионном соглашении ([License Agreement version 4.0](http://qt.io/terms-conditions/), которое кстати больше не разделяется на отдельные соглашения для Application Development и Device Creation.

### <anchor>website</anchor>Изменения на сайте

Работа над "улучшением" вебсайта не останавливается ни на минуту, и длина [списка](https://habrastorage.org/webt/lo/gu/kc/logukctsydoptse8yr0s-txipp8.png) подключённых сторонних скриптов уже больше километра. Анимация всего подряд позволила достичь утилизации процессора пользователя на уровне [80-90%](https://habrastorage.org/webt/z4/zo/jd/z4zojdk9lu1sflwvzofv5gv90ve.png) и соответствующего энергопотребления, что, однако, не осталось незамеченным для посетителей, потому сейчас идёт героическая борьба за оптимизацию всех этих красот.

Если вы задавались вопросом, почему какие-то разделы сайта лежат на поддомене `www`, а какие-то на `www1`, то это потому что на сайте используется две разных CMS. Ну потому что вот так.

Где-то в мае 2017 очередной эффективный менеджер решил запрятать Open Source загрузки куда подальше и поставить побольше кнопок Buy Qt ("купи лицензию"). Запрятали настолько хорошо, что нам даже стали присылать письма с вопросом "*Почему вы удалили Open Source?!*". К счастью, встретив критику как от Open Source сообщества, так и внутри компании, через каких-то полгода это изменение пересмотрели и вернули всё почти как было.

Появился новый раздел - [Qt Resource Center](https://resources.qt.io), такой агрегатор различных ресурсов (статьи, видео, "истории успеха" и т.д.) с разделением на категории и поиском. Теперь можно, например, разом заполучить [все твиты](https://resources.qt.io/twitter-all-tweets?onbrand) официального аккаунта <strike>(но зачем)</strike>.

### <anchor>releases</anchor>Релизы

#### <anchor>qt59</anchor>Qt 5.9

31 мая 2017 [вышел Qt 5.9](http://blog.qt.io/blog/2017/05/31/qt-5-9-released/). Он же следующий после Qt 5.6 релиз LTS - с долгосрочной поддержкой (3 года).

В [статье на OpenNET](http://www.opennet.ru/opennews/art.shtml?num=46632) уже есть отличный обзор.

Кстати, это вроде бы первый релиз со времён Qt 4.7, для которого было выпущено более трёх корректирующих (minor) релизов (текущая версия 5.9.5).

И начиная с этой версии, корректирующие (minor) релизы теперь опять не обновляют текущий, а устанавливаются отдельно:

![Корректирующие релизы Qt](https://habrastorage.org/webt/y5/9v/yd/y59vydtivei2thrwyhaegsdk3aw.png)

#### <anchor>qt510</anchor>Qt 5.10

7 декабря 2017 [вышел Qt 5.10](http://blog.qt.io/blog/2017/12/07/qt-5-10-released/).

И опять прекрасный обзор релиза в [статье на OpenNET](http://www.opennet.ru/opennews/art.shtml?num=47701).

### <anchor>addons</anchor>Аддоны

В дополнение к обычным (базовым) лицензиям (Application Development и Device Creation) теперь будут появляться "аддоны". Вообще, хотели сделать что-то вроде магазина аддонов/плагинов (как [qpm](https://www.qpm.io), только официальный), но дальше идеи пока не пошло, потому они будут просто добавляться в установщике.

Если взять за основу [схему из прошлой статьи](https://hsto.org/web/eb0/7ac/83c/eb07ac83cbad4b189dcb13186aeb6658.png), то новая выглядит так:

![Схема лицензирования Qt](https://habrastorage.org/webt/ei/y2/by/eiy2bybjcnr_xzlvuzltez5nihk.png)

И без того непростая структура лицензирования стала ещё сложнее. Если попытаться объяснить всё вкратце, то аддоны в "стандартные" лицензии не входят и продаются за дополнительные деньги. Учитывая, что не всем интересно читать про коммерческие лицензии, я подробно расписывать не буду (кроме того, надо и отделу продаж дать поработать).

Если же вы используете Qt под Open Source, то для вас ничего не поменялось - просто добавились новые библиотеки и инструменты.

#### <anchor>automation</anchor>Qt for Automation

[Qt for Automation](http://doc.qt.io/QtForAutomation/index.html) - первый аддон, [объявленный в августе 2017](http://blog.qt.io/blog/2017/08/14/qt-for-automation/). Представляет собой пакет библиотек для построения решений для так называемых [Industry 4.0](https://en.wikipedia.org/wiki/Industry_4.0) и [M2M](https://en.wikipedia.org/wiki/Machine_to_machine).

На данный момент (Qt 5.10) в состав аддона входят:

* [Qt MQTT](https://doc.qt.io/QtMQTT/index.html);
* [Qt KNX](https://doc.qt.io/QtKNX/index.html).

С Qt 5.11 должен появиться [OPC UA](https://en.wikipedia.org/wiki/OPC_Unified_Architecture), затем [CoAP](https://en.wikipedia.org/wiki/Constrained_Application_Protocol) и другие. Кроме самих библиотек также предоставляется пакет сервисных услуг по установке/настройке/обучению.

#### <anchor>medical</anchor>Qt for Medical

Пока больше [промо](https://www.qt.io/qt-in-medical/), чем реальный продукт/аддон. Ну а так, конечно, планируется добавление функционала, специфичного для медицинской индустрии, например работа с форматом [DICOM](https://en.wikipedia.org/wiki/DICOM) (хотя конкретно для этого формата уже есть [сторонние реализации](http://qtdcm.gforge.inria.fr)).

На самом деле, для связанных с медициной проектов больше важна сертификация, чем фичи, и потому мы теперь входим в состав таких ассоциаций и альянсов как [AdvaMed](https://www.advamed.org), [Qmed](https://directory.qmed.com) и [MassMEDIC](https://www.massmedic.com). Я от этой индустрии далёк, потому о реальной пользе от вхождения в эти альянсы ничего сказать не могу.

#### <anchor>3ds</anchor>Qt 3D Studio

В октябре 2017 исходники Qt 3D Studio были наконец-то [опубликованы](http://blog.qt.io/blog/2017/10/11/qt-3d-studio-source-code-pre-release-snapshots-available/) ([статья на OpenNET](http://www.opennet.ru/opennews/art.shtml?num=47372)). Почему не опубликовали сразу после получения их от Nvidia - потому что там всё было написано на MFC, и решили сначала портировать это на Qt.

Через месяц после публикации исходников [выпустили](http://blog.qt.io/blog/2017/11/30/qt-3d-studio-1-0-released/) и версию 1.0. В ней всё ещё используется собственный 3D движок за авторством Nvidia, но уже почти закончена [работа](http://blog.qt.io/blog/2017/12/11/towards-improved-qt-3d-studio-runtime/) по переводу его на уже существующий [Qt 3D](https://doc.qt.io/qt-5.10/qt3d-index.html) (потому что хватит плодить движки).

Qt 3D Studio и её рантайм доступны как под коммерческой лицензией, так и под GPLv3 (под LGPLv3 нет). Сама студия бесплатная, но использование её рантайма в вашем коммерческом приложении увеличивает стоимость лицензий на распространение (если таковые полагаются).

#### <anchor>ds</anchor>Qt Design Studio

Вообще, это пока полусекретный проект, но раз на официальном канале опубликовали [это видео](https://youtu.be/wRMkfdZ_ZxI), то получается уже и не очень секретный.

Но на всякий случай, пока без особых подробностей. Когда-то скоро должен состояться официальный анонс (через пару недель?) и первая публичная бета-версия (в июне?).

#### <anchor>sr</anchor>Qt Safe Renderer

[Qt Safe Renderer](http://blog.qt.io/blog/2017/05/22/functional-safety-qt-safe-renderer/) - это сертифицированный (IEC 61508 и производные стандарты [functional safety](https://www.qt.io/functional-safety-and-qt)) рендерер графики. Фактически отдельное приложение, которое рендерит критичные элементы GUI независимо от главного приложения. И если главное приложение "помрёт", то эти элементы продолжат отображаться на экране.

Очевидные сферы применения: автомобильная и медицинская индустрии, где зависание главного приложения на скорости 200 км/ч или во время хирургической операции чревато негативными последствиями.

Пример использования в цифровом инструментальном кластере (дашборде) автомобиля:

![Qt Safe safe-renderer](https://habrastorage.org/webt/un/3i/sh/un3ishtza1tgpe9xuoexdqvfmqs.png)

Если интересно, я могу написать отдельную статью с "живым" примером на железе под управлением QNX (в конце статьи будет опрос). Но сразу хочу сказать, что Safe Renderer в Open Source не попадёт и будет доступен только за деньги (и очень немаленькие).

## <anchor>roadmap</anchor>Roadmap

* Скорый релиз [PySide](http://blog.qt.io/blog/2018/05/04/hello-qt-for-python/) - использование Qt из Python;
* [Qt Quick Pointer Handlers](http://blog.qt.io/blog/2017/11/23/say-hello-qt-quick-pointer-handlers/) - "более лучший" мультитач и вообще работа с тачскринами;
* [Qt for WebAssembly](http://blog.qt.io/blog/2018/04/23/beta-qt-webassembly-technology-preview/) - запуск Qt приложений в браузере (<strike>не знаю, зачем</strike> могу попытаться объяснить, зачем);
* Переработка (new compiler pipeline) QML Engine;
* [Поддержка формата KTX](https://blog.qt.io/blog/2018/05/07/compressed-textures-in-qt-5-11/); 
* Qt 5.11 будет в мае-июне 2018 (уже вышел RC - release candidate);
* Следующий LTS релиз будет Qt 5.12 (ожидается в конце осени 2018). Минимум новых фич, фокус на надёжность и производительность;
* Qt 6 ожидается очень примерно года через два;
    - Всё ещё в силе план перейти с [qmake](http://doc.qt.io/qt-5/qmake-manual.html) на [Qbs](http://doc.qt.io/qbs/).

### <anchor>mcu</anchor>Qt на микроконтроллерах (MCU)

Очень часто спрашивают, можно ли использовать Qt для разработки ПО, и частности GUI, на микроконтроллерах.

И вот мы провели исследование, завершившееся портированием Qt под операционную систему реального времени [RTEMS](https://en.wikipedia.org/wiki/RTEMS) и оптимизацией сборки Qt для запуска на микроконтроллерах STM32F469, STM32F746 и STM32F769.

О результатах исследования недавно вышел [пост](http://blog.qt.io/blog/2018/05/03/qt-microncontrollers-mcu/) в официальном блоге, и кстати говоря, оригинал этого поста вообще-то был написан на русском, так что с минимальными усилиями его можно опубликовать и на Хабре (об этом тоже будет опрос в конце статьи).

Пока идёт сбор отзывов от клиентов, кто куда и что хотел бы портировать, и потом на основе пожеланий будет планироваться дальнейшее развитие.

## <anchor>job</anchor>Вакансии

В этом году вакансий не так много, как в прошлом, но поиск новых сотрудников [продолжается](https://www1.qt.io/careers/). Так что если что-то заинтересовало, можете написать мне, и я расскажу подробнее.

Вот например уже больше полутора лет (серьёзно) в берлинский офис разыскивается [sales engineer](https://www1.qt.io/careers/careers-sales-engineer-emea/) - это такой человек, который разбирается в Qt и при этом может разговаривать с людьми (клиентами) и отвечать на их технические вопросы. Уже настолько отчаялись найти, что <strike>возьмём кого угодно</strike> будем рады любым кандидатам. Кстати, не самый плохой способ завести трактор, хотя наверное мне не стоит такое говорить. Осложняется вакансия тем, что так как позиция в Берлине, то очень желательно знание ещё и немецкого.

Всего в 2017 наняли около 130 человек. Люди приходят из всех (включая русскоязычные) частей планеты, никаких рассовых/религиозных/половых предпочтений/предрассудков нет (кроме того что на позиции эффективных менеджеров берут <strike>только</strike> чаще финнов <strike>(шутка)</strike>).

## <anchor>tehend</anchor>Заключение

Если хотите узнать о чём-то подробнее, пишите комментарии, я постараюсь ответить сам или узнать у тех кто знает.

---

## <anchor>add1</anchor>Дополнение №1 - Про Qt Quick Compiler

Сначала Qt Quick Compiler [обещали](http://blog.qt.io/blog/2016/01/13/new-agreement-with-the-kde-free-qt-foundation/) отдать в Open Source с релизом Qt 5.8. Правда, там было сказано "*...integrate the Qt Quick Compiler functionality*", то есть как бы не сам Qt Quick Compiler, а только его функциональность. Забегая вперёд, это и так и не так одновременно.

В Qt 5.8 появился механизм кэширования QML, который [анонсировался](http://blog.qt.io/blog/2017/05/31/performance-improvements-with-qt-5-9-lts/) как "замена" Qt Quick Compiler. Сам Qt Quick Compiler при этом никуда не делся и был доступен для обладателей коммерческих лицензий как в релизе 5.8, так и в 5.9, так и в 5.10. В 5.11 ситуация изменится, об этом чуть ниже.

Почему кэширование QML назвали заменой Qt Quick Compiler? Потому что оно генерирует байт-код и складывает его в файлы кэша (`.qmlc` для QML и `.jsc` для JavaScript), и вот этот байт-код оказался более "производительным", чем промежуточный (intermediate/untyped) C++ код, который генерировался Qt Quick Compiler'ом. Так что QML кэшинг действительно является заменой (и хорошей) "старого" Qt Quick Compiler'а.

Теперь про Open Source. Исходники Qt Quick Compiler открыты не будут, потому что менеджмент решил, что в этом случае народ сможет его портировать на старые версии Qt, где этот компонент был доступен только коммерческим пользователям, которые могут от этого огорчиться.

Почему я назвал Qt Quick Compiler "старым" и вообще использовал прошедшее время? Потому что он прекращает своё существование как генератор C++ кода из QML/JS, и в Qt 5.11 он станет доступен во-первых, всем пользователям, а не только обладателям коммерческой лицензии, а во-вторых, его реализация будет существенно отличаться от текущей, и он больше не будет генерировать C++ код, а будет генерировать тот же байт-код, что и QML кэшинг.

В чём же тогда разница между "новым" Qt Quick Compiler'ом и QML кэшингом, раз они дают один и тот же байт-код? Пересказывая вкратце [документацию релиза 5.11](https://doc-snapshots.qt.io/qt5-5.11/qtquick-deployment.html), "новый" Qt Quick Compiler предоставляет следующие возможности, которых нет у QML кэшинга:

1. Первоначальное "кэширование" QML происходит не с первым запуском приложения, а во время сборки приложения, как дополнительный шаг компиляции. То есть первый старт приложения уже будет "оптимизированным";
2. Благодаря этому синтаксические ошибки QML можно отлавливать уже во время сборки приложения, а не получать их в рантайме;
3. Среди файлов приложения не будут валяться открытые текстовые QML, что хоть и слабенько, но всё-таки способствует защищённости приложения.

Проще говоря, этим "новый" Qt Quick Compiler повторяет функционал "старого".

Ну и соответственно не будет смысла использовать одновременно и QML кэшинг, и Qt Quick Compiler. Точнее, у вас этого и не получится, потому что они взаимоисключаются. QML кэшинг работает из коробки в неявном виде, а Qt Quick Compiler нужно явным образом задействовать, в результате чего механизм кэшинга просто "отключится" (что логично). И кстати, понятное дело, теперь между ними нет разницы в производительности, так как в сути своей оба механизма делают одно и то же.

Почему бы тогда просто не использовать всегда Qt Quick Compiler, что за смысл тогда в QML кэшинге? Как указано в документации, у Qt Quick Compiler'а будет ряд ограничений, которые подойдут не всем проектам, потому какие-то проекты будут полагаться на один механизм, а какие-то смогут воспользоваться другим.

Ещё одно отличие - если используя "старый" Qt Quick Compiler вы не могли использовать JIT (потому что результатом его работы был C++ код (хотя тут есть ещё и второе дно)), то "новый" Qt Quick Compiler а также QML кэшинг смогут использовать также и JIT для особо востребованных фрагментов кода. Короче говоря, до Qt 5.11 JIT ничего не давал поверх уже "скомпилированного" QML, а начиная с 5.11 - будет.

Кстати, тут оказалось, что у нас как раз готовится статья на эту тему, так что скоро сможете почитать в [официальном блоге](https://blog.qt.io/dev/) (там кстати есть RSS) более грамотное/корректное объяснение происходящего.

## <anchor>ios</anchor>Про iOS стиль для Qt Quick Controls 2

Как таковой стиль был более-менее готов ещё в феврале 2016:

![QQC2 iOS style](https://habrastorage.org/webt/zg/wz/0r/zgwz0rs-uwapgmirnuxjroj66po.png)

Но в релиз не попал по ряду причин, включая и юридические.

Apple совершенно не против приложений, которые не выглядят "нативно", то есть можно творить любое безумие и всё будет нормально (кроме количества звездей от ваших пользователей). Но как только речь заходит о "родном" стиле iOS, то там всё должно выглядеть идеально и строго соответствовать гайдлайнам.

Дизайны/гайдлайны стилей Material (Android) и Universal (Windows) не только находятся в общем доступе (мне так сказали), но также и не ограничены какой-то одной платформой, и Google как и Microsoft напротив всячески поощряют распространение своих дизайнов на все платформы, не только мобильные, но и десктопы с вебом, включая платформы конкурентов. Всего этого нельзя сказать про iOS.

Ну и потому любая попытка "воссоздать" стиль iOS будет лишь имитацией и подражанием оригинальному стилю. Говоря о "look and feel", часть, которая "look", уже достаточна сложна для воссоздания, но часть "feel" - вообще нереальна. То есть GUI может и будет выглядеть "родным", но первый же свайп / скролл / пинч выдадут "подделку".

Также в результате исследования оказалось, что это чревато как раз-таки юридическими проблемами - если мы будем выдавать наш стиль за "родной" стиль iOS, то Apple может сказать что-то неприятное. Плюс приложения наших клиентов могут получить отказ в App Store по причине несоответствия UX гайдлайнам.

Кроме того, всплыл ещё один интересный момент. Так как наша реализация стиля iOS разумеется запилена на Qt, который вообще-то является кроссплатформенным фреймворком, то внезапно китайские "производители" клонов iPhone/iPad смогут использовать наш стиль в своих ведроподелиях. Честно говоря, я не понимаю, почему нас это должно волновать, но вот тем не менее, мне сказали, что это проблема.

Отличным решением может стать [вот этот проект](http://blog.qt.io/blog/2017/02/06/native-look-feel/), я его уже упоминал в прошлых статьях. Вкратце, это использование реально "родного" GUI платформы (а не "воссозданного" стиля) через QML (или C++, если угодно). Но из того, что я вижу во внутреннем трекере, последняя активность по этой задаче была в октябре 2017 и с тех пор тишина.

Теперь про то, что предлагает [V-Play](https://v-play.net). Я, честно говоря, не знаю, и команда тоже не ответила. Но учитывая вышесказанное, есть два варианта:
1. Они пошли по пути воссоздания и реверс-инжениринга стиля iOS, и то что они предлагают, это просто реплика, и соответственно они либо их клиенты потенциально могут ожидать проблем от Apple. Я прошу учесть, что я ни в чём не обвиняю V-Play, а просто строю предположения;
2. Они реализовали упомянутый в предыдущем абзаце проект - то есть работают с настоящим GUI iOS через QML-обёртку.

Можно попытаться связаться с V-Play и спросить у них самих. Но они могут не захотеть делиться такой информацией.
