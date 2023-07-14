# subject-vscode-search-regex

## 改行を含む $.ajax の処理開始部分
```txt
\$.ajax[\s\S\n]+?\)
```

## [正規表現構文早見表](https://developer.mozilla.org/ja/docs/Web/JavaScript/Guide/Regular_expressions/Cheatsheet)


| 文字 | 意味 |
----|---- 
| . | 改行文字を除くあらゆる 1 文字と一致 |
| \s | ホワイトスペース 1 文字に一致。例えば空白、タブ、改ページ、改行、その他の Unicode 空白文字 |
| \S | \s でない文字 |
| \d | 数字に一致。[0-9] に相当 |
| \D | \d でない文字 |
