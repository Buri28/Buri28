## Beat Saber向けのMODを作成中です。 
多少長くやっているビーセイプレイヤーとして、こんな機能があったらというMODを作っていこうと思います。  
おそらくマニア向けなものとなります。  
※ AIが優秀過ぎて最近の開発はAI中心です。問題がないことは念入りに確認しています。  
　 (プログラミング歴は30年程、メイン言語はJava/オブジェクト指向)

#### 自作の台形カスタムノーツ：　[ファイル置き場](https://drive.google.com/drive/folders/1Vje74lBUID59DsR94PKk1jh5kLaETXBp)  　[Xの紹介記事](https://x.com/Buri_Resawa/status/1701996905163898890)  

## 開発中のツールやMOD

| ツールやMOD | 区分 | 概要 | バージョン | 動作確認バージョン |
| --- | --- | --- | --- | --- |
| [MyBeatSaberStats](https://github.com/Buri28/MyBeatSaberStats) | ツール<br>(Python)　 | 譜面の消化状況、PPやランクなどをスナップショットとして保存し、デスクトップから閲覧するためのアプリ | 0.8.4 (β) | Win11 |
| [quest-vd-wired-watchdog](https://github.com/Buri28/quest-vd-wired-watchdog) | ツール<br>(PowerShell)　 | QuestやPCの再起動によってQuest VD Wiredの接続が切れても、復旧し繋げ直す常駐スクリプト<br>（QuestでVirtualDesktopに有線接続する人向け） | v1.1 | Win11 |
| [MapMemo](https://github.com/Buri28/MapMemo) | MOD<br>(C#) | マップごとにローカルメモを残すMOD | v1.2.0 | BS 1.39.1 / 1.40.8 / 1.42.3 |
| [LRCounter](https://github.com/Buri28/LRCounter) | MOD<br>(C#) | 左右の精度とPPを表示するカウンター<br>(右手と左手の精度が違いすぎる人向け）<br>※左右のサウンドにも対応 | v0.3.1 | BS 1.39.1 / 1.40.8 |
| [WallHitSound](https://github.com/Buri28/WallHitSound) | MOD<br>(C#) | 壁に衝突したときに音を鳴らすMOD<br> ※衝突時のエフェクト機能もあり | v1.1.0 | BS 1.39.1 / 1.40.8 |
| [WallHitCounter](https://github.com/Buri28/WallHitCounter) | MOD<br>(C#) | 壁とボムの衝突回数を表示するCountersPlusのシンプルなカスタムカウンター | v1.0.0 | BS 1.39.1 / 1.40.8 |
| [HazardTimer](https://github.com/Buri28/HazardTimer) | MOD<br>(C#) | リプレイファイルをもとに、衝突した壁やフェイル地点に近づくとカウントダウンするMOD | v0.1.0 | BS 1.39.1 / 1.40.8 |
| [ModMemoryProfiler](https://github.com/Buri28/ModMemoryProfiler) | MOD<br>(C#) | MODのメモリプロファイラ | 試作段階<br>(製作者環境のリーク調査中) | BS 1.39.1 / 1.40.8 |
| [SkyLight](https://github.com/Buri28/SkyLight) | MOD<br>(C#) | 既存Environment（環境）の背景や構造物の色を変更したり非表示にするMOD <br>※今のところリリースする予定はありません。<br>(完成度が上がったら考えます) | 試作段階<br>(リリース予定なし) | BS 1.40.8 |

※案だしレベルで検討中  
・リプレイ解析ツール：BeatLeaderのリプレイからフォアハンドとバックハンドに分けて解析  
・ジャンプ練習譜面生成ツール(1段階目)  ：ツールからジャンプ配置だけの譜面作成  
・ジャンプ練習MOD(2段階目)：MODからジャンプ配置だけの譜面作成。  
　捻じれ具合や軌道の再現性、フォアとバックの切る位置の差などで得点を出したい  
・振りのフォームや姿勢を強制するMOD：コントローラの位置や捻じれから肘の位置などを出す  
・体重・運動量・睡眠時間管理ツール(ビーセイじゃないけど)
<!--
**Buri28/Buri28** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
