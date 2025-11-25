# 卡牌类

## 官职卡牌

### 卡牌示例

<div style="display: flex; gap: 20px; margin: 20px 0;">
  <wa-card class="card-overview" style="width:200px;">
    <div slot="media" class="wa-frame:portrait">
      <img src="/Dynasties/_media/户部尚书.png" alt="户部尚书" />
    </div>
    <strong>户部尚书</strong>
    <small class="wa-caption-s">户部尚书 / Minister of Treasury</small>
  </wa-card>

  <wa-card class="card-overview" style="width:200px;">
    <div slot="media" class="wa-frame:portrait">
      <img src="/Dynasties/_media/中书令.png" alt="中书令" />
    </div>
    <strong>中书令</strong>
    <small class="wa-caption-s">中书令 / Secretary of State</small>
  </wa-card>

  <wa-card class="card-overview" style="width:200px;">
    <div slot="media" class="wa-frame:portrait">
      <img src="/Dynasties/_media/太常卿.png" alt="太常卿" />
    </div>
    <strong>太常卿</strong>
    <small class="wa-caption-s">太常卿 / Master of Ceremonies</small>
  </wa-card>
</div>

* 唐×10（黄），宋×10（绿），元×10（蓝），明×10（红）

### 官职对照表

| 唐 | 宋 | 元 | 明 | 执行政策 | 颁布政策 |
| --- | --- | --- | --- | --- | --- |
| 中书令 | 平章政事 | 中书令 | 内阁首辅 |  | 割壤练兵减籍抚民招商扩市 |
| 吏部尚书 | 参知政事 | 平章政事 | 吏部尚书 | 叛乱：招抚政变：让权入侵：求和 |  |
| 户部尚书 | 三司使 | 户部尚书 | 户部尚书 | 干旱：赈粮地震：赈灾洪水：疏河 |  |
| 礼部尚书 | 礼部尚书 | 太常礼仪院使 | 太常寺卿 | 干旱：祈雨瘟疫：施药入侵：求和 |  |
| 工部尚书 | 国子监祭酒 | 国子监祭酒 | 工部尚书 | 地震：重建洪水：疏河洪水：迁民 |  |
| 刑部尚书 | 御史中丞 | 御史大夫 | 刑部尚书 | 瘟疫：封城贪污：肃腐政变：清洗 |  |
| 兵部尚书 | 枢密使 | 枢密使 | 五军都督府都督 | 叛乱：镇压入侵：开战瘟疫：封城 |  |
| 节度使 | 知州 | 行省丞相 | 总督 | 入侵：开战洪水：迁民叛乱：镇压 |  |
| 御史大夫 | 谏议大夫 | 达鲁花赤 | 左都御史 | 腐败事件不触发 |  |
| 太常卿 | 翰林学士承旨 | 宣政院使 | 国子监祭酒 | 干旱：祈雨 | 祈天延命 |


## 政策卡牌

### 执行政策

<div style="display: flex; gap: 20px; margin: 20px 0;">
  <wa-card class="card-media" style="width:220px; text-align:center;">
    <div slot="media" class="wa-frame:portrait">
      <img src="/Dynasties/_media/政策卡牌背面.png" alt="政策卡牌-背面" />
    </div>
    <small class="wa-caption-s">政策卡牌 - 背面</small>
  </wa-card>

  <wa-card class="card-media" style="width:220px; text-align:center;">
    <div slot="media" class="wa-frame:portrait">
      <img src="/Dynasties/_media/政策卡牌正面.png" alt="政策卡牌-正面" />
    </div>
    <small class="wa-caption-s">政策卡牌 - 正面</small>
  </wa-card>
</div>
* 每个阵营一套×4

* 干旱×3，地震×3，洪水×3，瘟疫×3
* 叛乱×3，入侵×3，政变×3，腐败×2

#### 干旱

