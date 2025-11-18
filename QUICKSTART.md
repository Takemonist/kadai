# クイックスタートガイド / Quick Start Guide

## 日本語 / Japanese

### 1. セットアップ

```bash
# リポジトリをクローン
git clone https://github.com/Takemonist/kadai.git
cd kadai

# 必要なライブラリをインストール
pip install -r requirements.txt
```

### 2. ゲームの起動

```bash
# Jupyter Notebookを起動
jupyter notebook
```

ブラウザが開いたら、`roguelike_game.ipynb` をクリックして開きます。

### 3. ゲームの実行

1. ノートブックの上部メニューから「Cell」→「Run All」を選択
2. または、各セルを上から順番に実行（Shift+Enter）
3. 最後のセルでゲームが開始されます

### 4. 遊び方

#### 基本操作
- **w** - 上に移動
- **a** - 左に移動  
- **s** - 下に移動
- **d** - 右に移動
- **p** - アイテムを拾う
- **i** - インベントリを表示
- **q** - ゲーム終了

#### ゲームの目的
1. マップを探索する
2. 敵を倒して経験値を得る
3. アイテムを集めて生き延びる
4. 出口（>）を見つけて次のエリアへ進む
5. できるだけ長く生き延びる！

#### 重要な要素

**回復要素：**
- ☀️ ソーラーパネル (S) - 体力回復
- 💧 水源 (≈) - 体力小回復
- 🌿 植物・樹木 (♣♠) - 時々体力回復
- 🌿 薬草アイテム - 体力+20

**危険要素：**
- ☢️ 放射線ゾーン (~) - ダメージ
- 👾 敵 (E) - 戦闘が発生
- 🏚️ 廃墟 (%) - 探索要素

### 5. ゲームのコツ

1. **体力管理が重要** - HPが減ったらソーラーパネルや水源で回復
2. **レベルアップを狙う** - 敵を倒して経験値を稼ぐ
3. **放射線に注意** - 放射線ゾーン(~)は避けて通る
4. **アイテムを集める** - 薬草や浄水は生存に必要
5. **慎重に探索** - 敵が多い時は回避も戦略

### トラブルシューティング

#### Jupyter Notebookが起動しない
```bash
# Jupyterを再インストール
pip install --upgrade jupyter notebook
```

#### ゲームが文字化けする
- ターミナルの文字コードをUTF-8に設定してください
- または、英語版のコメントを参考にプレイしてください

#### エラーが出る
- Python 3.7以上がインストールされているか確認
- すべてのセルを上から順番に実行しているか確認

---

## English

### 1. Setup

```bash
# Clone the repository
git clone https://github.com/Takemonist/kadai.git
cd kadai

# Install requirements
pip install -r requirements.txt
```

### 2. Launch the Game

```bash
# Start Jupyter Notebook
jupyter notebook
```

When the browser opens, click on `roguelike_game.ipynb`.

### 3. Run the Game

1. Select "Cell" → "Run All" from the top menu
2. Or run each cell sequentially (Shift+Enter)
3. The game starts in the last cell

### 4. How to Play

#### Controls
- **w** - Move up
- **a** - Move left
- **s** - Move down
- **d** - Move right
- **p** - Pick up item
- **i** - Show inventory
- **q** - Quit game

#### Objectives
1. Explore the map
2. Defeat enemies to gain experience
3. Collect items to survive
4. Find the exit (>) to progress to the next area
5. Survive as long as possible!

#### Key Elements

**Healing Elements:**
- ☀️ Solar Panels (S) - Restore HP
- 💧 Water (≈) - Small HP restore
- 🌿 Plants/Trees (♣♠) - Occasional HP restore
- 🌿 Healing Herbs - +20 HP

**Dangerous Elements:**
- ☢️ Radiation (~) - Take damage
- 👾 Enemies (E) - Combat occurs
- 🏚️ Ruins (%) - Exploration element

### 5. Tips

1. **Manage HP** - Heal at solar panels and water when low
2. **Level up** - Defeat enemies for experience
3. **Avoid radiation** - Stay away from radiation zones (~)
4. **Collect items** - Herbs and water are essential
5. **Explore carefully** - Sometimes avoiding enemies is better

### Troubleshooting

#### Jupyter Notebook won't start
```bash
# Reinstall Jupyter
pip install --upgrade jupyter notebook
```

#### Character display issues
- Set your terminal encoding to UTF-8
- Or use the English comments as reference

#### Errors occur
- Verify Python 3.7+ is installed
- Make sure to run all cells in order from top to bottom
