# パズルから始めるプログラミングエクササイズ

## 概要

### 目的

### 前提

| ソフトウェア   | バージョン | 備考 |
| :------------- | :--------- | :--- |
| nodejs     | 10.16.3    |      |
| python     | 3.7.0      |      |

## 構成

- [構築](#構築)
- [配置](#配置)
- [運用](#運用)
- [開発](#開発)

## 詳細

### 構築
#### 開発パッケージのセットアップ

```bash
npm init -y
npm install --save-dev npm-run-all watch foreman cpx rimraf markdown-to-html
npm install --save-dev prettier
npm install --save-dev browser-sync connect-browser-sync nodemon
npx browser-sync init
touch Procfile
```

**[⬆ back to top](#構成)**

### 配置

**[⬆ back to top](#構成)**

### 運用

**[⬆ back to top](#構成)**

### 開発

```bash
npm install
npm run start
```

#### TDD入門

- [フィボナッチ数](./jupyter/math_puzzles/Fibonacci.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hiroshima-arc/programing_puzzles/blob/develop/jupyter/sample/Fibonacci.ipynb)
- [フィボナッチ数(JavaScript)](./jupyter/math_puzzles/FibonacciJavaScript.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hiroshima-arc/programing_puzzles/blob/develop/jupyter/sample/FibonacciJavaScript.ipynb)

#### プログラマ脳を鍛える数学パズル

- [10進数で回文](./jupyter/math_puzzles/Q01.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hiroshima-arc/programing_puzzles/blob/develop/jupyter/math_puzzles/Q01.ipynb)

**[⬆ back to top](#構成)**

## 参照

- [プログラマ脳を鍛える数学パズル シンプルで高速なコードが書けるようになる70問](https://www.amazon.co.jp/%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9E%E8%84%B3%E3%82%92%E9%8D%9B%E3%81%88%E3%82%8B%E6%95%B0%E5%AD%A6%E3%83%91%E3%82%BA%E3%83%AB-%E3%82%B7%E3%83%B3%E3%83%97%E3%83%AB%E3%81%A7%E9%AB%98%E9%80%9F%E3%81%AA%E3%82%B3%E3%83%BC%E3%83%89%E3%81%8C%E6%9B%B8%E3%81%91%E3%82%8B%E3%82%88%E3%81%86%E3%81%AB%E3%81%AA%E3%82%8B70%E5%95%8F-%E5%A2%97%E4%BA%95-%E6%95%8F%E5%85%8B/dp/479814245X/ref=sr_1_5?hvadid=386565051530&hvdev=c&jp-ad-ap=0&keywords=%E6%95%B0%E5%AD%A6%E3%83%91%E3%82%BA%E3%83%AB&qid=1573277906&sr=8-5)
