オリジナルURL:https://heroku-app-mobileguide.herokuapp.com/exhibits/index

モバイルガイドのhtml,css,~~js~~をコピペしてファイルに起こしました。
*jsは謎が深かったので参照するの止めました。（Rails絡みのコードっぽい。）これでも十分閲覧に耐えます。


オリジナルと比べると、ディレクトリ構成を変更した箇所が一部あります。
（オリジナルでは/exhibits/indexとなっていた展示物一覧のページを、index.htmlと同じ階層にlist.htmlとして配置しています。）

railsで生成されたwebページを、素のhtml,cssに変更した都合で、いくつかhtmlファイルを修正しないとならない点があります。モバイルガイドを研究に使いたい人、暇な人がいたら修正お願いします。

階層構造など、利用する人の好きに変えてください。以下の点は、階層構造やファイル名を現行通りのままで使おうとする場合に修正が必要な点となっています。

- <meta charset="utf-8">を付与
- cssの参照先を"default.css"に変更
- 「モバイルガイド」「解説一覧」のリンクを"list.html"に変更(exhbits内のファイルについては"../list.html")
- list.htmlの"/default.png"について、頭の/を消す
