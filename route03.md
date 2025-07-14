# ○○の通学経路

[メンバー表に戻る](member.md#メンバー表)

```graphviz
digraph {
    edge [dir=both]
    
    北坂戸駅 -> 朝霞台駅 [label=東武東上線]
    朝霞台駅 -> 北朝霞駅 [label=徒歩]
    北朝霞駅 -> 西国分寺駅 [label=武蔵野線]
    西国分寺駅 -> 高尾駅 [label=中央線]
    高尾駅 -> 拓殖大学八王子国際キャンパス [label=バス]

}
```
