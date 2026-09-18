# creative_beverage_design

> A general-purpose SKILL for designing creative, visually appealing, and genuinely enjoyable beverages across alcoholic, zero-alcohol, tea, milk tea, fruit tea, yogurt, coffee, cocoa, sparkling, frozen, dessert, and hot-drink categories.
> 通用创意饮品设计SKILL，覆盖酒精、0酒精、茶饮、奶茶、果茶、优酪乳、咖啡、可可、气泡、冰沙、甜品饮与热饮。

## Current｜当前状态

**Type:** `SKILL`
**Status:** `Current / Developing`
**Visibility:** `Private`
**Current Confirmed:** `2026-09-18`

当前仓库保存：

* `README.md`：项目说明与成长记录
* `SKILL.md`：执行规范

---

## 念头｜First Thought

**2026-09-17**

最初只是一个很日常的用法：

> 把没喝完、没那么好喝的饮料交给AI，让它重新设计成一个更好喝、更好看、也更有意思的版本。

当时它还只是一次次临时对话，没有被当作一个正式、可复用的方法。

---

## 起点｜Origin

**2026-09-17**

鱼头老师看到这个用法之后说了一句：

> “搞个Skill吧。”

这句话让我第一次认真去想：原来平时和AI一起做饮品设计的过程，可以被整理成一个真正可复用、可调用的SKILL。

同一天开始把原本零散的做法整理成规则，并完成第一个可工作版本。

这是我真正开始制作的第一个SKILL。

---

## 灵感与致谢｜Inspiration & Acknowledgements

特别感谢鱼头老师。

那天我只是随口分享，我会把没喝完、没那么好喝的饮料丢给AI，让它帮我重新设计。鱼头老师看完后说了一句「搞个Skill吧」，然后默默「坐蹲」。

就是这个很小的推动，让我第一次把自己已经在做的AI协作方法看成一个可以被整理、复用与发布的东西。

Special thanks to 鱼头老师. A casual conversation about using AI to redesign unfinished or disappointing drinks led to one simple suggestion: “搞个 Skill 吧.” That small nudge turned an everyday workflow into my first hands-on reusable SKILL project.

---

## Purpose｜它现在是什么

这个SKILL的目标是：

> **围绕一个明确的主材料，设计一杯同时满足creative + visually appealing + delicious的完整饮品。**

三项同等优先：

```text
creativity = appearance = taste
```

它覆盖：

* beverage formulation
* flavor design
* visual design
* texture and temperature design
* ingredient compatibility
* preparation and serving method
* real-time adjustment

它不负责：

* drink-card graphics
* image generation
* branding
* promotional layout

这些应交给独立的视觉或图卡SKILL。

---

## 核心原则｜Core Principle

**The main ingredient defines the beverage's identity. Supporting ingredients exist to serve it.**

不要为了「把手头所有东西都用掉」而强迫材料进入同一杯饮品。

如果某个材料会破坏：

* flavor balance
* color
* texture
* aroma
* stability
* visual clarity

就应该省略。

---

## 设计范围｜Design Scope

当前`SKILL.md`把饮品设计拆成三个独立轴：

1. **Alcohol Mode**
2. **Beverage Family**
3. **Serve State**

支持的饮品家族包括：

* Tea-Based
* Dairy / Plant-Milk Based
* Yogurt / Cultured
* Fruit-Based
* Coffee / Cocoa
* Frozen / Dessert Beverage
* Sparkling
* Hybrid

Serve State包括：

* Hot / Warm
* Chilled / Iced
* Frozen / Blended
* Temperature Contrast

同时覆盖：

* Flavor Design
* Visual Design
* Layering / Gradient
* Texture Design
* Experimental Mode
* Real-Time Adjustment

完整执行规则以`SKILL.md`为准。

---

## 时间线｜Timeline

* **2026-09-17｜念头与起点**：从「把没喝完、没那么好喝的饮料交给AI重新设计」这个日常用法出发；鱼头老师提出「搞个Skill吧」后，第一次把这套协作方法正式整理成可复用SKILL。
* **2026-09-17｜第一版可工作SKILL**：把原本散落在对话中的饮品设计方法整理成第一版执行规则。
* **2026-09-18｜结构整理**：统一命名、README、SKILL职责与Private状态。
* **2026-09-18｜执行范围扩展**：从原先偏cocktail / mocktail的结构扩展到更多beverage families、serve states、texture design与worked examples。
* **2026-09-18｜镜像规则确认**：GitHub与OB开源库不再作为两份独立版本维护，统一视为同一个Current的镜像。

> Timeline记录真正改变SKILL定义、范围或维护方式的节点，不记录每次小措辞调整。

---

## 成长轨迹｜Evolution

### 日常对话→可复用SKILL

**日期：2026-09-17**

最初的价值并不在于某一杯具体饮料，而在于背后的重复方法：

* 先找主材料
* 判断酒精 / 0酒精
* 做味道结构
* 同时设计视觉
* 根据手头库存调整
* 实做过程中继续短步修正

当这些步骤被提取出来以后，它才从「一次聊天」变成真正可以反复调用的执行协议。

### 第一版→更完整的饮品系统

**日期：2026-09-18**

Current继续把原先偏cocktail / mocktail的结构扩展到：

* 茶饮
* 奶茶
* 果茶
* 优酪乳
* 咖啡
* 可可
* 气泡饮
* 冰沙 / Frozen
* 甜品饮
* 热饮
* 多种Hybrid

同时把「温度、质地、气泡、分层稳定性」从附带考虑提升为正式设计维度。

---

## 如何使用｜How to Use

执行饮品设计时，以`SKILL.md`中的规则为准。

`README.md`负责说明：

* 这个SKILL是什么
* 它为什么出现
* 它经历了哪些重要变化
* 当前发展到哪里

`SKILL.md`负责：

* 实际执行规则
* 设计流程
* Guardrails
* Worked Examples
* 默认输出结构

GitHub与OB开源库中的对应文件应保持相同内容。

如果未来两端出现差异：

> **先确认Current，再把同一份Current同步到两端，而不是分别修改。**

---

## Default Output

当前SKILL的默认输出顺序：

1. **Beverage name**
2. **One-line concept**
3. **Mode / family / serve state**
4. **Recipe**
5. **Method**
6. **Glass / cup / ice / garnish**
7. **Design rationale**
8. **Adjustment guide**

完整规则、Worked Examples与Guardrails请查看`SKILL.md`。

---

## 下一步｜Next

* [x] 明确`README.md`与`SKILL.md`职责
* [x] 扩展完整饮品设计范围
* [x] 清除个人Drive路径、File ID等内部基础设施信息
* [x] GitHub与OB开源库统一为同一个Current
* [ ] 只有明确决定公开时，才把当前Private状态改为Public

---

## Publication Notes

**Current Visibility:** Private

这个SKILL可以继续发展，也可以在未来发布。

但：

> **可发布 ≠ 当前已经公开。**

目前保持Private。

若未来明确转为Public，再进行公开版本所需的来源、说明与发布检查。
