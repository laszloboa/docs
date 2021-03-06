---

copyright:
  years: 2015, 2016

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen:.screen}
{:codeblock:.codeblock}


# 機械翻訳のヒント
{: #globalizationpipeline_tips}

*最終更新日: 2016 年 3 月 27 日*
{: .last-updated}

機械翻訳は、原文の大まかな意味を示すという点では効果的です。しかし、機械翻訳の品質と有用性は、ターゲット言語と使用する機械翻訳エンジンに大きく左右されます。機械翻訳の品質の重要な要素の 1 つは、原文自体の品質です。口語表現、不完全な文、不適切な句読点、あいまいな言い回しなどが多く含まれる原文は、正しく翻訳されないことがあります。
{:shortdesc}

{{site.data.keyword.Bluemix_notm}} アプリ UI を作成する場合は、ソース言語だけでなく機械翻訳の品質を向上させるためにも、表記についてのいくつかの基本的なガイドラインに従ってください。

また、その言語のネイティブ・スピーカーに機械翻訳のレビューと編集を依頼してください。そして、アプリ・ユーザーからのフィードバックを収集してください。かれらが、最も良く翻訳の有用性や正確さを判定できるはずです。

## 文体のヒント
{: #writingstyletips}

* **短い文または中程度の長さの文にする (単語数は 5 から 20 程度):** 機械翻訳エンジンは、セミコロンで接続された文も含め、複雑な複合文を翻訳するのが苦手です。1 文につき 1 つの内容を伝えてください。2 つの内容を伝えるために 1 文に能動態の動詞が 2 個含まれている場合は、その文を 2 文に分割してください。
短すぎてコンテキストが読み取れない文を解析するのも、機械翻訳エンジンは苦手です。
* **フレーズだけの文を避ける:** 可能な限り完全な文を使用してください。
見出しや副見出しではフレーズを使用してもかまいませんが、電報の見出しのような書き方は避けてください。箇条書きにする場合は、その前の文と合わせて完全な文になるようにしてください。
* **イディオム、スラング、業界用語を避ける:** 文字どおりの翻訳が意味をなさないフレーズは書き換えてください。例えば、「on the fly」は「dynamic」に、「on the other hand」は「alternatively」に、「keep in mind」は「remember」に書き換えてください。
* **ユーモア、皮肉、話し言葉、顔文字、メタフォーは避ける。**
* **簡潔:** 不要なテキストや冗長な表現は削除してください。例えば、「It is useful to remember that large values increase the response time」は「Large values increase the response time」と書き換えてください。
* **すべて大文字の文は避ける:** 大文字小文字の区別は語の意味を左右します。例えば、「BILL」と書いた場合、機械翻訳エンジンは名前の「Bill」なのか単語の「bill」(請求書) なのか判断できません。
* **あいまいな語を避ける:** 例えば、「after」や「when」の代わりに「once」を使用しないでください。「although」や「whereas」の代わりに「while」を使用しないでください。「might」や「can」の代わりに「may」を使用しないでください。
* **代名詞を避ける:** 名詞や名詞句は可能な限り何度も使用してください。代名詞「it」は特に問題になります。
* **可能な限り能動態で書く:** 通常、能動態の文は受動態の文よりも意味が明確です。例えば、「The most efficient path is determined」ではなく「The utility determines which path is most efficient」と書いてください。
* **文化固有の情報を避ける。**
* **機械翻訳エンジンが製品名を翻訳する可能性に注意する:** 多くの国では製品名は英語のままです。しかし、製品名に本物の単語が含まれている場合は特に、機械翻訳エンジンは製品名を翻訳しようとします。製品名を使用する前に、製品名の翻訳をテストしてください。問題があった場合は、適宜、テキストや訳語を修正してください。
* **すべての情報を 1 つの言語で記述する:** テキストに別の言語の単語が 1 つ以上含まれていても、機械翻訳エンジンは、すべての情報が単一言語で書かれていると想定します。例えば、テキストに「en route」(フランス語) が含まれていると、機械翻訳エンジンはその単語を英単語として訳そうとします。
* **マーケティング・スローガンを避ける:** マーケティング・スローガンには、特定の文化の購買層の認識を基にしたものがよくあります。そのようなスローガンは、機械翻訳エンジンで正確に翻訳できない可能性があるため、避けてください。
* **箇条書きの項目はすべて統一する:** 例えば、1 つの項目が動詞で始まるなら、他のすべての項目も動詞で始めてください。
* **please や thank you は使わないようにする:** このような語は不自然に見えることがあり、文化によっては恩着せがましい印象を与えることさえあります。
* **日付は数字でない表記にする:** 日付の数字表記は国によって異なります。月の名前、日、年を記述してください。例えば、9/01/03 ではなく 1 September 2003 を使用します。9/01/03 は、1 September 2003 と 9 January 2003 のどちらにも解釈できます。

## 文法のヒント
{: #grammartips}

* **句読点を適切に使用する:** ピリオドやコンマを略すと、機械翻訳エンジンが情報を誤って解釈する可能性があります。
* **動詞の活用形を主語に合わせる:** 複数主語には動詞の複数形、単数主語には動詞の単数形を使用してください。
* **現在形の動詞を使用する:** 英語以外の言語の多くは、態や時制といった英語動詞が持つ性質を持っていません。未来形や過去形は可能な限り避けてください。例えば、「If you run this program, DB2® will return an error message」は「If you run this program, DB2 returns an error message」と書き換えてください。
* **代名詞と先行する記述を合わせる:** 例えば、「A user should first determine their tasks」は「Users should first determine their tasks」と書き換える必要があります。
* **懸垂修飾語を避ける:** 修飾語は、意図した名詞を修飾するように適切な位置に配置してください。例えば、「While typing in commands, the program does not send any messages to you」は「While typing in commands, you do not receive any messages from the program」と書き換えることができます。
* **二重否定を避ける:** 例えば、「Do not omit the date」は「Include the date」と書き換えることができます。
* **文頭では動詞の不定詞 (to write)、現在分詞 (writing)、過去分詞 (wrote) を避ける:** 動詞のこれらの語形はあいまいで翻訳しにくいことがよくあります。
* **名詞句を避ける:** 「special filter factor estimate considerations」のような複合名詞句を避け、3 語以内にしてください。
* **複数の品詞として単語を使用しない:** 「default」など、英単語の多くは、名詞にも動詞にもなります。他の多くの言語は、そのような構造になっていません。単語ごとに用法を統一してください。例えば、「default」は常に名詞として使用するようにしてください。
* **文の要素を揃える:** 例えば、文の中で列挙する場合は、すべて名詞にするか、すべて動詞にします。名詞と動詞を混在させないでください。
* **必要な語を省かない:** 例えば、「The file names are displayed in uppercase characters and the file extensions in lowercase」ではなく「The file names are displayed in uppercase characters and the file extensions are displayed in lowercase characters」とします。必要に応じて、意味を明確にするために「that」を使用してください。例えば、「If you determine the problem is a missing file」は「If you determine that the problem is a missing file」と書き換えます。
* **ダッシュを挿入句として使用しない:** 例えば、「When you get to this point - the point when all data has been loaded- you need to test the system」のように書かないでください。ダッシュはコンマに書き換えるか、文全体を書き直してください。
 
## 用語のヒント
{: #terminologytips}

* **用語の統一:** 同じことを指す複数の用語を使用しないでください。単一の用語を複数の意味で使用することも避けてください。
* **専門用語には説明を付ける。**
* **環境や文脈で意味が変わる用語は避ける:** 例えば「billion」、「domestic」、「foreign」などがあります。
* **大文字小文字の区別、ハイフン付け、語の表記を標準化して統一する:** 例えば、「fixpack」ではなく「fix pack」と表記します。
* **固有名詞ではない用語は小文字で表記する。**
* **特殊文字を避ける:** # 記号を使用する必要がある場合に、「pound sign (ポンド記号)」と表記しないでください。代わりに、number symbol (番号記号) (#) と呼んでください。
* **略語を避ける:** 機械翻訳エンジンは、IBM や DB2 などの一般的な略語は認識しますが、あらゆる略語を認識するわけではありません。可能な限り略語は避けてください。「i.e.」や「etc.」などのラテン語起源の略語は使用しないでください。

## 句読法のヒント
{: #punctuationtips}

* **スラッシュを「and or」の意味で使用しないようにする:** 正確な意味がわかるように文を書き換えてください。例えば、「You can view the draft copy and/or the review copy」は「You can view the draft copy, the review copy, or both」と書き換えることができます。
* **複数であることを (s) を追加して示すことは避ける:** 「one or more」の句を使用するか、複数形のみを使用します。
* **and の意味でアンパーサンド (&) を使用しない。**
* **文中で列挙する場合はコンマで項目を区切り、続ける項目の前にコンマを置く:** 例えば、「Select your company, location, and profession」とします。

## スペルのヒント
{: #spellingtips}

* **スペル・チェック:** 単語のミススペルは翻訳エラーを引き起こす可能性があります。必ず、タイプミスがないことを確認してください。
* **スペルの統一:** 用語、頭字語、固有名詞のスペルは、大文字小文字の区別も含めて統一してください。

## ビジュアル表示のヒント
{: #visualtips}

* **グラフィックスの中にテキストを使用しない。**
* **強調のために書式設定を使用しない。**
