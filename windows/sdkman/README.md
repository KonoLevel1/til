# sdkman
Windowsにおけるsdkmanのあれこれ

# 導入


**前提条件**
* Git bash を導入済みであること

**.bashrc に下記を追加する**
```
export MSYS=winsymlinks:lnk
```
**下記のコマンドを入力して、SDKMANをインストールする**
```
$ curl -s "https://get.sdkman.io" | bash
```
**下記のコマンドを入力して、インストールを反映させる**
```
$ source "$HOME/.sdkman/bin/sdkman-init.sh"
```
```
"source"コマンドは、ファイルに書かれたコマンドを現在のシェルで実行するコマンドです。 
主にシェルの設定ファイルを反映させる際に使用します。
```

**下記のコマンドを入力して、SDKMANが無事導入できたか確認を行う**
```
sdk version
```