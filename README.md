# HIT-hackathon-doc

# How to write html <!---htmlの書き方-->

First, let's talk about "what is html". <!---htmlとは何か-->

html stands for Hypertext Markup Language and is primarily used to create homepages on the web. <!---htmlの略とhtmlの使用例-->

Introduction to tags and autotext commonly 　used in html. <!---htmlで良く使われるタグと定型文の紹介-->
<br>

# Tags when writing the body <!---本文を書く時のタグ-->
1. Declarations required to write html  sentences <!---htmlの文章の宣言-->
```
    <html>
        <body>
        "Where to write a sentence"
        </body>
    </html>
```
As mentioned above, you can start writing sentences with <html> and <body>. <!---前述のようにすれば文が書き始められる-->

2. A tag that can change the size of the characters used in headings, etc<!---見出しの文字サイズのタグ-->
```
    <h1> "Where to write a sentence" </h1>
```
There are six types of tags ＜h1＞ ＜h2＞ ＜h3＞ ＜h4＞ ＜h5＞ ＜h6＞in , and the characters grow as the number decreases. <!---<h1>~<h6>まであり、数字が小さくなるにつれて文字がでかくなる-->

3. Tags used when writing body text <!---本文を書くときに使うタグ-->
```
    <p> "Where to write a sentence" </p>
```
Since paragraphs can be separated by using <p>, it is used when writing the main text. <!---<p>で段落を区切れるから本文を書くときに使用される-->

4. Tags to use when line breaks <!---改行に使うタグ-->
```
    <br>
```
If you write at the end or between sentences, the statement becomes a newline. <!---文の最後や間に書くことで改行することが出来る-->
<br>

# Link to "css" <!---cssへのリンク-->
```
    <link href="./CSSfilename.css" rel="stylesheet" type="text/css" />
```
Convert "./CSSfilename.css" to the name of the css file. <!---"./CSSfilename.css"をCSSのファイル名に変換する-->
<br>

# How to make a list <!---リストの作り方-->
To create a list, you must first enclose the text you want to list with a ＜li＞ tag. <!---リストを作るには<li>タグを使う-->

1. List of bullet points <!---箇条書きのリスト-->
```
<ul>
<li>"Where to write a sentence"</li>
<li>"Where to write a sentence"</li>
<li>"Where to write a sentence"</li>
</ul>
```
Use ＜ul＞ for list of bulleted lists. <!---箇条書きのリストには<ul>を使用する-->

2. List with numbers <!---数字付きののリスト-->
```
<ol>
<li>"Where to write a sentence"</li>
<li>"Where to write a sentence"</li>
<li>"Where to write a sentence"</li>
</ol>
```
List with numbers uses ＜ol＞. <!---数字付きののリストには<ol>を使う-->
<br>

# Pasting images <!---画像の貼り付け-->
```
    <img src="filename" alt="Description of the image" width="100" height="50">
```
Rename "filename" to the image file and write the description of the image in "Description of the image". <!---"filename" を画像のファイル名に変更し、画像の説明を "Description of the image"に書き込みます。-->
Change the number ”width=100,height=50” by the width and height of the image, respectively. <!---「幅=100,高さ=50」の数値を、それぞれ画像の幅と高さで変更します。-->
Unit is px. <!---単位はpxです-->

