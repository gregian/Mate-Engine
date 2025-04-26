# 🌐 Language / 言語選択

- [English](#English)
- [日本語](#Japanese)

---


## English

![Mate Engine Preview](https://i.imgur.com/5cHHH8c.jpeg)

# Mate Engine

A free, lightweight alternative to **Desktop Mate** with custom VRM support and modding. Fewer limitations, more freedom.

- **App License**: Mixed — GNU AGPL v3 & Copyrighted Components  
  *Please read the license terms carefully.*
- **Default Avatar License**: All Rights Reserved by [Yorshka Shop](https://yorshkasencho.booth.pm/)  
  *Do not redistribute this model in your builds.*
- **QWEN 2.5 1.5b LLM**: *Apache License Version 2.0, January 2004*

---

## About the Project

**Mate Engine** was created as a free alternative to **Desktop Mate**.

Why? Because **Desktop Mate** charges **$10–$25 USD** for single character models—prices comparable to full games on Steam. On top of that, modding and custom models were disabled in later versions.

**Mate Engine** solves both problems:

- It's **completely free**
- It supports **custom VRM avatars**
- It’s **open-source and moddable**

![Mate Engine Preview](https://i.imgur.com/nNyWA1L.png)

---

## Free Hatsune Miku Support

Want to try with a free model?  
[Download Hatsune Miku VRM](https://booth.pm/en/items/3226395)

---

## Feature Comparison

| Feature                                      | Desktop Mate | Mate Engine |
|----------------------------------------------|--------------|-------------|
| Custom Shader Support                                  | ❌           | ✅          |
| Advanced .ME Model Format                                   | ❌           | ✅          |
| Mod Support                                   | ❌           | ✅          |
| Custom Model Support (.VRM, .ME)        | ❌           | ✅          |
| Window Sitting                     | ✅           | ⏸ (In Version 1.5.0)|
| Taskbar Sitting                    | ✅           | ⏸ |
| Dragging Animation                            | ✅           | ✅          |
| Idle Animation                                | ✅           | ✅          |
| Hiding on Edge of Screen                      | ✅           | ❌          |
| Head Movement                                 | ✅           | ✅          |
| Eye Movement                                  | ❌           | ✅          |
| Spine Movement                                | ❌           | ✅          |
| Hand Movement                                 | ✅           | ✅          |
| Alarm / Timed Animation                       | ✅           | ❌          |
| Dance Animation                               | ❌           | ✅          |
| Touch Reactions (Head / Sensitive Area)       | ⏸            | ✅          |
| Sound Effects                                 | ⏸ (On Paid Models Only)           | ✅          |
| Particle Effects                              | ❌           | ✅          |
| Smooth Animation Transitions                  | ❌ (Glitches between Animations)           | ✅          |
| FPS Control                                   | ❌           | ✅          |
| Always-on-Top Toggle                          | ❌           | ✅          |
| Open Source                                   | ❌           | ✅          |
| Chibi Mode                                    | ❌           | ✅          |

---

## Steam Release Support

![Mate Engine Preview](https://i.imgur.com/Efp1AfG.png)

**Funding Progress:** $239.34 / $100  
**Target Date:** March 26, 2025

Thanks to the amazing support of the community, **Mate Engine** will be released on Steam for **$3.99** — but it will always remain **free on GitHub**.

**Top Supporters:**
- Gra**** Ja***** – $94.00  
- Co**** Da***** – $96.00  
- Dym**** Sk***** – $5.59  
- Dreezer – $45.00

If you’d like to help with future updates or cover Steam fees, you can donate via **PayPal**:  
**johnson@soultechno.de**  
(*Please add a note: “MateEngine Donation”*)

---

## Smoother Transitions

![Mate Engine Preview](https://i.imgur.com/qS894h9.gif)

Mate Engine offers smoother animation transitions than Desktop Mate, avoiding the glitchy, abrupt changes often found in commercial alternatives.

---

## Performance

![Mate Engine Preview](https://i.imgur.com/MTbnIeE.png)

**Mate Engine** is lightweight and efficient. RAM usage depends on the avatar’s texture size. For example, the high-quality "Alice" model uses ~190MB of texture memory, leading to ~200MB total RAM usage. Using lighter models will reduce this further.

---

## Key Features

- **Idle Animations** – Loops while resting on your desktop  
- **Drag Animation** – Floats while being moved  
- **Dance Animation (Experimental)** – Reacts to music from Spotify, Firefox, etc.  
- **VRM Loader** – Supports any valid `.VRM` model  
- **Touch Regions** – Supports face/head interaction  
- **Custom Modding** – Drop in effects, sounds, and more  
- **Options Menu** – Right-click or press `M` to open the settings  
- **Always-on-Top Toggle**, **FPS Control**, **Chibi Mode**, and more

---

## Upcoming Features (Pre-Release 5–10)

- **Wallpaper Engine Integration** – Embed the pet directly into wallpapers  
- **Window & Taskbar Sitting** – Sit on any desktop app title bar  
- **Menu Color Customization** – Stylize your UI with custom themes  

---

## How to Use

1. Go to the **Releases** section (on the right-hand panel).  
2. Download the ZIP file marked as a public release (not source code).  
3. Unzip and run `MateEngineX.exe`.  
4. Right-click the avatar or press `M` to open the settings menu.

#### To use MateEngine with LocalAI, follow these steps:

1. Download the model from Hugging Face:  
   https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct-GGUF/resolve/main/qwen2.5-1.5b-instruct-q4_k_m.gguf
2. Once the download is complete, move the file `qwen2.5-1.5b-instruct-q4_k_m.gguf` into your project’s `Root/MateEngineX_Data/StreamingAssets` directory.

---

## Frequently Asked Questions

**Q: My VRM won’t load or inject!**  
A: This usually means your `.VRM` is incorrectly exported. Common issues include broken armatures or unsupported shaders. Use official exporters and test compatibility.

**Q: Is Hatsune Miku included?**  
A: No. Download her separately from [this Booth page](https://booth.pm/en/items/3226395).

**Need help with conversion?**  
Check this official guide: [VRM Conversion Guide](https://vrm.dev/en/vrm/how_to_make_vrm/)  
(Note: I can't provide support for model conversion.)

---

## Developer Guide

Want to contribute? Setup is easy:

1. Clone this repo and extract the folder.  
2. Open **Unity Hub** → **Add Project From Disk**  
3. Select the folder `Mate-Engine-BRANCH`  
4. Load the project, then open the scene:  
   `Scenes - USED FOR MATE ENGINE > Mate Engine Main`

> ⚠️ Avoid scenes like *Mate Engine InDev* unless you're on the dev branch.

---

## Antivirus Notice

If **Windows Defender** flags `Trojan:Script/Wacatac.B1ml`, **don’t worry** — this is a **false positive** caused by the app not being digitally signed.

You can verify safety by scanning the app on [VirusTotal](https://www.virustotal.com/).

---

## Final Words

Thanks for checking out **Mate Engine**!  
This project is made with love and designed to stay free forever.  
If you like it, share it or support it — but most of all, enjoy it.





---------------------------------------------------------------------



## Japanese

![Mate Engine Preview](https://i.imgur.com/5cHHH8c.jpeg)

# Mate Engine（メイトエンジン）

軽量なインターフェースとカスタムVRM対応を備えた、無料のDesktop Mate代替アプリ。制限が少なく、より自由に。

- **アプリのライセンス**：混合 — GNU AGPL v3 & 著作権付きコンポーネント  
  ※ライセンス内容をよくお読みください。
- **デフォルトアバターのライセンス**：[Yorshka Shop](https://yorshkasencho.booth.pm/) による著作権所有  
  ※このモデルを自作ビルドで再配布しないでください。

---

## プロジェクトについて

**Mate Engine** は、**Desktop Mate** の無料代替として開発されました。

理由はシンプルです：**Desktop Mate** のキャラモデルは 1体 **$10〜$25 USD** と高額で、これはSteamなどで販売されているフルゲームと同価格帯です。  
さらに、後期バージョンでは**Mod対応が削除**され、カスタムモデルの導入が不可能になりました。

**Mate Engine** はこれらの問題を解決します：

- 完全無料で利用可能  
- カスタムVRMアバターをロード可能  
- オープンソースかつMod対応

![Mate Engine Preview](https://i.imgur.com/nNyWA1L.png)

---

## 初音ミクを無料で楽しもう

無料モデルを試したい方へ：  
[初音ミク VRMをダウンロード](https://booth.pm/en/items/3226395)

---

## 機能比較

| 機能                                           | Desktop Mate | Mate Engine |
|-----------------------------------------------|--------------|-------------|
| ウィンドウ／タスクバーに座る                   | ✅           | ❌（計画中）|
| ドラッグ中アニメーション                        | ✅           | ✅          |
| 待機アニメーション                              | ✅           | ✅          |
| 画面端に隠れる機能                              | ✅           | ❌          |
| 頭の動き                                       | ✅           | ✅          |
| 目の動き                                       | ❌           | ✅          |
| 背骨の動き                                     | ❌           | ✅          |
| 手の動き                                       | ✅           | ✅          |
| アラーム／タイマーアニメーション               | ✅           | ❌          |
| ダンスアニメーション                            | ❌           | ✅          |
| タッチリアクション（頭・敏感部位）             | ❌           | ✅          |
| サウンドエフェクト                              | ❌           | ✅          |
| パーティクルエフェクト                          | ❌           | ✅          |
| スムーズなアニメーション遷移                    | ❌           | ✅          |
| FPS切り替え機能                                 | ❌           | ✅          |
| 最前面表示の切り替えボタン                      | ❌           | ✅          |
| VRMモデルのネイティブ読み込み                   | ❌           | ✅          |
| Mod対応                                         | ❌           | ✅          |
| オープンソース                                  | ❌           | ✅          |
| ちびキャラモード                                 | ❌           | ✅          |

---

## Steam公開のご支援をお願いします！

![Mate Engine Preview](https://i.imgur.com/Efp1AfG.png)

**資金状況：** $239.34 / $100  
**目標達成日：** 2025年3月26日

皆様のご支援により、**Mate Engine** は **$3.99** でSteam公開されます。  
ただし、**GitHubではこれからも完全無料です！**

**支援者の皆様：**
- Gra**** Ja***** – $94.00  
- Co**** Da***** – $96.00  
- Dym**** Sk***** – $5.59  
- Dreezer – $45.00

**支援はこちらから：**  
PayPal: **johnson@soultechno.de**  
（※「MateEngine Donation」と記載してください）

---

## スムーズなアニメーション遷移

![Mate Engine Preview](https://i.imgur.com/qS894h9.gif)

Mate Engineは**非常に滑らかなアニメーション遷移**を実現しています。  
Desktop Mateのようなカクつきや状態切り替えのバグがなく、常に自然な動きを保ちます。

---

## パフォーマンス

![Mate Engine Preview](https://i.imgur.com/MTbnIeE.png)

**Mate Engine** は軽量かつ省リソース設計。使用するモデルによってRAM消費は変動します。  
例：「Alice」モデルではテクスチャが約190MBで、合計約200MBのRAMを使用します。  
より軽量なモデルを使用すればさらに負荷は低下します。

---

## 主な機能

- **アイドルアニメーション** – デスクトップ上でループ再生  
- **ドラッグアニメーション** – 移動時にふわっと浮遊  
- **ダンス機能（実験的）** – SpotifyやFirefoxなどで音楽に反応  
- **VRMインジェクト** – 任意の正しい`.VRM`モデルを使用可能  
- **タッチリアクション** – 顔や頭のタッチに反応  
- **カスタムMod対応** – サウンド・パーティクルなどを自由に追加  
- **オプションメニュー** – ペットを右クリック、または`M`キーで開く  
- **FPS設定、最前面表示、ちびモード** なども搭載

---

## 今後のアップデート（Pre-Release 5〜10）

- **Wallpaper Engine連携** – 壁紙内にMate Engineを埋め込み可能  
- **ウィンドウ／タスクバーに座る機能** – 実装難易度高めですが検討中  
- **メニュー色カスタマイズ** – お好みに合わせてテーマ変更可能  

---

## 使い方

1. 右の「Releases」セクションから最新版ZIPをダウンロード  
2. `MateEngineX.exe` を展開し、実行  
3. ペットを右クリック、または `M` を押してオプションメニューを開く

---

## よくある質問

**Q: VRMモデルが読み込めません！**  
**A:** 多くの場合、モデルのエクスポート設定に問題があります。正しくボーンが設定されているか、互換性のあるシェーダーを使っているかご確認ください。

**Q: 初音ミクは最初から入っていますか？**  
**A:** 含まれていません。上記のBoothリンクから無料でダウンロードしてください。

**VRM変換の参考ガイド：**  
[公式VRM変換ガイド](https://vrm.dev/en/vrm/how_to_make_vrm/)

※VRMファイルの作成サポートは本プロジェクトの対象外です。

---

## 開発者向けセットアップ

Mate Engineの開発に参加するのはとても簡単です：

1. GitHubリポジトリをクローンし、展開  
2. **Unity Hub** を開き、「Add Project From Disk」を選択  
3. `Mate-Engine-BRANCH` フォルダを選択  
4. プロジェクトを開き、以下のシーンを開く：  
   `Scenes - USED FOR MATE ENGINE > Mate Engine Main`

> ⚠️ *Mate Engine InDev* などの別ブランチ用シーンは開かないでください。

---

## ウイルス検出に関する注意

**Windows Defender** が `Trojan:Script/Wacatac.B1ml` を検出する場合がありますが、**これは誤検知**です。  
アプリが**デジタル署名されていない**ために起こる問題です。

心配な方は [VirusTotal](https://www.virustotal.com/) などでスキャンしてください。

---

## 最後に

**Mate Engine** を楽しんでいただけたら嬉しいです！  
このプロジェクトはこれからも無料で公開していきます。  
支援やシェアも大歓迎ですが、何よりもまずは使って楽しんでください！
