ANDROID_SDK_ROOT=~/Android/Sdk/ ANDROID_NDK_ROOT=~/Android/Sdk/ndk/25.0.8775105/ cargo apk run --lib

~/Android/Sdk/platform-tools/adb logcat -s RustStdoutStderr