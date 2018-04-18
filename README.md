# Learn Swift

想學的東西太多，太貪心，時間太少。結果所有的東西都是略懂而已，沒有專精。這是我現在的窘境。

最近開始陪朋友練習學寫 iOS App 的開發，因為他們都選擇使用 Swift 來學習開發，所以我也就跟著開始練習使用 Swift 了。

## Swift for Windows

因為不是在辦公室或在家裡都有 Mac OS 環境能夠使用 Xcode 練習使用 Swift。所以我在家裡的 Windows 10 上安裝了 [Swift for Windows](https://swiftforwindows.github.io/) 來練習使用 Swift 程式語言寫程式。

### Environment Variables

在 cmd.exe 下必須先執行 C:\Swift\setPath.bat 增加 PATH 環境變數。

``` cmd.exe
> C:\Swift\setPath.bat
```

在 fish 底下，在 ~/.config/fish/config.fish 增加 PATH 環境變數。

``` fish
# Swift for Windows
set -gx PATH /cygdrive/c/Swift/mingw64/bin $PATH
set -gx PATH /cygdrive/c/Swift/wxWidgets-3.0.3/lib/gcc510TDM_x64_dll $PATH
set -gx PATH /cygdrive/c/Swift/usr/lib/swift/mingw $PATH
set -gx PATH /cygdrive/c/Swift/usr/bin $PATH
```

## Database

練習使用 [SQLiteDB wrapper](https://github.com/FahimF/SQLiteDB) 存取 SQLite 資料庫。