---
title: 拡張秘密鍵 (Xprv)
taxonomy:
    category:
        - glossary
---

## Extended Private Key (Xprv)
2,100 sats

<div><button class="zap-button" data-npub="npub17d7ham6ucsm2yxuwa9k9th49d44lfa50uk2fq0v2p0jxs2npnyxsaxxt59" data-relays="wss://relay.damus.io,wss://relay.snort.social,wss://nostr.wine,wss://relay.nostr.band">Zap Me ⚡</button><a href="https://twitter.com/akipponn">@akipponn</a></div>

拡張秘密鍵はxprvとも表記され、[階層型決定性（HD）ウォレット](https://lostinbitcoin.sakuraweb.com/glossary/bip32/)で子秘密鍵の生成に使われます。BIP32が実装されて以降、バックアップの利便性から、ほぼすべてのビットコイン[ウォレット](https://lostinbitcoin.sakuraweb.com/glossary/wallet/)がHDフォーマットを採用しています。マスター秘密鍵と呼ばれる拡張秘密鍵の1つだけをバックアップしておけば、ウォレット内のすべての[公開鍵](https://lostinbitcoin.sakuraweb.com/glossary/public_key/)と[秘密鍵](https://lostinbitcoin.sakuraweb.com/glossary/private_key/)を一括してバックアップ・復元できるのです。

マスター秘密鍵と拡張秘密鍵はよく混同されますが、マスター秘密鍵はHDウォレットの[シード](https://lostinbitcoin.sakuraweb.com/glossary/seed/)から直接生成される唯一の拡張秘密鍵で、HDツリーのルートに当たります。一方の拡張秘密鍵は子秘密鍵を生成できる秘密鍵を指し、1つのHDウォレットで無数に生成できます。

子秘密鍵が漏洩した場合、失うのはその鍵に関連する資金のみです。しかし、拡張秘密鍵が漏洩すると、それを基に生成されたすべての子秘密鍵に関連する資金が失われます。拡張秘密鍵はすべて'xprv'で始まり、その後に英数字からなる文字列が続きます。

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
