# AI Liquid Council

An AI data center liquid cooling evaluation skill with expert-distilled reasoning cards.

`AI Liquid Council` 是一个面向 `AI 数据中心液冷` 场景的单入口 skill，用来回答液冷专属问题，并对液冷项目、公司和技术路线做统一评估。

它适合小基金、产业研究者、技术尽调人员、设施侧从业者把复杂问题拆成一套更有依据的判断流程。

## 它解决什么问题

这个 skill 主要解决两类问题：

1. 液冷专属问题
2. 液冷项目/公司的综合评估

典型问题包括：

- 某家液冷公司值不值得进入观察池
- 冷板、CDU、manifold、QD 这类部件有没有真实壁垒
- `direct-to-chip` 和 `immersion` 分别适合什么场景
- 某个方案更适合新建机房还是 retrofit
- 一家液冷公司更像部件标的、系统标的还是并购标的

## 核心特点

### 1. 单入口，总控收口

所有 `项目评估`、`项目比较`、`推进建议`、`观察池判断` 都由这一个 skill 统一负责，不会把结论拆散在多个独立 skill 里。

### 2. 底层是“人物蒸馏”，不是名单堆砌

这个 skill 不是简单引用专家名字，而是把 8 位核心专家的判断方式蒸馏成专家卡，再在回答时转成可执行的分析语言。

每张专家卡包含：

- 思维模型
- 判断启发式
- 高频红旗
- 不适用边界
- 证据来源

### 3. 评分只是辅助，剖析才是核心

这个 skill 可以附带评分卡，但分数不是主结论。默认会先给文字判断、依据、证据和红旗，再在必要时补充排序或分数。

### 4. 输出稳定

每次回答默认分成两部分：

- `总结`
- `详细`

复杂问题会进一步展开成：

- 分模式判断
- 共识与分歧
- 评分卡
- 行动清单

## 四个内部模式

### 技术尽调

关注：

- 冷板、CDU、manifold、QD、流体回路
- GPU 热边界、机柜密度、可维护性
- `direct-to-chip` 与 `immersion` 的工程现实性

### 设施落地

关注：

- 新建 vs retrofit
- 园区级部署、停机窗口、BMS/消防/楼板等现场约束
- 服务体系、维护和规模化复制能力

### 深科技验证

关注：

- 两相/相变路线是否真有物理优势
- 工质、材料兼容、寿命、可靠性
- 专利护城河与可制造性

### 投资退出

关注：

- 该不该投
- 公司在价值链哪一层
- 下一轮谁来接
- 谁可能成为并购方

## 底层专家蒸馏层

当前蒸馏层覆盖 8 位专家：

### 技术尽调组

- Dave Klusas
- Mark Steinke
- Emily Clark
- Sean Sivapalan

### 设施落地组

- Suresh Pichai
- Jason Zeiler

### 深科技验证组

- Mehmet Arik
- Xiaolei Yuan

这些卡片的作用不是“引用权威”，而是帮助形成更稳定的判断骨架。

## 仓库结构

```text
.
├── README.md
├── SKILL.md
└── references/
    ├── usage-zh.md
    └── experts/
        ├── 00-expert-index.md
        ├── 01-dave-klusas.md
        ├── 02-mark-steinke.md
        ├── 03-emily-clark.md
        ├── 04-sean-sivapalan.md
        ├── 05-suresh-pichai.md
        ├── 06-jason-zeiler.md
        ├── 07-mehmet-arik.md
        └── 08-xiaolei-yuan.md
```

## 如何使用

如果你是在本地 skills 环境里使用它：

1. 把这个目录放到你的 skills 目录中
2. 让 agent 读取 `SKILL.md`
3. 直接提问

推荐提问方式：

- 用 `ai-liquid-council` 看一下这家公司值不值得进观察池
- 只用技术尽调模式，拆一下这家冷板公司的真实壁垒
- 只用设施落地模式，判断这个方案适不适合 retrofit
- 用综合评估模式比较 A、B 两家液冷公司
- 带评分卡，把这 3 个项目排一下优先级

如果你只是想快速理解这套 skill，先读：

- `README.md`
- `references/usage-zh.md`
- `SKILL.md`

## 适用边界

这个 skill 专注在：

- `AI 数据中心液冷`
- `AI 工厂 / GPU 集群 / 高密度机柜`
- `技术尽调 / 设施落地 / 深科技验证 / 投资退出`

它不适合直接回答：

- 泛数据中心 REIT 或 IDC 估值
- 泛 HVAC 行业研究
- 光互连、CPO、光交换主赛道判断
- 与 AI 数据中心液冷无关的普通工业热管理问题

## 方法论说明

这套 skill 建立在公开资料、论文、机构动作和专家公开角色之上，属于“结构化蒸馏”框架。

它的目标是：

- 提高问题拆解质量
- 让结论更有证据约束
- 减少只看概念热度、不看部署现实和退出路径的误判

它不等于这些专家本人受雇参与，也不等于内部访谈结论。

## 中文使用说明

更完整的中文使用说明见：

- [references/usage-zh.md](references/usage-zh.md)
