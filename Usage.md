# Integration #

  1. download the last version of [wiki2html](http://code.google.com/p/wiki2html/downloads/list);
  1. copy wiki2html.js in your project directory;
  1. import the script in your page using
> > `<script type="text/javascript" src="path/to/wiki2html.js"></script>`
  1. use the function
> > `// wikicode contains the wiki-formatted text`<br>
<blockquote><code>var wikicode = "=wiki text= ...";</code><br>
<code>var html = wiki2html.parse(wikicode);</code>