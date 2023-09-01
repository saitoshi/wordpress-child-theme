# wordpress-child-theme

# WordPress 用の子テーマを作成するためのコード

## 何故子テーマを作成する必要か？

<ol>
<li>https://developer.wordpress.org/themes/advanced-topics/child-themes/#3-enqueue-stylesheet</li>
<li>https://technumero.com/create-child-theme-wordpress/</li>

</ol>

## 子テーマの作成手順

<ol>
<li>style.css ファイルの{大元のテーマ名}の部分を子テーマをもとに作る、テーマ名を入力してください。</li>
<li>style.cssとfunctions.phpファイルを選択し、それをzip化してください。</li>
<li>WordPressの管理画面のテーマ内で、zipしたフォルダを新規テーマとして追加してください。</li>
<li>テーマ選択画面で、子どもテーマを選択してください。
<div style="text-align: center">
<img src ="https://technumero.com/wp-content/uploads/2016/06/Child-Theme-680x184.png">
</div>
</li>
</ol>

## エラーが発生した場合チェックリスト

<ul>
<li>style.cssファイルで、大元のファイル（親のテーマ）の名前が正しいかを確認してください。<br/> WordPressの管理画面で表示されている名前ではないケースがあります。<br/>
<b>(例)</b> GensenはGensenではなくgensen_tcd050になります。
</li>
<li>style.css またはfunctions.phpの方を修正した場合、新しくzip化するのを忘れないでください。</li>

</ul>
