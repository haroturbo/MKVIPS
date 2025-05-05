📘 概要
MKVIPS は、PSP（PlayStation Portable）向けの MIPS アセンブリコードを解析・デバッグ・変換するための Windows 用ツールです。Visual Basic .NET で開発されており、GUI ベースで操作可能です。主に PSP のチートコードや自作アプリケーションの開発支援を目的としています。

🧩 主な機能
PSP 用 MIPS アセンブリコードの解析と可視化

バイナリファイルの逆アセンブル機能

チートコードの作成・編集・変換機能

コードページの変更や文字コードの変換機能

GUI ベースの直感的な操作

🗂️ ディレクトリ構成
CLASS/：アプリケーションの主要なクラスファイルが含まれています。

My Project/：プロジェクト設定やリソースファイルが含まれています。

bin/Release/：ビルド済みの実行ファイルが出力されるディレクトリです。

Form1.vb、Form2.vb：メインフォームおよびサブフォームのコードファイルです。

codepage.vb：文字コード変換に関連する機能を提供するモジュールです。

ver.vb：バージョン情報を管理するモジュールです。

MK_VIPS.sln、MK_VIPS.vbproj：Visual Studio 用のソリューションおよびプロジェクトファイルです。

🛠️ ビルド手順
Visual Studio の準備：Visual Studio（推奨バージョンは 2010 以降）をインストールします。

リポジトリのクローン：以下のコマンドでリポジトリをクローンします。

bash
コピーする
編集する
git clone https://github.com/haroturbo/MKVIPS.git
プロジェクトの読み込み：MK_VIPS.sln を Visual Studio で開きます。

依存関係の確認：必要なライブラリや参照設定が正しく構成されていることを確認します。

ビルドの実行：「ビルド」メニューから「ソリューションのビルド」を選択し、ビルドを実行します。
GitHub

🔗 関連リンク
GitHub リポジトリ：https://github.com/haroturbo/MKVIPS

旧公式ウェブページ（アーカイブ）：https://web.archive.org/web/20230204142913/http://ijiro.daiwa-hotcom.com/data/mkvips.html

開発者のブログ：https://haroturbo.blog70.fc2.com/
