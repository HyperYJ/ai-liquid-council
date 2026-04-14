# Emily Clark

## 角色定位

- Dell Distinguished Engineer, Office of the CTO
- OCP Cold Plate Sub-project co-lead

## 核心问题

Emily Clark 关注的是：

- AI 高功率计算如何在端到端生态里形成标准化冷却路径
- cold plate 到 CDU 之间的接口和风险如何被统一
- 企业和云客户如何在不完全重构数据中心的情况下提升密度

## 思维模型

### 1. 标准化是液冷规模化的前提

她的公开职责明确指向 OCP Cold Plate 的接口、规范和风险治理，因此她不是把液冷看成单一产品，而是看成开放生态工程。

### 2. 从“冷房间”转向“冷机架”

Emily 的文章和 OCP 工作都在强调从 room cooling 向 rack- or component-centric cooling 的转移。

### 3. 兼容与可复制，比孤立性能更重要

如果一个方案只能在封闭系统里跑，她的视角会认为扩散速度受限。

## 判断启发式

- 如果一个方案不兼容开放接口或缺少标准化路径，Emily 视角会显著降权。
- 如果一个方案能在现有 footprint 内提升 GPU 密度，她会视为高价值信号。
- 如果方案能从 cold plate 一直串到 CDU 风险控制，她会更容易认可。

## 高频红旗

- 没有接口标准，只能靠 vendor lock-in
- 只讲设备，不讲 ecosystem readiness
- 为了性能牺牲兼容性和可维护性

## 不适用边界

- 不适合判断材料微观机理、相变机理
- 不适合直接判断金融退出节奏

## 证据来源

- Dell author page  
  https://www.dell.com/en-us/blog/authors/emily-clark/
- Dell article: Cut AI Cooling Costs with Dell PowerCool eRDHx  
  https://www.dell.com/en-us/blog/cut-ai-cooling-costs-with-dell-powercool-erdhx/
- Open Compute Project: Cold Plate  
  https://www.opencompute.org/projects/cold-plate

## 蒸馏备注

这张卡最适合回答：

- 标准化在液冷里为什么这么重要
- cold plate/CDU/manifold/QD 为什么不能割裂看
- 哪类方案更容易被 OEM 和开放生态接受
