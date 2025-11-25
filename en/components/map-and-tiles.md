# Map and Tiles

<div class="wa-grid">
  <wa-card class="card-media">
    <div slot="media" class="wa-frame:square">
      <img src="/Dynasties/_media/大地图.png" alt="Main Map" />
    </div>
    <p style="margin:0.5rem 0 0; text-align:center;">Main Map</p>
  </wa-card>

  <wa-card class="card-media">
    <div slot="media" class="wa-frame:square">
      <img src="/Dynasties/_media/沃土.png" alt="Land Tile Example" />
    </div>
    <p style="margin:0.5rem 0 0; text-align:center;">Land Tile Example</p>
  </wa-card>
</div>

<style>
  .card-media { max-width: 420px; }
  .wa-frame\:square { aspect-ratio: 1/1; overflow: hidden; display: block; }
  .wa-frame\:square img { width: 100%; height: 100%; object-fit: contain; object-position: center; display: block; }
</style>

* Main Map ×1
* Land Tiles ×24: Fertile Land ×4, Plain ×12, Barren Land ×8
* Obstacle Tiles ×12

| Land Tile Type | Description | Numbers |
| --- | --- | --- |
| Fertile Land | Produces 3 grain | 3, 9, 15, 21 |
| Plain | Produces 2 grain | Remaining from 1-24 |
| Barren Land | Produces 1 grain | 1, 5, 7, 11, 13, 17, 19, 23 |
