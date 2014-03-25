# Customization 

This is the base code.
```java
UpdateChecker checker = new UpdateChecker(this);
checker.start();
```
You can declare the store where your app is published on, the successful checks necessary to show notice, modify the notice(Dialog or Notification) and modify the notice icon.

##setStore(Store store)

```java
UpdateChecker checker = new UpdateChecker(this);
checker.setStore(Store.GOOGLE_PLAY)
checker.start();
```
Declare the store where your are is published on. If you publish in more than one store modify this value before exporting the .apk for every store.
Stores supported:

* Google Play Store = GOOGLE_PLAY
* Amazon App Store = AMAZON

More stores coming soon...

##setSuccessfulChecksRequired(int checksRequired)

```java
UpdateChecker checker = new UpdateChecker(this);
checker.setSuccessfulChecksRequired(1);
checker.start();
```
Set the checks successful necessary to show the Notice. Default is 5.

##setNotice(Notice notice)

```java
UpdateChecker checker = new UpdateChecker(this);
checker.setSuccessfulChecksRequired(1);
checker.start();
```
Set the checks successful necessary to show the Notice. Default is 5.


##setNoticeIcon(int noticeIconResId)

```java
UpdateChecker checker = new UpdateChecker(this);
checker.setSuccessfulChecksRequired(1);
checker.start();
```
Set the checks successful necessary to show the Notice. Default is 5.