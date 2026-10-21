# Spellivery 魔法外送

### ▶ [玩 Spellivery 魔法外送 · Play Spellivery](https://rolanthhuang.github.io/spellivery/)

`https://rolanthhuang.github.io/spellivery/` · 手機、電腦都能直接玩 · Works on phone and desktop

A jet-powered delivery car, a crooked magic academy, and five hungry customers.
Fly bubble tea, chicken cutlets and stinky tofu across Crookspire Academy before the food gets cold.

你開著噴射外送車，在一座歪七扭八的魔法學院送珍奶、雞排、臭豆腐。餐要熱，塔別撞。

**Play:** [rolanthhuang.github.io/spellivery](https://rolanthhuang.github.io/spellivery/), or download `index.html` and open it in a browser.

## How to play 玩法

| | Desktop 電腦 | Phone 手機 |
|---|---|---|
| Steer and climb 轉向與升降 | WASD / arrow keys | Drag on the left half of the screen |
| Boost 推進 | Space | BOOST button |
| Brake 減速 | Shift | BRAKE button |
| Camera 換鏡頭 | C | Camera button |
| Hide HUD for recording 隱藏介面錄影 | H | Eye button |
| Pause 暫停 | P / Esc | Pause button |

- A shift has 5 orders: pick up at the shop (gold beacon), deliver to the customer (cyan beacon).
- Late or crashed deliveries cost stars. Blue rune rings recharge the battery.
- Three original jet cars in the garage: Comet GT, Atomic '58, Bao Van.
- Lines are voiced with the browser's built-in speech; Chinese subtitles are shown under every line.

一班 5 張單：先到金色光柱取餐，再送到藍色光柱。遲到或撞車會扣星，穿過藍色符文環可以充電。車庫有三台原創噴射車可以換。

## Tech

- Single self-contained `index.html`; the 3D engine ([three.js](https://threejs.org) r160, MIT) loads from jsDelivr.
- Graphics quality adapts to the device automatically (resolution scaling plus Low/Medium/High presets in the menu).
- Everything else (terrain, castle, cars, sound, music) is generated in code. No image or audio files.

An original parody game. Not affiliated with any film, book, or car maker.
