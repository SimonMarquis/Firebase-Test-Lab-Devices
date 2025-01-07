# Firebase Test Lab Devices [![🔃 Refresh](https://github.com/SimonMarquis/Firebase-Test-Lab-Devices/actions/workflows/refresh.yml/badge.svg)](https://github.com/SimonMarquis/Firebase-Test-Lab-Devices/actions/workflows/refresh.yml)

## Android

```
┌─────────────────────┬────────────┬──────────────────────────────────────────┬──────────┬─────────────┬───────────────────────────────┬────────────────────────────────────┐
│       MODEL_ID      │    MAKE    │                MODEL_NAME                │   FORM   │  RESOLUTION │         OS_VERSION_IDS        │                TAGS                │
├─────────────────────┼────────────┼──────────────────────────────────────────┼──────────┼─────────────┼───────────────────────────────┼────────────────────────────────────┤
│ 1610                │ Vivo       │ vivo 1610                                │ PHYSICAL │ 1280 x 720  │ 23                            │ reduced_stability=23               │
│ AmatiTvEmulator     │ Google     │ Google TV Amati                          │ VIRTUAL  │ 1080 x 1920 │ 29                            │ beta=29                            │
│ AndroidTablet270dpi │ Generic    │ Generic 720x1600 Android tablet @ 270dpi │ VIRTUAL  │ 1600 x 720  │ 30                            │                                    │
│ CPH2449             │ OnePlus    │ OnePlus 11 5G                            │ PHYSICAL │ 2412 x 1080 │ 34                            │                                    │
│ F01L                │ FUJITSU    │ F-01L                                    │ PHYSICAL │ 1280 x 720  │ 27                            │                                    │
│ FRT                 │ HMD Global │ Nokia 1                                  │ PHYSICAL │  854 x 480  │ 27                            │                                    │
│ GoogleTvEmulator    │ Google     │ Google TV                                │ VIRTUAL  │  720 x 1280 │ 30                            │ beta=30                            │
│ J606F               │ Lenovo     │ Lenovo Tab P11                           │ PHYSICAL │ 2000 x 1200 │ 30                            │                                    │
│ MediumPhone.arm     │ Generic    │ Medium Phone, 6.4in/16cm (Arm)           │ VIRTUAL  │ 2400 x 1080 │ 26,27,28,29,30,31,32,33,34,35 │                                    │
│ MediumTablet.arm    │ Generic    │ Medium Tablet, 10in/25cm (Arm)           │ VIRTUAL  │ 2560 x 1600 │ 26,27,28,29,30,31,32,33,34,35 │                                    │
│ Nexus5X             │ LG         │ Nexus 5X                                 │ VIRTUAL  │ 1920 x 1080 │ 24,25,26                      │ deprecated=24, deprecated=25       │
│ Nexus6              │ Motorola   │ Nexus 6                                  │ VIRTUAL  │ 2560 x 1440 │ 24,25                         │ deprecated=24, deprecated=25       │
│ Nexus6P             │ Google     │ Nexus 6P                                 │ VIRTUAL  │ 2560 x 1440 │ 24,25,26,27                   │ deprecated=24, deprecated=25       │
│ Nexus7_clone_16_9   │ Generic    │ Nexus7 clone, DVD 16:9 aspect ratio      │ VIRTUAL  │ 1280 x 720  │ 24,25,26                      │ deprecated=24, deprecated=25, beta │
│ Nexus9              │ HTC        │ Nexus 9                                  │ VIRTUAL  │ 2048 x 1536 │ 24,25                         │ deprecated=24, deprecated=25       │
│ NexusLowRes         │ Generic    │ Low-resolution MDPI phone                │ VIRTUAL  │  640 x 360  │ 24,25,26,27,28,29,30          │ deprecated=24, deprecated=25       │
│ OP515BL1            │ OnePlus    │ OnePlus Nord2 5G                         │ PHYSICAL │ 2400 x 1080 │ 33                            │                                    │
│ OP573DL1            │ OPPO       │ CPH2557                                  │ PHYSICAL │ 2400 x 1080 │ 34                            │                                    │
│ OP5958L1            │ OnePlus    │ OnePlus Nord CE3 Lite                    │ PHYSICAL │ 2400 x 1080 │ 34                            │                                    │
│ OnePlus9Pro         │ OnePlus    │ LE2121                                   │ PHYSICAL │ 2412 x 1080 │ 33                            │ deprecated=33                      │
│ Pixel2              │ Google     │ Pixel 2                                  │ VIRTUAL  │ 1920 x 1080 │ 26,27,28,29,30                │                                    │
│ Pixel2.arm          │ Google     │ Pixel 2 (Arm)                            │ VIRTUAL  │ 1920 x 1080 │ 26,27,28,29,30,31,32,33       │                                    │
│ Pixel3              │ Google     │ Pixel 3                                  │ VIRTUAL  │ 2160 x 1080 │ 30                            │                                    │
│ RED8BEL1            │ realme     │ realme GT NEO 3 150W                     │ PHYSICAL │ 2412 x 1080 │ 33                            │ deprecated=33                      │
│ SH-01L              │ SHARP      │ AQUOS sense2 SH-01L                      │ PHYSICAL │ 2160 x 1080 │ 28                            │                                    │
│ SO-41A              │ Sony       │ Xperia 10 II                             │ PHYSICAL │ 1080 x 2520 │ 31                            │                                    │
│ SmallPhone.arm      │ Generic    │ Small Phone, 4.7in/12cm (Arm)            │ VIRTUAL  │ 1280 x 720  │ 26,27,28,29,30,31,32,33,34,35 │                                    │
│ TB370FU             │ Lenovo     │ Lenovo Tab P12                           │ PHYSICAL │ 2944 x 1840 │ 34                            │                                    │
│ XQ-DC54             │ Sony       │ XQ-DC54                                  │ PHYSICAL │ 2520 x 1080 │ 34                            │                                    │
│ XQ-DQ72             │ Sony       │ XQ-DQ72                                  │ PHYSICAL │ 2560 x 1096 │ 34                            │                                    │
│ a02q                │ Samsung    │ Galaxy A02s                              │ PHYSICAL │ 1600 x 720  │ 31                            │                                    │
│ a03s                │ Samsung    │ Galaxy A03s                              │ PHYSICAL │ 1600 x 720  │ 33                            │                                    │
│ a10                 │ Samsung    │ Galaxy A10                               │ PHYSICAL │  720 x 1520 │ 29                            │                                    │
│ a12                 │ Samsung    │ Galaxy A12                               │ PHYSICAL │ 1600 x 720  │ 31                            │                                    │
│ a14xm               │ Samsung    │ Galaxy A14                               │ PHYSICAL │ 2400 x 1080 │ 34                            │                                    │
│ a25x                │ Samsung    │ SM-A256U1                                │ PHYSICAL │ 2340 x 1080 │ 34                            │                                    │
│ a51                 │ Samsung    │ Galaxy A51                               │ PHYSICAL │ 2400 x 1080 │ 31                            │                                    │
│ a52sxq              │ Samsung    │ Galaxy A52s                              │ PHYSICAL │ 2400 x 1080 │ 34                            │                                    │
│ a54x                │ Samsung    │ Galaxy A54 5G                            │ PHYSICAL │ 2340 x 1080 │ 34                            │                                    │
│ akita               │ Google     │ Pixel 8a                                 │ PHYSICAL │ 2400 x 1080 │ 34                            │                                    │
│ b0q                 │ Samsung    │ Galaxy S22 Ultra                         │ PHYSICAL │ 3088 x 1440 │ 33                            │                                    │
│ b4q                 │ Samsung    │ Galaxy Z Flip4                           │ PHYSICAL │ 2640 x 1080 │ 33                            │                                    │
│ b5q                 │ Samsung    │ Galaxy Z Flip5                           │ PHYSICAL │ 2640 x 1080 │ 34                            │                                    │
│ bluejay             │ Google     │ Pixel 6a                                 │ PHYSICAL │ 2400 x 1080 │ 32                            │                                    │
│ blueline            │ Google     │ Pixel 3                                  │ PHYSICAL │ 2160 x 1080 │ 28                            │                                    │
│ cactus              │ Xiaomi     │ Redmi 6A                                 │ PHYSICAL │ 1440 x 720  │ 27                            │                                    │
│ caiman              │ Google     │ Pixel 9 Pro                              │ PHYSICAL │ 2142 x 960  │ 34                            │                                    │
│ cancunf             │ Motorola   │ moto g54 5G                              │ PHYSICAL │ 2400 x 1080 │ 34                            │                                    │
│ caprip              │ Motorola   │ moto g(30)                               │ PHYSICAL │ 1600 x 720  │ 31                            │                                    │
│ caymanlm            │ LG         │ VELVET                                   │ PHYSICAL │ 2460 x 1080 │ 31                            │                                    │
│ cheetah             │ Google     │ Pixel 7 Pro                              │ PHYSICAL │ 3120 x 1440 │ 33                            │                                    │
│ comet               │ Google     │ Pixel 9 Pro Fold                         │ PHYSICAL │ 2152 x 2076 │ 34                            │ dda-default                        │
│ crownqlteue         │ Samsung    │ Galaxy Note9                             │ PHYSICAL │ 1080 x 2220 │ 29                            │                                    │
│ dm3q                │ Samsung    │ Galaxy S23 Ultra                         │ PHYSICAL │ 3088 x 1440 │ 33,34                         │                                    │
│ e1q                 │ Samsung    │ Galaxy S24                               │ PHYSICAL │ 2340 x 1080 │ 34                            │ dda-default                        │
│ felix               │ Google     │ Pixel Fold                               │ PHYSICAL │ 1840 x 2208 │ 33,34                         │                                    │
│ felix_camera        │ Google     │ Pixel Fold (Camera-enabled)              │ PHYSICAL │ 1840 x 2208 │ 33                            │                                    │
│ gta8wifi            │ Samsung    │ Galaxy Tab A8                            │ PHYSICAL │ 1920 x 1200 │ 34                            │                                    │
│ gtaxlwifi           │ Samsung    │ Galaxy Tab A (2016)                      │ PHYSICAL │ 1920 x 1200 │ 27                            │                                    │
│ gts3lltevzw         │ Samsung    │ Galaxy Tab S3                            │ PHYSICAL │ 1536 x 2048 │ 28                            │ deprecated=28                      │
│ gts8uwifi           │ Samsung    │ Galaxy Tab S8 Ultra                      │ PHYSICAL │ 2960 x 1848 │ 33                            │                                    │
│ husky               │ Google     │ Pixel 8 Pro                              │ PHYSICAL │ 2244 x 1008 │ 34                            │                                    │
│ java                │ Motorola   │ Motorola G20                             │ PHYSICAL │ 1600 x 720  │ 30                            │                                    │
│ komodo              │ Google     │ Pixel 9 Pro XL                           │ PHYSICAL │ 2244 x 1008 │ 34                            │                                    │
│ lynx                │ Google     │ Pixel 7a                                 │ PHYSICAL │ 2400 x 1080 │ 33                            │                                    │
│ oriole              │ Google     │ Pixel 6                                  │ PHYSICAL │ 2400 x 1080 │ 32,33,31                      │                                    │
│ panther             │ Google     │ Pixel 7                                  │ PHYSICAL │ 2400 x 1080 │ 33                            │                                    │
│ pettyl              │ Motorola   │ moto e5 play                             │ PHYSICAL │  960 x 480  │ 27                            │                                    │
│ q2q                 │ Samsung    │ Galaxy Z Fold3                           │ PHYSICAL │ 2208 x 1768 │ 30                            │ deprecated=30                      │
│ q4q                 │ Samsung    │ Galaxy Z Fold4                           │ PHYSICAL │ 2176 x 1812 │ 33                            │                                    │
│ q5q                 │ Samsung    │ Galaxy Z Fold5                           │ PHYSICAL │ 2176 x 1812 │ 34                            │                                    │
│ q6q                 │ Samsung    │ Galaxy Z Fold6                           │ PHYSICAL │ 2160 x 1856 │ 34                            │                                    │
│ r11                 │ Google     │ Google Pixel Watch                       │ PHYSICAL │  384 x 384  │ 30                            │                                    │
│ redfin              │ Google     │ Pixel 5                                  │ PHYSICAL │ 2340 x 1080 │ 30                            │ default                            │
│ shiba               │ Google     │ Pixel 8                                  │ PHYSICAL │ 2400 x 1080 │ 34                            │                                    │
│ shiba_beta          │ Google     │ Pixel 8                                  │ PHYSICAL │ 2400 x 1080 │ 35                            │                                    │
│ starlte             │ Samsung    │ Galaxy S9                                │ PHYSICAL │ 1080 x 2220 │ 29                            │                                    │
│ starqlteue          │ Samsung    │ Galaxy S9                                │ PHYSICAL │ 1080 x 2220 │ 26                            │                                    │
│ tangorpro           │ Google     │ Pixel Tablet                             │ PHYSICAL │ 2560 x 1600 │ 33                            │                                    │
│ tokay               │ Google     │ Pixel 9                                  │ PHYSICAL │ 2424 x 1080 │ 34                            │ dda-default                        │
│ x1q                 │ Samsung    │ Galaxy S20                               │ PHYSICAL │ 3200 x 1440 │ 29                            │                                    │
│ xcoverpro           │ Samsung    │ Galaxy XCover Pro                        │ PHYSICAL │ 2340 x 1080 │ 33                            │                                    │
└─────────────────────┴────────────┴──────────────────────────────────────────┴──────────┴─────────────┴───────────────────────────────┴────────────────────────────────────┘
```

## iOS

```
┌─────────────┬────────────────────────┬────────────────┬─────────┐
│   MODEL_ID  │          NAME          │ OS_VERSION_IDS │   TAGS  │
├─────────────┼────────────────────────┼────────────────┼─────────┤
│ ipad10      │ iPad (10th generation) │ 16.6           │         │
│ iphone11pro │ iPhone 11 Pro          │ 14.7,16.6      │         │
│ iphone12pro │ iPhone 12 Pro          │ 14.8           │         │
│ iphone13pro │ iPhone 13 Pro          │ 15.7,16.6      │ default │
│ iphone14pro │ iPhone 14 Pro          │ 16.6           │         │
│ iphone8     │ iPhone 8               │ 14.7,15.7,16.6 │         │
└─────────────┴────────────────────────┴────────────────┴─────────┘
```
