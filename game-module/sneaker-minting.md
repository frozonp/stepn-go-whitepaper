# スニーカーミント

## ミントとは？

既存の2つのスニーカーを使用して新しいスニーカーを作成することができる。\
ミントの条件は以下の通り：

1. **片方のスニーカーを左足用、もう片方を右足用とし**、左足用スニーカーは左、右足用スニーカーは右を指す。
2. 両スニーカーがLv.10以上
3. GGTコスト
4. ダイナミックミントQuotaが必要。ミントQuotaはエナジー消費量（ユーザーとゲストのエナジー消費量の組み合わせ）から算出される。

ミントには48時間のクールダウン期間があり、各スニーカーは合計で最大7回のミントを行うことができる。**GGTコストはミントするごとに増加し、同様に靴箱をドロップする確率も増加します。**ミントした靴箱はインベントリに入り、すぐに開封できる。

各スニーカーのミントコストはクオリティに基づいて計算され、ミントコストの合計に組み合わされます。最初2回のミントコストは一定です。

_**注：現在、スニーカーのミントにGMTは必要ありません。**_

## 靴箱とは？

ミントプロセスにおいてユーザーはスニーカーを直接受け取るのではなく、靴箱を受け取る。靴箱を開けると、ユーザーはスニーカーを受け取る。靴箱を開けることでスニーカーを受け取る。

## 双子

ミント時、余分に靴箱を得るチャンスがある。スニーカーのミント回数が多いほど、双子の確率は上がる。

## 靴箱のクオリティ

靴箱のミント結果は、「親」スニーカーのクオリティによって異なる。以下は、「親」スニーカーに違いに基づく結果：

<table><thead><tr><th>クオリティ</th><th width="125" data-type="number">Common靴箱 %</th><th data-type="number">Uncommon靴箱 %</th><th data-type="number">Rare靴箱 %</th><th data-type="number">Epic靴箱 %</th><th data-type="number">Legendary靴箱 %</th></tr></thead><tbody><tr><td>Common x Common</td><td>100</td><td>0</td><td>0</td><td>0</td><td>0</td></tr><tr><td>Common x Uncommon</td><td>50</td><td>49</td><td>1</td><td>0</td><td>0</td></tr><tr><td>Common x Rare</td><td>50</td><td>0</td><td>49</td><td>1</td><td>0</td></tr><tr><td>Common x Epic</td><td>50</td><td>0</td><td>0</td><td>49</td><td>1</td></tr><tr><td>Common x Legendary</td><td>50</td><td>0</td><td>0</td><td>0</td><td>50</td></tr><tr><td>Uncommon x Uncommon</td><td>0</td><td>98</td><td>2</td><td>0</td><td>0</td></tr><tr><td>Uncommon x Rare</td><td>0</td><td>49</td><td>50</td><td>1</td><td>0</td></tr><tr><td>Uncommon x Epic</td><td>0</td><td>49</td><td>1</td><td>49</td><td>1</td></tr><tr><td>Uncommon x Legendary</td><td>0</td><td>49</td><td>1</td><td>0</td><td>50</td></tr><tr><td>Rare x Rare</td><td>0</td><td>0</td><td>98</td><td>2</td><td>0</td></tr><tr><td>Rare x Epic</td><td>0</td><td>0</td><td>49</td><td>50</td><td>1</td></tr><tr><td>Rare x Legendary</td><td>0</td><td>0</td><td>49</td><td>1</td><td>50</td></tr><tr><td>Epic x Epic</td><td>0</td><td>0</td><td>0</td><td>98</td><td>2</td></tr><tr><td>Epic x Legendary</td><td>0</td><td>0</td><td>0</td><td>49</td><td>51</td></tr><tr><td>Legendary x Legendary</td><td>0</td><td>0</td><td>0</td><td>0</td><td>100</td></tr></tbody></table>

_**注：高いクオリティのスニーカーは段階的にリリースされます。したがって、そのクオリティが正式にリリースされるまでは、ユーザーはミントから高いクオリティのスニーカーを入手することはできません。**_

_**注：上表の情報は、テスト段階で予告なく変更される場合がある。**_

## 靴箱開封

