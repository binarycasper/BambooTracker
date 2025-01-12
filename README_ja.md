<!-- Icon & Title -->
<p align="center">
  <img src="./data/icons/128x128/apps/BambooTracker.png" alt="BambooTracker-icon">
  <h1 align="center">BambooTracker</h1>
</p>
<!-- Badges -->
<p align="center">
  <a href="https://github.com/BambooTracker/BambooTracker/releases">
    <img src="https://img.shields.io/github/v/release/BambooTracker/BambooTracker?color=brightgreen" alt="BambooTracker Version Number (autogenerated image)">
  </a>
  <img src="https://img.shields.io/badge/platforms-windows%20|%20macos%20|%20linux%20|%20bsd-yellow.svg" alt="BambooTracker Platforms: Windows, macOS, Linux, BSD">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/license-GPL--2.0%2B-orange" alt="BambooTracker License: GPL-2.0 or later">
  </a>
  <br>
  [Build Tests]<br>
  <a href="https://github.com/BambooTracker/BambooTracker/actions?query=workflow%3A%22Windows+10+%2864-bit%2C+Qt6%29%22">
    <img src="https://img.shields.io/github/actions/workflow/status/BambooTracker/BambooTracker/windows-10-qt6.yml?label=Windows%2010&logo=windows" alt="BambooTracker Build-Test Status on Windows (Qt6)">
  </a>
  <a href="https://github.com/BambooTracker/BambooTracker/actions?query=workflow%3A%22Windows+7+and+up+%2832-bit%2C+Qt5%29%22">
    <img src="https://img.shields.io/github/actions/workflow/status/BambooTracker/BambooTracker/windows.yml?label=Windows%207&logo=windows-xp" alt="BambooTracker Build-Test Status on Windows (Qt5)">
  </a>
  <a href="https://github.com/BambooTracker/BambooTracker/actions?query=workflow%3AmacOS">
    <img src="https://img.shields.io/github/actions/workflow/status/BambooTracker/BambooTracker/macos.yml?label=macOS&logo=apple" alt="BambooTracker Build-Test Status on macOS">
  </a>
  <a href="https://github.com/BambooTracker/BambooTracker/actions?query=workflow%3A%22Linux+%28Ubuntu%29%22">
    <img src="https://img.shields.io/github/actions/workflow/status/BambooTracker/BambooTracker/ubuntu.yml?label=Ubuntu&logo=ubuntu&logoColor=white" alt="BambooTracker Build-Test Status on Linux (Ubuntu)">
  </a>
  <a href="https://github.com/BambooTracker/BambooTracker/actions?query=workflow%3A%22Linux+%28Nixpkgs%29%22">
    <img src="https://img.shields.io/github/actions/workflow/status/BambooTracker/BambooTracker/ubuntu.yml?label=Nixpkgs&logo=nixos&logoColor=white" alt="BambooTracker Build-Test Status on Linux (Nixpkgs)">
  </a>
  <a href="https://ci.appveyor.com/project/BambooTracker/bambootracker">
    <img src="https://img.shields.io/appveyor/build/BambooTracker/BambooTracker?label=Appveyor&logo=appveyor&logoColor=white" alt="BambooTracker Development-Build Status">
  </a>
  <br>
  <a href="./README.md">English</a> | <a href="./README_ja.md">日本語</a>
</p>

BambooTrackerはNEC PC-8801/9801シリーズに搭載されていたFM音源YM2608(OPNA)向けのクロスプラットフォームのトラッカーです。

## 目次

