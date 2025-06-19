---
title: 不変性
taxonomy:
    category:
        - glossary
---

## Immutability
2,100 sats

[ビットコイン](https://lostinbitcoin.sakuraweb.com/glossary/bitcoin/)は不変性という特徴を持ちます。この不変性には2つの意味があります。

1つは、ビットコインの[コンセンサス](https://lostinbitcoin.sakuraweb.com/glossary/consensus/)[プロトコル](https://lostinbitcoin.sakuraweb.com/glossary/protocol/)、つまり、ネットワークの合意規則は変更が非常に難しいという意味です。コンセンサスプロトコルの核であるビットコインの通貨政策、すなわち、発行上限と発行スケジュールはほぼ変更不可能です。この不変性を堅持しているのが、ビットコインネットワークを形成する[ノード](https://lostinbitcoin.sakuraweb.com/glossary/node/)です。世界中に分散する数万のノードは、それぞれ個別にビットコインソフトウェアを実行し、合意規則に基づいて[トランザクション](https://lostinbitcoin.sakuraweb.com/glossary/transaction/)の正当性を検証します。マイナーや政府は変更を強制できません。変更に同意して、変更を反映したソフトウェアをダウンロードして実行するノードがマジョリティに達しない限り、合意規則は不変です。この不変性なしに、機関投資家や個人投資家がビットコインの[希少性](https://lostinbitcoin.sakuraweb.com/glossary/scarcity/)や、将来にわたる安定稼働性を信じることはできないでしょう。

2つ目の不変性は、ビットコインの取引履歴についてです。ビットコイン[ブロックチェーン](https://lostinbitcoin.sakuraweb.com/glossary/blockchain/)の記録を書き換えるのは実質不可能です。これは[SHA-256](https://lostinbitcoin.sakuraweb.com/glossary/sha_256/)ハッシュ関数の特性に由来します。ビットコインブロックチェーンには、約10分間隔で新規[ブロック](https://lostinbitcoin.sakuraweb.com/glossary/block/)を追加されます。マイナーは有効なハッシュを見つけるまで、ブロックのハッシュを計算し続けます。ハッシュするブロックには1つ前のブロックのハッシュが含まれます。[ハッシュ関数](https://lostinbitcoin.sakuraweb.com/glossary/hash_function/)の特性により、前のブロックのハッシュが変更されると、そのハッシュを含む次のブロックのハッシュも変わってしまいます。すると、[プルーフ・オブ・ワーク](https://lostinbitcoin.sakuraweb.com/glossary/pow/)が無効となり、ブロックも無効となります。例えば、ブロックチェーンに500ブロックある場合、ブロック#400のハッシュはブロック#399のハッシュを含みます。ブロック#399の一部が変更されると、ブロック#399のハッシュが変わり、ブロック#400のハッシュも変わります。このハッシュ変更の連鎖は最新のブロック#500まで及び、結果として#399以降のブロックはすべて無効になります。このため、一度ブロックチェーンに追加されたブロックは、ブロックチェーンを構築し直さない限り、変更できないのです。支払いを受ける店舗や事業者からすれば、キャンセル可能なクレジットカードや銀行を介した従来の法定通貨での決済より、取り消し不可能なビットコイン決済の方が信用できるのではないでしょうか。

しかし、ビットコインの不変性も絶対ではありません。攻撃者はビットコインネットワークの総演算能力の過半を掌握すれば、[51％攻撃](https://lostinbitcoin.sakuraweb.com/glossary/51_attack/)と呼ばれる方法で、過去のブロックを改ざんできます。攻撃コストを高めて攻撃を牽制するために、[ハッシュレート](https://lostinbitcoin.sakuraweb.com/glossary/hash_rate/)の高水準での維持と地理的分散が不可欠です。

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
