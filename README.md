# HIT-hackathon-doc

# How to write html <!---htmlの書き方-->

First, let's talk about "what is html". <!---htmlとは何か-->

html stands for Hypertext Markup Language and is primarily used to create homepages on the web. <!---htmlの略とhtmlの使用例-->

Introduction to tags and autotext commonly used in html. <!---htmlで良く使われるタグと定型文の紹介-->
<br>

## Tags when writing the body <!---本文を書く時のタグ-->
1. Declarations required to write html  sentences <!---htmlの文章の宣言-->
```html
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

## Link to "css" <!---cssへのリンク-->
```
    <link href="./CSSfilename.css" rel="stylesheet" type="text/css" />
```
Convert "./CSSfilename.css" to the name of the css file. <!---"./CSSfilename.css"をCSSのファイル名に変換する-->
<br>

## How to make a list <!---リストの作り方-->
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

## Pasting images <!---画像の貼り付け-->
```
    <img src="filename" alt="Description of the image" width="100" height="50">
```
Rename "filename" to the image file and write the description of the image in "Description of the image". <!---"filename" を画像のファイル名に変更し、画像の説明を "Description of the image"に書き込みます。-->
Change the number ”width=100,height=50” by the width and height of the image, respectively. <!---「幅=100,高さ=50」の数値を、それぞれ画像の幅と高さで変更します。-->
Unit is px. <!---単位はpxです-->

# How to write CSS

CSS is a language used to specify the style of a web page.

It stands for Cascading Style Sheets, and is used to apply styles to web pages created with HTML or XHTML.

Files to which CSS has been applied will only change the appearance of the design, etc., but will not change the structure of the document, such as HTML.

In this section, we will introduce the syntax and usage of CSS.

## How to add styles to HTML with CSS

CSS should be written according to these rules.

```css
"The HTML tag to which you want to apply the style" {
    "The type of style to be applied": "Value of the style to apply";
}
```

If you are not sure, try following the example below.

1. Color the elements

With CSS, you can add colors to text and other objects.

```css
p {
    color: #000000;
    background-color: #99cc00
}
```

This "p" is a tag called `<p>` written in HTML.

In this example, `color` is specified for the text color of `<p>`, and `background` is specified for the background of `<p>`.

In addition to `<p>` tags, it can also be used for `<h1>` tags.

2. Change the font

```css
p {
    font-family: Impact,Charcoal;
}
```

By using `font-family`, you can adapt various fonts to HTML elements.

3. Change the size of text

```css
p {
    font-size: 12px;
}

p {
    font-size: large;
}
```

In this way, by specifying the size of the `<p>` tag, you can change the size of text.

4. Setting the width and height

```css
img {
    width: 256px;
    height: 256px;
}

img {
    width: 256px;
}

img {
    height: 256px;
}
```

By using `width` and `height`, it is possible to specify the width and height of tags such as `<img>`.

Alternatively, you can specify only the width or height, as in the second and third options.

## How to write CSS other than these

There are many ways to write CSS, and most of them are described in a document called MDN, so if you have any questions, please check it out.

[CSS: Cascading Style Sheets](https://developer.mozilla.org/en-US/docs/Web/CSS)

# Installing the editor

In this exercise, we will use a unified editor for writing HTML and CSS. Please download it from this link. If you have any questions, please feel free to ask.

[Visual Studio Code](https://code.visualstudio.com/docs)
