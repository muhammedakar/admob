## Admob Mobile App

You can easily log in to your admob account and see your earnings on your phone.

### Setup

- First you have to install webview Library into your Project. To do this, you can write the following code block in your console

    ``flutter pub add webview_flutter``
    
- And finally you have to import it

    ``import 'package:webview_flutter/webview_flutter.dart';``
    
### Configure

you need to configure the following script

    ``String admobUrl='You need to write yor admob URL in here';``

this code is in Lib>main.dart

### Build

you need to write the following code block in your terminal

    ``flutter build apk``

Finally you can find this app on this path

    ``YourProject/build/app/outputs/flutter-apk/app-release.apk``
