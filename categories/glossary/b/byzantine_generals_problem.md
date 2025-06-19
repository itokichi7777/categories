---
title: ビザンチン将軍問題
taxonomy:
    category:
        - glossary
---

## Byzantine Generals Problem
2,100 sats

ビザンチン将軍問題は、中央集権的な調整機能や盗聴のおそれのない通信手段がない環境で、複数の関係者がゲーム理論的に安全な方法で合意形成する難しさを指します。この問題を解決するには、すべての関係者が他者を信頼せず独自に事の真偽を判断でき、最終的に集団としての合意に達する方法が必要です。

例えば、複数の軍隊がビザンチンの包囲に成功したとします。次のステップは、ビザンチンを攻撃するタイミングについて、各隊を率いる将軍間での合意形成です。全隊一致して攻撃できれば勝利しますが、各隊バラバラに攻めれば負けてしまいます。将軍たちが安全に意思疎通できる通信チャネルがあればよいのですが、彼らのやりとりがビザンチン防衛軍に盗聴、妨害される可能性は否定できません。

[ビットコイン](https://lostinbitcoin.sakuraweb.com/glossary/bitcoin/)は[プルーフオブワーク](https://lostinbitcoin.sakuraweb.com/glossary/pow/)機構を実装することで、ビザンチン将軍問題を克服しました。ネットワークに参加する全ての[ノード](https://lostinbitcoin.sakuraweb.com/glossary/node/)は、有効なハッシュという形でプルーフオブワークを含む[ブロック](https://lostinbitcoin.sakuraweb.com/glossary/block/)だけを独自に有効と判断して承認します。これにより、世界中に分散したノードがトラストレス、つまり、信頼できる第三者の仲介なしに合意形成できます。ハッシュはブロックを生成したマイナーが特定の作業を行った事の証明にすぎません。ブロック生成の際に一定の作業を義務付けることで、マイナーが無効あるいは空のブロックを生成してネットワークにスパム攻撃を仕掛けるコストを高めています。さらに、マイナーは有効なブロックを生成して初めて[マイニング報酬](https://lostinbitcoin.sakuraweb.com/glossary/block_reward/)（[送金手数料](https://lostinbitcoin.sakuraweb.com/glossary/transaction_fee/)とブロック生成時に新規発行されるビットコインで支払われる[ブロック報酬](https://lostinbitcoin.sakuraweb.com/glossary/block_subsidy/)）を手にすることができるため、攻撃するよりも規則を遵守して誠実に行動するインセンティブの方が大きいです。

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.
