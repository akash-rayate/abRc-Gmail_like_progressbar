abRc-Gmail-like-progressbar
===========================

Progress Bar, called as ButteryProgressBar by Google used in Gmail application.

Recently with release of Android 4.4 a.k.a. Android Kit-Kat. They reused lots of code from Gmail to make default email client application. While going through android source code, found this very interesting class, ButteryProgressBar.java that can be reused to show progress bar in Gmail application.

Original Source can be found here https://android.googlesource.com/platform/packages/apps/UnifiedEmail/+/kitkQ-release/src/com/android/mail/ui/ButteryProgressBar.java

This class can be used in Android 3.0 and above without any code change, as this custom progress bar uses value animator, which is introduced in Android 3.0.

To use this progress bar with Android 2.x project's, use 'jake wharton nine old androids library+IBk- (https://github.com/JakeWharton/NineOldAndroids) to replace Android value animator.
  

