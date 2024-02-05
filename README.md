# Apk/Zip signing tool pulled out of the AOSP

## Source

The code is taken as is from build/tools/signapk/SignApk.java from the git 
repo at: https://android.googlesource.com/platform/build
and is just here for convenient access along with a prebuilt jarfile.

## Usage

Eg.

```
jdk/jdk8/linux-x86/bin/java -jar prebuilt/aospsign.jar -w aosp_test_keys/platform.x509.pem aosp_test_keys/platform.pk8 test.apk test-signed.apk
```
