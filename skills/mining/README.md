# Mining

You can train Mining using `+mine [quantity] <ore>`, for example `+mine 10 coal`.

See [Mining Training](mining-training.md) and [Volcanic Mine](volcanic-mine.md)

The bot uses XP rates based off rune pickaxe as standard; however, you can get one of the following boosts to mining output from owning these items:

| Item                   | Requirement | Speed boost                 |
| ---------------------- | ----------- | --------------------------- |
| Gilded Pickaxe         | 41 Mining   | 11%                         |
| Dragon pickaxe         | 61 Mining   | 6%                          |
| Infernal pickaxe       | 61 Mining   | 6%                          |
| Crystal pickaxe        | 71 Mining   | 11%                         |
| Mining gloves          |             | 2%                          |
| Superior mining gloves |             | 4%                          |
| Expert mining gloves   |             | 6%                          |
| Amulet of glory        |             | 50% (on gem rocks **only**) |

| Item              | XP boost | Golden nugget cost |
| ----------------- | -------- | ------------------ |
| Prospector helmet | 0.4%     | 40                 |
| Prospector jacket | 0.8%     | 60                 |
| Prospector legs   | 0.6%     | 50                 |
| Prospector boots  | 0.2%     | 30                 |
| **Complete set:** | **2.5%** | **180**            |

## Golden Nuggets & Unidentified Minerals

Some [ores](./#ores) reward you with golden nuggets or unidentified minerals. You can use nuggets to buy the prospector outfit and minerals to buy the three mining gloves, this is done via the `+buy` command.

The amount of golden nuggets or unidentified minerals rewarded is based in the total trip time. The amount received is a randomly selected number between 0 and the total trip time divided by 4, floored/rounded down.

$$
⌊\frac{tripTime}{4}⌋=maxAmount
$$

For example, a trip of 30 minutes will award between 0 and 7 golden nuggets or unidentified minerals.

## Ores

| **Ore Name**   | **Nuggets** | **Minerals** | **Required level** | Experience | XP/Hr. @ 99 |
| -------------- | :---------: | :----------: | :----------------: | ---------- | ----------- |
| Rune essence   |             |              |          1         | 5          | 10,288      |
| Copper ore     |             |              |          1         | 17.5       | 26,881      |
| Tin ore        |             |              |          1         | 17.5       | 26,881      |
| Saltpetre      |             |              |          1         |            |             |
| Iron ore       |             |       ✔      |         15         | 35         | 50,332      |
| Silver ore     |             |              |         20         | 40         | 22,454      |
| Volcanic ash   |             |              |         22         |            |             |
| Pure essence   |             |              |         30         | 5          | 10,288      |
| Coal           |             |       ✔      |         30         | 50         | 31,644      |
| Gold ore       |      ✔      |              |         40         | 65         | 36,556      |
| Gem rock       |             |              |         40         |            |             |
| Mithril ore    |      ✔      |              |         55         | 80         | 17,231      |
| Adamantite ore |      ✔      |              |         70         | 95         | 12,654      |
| Runite ore     |      ✔      |              |         85         | 125        | 6,731       |
| Amethyst       |             |       ✔      |         92         | 240        | 14,321      |
