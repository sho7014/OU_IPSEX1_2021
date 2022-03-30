# 情報数理学演習I 2021 講義資料

大阪大学工学部応用自然科学科応用物理学科目２年次演習科目 情報数理学演習I 講義資料 2021年度版  
講義担当: 庵 智幸，岩崎 悟，白坂 将  
TA: 芝田 拓真，生野 圭一郎，羽田 充宏

## 概要
Google Colaboratory を利用した Python プログラミング演習に利用した配布資料です．  
2021年度版作成者: 白坂（[sho7014](https://github.com/sho7014)）

## 目次

[ガイダンス](https://colab.research.google.com/drive/1J_8NN0vUCmaP924D70tcBVXjSrtOnGeu#scrollTo=zQOUg_LM2Llq)

<details>
  <summary> <a href="https://colab.research.google.com/drive/1EVBZekpCd_GGdZi0qTx_8t_T5zrT8EBx">第１回（式・関数とライブラリの初歩）</a> </summary>
    
  * 1-1: 式  
  * 1-2: 関数とライブラリの初歩  
    * 1-2-1: print() 関数 
    * 1-2-2: ライブラリの初歩
  * 1-3: 複数行にまたがる式
  * 1-4: コメント
</details>

<details>
  <summary> <a href="https://colab.research.google.com/drive/1IGMcyWK6bDDYNj_g934AMasohigIGWv6">第２回（変数，単一要素をもつ型，文，条件分岐）</a> </summary>
    
  * 2-1: 変数
    * 2-1-1: 変数の使い方
    * 2-1-2: 変数を利用する動機
  * 2-2: オブジェクトI: 単一要素をもつ型
    * 2-2-1: 型の取得
    * 2-2-2: 数値型
    * 2-2-3: 真理値型
  * 2-3: 文
    * 2-3-1: 複合文
    * 2-3-2: 単純文
  * 2-4: 条件分岐
    * 2-4-1: if 文
    * 2-4-2: if ... else 文
    * 2-4-3: if ... elif ... else 文
    * 2-4-4: 入れ子になった条件分岐
</details>

<details>
  <summary> <a href="https://colab.research.google.com/drive/1BcijDI8pW0n3h5yqdt2fy2n6-ZvDcq0r">第３回（複数要素をもつ型，繰り返し制御）</a>，<a href="https://colab.research.google.com/drive/1y0WkHsNTCL51dU4S2Ngc90IuE5UIxlll">第３回練習問題</a> </summary>
    
  * 3-1: オブジェクトII: 複数要素をもつ型
    * 3-1-1: シーケンス型
      * 3-1-1-1: 文字列
      * 3-1-1-2: リスト
      * 3-1-1-3: タプル
      * 3-1-1-4: range
    * 3-1-2: 辞書
  * 3-2: 論理値再訪
  * 3-3: 繰り返し制御
    * 3-3-1: for 文
    * 3-3-2: while 文
    * 3-3-3: 多重ループ
    * 3-3-4: 異なる複合文の組み合わせ，break 文，continue 文
</details>

<details>
  <summary> <a href="https://colab.research.google.com/drive/1TL0YN_qSjWNP6WL3faWdHO9Stmwb-R8l">第４回（オブジェクトの同一性，関数と変数のスコープ）</a> ，<a href="https://colab.research.google.com/drive/1NFs2cn5HNxmI8YVMGDiO2RO505M9b7pX">第４回練習問題</a></summary>
    
  * 4-1: オブジェクトの同一性
    * 4-1-1: 同一性・等価性とは
    * 4-1-2: コレクションの同一性
    * 4-1-3: ミュータブル・イミュータブル
    * 4-1-4: オブジェクトの複製について
      * 4-1-4-1: ビュー
      * 4-1-4-2: 浅いコピー
      * 4-1-4-3: 深いコピー
  * 4-2: 関数と変数のスコープ
    * 4-2-1: 関数の種類
    * 4-2-2: 関数定義と呼び出し
    * 4-2-3: 関数の引数
      * 4-2-3-1: 位置引数・キーワード引数
      * 4-2-3-2: デフォルトの引数値
      * 4-2-3-3: 可変長引数
      * 4-2-3-4: 実引数のアンパック
    * 4-2-4: 関数呼び出しとスタック
      * 4-2-4-1: スタック
      * 4-2-4-2: コールスタック
    * 4-2-5: 名前解決
      * 4-2-5-1: 名前空間とスコープ
      * 4-2-5-2: LEGB ルール
      * 4-2-5-3: global 文，nonlocal 文
    * 4-2-6: 関数中での関数呼び出し
      * 4-2-6-1: 再帰呼び出し
</details>

<details>
  <summary> <a href="https://colab.research.google.com/drive/1TqjAqNQcm9DxoO0QQrwYCiCPXE1ne2Tq">第５回（テストとデバッグ）</a> </summary>
    
  * 5-1: テストとデバッグ
    * 5-1-1: 予備知識: Pythonインタプリタ
    * 5-1-2: エラー・バグの分類
      * 5-1-2-1: 構文エラー
      * 5-1-2-2: 静的意味論的エラー
      * 5-1-2-3: 意味論的エラー
      * 5-1-2-4: 顕在性によるバグの分類
      * 5-1-2-5: 継続性によるバグの分類
    * 5-1-3: テスト
      * 5-1-3-1: テストの分類
      * 5-1-3-2: テストのためのツール
      * 5-1-3-3: ブラックボックス・テスト
      * 5-1-3-4: グラスボックス・テスト
    * 5-1-4: デバッグ
      * 5-1-4-1: print デバッグ
      * 5-1-4-2: デバッガの利用
</details>

<details>
  <summary> <a href="https://colab.research.google.com/drive/1sdeH6yInNaVKHK0Ng5BBLVf8KouTbMEn">第６回（内包表記，高階関数，ファイル入出力）</a>，<a href="https://colab.research.google.com/drive/19VR_hg2IHHXuFzdgLXSV5H6NY2r3yI_I">第６回練習問題</a> </summary>
    
  * 6-1: 内包表記
    * 6-1-1: リスト内包表記
    * 6-1-2: 辞書内包表記
    * 6-1-3: ジェネレータ式
  * 6-2: 高階関数
    * 6-2-1: 準備: 第一級オブジェクトとしての関数
    * 6-2-2: 準備: 無名関数
    * 6-2-3: 高階関数としての既習関数
    * 6-2-4: map
    * 6-2-5: filter
    * 6-2-6: 集約
  * 6-3: ファイル入出力
    * 6-3-1: 予備知識: ディレクトリ，パス
    * 6-3-2: ファイル操作
      * 6-3-2-1: 準備: Colab 上でのテキストファイル作成＆編集
      * 6-3-2-2: 読み出し
      * 6-3-2-3: 書き込み
    * 6-3-3: ローカルおよび Google Drive とのファイルのやりとり
      * 6-3-3-1: ローカルとのやりとり
      * 6-3-3-2: Google Drive とのやりとり
</details>

<details>
  <summary> <a href="https://colab.research.google.com/drive/1OOLecMFETwzkgftrABr6CuMentKWCHtW">第７回（モジュールとパッケージ，データの可視化）</a> </summary>
    
  * 7-1: モジュール
    * 7-1-1: 準備: py ファイルと Python スクリプト
    * 7-1-2: モジュールの種類
    * 7-1-3: モジュールの読み込み
    * 7-1-4: モジュールを作成し，利用する
    * 7-1-5: モジュールとスコープ
    * 7-1-6: Python スクリプト実行再訪
  * 7-2: パッケージ
  * 7-3: データの可視化
    * 7-3-1: 一次元系列データの可視化
      * 7-3-1-1: 基本
      * 7-3-1-2: 複数の系列データ
      * 7-3-1-3: 点・線のスタイル
      * 7-3-1-4: 凡例
      * 7-3-1-5: 軸
      * 7-3-1-6: フォント
    * 7-3-2: 二次元の場の可視化
    * 7-3-3: 散布図
    * 7-3-4: 棒グラフ
    * 7-3-5: ヒストグラム
    * 7-3-6: 複数の図を並べて描画する
    * 7-3-7: 図の保存
</details>

<details>
  <summary> <a href="https://colab.research.google.com/drive/1l0iw0zHw2MH3tTsZUx-JlJDa1YYUoeo0">第８回（クラス）</a> </summary>
    
  * 8: クラス
    * 8-1: クラス定義
    * 8-2: インスタンスの生成
    * 8-3: コンストラクタ
    * 8-4: メソッドとそのスコープ
    * 8-5: 継承
</details>

<details>
  <summary> <a href="https://colab.research.google.com/drive/1HQYi3XkF6h9Zdq_6T1QY4PwUJ5C1S8SV">第９回（数値計算ライブラリ）</a> </summary>
    
  * 9: NumPy ライブラリ
    * 9-1: NumPy 配列の初歩
    * 9-2: 配列の生成
    * 9-3: 部分配列の切り出し
      * 9-3-1: スライシング
      * 9-3-2: ブールインデックス参照
      * 9-3-3: ファンシーインデックス参照
    * 9-4: 配列の再成形・加工
      * 9-4-1: 予備知識: 行・列優先順序
      * 9-4-2: 再成形
      * 9-4-3: 配列の結合・分割
      * 9-4-4: ソート
    * 9-5: 演算とブロードキャスト
      * 9-5-1: 配列の要素毎の演算
      * 9-5-2: ブロードキャスト演算
      * 9-5-3: ブロードキャスト代入
    * 9-6: ユニバーサル関数
      * 9-6-1: 単項ユニバーサル関数
      * 9-6-2: 二項ユニバーサル関数
      * 9-6-3: where 関数（ユニバーサル三項演算）
    * 9-7: 擬似乱数生成器
    * 9-8: 線形代数
    * 9-9: 集約
      * 9-9-1: 集約関数
      * 9-9-2: ユニバーサル関数のインスタンス集約メソッド
    * 9-10: ファイル入出力
      * 9-10-1: テキストファイルの入出力
      * 9-10-2: バイナリファイルの入出力
    * 9-11: 実行時間パフォーマンス向上について
</details>
