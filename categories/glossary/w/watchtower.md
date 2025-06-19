---
title: ウォッチタワー
taxonomy:
    category:
        - glossary
---

## Watchtower
2,100 sats

<div><button class="zap-button" data-npub="npub17d7ham6ucsm2yxuwa9k9th49d44lfa50uk2fq0v2p0jxs2npnyxsaxxt59" data-relays="wss://relay.damus.io,wss://relay.snort.social,wss://nostr.wine,wss://relay.nostr.band">Zap Me ⚡</button><a href="https://twitter.com/akipponn">@akipponn</a></div>

信頼関係にない2者が運用するライトニングノード間に構築されたペイメントチャネルから成る[ライトニングネットワーク](https://lostinbitcoin.sakuraweb.com/glossary/lightning_network/)には、[二重支払い](https://lostinbitcoin.sakuraweb.com/glossary/double_spend/)の問題があります。ウォッチタワーは二重支払い防止を目的に、特定チャネルを監視するサービスです。ウォッチタワーを請け負う第3者への信用が求められますが、ライトニングノード運用者はウォッチタワーを利用することで、チャネルパートナーによる二重支払いを防ぐことができます。

ライトニングネットワークは資金移動に未承認トランザクションを使うため、二重支払い問題を完全に解消することはできません。[チャネル](https://lostinbitcoin.sakuraweb.com/glossary/lightning_channel/)を開いた相手が悪意ある攻撃者であれば、過去のライトニング決済を無効にすべく、古い未承認トランザクションをブロードキャストして、二重支払いを試みるかもしれません。

この対策として、ライトニングネットワークにはジャスティス・トランザクションと呼ばれる仕組みがあります。ジャスティス・トランザクションを利用することで、二重支払いの被害者は被害金額の回復にとどまらず、攻撃者が正当な所有権を持つ[ビットコイン](https://lostinbitcoin.sakuraweb.com/glossary/bitcoin/)を含むチャネルの全残高を獲得できます。

ジャスティス・トランザクションは攻撃発生から一定時間内に実行する必要がありますが、全てのライトニングノード運用者が、自身のノードを常時監視して、期限内にジャスティス・トランザクションを実行できるとは限りません。ウォッチタワーを利用してジャスティス・トランザクションの実行をアウトソースすれば、ノード運用者はノードを監視していなくても、ノードがオフラインの時でも、タイムリーにジャスティス・トランザクションを実行できます。

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
