---
title: ハードウェアウォレットCOLDCARDで大事なビットコインを守ろう【番外編】
taxonomy:
    category:
        - how-to
        - wallet
    post_tag:
        - beginner
---

## COLDCARD 初心者向けガイド

<div><button class="zap-button" data-npub="npub1uyf6ghmjy8p8mnt8jhutgh4jtjvzn7euwjf4yvpwuzwan5jl8xysnvsmuw" data-relays="wss://relay.damus.io,wss://relay.snort.social,wss://nostr.wine,wss://relay.nostr.band">Zap Me ⚡</button><a href="https://twitter.com/katakoto">@katakoto</a></div>

|  ![Category](/_images/category.png)  |  ハウツー、ビットコインを安全に管理するには |  ![Tag](/_images/tag.png)  |  初級  | ![Time](/_images/timer.png)  |  5分  |
| ---- | ---- | ---- | ---- | ---- | ---- |

*本記事は [Coldcard 公式サイト](https://coldcard.com/)「[Guide For Bitcoin Beginners](https://coldcard.com/docs/beginner)」を [@katakoto](https://twitter.com/katakoto)が翻訳、一部加筆修正したものです。*


### イントロダクション

[ビットコイン](https://lostinbitcoin.sakuraweb.com/glossary/bitcoin/)は、進化のペースが速く広大なコミュニティです。

とりわけ初めて暗号通貨を使う際には、常に何か新しいことが出てきたり、理解し難い専門用語の羅列に出会ったりすることがあります。

でも、心配しないで大丈夫。あなたは今、正しい場所にいます。

[Coldcard](https://coldcard.com/)は、セキュリティの面で最高の製品であり、**非常にたくさん**の機能を備えています！あまりに多くの先進的なトピックやセキュリティ機能があるため、ビットコイン初心者には、時に混乱したり近寄りがたく感じてしまうかもしれません。

Coldcardには、たくさんの高度なセキュリティ機能がありますが、それらは全て追加的なものです。基本的なことからスタートして、自分の[ウォレット](https://lostinbitcoin.sakuraweb.com/glossary/wallet/)をあなたと共に成長させることができます。もうセキュリティの必要性に応じて、新たな[ハードウェア・ウォレット](https://lostinbitcoin.sakuraweb.com/glossary/hardware_wallet/)を買い続ける必要はないのです！

このガイドは、Coldcardの基本機能を紹介し、あなたの知識をそこから広げていくためのものです。


### ウォレットって何？

ハードウェア・ウォレットとしても知られるColdcardは、あなたのビットコインを安全に保管するための優れた方法です。インターネットに接続した[ソフトウェア・ウォレット](https://coldcard.com/docs/glossary#software-wallet)は、本来決して知られるべきではない[シードフレーズ](https://coldcard.com/docs/glossary#seed-words)と、それに紐付く[秘密鍵](https://lostinbitcoin.sakuraweb.com/glossary/private_key/)を保管するために作られています。

Coldcardは、ソフトウェア・ウォレットと連動してあなたのビットコインを安全に保管します。ソフトウェア・ウォレットは、全ての[トランザクション](https://lostinbitcoin.sakuraweb.com/glossary/transaction/)を表示したり、あなたのウォレットにビットコインを送るための[アドレス](https://lostinbitcoin.sakuraweb.com/glossary/address/)を作成したり、あなたのウォレットから他の人にビットコインを送るためのトランザクションを作成するためのツールです。

ソフトウェア・ウォレットがColdcardと連帯する際には、送信される各トランザクションにColdcardによる「署名」が必須となります。トランザクションへの「署名」は、ウォレットに関連付けられたColdcardへアクセスできる人だけが行うことができます。

[対応ウォレットのページ](https://coldcard.com/docs/compatible-wallets)では、いくつかの選択肢をご紹介しています。


### シードフレーズはとても大切

あなたの[シード](https://lostinbitcoin.sakuraweb.com/glossary/seed/)フレーズは、他人から知られないようにすべき最も大切な情報です。もしあなたのシードフレーズが他人の手に渡ってしまったなら、彼らはいとも簡単にあなたの全てのビットコインを盗み出してしまえます。


### Coldcardのセットアップ

COLDCARDのセットアップは非常に簡単で、[こちら](https://coldcard.com/docs/quick)のクイックスタート・ガイドに従うだけです！このガイドは開封からCOLDCARDのセットアップを手助けします。不正開封を防止する袋の開封から、資金の受け取り、送金方法までを網羅しています。

よりシンプルにしたバージョンのガイドは[こちら](https://www.notion.so/6fcf6cb3d25a49aa898c8d109ddec171)です。


### COLDCARDでビットコインを安全に保管する方法

Coldcardは、マーケットにおいてビットコインを保護するための最も高度なセキュリティを手に入れられる製品としてよく知られています。あなたのウォレットに適用できるセキュリティの層は非常に多くあり、そうしたオプションを知ることは難しいかもしれません。

以下は、Coldcardを利用して、ビットコインを安全に管理するための２つの主な方法です。


### USB経由で利用する

トランザクションに署名するために、USB経由でColdcardを利用するのが、最もわかりやすくて簡単な方法です。[ElectrumでColdcardをセットアップ](https://coldcard.com/docs/quick#using-with-electrum-via-usb)すれば、毎日のあらゆる送金トランザクションに署名するのもとっても簡単です！


#### Electrumと一緒にUSB経由で利用する

- Electrumのバージョン3.2.3以降の全バージョンにはColdcardへのサポートが内蔵されています。
- 最新バージョンを[ここからダウンロード](https://electrum.org/#download)して、[PGP署名](https://coldcard.com/docs/glossary#pgp-signature)にて検証しましょう。
- ファイルメニューから**「New/Restore」**を選択。
- ファイルネームを選びます。
- **「Standard Wallet」**を選択。
- **「Use a hardware device　(ハードウェアデバイスを使う)」**を選択。
- 表示されたColdcardデバイスを選択。
- アドレスフォーマットを[Segwit](https://coldcard.com/docs/glossary#segwit)かClassic/Legacyから選ぶ。

ポイント：Segwitアドレスは、BTCを送る際のトランザクション手数料を下げるのに役立ちます。

- その他のあらゆるUSBハードウェア・ウォレットのように利用可能です。


#### Coldcardをオフラインで利用する（Electrum4.0.3連携によるエアギャップ方式とMicroSDを利用)

Coldcardをオフラインで利用すると、あなたの資金を可能な限り安全に保管できるためおすすめです。利用開始のプロセスと、トランザクションの作成は少しだけ面倒にはなりますが、私達の意見では、その価値は十分にあると考えています。

この方法は、シードフレーズ（Coldcard内に保存）とインターネットに接続されたデバイス/コンピュータが、直接に接続されることがないため、「エアギャップ・トランザクション」と呼ばれます。

Coldcardを直接インターネットに接続されたコンピュータに接続する代わりに、あらゆる重要な情報（シードフレーズ）をオフラインに保ち、ハッカーたちがアクセスできないようにする方法です。この方法には[Coldcard](https://store.coinkite.com/store/coldcard)と[MicroSD](https://store.coinkite.com/store/microsd-cc)が必要になります。

エアギャップ方式は、Coldcardからスケルトン・ウォレット（ウォッチ・オンリー・ウォレット）をMicroSDにコピーし、お使いのソフトウェアウォレットにエクスポートする仕組みです。この方法は、スケルトン・ウォレットはシードフレーズを含まないためUSB方式よりも安全です。スケルトン・ウォレットには、トランザクションを確認したり、ビットコインを受け取るためのアドレスを作成したり、[PSBT](https://coldcard.com/docs/glossary#psbt)を作成するのに最低限の情報しか含まれていないのです。

Coldcardが送信されるトランザクションに「署名」しない限り、ソフトウェア・ウォレットがあなたのビットコインを利用することはできません。ウォレットからビットコインを実際に利用するには、MicroSDに保存されたPSBT（部分的に署名されたビットコイン・トランザクション）ファイルを読み込み、Coldcardを利用してそれに「署名」する必要があります。


**下記の手順に従ってください。（また[クイックスタート・ガイド](https://coldcard.com/docs/quick#ready-to-sign)もご覧ください。）**

- 小容量で安全品質なMicroSDを確保する。
- Coldcardにて**「Advanced」 > 「MicroSD Card」 > 「Export Wallet」 > 「Electrum Wallet」**と選択。
- このように警告メッセージを確認し承認する。

```
This saves a skeleton Electrum wallet file onto the MicroSD card. You can then open that file in Electrum without ever connecting this Coldcard to a computer.
Choose an address type for the wallet on the next screen.

Press 1 to enter a non-zero account number.

The file created is sensitive--in terms of privacy--but should not compromise your funds directly.

MicroSDカードにElectrumのスケルトンウォレットファイルが保存されます。このファイルは、Coldcardをコンピュータに接続することなく、Electrumで開くことができます。
次の画面でウォレットのアドレスの種類を選択します。

1を押して、0以外のアカウント番号を入力してください。

作成されるファイルは、プライバシーの観点から機密性の高いものですが、あなたの資金を直接危険にさらすものではありません。
```

- 新しいファイル、new-wallet.jsonがMicroSDに書き込まれます。
- MicroSDカードを取り出し、Electrumが動作しているコンピュータに挿入します。
- この際、ElectrumクライアントでColdcardプラグインが有効になっている必要があります。
- ウォレットファイルを開き、同期が完了するのを待ちます。
- ウォレットファイルは、コンピュータの別の場所に保存しておくとよいでしょう。

[動画 ElectrumでCOLDCARDをセットアップする方法](https://www.youtube.com/watch?v=u5jRJ8L1Vwo&list=PLZKkuPrgFw0axLoDDzxAIYzpZeC_T1i7W&index=7)


### このウォレットから送金する場合

- Electrumでウォレットを開きます。
- 通常通り、新しいトランザクションをセットアップします。
- **「Finalize transaction」**を選択し、**「Export」 > 「For hardware device; include xpubs」> 「Export to file」**を選択します。
- (最上段の「Export to file」オプションは選択しないでください：生成されるPSBTファイルは互換性がありません)。
- この時点で、PSBTファイルをMicroSDカードに直接保存することができます。
- ファイル名にはトランザクションの説明、もしくは日付を含む短いファイル名を使用し、末尾は .PSBTである必要があります。
- MicroSDカードをColdcardに移動します。
- Coldcard のメインメニューから 「Ready to Sign」を選択します。
- 作成したPSBT ファイルを一覧から選択します。 (カードに複数のファイルがある場合)
- トランザクションを[承認](https://lostinbitcoin.sakuraweb.com/glossary/confirmation/)します。
- 作成されたトランザクションはMicroSDカードに保存され、同じファイル名に新しい末尾（-final.txn）が付けられます。
- Electrumまたはパブリックサービスを使って、そのファイルから16進エンコードされたトランザクションをプッシュします。
- 例えば、Electrumの場合、「Tools」→「Load transaction」→「From File」を選択します。

[動画 COLDCARDとElectrumでPSBTトランザクションをエアギャップで署名する方法](https://www.youtube.com/watch?v=fNZgVHq0FGM)


#### 変更される可能性あり

Electrumは、オープンソースのプロジェクトであり、常に変化しています。これらの手順が古くなっている場合は、お知らせください。


### 簡易版 COLDCARD セットアップ・ガイド


#### 梱包袋について

あなたのColdcardは、特別な袋に密封されて到着しているはずです。大きなCoinkiteのロゴ、緑色の文字、青色の縁取り、そしてその下に番号の付いたバーコードが印字されています。この番号は重要で、私たちはこれを「バッグナンバー」と読んでいます。Coinkiteの工場では、この番号をあなたのColdcard内のフラッシュメモリの安全な領域に記録していますので、この番号をメモしておいてください。

袋を開封する前に、袋にダメージが無いか、以前に開封された形跡がないか、点検してください。上部のシールを引き剥がすと「VOID」（無効）という文字が表示されるようになっています。

この袋の目的、および固有の番号は、Coldcard が工場から直接出荷されたものであり、お客様が作業を開始する前に誰かに変更されたものではないという確信を与えるためのものです。

何か異常が見つかった場合は、次の連絡先まで写真を添付の上ご連絡ください。

[support@coinkite.com](mailto:support@coinkite.com)

これはあくまで数あるセキュリティ層のひとつに過ぎません。そして、ビニールの袋は鋭利なナイフなどによって「ハッキング」される可能性があることがわかっています。これは情報セキュリティにおける「多層防御」戦略の一例です。


##### 不正開封防止袋 (バージョン2)

袋の内側に、シリアルナンバー入りの一片が同封されています。この一片を使って、袋の横幅を再確認してください。また虫眼鏡を使って、一片のミシン目が袋と一致しているのを確認することもできます。袋の底に、つなぎ目がないのを確認することも重要です。

![](/_images/cc_beginner_guide1.png)


#### 電源オン

上部にあるUSBポートを使用して、Coldcardに電源を接続します。すでにお持ちのMicro USBケーブルが使用可能です。（※Mk4はUSB-Cケーブルが必要）USBをコンピュータに接続することもできますが、この段階では、壁掛け充電器やUSBパワーパックを使用することもできます。電力が必要なだけでデータは必要ないからです。


#### 販売条件

最初に表示される画面はこのようなものです。

![](/_images/cc_beginner_guide2.png)

画面の右端をよく見ると、小さなスクロールバーと下向きの矢印があるのがわかります。5キーと8キーを使って上下に移動し、メッセージの全文を見ることができます。

規約の全文は[こちら](https://coinkite.com/terms)でご覧になれます。OKキー(✔)を押して、規約に同意し、次に進みます。


#### イニシャルPIN

ビットコイン・シードフレーズが生成される前に、最初のPINを選択する必要があります。これは、あなたが近くにいない時に、不特定の人々があなたの Coldcard を使おうとする事態への主な防御方法です。ぜひ効果的なPINコードを選択してください。

![](/_images/cc_beginner_guide3.png)

Coldcardでは、PINは以下の例のように2つの部分から成ります。

```
12-34
1234-5678
872323-39843
12-345678
```

最初の部分はプレフィックス（1234-）、2番目の部分はサフィックス（-4567）と呼ばれます。それぞれの部分は2桁から6桁の数字でなければなりません。プリフィックスは、ログインするたびに表示される[アンチフィッシング](https://coldcard.com/docs/glossary#anti-phishing)防止のための単語を決定します。


#### PIN プレフィックス

PIN プレフィックス (PINの最初の部分) によって、フィッシング防止のための単語が決まります。アンチフィッシング防止のための単語は、Coldcard が危険にさらされた場合に PIN 全体が漏れないように、サフィックス (PINの2番目の部分) を入力しても安全であることを確認するためのものです。

![](/_images/cc_beginner_guide4.png)

PIN コードを選択すると、PIN プレフィックスに関連するフィッシング防止用の単語が表示されます。これらの単語は、Coldcard ごとに固有です。楽しい単語や印象的な単語を見つけるまで、数種類のPINプレフィックスを試してみるのもよいでしょう。Coldcardにログインするたびに、PIN の2番目部分に進む前に、これらの単語の確認作業が重要になるため、これらの単語を覚えておく必要があります。

いつものように、新しいPINを確認し、2回目の入力を求められます。


#### 重要

**PIN を忘れてしまうと、助けてあげられる人は誰もいません。Coldcard にログインするためのバックドア、ヒント、代替手段は一切ないのです。**


#### より長いPINを使おう

暗証番号には「4＋4」桁の数字を使うことを強くお勧めします：1234-5678 「2＋2」桁でもかまいませんが、ブルートフォースアタック（総当り攻撃）を受ける可能性があります。

新しいウォレットのPINが設定されたら、ウォレットを設定します。このようなメニューが表示されます。


### 新しいウォレット（新しいシード）

**「New Wallet」**を選ぶと、[BIP-39](https://coldcard.com/docs/glossary#bip39)の単語リストを使って24個の単語が生成されます。

![](/_images/cc_beginner_guide5.png)

そして、それらの単語が表示されます。シードとなる単語を順番に、付属のカードなどに書き留めてください。この段階で注意することは、それぞれの単語が100％正しく記録されていることを確認することです。この際、手書きで複製を作っておくとよいでしょう。（つまり、バックアップをとっておく）

![cc_beginner_guide6](/_images/cc_beginner_guide6.png)

単語を書き留めたら、OK(✔)を押してクイズに進みます。Coldcardが、それぞれの単語が何であるかをランダムな順番で尋ねてきます。これは、あなたのバックアップが正しいかどうかを確認するためです。わからない単語があった場合、OK(✔)を押すと、もう一度見ることができます。

![](/_images/cc_beginner_guide7.png)

クイズに成功すると、単語が保存され、新しい Coldcard を使用できるようになります。

PIN コードとマスターシードが確立されると、Coldcard は日常的に使用できるようになります。


#### 重要な警告

ウォレット・シードを書き留めることは、非常に有用です。シードを書き留め、オフラインの安全な場所に保管することなしに、本製品を利用しないようにしてください。ウォレット・シードをコンピュータやモバイルフォンに保存しないようにしてください。シードの単語を、デジタルカメラやモバイルフォンのカメラなどで撮影しないようにしてください。



### 参考資料

[Swan](https://www.swanbitcoin.com/COLDCARD/)は、あなたのウォレットに自動支払いを行うための素晴らしいサービスです、このサービスを利用することで、あなたのビットコインの成長具合を確認することができます。

[用語集](https://coldcard.com/docs/glossary)は、ビットコインに関する用語を理解するのに役立ちます。

[クイックスタート・ガイド](https://coldcard.com/docs/quick): Coldcard をセットアップするのに便利です。

[Coldcard ドキュメント](https://coldcard.com/docs/index): より高度なトピックを参照し、セキュリティ対策を強化する場合に使用します。

何か問題がある場合、またはご注文についてご質問がある場合は、以下までご連絡ください。

[support@coinkite.com](mailto:support@coinkite.com)

宛に、写真と請求書IDを添えてご連絡ください。

[テレグラムグループ](https://t.me/coldcard)に参加して、より多くのサポートを得たり、コミュニティ意識を高めましょう！

***
コンテンツの著作権は[Coinkite.com](https://coinkite.com/)に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to [Coinkite.com](https://coinkite.com/)
