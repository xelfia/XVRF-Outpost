<img src="../image/xvrf-title-icon.png"/> May the XVRF with you

[🔙](../README.md) | `取扱説明書` | [`操作方法`](controls.md) | [`更新履歴`](history.md) | [`デバッグツール`](debug.md) | `English (N/A)` | `Japanese`

----

# XVRF（仮称） | 取扱説明書（仮）

* 本ソフトウェアはゲームの形態ですが、まだその開発中のプロトタイプ（アーリーアクセス）とお考えください。
* お気に入りのVRMキャラクターが動き回るアプリのつもりで、お楽しみいただければ幸いです。
* 可能であれば随時、本作および説明を更新していきます。

# 💻推奨動作環境

|||
|----|----|
|オペレーティングシステム|Windows 10 64-bit|
|ビデオ|DirectX 11以降|
|メモリ|4GB RAM|
|ストレージ|25GB以上の空き容量|
|ブロードバンドインターネット接続|✅|

> あくまで参考としての情報です。

# 起動方法

1. zipファイルをすべて展開する。（ダウンロードした後の初回）
2. 展開したフォルダの`XVRF.exe`を開く。

> * オペレーティングシステム`Windows 10`やセキュリティ対策ソフトウェアによる保護の動作に対しては、一般的な手順に従ってお願いいたします。
> * 更新版は改めてダウンロードし、同じ手順で起動してください🙇

## 有効期限について / About `Expilation`

* 「アーリーアクセス版」として、バージョン毎に有効期限を設定をしています。
* 画面下部にある有効期限`Expilation`を迎えると、そのバージョンの利用期間は終了となります。有効期限以降に起動すると`Expired on`の句を含んだメッセージが表示されます。XVRFダウンロードサイトに最新版がないか探してみてください。

> * 表示はUTC(協定世界時)です。
> * 先々の有効期限の扱いは未定です。

# 🏠ロビー / `🏠Lobby`

* ゲームを起動すると、まもなくしてロビー`🏠Lobby`が表示されます。
 
> ここで説明する絵文字とゲーム内アイコンでは、見た目が異なることにご注意ください。

|||
|---|---|
|`👤🆚🤖`| 一人プレイ（プレイヤー対AI）を開始します。|
|`🤖🆚🤖`| AI対AIの対戦デモを開始します。|
|`Enable to start from URL`|この機能を有効化すると、 https://xelfia.github.io/XVRF-Outpost/ のページにある`▶️XVRF`のリンクから、あなたのWindowsにあるXVRFが起動できるようになります。通常はWindowsによるセキュリティの確認があります。進めた場合、XVRFをもう1つ起動して（Unityロゴが出て）、まもなく閉じます。もとのゲーム内で`Succeeded`が表示されれば、有効化に成功しています。|
|`👤Character Selection`| キャラクター選択画面に移動します。（後述）|
|`Discord`|（仮設置です。今後解説を検討）|
|`Web`| [暫定公式サイト](../README.md)を開きます。|
|`📜Report`| ソフトウェアの動作に関する報告フォームです。内容に問題なければ`Send`で送信できます。これが利用できない場合は、ほかの連絡方法でお知らせください。|
|`⚙Settings`|設定画面を開きます。（後述）|
|`Quit`|ゲームを終了します。（確認あり）|

# ⚙設定 / `⚙Settings`

|||
|---|---|
|`Audio`|スライダーで全体の音量を調節できます。|
|`Music`|スライダーで音楽の音量を調節できます。|
|`Sound Effect`|スライダーで効果音の音量を調節できます。|
|`AI Level`|AIの腕前を調節できます。現在のところ単純に防御行動の割合に関与します。|
|`Active Camera`|☑のとき、カメラが被写体に合わせて動き回ります。|
|`Debug Tools`|☑のとき、デバッグツール関連のUIが表示されます。（後述）|
|`Move by Mouse`|☑のとき、マウスポインタの相対移動が、移動入力（ゲームパッド🎮の左スティック相当）に対応します。|
|`Back`|前の画面に戻ります。|

> * 設定は操作した時点で保存されます。

# エスケープメニュー / `Escape Menu`

`👤🆚🤖`（一人プレイ）の戦闘画面において、🔙操作をすると、エスケープメニューが表示されます。

