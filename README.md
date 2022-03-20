# PlatformIO for VSCode 用 ATOM Babies 雛形

「Use this template」ボタンでクローンする場合，サブモジュールになっている ATOM Babies のライブラリ（[https://github.com/3110/atom-babies-arduino](https://github.com/3110/atom-babies-arduino)）がクローンされないので，クローンした後に以下を実行してください。

```bash
git submodule update --init --recursive
```
