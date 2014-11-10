版本
最新 Android SDK
Gradle 1.8
环境变量
ANDROID_HOME
GRADLE_HOME，同时把bin放入path变量
Android SDK 安装
Android SDK Build-tools 19+
Google Repository 4+
Google Play services 13+
Android Support Repository 3+
Android Support Library 19+
移除配置
修改AndroidManifest.xml里面com.google.android.maps.v2.API_KEY为你的Google Map key
移除AndroidManifest.xml里面com.crashlytics.ApiKey和GlobalContext的Crashlytics.start(this)，以免影响四次元的崩溃统计数据