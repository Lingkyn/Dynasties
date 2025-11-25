# 地图与地块

<div class="wa-grid">
  <wa-card class="card-media">
    <div slot="media" class="wa-frame:square">
      <img src="/Dynasties/_media/大地图.png" alt="大地图" />
    </div>
<p style="margin:0.5rem 0 0; text-align:center;">大地图</p>
  </wa-card>

  <wa-card class="card-media">
    <div slot="media" class="wa-frame:square">
      <img src="/Dynasties/_media/沃土.png" alt="地块板示例" />
    </div>
    <p style="margin:0.5rem 0 0; text-align:center;">地块板示例</p>
  </wa-card>
</div>

<style>
  .card-media { max-width: 420px; }
  .wa-frame\:square { aspect-ratio: 1/1; overflow: hidden; display: block; }
  .wa-frame\:square img { width: 100%; height: 100%; object-fit: contain; object-position: center; display: block; }
</style>

* 大地图×1
* 土地块×24：沃土×4，平地×12，瘠土×8
* 路障块×12

| 土地格类型 | 说明文字 | 编号 |
| --- | --- | --- |
| 沃土 | 粮食产出3份 | 3，9，15，21 |
| 平地 | 粮食产出2份 | 1~24剩余编号 |
| 瘠土 | 粮食产出1份 | 1，5，7，11，13，17，19，23 |