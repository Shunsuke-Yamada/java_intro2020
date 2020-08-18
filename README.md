# はじめに
このプロジェクトは「Java入門」のための解説＋コード例＋課題例について整理している。想定している前提は以下の通り。

- 前提
  - Pythonで基本的なプログラミング（関数、制御文、スコープ、ファイルI/O、docstring, doctest）はできるレベル。
    - 参考: [2020年度 : プログラミング1](https://ie.u-ryukyu.ac.jp/~tnal/2020/prog1/)
      - クラスは教えていない。オブジェクトについても詳細は教えていない。
      - VS Codeによるデバッグ実行、breakpointは体験済み。
      - コンパイラ言語や静的型付け言語についての知識ゼロ。
- 目標
  - 2年次前期の別講義「[アルゴリズムとデータ構造](https://ie.u-ryukyu.ac.jp/syllabus/2017/early/601052001.html)」で、実装をC言語で進めるため、C言語の基礎（宣言・式・関数・制御文・関数・スコープ・構造体）は抑えておきたい。ポインタ周りは別講義側で解説導入。
  - 2年次後期の別講義「[モデリングと設計](https://ie.u-ryukyu.ac.jp/syllabus/2016/late/60153500.html)]で、Git + GitHubによる開発を行うため、一般的な流れは終えておきたい。
  - 2年次後期の別講義「[2015年度: オペレーティングシステム](https://ie.u-ryukyu.ac.jp/syllabus/2016/late/60105300.html)」で、実装をJavaで進めるため、一般的なJava開発プロセスを一通り終えておきたい。具体的な要求は次の通り。

```
File I/O、構成管理(gradle)、バージョン管理、ユニットテスト、、、
```
- 上記を踏まえ、以下の事柄を含めつつ、Python 3のコードと比較する形でJava・C言語の解説を行う。
  - (0) 参考文献、サイトの提示。逐次処理・条件分岐・ループ処理あたりの概念説明は省略。
  - (1) Javaにおけるコンパイラの役目。（Cコンパイラとの違い）
  - (2) 静的型付け言語と動的型付け言語の違い。（入門編ではC言語と基本的には一緒だが、継承周りの説明を含む）
  - (3) 統合環境・デバッガの利用。
    - [Visual Studio Code](https://code.visualstudio.com/docs/languages/java)
  - (?) Makefile（ファイル分割されたプログラムのビルド方法）
  - (?) 「C言語の配列」と「Pythonのリスト」比較によるメモリのイメージ付け。
