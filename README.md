# SampleWindowsFormsApp_label
Healing Agent による自己修復を検証する際に利用可能な Windows アプリのサンプルコードです。

---

## 最新の更新情報

- **バージョン 1.0.0 のリリース (2025-04-02)**: 初期バージョンです。

---

## 説明

Microsoft Visual Studio Community 2022 で開発したものです。  
利用手順は以下の通りです。

- ソースコードを Clone します。

- Visual Studio で Clone した環境を開きます。

- [ビルド] -> [ソリューションのビルド] を実行し、EXE ファイルを作成します。
  - <ユーザー名>\source\repos\SampleWindowsFormsApp_label\SampleWindowsFormsApp\bin\Debug フォルダなどに **SampleWindowsFormsApp.exe** ファイルが生成されます。

- **SampleWindowsFormsApp.exe** を任意の場所にコピーして利用します。

- （補足）登録画面の下にあるボタン名は "エントリー" になっています。この部分を任意のラベルへ変更しに再ビルドすることで、オブジェクト認識させるバージョンと Healing Agent による自己修復が行われるバージョンなどを用意してください。

This was developed using Microsoft Visual Studio Community 2022.  
The usage procedure is as follows.

- Clone the source code.

- Open the cloned environment in Visual Studio.

- Execute [Build] -> [Build Solution] to create an EXE file.
  - A **SampleWindowsFormsApp.exe** file will be generated in the <username>/source/repos/SampleWindowsFormsApp_label/SampleWindowsFormsApp/bin/Debug folder, etc.

- Copy **SampleWindowsFormsApp.exe** to a location of your choice and use it.

- (Additional Information) The button at the bottom of the registration screen is labeled “エントリー”. Change this to a label of your choice and rebuild to create versions that can be Object Recognized and can be Self-Healed by the Healing Agent.
