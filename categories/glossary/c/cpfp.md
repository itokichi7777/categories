---
title: CPFP
taxonomy:
    category:
        - glossary
---

以下の英語の用語と説明を日本語にしてください。忠実な翻訳でなくて構いません。AI翻訳にかけて内容を理解した上で、ご自身の言葉で説明してください。

日本語の提案はGitHubでプルリクエストとして受付中。プルリクエストがマージされたら、報酬をライトニング⚡️送金します。
提案手順は[こちら](https://github.com/lostinbitcoin/categories/wiki)の「2. 用語集の用語説明の提案手順」をご参照ください。

## Child-Pays-for-Parent (CPFP)
2,100 sats

CPFPは、[トランザクション](http://lostinbitcoin.jp.testrs.jp/staging/glossary/transaction/)の確認速度を速める手法のことを指します。[RBF（Replace-by-Fee）](http://lostinbitcoin.jp.testrs.jp/staging/glossary/rbf/)と似た目的を持ちますが、RBFが送信者によってトランザクションの確認速度を向上させるのに対し、CPFPでは受信者がトランザクションの確認速度を向上させることができます。

もし送信者が低い手数料でトランザクションを送信し、そのトランザクションが十分な速さで[ブロック](http://lostinbitcoin.jp.testrs.jp/staging/glossary/block/)に取り込まれない場合、受信者は、未確認の状態でそのトランザクションの[ビットコイン](http://lostinbitcoin.jp.testrs.jp/staging/glossary/bitcoin/)を使用する新しいトランザクションを作成できます。(元のトランザクションがまだ[メンプール](http://lostinbitcoin.jp.testrs.jp/staging/glossary/mempool/)にある状態でも可能です。)この2番目のトランザクション（子トランザクション）で高い手数料を設定し、マイナーに対して「この子トランザクションを[マイニング](http://lostinbitcoin.jp.testrs.jp/staging/glossary/mining/)するには、まず最初のトランザクション（親トランザクション）もマイニングしなければならない。」と示すことになります。この仕組みにより、送信者が低い手数料を設定していても、受信者がトランザクションの確認速度を速めることができます。

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
