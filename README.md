# ゲーム のタイトル
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
簡易版マリオとRPG要素を足したゲーム
・敵を倒すと「コイン」と「スコア」が出る。種類によって固定
・ステージの作成（障害物の地形など）
・「コイン」を消費して、「レベル」や「能力」を獲得できる。
・最終スコアを高いことを目指す。（残り秒数＋「スコア」

## ゲームの実装
###共通基本機能
* 主人公キャラクターに関するクラス
* 画面推移機能に関する機能
* フィールドに関するクラス
### 担当追加機能
<<<<<<< HEAD
* コインに関する機能
* 能力に関する機能
* スコアに関する機能
* ゴールの設置
* 説明コメントの追加
* 即死ブロックの追加
=======
* スコアとレベル機能(担当：陶山)：スコアは敵を倒したときに得られるポイント。レベルは敵を倒したときに別で得られる経験値でのバーでの表示とレベル表記。
* スキル機能とスキルアイコンの表示機能(担当：陶山)：スキルによる能力の発動とレベルに合わせてスキルの解放とアイコンの表示の機能。
>>>>>>> C0A22089/skill
### ToDo
- [ ] 
### メモ
* 許可を与えるbool値の変数はMV_で始める
* 判定,if文などにはほぼすべて説明コメントを追加する
* 後からランダムで出現するオブジェクトは画面外で生成を行う
