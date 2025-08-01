# Firebase Test Lab Devices [![🔃 Refresh](https://github.com/SimonMarquis/Firebase-Test-Lab-Devices/actions/workflows/refresh.yml/badge.svg)](https://github.com/SimonMarquis/Firebase-Test-Lab-Devices/actions/workflows/refresh.yml)

## Android

```
┌─────────────────────────┬────────────┬────────────────────────────────────────────────┬──────────┬─────────────┬───────────────────────────────┬────────────────────────┐
│         MODEL_ID        │    MAKE    │                   MODEL_NAME                   │   FORM   │  RESOLUTION │         OS_VERSION_IDS        │          TAGS          │
├─────────────────────────┼────────────┼────────────────────────────────────────────────┼──────────┼─────────────┼───────────────────────────────┼────────────────────────┤
│ 1610                    │ Vivo       │ vivo 1610                                      │ PHYSICAL │ 1280 x 720  │ 23                            │ reduced_stability=23   │
│ A402SO                  │ Sony       │ Xperia 10                                      │ PHYSICAL │ 2520 x 1080 │ 34                            │                        │
│ AmatiTvEmulator         │ Google     │ Google TV Amati                                │ VIRTUAL  │ 1080 x 1920 │ 29                            │ beta=29, deprecated=29 │
│ AndroidTablet270dpi.arm │ Generic    │ Generic 720x1600 Android tablet @ 270dpi (Arm) │ VIRTUAL  │ 1600 x 720  │ 30                            │                        │
│ CPH2449                 │ OnePlus    │ OnePlus 11 5G                                  │ PHYSICAL │ 2412 x 1080 │ 34                            │                        │
│ F01L                    │ FUJITSU    │ F-01L                                          │ PHYSICAL │ 1280 x 720  │ 27                            │                        │
│ FRT                     │ HMD Global │ Nokia 1                                        │ PHYSICAL │  854 x 480  │ 27                            │ deprecated=27          │
│ GoogleTvEmulator        │ Google     │ Google TV                                      │ VIRTUAL  │  720 x 1280 │ 30                            │ beta=30, deprecated=30 │
│ MediumPhone.arm         │ Generic    │ Medium Phone, 6.4in/16cm (Arm)                 │ VIRTUAL  │ 2400 x 1080 │ 26,27,28,29,30,31,32,33,35,34 │                        │
│ MediumTablet.arm        │ Generic    │ Medium Tablet, 10.05in/25cm (Arm)              │ VIRTUAL  │ 2560 x 1600 │ 26,27,28,29,30,31,32,33,34,35 │                        │
│ OP515BL1                │ OnePlus    │ OnePlus Nord2 5G                               │ PHYSICAL │ 2400 x 1080 │ 33                            │ deprecated=33          │
│ OP535DL1                │ OnePlus    │ CPH2409                                        │ PHYSICAL │ 2412 x 1080 │ 34                            │                        │
│ OP5552L1                │ OnePlus    │ CPH2415                                        │ PHYSICAL │ 2412 x 1080 │ 34                            │                        │
│ OP573DL1                │ OPPO       │ CPH2557                                        │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ OP5958L1                │ OnePlus    │ OnePlus Nord CE3 Lite                          │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ Pixel2.arm              │ Google     │ Pixel 2 (Arm)                                  │ VIRTUAL  │ 1920 x 1080 │ 26,27,28,29,30,31,32,33       │                        │
│ RED8BEL1                │ realme     │ realme GT NEO 3 150W                           │ PHYSICAL │ 2412 x 1080 │ 33                            │ deprecated=33          │
│ SH-01L                  │ SHARP      │ AQUOS sense2 SH-01L                            │ PHYSICAL │ 2160 x 1080 │ 28                            │                        │
│ SO-41A                  │ Sony       │ Xperia 10 II                                   │ PHYSICAL │ 1080 x 2520 │ 31                            │                        │
│ SmallPhone.arm          │ Generic    │ Small Phone, 4.65in/12cm (Arm)                 │ VIRTUAL  │ 1280 x 720  │ 26,27,28,29,30,31,32,33,34,35 │                        │
│ TB370FU                 │ Lenovo     │ Lenovo Tab P12                                 │ PHYSICAL │ 2944 x 1840 │ 35                            │                        │
│ XQ-DC54                 │ Sony       │ XQ-DC54                                        │ PHYSICAL │ 2520 x 1080 │ 34                            │                        │
│ XQ-DQ72                 │ Sony       │ XQ-DQ72                                        │ PHYSICAL │ 2560 x 1096 │ 34                            │                        │
│ a02q                    │ Samsung    │ Galaxy A02s                                    │ PHYSICAL │ 1600 x 720  │ 31                            │                        │
│ a03s                    │ Samsung    │ Galaxy A03s                                    │ PHYSICAL │ 1600 x 720  │ 33                            │                        │
│ a10                     │ Samsung    │ Galaxy A10                                     │ PHYSICAL │  720 x 1520 │ 29                            │                        │
│ a12                     │ Samsung    │ Galaxy A12                                     │ PHYSICAL │ 1600 x 720  │ 31                            │                        │
│ a14m                    │ Samsung    │ SM-A145R                                       │ PHYSICAL │ 2408 x 1080 │ 34                            │                        │
│ a14xm                   │ Samsung    │ Galaxy A14                                     │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ a15                     │ Samsung    │ Samsung A15                                    │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ a15x                    │ Samsung    │ Samsung A15 5G                                 │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ a16x                    │ Samsung    │ Samsung A16 5G                                 │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ a25x                    │ Samsung    │ SM-A256U1                                      │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ a35x                    │ Samsung    │ Samsung A35                                    │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ a52sxq                  │ Samsung    │ Galaxy A52s                                    │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ a54x                    │ Samsung    │ Galaxy A54 5G                                  │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ akita                   │ Google     │ Pixel 8a                                       │ PHYSICAL │ 2400 x 1080 │ 34,35                         │                        │
│ arcfox                  │ Motorola   │ motorola razr plus 2024                        │ PHYSICAL │ 1272 x 1080 │ 34                            │                        │
│ austin                  │ Motorola   │ moto g 5G (2022)                               │ PHYSICAL │ 1600 x 720  │ 33                            │                        │
│ b0q                     │ Samsung    │ Galaxy S22 Ultra                               │ PHYSICAL │ 3088 x 1440 │ 33                            │                        │
│ b4q                     │ Samsung    │ Galaxy Z Flip4                                 │ PHYSICAL │ 2640 x 1080 │ 33                            │                        │
│ b5q                     │ Samsung    │ Galaxy Z Flip5                                 │ PHYSICAL │ 2640 x 1080 │ 34                            │                        │
│ b6q                     │ Samsung    │ Flip 6                                         │ PHYSICAL │ 2640 x 1080 │ 34                            │                        │
│ bluejay                 │ Google     │ Pixel 6a                                       │ PHYSICAL │ 2400 x 1080 │ 32                            │                        │
│ blueline                │ Google     │ Pixel 3                                        │ PHYSICAL │ 2160 x 1080 │ 28                            │                        │
│ cactus                  │ Xiaomi     │ Redmi 6A                                       │ PHYSICAL │ 1440 x 720  │ 27                            │                        │
│ caiman                  │ Google     │ Pixel 9 Pro                                    │ PHYSICAL │ 2142 x 960  │ 34,35                         │                        │
│ cancunf                 │ Motorola   │ moto g54 5G                                    │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ caprip                  │ Motorola   │ moto g(30)                                     │ PHYSICAL │ 1600 x 720  │ 31                            │                        │
│ caymanlm                │ LG         │ VELVET                                         │ PHYSICAL │ 2460 x 1080 │ 31                            │ deprecated=31          │
│ cheetah                 │ Google     │ Pixel 7 Pro                                    │ PHYSICAL │ 3120 x 1440 │ 33                            │                        │
│ comet                   │ Google     │ Pixel 9 Pro Fold                               │ PHYSICAL │ 2152 x 2076 │ 34,35                         │ dda-default            │
│ crownqlteue             │ Samsung    │ Galaxy Note9                                   │ PHYSICAL │ 1080 x 2220 │ 29                            │                        │
│ dm2q                    │ Samsung    │ S23 Plus                                       │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ dm3q                    │ Samsung    │ Galaxy S23 Ultra                               │ PHYSICAL │ 3088 x 1440 │ 33,34                         │                        │
│ dubai                   │ Motorola   │ motorola edge 30                               │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ e1q                     │ Samsung    │ Galaxy S24                                     │ PHYSICAL │ 2340 x 1080 │ 34                            │ dda-default            │
│ e3q                     │ Samsung    │ Galaxy S24 Ultra                               │ PHYSICAL │ 3120 x 1440 │ 34                            │                        │
│ eos                     │ Google     │ Eos                                            │ PHYSICAL │  384 x 384  │ 33                            │                        │
│ eqe                     │ Motorola   │ motorola edge 50 pro                           │ PHYSICAL │ 2712 x 1220 │ 35                            │                        │
│ felix                   │ Google     │ Pixel Fold                                     │ PHYSICAL │ 1840 x 2208 │ 33,34                         │                        │
│ felix_camera            │ Google     │ Pixel Fold (Camera-enabled)                    │ PHYSICAL │ 1840 x 2208 │ 33                            │                        │
│ fogona                  │ Motorola   │ moto g play - 2024                             │ PHYSICAL │ 1600 x 720  │ 34                            │                        │
│ fogos                   │ Motorola   │ moto g34 5G                                    │ PHYSICAL │ 1600 x 720  │ 34                            │                        │
│ g0q                     │ Samsung    │ SM-S906U1                                      │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ gta7lite                │ Samsung    │ Galaxy Tab A7 Lite                             │ PHYSICAL │ 1340 x 800  │ 34                            │                        │
│ gta8wifi                │ Samsung    │ Galaxy Tab A8                                  │ PHYSICAL │ 1920 x 1200 │ 34                            │                        │
│ gta9pwifi               │ Samsung    │ SM-X210                                        │ PHYSICAL │ 1920 x 1200 │ 34                            │                        │
│ gtaxlwifi               │ Samsung    │ Galaxy Tab A (2016)                            │ PHYSICAL │ 1920 x 1200 │ 27                            │ deprecated=27          │
│ gts3lltevzw             │ Samsung    │ Galaxy Tab S3                                  │ PHYSICAL │ 1536 x 2048 │ 28                            │ deprecated=28          │
│ gts7lwifi               │ Samsung    │ SM-T870                                        │ PHYSICAL │ 2560 x 1600 │ 33                            │                        │
│ gts7xllite              │ Samsung    │ SM-T738U                                       │ PHYSICAL │ 2560 x 1600 │ 34                            │                        │
│ gts8uwifi               │ Samsung    │ Galaxy Tab S8 Ultra                            │ PHYSICAL │ 2960 x 1848 │ 33                            │                        │
│ gts8wifi                │ Samsung    │ Galaxy Tab S8                                  │ PHYSICAL │ 2560 x 1600 │ 34                            │                        │
│ gts9fe                  │ Samsung    │ Samsung Galaxy Tab S9 FE 5G                    │ PHYSICAL │ 2304 x 1440 │ 34                            │                        │
│ gts9wifi                │ Samsung    │ SM-X710                                        │ PHYSICAL │ 2560 x 1600 │ 34                            │                        │
│ husky                   │ Google     │ Pixel 8 Pro                                    │ PHYSICAL │ 2244 x 1008 │ 34                            │                        │
│ java                    │ Motorola   │ Motorola G20                                   │ PHYSICAL │ 1600 x 720  │ 30                            │                        │
│ komodo                  │ Google     │ Pixel 9 Pro XL                                 │ PHYSICAL │ 2244 x 1008 │ 34,35                         │                        │
│ lion                    │ Motorola   │ moto g04                                       │ PHYSICAL │ 1612 x 720  │ 34                            │                        │
│ lynx                    │ Google     │ Pixel 7a                                       │ PHYSICAL │ 2400 x 1080 │ 33                            │                        │
│ lyriq                   │ Motorola   │ motorola edge 40                               │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ manaus                  │ Motorola   │ motorola edge 40 neo                           │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ maui                    │ Motorola   │ moto g play - 2023                             │ PHYSICAL │ 1600 x 720  │ 33                            │                        │
│ o1q                     │ Samsung    │ Galaxy S21                                     │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ oriole                  │ Google     │ Pixel 6                                        │ PHYSICAL │ 2400 x 1080 │ 32,33,31                      │                        │
│ p3q                     │ Samsung    │ Galaxy S21 Ultra                               │ PHYSICAL │ 3200 x 1440 │ 34                            │                        │
│ pa3q                    │ Samsung    │ Galaxy S25 Ultra                               │ PHYSICAL │ 3120 x 1440 │ 35                            │                        │
│ panther                 │ Google     │ Pixel 7                                        │ PHYSICAL │ 2400 x 1080 │ 33                            │                        │
│ pettyl                  │ Motorola   │ moto e5 play                                   │ PHYSICAL │  960 x 480  │ 27                            │                        │
│ q4q                     │ Samsung    │ Galaxy Z Fold4                                 │ PHYSICAL │ 2176 x 1812 │ 33                            │                        │
│ q5q                     │ Samsung    │ Galaxy Z Fold5                                 │ PHYSICAL │ 2176 x 1812 │ 34                            │                        │
│ q6q                     │ Samsung    │ Galaxy Z Fold6                                 │ PHYSICAL │ 2160 x 1856 │ 34                            │                        │
│ r0q                     │ Samsung    │ Galaxy S22                                     │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ r11                     │ Google     │ Google Pixel Watch                             │ PHYSICAL │  384 x 384  │ 30                            │                        │
│ r11q                    │ Samsung    │ SM-S711U                                       │ PHYSICAL │ 2340 x 1080 │ 34                            │                        │
│ redfin                  │ Google     │ Pixel 5                                        │ PHYSICAL │ 2340 x 1080 │ 30                            │ default                │
│ shiba                   │ Google     │ Pixel 8                                        │ PHYSICAL │ 2400 x 1080 │ 35,34                         │                        │
│ starlte                 │ Samsung    │ Galaxy S9                                      │ PHYSICAL │ 1080 x 2220 │ 29                            │                        │
│ t2q                     │ Samsung    │ Galaxy S21 Plus                                │ PHYSICAL │ 2400 x 1080 │ 34                            │                        │
│ tangorpro               │ Google     │ Pixel Tablet                                   │ PHYSICAL │ 2560 x 1600 │ 33                            │                        │
│ tegu                    │ Google     │ Pixel 9a                                       │ PHYSICAL │ 2424 x 1080 │ 35                            │                        │
│ tokay                   │ Google     │ Pixel 9                                        │ PHYSICAL │ 2424 x 1080 │ 34,35                         │ dda-default            │
│ xcover7                 │ Samsung    │ SM-G556B                                       │ PHYSICAL │ 2408 x 1080 │ 34                            │                        │
│ xcoverpro               │ Samsung    │ Galaxy XCover Pro                              │ PHYSICAL │ 2340 x 1080 │ 33                            │                        │
└─────────────────────────┴────────────┴────────────────────────────────────────────────┴──────────┴─────────────┴───────────────────────────────┴────────────────────────┘
```

## iOS

```
┌─────────────┬────────────────────────┬────────────────┬──────────────┐
│   MODEL_ID  │          NAME          │ OS_VERSION_IDS │     TAGS     │
├─────────────┼────────────────────────┼────────────────┼──────────────┤
│ ipad10      │ iPad (10th generation) │ 16.6           │              │
│ iphone11pro │ iPhone 11 Pro          │ 16.6           │              │
│ iphone13pro │ iPhone 13 Pro          │ 15.7,16.6      │ default      │
│ iphone14pro │ iPhone 14 Pro          │ 16.6           │              │
│ iphone15    │ iPhone 15              │ 18.0           │ preview=18.0 │
│ iphone15pro │ iPhone 15 Pro          │ 18.0           │ preview=18.0 │
│ iphone8     │ iPhone 8               │ 15.7,16.6      │              │
└─────────────┴────────────────────────┴────────────────┴──────────────┘
```
