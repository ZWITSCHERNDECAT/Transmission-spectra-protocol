 <img src="https://img.shields.io/badge/-Python-F2C63C.svg?logo=python&style=for-the-badge">


# Transmission-spectra-protocol
The original code of the derivation of transmission spectra from TOI654.01, observerd by Subaru(IRD).

<img width="947" alt="スクリーンショット 2024-08-05 22 52 21" src="https://github.com/user-attachments/assets/076a7d30-bf82-42ae-8369-e095a6fda8a2">


```markdown
# Transmission Spectra Protocol

## 概要
このリポジトリは、天文学および惑星科学における透過スペクトルの解析を行うためのPythonコードを含んでいます。このコードは、惑星大気の観測データを用いて、大気の組成や特性を推定するためのツールです。

## 目的
本プロジェクトの目的は、観測データから透過スペクトルを生成し、そのスペクトルに基づいて惑星大気の特徴を明らかにするプロトコルを提供することです。このコードは、研究者や学生が効率的にデータ解析を行うための基盤として開発されました。

## 使い方
1. リポジトリをクローンするか、ダウンロードします。
2. `Jupyter Notebook` 形式で提供される `.ipynb` ファイルを開きます。
3. 必要なライブラリをインストールし、データセットを準備します。
4. 各セルを順に実行し、データの読み込みから解析までのプロセスを実行します。

```bash
git clone https://github.com/ZWITSCHERNDECAT/Transmission-spectra-protocol.git
```

## 使用言語・フレームワーク
- **Python 3.10**
- **Jupyter Notebook**
- **主要ライブラリ**
  - NumPy 1.24.0
  - Matplotlib 3.7.0
  - Pandas 1.5.3
  - SciPy 1.10.0
  - Astropy 5.2

## こだわりのポイント
- **データの前処理**: 透過スペクトル解析において、観測データのクリーンアップと前処理が非常に重要です。このコードでは、データノイズの除去や異常値の検出と修正を効率的に行うための機能が実装されています。
- **カスタマイズ可能な解析プロセス**: 研究目的に応じて、解析プロセスをカスタマイズできるように設計されています。ユーザーは簡単にパラメータを調整し、独自の解析を行うことができます。
- **視覚化**: 解析結果を直感的に理解できるように、Matplotlibを用いた高品質なグラフ生成機能が備わっています。視覚的な結果から、惑星大気の特性を容易に把握できます。
```

こちらを `README.md` にそのまま貼り付けてご利用ください。


