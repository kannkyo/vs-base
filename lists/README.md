# vs-extensions

Visual Studio Codeのよく使う拡張機能のまとめ。

言語やフレームワーク別に拡張機能のリストを1つのファイルにまとめた。

以下のコマンドにより、1つのリストからインストールできる。

```shell
cd lists
cat python.txt | xargs -L1 code --install-extension
```

以下のコマンドにより、複数リストから一括インストールできる。

```shell
cd lists/general
cat *.txt | xargs -L1 code --install-extension
```
