### 2012/04/27 Ver.2.0.0 (安定版)

 - アイテムの並べ方と我が家に関する変更と修正。
 - ペット維持計算処理の統合。
 - ユニーク・モンスター召喚で, 召喚に応じたユニークが足りなかった場合の埋め合わせ召喚の仕様を変更。
 - ペットのモンスターが変身しても親モンスターと名前を維持するように変更。
 - 鑑定に関する変更と修正。
 - モンスターのアイテム拾い/破壊の仕様変更。
 - 切り裂きの大鎌『ブラッディ・ムーン』に関する変更。
 - シンダリン銘を与えるコードをXAngbandより移植。
 - クエスト "湖の洞窟" を削除。
 - 自動拾いの各種説明を修正。
 - 死の大鎌に SLAY_HUMAN を追加。野蛮人、獣人も跳ね返りスレイの対象にした。
 - cast_meteor() を、壁の中には隕石を召喚しないように修正。
 - teleport系の行動ではプレイヤーはトラップの上に行かないように修正。
 - 無双三段の途中で壁にぶつかる等して中断した時、MPを消費するように修正。
 - 毒針を装備している時は必ず攻撃回数を1にするようにした。(乱れ雪月花で増えない)
 - 無双三段の時は毒針の命中率が1/2になるように修正。
 - ドラゴンスケイルメイルからエッセンスを抽出時に発動の充填時間がリセットされないように修正。
 - 必要エネルギーがマイナスになって無条件連続移動が発生する可能性をなくした。
 - windows版で、windowsを最大化したときに元のウィンドウサイズを保持するように変更。
 - windows版にマウスを使った画面コピーアンドペースト機能を追加。(Xangbandより)
 - 「`」キーで、指定した場所に自動移動するnethack風トラベルコマンドを実装。(Xangbandより)
 - 次元の扉などの場所指定で、「<」「>」で階段を指定できるように。(Xangbandより)
 - 画面が大きいときに、店や家のメニューが12個を超えて表示されるようにした。
 - '~'コマンドの既知のモンスターリストで、賞金首とアンバーの王族を選択表示。(変愚スレよりパッチ拝領)
 - 魔道具術師の取り込んだ魔法道具一覧をダンプするようにした。(So-Miyaさんのパッチ)
 - オプションメニューでカーソルを使用して項目を選択できるようにした。
 - キャラ生成時に自動装備。(Angband3.1.0より拝領)
 - 新職業スナイパー追加。
 - 新or移植アーティファクト。
 - 新領域「呪術」(ハイメイジ専用)
 - プレイ動画録画再生機能(']'キー)
 - ユニーク追加
 - 家と博物館の収蔵アイテム数を表示するようにした。(so-miyaさんより拝領)
 - 魔法の難易度を下げる能力に「易/Es」を刻むようにした。
 - あわせて、消費魔力減少をこれまでの「魔力/Ma」から「減/Dm」に変更。
 - 不可能な地形上での忍者の速駆け発動禁止。
 - 速駆けが終了した瞬間に、移動消費エネルギーが元に戻るよう設定。
 - バグ修正
     - 幻覚時のモンスター情報に関する各種バグ。
     - ペットのターゲット指定であやしい影の正体が判明するバグ。
     - モンスター写真のシンボル表示でデフォルト文字しか表示されないバグ。
     - エレメンタルvaultに生成されたモンスターやアイテムが溶岩の鉱脈などに埋もれるバグ
     - 孤立した部屋ができるバグのうちbuild_tunnel()の失敗によるもの
     - ランダムアーティファクトがロード時にランダムアーティファクトでなくなるバグ
     - 我が家やザックの詰替がうまくいかないバグ
     - 博物館のstack_force_notes, stack_fotce_costs判定の不整合によるバグ
     - ゲーム開始やフロア移動直後にペットの存在判定すぐにが更新されなかったバグ
     - モンスター格闘場でモンスターのテレポートを追尾できてしまうバグ
     - 変わり身かつ幻覚などの状態の忍者がダメージを全く受けない場合があるバグ。
     - 一定の処理で消滅する名前付きペットが正しい処理を経ないバグ。
     - アイテムのソート条件に関する修正。
     - 分解属性で回避の彫像や爆発のルーンが壊れなかったバグ。
     - 特定条件のフロア移動時に一時的に乗馬から降りたメッセージが出るバグ。
     - アイテムが増減する度にモンスター・ボールが不正に並べ替えられるバグ。
     - '%'メニューのファイル書き出しでデータが正しく書き出されなかったバグ
     - プレイヤーが死亡して次のプレイで名前を変えるとセーブファイルが新規作成されるバグ。
     - プレイヤー名入力時Enterで空文字列を入力すると名無しになるバグ
     - ヘルプの検索や強調で空の文字列を入力した場合にフリーズするバグ
     - 英語版のフォント設定で日本語フォントを指定すると次回に設定が反映されていなかった。
     - 魔法を唱える事が出来ない条件下で連続魔が使えてしまう。
     - いくつかのアイテムの発動などで恐怖状態が解除されない。
     - 闘技場に入ったときに魔法の鎧が消えないバグ。
     - 守護魔神の抹殺系報酬時のメッセージバグ
     - アンドロイドで最後の1服の油つぼを服用した際に腹が満たされないバグ。
     - 視界の狭いモンスターに、losトリックを使うと特定軌道で反撃がこないバグ
     - 誤簡易鑑定が装備警告に反映されないので修正。(討論スレ8 877さんのパッチ)
     - 剣術家の魔神斬りが当たらないバグを仕様を変更して修正。
     - 中継送信側のウィンドウサイズが大きくても、受信側が落ちない修正。()
     - 呪術で途中で解呪しても影のクロークの効果が消えないバグ。
     - 光速移動中は探索中であっても表示上の速度を+10しないように修正。
     - 光速移動の状態で広域マップに入ると効果が切れるように修正。
     - 割引価格の魔法棒の回数が過充填されないように修正。
     - 重量0のアイテムをサブウィンドウ表示した時に重量の表示が消えるのを修正。
     - 食事として杖や魔法棒を食べた時にサブウィンドウの表示が更新されるように修正。
     - 薬の最後の1服を飲んだ時、徳・満腹度が正しく増減されない不具合。
     - 性格選択時の配列外参照を修正。
