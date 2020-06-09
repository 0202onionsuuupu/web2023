# GitHub Pages で、じぶんのウェブサイトをつくろう！

## ひとまず作ってみよう！

1. GitHubアカウントを作る [Sign up for GitHub](https://github.com/)（ウェブサイトの名前の一部になるのでいい名前を付けましょう）
2. このリポジトリを右上にあるForkを押して自分のリポジトリとしてコピーする
3. 自分のリポジトリの設定(Settings)を開く
4. GitHub Pages の項目までスクロールし、Sourceを[master brunch]に変更する
5. もう一度 GitHub Pages の項目までスクロールすると書いてあるリンクを新しいウィンドウで開いておく
6. すぐには表示されないので、待っている間にカスタマイズ！自分のリポジトリの index.html を開く
7. 右上の鉛筆マークで編集モードにする
8. &lt;h1&gt;たいとる&lt;/h1&gt;とあるところを好きなタイトルに変える
9. 画面下の「commit changes」を押す
10. さっき開いたウィンドウをリロードしてみる
11. 数分すると、編集したタイトルに変わる！
12. 以降、編集、コミット、ちょっと待って、反映でウェブサイトづくりができる

## 画像をつけよう

1. pngかjpg画像を準備する
2. 半角英数字を使った空白を含まないファイル名に変更する （日本語名やトラブルの元になる）
3. [Upload files]を押す
4. 画像ファイルをドロップして、コミットする
5. index.html を編集する
6. &lt;img src="imgfile.jpg"&gt; と、&lt;h1&gt;タイトル&lt;/h1&gt; の前の行に書く (imgfile.jpg はアップロードしたファイル名に）
7. コミットし、しばらく待って、リロードすると表示される！

もう少し詳しく？ → HTMLはじめのいっぽ  
https://github.com/code4sabae/website/blob/master/what_is_html.md

## GitHub Desktop を使って効率アップ！

1. [GitHub Desktop](https://desktop.github.com/)をダウンロードする
2. 自分のリポジトリの右側[clone or download]を押し、[Open in Desktop]を押す
3. ダウンロードするフォルダをローカルパスとして指定し[Clone]する
4. ダウンロードしたフォルダの中の index.html をブラウザで開くと表示される
5. [VSCode](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)などのエディタを使って、index.html や index.css を編集し、サイトをつくる
6. GitHub Desktop で、コミットする（更新用のメモは必須、”更新”など、一言でもOK！）
7. [Fetch origin] を押し、サーバーにプッシュする
8. しばらく待つと、反映される

## ドメイン名だけでアクセスできるようにしよう

[Settings]で、リポジトリ名を (自分のGitHubアカウント名).github.io に変更すると、そのアドレスでアクセスできます！短くてかっこいいですね！

## 独自ドメインを設定しよう

1. ドメインを用意する
2. [Settings]のGitHub Pagesの Custom domain に、設定したいドメイン名を書き[Save]する
3. 管理するドメインのサービスの設定画面へ行き、下記のようにDNSを設定する （4つのIPアドレスがGitHub Pagesを指しています [詳細](https://help.github.com/ja/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site))
```
A	@	185.199.108.153
A	@	185.199.109.153
A	@	185.199.110.153
A	@	185.199.111.153
```
4. DNSの設定が伝搬し有効になるまで待つ
5. 独自ドメインでアクセスしてみる

## サイトを育てましょう！

HTMLはじめのいっぽ  
https://github.com/code4sabae/website/blob/master/what_is_html.md  

## わからないこと？

こちらのIssuesに分からないことをどうぞ！  
https://github.com/code4sabae/website/issues  
