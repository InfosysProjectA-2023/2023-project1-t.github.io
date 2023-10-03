# 2023度「プロジェクト演習A」
## 課題プロジェクト(1)テンプレート

このリポジトリ（スターターキット）にすでにあるファイルは，課題プロジェクト(1)の作成例ファイルです．
Bootstrap5を利用して表示のベースを作成しているため，グリッドやコンポ―ネント等を使っての表示の作成については，公式ドキュメントの和訳（https://getbootstrap.jp/docs/5.0/getting-started/introduction/ ）などを参照してください．

### ファイルの一覧
- README.md：このファイル
- .gitignore：Gitの管理対象外のファイルやフォルダを指定（今回の初期設定ではtmpという名前のフォルダを除外）
- simple_example.html：テンプレートの内容を理解しやすいように内容を省いた例示
- detail_example.html：紹介施設のページのテンプレートから作成した例示のページを表示するHTMLファイルの作成例（テンプレート）
- satoyama_park.html：HTML内の`<div id="obj_id">`タグのvaluesの値で表示内容を変化させる場合のHTMLファイル作成例）
- data.json：紹介対象の施設などのデータを記入するJSON形式のファイル（要編集）
- js/フォルダ
  - js/readJSON.js：各チームで作成したデータファイルをページに書き込むJavaScriptプログラム（json_urlの値ほか，要編集）
- css/フォルダ
  - css/ProA_style.css：各チームで装飾を行うCSSファイル（要編集）
  - css/star-rating.css：評価（☆の数）を表示するためのCSSファイル（編集不要）