|||
|---|---|
|`Continue▶`|戦闘画面に戻って続行します。|
|||
|`AI Level`|AIの腕前を調節できます。現在のところ単純に防御行動の割合に関与します。|
|`👤Character Selection`|キャラクター選択を開きます。|
|`🏠Lobby`|ロビーに戻ります。|

> * 現在のところ、戦闘は一時停止しません。

# デバッグツール

VRM作者などのクリエイティブな方に、効果的に活用していただけるような機能を入れています。

☛ `English (N/A)` [`Japanese`](debug.md)

# キャラクターの選択方法 / `👤Character Selection`

* 同梱キャラクターは、1キャラクターです。 `参考` ☛ [`VRoid Hub` ᚡᛆᛚᚴᚤᚱᛄᛆ](https://hub.vroid.com/characters/5500341240985797385/)

> 同梱状態は変更される可能性もあります。

* そのほかのキャラクターは、後述の方法で利用可能です。

> 同梱以外のキャラクターについては、想定外の挙動が起きることがあります。
[VRoid Studio](https://studio.vroid.com/)の標準的デザインのキャラクターはそれなりに動作します。
どんなキャラクターがいい動作をするか、世界に合いそうか、あるいはおかしな、面白い動作をするでしょうか。
よろしければ、ぜひあなたの体験をソーシャルメディアなどで共有してください☺

## `👤Character Selection`画面の操作方法

|||
|---|---|
|`P1`|☑のとき、キャラクターを選択後、プレイヤー1`P1`（またはAI1`A1`）に適用します。|
|`P2`|☑のとき、キャラクターを選択後、プレイヤー2`P2`（またはAI2`A2`）に適用します。|
|`Select VRM`|ここに選択したキャラクターのモデル名が表示されます。|
|`Author`|ここに選択したキャラクターの作者名が表示されます。|
|`Back`|前の画面に戻ります。|
|`Open Folder`|ローカルVRMフォルダ📁を開きます。（後述）|
|`⟳`|キャラクターモデルのリストをリロード（再読み込み）します。|
|`⚙`|「VRoid Hub」連携`Link`または連係解除`Unlink`ができます。（後述）|
|`Local`|ローカルのVRMファイルを有効/無効にする（後述）|
|`VRoid Hub`|あなたの`VRoid Hub`のキャラクターモデルの有効/無効（後述）|
|`VRoid Hub💛`|お気に入りの`VRoid Hub`のキャラクターモデルの有効/無効（後述）|
|`VRoid Hub★`|おすすめ`VRoid Hub`のキャラクターモデルの有効/無効（後述）|
|`Back`|前の画面に戻ります。|

> * `VRoid Hub連携`をしていない状態で、`VRoid Hub`関連の操作をした場合、`⚙`と同様に`VRoid Hub連携`の画面になります。
> * おすすめキャラクターモデルはゲーム側で固定されており、予告なく変更されることがあります。

## キャラクターの選択方法

* まず`P1`と`P2`の☑または☐の状態を確認（設定）しておいてください。
* 画面最下部のフィルタに応じて、画面下部にキャラクターモデルのアイコンが表示されます。

> * 該当がない場合、空欄になります。
> * 「🛇」が表示されている場合、利用条件が適合しないため使用できません。

* キャラクターモデルのアイコンを1度選択すると、選択状態になり、その詳細情報が画面に表示されます。
* キャラクターモデルのアイコンの選択状態で、もう一度選択すると、そのキャラクターの使用が決定になります。
* しばらくするとロード`Loading...`が終わり、戦闘が始まります。

> * XVRFと選択したキャラクターモデルとの相性に何か問題がある場合には、`Loading...`の途中または終了後に、通常と異なる挙動が起きる可能性があります。
> * 新たな発見である可能性があれば、お知らせください☺

## VRoid Hubと連携する

1. ゲーム内`👤Character Selection`の`⚙`を押します。
2. 自動的にウェブブラウザが開いて、`VRoid Hub`認可コードが表示されます。
3. ページ内の認可コードを`コピー`します。
4. ゲーム画面に認可コードが自動的に貼り付けされます。

> もし、認可コードが入力できない場合、仕様変更などの可能性があるので、当方(XVRF側)にお問い合わせください。

5. 認可コードが貼り付けが確認できたら、`Link`を押して連携します。
6. 成功`Succeeded`なら次へ進みます。

> 失敗`Failed. Please retry.`の場合、入力内容/通信状態/サービス稼働状態などを確認して、再挑戦してみてください。

## VRoid Hubキャラクターモデルで遊ぶ

1. 連携後、[VRoid Hub](https://hub.vroid.com)でお気に入りキャラクターを探してみましょう。
2. ページ内の「♡」を押してみましょう。（XVRFでは、利用条件が`暴力表現OK`のキャラクターに限ります）
3. ゲーム内`👤Character Selection`の`VRoid Hub💛`を押して、☑にします。
4. きっとキャラクターが見つかり、遊ぶことができます。

## VRoid Hubにあるあなたのキャラクターモデルで遊ぶ

1. 連携後、ゲーム内`👤Character Selection`の`VRoid Hub`を押して、☑にします。
2. きっとキャラクターが見つかり、遊ぶことができます。

> * XVRFでは、利用条件が`暴力表現OK`のキャラクターに限ります。
> * もし、同梱または標準的なものと比較して動作が良くない場合、以下を参考にしていただければ幸いです。
> ☛ [XVRF Model Definitions / XVRFで良く動くVRMのために](https://scrapbox.io/XVRF/XVRF_Model_Definitions_%2F_XVRF%E3%81%A7%E8%89%AF%E3%81%8F%E5%8B%95%E3%81%8FVRM%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AB)

## ローカルのVRMファイルで遊ぶ

自作や条件を満たしたVRMファイルを利用することもできます。

> ☛ [VRMとは](https://vrm-consortium.org/#vrm)

1. `👤Character Selection`画面の`Open Folder`（フォルダ📁を開く）から、以下の形式のフォルダ📁を開く。
  * `≪ドライブ名≫:\Users\≪ユーザー名≫\Documents\VRM`
2. このフォルダ📁にVRMファイル (`.vrm`形式)をおいてください。
3. ゲーム内`Character Selection`画面の`Local`（ローカル）を押して、☑にします。
4. きっとキャラクターが見つかり、遊ぶことができます。

> * XVRFでは、利用条件が`暴力表現OK`のキャラクターに限ります。
> * もし、同梱または標準的なものと比較して動作が良くない場合、以下を参考にしていただければ幸いです。
> ☛ [XVRF Model Definitions / XVRFで良く動くVRMのために](https://scrapbox.io/XVRF/XVRF_Model_Definitions_%2F_XVRF%E3%81%A7%E8%89%AF%E3%81%8F%E5%8B%95%E3%81%8FVRM%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AB)

## ⚠既知の問題 / Known Issues

* 戦闘のバランスやアニメーションはプロトタイプ相当です。
* AIの挙動は前述を追う形で、段階的な対応となる見込みです。
* キャラクターの体格などの違いによる制限や調整は、現在のところ行っていません。たくさんの情報をお待ちしています。
* 建設的なフィードバック、ツイート（リツイートや返信含む）、ゲームプレイ配信などは歓迎します。
* 戦闘においては🎮ゲームパッドを推奨していますが、メニューは🖱マウスでの操作を暫定的におすすめします。素直に操作できない部分が多くあるためです。
* 動作パフォーマンスの調整などを行っていません。前述`💻推奨動作環境`と比べても、相応の動作環境で問題があれば、お知らせください。
* `[Esc]`操作の応答が不安定なことがあります。
* キャラクター選択のフィルタのトグルと反映が不完全のようです。
* キャラクター選択のキャラクターモデルリストの順序が不確かです。
* `Active Camera`がときどき不安定です。
* 🎮ゲームパッドでメニュー操作ができなくなることや、メニュー移動がわかりにくいことがあります。
  * 画面遷移でUIフォーカスが外れたり、移動先が想像しにくいことがあります。

## ✒更新履歴 / Update Logs

バージョンの違いなどについては以下をご覧ください。

☛ `English (N/A)` | [`Japanese`](history.md)

## 🎮操作方法と入力デバイス

戦闘やメニューでの操作と、入力デバイスの割り当てなどは以下を合わせてご覧ください。

☛ [`English`](../controls.md) | [`Japanese`](controls.md)

## 📧情報共有 / 連絡先

* 推奨Twitterハッシュタグ（仮）: `#XVRF`

* [xelfia@twitter.com](https://twitter.com/xelfia)

* 最新版 XVRF ダウンロードサイト: https://xelf.booth.pm/items/1341365
* [ライセンス表示](../LICENSE.md)

--------
🆇🅴🅻🅵
©2018-2019 XELF