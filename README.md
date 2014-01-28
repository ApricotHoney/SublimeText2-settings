SublimeText2-settings
=====================

Mac版SublimeText2の設定置き場

## 目次
* [PackageControlをインストール](#how-to-install)  
* [必要なPackageをインストール](#Add-Package)  
* [テーマを導入](#Add-Thema)   

## <a name="how-to-install">PackageControlをインストール
1. 以下のサイトを参照  
[PackageControl](https://sublime.wbond.net/installation#st2)

2. SublimeText2を起動して``Command + `(バッククオート)``でコンソールを開く

3. 先ほどコピーしたコードをペーストし、`Enter`を押す。

> 以下PackageControlがインストールされていることが前提

## <a name="Add-Package">必要なPackageをインストール
1. `Command + Shift + P`でコマンドパレットを開く

2. `Install Package`と入力後、`Enter`

3. 入れたいパッケージ名を入力して`Enter`

### 導入したパッケージ
* Angular JS
* Arduino-like IDE
* AutoFileName
* BracketHighlighter
* Compass
* ConvertToUTF8
* Ctags
* Emmet
* FuluentREPL https://github.com/zaneli/FluentREPL
* GitHub Flavored Markdown Preview
* Grunt
* Hayaku
* IMESupport
* jQuery
* Line Endings
* LiveReload
* Mac Terminal※
* Markdown Extended
* Markdown Preview
* Monokai Extended
* Nodejs
* Package Control -DefactStandard
* Pandoc
* PyV8 -automatic
* ReVIEW https://github.com/yanzm/ReVIEW
* Sass
* SASS Build
* SCSS
* SCSS Snippets
* SideBarEnhancements
* Stino-master -Arduino IDE
* SublimeCodeIntel
* SublimeLinter
* Tag
* Terminal※
* Theme - Flatland

## <a name="Add-Thema">テーマを導入
ついでにMarkdownのシンタックスハイライトにも対応しているテーマを導入する。  

1.  `Command + Shift + P`でコマンドパレットを開く

2. `Install Package`と入力後、`Enter`

3. `Monokai Extended`と入力後、`Enter`でテーマをインストールする。


## メモ
### Settings-User

	{
		//カラースキーム
		"color_scheme": "Packages/Monokai Extended/Monokai Extended Bright.tmTheme",
		"detect_slow_plugins": false,
		//Emmetで日本語変換をうまくできるように
		"disable_formatted_linebreak": true,
		//Emmetでtabでの展開を禁止
		"disable_tab_abbreviations": true,
		//tabのspace挿入を阻止
		"translate_tabs_to_space": false,
		//空白スペースを可視化
		"draw_white_space": "all",
		//フォントの種類
		"font_face": "Ricty Discord Regular",
		//フォントサイズ
		"font_size": 14.0,
		//Tabのサイズ
		"tab_size": 4,
		//行間
		"line_padding_top": 2,
		//カーソル行をハイライト
		"highlight_line": true,
		//使用しないパッケージ
		"ignored_packages":
		[
			"Vintage"
		],
		"rulers":
		[
			80
		],
		//テーマ
		"theme": "Flatland Dark.sublime-theme"
	}


### Key Bindings
`Key Bindings > User`を開いて以下を設定。  

	[
		{ 
			// Markdown Preview
			"keys": ["alt+m"], "command": "markdown_preview","args": {"target": "browser"}
		}
	]
