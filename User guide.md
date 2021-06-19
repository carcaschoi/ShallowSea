This guide is updated on 20/5/2021
# 目錄 table of contents
- [大氣層更新整合包(手動) Atmosphere update aio-package guide (manual)](#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E6%9B%B4%E6%96%B0%E6%95%B4%E5%90%88%E5%8C%85%E6%8C%87%E5%8D%97-atmosphere-update-aio-package-guide)
- [大氣層更新整合包(ShallowSea-updater-pc) Atmosphere update aio-package guide (ShallowSea-updater-pc)](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E6%9B%B4%E6%96%B0%E6%95%B4%E5%90%88%E5%8C%85shallowsea-updater-pc-atmosphere-update-aio-package-guide-shallowsea-updater-pc)
- [ShallowSea使用方法 How to use ShallowSea](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-how-to-use)
- [sxos轉大氣層指南 Change sxos to atmosphere](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#sxos%E8%BD%89%E5%A4%A7%E6%B0%A3%E5%B1%A4%E6%8C%87%E5%8D%97-change-sxos-to-atmosphere)

# 大氣層更新整合包指南 Atmosphere update aio-package guide:
| 中文指南 | English guide |
| ------ | ------------- |
| 1. 從[這裡](https://github.com/carcaschoi/ShallowSea/releases/latest)下載大氣層整合包 | 1. Download ShallowSea aio package 「Shalloesea-ams.zip」 & 「switch English extra package.zip」 from [here](https://github.com/carcaschoi/ShallowSea/releases/latest) |
| 2. SD卡除了（Nintendo，emuiibo，emuMMC，BCAT，JKSV，warmboot_mariko，license.dat）文件夾(沒有的可略過)，刪除其餘文件夾。把整合包裏面所有東西解壓縮放到SD卡中。 | 2. Delete all the folders in sd card except (Nintendo,emuiibo,emuMMC,BCAT,JKSV,warmboot_mariko，license.dat) folders or files. Then drapes and drops aio package contents into your sd card. Replace all existing file |
| ...... | 3. After that extract 「switch English extra package.rar」 into the root of the sd card. Replace all existing file. |
| [點此繼續查看使用方法](#%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-how-to-use) | [press here to continue read the guide (How to use)](#%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-how-to-use) |

# 大氣層更新整合包(ShallowSea-updater-pc) Atmosphere update aio-package guide (ShallowSea-updater-pc)
* This is the ShallowSea updater on window，It will help you to delete and place ShallowSea-ams package to sd card automatically
* 此方法不適用第一次使用ShallowSea-ams的用戶，第一次使用整合包的話請跟隨手動方法 
* This method does not support user who use ShallowSea-ams first time, please use the manual method instead if you want to install ShallowSea-ams package first time

| 中文指南 | English guide |
| ------- | ------------- |
| 1. 從[這裡](https://github.com/carcaschoi/ShallowSea/releases/latest)下載ShallowSea整合包「Shalloesea-ams.rar」並解壓縮到電腦任意位置 | 1. Download atmosphere package 「ShallowSea-ams.zip」from [here](https://github.com/carcaschoi/ShallowSea/releases/latest) & unzip it to anyplace of pc
| 2. 從[這裏](https://github.com/carcaschoi/ShallowSea-Updater-pc/releases/latest)下載ShallowSeaupdaterpc.zip並解壓縮文件到電腦任意位置 | 2. Download 「ShallowSeaupdaterpc.zip」from [here](https://github.com/carcaschoi/ShallowSea-Updater-pc/releases/latest) & unzip it to anyplace of pc|
| 3. 運行exe文件，按照程式指示，選擇SD卡和ShallowSea-ams整合包文件位置 | 3. Run exe file. Follow the app instructions and choose your sd card drive and ShallowSea-ams file path
| 4. 等待完成更新即可 | 4. wait until it finished the process
| …… | 5. Download 「switch_English_extra_package.zip」 from [here](https://github.com/carcaschoi/ShallowSea/releases/latest). Then unzip it to the root of the sd card. Replace all existing file. |
| [點此繼續查看使用方法](#%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-how-to-use) | [press here to continue read the guide (How to use)](#%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95-how-to-use) |

# 使用方法 How to use:
| 中文 | English |
| --- | ------- |
| * 硬破機不需做1.1/1.2步 | modchip switch don't need to do steps 1.1/1.2 |
| 1.1 . 用[tegrarcmgui](https://github.com/eliboa/TegraRcmGUI/releases/latest)注入release附有的payload.bin(the same payload in every releases, no any update)  | 1.1 . use [tegrarcmgui](https://github.com/eliboa/TegraRcmGUI/releases/latest) to inject the payload.bin enclose the releases(the same payload in every releases, no any update) |
| 1.2 . 或者[更新注入器檔案](https://github.com/carcaschoi/rcmloader-package)後，使用rcmloader注入(使用藍燈) | 1.2 . or using rcmloader(blue light) to inject payload after [updating rcmloader file](https://github.com/carcaschoi/rcmloader-package)
| 2. 進入hekate menu | 2. get into hekate menu |
| 3. 第一次使用的話建議創建虛擬系統，[大氣層&SXOS創建虛擬系統指南(點擊查看)](https://github.com/carcaschoi/ShallowSea/blob/main/create%20emuMMC%20guide%20(Chinese).md) | 3. recommended to create emuMMC/emunand if u r first time to hack switch |
| 4. 點選launch | 4. press 「launch」|
| 5. 如果你是使用大氣層，點選CFW Atmosphere ; 如果你是使用sxos，點選CFW SXOS，有虛擬系統的話它會自動引導到虛擬系統 | 5. press 「CFW Atmosphere」 if u r using atmosphere. press 「CFW SXOS」 if u r using sxos. They will launch emuMMC/emunand automatically if u have emuMMC/emunand |

# sxos轉大氣層指南 Change sxos to atmosphere
### 第1至3步用sxos 3.1.0，第4步之後用ShallowSea-ams
### First 3 steps use sxos 3.1.0, Then use ShallowSea-ams for later steps
| 中文 | English |
| --- | ------- |
| 1. 先到sxos破解系統用JKSV備份存檔 | get into sxos cfw & use JKSV to backup game save if possible |
| 2. (硬破機需做此步驟，只需做一次即可)先用sxos 3.1.0到sxos menu→options→sx core→clean up，之後到nand→repair GPT | (sx core/lite user need to to this step) use sxos 3.1.0 to get into sxos menu. Chooe options sx core clean up. Then choose nand repair GPT |
| 3. 保留Nintendo，license.dat，JKSV | Keep [Nintendo, license.dat, JKSV] and delete other file |
| 4. 解壓縮[大氣層整合包](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E6%9B%B4%E6%96%B0%E6%95%B4%E5%90%88%E5%8C%85%E6%8C%87%E5%8D%97-atmosphere-update-aio-package-guide)(ShallowSea-ams) | Download & unzip [AMS package](https://github.com/carcaschoi/ShallowSea/blob/main/User%20guide.md#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E6%9B%B4%E6%96%B0%E6%95%B4%E5%90%88%E5%8C%85%E6%8C%87%E5%8D%97-atmosphere-update-aio-package-guide)(ShallowSea-ams) |
| 5. 正常開機(軟破機需注入payload.bin)會進入hekate menu | It will boot to hekate menu when you turn on switch (RCM switch need to inject payload.bin)
| 6. (sxos有虛擬系統才需做此步驟)，[點擊查看步驟](https://github.com/carcaschoi/ShallowSea/blob/main/create%20emuMMC%20guide%20(Chinese).md#%E5%A4%A7%E6%B0%A3%E5%B1%A4%E5%89%B5%E5%BB%BAsd-file-%E8%99%9B%E6%93%AC%E7%B3%BB%E7%B5%B1-) | (you need to do this step if you have emuMMC when you are using sxos before) create emuMMC in hekate menu |
| 7. 每次開機選launch→CFW Atmosphere | press launch CFW Atmosphere |
| * . 如果硬破機出現boot0 error，[點擊查看方法](https://www.sthetix.info/generating-a-fresh-boot0-from-scratch-fix-your-switch-now/) | Follow [this guide](https://www.sthetix.info/generating-a-fresh-boot0-from-scratch-fix-your-switch-now/) if you have boot0 error |
| 8. 完成😎 | Finished😎
| 9. 有需要的話可以用JKSV還原存檔 | use JKSV to restore game saves if you needed
