Amazon22 新卒技術試験

# Technical Topics to Review

- 時間がないなら、`practicing writing code outside of an IDE` and `reviewing CS fundamentals` will likely yield the best results for your time.

## Programming Languages

- どれか一つ卓越した言語を。
- メモリ管理などのニュアンスも。

## Data Structures

- 内部を知り、用途を比較できる
- runtime とメモリの使い方を知っていること

## Algorithms

- アルゴリズムの rote memorization はいらない。が、知ってたら問題がときやすくなるかも
- traversals, divide and conquer といった普遍的な流ゴリズムを見直せ
  - how and when to use a breadth-first search versus a depth-first search, and what the tradeoffs are
- Knowing the runtimes, theoretical limitations, and basic implementation strategies of different classes of algorithms is more important than memorizing the specific details of any given algorithm.(根本を知れ)

## Coding

- IDE なしで描けるように(少しのタイポやコンマのミスは OK)
- コードの評価基準は、`write scalable, robust, and well-tested code`.
  - => `check for edge cases and validate that no bad input can slip through`

## Object-Oriented Design

- やっとくべき

  - a working knowledge of a few common and useful design patterns
  - know how to write software in an object-oriented way, with appropriate use of inheritance and aggregation

- to describe the details of how specific design patterns work, but you may be asked about the logic behind your design choices.
  - デザインパターン自体の動きに関しては知らなくてもいいが、そのデザインパターン選択のロジックを問われるかも

## Databases

- RDB の NoRDB の動きの違い、そのトレードオフを知るほど、準備ができていると言える
- 専門家のレベルであることまでは想定していない
- 以下 Amazon の自分語り
  - Amazon has been at the forefront of the non-relational DB movement. We have made Amazon Web Services such as DynamoDB available for the developer community that let them easily leverage the benefits of non-relational databases.

## Distributed Computing

- いくつかの基本的な computing concepts を理解していることが必要。
- `service oriented architectures`, `MapReduce`, `distributed caching`, `load balancing`と言ったトピックを理解していれば、より複雑な分散アーキテクチャの質問にも答えられる。

- 以下 Amazon の自分語り
- Systems at Amazon have to work under very strict tolerances at a high load. While we have some internal tools that help us with scaling, it’s important to have an understanding of a few basic distributed computing concepts.

## Operating Systems

- OS を自分でフルスクラッチで作れる必要はない
- コードパフォーマンスに影響を与えるような、`memory management`, `processes`, `threads`, `synchronization`, `paging`, `multithreading`の理解は必要。

Internet Topics

- インターネットが実はどう動いているかの知識は必要

  - `how browsers work at a high level, from DNS lookups and TCP/IP, to socket connections`( We aren’t looking for network engineer qualifications, but a solid understanding of the fundamentals of how the web works is a requirement.)

- 面接官は記憶できているかを評価しているのではなく、それを使って問題を効率的/効果的に解けるよう応用する力を見たいのだ

# Amazon’s Leadership Principles

- あとでやる

# General Interview Tips

- Clarifying Question をしよう
- Customer Obsession が Amazon の全ての中心。

  - customer -> work の順番で話す
  - customer へのコミットメントを確かめるため、`talk about customers, advocate for them, and champion them`してもらう。
  - Amazon は本当に customer に取り憑かれていて、君もそうであることを確認したい。だから毎回のインタビューで customer について話してくれ。

- どのような思考の過程を辿っているのかを知りたいんので、推測したことを口に出すなどして、面接官には考えていることを伝える。
- チームでやったことに関しても、あなたが特に貢献した場所を明確に教えてください。

- 面接官に他の方法で解くように言われたら、それに柔軟に従いなさい

  - `flexibility is key at Amazon.`

- 質問に答える際には、簡潔且つ詳細に答えてください。

- 履歴書に書かれていることにはなんでも答えられるようにしておけ

  - 例えば履歴書に Java と Python と書いてあったら、その経験について技術質問するかも。

