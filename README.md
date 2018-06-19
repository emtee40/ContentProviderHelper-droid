Content Provider Helper
=======================

... is a frontend to discover/view/query data of android content providers.

* [Original repository](https://github.com/jenzz/ContentProviderHelper) : Copyright (c) 2014-2016 Jens Driller under [MIT license](LICENSE-old-mit-jenzz)
* [Improvements in this repository](https://github.com/k3b/ContentProviderHelper) : Copyright (c) 2015-2016 k3b under [GNU GENERAL PUBLIC LICENSE Version 3 or later](LICENSE)

[<img src="https://f-droid.org/badge/get-it-on.png" alt="available on F-Droid app store" height="45">](https://f-droid.org/app/de.k3b.android.contentproviderhelper)

Description
-----------

Android content-providers are similar to database-tables. 
They have a name (aka "content:" uri), 
columns and they can be queried similar to Sql.

Android uses 
[https://developer.android.com/guide/topics/providers/content-providers.html content-providers]
as api to manage global accessable data (i.e. Images, Telephone-book, SMS, ...).

ContentProviderHelper is a frontend to query installed content-providers.

You can add and delete your own content URIs manually or search for all available content providers on the device.

App permissions are set generously to provide maximum compatibility.

Requirements: Android-2.2 (api-8) or newer. (tested with android-2.2, 4.2, 4.4)

Program enhancements as merge-request are welcome.

* Predefined content providers see https://github.com/k3b/ContentProviderHelper/blob/FDroid/app/src/main/res/values/arrays.xml
* Granted permissions see https://github.com/k3b/ContentProviderHelper/blob/FDroid/app/src/main/AndroidManifest.xml
* What's New: see https://github.com/k3b/ContentProviderHelper/wiki/History

## See also

There is a similar devtool [intent-intercept](https://github.com/k3b/intent-intercept) to analyse android intent communication