* 赈粮：国库-1500；民生+1，财富-1
* 祈雨：国库-500，掷骰子
  * 1~3成功，民生+1
  * 4~6失败，财富-1
* 放任：民生-1，财富-2

#### 地震

* 重建：国库-1500；民生+2，财富-1
* 赈灾：国库-1000，掷骰子
  * 1~3成功，民生+1，财富+1
  * 4~6失败，国库-1000，民生-1
* 放任：民生-1，财富-1

#### 洪水

* 疏河：国库-1500，掷骰子
  * 1~3成功，民生+1，财富+1
  * 4~6失败，国库-1000，民生-1
* 迁民：国库-800；财富值-1
* 放任：民生-1，财富-1

#### 瘟疫

* 施药：国库-1500，掷骰子
  * 1~3成功，民生+1
  * 4~6失败，民生-1，财富-1
* 封城：国库-800；民生-1，财富-1
* 放任：民生-2，财富-1

#### 叛乱：民生≦3的阵营触发

* 镇压：民生值-1，掷骰子
  * 1~军事值为胜，国库+1000
  * 反之为败，国库-1500，军事值-1
* 招抚：军事值-1；国库-800
* 放任：国库-1500；民生+1，财富值-2

#### 入侵：军事≦3的阵营触发

* 开战：民生值-1，掷骰子
  * 1~军事值为胜，国库+2000，财富值+1
  * 反之为败，国库-2500，军事值-1，财富值-1
* 求和：军事值-1；国库-1500，财富值-1
* 放任：损失3块土地+其上子民棋子；民生+1，财富值-1

#### 政变：军事≧4的阵营触发

* 清洗：国库-1500，掷骰子
  * 1~军事值为胜，国库+1000，财富+1
  * 反之为败，国库-2000，民生-1，财富值-1
* 让权：放弃下一回合；国库-800，军事-1
* 放任：国库-1000；军事-1，民生-2

#### 腐败：财富≧4的阵营触发

* 肃腐：国库-800
* 放任：民生-1；国库+500，财富值-1

### 颁布政策

<div style="display: flex; gap: 20px; margin: 20px 0;">
  <wa-card class="card-media" style="width:220px; text-align:center;">
    <div slot="media" class="wa-frame:portrait">
      <img src="/Dynasties/_media/颁布政策-背面.png" alt="颁布政策 - 背面" />
    </div>
    <small class="wa-caption-s">颁布政策 - 背面</small>
  </wa-card>

  <wa-card class="card-media" style="width:220px; text-align:center;">
    <div slot="media" class="wa-frame:portrait">
      <img src="/Dynasties/_media/颁布政策-正面.png" alt="颁布政策 - 正面" />
    </div>
    <small class="wa-caption-s">颁布政策 - 正面</small>
  </wa-card>
</div>
* 每个阵营一套×4
* 割壤练兵×1，减籍抚民×1，招商扩市×1，祈天延命×1

| 属性值 | 政策名 | 增加条件 |
| --- | --- | --- |
| 军事+1 | 割壤练兵 | 阵营土地-3，及其上子民棋子 |
| 民生+1 | 减籍抚民 | 子民棋子-3 |
| 财富+1 | 招商扩市 | 阵营国库-1500 |
| 信仰+1 | 祈天延命 | 军事值-1，民生值-1，财富值-1 |


### 特殊政策

| 朝代 | 特殊政策卡 | 作用 |
| --- | --- | --- |
| 唐 | 通货膨胀卡×3 | 该轮粮食价格上涨至300/份 |
| 宋 | 杯酒释兵权卡×3 | 该轮其他阵营战力计算-3 |
| 元 | 开疆扩土卡×3 | 该轮该阵营骰子数量+1 |
| 明 | 重建孔庙学校卡×3 | 该轮初始子民棋子获取2次 |


## 粮食卡牌

* 2.5cm×2.5cm 小卡

* 3份粮食卡×10，2份粮食卡×18，1份粮食卡×24
