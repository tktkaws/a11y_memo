0722
■達成方法/達成基準：1.1.1(A) / G73,G74,G92,H45

■地図画像のaltについて
主要な駅からの道のりを口頭で説明したものを文章化するイメージ

参考
https://www.mitsue.co.jp/company/access/head_office.html
https://alfasado.net/about/index.html"

■グラフのaltについて

参考
https://247accessibledocuments.com/writing-image-descriptions-for-graphs/


■組織図のaltについて

参考
https://www.digital.go.jp/about
https://www.mitsue.co.jp/company/structure.html


0723
今、アクセシビリティを考える 〜デジタル庁と富士通、それぞれの取り組み〜
https://nijibox.connpass.com/event/322922/?utm_campaign=event_message_to_selected_participant&utm_source=notifications&utm_medium=email&utm_content=title_link

https://www.digital.go.jp/policies/servicedesign/designsystem


0725
達成基準：1.3.1(A)

達成方法：G115,G117,G138,H49

検査項目：テキストの見た目や色によって情報を伝える場合、セマンティックな要素を使用していますか？（段落の表現、行間の調整、強調など）

不適合理由：読み手が文章の意味を把握しやすいようにハイライトしている場合はem要素を用いる。(そうでない場合は、そのようにお客様欄に記入してください。)

修正案：em要素を用いる。

文字サイズ選択ボタンで選択されたボタンの色が反転する実装だった。

修正案：em要素を用いる。　とあるが、ナビの現在地やテキスト拡大ボタンなどで選択されているボタンにem要素を使用している例が見当たらない

aria-current要素を使用しつつ、ボタンのテキストをem要素に変更するように実装した。em要素の必要性がまだ分かっていないので納得いってない。