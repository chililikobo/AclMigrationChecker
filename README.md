# ACL Migration Checker

[![Latest Release](https://badgen.net/github/release/chililikobo/AclMigrationChecker)](https://github.com/chililikobo/AclMigrationChecker/releases/latest)
[![Downloads](https://badgen.net/github/assets-dl/chililikobo/AclMigrationChecker)](https://github.com/chililikobo/AclMigrationChecker/releases/latest)
[![License](https://badgen.net/badge/license/Freeware/purple)](#-terms-of-use--disclaimer)
[![Platform](https://badgen.net/badge/platform/Windows/black)](#-installation-portable)

[English](#english) | [日本語](#日本語)

---

## English

ACL Migration Checker is a dedicated checking tool designed to verify that access control lists (ACLs) are correctly transferred without discrepancies during data migration on file servers and storage servers. 

It is especially powerful for verifying permission reconfigurations and preventing human error in Workgroup environments where SID migration is difficult, as well as in standard Active Directory environments.

🌐 **For detailed specifications and support, please visit the [Official Website](https://chililikobo.github.io/en/).**

### 🚀 Installation (Portable)

No installation or special configuration is required. Simply place the downloaded folder (containing `AclMigrationChecker.exe` and its required DLL files) in your preferred location and run the executable. To uninstall, just delete the entire folder.

**Portable Design:** This software is designed to be fully portable. You can save the folder to a USB drive or external storage and easily run it on any compatible PC without needing administrative installation or additional .NET Runtime.

* **Supported OS**: Windows 10 / Windows 11
* **Supported OS (Server)**: Windows Server 2016 / 2019 / 2022 / 2025

### 🛠 Key Features & Usage

#### 1. ACL Scanning and Saving
Run the software to scan and save the access rights information for both the migration source and destination. It saves the data in a compressed, lightweight JSON.GZ format.

#### 2. Pre/Post Migration Comparison
Load the saved source and destination data into the application. It will automatically detect and list missing permissions, excessive privileges, and account mismatches.

#### 3. CSV Export of Results
Click the "Export CSV" button to save the comparison results. This is highly useful for post-migration reporting and creating action lists for correcting access rights.

#### 4. Multilingual UI Support
Automatically adapts to the OS language settings, providing a seamless experience in both English and Japanese.

### 📄 Terms of Use & Disclaimer

* **License**: This software is freeware and can be used free of charge by both individuals and corporations.
* **Distribution**: Redistribution is prohibited. Please link to the official website instead.
* **Privacy**: This software does not transmit logs or scan results to any external servers.
* **Disclaimer**: This software is provided "As-Is" without any warranty. The author shall not be liable for any damages arising out of its use. Use at your own risk.

### 📚 Credits (External Libraries)
* Avalonia UI Framework (MIT License)
* CommunityToolkit.Mvvm (MIT License)
* System.IO.FileSystem.AccessControl (MIT License)

---

## 日本語

ACL Migration Checkerは、ファイルサーバーやストレージサーバーのデータ移行（マイグレーション）において、移行元と移行先のアクセス権（ACL）に差異がないかを検証するための専用チェックツールです。

Active Directory環境での移行はもちろんのこと、SID（セキュリティ識別子）の移行が困難なWorkgroup環境における権限の再設定・付け直し作業の確認・検証に強力な威力を発揮します。

🌐 **詳細な仕様やサポート情報については、[公式ホームページ](https://chililikobo.github.io/) をご覧ください。**

### 🚀 インストール (ポータブル対応)

インストール作業や特別な設定は不要です。ダウンロードしたフォルダ（`AclMigrationChecker.exe` と必要なDLLファイルが含まれています）を任意の場所に配置するだけで使用できます。アンインストールはフォルダごと削除するだけです。

**ポータブル設計:** 本ソフトウェアはポータブルに設計されており、USBメモリ等に入れて持ち運ぶことが可能です。.NETランタイム等の追加インストールは一切不要で、様々なPCですぐに起動して利用できます。

* **対応OS**: Windows 10 / Windows 11
* **対応OS (サーバー)**: Windows Server 2016 / 2019 / 2022 / 2025

### 🛠 主な機能と使い方

#### 1. アクセス権（ACL）のスキャンと保存
移行元および移行先のフォルダ・ファイルに対して本ソフトを実行し、設定されているACL情報を取得します。データは圧縮された軽量なJSON.GZ形式で保存されます。

#### 2. 移行前後の差分比較
保存した移行元と移行先のデータを本ソフトに読み込みます。取得した2つのACL情報を突き合わせ、権限の欠落や過剰な付与、アカウントの不一致などを自動で検出・リストアップします。

#### 3. 比較結果のCSVエクスポート
「CSVエクスポート」ボタンを押すことで、検出された差異の一覧を出力できます。移行後のレポート作成や、アクセス権の修正作業用のチェックリストとして活用可能です。

#### 4. 多言語対応 (日本語 / 英語)
OSの言語設定に合わせて自動的にインターフェース言語が切り替わり、幅広い環境でスムーズに利用できます。

### 📄 利用規約・免責事項

* **ライセンス**: 本ソフトウェアはフリーウェアです。個人・法人を問わず、無料で利用可能です。
* **転載・再配布**: 二次配布は原則として禁止します。公式サイト等へのリンクを推奨します。
* **外部通信**: 本ソフト自体がログやスキャン結果等の情報を外部に送信することはありません。
* **免責事項**: 本ソフトウェアは「現状有姿（As-Is）」で提供され、不具合がないこと等の動作保証はいたしません。使用により生じた一切の損害について作者は責任を負いかねます。すべて利用者の自己責任において使用してください。

### 📚 外部ライブラリ（クレジット）
* Avalonia UI Framework (MIT License)
* CommunityToolkit.Mvvm (MIT License)
* System.IO.FileSystem.AccessControl (MIT License)

