# tabilog

A new Flutter project.

# 環境構築

参考：https://qiita.com/tomy0610/items/896dc8ec9ba95c33194f

0.事前作業<br>
・Android Studio<br>
https://akira-watson.com/android/adt-mac.html<br>
・X-code<br>
>sudo xcodebuild -runFirstLaunch
CocoaPodsインストール<br>
>sudo gem install cocoapods
>pod setup

1.インストール<br>
https://flutter.dev/docs/get-started/install/macos<br>
2.ホーム直下に好きなディレクトリ作成（ここではdevelopmentとする）<br>
>mkdir development
>cd development
4.解凍<br>
>unzip ~/Downloads/flutter_macos_1.17.1-stable.zip
5.PATHを通す<br>
>vi .zprofile
以下追記<br>
>export PATH="$PATH:$HOME/development/flutter/bin"
6.パスが表示されればOK<br>
>which flutter
7.チェック<br>
>flutter doctor
エラーがなくなるまで実行<br>
※Connected deviceのみ無視でOK<br>
8.アプリ起動<br>
>cd tabilog
>open -a Simulator
>flitter run
