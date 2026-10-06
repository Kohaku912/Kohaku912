<div align="center">

# 河原 樹 / Kohaku912

**バックエンド・アプリケーション開発** ｜ N高等学校 3年次（ネットコース）｜ 2027年3月 卒業見込み

Python / Java / Kotlin / C++ を中心に、サーバーサイドからアプリ・ハードウェア制御まで開発しています。

[![Portfolio](https://img.shields.io/badge/Portfolio-kohaku912.github.io-2563eb?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kohaku912.github.io/portfolio/)
[![Resume](https://img.shields.io/badge/Resume-%E8%81%B7%E5%8B%99%E7%B5%8C%E6%AD%B4%E6%9B%B8-0f766e?style=for-the-badge&logo=readdotcv&logoColor=white)](https://kohaku912.github.io/portfolio/resume.html)
[![AtCoder](https://img.shields.io/badge/AtCoder-Cyan%201249-1f8ac0?style=for-the-badge&logo=atcoder&logoColor=white)](https://atcoder.jp/users/tatuki912)

</div>

---

## できること

| 領域 | 内容 |
|---|---|
| **バックエンド** | REST API の設計・実装（FastAPI / SQLAlchemy）、JWT 認証、DB 設計、ページネーション・検索・ソート |
| **テスト・品質** | pytest による自動テスト、カバレッジ計測、Ruff による lint / format |
| **インフラ・運用** | Docker（multi-stage・非 root）、GitHub Actions による CI |
| **アプリ開発** | Android（Kotlin / Java）、デスクトップ、Web フロントエンド（React / Vue / Three.js） |
| **ハードウェア** | LiDAR を用いたロボットアームの制御（Python） |

## 技術スタック

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

## 主なプロジェクト

### 🚀 [TaskFlow API](https://github.com/Kohaku912/taskflow-api) — タスク管理 REST API
サーバーサイドの実装力を示すために、設計から CI まで一通り自作した API。

- JWT 認証（bcrypt によるパスワードハッシュ）、検索・フィルタ・ソート、ページネーション
- **他人のリソースは 404 を返して存在を秘匿**（IDOR 対策）
- **テスト 30 件 / カバレッジ 97%**、Docker（非 root）＋ GitHub Actions CI
- 技術：`Python` `FastAPI` `SQLAlchemy 2.0` `Pydantic v2` `pytest` `Docker`

### 🤖 [JARVIS（仮）](https://github.com/Kohaku912/JARVIS) — 音声 AI アシスタント
ウェイクワード検出と生成 AI を組み合わせた、音声で操作できるアシスタント。`Kotlin` `Gemini API` `Porcupine`

### 📚 [まなとも](https://ai-friend-theta.vercel.app/) — 学習支援アプリ
各教科の AI が会話の中で問題を出題するアプリ。**第6回 学力向上アプリコンテスト 優秀賞**。`React` `Gemini API`

### 🦾 [robotarm](https://github.com/Kohaku912/robotarm) — LiDAR ロボットアーム
部屋の中の物を把持・運搬するロボットアームの制御。`Python` `LiDAR`

### ✂️ [RealNote](https://github.com/Kohaku912/RealNote) — ちぎれるメモ帳
**ZEN Study 動くWebページコンテスト 2025 夏 優秀賞／角川ドワンゴ学園部門**。`HTML` `CSS` `JavaScript`

### 🏛️ [MyMuseum](https://github.com/Kohaku912/MyMuseum) — 3D ミュージアム
WebGL で作った自分だけの 3D ミュージアム。`HTML` `JavaScript` `WebGL`

## 実務経験

| 期間 | 会社 | 形態 | 職種 |
|---|---|---|---|
| 2026年6月頃（約1か月） | 株式会社ナノベース | 業務委託 | フルスタックエンジニア |
| 2025年8月頃（約2週間） | 株式会社ビーライズ | インターン | XRエンジニア |

ナノベースでは **PHP / Laravel** で就職・求人サイトの改修をフルスタックに担当しました。ビーライズでは **Unity** でごみ処理場の 3D 見学アプリと、音楽系マネージャー機能の実装・バグ修正を担当しました。

## 資格・受賞

- 🏅 **基本情報技術者試験** 合格（2025年9月）
- 📈 **AtCoder 水色**（Rating 1249 / 4級）
- 🥈 第6回 学力向上アプリコンテスト **優秀賞**（2025年10月）
- 🥈 ZEN Study 動くWebページコンテスト 2025 夏 **優秀賞**／角川ドワンゴ学園部門（2025年10月）
- 🏅 ZEN Study 動くWebアプリコンテスト 2024 冬 **ラムダ技術部特別賞**（「SpeedyFingers」・2025年3月）

## いま取り組んでいること

- サーバーサイドの設計力強化（DB 設計・マイグレーション・パフォーマンス）
- クラウド（AWS / GCP）とコンテナオーケストレーションの学習
- AtCoder への継続参加

---

<div align="center">

**お仕事のご相談・ご連絡は [ポートフォリオ](https://kohaku912.github.io/portfolio/) からお願いします。**

</div>
