# Firebase Test Lab Devices [![🔃 Refresh](https://github.com/SimonMarquis/Firebase-Test-Lab-Devices/actions/workflows/refresh.yml/badge.svg)](https://github.com/SimonMarquis/Firebase-Test-Lab-Devices/actions/workflows/refresh.yml)

```
┌─────────────────────┬────────────────────┬──────────────────────────────────────────┬──────────┬─────────────┬─────────────────────────┬──────────────────┐
│       MODEL_ID      │        MAKE        │                MODEL_NAME                │   FORM   │  RESOLUTION │      OS_VERSION_IDS     │       TAGS       │
├─────────────────────┼────────────────────┼──────────────────────────────────────────┼──────────┼─────────────┼─────────────────────────┼──────────────────┤
│ 1610                │ Vivo               │ vivo 1610                                │ PHYSICAL │ 1280 x 720  │ 23                      │                  │
│ ASUS_X00T_3         │ Asus               │ ASUS_X00TD                               │ PHYSICAL │ 1080 x 2160 │ 27,28                   │                  │
│ AmatiTvEmulator     │ Google             │ Google TV Amati                          │ EMULATOR │ 1080 x 1920 │ 29                      │ beta=29          │
│ AndroidTablet270dpi │ Generic            │ Generic 720x1600 Android tablet @ 270dpi │ VIRTUAL  │ 1600 x 720  │ 30                      │                  │
│ F01L                │ FUJITSU            │ F-01L                                    │ PHYSICAL │ 1280 x 720  │ 27                      │                  │
│ FRT                 │ HMD Global         │ Nokia 1                                  │ PHYSICAL │  854 x 480  │ 27                      │                  │
│ G8142               │ Sony               │ G8142                                    │ PHYSICAL │ 1080 x 1920 │ 25                      │                  │
│ G8342               │ Sony               │ G8342                                    │ PHYSICAL │ 1080 x 1920 │ 26                      │                  │
│ GoogleTvEmulator    │ Google             │ Google TV                                │ EMULATOR │  720 x 1280 │ 30                      │ beta=30          │
│ H9493               │ Sony               │ H9493                                    │ PHYSICAL │ 2880 x 1440 │ 28                      │                  │
│ HWANE-LX1           │ Huawei             │ ANE-LX1                                  │ PHYSICAL │ 1080 x 2280 │ 28                      │ deprecated=28    │
│ HWANE-LX2           │ Huawei             │ ANE-LX2                                  │ PHYSICAL │ 1080 x 2280 │ 28                      │                  │
│ HWCOR               │ Huawei             │ COR-L29                                  │ PHYSICAL │ 1080 x 2340 │ 27                      │                  │
│ HWMHA               │ Huawei             │ MHA-L29                                  │ PHYSICAL │ 1920 x 1080 │ 24                      │                  │
│ MediumPhone.arm     │ Generic            │ MediumPhone (ARM)                        │ EMULATOR │ 2400 x 1080 │ 28,29,30,32,33          │ preview=33, beta │
│ Nexus10             │ Samsung            │ Nexus 10                                 │ VIRTUAL  │ 2560 x 1600 │ 19,21,22                │                  │
│ Nexus4              │ LG                 │ Nexus 4                                  │ VIRTUAL  │ 1280 x 768  │ 19,21,22                │                  │
│ Nexus5              │ LG                 │ Nexus 5                                  │ VIRTUAL  │ 1920 x 1080 │ 19,21,22,23             │                  │
│ Nexus5X             │ LG                 │ Nexus 5X                                 │ VIRTUAL  │ 1920 x 1080 │ 23,24,25,26             │                  │
│ Nexus6              │ Motorola           │ Nexus 6                                  │ VIRTUAL  │ 2560 x 1440 │ 21,22,23,24,25          │                  │
│ Nexus6P             │ Google             │ Nexus 6P                                 │ VIRTUAL  │ 2560 x 1440 │ 23,24,25,26,27          │                  │
│ Nexus7              │ Asus               │ Nexus 7 (2012)                           │ VIRTUAL  │ 1280 x 800  │ 19,21,22                │                  │
│ Nexus7_clone_16_9   │ Generic            │ Nexus7 clone, DVD 16:9 aspect ratio      │ VIRTUAL  │ 1280 x 720  │ 23,24,25,26             │ beta             │
│ Nexus9              │ HTC                │ Nexus 9                                  │ VIRTUAL  │ 2048 x 1536 │ 21,22,23,24,25          │                  │
│ NexusLowRes         │ Generic            │ Low-resolution MDPI phone                │ VIRTUAL  │  640 x 360  │ 23,24,25,26,27,28,29,30 │                  │
│ OnePlus5T           │ OnePlus            │ ONEPLUS A5010                            │ PHYSICAL │ 1080 x 2160 │ 28                      │                  │
│ Pixel2              │ Google             │ Pixel 2                                  │ VIRTUAL  │ 1920 x 1080 │ 26,27,28,29,30          │                  │
│ Pixel2.arm          │ Google             │ Pixel 2 (ARM)                            │ EMULATOR │ 1920 x 1080 │ 28,29,30,32,33          │ preview=33, beta │
│ Pixel3              │ Google             │ Pixel 3                                  │ VIRTUAL  │ 2160 x 1080 │ 30                      │                  │
│ SC-02K              │ Samsung            │ SC-02K                                   │ PHYSICAL │ 2220 x 1080 │ 28                      │ deprecated=28    │
│ SH-01L              │ SHARP              │ SH-01L                                   │ PHYSICAL │ 2160 x 1080 │ 28                      │                  │
│ SmallPhone.arm      │ Generic            │ SmallPhone (ARM)                         │ EMULATOR │ 1280 x 720  │ 28,29,30,32,33          │ preview=33, beta │
│ TC77                │ Zebra Technologies │ TC77                                     │ PHYSICAL │ 1280 x 720  │ 27                      │                  │
│ a10                 │ Samsung            │ SM-A105FN                                │ PHYSICAL │  720 x 1520 │ 29                      │                  │
│ b2q                 │ Samsung            │ SM-F711U1                                │ PHYSICAL │  260 x 512  │ 30,31                   │                  │
│ bluejay             │ Google             │ Pixel 6a                                 │ PHYSICAL │ 2400 x 1080 │ 32                      │                  │
│ blueline            │ Google             │ Pixel 3                                  │ PHYSICAL │ 2160 x 1080 │ 28                      │                  │
│ cactus              │ Xiaomi             │ Redmi 6A                                 │ PHYSICAL │ 1440 x 720  │ 27                      │                  │
│ cruiserlteatt       │ Samsung            │ SM-G892A                                 │ PHYSICAL │ 1080 x 2220 │ 26                      │                  │
│ dreamlte            │ Samsung            │ SM-G950F                                 │ PHYSICAL │ 1080 x 2220 │ 28                      │                  │
│ f2q                 │ Samsung            │ SM-F916U1                                │ PHYSICAL │ 2208 x 1768 │ 30                      │                  │
│ flo                 │ Asus               │ Nexus 7                                  │ PHYSICAL │ 1200 x 1920 │ 19                      │                  │
│ grandppltedx        │ Samsung            │ SM-G532G                                 │ PHYSICAL │  540 x 960  │ 23                      │                  │
│ griffin             │ Motorola           │ XT1650                                   │ PHYSICAL │ 1440 x 2560 │ 24                      │                  │
│ gts3lltevzw         │ Samsung            │ SM-T827V                                 │ PHYSICAL │ 1536 x 2048 │ 28                      │                  │
│ gts4lltevzw         │ Samsung            │ SM-T837V                                 │ PHYSICAL │ 2560 x 1600 │ 28                      │                  │
│ hammerhead          │ LG                 │ Nexus 5                                  │ PHYSICAL │ 1920 x 1080 │ 23                      │                  │
│ harpia              │ Motorola           │ Moto G Play                              │ PHYSICAL │ 1280 x 720  │ 23                      │                  │
│ heroqlteaio         │ Samsung            │ SAMSUNG-SM-G930AZ                        │ PHYSICAL │ 1080 x 1920 │ 26                      │                  │
│ htc_pmeuhl          │ HTC                │ HTC 10                                   │ PHYSICAL │ 1440 x 2560 │ 26                      │ deprecated=26    │
│ hwALE-H             │ Huawei             │ ALE-L23                                  │ PHYSICAL │ 1280 x 720  │ 21                      │ deprecated=21    │
│ joan                │ LG                 │ LG-H932                                  │ PHYSICAL │ 1440 x 2880 │ 26                      │                  │
│ lt02wifi            │ Samsung            │ SM-T210                                  │ PHYSICAL │  600 x 1024 │ 19                      │                  │
│ lv0                 │ LG                 │ LG-AS110                                 │ PHYSICAL │  854 x 480  │ 23                      │                  │
│ oriole              │ Google             │ Pixel 6                                  │ PHYSICAL │ 2400 x 1080 │ 31,32,33                │                  │
│ pettyl              │ Motorola           │ moto e5 play                             │ PHYSICAL │  960 x 480  │ 27                      │                  │
│ q2q                 │ Samsung            │ SM-F926U1                                │ PHYSICAL │ 2208 x 1768 │ 30,31                   │                  │
│ redfin              │ Google             │ Pixel 5                                  │ PHYSICAL │ 2340 x 1080 │ 30                      │ default          │
│ sailfish            │ Google             │ Pixel                                    │ PHYSICAL │  640 x 480  │ 25                      │                  │
│ starqlteue          │ Samsung            │ SM-G960U1                                │ PHYSICAL │ 1080 x 2220 │ 26                      │                  │
│ walleye             │ Google             │ Pixel 2                                  │ PHYSICAL │ 1920 x 1080 │ 27                      │                  │
│ x1q                 │ Samsung            │ SM-G981U1                                │ PHYSICAL │ 3200 x 1440 │ 29                      │                  │
└─────────────────────┴────────────────────┴──────────────────────────────────────────┴──────────┴─────────────┴─────────────────────────┴──────────────────┘
```
