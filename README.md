# robosys3
ロボットシステム学第3回提出課題

## 本プログラムの目的・概要
本プログラムは予め人物名とそれに対応する情報（メールアドレス）が登録されており，人物名を渡すと対応情報が渡されるアドレス帳である．

# address command
![test](https://github.com/RuiLewis/robosys3/actions/workflows/test.yml/badge.svg)

## 使用に当り
### インストール
* 下記の手順に従う

    * $ git clone https://github.com/RuiLewis/robosys3.git
    * $ cd robosys3
    * $ make
    * $ sudo make install

### クイックトライアル
     * :~$ cd ~/robosys3
     * :~/robosys3$ echo SUZUKI | ./address
     * E-mail address:  ruiszk@usomail.rs

### 推奨環境
* Python 3.7 ~ 3.10

### テスト実行環境
* ubuntu22.04.1 LTS

# ライセンス
BSD3条項ライセンス適用．詳細はLICENSEを参照．

# 権利関係・謝辞
* 本プログラムで行われたテストプログラムは千葉工業大学准教授上田隆一先生が講義「ロボットシステム学2022」において使用されたコードを参考とした．以下にその講義動画を掲載する．
（https://www.youtube.com/watch?v=9HPLMhKvecY&list=PLbUh9y6MXvjeM-lT7UoHix3zxxa6M5Jui&index=7）
* このREADME.mdはマークダウン方式で記述された．
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
      * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2023 Rui Suzuki
