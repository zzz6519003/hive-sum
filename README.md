# 蜂巢点算

把一点到三点放进六角格，让每条箭头上的和数刚好成立。

这是一款原创的六角求和解谜。四界、三十二盘，进度存在你自己的浏览器里。

**直接玩：** 打开本仓库根目录的 [index.html](./index.html)。若已开启 GitHub Pages，地址是 <https://zzz6519003.github.io/hive-sum/>。

## 怎么玩

- 点按空格，在一点、两点、三点之间轮换，再点一次清空。右键可往回减。
- 箭头里的数字，是那条直线上所有点数之和。刚好时箭头变玉色，超出则变朱色。
- 斜纹石格已经刻好，不能改。同色描边的格子绑在同一根丝线上，改一个，其余一起变。
- 两格之间的 `<`、`>`、`=` 也要成立。每条线都成立，且没有空格，这一盘才算点齐。

## 四界

| 界 | 规则 |
| --- | --- |
| 晨露 | 直线上的点数之和要等于箭头 |
| 石刻 | 斜纹石格已经刻好，不能更改 |
| 丝线 | 同色描边的格子，数字永远相同 |
| 天平 | 格与格之间的 `<` `>` `=` 也要成立 |

每界 8 盘，由浅入深。

## 操作

- 撤销、重开、提示（每盘最多三次）、静音，都在盘面旁边。
- 进度、未完成的草稿和提示次数保存在本机，换浏览器或清掉站点数据会从头开始。

---

# Hive Sum

Place one, two, or three dots in each hex so every arrow line adds up.

An original hex-sum puzzle: four realms, thirty-two boards. Progress stays in your browser.

**Play:** open [index.html](./index.html) at the repository root. With GitHub Pages enabled, the address is <https://zzz6519003.github.io/hive-sum/>.

## How to play

- Tap a cell to cycle through one, two, and three dots, then empty. Right-click steps backward.
- The number in an arrow is the sum of every dot on that straight line. The arrow turns jade when the sum is exact, and cinnabar when it goes over.
- Hatched stone cells are already carved and cannot change. Cells with the same colored rim share one thread: change one, and the rest follow.
- Comparisons between two cells (`<`, `>`, `=`) must hold as well. The board is clear only when every line holds and no cell is empty.

## Four realms

| Realm | Rule |
| --- | --- |
| Morning Dew (晨露) | Dots on a line must equal the arrow |
| Stone (石刻) | Hatched cells are fixed |
| Thread (丝线) | Cells with the same rim always share a number |
| Balance (天平) | The `<` `>` `=` marks between cells must hold |

Eight boards in each realm, from small to dense.

## Controls

- Undo, restart, hint (three per board), and mute sit beside the board.
- Progress, unfinished drafts, and hint counts are stored on this device. Another browser, or clearing site data, starts you over.