靴箱から得られる新しいスニーカーのクオリティ、タイプ、ソケットタイプは、「親」スニーカーの特性によって以下のように決定される：

<table><thead><tr><th>靴箱クオリティ</th><th data-type="number">Common靴</th><th data-type="number">Uncommon靴</th><th data-type="number">Rare靴</th><th data-type="number">Epic靴</th><th data-type="number">Legendary靴</th></tr></thead><tbody><tr><td>Common</td><td>97</td><td>3</td><td>0</td><td>0</td><td>0</td></tr><tr><td>Uncommon</td><td>25</td><td>73</td><td>2</td><td>0</td><td>0</td></tr><tr><td>Rare</td><td>0</td><td>27</td><td>71</td><td>2</td><td>0</td></tr><tr><td>Epic</td><td>0</td><td>0</td><td>30</td><td>68</td><td>2</td></tr><tr><td>Legendary</td><td>0</td><td>0</td><td>0</td><td>35</td><td>65</td></tr></tbody></table>

_**注：上表の情報は、テスト段階で予告なく変更される場合がある。**_

## スニーカータイプ



<table><thead><tr><th>タイプ</th><th data-type="number">Walker %</th><th data-type="number">Jogger %</th><th data-type="number">Runner %</th><th data-type="number">Trainer %</th></tr></thead><tbody><tr><td>Walker x Walker</td><td>85</td><td>6</td><td>6</td><td>3</td></tr><tr><td>Waleker x Jogger</td><td>45</td><td>45</td><td>7</td><td>3</td></tr><tr><td>Walker x Runner</td><td>45</td><td>7</td><td>45</td><td>3</td></tr><tr><td>Walker x Trainer</td><td>80</td><td>6</td><td>6</td><td>8</td></tr><tr><td>Jogger x Jogger</td><td>6</td><td>85</td><td>6</td><td>3</td></tr><tr><td>Jogger x Runner</td><td>7</td><td>45</td><td>45</td><td>3</td></tr><tr><td>Jogger x Trainer</td><td>6</td><td>80</td><td>6</td><td>8</td></tr><tr><td>Runner x Runner</td><td>6</td><td>6</td><td>85</td><td>3</td></tr><tr><td>Runner x Trainer</td><td>6</td><td>6</td><td>80</td><td>8</td></tr><tr><td>Trainer x Trainer</td><td>25</td><td>25</td><td>25</td><td>25</td></tr></tbody></table>

_**注：上表の情報は、テスト段階で予告なく変更される場合がある**_

新しいスニーカーのソケットタイプは、2つの「親」スニーカーのソケットタイプによって決定される。

<table><thead><tr><th>親</th><th data-type="number">Efficiency %</th><th data-type="number">Luck %</th><th data-type="number">Charm</th><th data-type="number">Karma</th></tr></thead><tbody><tr><td>Efficiency x Efficiency</td><td>70</td><td>10</td><td>10</td><td>10</td></tr><tr><td>Efficiency x Luck</td><td>40</td><td>40</td><td>10</td><td>10</td></tr><tr><td>Efficiency x Charm</td><td>40</td><td>10</td><td>40</td><td>10</td></tr><tr><td>Efficiency x Karma</td><td>40</td><td>10</td><td>10</td><td>40</td></tr><tr><td>Luck x Luck</td><td>10</td><td>70</td><td>10</td><td>10</td></tr><tr><td>Luck x Charm</td><td>10</td><td>40</td><td>40</td><td>10</td></tr><tr><td>Luck x Karma</td><td>10</td><td>40</td><td>10</td><td>40</td></tr><tr><td>Charm x Charm</td><td>10</td><td>10</td><td>70</td><td>10</td></tr><tr><td>Charm x Karma</td><td>10</td><td>10</td><td>40</td><td>40</td></tr><tr><td>Karma x Karma</td><td>10</td><td>10</td><td>10</td><td>70</td></tr><tr><td></td><td>null</td><td>null</td><td>null</td><td>null</td></tr></tbody></table>

_**注：上表の情報は、テスト段階で予告なく変更される場合がある。**_

## **ミントフィー**

ミントフィーは6%
