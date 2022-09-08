# Dev Container + Rails + vscode-rdbg (debug.gem)

設定済みの Rails + [vscode-rdbg](https://github.com/ruby/vscode-rdbg)([debug.gem](https://github.com/ruby/debug)) 環境を [Dev Container](https://code.visualstudio.com/docs/remote/containers) で提供する実験です。

![debug-demo](https://user-images.githubusercontent.com/60980/189170864-f443cb07-99d5-4ac1-978b-7d7f0b163e83.gif)

## 試し方

1. Visual Studio Code Remote - Containers エクステンションをインストール
2. rails-debug-sample フォルダーを開く
3. Reopen in Container
4. bundle exec rails setup
5. 実行 > デバッグの開始