- 何百もの質問の羅列ではなく、一掴みの質問を聞き、それを深堀していく。

  - 高次元の状況下での質問を基に、who, what, when, where, why, how, etc に踏み込んでいく。

- 面接官の名前が事前にわかるなら、LinkedIn で調べよ
- 逆質問を数問用意していくこと
- カジュアルな格好で良い。

- Please spend some time thinking about why a career with Amazon would be mutually beneficial and be prepared to speak to it.ー

# Amazon Press

- またあとで

# Leadership Principle Worksheet

- Customer Obsession: Leaders start with the customer and work backwards. They work vigorously to earn and keep customer trust. Although leaders pay attention to competitors, they obsess over customers.

  - [ ] Example 1:
  - [ ] Example 2:

- Ownership: Leaders are owners. They think long-term and don’t sacrifice long-term value for short-term results. They act on behalf of the entire company, beyond just their own team. They never say “that’s not my job.”

  - [ ] Example 1:
  - [ ] Example 2:

- Invent and Simplify: Leaders expect and require innovation and invention from their teams and always find ways to simplify. They are externally aware, look for new ideas from everywhere, and are not limited by “not invented here.” As we do new things, we accept that we may be misunderstood for long periods of time.

  - [ ] Example 1:
  - [ ] Example 2:

- Are Right, A Lot: Leaders are right a lot. They have strong judgment and good instincts. They seek diverse perspectives and work to disconfirm their beliefs.

  - [ ] Example 1:
  - [ ] Example 2:

- Hire and Develop the Best: Leaders raise the performance bar with every hire and promotion. They recognize exceptional talent, and willingly move them throughout the organization. Leaders develop leaders and take seriously their role in coaching others. We work on behalf of our people to invent mechanisms for development like career choice.

  - [ ] Example 1:
  - [ ] Example 2:

- Insist on the Highest Standards: Leaders have relentlessly high standards—many people may think these standards are unreasonably high. Leaders are continually raising the bar and drive their teams to deliver high quality products, services and processes. Leaders ensure that defects do not get sent down the line and that problems are fixed so they stay fixed.

  - [ ] Example 1:
  - [ ] Example 2:

- Think Big: Thinking small is a self-fulfilling prophecy. Leaders create and communicate a bold direction that inspires results. They think differently and look around corners for ways to serve customers.

  - [ ] Example 1:
  - [ ] Example 2:

- Bias for Action: Speed matters in business. Many decisions and actions are reversible and do not need extensive study. We value calculated risk taking.

  - [ ] Example 1:
  - [ ] Example 2:

- Frugality: Accomplish more with less. Constraints breed resourcefulness, self-sufficiency and invention. There are no extra points for growing headcount, budget size or fixed expense.

  - [ ] Example 1:
  - [ ] Example 2:

- Learn and Be Curious: Leaders are never done learning and always seek to improve themselves. They are curious about new possibilities and act to explore them.

  - [ ] Example 1:
  - [ ] Example 2:

- Earn Trust: Leaders listen attentively, speak candidly, and treat others respectfully. They are vocally self-critical, even when doing so is awkward or embarrassing. Leaders do not believe their or their team’s body odor smells of perfume. They benchmark themselves and their teams against the best.

  - [ ] Example 1:
  - [ ] Example 2:

- Dive Deep: Leaders operate at all levels, stay connected to the details, audit frequently, and are skeptical when metrics and anecdote differ. No task is beneath them.

  - [ ] Example 1:
  - [ ] Example 2:

- Have Backbone; Disagree and Commit: Leaders are obligated to respectfully challenge decisions when they disagree, even when doing so is uncomfortable or exhausting. Leaders have conviction and are tenacious. They do not compromise for the sake of social cohesion. Once a decision is determined, they commit wholly.

  - [ ] Example 1:
  - [ ] Example 2:

- Deliver Results: Leaders focus on the key inputs for their business and deliver them with the right quality and in a timely fashion. Despite setbacks, they rise to the occasion and never settle.
  - [ ] Example 1:
  - [ ] Example 2:
