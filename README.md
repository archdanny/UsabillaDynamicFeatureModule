# UsabillaDynamicFeatureModule

Usabilla dynamic feature module issue sample project

Steps to reproduce:

- uncheck the UsabillaDynamicFeatureModule.usabilla dynamic feature module 

  Don't deploy the usabilla feature module with the debug build. In a real world scenario the usabilla feature module will be installed on demand (after the initial install).

  <img width="711" alt="Screenshot 2022-07-27 at 08 35 21" src="https://user-images.githubusercontent.com/12575099/181179387-8ecf7e72-26d4-45db-928c-709fe25aa9f5.png">

- Run the app

  The app will crash with the following fatal exception:

```
java.lang.RuntimeException: Unable to get provider com.usabilla.sdk.ubform.utils.UbFileProvider: java.lang.ClassNotFoundException: Didn't find class "com.usabilla.sdk.ubform.utils.UbFileProvider"
```
