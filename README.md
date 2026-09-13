# Kronos 5G Core

**5G SA Core Network Software for Evaluation, Development, and PoC**

Kronos 5G Core is a 5G Standalone (SA) Core Network software platform intended for evaluation, development, interoperability testing, and Local 5G / Private 5G PoC environments.

> The Kronos 5G Core software package is distributed through **GitHub Releases**.
> `git clone` retrieves this repository and README, but does not download the release package.

## Download v0.1.0

You can download the current release directly from the links below:

* [Download kronos5gcore.tar.gz](https://github.com/PrototypeDeveloper/kronos-5g-core/releases/download/v0.1.0/kronos5gcore.tar.gz)
* [Download SHA256SUMS](https://github.com/PrototypeDeveloper/kronos-5g-core/releases/download/v0.1.0/SHA256SUMS)

Or download from the command line:

```bash
wget https://github.com/PrototypeDeveloper/kronos-5g-core/releases/download/v0.1.0/kronos5gcore.tar.gz
wget https://github.com/PrototypeDeveloper/kronos-5g-core/releases/download/v0.1.0/SHA256SUMS

sha256sum -c SHA256SUMS
```

If verification succeeds:

```text
kronos5gcore.tar.gz: OK
```

Extract the package with:

```bash
tar xzf kronos5gcore.tar.gz
```

```

[English](#english) | [日本語](#日本語)

---

<a id="english"></a>

## English

### Overview

Kronos 5G Core provides a 5G Core environment for evaluating and testing 5G SA networks.

The software is designed with consideration for the functional architecture defined by 3GPP specifications and is intended for use in research, development, interoperability testing, and PoC environments.

### Highlights

* 5G Standalone Core Network software
* Designed with consideration for the 5G Core functional architecture defined by 3GPP specifications
* Basic 1 Call connectivity verified using a gNodeB emulator
* Free Demo Mode available
* Suitable for 5G / Local 5G / Private 5G evaluation and PoC environments

### Verified Connectivity

Basic connectivity has been verified with the following configuration:

```text
gNodeB (emulator) ⇔ Kronos 5G Core ⇔ DN
```

DN: Data Network

### Demo Mode

A free **Demo Mode** is available for evaluation.

Demo Mode supports:

* Up to **2 gNodeBs**
* Up to **2 UEs**

This allows basic 5G Core functionality to be evaluated without a paid license.

### Releases

Release packages are distributed through the **Releases** section of this repository.

Current public release:

**Kronos 5G Core v0.1.0**

Release files:

```text
kronos5gcore.tar.gz
SHA256SUMS
```

The integrity of the downloaded archive can be verified with:

```bash
sha256sum -c SHA256SUMS
```

### Project Status

Kronos 5G Core is currently intended primarily for:

* Evaluation
* Development
* Testing
* Interoperability verification
* Proof of Concept (PoC)

Functionality and interoperability will continue to be expanded in future releases.

### Disclaimer

Kronos 5G Core is an independent implementation intended for evaluation, development, testing, and PoC purposes.

This project does not claim 3GPP certification or full conformance.

---

<a id="日本語"></a>

## 日本語

### 概要

**Kronos 5G Core** は、5G Standalone（SA）ネットワークの評価・開発・相互接続試験を目的とした5Gコアネットワークソフトウェアです。

ローカル5G / プライベート5Gを含む、研究・開発・検証・PoC環境での利用を想定しています。

3GPP仕様で定義されている5G Coreの機能構成を考慮して設計されています。

### ダウンロード

Kronos 5G Coreのソフトウェアパッケージは、GitHubの **Releases** から配布しています。

Linuxでは以下のコマンドでv0.1.0を取得できます。

```bash
wget https://github.com/PrototypeDeveloper/kronos-5g-core/releases/download/v0.1.0/kronos5gcore.tar.gz
wget https://github.com/PrototypeDeveloper/kronos-5g-core/releases/download/v0.1.0/SHA256SUMS
```

ダウンロード後、SHA-256ハッシュを確認します。

```bash
sha256sum -c SHA256SUMS
```

正常な場合は以下のように表示されます。

```text
kronos5gcore.tar.gz: OK
```

アーカイブを展開します。

```bash
tar xzf kronos5gcore.tar.gz
```

### 主な特徴

* 5G Standalone Core Networkソフトウェア
* 3GPP仕様で定義されている5G Coreの機能構成を考慮した設計
* gNodeBエミュレータを使用した基本的な1 Call接続を確認済み
* 無料で利用可能なDemo Modeを提供
* 5G / ローカル5G / プライベート5Gの評価・PoC環境で利用可能

### 動作確認

以下の構成で基本通信を確認しています。

```text
gNodeB (emulator) ⇔ Kronos 5G Core ⇔ DN
```

DN：Data Network

### Demo Mode

評価用途として無料で利用できる **Demo Mode** を提供しています。

Demo Modeでは以下を利用できます。

* gNodeB：最大 **2台**
* UE：最大 **2台**

有料ライセンスなしで、基本的な5G Core機能を評価できます。

### リリース

現在の公開リリース：

**Kronos 5G Core v0.1.0**

リリースファイル：

```text
kronos5gcore.tar.gz
SHA256SUMS
```

### プロジェクトステータス

Kronos 5G Coreは、現在主に以下の用途を想定しています。

* 評価
* 開発
* テスト
* 相互接続検証
* Proof of Concept（PoC）

今後のリリースで、機能および相互接続性を継続して拡張していく予定です。

### 免責事項

Kronos 5G Coreは、評価、開発、テスト、PoC用途を目的とした独立実装です。

本プロジェクトは、3GPP認証取得や完全準拠を主張するものではありません。
