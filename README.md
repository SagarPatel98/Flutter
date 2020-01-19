# Flutter Demo App 

A new Flutter project.

#### Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# Flutter Installation Guide for Window

To install and run Flutter, your development environment must meet these minimum requirements:

* Operating Systems: Windows 7 SP1 or later (64-bit)
* Disk Space: 400 MB (does not include disk space for IDE/tools).
* Tools: Flutter depends on these tools being available in your environment.
* Windows PowerShell 5.0 or newer (this is pre-installed with Windows 10)
* Git for Windows 2.x, with the Use Git from the Windows Command Prompt option

#### Step-1 : Get the Flutter SDK
Using git clone the following repository
 **git clone https://github.com/flutter/flutter.git**
#### Step-2 : Update the Path
From the Start search bar, enter ‘env’ and select Edit environment variables for your account.
Under User variables check if there is an entry called Path:
If the entry exists, append the full path to flutter\bin using ; as a separator from existing values.
If the entry doesn’t exist, create a new user variable named Path with the full path to flutter\bin as its value.
#### Step-3 : Setup the Editor
1) If you are using the **Android Studio** follow the following step to get the flutter plugin
    * Start Android Studio.
    * Open plugin preferences (Preferences > Plugins on macOS, File > Settings > Plugins on Windows & Linux).
    * Select Marketplace, select the Flutter plugin and click Install.
    * Click Yes when prompted to install the Dart plugin.
    * Click Restart when prompted.
2) If you are using the **Visual Studio Code** Editor then follow the following step for flutter plugin
    * Start VS Code.
    * Invoke View > Command Palette….
    * Type “install”, and select Extensions: Install Extensions.
    * Type “flutter” in the extensions search field, select Flutter in the list, and click Install. This also installs the required      Dart plugin.
#### Step-4 : Connect the Mobile device or enable or on and emulator if available for app deployment.
#### Step-5 : Run flutter doctor to validate all the requirements for Flutter is available or not.

# Creating the First Flutter App
1) Android Studio
         * Open the IDE and select Start a new Flutter project.
         * Select Flutter Application as the project type. Then click Next.
         * Verify the Flutter SDK path specifies the SDK’s location (select Install SDK… if the text field is blank).
         * Enter a project name (for example, myapp). Then click Next.
         * Click Finish.
         * Wait for Android Studio to install the SDK and create the project.
         
  To run the app in android studio **run>run**
 
 2) Visual Studio Code Editor
         * Invoke View > Command Palette.
         * Type “flutter”, and select the Flutter: New Project.
         * Enter a project name, such as myapp, and press Enter.
         * Create or select the parent directory for the new project folder.
         * Wait for project creation to complete and the main.dart file to appear.
         
  to run the app in visual editor type **flutter run** inside the project directory.


## Below is the screenshot of Flutter First App demo deployment.
<center><img src="https://github.com/SagarPatel98/Flutter-Demo-App/blob/master/Screenshot_20200119-183905.jpg" height="400" width="280"></center>

