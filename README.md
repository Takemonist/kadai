# ポストアポカリプス・ソーラーパンク探索ゲーム
# Post-Apocalyptic Solar-Punk Roguelike Explorer

荒廃した世界で緑の技術を探索するローグライクゲーム  
A roguelike exploration game set in a post-apocalyptic world where nature and solar technology are reclaiming the wasteland.

## 概要 / Overview

このゲームはJupyter Notebookで動作するローグライク探索ゲームです。プロシージャル生成されたマップを探索し、敵と戦い、アイテムを集めながら生き延びます。

This is a roguelike exploration game that runs in Jupyter Notebook. Explore procedurally generated maps, fight enemies, collect items, and survive!

## 特徴 / Features

### ポストアポカリプス要素 / Post-Apocalyptic Elements
- 🏚️ **廃墟 (%)** - 過去の文明の痕跡 / Ruins of past civilization
- ☢️ **放射線ゾーン (~)** - 危険な汚染地帯 / Dangerous contaminated zones
- 👾 **変異生物** - 変異ネズミ、野犬、放射線獣 / Mutated creatures

### ソーラーパンク要素 / Solar-Punk Elements
- ☀️ **ソーラーパネル (S)** - クリーンエネルギーで回復 / Recover health with clean energy
- 🌿 **植物と樹木 (♣♠)** - 自然の再生 / Nature reclamation
- 💧 **きれいな水源 (≈)** - 生命の源 / Clean water sources

### ローグライク要素 / Roguelike Elements
- 🗺️ **プロシージャル生成マップ** / Procedurally generated maps
- ⚔️ **ターン制戦闘** / Turn-based combat
- 📈 **レベルアップシステム** / Level-up system
- 🎒 **アイテム収集** / Item collection
- 💀 **パーマデス** / Permadeath

## インストール / Installation

### 必要なもの / Requirements
- Python 3.7+
- Jupyter Notebook または JupyterLab

### セットアップ / Setup

```bash
# リポジトリをクローン / Clone the repository
git clone https://github.com/Takemonist/kadai.git
cd kadai

# Jupyter Notebookをインストール（まだの場合）/ Install Jupyter Notebook (if not installed)
pip install jupyter

# Jupyter Notebookを起動 / Start Jupyter Notebook
jupyter notebook
```

## 遊び方 / How to Play

1. `roguelike_game.ipynb` をJupyter Notebookで開く / Open `roguelike_game.ipynb` in Jupyter Notebook
2. すべてのセルを順番に実行 / Run all cells in order
3. 最後のセルでゲームが開始 / The game starts in the last cell
4. コマンドを入力してプレイ / Enter commands to play

## 操作方法 / Controls

- **w** - 上に移動 / Move up
- **a** - 左に移動 / Move left
- **s** - 下に移動 / Move down
- **d** - 右に移動 / Move right
- **p** - アイテムを拾う / Pick up item
- **i** - インベントリを表示 / Show inventory
- **q** - ゲーム終了 / Quit game

## マップ記号 / Map Symbols

| 記号 | 説明 | Description |
|------|------|-------------|
| @ | プレイヤー | Player |
| E | 敵 | Enemy |
| * | アイテム | Item |
| # | 壁 | Wall |
| . | 床 | Floor |
| S | ソーラーパネル | Solar Panel |
| ♣ | 植物 | Plant |
| ♠ | 樹木 | Tree |
| ~ | 放射線 | Radiation |
| ≈ | 水 | Water |
| % | 廃墟 | Ruins |
| > | 出口 | Exit |

## ゲームシステム / Game Systems

### 戦闘 / Combat
敵に接触すると戦闘が発生します。攻撃力と防御力によってダメージが決まります。

When you touch an enemy, combat occurs. Damage is determined by attack and defense values.

### レベルアップ / Level Up
敵を倒すと経験値を獲得し、一定値に達するとレベルアップします。

Defeat enemies to gain experience. Level up when you reach certain thresholds.

### アイテム / Items
- **ソーラーバッテリー** - エネルギーを蓄える / Store energy
- **薬草** - 体力を20回復 / Restore 20 HP
- **浄水** - 体力を10回復 / Restore 10 HP
- **テクノスクラップ** - 技術の欠片 / Tech fragments
- **植物の種** - 新しい命の種 / Seeds of new life
- **放射線防護服** - 放射線から保護 / Protect from radiation

### 環境効果 / Environmental Effects
- **ソーラーパネル** - 体力回復 / Restore HP
- **放射線ゾーン** - ダメージを受ける / Take damage
- **水源** - 体力小回復 / Small HP restore
- **植物** - 稀に体力回復 / Occasionally restore HP

## 目標 / Objectives

出口（>）を見つけて次のエリアへ進み、できるだけ長く生き延びましょう！

Find the exit (>) to progress to the next area and survive as long as possible!

## ライセンス / License

MIT License

## 作者 / Author

Takemonist