¶ [Home](./) | [ROM List](./docs/all-roms.md) | [GSI List](./docs/dl-aoslevel.md) | [Thanks](./docs/thanks.md) | [Changelog](./docs/changelog.md)
---

(｡･∀･)ﾉﾞHi~

## What is this? | 這是什麽？

- This is a project to collect GSI download link, you can choose a suitable GSI for your Android phone here and flash it.

  這是一個收集 GSI 下載地址的項目，您可以在此為您的設備挑選一個適合的 GSI 刷入。

## What is GSI? | 什麽是 GSI？

- Generic System Image (GSI).

  通用系統映像。

- You can visit [Android Developers](https://developer.android.com/topic/generic-system-image) for more information about it. ^^

  您可以訪問 [Android Developers](https://developer.android.com/topic/generic-system-image) 以獲取更多相關信息。^^

## GSI Naming Rules | GSI 命名規則

- **e.g. exTHmUI[^1]-arm64[^2]-11.0[^3]-20211211[^4]-b[^5]v[^6]N[^7]-vndklite[^8]-other[^9].img**

  |     Name 名稱     | Info 詳情                                                    |
  | :---------------: | ------------------------------------------------------------ |
  |    exTHmUI[^1]    | ROM name 「ROM 名稱」                                        |
  |     arm64[^2]     | Device architecture 「設備處理器架構」<br>1. arm64: ARM 64-bit<br>2. a64: ARM 32-bit with 64-bit binder<br>3. arm: ARM 32-bit |
  |     11.0[^3]      | ROM version 「ROM 版本」                                     |
  |   20211211[^4]    | ROM build time 「編譯日期」                                  |
  |       b[^5]       | a: A-only (system-as-system)<br>b: A/B (system-as-root)      |
  |       v[^6]       | v: Vanilla (No GApps included) 「不包含谷歌服務套件」<br>g: GApps 「包含谷歌服務套件」<br>o: GApps Go 「Android Go 谷歌服務套件」<br>f: Foss (Free & open source apps instead GApps) 「使用開源應用代替 GApps」 |
  |       N[^7]       | N: No superuser 「無超級使用者」<br/>S: Phh Superuser included 「包含超级使用者」<br/>Z: Dynamic superuser (Root can be enabled/disabled during use) 「動態超級使用者（Root 權限可隨時啟用/禁用） |
  | vndklite/lite[^8] | /system is read/write 「/system 分區可讀寫」                 |
  |     other[^9]     | secure: Remove Superuser and spoof system props for passing SafetyNet 「移除超級使用者和欺騙系統以通過 SafetyNet」 |

## Footnote | 註腳

- [^1]:Name 「名稱」
  [^2]:Device Architecture「設備處理器架構」
  [^3]: Version「版本」
  [^4]: Build Time 「編譯日期」
  [^5]: A-only & AB
  [^6]: GApps 「谷歌服務套件」
  [^7]: Superuser 「超級使用者」
  [^8]: r/w 「可讀寫」
  [^9]: Other「其他」
