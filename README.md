## m-higashi

放射線科医です。画像診断が本業で、**医療画像とAIの研究**に関わっています。

仕事をしていて「こういう道具があれば」と思ったものを、自分で作って使っています。
ここに置いてあるのは、実際に自分の日常業務で毎日動かしているものです。

### 作っているもの

| | |
|---|---|
| **[reftool](https://github.com/m-higashi/reftool)** | 手元の PDF / PPT / PPTX を1ファイルも移動せずに一覧・検索・整理する文献リファレンスツール（Python・依存4つ） |
| **[focus-tracker](https://github.com/m-higashi/focus-tracker)** | 作業1件ごとにワンタップ記録、休憩アラートと集中力の統計まで。キャラクターが見守る集中力トラッカー（Node.js・依存ゼロ） |
| **[exam-drill](https://github.com/m-higashi/exam-drill)** | 答えの無い過去問を、自分で解きながら解説つきの問題集に育てる練習アプリ。まちがい復習・スマホ対応（Python 標準ライブラリのみ・依存ゼロ） |
| **[Benchforge](https://github.com/m-higashi/benchforge)** | 手元の PC で動く AI に試験問題を解かせ、成績を信頼区間・検定つきで比べる評価ツール。画像問題対応・外部送信なし（Python・ollama） |

### 作るときに決めていること

- **ローカルで完結させる。** データを外に出さない。クラウドに預けない
- **依存を増やさない。** 入れるものが少ないほど、数年後も動く
- **インストール作業を、なるべく利用者に求めない。** ダブルクリックで起動して、閉じたら終わり
- **自分のデータで毎日使う。** 使わなくなった機能は、たいてい要らなかった機能

医療の現場は、データを外に出せない場面が多く、環境も自由になりません。
その制約の中で使えるものを作ろうとすると、自然とこうなりました。

---

<sub>**English**: Radiologist. I build small, local-first tools for my own clinical and research
workflow — no cloud, minimal dependencies, no installation required. Everything here is
something I actually use every day.</sub>
