# 参加ガイド / Contributing Guide

## 日本語

### はじめに

SDI Dashboardは、世界中の人々が「社会の歪み」を一緒に見て、  
一緒に考え、一緒に修復していくためのプロジェクトです。

あなたの参加を、どんな形でも歓迎します。

---

### 参加の方法

#### 1. まず話しかけてください

[Discussions](../../discussions) で自己紹介してください。  
どんな国から来たか、何に共感したか、それだけで十分です。

#### 2. データを追加する

あなたの国・地域のデータを `data/` フォルダに追加できます。

```json
{
  "country": "Japan",
  "year": 2025,
  "entries": [
    {
      "label": "看護師",
      "income": 380,
      "contrib": 9,
      "risk": 3,
      "social": 5,
      "time": 1,
      "sector": "healthcare",
      "role": "worker"
    }
  ]
}
```

データの根拠（出典）を一緒に記載してください。  
完璧でなくて構いません。議論しながら改善します。

#### 3. 数式を検証・改善する

SDIの数式はまだ発展途上です。  
「この係数はこう変えるべき」「この変数が足りない」  
そういう批評こそが理論を強化します。

[Issues](../../issues) に投稿してください。

#### 4. 翻訳する

README・ダッシュボード・解説文を多言語化したいです。  
あなたの母語で翻訳してくれるだけで、世界が広がります。

#### 5. 広める

Starを押す、SNSでシェアする、仲間に話す。  
それだけでも球面の一点になります。

---

### 行動規範

- 批判ではなく**修復**を目指す
- 数値や根拠を大切にする
- 異なる意見を球面上の別のベクトルとして尊重する
- 「総和がゼロに向かう」という原理を忘れない

---

## English

### Welcome

SDI Dashboard is a project for people around the world  
to see social distortions together, think together,  
and work toward repair together.

Any form of participation is welcome.

---

### How to Participate

#### 1. Say Hello First

Introduce yourself in [Discussions](../../discussions).  
Where you're from, what resonated with you — that's enough.

#### 2. Add Data

Add your country or region's data to the `data/` folder.

Please include the source of your data.  
It doesn't need to be perfect — we improve through discussion.

#### 3. Challenge the Formula

The SDI formula is still evolving.  
"This coefficient should change." "This variable is missing."  
Critical feedback is what strengthens the theory.

Post in [Issues](../../issues).

#### 4. Translate

We want to localize the README, dashboard, and explanations.  
Translating into your native language expands our world.

#### 5. Spread the Word

Star the repo, share on social media, tell a friend.  
Even that makes you a point on the sphere.

---

### Code of Conduct

- Aim for **repair**, not criticism
- Value data and evidence
- Respect different opinions as different vectors on the sphere
- Remember: the sum of all vectors converges to zero

---

*The sphere is completed by many points.*  
*You are one of them.*
