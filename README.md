# 超级三索杯立直麻将争霸赛

## 基本规则

> 比赛分为五部分进行：初赛、复赛、奖励赛、半决赛、决赛。

### 初赛 (11.1 0:00 - 11.15 12:00)

+ 初赛阶段，所有选手自行匹配，需至少完成 `10` 个半庄

+ 初始点数 `30000` 点，有天边，无西入，和牌连庄

+ 根据位次按照 `+7` / `+4` / `+1` / `0` 计算成绩，分数相同看精算点，无顺位马

+ 超过 `10` 个半庄后位次按照 `+2` / `0` / `-1` / `-2` 计算成绩

+ 选手可以在完成 `10` 个半庄后任意时刻**冻结分数** <sup id="a1">[[1]](#fn1)</sup>，此后无法获得任何位次分及奖惩分

+ 奖励分 <sup id="a2">[[2]](#fn2)</sup>

+ 惩罚分 <sup id="a3">[[3]](#fn3)</sup>

### 复赛 (11.16 0:00 - 11.22 24:00)

+ 初赛总成绩前 `16` 名进入复赛阶段，抽签分为 `A` / `B` / `C` / `D` 四组

+ 复赛分为 `8` 个半庄，每两个半庄交换组内三四位比赛

+ 交换规则由每组的 `1` 位成绩从高到低依次选择

+ 初始点数 `30000` 点，有天边，有西入，和牌连庄，顺位马为 `+10` / `+5` / `-5` / `-10`

+ 最终初始组内精算点数前 `2` 名晋级半决赛

### 奖励赛 (11.28 14:00 - 19:00)

+ 初赛奖励总分成绩前 `4` 名进入奖励赛阶段

+ 奖励赛共 `3` 个半庄，只统计奖励分与惩罚分

+ 初始点数 `30000` 点，有天边，无西入，和牌连庄，分数相同看精算点，精算点相同看初赛成绩，无顺位马

### 半决赛 (11.29 14:00 - 19:00)

+ 半决赛阶段，`8` 名选手分组进行 `3` 个半庄的比赛

+ 由复赛成绩依次选择对手，被选择后接替选择，成绩高者拥有拒绝被成绩低者选择的权利

> 例：复赛成绩从高到低依次为 A - H，A 选择 G，之后 G 选择 C，但 C 拒绝被选择，则 C 自成一组，C 开始选择。两组成形后，拒绝者自动加入另一组，并开始选择。未被选择者自动分配到成员未满的小组

+ 初始点数 `30000` 点，有天边，有西入，和牌连庄，顺位马为 `+10` / `+5` / `-5` / `-10`

+ 最终组内精算点数前 `1` 名和两组综合成绩前 `2` 名晋级决赛，名额重复则顺延

### 决赛 (12.5 - 12.6)

+ 决赛阶段，`4` 名选手进行 `5` 个半庄的比赛

+ 基础点数为 `100000` 点，补充点数为 `初赛成绩 * 100`，上限为 `10000` 点

> 例：初赛成绩为 66 分，则决赛点数为 100000 + 66 * 100 = 106600 点

+ 无天边，无西入，和牌连庄

+ 第四局结束后若出现比赛分差过大，主办认为四位无翻盘机会，第五局比赛**可能**会改为三人南

+ 最终根据终局点数决出超级三索杯第一届的冠亚季殿军

## 奖金

### 冠军

奖金 = 终局点数 / 1000，向上取整

> 例：冠军点数为 188800 点，则可以获得 cell(188800 / 1000) = 189 元

### 亚军

奖金分为两种计算方式：

1. 终局点数 / 10000

2. (终局点数 - 初始点数) / 1000

以上两种情况取最高并向上取整。

> 例：亚军点数为 123400 点，初始点数为 106600 点，则可以获得
> 
> cell(Max(123400 / 10000, (123400 - 106600) / 1000)) = cell(Max(12.34, 16.8)) = 17 元

### 奖励赛冠军

奖金 = 奖励总分

> 例：奖励赛冠军的奖励总分为 25，则可以获得 25 元

### 特别奖

| 奖项 | 说明 | 奖金 |
|:-----:|:-----|:-----:|
| 超级三索奖 | 和牌为 3s 次数（至少 3 次）最多的选手 | 10 元 |
| 高番赏 | 和出最高番数（一倍役满按 13 番计算）的选手 | n 元 （n 为番数） |
| 杠精 | 杠最多的选手 | 10 元 |
| 自摸怪 | 自摸率最高的选手 | 10 元 |
| 立直之王 | 立直数 >= 10 次，立直和牌率（立直和牌数 / 立直数）最高的选手 | 10 元 |
| 绯红之王 | 红宝牌数最多的选手 | 10 元 |
| 工具人 | 参与局数最多但未取得任何奖项的选手 | 10 元 |

## 备注

<span id="fn1">[1]</span>: 冻结分数

| 时间点 | 说明 |
|:-----|:-----|
| 距离初赛结束 `48` 小时以上 | 无需消耗分数 |
| 距离初赛结束 `48` 小时以内，`24` 小时以上 | 消耗点数为掷 2 颗骰子的和 |
| 距离初赛结束 `24` 小时以内，`12` 小时以上 | 消耗点数为掷 3 颗骰子的和 |
| 距离初赛结束 `12` 小时以内 | 消耗点数为掷 5 颗骰子的和 |

-----

> 以下未特殊说明，均指在一局半庄内

<span id="fn2">[2]</span>: 奖励分

| 名称 | 说明 | 分数 |
|:-----:|:-----|:-----:|
| 役满 | 含累计、多倍 | +13 |
| 四家立直 | | all +2 |
| 流局满贯 | | +5 |
| lucky dog | 两立直 / 一发 / 门前清自摸和 / 岭上开花 / 抢杠 / 海底摸月 / 河底捞鱼 | +1 |
| 花天月地 | 牌山剩最后一张牌时，开杠并岭山开花，不与 [lucky dog] 累计 | +4 |
| 石上三年 | 两立直 + 海底摸月 / 河底捞鱼，不与 [lucky dog] 累计 | +8 / +4 |
| 一炮多响 | | +2 / +3 |
| 反向累满 | 一炮多响且放铳点数超过 32000，不与 [一炮多响] 累计 | +13 |
| 大锤 80 | 符数 >= 80 | +2 |
| 东南西北风 | 和的牌为东南西北 | +1 |
| 振听人 | 4 面及以上振听立直自摸 | +3 |
| 续 1 秒 | 和的牌为 1s | +1 |
| 吉祥物 | 杠 3s | +1 |
| 三级跳 | 跳满数 >= 3 | +4 |
| 南三的奇迹 | 南 3 局跳满及以上 | +2 |
| 屁胡也是胡 | 1 番和牌数 >= 3 | +2 |
| 蚊子肉 | 听牌流局且获得罚符的局数 >= 3 | +2 |
| 宫永照 | 连续和牌数 >= 3，每次都比前一次大（不算本场棒、立直棒），且最终超过满贯 | +6 |
| 八连庄 | 本场棒 >= 8 | +8 |
| 燕返 | 和立直声明牌 | +1 |
| 好事成双 | 统计和 2 番役种的个数（统计宝牌） | +0.5*n（n 为 2 番的役种数） |
| 000 | 和牌时红宝牌数为 3 | +3 |
| 染手怪 | 混一色 / 清一色次数 >= 3 | +4 |
| dora 回避 | 满贯及以上和牌且宝牌数 <= 1 的局数 >= 3 | +5 |
| 亲跳回避 | 自亲且跳满及以上和牌 | +2 |
| 连风战神 | w东 / w南次数 >= 2 | +2 |
| 中个里三 | 里宝牌 >= 3 | +3 |
| 虎牢关 | 2 位结算点数 <= 20000 点 | 一位 +3 |
| 星象学家 | 和牌包含 1p / 3p / 7p / 自风 / 白 至少两种刻子 | +n+1（n 为刻子数） |
| 报菜名 | 和牌番种 >= 6（不统计宝牌） | +n（n 为番种数） |

<span id="fn3">[3]</span>: 惩罚分

| 名称 | 说明 | 分数 |
|:-----:|:-----|:-----:|
| 烧鸡 | 南四完场一把未和，且未获得罚符 | -3 |
| 四杠散了 | | -n（n 为杠数） |
| 岭上放铳 | | -1 |
| 三而竭 | 立直但未和牌数 >= 3，包括听牌流局 | -3 |
| 欢乐三打一 | 3 位结算点 >= 35000 点 | 四位 -3 |
| 无铳吃四 | | -4 |
| 铳圣 | 放铳次数 >= 5 | -8 |
| 闪电人 | 掉线次数 >= 3 且在掉线期间放铳 | -5 |
| 杠精之死 | 有杠并放铳，荣和家 dora 数（不统计红宝牌） >= 5 | -5 |
| 东一被飞 | 东一局被击飞 | -5 |
| 绝对防御 | 未听流局所支付的点数总和 >= 8000 | -5 |
| 僵局 | 终局所有人未超过 35000 分 | all -2 |

## 写在最后

参赛者请**确保**在指定日期时间段内有时间参与比赛。尤其是复赛及之后的阶段，**弃赛**或**未在指定时间参赛**对所有人的参赛体验都会有影响，请大家以认真负责的态度完成比赛

本次比赛**不支持**不正打，请所有参赛选手认真对待比赛，不要放弃任何可以翻盘的机会

弃赛、未完赛和不正打者主办有权取消其评奖资格

本次活动最终解释权归主办方所有
