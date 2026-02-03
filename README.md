# novel_writing
小説を書くところ
作業は作品ごとにフォルダ(novel_writing直下)をつくって、それをvscodeで開く

環境　https://taiyolab.com/ja/novel-writer/
pdf縦書きか横書きか　Novel › Preview: Writing Direction

（テキスト校正くん）

markdown pdf 拡張
publishでnovel_writing.txtをmdにした上で、右クリック>markdown pdf: exportでchromeから見れるpdfを出力できる
が，pdfとしてきれいなのはnovel: pdf出力　ただしwslだとできなかった

各作品フォルダでln  -s  ../.vscode  .vscodeをたたき，親(novel_writing).vscodeをシンボリックリンクとして共有する
