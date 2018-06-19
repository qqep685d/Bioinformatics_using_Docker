# Dockerのインストール
_更新日: 2018年6月15日_

パソコンの基本情報の確認は[こちら](pc_spec.md)を参考にしてください。

## Windows 10 Professional / Enterprise (64-bit)

1. [Dockerダウンロードページ](https://store.docker.com/editions/community/docker-ce-desktop-windows)で「Docker Community Edition for Windows」をダウンロードします。
1. ダウンロード先フォルダにある「Docker for Windows Installer」をダブルクリックして、Dockerをインストールします。
1. インストール完了後、自動的にDockerが起動します。
1. ターミナル（Windows PowerShell）に`docker run --rm hello-world`を入力して、Enterを押して実行してください。
1. ターミナル画面に「Hello from Docker!（以下略）」が表示されれば、上手くインストールされています。

__Docker for Windowsの代わりに、下記のDocker Toolbox for Windowsをインストールしても構いません。__

## Windows 10 Home / 8.1 / 8 / 7（64-bit）

1. [Dockerダウンロードページ](https://docs.docker.com/toolbox/toolbox_install_windows/)で「Docker Toolbox for Windows」をダウンロードします。
1. ダウンロード先フォルダにある「Docker for Windows Installer」をダブルクリックして、Dockerをインストールします。
1. インストール完了後、自動的にDockerが起動します。
1. ターミナル（Windows PowerShell）に`docker run --rm hello-world`を入力して、Enterを押して実行してください。
1. ターミナル画面に「Hello from Docker!（以下略）」が表示されれば、上手くインストールされています。

## Windows (32-bit)

通常の方法では、Dockerのインストールが難しいので、下記サイトなどを参考にDockerをインストールしてください。
- [【2018年度版】32bitのWindowsにDocker環境を構築してみる](https://www.niandc.co.jp/sol/tech/date20180316_1645.php)

## Mac (OS X El Capitan 10.11 以降)

1. [Dockerダウンロードページ](https://store.docker.com/editions/community/docker-ce-desktop-mac)で「Docker for Mac」をダウンロードします。
1. ダウンロード先フォルダにある「Docker.dmg」をダブルクリックして、Dockerをインストールします。
1. インストール完了後、自動的にDockerが起動します。
1. ターミナルを開きます。
1. ターミナルに`docker run --rm hello-world`を入力して、Enterを押して実行してください。
1. ターミナル画面に「Hello from Docker!（以下略）」が表示されれば、上手くインストールされています。

## Mac (OS X Yosemite 10.10 以前)

1. [Dockerダウンロードページ](https://store.docker.com/editions/community/docker-ce-desktop-mac)で「Docker Toolbox for Mac」をダウンロードします。
1. ダウンロード先フォルダにある「DockerToolbox.pkg」をダブルクリックして、Dockerをインストールします。
1. Launchpad（ロケットアイコン）の中にある「Docker Quickstart Terminal」をクリックして、ターミナルを開いてください。
1. ターミナルに`docker run --rm hello-world`を入力して、Enterを押して実行してください。
1. ターミナル画面に「Hello from Docker!（以下略）」が表示されれば、上手くインストールされています。

## その他

- [Docker Store](https://store.docker.com/search?type=edition&offering=community)でパソコンのOSに合ったDockerをインストールしてください。  
__詳しくは、ダウンロードページを参考にしてください。__
