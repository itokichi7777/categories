---
title: オーファン (孤立) ブロック
taxonomy:
    category:
        - glossary
---

## Orphan Block
2,100 sats

<div><button class="zap-button" data-npub="npub17d7ham6ucsm2yxuwa9k9th49d44lfa50uk2fq0v2p0jxs2npnyxsaxxt59" data-relays="wss://relay.damus.io,wss://relay.snort.social,wss://nostr.wine,wss://relay.nostr.band">Zap Me ⚡</button><a href="https://twitter.com/akipponn">@akipponn</a></div>

ビットコイン[ブロックチェーン](https://lostinbitcoin.sakuraweb.com/glossary/blockchain/)は、通常、約10分間隔で新規[ブロック](https://lostinbitcoin.sakuraweb.com/glossary/block/)が生成されるよう設計されていますが、時々、2つのブロックがほぼ同時に生成されることがあります。一方のブロックがネットワークを構成するノードの約半数に伝播する間、もう一つのブロックが残りの[ノード](https://lostinbitcoin.sakuraweb.com/glossary/node/)に伝播するケースが考えられます。この場合、どちらのブロックも有効なため、ノードは両方を保持します。その結果、有効なビットコインブロックチェーンが２つ併存することになります。マイナーはどちらか一方のチェーンにブロックを追加していくので、最終的には、一方のチェーンが他方より長くなります。この時点で、全てのノードは長い方を正当なチェーンとみなして残し、短い方のチェーンを破棄します。この破棄されたチェーンに含まれるのが、オーファンブロックです。オーファンブロックは大抵1つですが、理論上、その数に上限はありません。リオルグと呼ばれるチェーン再編成が起きたり、有効な2つのチェーンが同じ長さで併存する期間が長期化すれば、オーファンブロックは増えます。

オーファンブロックを生成したマイナーは、[マイニング報酬](https://lostinbitcoin.sakuraweb.com/glossary/block_reward/)を失うので大きな経済的損失を被ります。そのため、ノード間のブロック伝播スピードを上げて、オーファンブロックの発生を最小化するのがネットワークの使命です。これが[ビットコイン](https://lostinbitcoin.sakuraweb.com/glossary/bitcoin/)の[ブロックサイズ](https://lostinbitcoin.sakuraweb.com/glossary/block_size/)に上限が設けられており、上限引き上げが受け入れられない理由の1つです。

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
