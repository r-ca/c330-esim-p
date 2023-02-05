### Rakuten Mini(C330)用eSIM有効化モジュール(+α)

Rakuten Mini(C330)に焼いたPieのGSIでeSIMを管理できるようしたりするモジュールです\n
forked by AndroPlus-org/magisk-module-c330-gsi

## 機能一覧
- ~~ブートループを修正 (Xiaomi Redmi 8 の android.hardware.graphics.composer@2.1-impl.so 等を流用)~~ ←Android9向けフォークのため削除されています
- VoLTE を有効化 ~~(楽天モバイルにてテスト済み)~~ ←9移植後に動作テストが出来ていません
- FlokoROM などで、クイック設定での FPS 表示タイルを有効化 (表示させるには初回のみ`adb shell cmd overlay enable me.phh.treble.overlay.rakuten.mini.systemui`の実行が必要)
- FeliCa / おサイフケータイアプリを追加 (ただしエラーで使用不可)
- eSIM の管理画面を追加

## TODO
- おサイフケータイアプリのエラー修正
