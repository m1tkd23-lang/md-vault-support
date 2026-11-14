---
title: md-vault Privacy Policy
permalink: /privacy-policy
---

# md-vault プライバシーポリシー

最終更新日: 2026年11月14日
発行者: arigatouna

md-vault（以下「本アプリ」）は、パソコン上の Markdown ファイルを編集・管理するノートアプリです。本ポリシーは、本アプリが扱う情報について説明します。

## 1. 収集する情報

本アプリは、利用者の個人情報・利用状況・端末情報を**収集しません**。発行者のサーバーへデータを送信することはなく、広告・アクセス解析・テレメトリの仕組みも含みません。

## 2. 端末内に保存される情報

次の情報は利用者のパソコン内にのみ保存され、発行者が取得することはありません。

- 利用者が作成・編集したノート（利用者が選んだフォルダ内の `.md` ファイルと画像）
- 本アプリの設定（最近開いたフォルダ、表示設定など。`%APPDATA%\com.mdvault.app` 等に保存）

## 3. 利用者の操作による外部との通信

次の機能は、利用者が明示的に操作したときに限り、利用者のパソコンから外部サービスへ直接通信します。発行者は通信内容を取得しません。

- **GitHub への公開**: 利用者が「GitHub に公開」を実行すると、GitHub API（api.github.com）でリポジトリを作成します。認証には利用者のパソコンの Git 資格情報マネージャーに保存された情報を一時的に使用し、本アプリ内には保存しません。
- **Git の同期（push / pull など）**: 利用者が設定したリモートリポジトリと通信します。
- **ターミナル機能**: 本アプリ内のターミナルで利用者が実行したプログラム（Git、Claude Code などの外部ツール）は、それぞれのツール自身の規約とプライバシーポリシーに従って動作します。

これらの外部サービスでの情報の取り扱いは、各サービスのプライバシーポリシーをご確認ください。

## 4. 第三者への提供

本アプリは情報を収集しないため、第三者へ提供することはありません。

## 5. 本ポリシーの変更

本ポリシーを変更する場合は、このページで告知します。

## 6. お問い合わせ

本ポリシーおよび本アプリに関するお問い合わせは、GitHub の Issues で受け付けます: https://github.com/m1tkd23-lang/md-vault-support/issues

---

# md-vault Privacy Policy

Last updated: November 14, 2026
Publisher: arigatouna

md-vault ("the App") is a note-taking app that edits and manages Markdown files on your computer.

## 1. Information we collect

The App does **not** collect any personal information, usage data, or device information. It never sends data to the publisher's servers and contains no advertising, analytics, or telemetry.

## 2. Information stored on your device

Your notes (Markdown files and images in folders you choose) and the App's settings are stored only on your computer. The publisher has no access to them.

## 3. Network access initiated by you

Only when you explicitly use the following features does the App communicate directly from your computer with external services. The publisher does not receive this data.

- **Publish to GitHub**: creates a repository via the GitHub API (api.github.com), using credentials temporarily obtained from your Git credential manager. Credentials are not stored by the App.
- **Git sync (push / pull, etc.)**: communicates with the remote repositories you configure.
- **Terminal**: programs you run in the built-in terminal (such as Git or Claude Code) operate under their own terms and privacy policies.

## 4. Sharing with third parties

Because the App collects no information, nothing is shared with third parties.

## 5. Changes

Any changes to this policy will be posted on this page.

## 6. Contact

Please contact us via GitHub Issues: https://github.com/m1tkd23-lang/md-vault-support/issues
