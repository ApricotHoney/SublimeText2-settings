SublimeText3-settings
=====================

Mac版SublimeText3の設定置き場

## PackageControlをインストール
1. 以下のサイトを参照するか下記のコードをコピー  
[PackageControl](https://sublime.wbond.net/installation#st3)
```
import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = 
sublime.installed_packages_path();       urllib.request.install_opener( 
urllib.request.build_opener( urllib.request.ProxyHandler()) ); 
open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 
'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
```

2. SublimeText3を起動して``Command + `(バッククオート)``でコンソールを開く

3. 先ほどコピーしたコードをペーストし、`Enter`を押す。

> 以下PackageControlがインストールされていることが前提

## 必要なPackageをインストール
1. `Command + Shift + P`でコマンドパレットを開く

2. `Install Package`と入力後、`Enter`

3. 入れたいパッケージを探して`Enter`