1. [Wiki](#wiki)
2. [コミュニティ](#コミュニティ)
3. [対応言語](#対応言語)
4. [ダウンロード](#ダウンロード)  
  4.1. [リリース (Windows 7以降, Windows XP, macOS, Linux)](#リリース-windows-7以降,-windows-xp,-macos,-linux)  
  4.2. [開発版ビルド (Windows 7以降, Windows XP, macOS)](#開発版ビルド-windows-7以降,-windows-xp,-macos)  
  4.3. [パッケージ (macOS, Linux, BSD)](#packages-macos,-linux,-bsd)
5. [ショートカット](#ショートカット)
6. [エフェクトリスト](#エフェクトリスト)
7. [ファイル入出力](#ファイル入出力)
8. [ビルド方法](#ビルド方法)  
  8.1. [依存関係](#依存関係)  
  8.2. [コンパイル](#コンパイル)
9. [変更履歴](#変更履歴)
10. [ライセンス](#ライセンス)
11. [クレジット](#クレジット)

## Wiki

[BambooTracker GitHub Wiki](https://github.com/BambooTracker/BambooTracker/wiki)で以下の情報が得られます。

- トラッカーって何？
- BambooTrackerって何？何ができるの?
- インターフェースの使い方と操作方法
- BambooTrackerでYM2608を制御する方法

## コミュニティ

[公式Discordサーバー](https://discord.gg/gBscTMF)では、BambooTrackerユーザーや開発者、パッケージメンテナーとチャットしたり、助けを求めたり、他の人を助けたり、自分の曲をシェアしたりすることができます。

## 対応言語

現在、Bambootrackerでは以下の言語に対応しています。

- English / 英語 (デフォルト)
- 日本語
- Français / フランス語
- Polski / ポーランド語

## ダウンロード

### リリース (Windows 7以降, Windows XP, macOS, Linux)

リリースは、優れた安定したエクスペリエンスを提供する必要があるため、ほとんどのユーザーに推奨されます。

[![Release](https://img.shields.io/badge/Download-Release-brightgreen?style=for-the-badge)](https://github.com/BambooTracker/BambooTracker/releases/latest)

### 開発版ビルド (Windows 7以降, Windows XP, macOS)

開発版のビルドはコードの変更がベースリポジトリにコミットされるたびにビルドされ、アップロードされます。
そのため最新または開発中の機能や修正を提供しますが、通常の使用には最適化されていません。

[![Development Build](https://img.shields.io/badge/Download-Development%20Build-yellow?style=for-the-badge)](https://ci.appveyor.com/project/BambooTracker/bambootracker)

- ビルドの取得に関して、
  - 最新のマージされたコミットは、  
    `master -o- (英数字)`  
    と表示されている一番上のもの**のみ**参照してください。  
    `master -o- (英数字) ← 何らかのブランチ名 (英数字)`  
    ではありません。
  - 特定のPull Requestは、左上の
    `Pull request #(Pull Request ID)`  
    の表記を確認してください。

  それ以外は、Historyタブから必要な物をお探しください。
- "Job name"の欄に`APPVEYOR_JOB_NAME=for (OS名)`と書かれた行を見つけてクリックします。
- 開いたページで、右側の`Artifacts`タブをクリックすると、ダウンロードページが表示されます。

### パッケージ (macOS, Linux, BSD)

[![Packaging status](https://repology.org/badge/vertical-allrepos/bambootracker.svg)](https://repology.org/project/bambootracker/versions)

#### Nixpkgs (macOS, Linux)

Nixpkgsパッケージ: <https://search.nixos.org/packages?query=bambootracker>

宣言的インストール:

```nix
{
  environment.systemPackages = with pkgs; [
    bambootracker
  ];
}
```

強制インストール:

```sh
nix-env -iA nixpkgs.bambootracker
```

#### Debian / Ubuntu

```sh
sudo apt install bambootracker
```

#### Arch / Manjaro

AUR package: <https://aur.archlinux.org/packages/bambootracker-git>

#### FreeBSD

```sh
pkg install bambootracker
```

#### その他

[ビルド方法](#ビルド方法)の項を参照してください。

## ショートカット

*[KEYCOMMANDS.md](./KEYCOMMANDS.md)を参照してください。*

## エフェクト一覧

*[EFFECTLIST.md](./EFFECTLIST.md)を参照してください。*

## ファイル入出力

*[FILEIO.md](./FILEIO.md)を参照してください。*

## ビルド方法

### 依存関係

BambooTrackerをビルドする際には全てのプラットフォームで以下の依存関係を用意してください。

- Qt (5.5以降)
- Qt Tools (qmake, lrelease, ...)
- QtでサポートされているC++コンパイラ (GCC, Clang, MSVC, ...)
- make

それ以外の必須/オプションの依存関係を取得する方法は、OS(ディストリビューション)ごとに異なります。

#### Windows

- C++コンパイラ: いずれかを利用できます。
  - MinGW  
    Qtインストーラにバンドルされているオプションを使用することをお薦めします。  
    それ以外のものを使用する場合は、QtのドキュメントでQtのバージョンと互換性のあるGCCのバージョンを確認してください。
  - Clang  
    未テストですが恐らく動作します。
  - MSVC  
    [Visual Studio](https://visualstudio.microsoft.com)にバンドルされているものか、スタンドアロン版("Build Tools for Visual Studio 2019"のダウンロードを確認してください)
- [Qt](https://www.qt.io/download-qt-installer)
  古いバージョンのQt(XPビルドなど)では、自分でチェックアウトしてコンパイルする必要があるかもしれませんが、公式のプリビルド版はQtによって削除されました。

#### macOS

ここではHomebrew & Qt5を用いた導入方法を紹介します。

- C++コンパイラ: Xcode Command Line Tools  
  (開発者はmacOSを使っていないので、導入方法については検索してください。すみません)
- Qt5:  

```bash
brew install qt5
```

**オプションの依存関係**:

- JACK: このリポジトリに含まれるRtAudio / RtMidiでのJACKサーバへの接続をサポートします。  
  JACK(バージョン1または2)のヘッダとライブラリが必要です。  

  ```bash
  brew install jack
  ```

  オプション: pkg-configによってこの処理をスキップできますが、JACKのヘッダやライブラリの検出が困難になる可能性があります。  

  ```bash
  brew install pkg-config
  ```

- RtAudio / RtMidi: このリポジトリで含んでいるものの代わりにコンパイル済みのRtAudio / RtMidiを使います。  
  (上記のオプションの依存関係は削除されます)  
  RtAudio (5.1.0以降)と/またはRtMidi (4.0.0以降) + pkg-configが必要です。

  ```bash
  brew install rt-audio rt-midi pkg-config
  ```

#### Linux

依存関係のインストールは、お使いのディストリビューションとパッケージマネージャに大きく依存します。  
お使いのディストリビューションの項を参照し、インストール手順をテストセットを確認してください。

**追加の依存関係**:

- ALSA: 最小限のオーディオとMIDIをサポートするために必要です。  
  ALSAのヘッダとライブラリが必要です。

**オプションの依存関係**:

- PulseAudio: リポジトリに含まれるRtAudioでPulseAudioサーバーへの接続をサポートします。  
  PulseAudioのヘッダとライブラリが必要です。  
  オプション: pkg-configによってこの処理をスキップできますが、PulseAudioのヘッダやライブラリの検出が困難になる可能性があります。
- JACK: リポジトリに含まれるRtAudio / RtMidiでPulseAudioサーバーへの接続をサポートします。  
  JACK(version 1または2)ののヘッダとライブラリが必要です。  
  オプション: pkg-configによってこの処理をスキップできますが、JACKのヘッダやライブラリの検出が困難になる可能性があります。
- RtAudio / RtMidi: このリポジトリで含んでいるものの代わりにコンパイル済みのRtAudio / RtMidiを使います。  
  (上記のオプションの依存関係は削除されます)  
  RtAudio (5.1.0以降)と/またはRtMidi (4.0.0以降) + pkg-configが必要です。

##### Debian / Ubuntu

```bash
# Optional dependencies
OPTIONALDEPS=""

# PulseAudio
OPTIONALDEPS="$OPTIONALDEPS libpulse-dev"

# Either:
# JACK 1
OPTIONALDEPS="$OPTIONALDEPS libjack-dev"
# JACK 2
OPTIONALDEPS="$OPTIONALDEPS libjack-jackd2-dev"

# Either / Both:
# System-RtAudio
OPTIONALDEPS="$OPTIONALDEPS librtaudio-dev"
# System-RtMidi
OPTIONALDEPS="$OPTIONALDEPS librtmidi-dev"

# Install dependencies
apt install \
  build-essential \
  qt5-default qttools5-dev-tools \
  libasound2-dev \
  $OPTIONALDEPS
```

##### Arch Linux / Manjaro

```bash
# Optional dependencies
OPTIONALDEPS=""

# PulseAudio
OPTIONALDEPS="$OPTIONALDEPS libpulse"

# Either:
# JACK 1
OPTIONALDEPS="$OPTIONALDEPS jack"
# JACK 2
OPTIONALDEPS="$OPTIONALDEPS jack2"

# Either / Both:
# System-RtAudio
OPTIONALDEPS="$OPTIONALDEPS rtaudio"
# System-RtMidi
OPTIONALDEPS="$OPTIONALDEPS rtmidi"

# Install dependencies
pacman -S \
  qt5-tools \
  alsa-plugins \
  $OPTIONALDEPS
```

#### BSD

以下を除けばLinuxと同じです:

- ALSAはオプションです。
- OSS4のヘッダとライブラリが必須です。

(もしあなたがBSDシステム上でBambooTrackerを手動でコンパイルできた場合は、Pull Requestを開いて依存関係のインストール手順をここに追加してください!)

### コンパイル

これらのコンパイル手順はCLIの使用を前提としていますが、代わりにQt CreatorのようなIDEを使用することも可能です。
これらは一般的にすべてのプラットフォームで動作するはずですが、特定の変更点については以下の項で言及しています。

Qmakeのオプション (フラグ/スイッチ):

- PREFIX: ビルド後にインストールする場所です。  
  デフォルト:  
  - Windows: `C:\BambooTracker`  
  - macOS/Linux/BSD: `/usr/local`  
  例: `PREFIX=C:\Users\Owner\Programs\BambooTracker`
- CONFIG  
  複数回指定して複数のオプションを追加することができます。  
  オプションの追加には`+=`を、削除には`-=`を使用してください。
  - debug: デバッグビルド。クラッシュをデバッグする際に有用です。
  - release: リリースビルド。デバッグビルドよりも最適・コンパクトにビルドします。
  - install_flat: インストール時にPREFIX下のLinux FHSパスを使用しません。(Windowsではデフォルトで有効)
  - install_minimal: 不要なファイルのインストールをスキップします。
  - use_alsa: 明示的にALSA<sup>1</sup>に対応したリポジトリに含まれるRtAudioとRtMidiをコンパイルします。(Linuxではデフォルトで有効)
  - use_oss: 明示的にOSS4<sup>2</sup>に対応してコンパイルします。(BSDではデフォルトで有効)
  - use_pulse: 明示的にPulseAudio<sup>1</sup>に対応したリポジトリに含まれるRtAudioをコンパイルします。
  - use_jack: 明示的にJACK 1/2<sup>13</sup>に対応してコンパイルします。
  - system_rtaudio: RtAudioのコンパイルをスキップし、代わりにシステムのインストールされているRtAudioにリンクします。
  - system_rtmidi: RtMidiのコンパイルをスキップし、代わりにシステムのインストールされているRtMidiにリンクします。
  - real_chip: SCCIとC86CTLに対応したコンパイルを行います<sup>4</sup>。(Windowsではデフォルトで有効)

<sup>1</sup>: LinuxとBSDでのみ動作します。  
<sup>2</sup>: FreeBSDでは自動検出されます(?)が、RtAudioでは機能しない可能性があります。  
<sup>3</sup>: APIは技術的にはWindowsでサポートされていますが、Rtライブラリではコンパイルが困難なようです。  
<sup>4</sup>: OSI認証ライセンスを使用しないコードをビルドします。これらはWindowsにのみ対応しています。

例:

```bash
# Where you want to locally keep the source code clone
cd /home/owner/devel

# Replace --recurse-submodules with --recurse-submodules=submodules/emu2149/src if CONFIG+=system_rtaudio AND CONFIG+=system_rtmidi will be used
git clone https://github.com/BambooTracker/BambooTracker --recurse-submodules
cd BambooTracker

# Configure
qmake PREFIX=/usr/local CONFIG-=debug CONFIG+=release CONFIG+=use_alsa CONFIG+=use_pulse CONFIG+=use_jack

# Recursively initialises subprojects properly, dependency tests may be flakey if run multithreaded
make qmake_all

# Compile with 4 threads
make -j4

# Installs to PREFIX
make install
```

#### Windows

上記の手順を始める前に、Qtとコンパイラをセットアップしたシェルに入ります。(Qtのインストーラには、このために使えるスクリプトが追加されています)

- MinGWを使う場合は`make`ではなく`mingw32-make` / `mingw64-make`を使って下さい.
- MSVCを使う場合は**TODO**。

Qt Creatorを使用すると、よりグラフィカルなコンパイル処理を行うことができます。

#### macOS

pkg-configを使わずにHomebrewのJACKを使用する際は、`qmake`にいくつかの引数を渡します:
 `LIBS+=-L/usr/local/opt/jack/lib INCLUDEPATH+=/usr/local/opt/jack/include`

##### FreeBSD

BambooTrackerはFreeBSDのポートを使ってビルドすることができます。

```bash
cd /usr/ports/audio/bambootracker
make install clean
```

## 変更履歴

*[CHANGELOG.md](./CHANGELOG.md)を参照してください。*

## ライセンス

このプログラム及びソースコードのライセンスははGNU General License Version 2及びそれ以降のバージョンです。

*詳細は[LICENSE](./LICENSE)と[licenses/list.md](./licenses/list.md)を参照してください。*

## クレジット

このアプリの作成において、以下の方々にお世話になっております。ありがとうございます。

- Qt
- MAME YM2608のエミュレーションコードに関してTatsuyuki Satohさん，Jarek Burczynskiさん，Valley Bellさん
- emu2149に関してDigital Sound Antiquesさん
- トラッカーのアイコンに関してDecidettoさん
- その他のアイコンに用いているSilk iconsに関してMark Jamesさん
- VGMファイルのフォーマットのドキュメントに関してVGMRipsチームの方々
- トラッカーのUIやルーチンに関して多くのトラッカー作成者様、特に0CC-FamiTrackerのHertzDevilさん、Deflemask TrackerのLeonardo Demartino (delek)さん、GoatTrackerのLasse Öörni (Cadaver)さん、Furnace Trackerのtildearrowさん
- サンプル曲を提供してくださったmaakさん、SuperJet Spadeさん、Dippyさん、RigidatoMSさん、ImATrackManさん
- サンプルインストゥルメントを提供してくださったpapiezakさん、阿保　剛さん
- サンプルカラースキームを提供してくださったYuzu4Kさん
- WOPNインストゥルメントのフォーマットファイルに関してVitaly Novichkov (Wohlstand)さん
- S98ファイルのフォーマットのドキュメントに関してRu^3さん
- SCCIライブラリに関してがし３さん
- C86CTLライブラリに関してhonetさん
- RtAudioとRtMidiライブラリに関してGary P. Scavoneさん他
- Nuked OPN-Modエミュレーションに関してAlexey Khokholov (Nuke.YKT)さん、Jean Pierre Cimalandoさん
- フランス語翻訳に関してJean Pierre Cimalandoさん、Olivier Humbertさん
- ポーランド語翻訳に関してfreq-modさん、Midoriさん
- ADPCMエンコーダ/デコーダに関してIan Karlssonさん
- ymfmに関してAaron Gilesさん
- リサンプリングライブラリに関してShay Greenさん
- そしてこのプロジェクトに手助けしてくださるみなさん!
