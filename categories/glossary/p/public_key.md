---
title: 公開鍵
taxonomy:
    category:
        - glossary
---

## Public Key
2,100 sats

公開鍵は[ビットコイン](https://lostinbitcoin.sakuraweb.com/glossary/bitcoin/)の受け取りに使われます。公開鍵に送信されたビットコインは、対応する[秘密鍵](https://lostinbitcoin.sakuraweb.com/glossary/private_key/)の所有者しか使用できません。公開鍵は私書箱に例えることができます。誰でも私書箱に郵便物を送ることができますが、その郵便物にアクセスできるのは、（秘密）鍵の所有者のみです。秘密鍵には対応する公開鍵が1つだけあり、その逆も同じです。公開鍵は公表しても問題ありませんが、秘密鍵は誰にも知られないよう安全に保管する必要があります。

公開鍵と[アドレス](https://lostinbitcoin.sakuraweb.com/glossary/address/)はしばしば混同されますが、アドレスは公開鍵のハッシュであり、現在ではビットコインの受け取りには公開鍵ではなくアドレスが使用されています。アドレスは利便性と安全性の向上のために公開鍵を短縮したものにすぎず、ビットコインを使う際の[署名](https://lostinbitcoin.sakuraweb.com/glossary/signature/)検証に使用するのは公開鍵です。

公開鍵を生成、管理するのに使うのがビットコイン[ウォレット](https://lostinbitcoin.sakuraweb.com/glossary/wallet/)です。ウォレットを新規作成すると、まず大きな乱数である秘密鍵が導出されます。次に秘密鍵から公開鍵が導出され、最後に、公開鍵のハッシュにプレフィックスを追加してアドレスが生成されます。

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
