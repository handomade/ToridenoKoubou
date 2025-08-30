# Toride no Koubou (Fortress Battle)

**砦の攻防** (*Toride no Koubou*, Fortress Battle) は、*マイコンBASICマガジン* で多数のハードに移植されたストラテジック・シミュレーション・ゲームです。  
オリジナルは大高 準一郎氏によるPC-8801シリーズ向けで、1989年5月号に掲載されました。  
各ハードに移植されたものは、大幅なアレンジが施されたものもありました。  
本SymbOS版はPC-8801版を参考に、ゲームバランスの調整や一人プレイモードの追加など、アレンジを加えて移植したものです。

*Fortress Battle* is a strategic simulation game ported to numerous platforms in *Microcomputer BASIC Magazine*.  
The original version was developed by Junichiro Ohtaka for the PC-8801 series and published in the May 1989 issue.  
Some ports featured significant modifications.  
This SymbOS version is primarily based on the PC-8801 version, with adjustments to game balance and the addition of a single-player mode.

## 遊び方 / How to Play

タイトル画面で、画面下のmode欄に「1」を入力（デフォルト設定）してSTARTボタンを押すと一人プレイモード、「2」を入力すると二人プレイモードで遊べます。  
ランダムに生成された地形と、BLUEの砦、PINKの砦が描画されます。  
BLUEは1PLAYER、PINKはコンピュータまたは2PLAYERが操作します。  
角度と速度を入力し、FIRE!ボタンで攻撃します。  
両プレイヤーとも、敵側が0度、真上が90度です。  
風向きは攻撃ごとにランダムで変化します。  
3ポイント（相手の砦を3回破壊）を先に獲得した方が勝利です。

At the title screen, enter "1" in the mode field (default setting) and press the START button for single-player mode, or enter "2" for two-player mode.  
A randomly generated terrain with BLUE and PINK fortresses will be displayed.  
BLUE is controlled by Player 1, while PINK is controlled by the computer or Player 2.  
Enter the angle and velocity, then press the FIRE! button to attack.  
For both sides, 0 degrees is directly facing the enemy, and 90 degrees is straight up.  
Wind has a significant impact, and its direction changes randomly with each attack.  
The first to score 3 points (destroying the opponent's fortress 3 times) wins.

## 更新履歴 / History

### 2025/8/30 ... ver1.0
- 弾丸が点ではなく線で描画されるようになり、速度があっても地形や砦を貫通することがなくなりました。  
- 砦の位置がランダムで多少変わるようになりました。  
- ランダムで壁が生成されることがあります。  
- 敵のAIがランダムで撃つだけではなくなりました（ただし、まだ賢くはありません）。  
- 砦が大きくなりました。  

- Bullets are now drawn as lines instead of dots, and they no longer pass through terrain or forts regardless of speed.  
- The position of forts now varies slightly at random.  
- Walls may now be randomly generated.  
- Enemy AI no longer just shoots randomly (though it's still pretty dumb).  
- The fort has become larger.

### 2025/8/29 ... ver0.1
- 初期リリース / Initial release.

## クレジット / Credits
- オリジナル / Original: 大高 準一郎 (Junichiro Ohtaka), 1989  
- SymbOS版 / SymbOS Port: 反動のゲームちゃんねる (Hando), 2025
