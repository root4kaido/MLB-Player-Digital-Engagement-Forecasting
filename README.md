# MLB-Player-Digital-Engagement-Forecasting

- 01…baseline
- 02…baseline2
- 03…lag特徴量
- 04…特徴量追加
- 05…特徴量追加2
- 06…lag+lgbm
- 07…CV考える→プレイヤーごと
- 08…CV考える→sliding window
- 09…target自分で統計量出す
- 10…target公開notebookの統計量使う
- 11…09と10の合わせ技
- 12…tsfresh使ってみる
- 13…targetの統計量を，どの期間使えばいいかいろいろ試した
- 14…validationをちゃんとやる
- 15…3月もtargetの統計量に加える
- 16…試合してからの日数を加える
- 17…16にミスがあったので，なおした
- 18…シーズンONだけにしぼる
- 19…playerを，testで使われるものだけに絞る→なぜかだめだった
- 20…3月もtargetの統計量に加える
- 21…相関係数も含める
- 22…optuna
- 23…22で実験，なぜかだめ
- 24…pre,postseasonとかにフラグ
- 25…twitterも含める
- 26…optuna(sklearnバージョン)
