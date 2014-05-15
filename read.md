# Markdownについて
&nbsp;  
今回のマークアップミーティング、最近若干盛り上がってる感のあるMarkdownについて紹介したいと思います。  
&nbsp;
&nbsp;
&nbsp;
&nbsp;
## Markdownって何？？  
&nbsp;  
Markdownのような言語は軽量マークアップ言語と呼ばれています。
本家サイトには以下のように説明があります。
>Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to->read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).
>  
>Markdownは、ライターのためのテキストからHTMLに変換するツールです。Markdownは読みやすく、書きやすいプレーンテキストフォーマットで、正しいXHTML(HTML)へ変換できます。

他の軽量マークアップ言語では「はてな記法」や「PukiWiki記法」などがありますね。他にもいろいろとあるようです。
  
<a href="http://ja.wikipedia.org/wiki/%E8%BB%BD%E9%87%8F%E3%83%9E%E3%83%BC%E3%82%AF%E3%82%A2%E3%83%83%E3%83%97%E8%A8%80%E8%AA%9E" target="_blank">wikipedia: 軽量マークアップ言語</a>

&nbsp;
&nbsp;
## どこで使われているの？？
&nbsp;  
Markdownを採用しているWebサービスやアプリケーションは実は結構あります。  
* Tumblr
* Github
* Bitbucket
* Backlog
* WordPress.com
  
&nbsp;  
WordPress.comにはMarkdownの<a href="http://en.support.wordpress.com/markdown-quick-reference/" target="_blank">リファレンス</a>もあります。  
WordPressで作られたWebサイトでもJetpackプラグインを使用すれば、投稿画面でMarkdownを使う事ができるようです。  
このドキュメントもMarkdownで書かれています。  
&nbsp;  
&nbsp;  
## どうやって書くの？？
&nbsp;  
&nbsp;  
記述方法も簡単なのでHTMLに慣れていない人でも覚えやすいと思います。  
こちらのオンラインエディタを使用すると即HTMLに変換されるので分かりやすいです。
<a href="http://dillinger.io/">Dillinger</a>
&nbsp;  

###  見出し  
~~~~
#これはh1です  
##これはh2です  
###これはh3です
~~~~
#これはh1です
##これはh2です
###これはh3です
&nbsp;  
&nbsp;  
###  リスト
~~~~
* りんご
* ぶどう
* バナナ
~~~~

* りんご
* ぶどう
* バナナ

この書き方でも
~~~~
- りんご
- ぶどう
- ばなな
~~~~
- りんご
- ぶどう
- ばなな

この書き方でも
~~~~
+ りんご
+ ぶどう
+ ばなな
~~~~
+ りんご
+ ぶどう
+ ばなな
&nbsp;  
&nbsp;  
&nbsp;  

### 番号付きリスト
~~~~
1. りんご
2. ぶどう
3. ばなな
~~~~
1. りんご
2. ぶどう
3. ばなな

&nbsp;  
&nbsp;  
&nbsp;  

### 引用
~~~~
>引用文引用文引用文引用文引用文
>引用文引用文引用文引用文引用文
>引用文引用文引用文引用文引用文
~~~~
>引用文引用文引用文引用文引用文  
>引用文引用文引用文引用文引用文  
>引用文引用文引用文引用文引用文  

&nbsp;  
&nbsp;  
&nbsp;  

### 改行
改行はスペース2回！

&nbsp;  
&nbsp;  
&nbsp;  

### リンク
~~~~
[Hivelocity](http://www.hivelocity.co.jp)
~~~~
[Hivelocity](http://www.hivelocity.co.jp)

&nbsp;  
&nbsp;  
&nbsp;  

### 画像
~~~~
![画像の説明](https://raw.githubusercontent.com/github/media/master/octocats/octocat.png)
~~~~
![画像の説明](https://raw.githubusercontent.com/github/media/master/octocats/octocat.png)

### テーブル

~~~~
野菜|果物|きのこ|
----|-----|-----|
白菜 |りんご|しいたけ|
とまと|ぶどう|なめこ|
クレソン|梨|エリンギ|
~~~~

野菜| 果物 |きのこ|
----|-----|-----|
白菜 |りんご|しいたけ|
とまと|ぶどう|なめこ|
クレソン|梨|エリンギ|

&nbsp;  
&nbsp;  
&nbsp;  

## コードブロック
~~~~
    ~~~~
    $('a.btn').on('click', function() { alert('Hellow World!'); });
    ~~~~
~~~~
~~~~
    $('a.btn').on('click', function() { alert('Hellow World!'); });
~~~~

&nbsp;  
&nbsp;  
&nbsp;  
## あとがき


いかがだったでしょうか？
比較的覚えやすいと感じたのではないでしょうか？？  
テーブルなんてHTMLを覚えるよりも遥かに簡単なので、  
普段HTMLを書かないライターさんにもオススメだと思います。  
エンジニアさんもMarkdownでwikiなどを書く機会も増ていくのではないかと思うので覚えてても損はないかもしれませんねー。  

おわり

