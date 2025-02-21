**StackTrace**
```
Launching lib\main.dart on M2102J20SG in debug mode...
√ Built build\app\outputs\flutter-apk\app-debug.apk
I/flutter (26730): [IMPORTANT:flutter/shell/platform/android/android_context_vk_impeller.cc(60)] Using the Impeller rendering backend (Vulkan).
Connecting to VM Service at ws://127.0.0.1:56554/EwsXTLuxtHg=/ws
Connected to the VM Service.
I/Choreographer(26730): Skipped 52 frames!  The application may be doing too much work on its main thread.
W/Looper  (26730): PerfMonitor doFrame : time=0ms vsyncFrame=0 latency=869ms procState=-1 historyMsgCount=1
D/nativeloader(26730): Load /data/app/~~zh46x5SzFsxTPvdVqRUV4A==/com.example.ya_maps_test-qbZL_0ZGSUvAdPHpHEIBHw==/base.apk!/lib/arm64-v8a/libmaps-mobile.so using ns clns-4 from class loader (caller=/data/app/~~zh46x5SzFsxTPvdVqRUV4A==/com.example.ya_maps_test-qbZL_0ZGSUvAdPHpHEIBHw==/base.apk): ok
F/libc    (26730): Fatal signal 6 (SIGABRT), code -1 (SI_QUEUE) in tid 26730 (le.ya_maps_test), pid 26730 (le.ya_maps_test)
*** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
Build fingerprint: 'POCO/vayu_ru/vayu:12/SKQ1.211006.001/V13.0.1.0.SJURUXM:user/release-keys'
Revision: '0'
ABI: 'arm64'
Timestamp: 2025-02-21 12:02:44.498199808+0300
Process uptime: 0s
Cmdline: com.example.ya_maps_test
pid: 26730, tid: 26730, name: le.ya_maps_test  >>> com.example.ya_maps_test <<<
uid: 11217
signal 6 (SIGABRT), code -1 (SI_QUEUE), fault addr --------
    x0  0000000000000000  x1  000000000000686a  x2  0000000000000006  x3  0000007ff1632050
    x4  000000000000000a  x5  000000000000000a  x6  000000000000000a  x7  000000000000000a
    x8  00000000000000f0  x9  c0d37522672590bf  x10 0000000000000000  x11 ffffff80fffffbdf
    x12 0000000000000001  x13 000000000f70eca8  x14 0000000000000600  x15 0000000000000040
    x16 0000007898f5cd30  x17 0000007898f36650  x18 00000078aa704000  x19 000000000000686a
    x20 000000000000686a  x21 00000000ffffffff  x22 0000007600008081  x23 0000000005f019e1
    x24 0000007600008081  x25 0000007ff0e57000  x26 b4000077cd4c5000  x27 00000076072ad560
    x28 0000000800000076  x29 0000007ff16320d0
    lr  0000007898ee69fc  sp  0000007ff1632030  pc  0000007898ee6a28  pst 0000000000000000
backtrace:
      #00 pc 000000000008aa28  /apex/com.android.runtime/lib64/bionic/libc.so (abort+168) (BuildId: 94065bf91428f6ae9fb310c478171302)
      #01 pc 0000000000ab057c  /data/app/~~zh46x5SzFsxTPvdVqRUV4A==/com.example.ya_maps_test-qbZL_0ZGSUvAdPHpHEIBHw==/base.apk!libmaps-mobile.so (BuildId: 6ba3d7b8e61c84a9)
      #02 pc 0000000000abe6d8  /data/app/~~zh46x5SzFsxTPvdVqRUV4A==/com.example.ya_maps_test-qbZL_0ZGSUvAdPHpHEIBHw==/base.apk!libmaps-mobile.so (BuildId: 6ba3d7b8e61c84a9)
      #03 pc 0000000000adad04  /data/app/~~zh46x5SzFsxTPvdVqRUV4A==/com.example.ya_maps_test-qbZL_0ZGSUvAdPHpHEIBHw==/base.apk!libmaps-mobile.so (yandex_flutter_runtime_i18n_I18nManagerFactory_setLocale+52) (BuildId: 6ba3d7b8e61c84a9)
      #04 pc 0000000000008184  [anon:dart-code]
Lost connection to device.

Exited.
```
