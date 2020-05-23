# tabilog

A new Flutter project.

# 環境構築

参考：https://qiita.com/tomy0610/items/896dc8ec9ba95c33194f

0.事前作業
・Android Studio
https://akira-watson.com/android/adt-mac.html
・X-code
>sudo xcodebuild -runFirstLaunch
CocoaPodsインストール
>sudo gem install cocoapods
>pod setup

1.インストール
https://flutter.dev/docs/get-started/install/macos
2.ホーム直下に好きなディレクトリ作成（ここではdevelopmentとする）
>mjdir development
>cd development
4.解凍
>unzip ~/Downloads/flutter_macos_1.17.1-stable.zip
5.PATHを通す
>vi .zprofile
以下追記
>export PATH="$PATH:$HOME/development/flutter/bin"
6.パスが表示されればOK
>which flutter
7.チェック
>flutter doctor
エラーがなくなるまで実行
※Connected deviceのみ無視でOK
8.アプリ起動
>cd tabilog
>open -a Simulator
>flitter run
