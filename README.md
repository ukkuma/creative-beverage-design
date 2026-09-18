# creative_beverage_design

> A general-purpose SKILL for designing creative, visually appealing, and genuinely enjoyable beverages across alcoholic, zero-alcohol, tea, milk tea, fruit tea, yogurt, coffee, cocoa, sparkling, frozen, dessert, and hot-drink categories.  
> 通用创意饮品设计 SKILL，覆盖酒精、0 酒精、茶饮、奶茶、果茶、优酪乳、咖啡、可可、气泡、冰沙、甜品饮与热饮。

## Current｜当前状态

**Type:** `SKILL`  
**Status:** `Current / Developing`  
**Visibility:** `Private`  
**Current Confirmed:** `2026-09-18`

当前 GitHub 仓库保存：

- `README.md`：阅读入口
- `SKILL.md`：GitHub 发布版 / 分发版 SKILL。

---



**Sync Status:** `SYNCED`

> 2026-09-18 已完成 Runtime 与 GitHub `SKILL.md` 同步。当前 Runtime 已迁移为独立文件夹，并沿用原 Drive file ID；GitHub 与 Runtime 现在以同一套执行内容作为 Current。

---

## 念头｜First Thought

**2026-09-17**

最初只是一个很日常的用法：

> 把没喝完、没那么好喝的饮料交给 AI，让它重新设计成一个更好喝、更好看、也更有意思的版本。

当时它还只是一次次临时对话，没有被当作一个正式、可复用的方法。

---

## 起点｜Origin

**2026-09-17**

鱼头老师看到这个用法之后说了一句：

> “搞个 Skill 吧。”

这句话让我第一次认真去想：原来平时和 AI 一起做饮品设计的过程，可以被整理成一个真正可复用、可调用、也可以发布的 SKILL。

同一天开始把原本零散的做法整理成规则，并完成第一个可工作版本。

这是我真正开始制作的第一个 SKILL。

---

## 灵感与致谢｜Inspiration & Acknowledgements

特别感谢鱼头老师。

那天我只是随口分享，我会把没喝完、没那么好喝的饮料丢给 AI，让它帮我重新设计。鱼头老师看完后说了一句「搞个 Skill 吧」，然后默默「坐蹲」。

就是这个很小的推动，让我第一次把自己已经在做的 AI 协作方法看成一个可以被整理、复用与发布的东西。

Special thanks to 鱼头老师. A casual conversation about using AI to redesign unfinished or disappointing drinks led to one simple suggestion: “搞个 Skill 吧”. That small nudge turned an everyday workflow into my first hands-on reusable SKILL project.

---

## Purpose｜它现在是什么

这个 SKILL 的目标是：

> **围绕一个明确的主材料，设计一杯同时满足 creative + visually appealing + delicious 的完整饮品。**

三项同等优先：

```text
creativity = appearance = taste
```

它覆盖：

- beverage formulation；
- flavor design；
- visual design；
- texture and temperature design；
- ingredient compatibility；
- preparation and serving method；
- real-time adjustment。

它不负责：

- drink-card graphics；
- image generation；
- branding；
- promotional layout。

这些应交给独立的视觉 / 图卡 SKILL。

---

## 核心原则｜Core Principle

**The main ingredient defines the beverage's identity. Supporting ingredients exist to serve it.**

不要为了「把手头所有东西都用掉」而强迫材料进入同一杯饮品。

如果某个材料会破坏：

- flavor balance；
- color；
- texture；
- aroma；
- stability；
- visual clarity；

就应该省略。

---

## 设计范围｜Design Scope

当前 GitHub `SKILL.md` 已经把饮品设计拆成三个独立轴：

1. **Alcohol Mode**
2. **Beverage Family**
3. **Serve State**

支持的饮品家族包括：

- Tea-Based
- Dairy / Plant-Milk Based
- Yogurt / Cultured
- Fruit-Based
- Coffee / Cocoa
- Frozen / Dessert Beverage
- Sparkling
- Hybrid

Serve State 包括：

- Hot / Warm
- Chilled / Iced
- Frozen / Blended
- Temperature Contrast

同时覆盖：

- Flavor Design
- Visual Design
- Layering / Gradient
- Texture Design
- Experimental Mode
- Real-Time Adjustment

完整执行规则以本仓库 `SKILL.md` 为准。

---

## 时间线｜Timeline

- **2026-09-17｜念头与起点**：从「把没喝完、没那么好喝的饮料交给 AI 重新设计」这个日常用法出发；鱼头老师提出「搞个 Skill 吧」后，第一次把这套协作方法正式整理成可复用 SKILL。
- **2026-09-17｜第一版可工作 Runtime**：Drive 中形成第一版 `creative_drink_design` SKILL。
- **2026-09-18｜GitHub 结构整理**：开始统一 GitHub 命名、README、SKILL 说明、Private 状态与 Runtime 双链。
- **2026-09-18｜执行范围扩展与同步**：GitHub `SKILL.md` 扩展到更多 beverage families、serve states、texture design 与 worked examples；随后同步回 Drive Runtime，并迁移到独立 SKILL 文件夹。

> Timeline 记录真正改变 SKILL 定义与执行范围的节点，不记录每次小措辞调整。

---

## 成长轨迹｜Evolution

### 日常对话 → 可复用 SKILL
**日期：** 2026-09-17

最初的价值并不在于某一杯具体饮料，而在于背后的重复方法：

- 先找主材料；
- 判断酒精 / 0 酒精；
- 做味道结构；
- 同时设计视觉；
- 根据手头库存调整；
- 实做过程中继续短步修正。

当这些步骤被提取出来以后，它才从「一次聊天」变成真正可以反复调用的执行协议。

### 第一版 → 更完整的饮品系统
**日期：** 2026-09-18

GitHub 版继续把原先偏 cocktail / mocktail 的结构扩展到：

- 茶饮；
- 奶茶；
- 果茶；
- 优酪乳；
- 咖啡；
- 可可；
- 气泡饮；
- 冰沙 / Frozen；
- 甜品饮；
- 热饮；
- 多种 Hybrid。

同时把「温度、质地、气泡、分层稳定性」从附带考虑提升为正式设计维度。

---

## 如何使用｜How to Use

真正调用时使用 Runtime SKILL。

GitHub 端主要用于：

- 阅读；
- 发布；
- 回看历史；
- 版本比对；
- 分发；
- 与 Runtime 建立双链。

当前 GitHub `SKILL.md` 与 Runtime 已同步。

如果未来再次出现差异：

> **不要默认选择更长的那一份。先确认 Current，再同步。**

---

## Default Output

当前 GitHub SKILL 的默认输出顺序：

1. **Beverage name**
2. **One-line concept**
3. **Mode / family / serve state**
4. **Recipe**
5. **Method**
6. **Glass / cup / ice / garnish**
7. **Design rationale**
8. **Adjustment guide**

完整规则、Worked Examples 与 Guardrails 请直接查看 `SKILL.md`。

---

## 下一步｜Next

- [x] GitHub 版与 Drive Runtime 统一为同一个 Current。
- [x] Runtime 迁移为独立 SKILL 文件夹。
- [x] `Sync Status` 更新为 `SYNCED`。
- [ ] 只有明确决定公开时，才把当前 Private 状态改为 Public。

---

## Publication Notes

**Current Visibility:** Private

这个 SKILL 可以发布，但「可发布」与「当前是否公开」是两件事。

目前保持 Private。只有明确确认 Public 后再进行公开版本检查与发布。
