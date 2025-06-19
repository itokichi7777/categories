---
title: メンプール (メモリープール)
taxonomy:
    category:
        - glossary
---

## Mempool
2,100 sats

mempool (メンプール、メモリープール) は各[ノード](https://lostinbitcoin.sakuraweb.com/glossary/node/)が保持する未承認あるいは保留中トランザクションから成るデータベースです。mempoolにある[トランザクション](https://lostinbitcoin.sakuraweb.com/glossary/transaction/)は、[ブロック](https://lostinbitcoin.sakuraweb.com/glossary/block/)に取り込まれるとmempoolから削除されます。

mempoolは各ノードが持ち、ノード間で署名済みトランザクションを相互中継することでmempoolデータを共有します。つまり、[ビットコイン](https://lostinbitcoin.sakuraweb.com/glossary/bitcoin/)ネットワークには、全てのノードが参照するマスターmempoolのようなものは存在しませんし、全ての未承認あるいは保留中トランザクションを集めたmempoolを保持するノードもおそらくありません。

マイナーは自ら運用するノードのmempoolから未承認トランザクションを取り出してブロックに含めます。

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
