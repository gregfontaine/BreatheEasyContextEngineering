# BreatheEasy — コンテキストエンジニアリング実験用データセット / A Dataset for Experimenting with Context Engineering

架空のスタートアップ「BreatheEasy」の社内資料一式です。AIに与えるコンテキストの量と質を変えながら、回答の精度や具体性がどう変わるかを体験・比較するために使えます。研修やワークショップの教材としても利用できます。

A complete set of internal documents for a fictional startup, "BreatheEasy." Use it to experience and compare how the quality and specificity of an AI's answers change as you vary the amount and quality of context you provide. It also works well as material for training sessions and workshops.

言語 / Language: **[日本語](#日本語)** ｜ **[English](#english)**

---

## 日本語

### これは何か

これは、実在しない企業「BreatheEasy」（呼吸・メンタルウェルネスアプリを提供する日本のスタートアップ）を題材にした、一貫性のある社内資料のセットです。すべて架空のデータですが、互いに矛盾しないように作られています（数字、時系列、登場人物、プロダクトの状況がドキュメント間でつながっています）。

目的はひとつです。同じ質問をAIに投げるとき、渡すコンテキスト（背景情報）が変わると、答えの質と具体性がどれだけ変わるかを、自分の手で確かめられるようにすることです。

### なぜコンテキストエンジニアリングなのか

AIは、与えられた情報の範囲でしか具体的に答えられません。会社の状況を何も知らなければ、返ってくるのは一般論です。逆に、適切な資料を適切な形で渡せば、その会社の事情に即した、実務で使える答えに近づきます。

ここで大事なのは「多ければよい」ではない、という点です。関係のない資料を大量に渡すと、かえって焦点がぼやけます。コンテキストエンジニアリングとは、どの情報を、どれだけ、どう構造化して渡すかを設計する技術です。このデータセットは、その効果を体感するための素材です。

### 舞台設定（BreatheEasyとは）

- 2024年設立、2025年6月にアプリを正式ローンチ、2026年1月に月額¥1,000のプレミアムプランを開始
- プレミアム会員数は2026年4月に5,400人でピークに達し、その後は減少（直近5か月で900人以上減）
- 創業以来ずっと赤字。2026年の最大の目標は黒字化
- 従業員11名、CEOはエミリー山口
- すべて架空の設定です

### 収録資料

資料はおおまかに4つのレイヤーに分かれています。この分類は、後述の「コンテキストのレベル」を組み立てるときにも役立ちます。

**経営・事業レイヤー**

- CEOメモ（2026年1月）: 戦略、現状の財務、年間目標、チームへの期待
- 投資家向けピッチ（2024年12月）: シードラウンドの資料（5ページ）
- プロダクト開発チームのOKR: 転換とリテンションに焦点を当てた四半期目標

**プロダクト・技術レイヤー**

- プロダクト構成図（2ページ）: システム全体像と主要な処理の流れ（非エンジニア向け）
- 従業員リスト: 11名の氏名・役割

**データ・調査レイヤー**

- ユーザー分析（Excel）: 月次のMAU・プレミアム会員数・売上・損益（グラフ付き）
- 解約ユーザーインタビュー: プレミアムを解約した12名への調査結果

**開発プロセスレイヤー**

- プロダクトバックログ（Excel）: 完了済み22項目（スプリント1〜12）と将来検討中16項目
- スプリントレポート（12本）: 各スプリントの完了アイテムとレトロスペクティブ議事録

（ファイル形式はExcel・Word・PowerPoint・PDF・テキストが混在します。お使いのAIツールによっては、テキストに変換したりファイルとしてアップロードしたりする必要があります。）

### 使い方：コンテキストのレベルを変えて試す

まず「試したい質問」を1つ決めます。次に、渡すコンテキストのレベルを変えながら同じ質問を投げ、返ってきた答えを並べて比べます。

| レベル     | 渡すコンテキスト                             | 観察できること                                               |
| ---------- | -------------------------------------------- | ------------------------------------------------------------ |
| L0：なし   | 資料を一切渡さず、質問だけ                   | 一般論・当たり障りのない回答。この会社ならではの具体性はない |
| L1：最小限 | CEOメモ1つだけ                               | 目標や大枠は踏まえるが、根拠となる数字や現場の声は薄い       |
| L2：中程度 | CEOメモ＋ユーザー分析＋解約インタビュー      | 数字と顧客の声に裏づけられた、具体的な打ち手が出はじめる     |
| L3：フル   | 資料一式（バックログやスプリント記録も含む） | 現状・原因・打ち手・実行計画までつながった、実務に近い回答   |

比べるときは、次のような観点で見ると違いがはっきりします。回答が具体的な数字や固有名詞に触れているか。この会社の実際の状況（4月のピークとその後の減少、黒字化目標）を踏まえているか。実行できるレベルまで落ちているか。それとも一般論で終わっているか。

発展として、「多ければよいわけではない」ことも試せます。質問に関係のない資料をあえて大量に混ぜてみて、焦点がぼやけないかを観察します。あるいは、生の資料をそのまま渡す場合と、要点を整理してから渡す場合を比べます。

### 注意事項

ここに含まれる企業、人物、数値、発言はすべて架空です。実在の企業・個人とは関係ありません。学習・実験・研修の目的で自由にお使いください。

### ライセンス

利用する際、私の会社「Agorax G.K（合同会社アゴラックス）」および／または私の氏名を明記していただけますようお願いいたします。

---

## English

### What this is

This is a consistent set of internal documents built around a fictional company called "BreatheEasy" (a Japanese startup that makes a breathwork and mental-wellness app). All of the data is invented, but it is designed to be internally consistent; the numbers, timeline, people, and product situation connect across the documents.

It has a single purpose: to let you see for yourself how much the quality and specificity of an AI's answer change when you change the context (the background information) you give it for the same question.

### Why context engineering

An AI can only be specific within the bounds of what it is given. If it knows nothing about your company, you get generic advice. Give it the right material in the right form, and its answers move closer to something grounded in that company's actual situation and usable in practice.

The key point is that more is not automatically better. Dumping in a pile of irrelevant material can blur the focus rather than sharpen it. Context engineering is the practice of designing which information you provide, how much of it, and how it is structured. This dataset is raw material for feeling that effect directly.

### The scenario (who BreatheEasy is)

- Founded in 2024; app launched June 2025; a ¥1,000/month premium plan launched January 2026
- Premium subscribers peaked at 5,400 in April 2026 and have declined since (down more than 900 over the last five months)
- Unprofitable since founding; the top goal for 2026 is to reach profitability
- 11 employees; the CEO is Emily Yamaguchi
- Everything is fictional

### What is included

The documents fall into roughly four layers. This grouping is also useful when you assemble the "context levels" described below.

**Business and strategy layer**

- CEO memo (January 2026): strategy, current finances, annual objectives, expectations for the team
- Investor pitch (December 2024): the seed-round deck (5 slides)
- Product team OKRs: quarterly objectives focused on conversion and retention

**Product and technology layer**

- Product architecture diagram (2 pages): the overall system and its main flows, written for non-engineers
- Employee roster: the names and roles of all 11 people

**Data and research layer**

- User analytics (Excel): monthly MAU, premium subscribers, revenue, and profit/loss, with charts
- Canceled-user interviews: findings from 12 people who canceled premium

**Development process layer**

- Product backlog (Excel): 22 completed items (sprints 1 to 12) and 16 items under future consideration
- Sprint reports (12 of them): each sprint's completed items and the retrospective minutes

(The files come in a mix of formats: Excel, Word, PowerPoint, PDF, and text. Depending on your AI tool, you may need to convert some to text or upload them as files.)

### How to use it: vary the level of context

Pick one question you want to test. Then ask that same question repeatedly while changing the level of context you provide, and line up the answers side by side.

| Level        | Context you provide                                       | What you can observe                                                                             |
| ------------ | --------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| L0: none     | The question only, with no documents                      | Generic, safe answers with none of this company's specifics                                      |
| L1: minimal  | The CEO memo alone                                        | Reflects the goals and broad shape, but is thin on supporting numbers and the voice of the field |
| L2: moderate | CEO memo + user analytics + cancellation interviews       | Concrete moves start to appear, backed by numbers and customer voices                            |
| L3: full     | The entire set (including the backlog and sprint records) | Answers that connect situation, cause, action, and a plan; close to something usable             |

When you compare, a few lenses make the differences obvious. Does the answer cite specific numbers or proper nouns? Does it reflect this company's actual situation (the April peak, the decline that followed, the profitability goal)? Does it get concrete enough to act on, or does it stay at the level of general advice?

As a further step, you can test the idea that more is not always better. Deliberately mix in documents that are irrelevant to the question and watch whether the focus blurs. Or compare handing over the raw documents as-is versus organizing the key points first.

### Disclaimer

Every company, person, number, and statement here is fictional. None of it relates to any real company or individual. Use it freely for learning, experimentation, and training.

### License

Kindly mention my company Agorax G.K (合同会社アゴラックス) and/or my name if you decide to use this.
