# Image-Uploading-Using-FTP
Image-Uploading-Using-FTP-Android


Manifest
    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.ACCESS_WIFI_STATE" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.CAMERA" />

Dependencies
    compile files('libs/simpleftp.jar')

In ImageUploadActivity change following code.

    ftp.connect("server address", 21, "username", "pwd");
