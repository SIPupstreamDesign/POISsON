# POISsON
Probe in solution space

## ソフトウェアの特徴
データ空間をインタラクティブに探査するための可視化システム。Webインターフェイスをもち、ユービキタスな環境で利用できる。

## 機能
* 複数列のデータ（csv形式, N列xM行）を読み、選択した3軸のデータ列を三次元空間の座標値として点群をプロット
+ データプロットとして、直交座標系、球座標系
+ 点群とリンクしたURLやスクリプトを起動
- データ間の関連性の強調表示
- 形状表示（STL, obj形式）

## Copyright
Copyright (c) 2015 Advanced Institute for Computational Science, RIKEN.
All rights reserved.

This software product also includes other OSS source codes of MIT license (see remarks in source code).
BSD lisence will be applied to the our original source code.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

- Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
- Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.


## Contributor
* Kenji    Ono        keno@riken.jp
* Tomohiro Kawabnabe
* Kentarou Oku
* Masaki Sasaki
* Kazuma Hatta


### プロダクト名
PrObe In SolutiON space のAcronymをとるとPOISON（毒）になってしまうので、spaceの"s"を入れて魚。数学者でもある。


## Acknowledgment
本プログラムは、「ＳＩＰ（戦略的イノベーション創造プログラム）／革新的設計生産技術」の採択テーマ「全体俯瞰設計と製品設計の着想を支援するワークスペースの研究開発」に関する研究開発の一環で開発された。


## How to use
Download and unarchive zip file, and open index.html file by web browser.  We confirmed operations on Chrome, Firefox, and Safari.

## LICENSE表記
本プログラムは以下の3rd製ツールを利用しております。

* jquery-1.11.2        jQuery License http://jquery.com/
* Handsontable         MIT License http://handsontable.com/
* jQuery               MIT License http://bassistance.de/jquery-plugins/jquery-plugin-treeview/
* Qatrix               MIT License http://qatrix.com/

### jQuery License表記
Copyright jQuery Foundation and other contributors, https://jquery.org/

This software consists of voluntary contributions made by many
individuals. For exact contribution history, see the revision history
available at https://github.com/jquery/jquery

The following license applies to all parts of this software except as
documented below:

====

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

====

All files located in the node_modules and external directories are
externally maintained libraries used by this software which have their
own licenses; we recommend you read them, as their terms may differ from
the terms above.
