# ACL Migration Checker

[![Latest Release](https://badgen.net/github/release/chililikobo/AclMigrationChecker)](https://github.com/chililikobo/AclMigrationChecker/releases/latest)
[![Downloads](https://badgen.net/github/assets-dl/chililikobo/AclMigrationChecker)](https://github.com/chililikobo/AclMigrationChecker/releases/latest)
[![License](https://badgen.net/badge/license/Freeware/purple)](#-terms-of-use--disclaimer)
[![Platform](https://badgen.net/badge/platform/Windows/black)](#-installation-portable)

[English](#english) | [日本語](#日本語)

---

## English

ACL Migration Checker is a high-speed tool designed to verify that access control lists (ACLs) are accurately preserved without discrepancies during data migration on file servers and storage servers.

It is specifically engineered to pinpoint ACL differences even when hostnames, IP addresses, or top-level folder names change between source and destination—making it ideal for Workgroup environments where SID migration is difficult, as well as standard Active Directory migrations.

🌐 **For detailed specifications and support, please visit the [Official Website](https://chililikobo.github.io/en/).**

### 🚀 Installation (Portable)

No installation or registry setup is required. Extract the downloaded package and run `AclMigrationChecker.exe` with its bundled native DLLs in the same folder. To uninstall, just delete the entire folder.

**Required Runtime Files (NativeAOT):**
* `AclMigrationChecker.exe` *(includes embedded English & Japanese UI resources)*
* `av_libglesv2.dll`
* `libHarfBuzzSharp.dll`
* `libSkiaSharp.dll`

**Portable Design:** Built as a self-contained NativeAOT application, you can carry the folder on a USB drive and run it directly on compatible PCs and servers without installing any additional .NET Runtime.

* **Supported OS**: Windows 10 / Windows 11 (x64)
* **Supported OS (Server)**: Windows Server 2016 / 2019 / 2022 / 2025 (x64)

### 🛠 Key Features & Usage

#### 1. High-Speed ACL Scanning & Snapshots
* Scans local drives and network shares (`\\server\share`) at high speed and saves results as lightweight `.json.gz` files for offline or cross-server comparison.
* Automatically selects the fastest scan mode for your environment and shows a 4-tier speed indicator in the header as soon as scanning starts. Running as **Administrator** on a local NTFS drive unlocks ultra-fast mode.
* Starts as a Standard User by default; click **Restart as Admin** anytime without losing your entered paths or language setting.
* *Note*: `.json.gz` files saved in `v26.11.23.0` or later are not compatible with v1 (`26.7.31.2`).

#### 2. Flexible Migration Comparison (Workgroup & AD)
* Compares folder structures and access permissions accurately even if server names, IP addresses, or top-level folder names change.
* Matches local accounts by name across different servers in Workgroup environments, and detects missing/extra folders, permission changes, and Deny rules.

#### 3. Easy Diff Inspection (3 Views)
* **Tree View**: Side-by-side trees with **Diffs Only**, **Folders Only**, **Prev / Next** diff jumping, **Open Folder**, and right-click menu (**Open Folder** / **Copy Path**).
* **Diff List**: Filter by status (`Match`, `Mismatch`, `Missing`, `Extra`), search by keyword, copy paths, or open in Explorer.
* **Error Log**: Review and filter skipped items (such as access-denied folders).
* Click any item to compare exact user permissions side by side in the bottom **ACL Details** pane.

#### 4. Themes, Language Switch & CSV Export
* Switch between **Light / Dark** themes and **English / Japanese** live from the header without restarting.
* Export comparison results and error logs to CSV files ready to open in Excel.

### 📄 Terms of Use & Disclaimer

* **License**: This software is freeware and can be used free of charge by both individuals and corporations.
* **Distribution**: Redistribution is prohibited. Please link to the official website instead.
* **Privacy**: This software does not transmit logs or scan results to any external servers.
* **Disclaimer**: This software is provided "As-Is" without any warranty. The author shall not be liable for any damages arising out of its use. Use at your own risk.

### 📚 Credits (External Libraries)
This application incorporates open-source components. For detailed copyright notices and license agreements, refer to [ThirdPartyNotices.md](ThirdPartyNotices.md) (also bundled as `ThirdPartyNotices.txt` with the app).

---

## 日本語

ACL Migration Checkerは、ファイルサーバーやストレージサーバーのデータ移行（マイグレーション）において、移行元と移行先のアクセス権（ACL）に差異がないかを高速かつ正確に検証するための専用チェックツールです。

新旧サーバーでホスト名・IPアドレス・トップフォルダ名が異なっていてもトップフォルダ配下の構造とACLの差異をピンポイントで特定できるため、SID（セキュリティ識別子）の移行が困難なWorkgroup環境での権限再設定や、Active Directory環境のデータ移行検証に強力な威力を発揮します。

🌐 **詳細な仕様やサポート情報については、[公式ホームページ](https://chililikobo.github.io/) をご覧ください。**

### 🚀 インストール (ポータブル対応)

インストール作業やレジストリ登録は不要です。配布フォルダ内の実行ファイルと必要なネイティブDLLを同じフォルダに配置して起動してください。アンインストールはフォルダごと削除するだけです。

**必須同梱ファイル（NativeAOT 構成）：**
* `AclMigrationChecker.exe` *(日本語・英語 UI リソースを内蔵)*
* `av_libglesv2.dll`
* `libHarfBuzzSharp.dll`
* `libSkiaSharp.dll`

**ポータブル設計:** NativeAOT による自己完結型アプリのため、USBメモリ等で持ち運び、.NETランタイム未導入のPC・サーバー上でもそのまま起動して利用できます。

* **対応OS**: Windows 10 / Windows 11 (x64)
* **対応OS (サーバー)**: Windows Server 2016 / 2019 / 2022 / 2025 (x64)

### 🛠 主な機能と使い方

#### 1. 高速スキャンとスナップショット保存
* ローカルドライブや共有フォルダ（`\\server\share`）のアクセス権を高速にスキャンし、軽量な `.json.gz` ファイルとして保存・持ち運び比較ができます。
* 環境に合わせて最適なスキャン方式を自動選択し、スキャン開始時にヘッダーの 4 段階バッジで速度目安を表示します（管理者モードでローカル NTFS ドライブをスキャンすると最速モードで動作します）。
* 通常は標準ユーザー権限で起動し、必要なときだけ「管理者として再起動」からパスと言語を引き継いで昇格できます。
* ※ `v26.11.23.0` 以降の `.json.gz` ファイルは、旧版（`26.7.31.2`）とは互換性がありません。

#### 2. サーバー名・フォルダ名が違っても比較可能（Workgroup / AD 対応）
* 移行元と移行先でサーバー名・IPアドレス・トップフォルダ名が異なっていても、配下のフォルダ構成とアクセス権の過不足・不一致を正確に検出します。
* Workgroup 環境でサーバーが変わる同名アカウントの照合や、拒否（Deny）権限の違いも判別できます。

#### 3. 分かりやすい 3 画面表示と詳細比較
* **ツリー表示**: 左右のツリーを同期しながら、「差分のみ」「フォルダのみ」絞込、`◀` / `▶` での差分ジャンプ、「フォルダを開く」、右クリックメニュー（フォルダを開く／パスをコピー）が使えます。
* **差分リスト**: 一致／不一致／欠損／追加での絞り込み、キーワード検索、パスコピー、Explorer 起動に対応。
* **エラー一覧**: アクセス拒否などでスキップされた項目を確認・検索できます。
* 項目を選ぶと、画面下部で移行元・移行先のアクセス権を並べて比較できます。

#### 4. テーマ切替・日英切替・CSV 出力
* ヘッダーから**ライト／ダークテーマ**と**日本語／英語**を再起動なしで切り替えられます。
* 比較結果とエラー一覧は Excel でそのまま開ける CSV 形式で出力できます。

### 📄 利用規約・免責事項

* **ライセンス**: 本ソフトウェアはフリーウェアです。個人・法人を問わず、無料で利用可能です。
* **転載・再配布**: 二次配布は原則として禁止します。公式サイト等へのリンクを推奨します。
* **外部通信**: 本ソフト自体がログやスキャン結果等の情報を外部に送信することはありません。
* **免責事項**: 本ソフトウェアは「現状有姿（As-Is）」で提供され、不具合がないこと等の動作保証はいたしません。使用により生じた一切の損害について作者は責任を負いかねます。すべて利用者の自己責任において使用してください。

### 📚 外部ライブラリ（クレジット）
本ソフトウェアはオープンソースコンポーネントを使用しています。各コンポーネントの著作権表示およびライセンス条文の詳細は [ThirdPartyNotices.md](ThirdPartyNotices.md)（配布パッケージにも `ThirdPartyNotices.txt` を同梱）をご参照ください。
