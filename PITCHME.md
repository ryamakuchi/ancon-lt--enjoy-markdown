# enjoy Markdown 😉

---

## まずはじめに

- この資料は「アンコン7月 LT 大会」（社内勉強会）で使用したスライドです
- 非エンジニアの方に向けて、Markdown について語っています

---

## Markdown って何か知っている人？ ✋️

---

## Markdown を実際に使っているよ〜って人は？ ✋️

---

## Markdown とは

---

- 書きやすくて読みやすい、軽量マークアップ言語
- 書いた言語は HTML へ変換できる
- HTML だけではなく他のいろんなものに変換できる

---

### リッチエディタとの違い

- 一度書いてから画面をポチポチ押して見た目を成形するリッチエディタ
- Markdown は書くだけで見た目がエディタによって整形されるため、圧倒的に作業効率が良い

---

### HTML との違い

- そもそも非エンジニアは HTML とか書けない
  （でもきれいな文書を簡単に作りたい）
- Markdown なら非エンジニアでも簡単に書ける！！！ 😚

---

## どんなときに便利？

---

- 自分用のまとめメモとして（esa）
<img width="100%" alt="esa でまとめた Markdown" src="https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/3045945f-2731-de33-2b5e-cab1b81a0c5c.png">

---


- ブログ書くときに（はてなブログ）
<img width="100%" alt="はてなブログでまとめた Markdown" src="https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/f1cb986e-192b-d300-8065-0d098b8c527e.png">

---

- MTG の議事録に（HackMD）
<img width="100%" alt="HackMD でまとめた Markdown" src="https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/9ab99527-2cd7-2d44-8497-15bc04a7fb0d.png">

---

- 印刷すれば見やすい資料が簡単に作れる（HackMD）
<img width="100%" alt="HackMD を印刷してみた" src="https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/23f1d685-f557-7d51-f212-0336b07fe316.png">

---

- 何ならこんな感じのスライドですら Markdown で作れる ✌️ （Qiita）
<img width="100%" alt="Qiita スライドでまとめた" src="https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/c0804c06-c377-ec6f-0e75-b7b9b301f1b0.png">

---

※ 他にも色んな Web サービスやツールがあるけど詳しくは割愛

---

## Markdown の使い方

---

### 基本的な使い方

- `## 見出し`
    - # タイトル
        - `# ` がタイトル、`## ` が大見出し、`### ` など `#` の数が多くなるにつれて小さい見出しになっていく
    - HTML でいう `h1 ~ h6` と同じ意味

---

- `- リスト`
    1. `- ` や `* ` をつけて書くと、リストになる
    2. `1. ` `2. ` という風に書くと順番つきリストになる

---

- `**太字**`
    - **太字**

---

- `~~打ち消し線~~`
    - ~~打ち消し線~~

---

- `> 引用`
    - > 何かを引用したいときに使う

---

- `--- 水平線`
    - `---` と書くと水平線が引ける

---

- `code 記法`
    - バッククォート ` で囲むとコードとして扱われる
        - Slack で文字を赤くしているのはコレ
    - バッククォート 3つで囲むと、コードフェンスとして使える（エンジニアがよく使ってるやつ）

---

### ここがすごいよ Markdown

- 表も書ける！

```
| 表1 | 表2 |
| --- | --- |
| ほげほげ | ふがふが |
| まげまげ | むがむが |
```

---

| 表1 | 表2 |
| --- | --- |
| ほげほげ | ふがふが |
| まげまげ | むがむが |

---

- リンクも貼れる！
    - `[アン・コンサルティング株式会社](https://www.anconsulting.jp/)`
    - [アン・コンサルティング株式会社 | an consulting inc](https://www.anconsulting.jp/)

---

- イメージ画像も貼れる！！
    - `![チューチュートレイン.jpg](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/f7027e53-9b99-1841-6993-0850735f5f97.jpeg)`
    - ![チューチュートレイン.jpg](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/f7027e53-9b99-1841-6993-0850735f5f97.jpeg)

---

- 絵文字も書けるよ 👍 （厳密には Markdown ではないけれど、よく見る書き方）
    - `:relaxed:` というふうに、`:` で囲む
    - ☺️

---

## こんな Markdown ツールが便利

---

- HackMD （ https://hackmd.io/ ）
    - 同時編集機能がある
    - キーマップで使いたいエディタを設定できる（書き心地を選べる）
        - Sublime
        - Emacs
        - Vim
    - ⚠️ URL を公開すると共有ができ、URL を知っている人はアクセスできる

---

- esa（ https://esa.io/ ）
    - WIP 機能があり書き途中かどうかがわかる
    - パスでディレクトリを区切ることで文書整理がしやすい
    - コメントも残せる
    - Slack のように絵文字の追加ができる
    - 基本 URL は非公開だけど共有リンクも作れて共有することができる
    - ![esa.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/5675cd3c-1744-ada5-547e-437a8275e588.png)
    - エンジニアチームや勉強会などのコミュニティで使われることが多い
    - 何よりプロダクトがかわいい
    - **esa だいすき**

---

### Markdown が使える Web サービスやエディタツールは他にもたくさんあるよ

- Qiita（ https://qiita.com/ ）
    - エンジニアの情報共有を目的とした Web サービス
    - このスライドも Qiita の機能
    - エンジニアチームは Qiita Team という文書管理ツールを使っているところが多い

---

- Gist（ https://gist.github.com/ ）
    - GitHub が出している Web サービス
    - Git でバージョン管理ができる
    - GitPitch という機能を使ってスライドを作ることもできる
        - https://github.com/kakisoft/HowToUseGitPitch
    - **このスライドもそう！**

---

- VS Code（ https://code.visualstudio.com/ ）
    - これはプログラマーがよく使っている無料のエディタ
    - Microsoft が開発している
    - プラグインが豊富

---

- Boostnote（ https://boostnote.io/ja/ ）
    - これはノートアプリで、インストールして使う

---

などなど...

**Markdown で書けるツールはすごくたくさんある**

---

- 実際に触ってみた
<img width="300px" alt="misawa.jpeg" src="https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/236385/1384ecfe-b36a-7993-d1f0-600550024dfb.jpeg">

---

## Markdown がだいすき 💕

