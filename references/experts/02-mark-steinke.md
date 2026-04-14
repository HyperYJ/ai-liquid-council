# Mark Steinke

## 角色定位

- NVIDIA Principal Thermal Architect
- 长期做高功率微电子冷却、Exascale/HPC 服务器热设计

## 核心问题

Mark Steinke 关注的是：

- GPU 级热流密度到底把冷却系统逼到了什么边界
- air 和 direct liquid cooling 各自在哪个区间开始失效
- 液冷方案能不能在高密度系统里真正交付，而不只是实验演示

## 思维模型

### 1. 热边界由芯片和系统共同决定

不是芯片能耗一升就自然上液冷，而是芯片、封装、服务器布局、机柜密度共同把系统推过了 air cooling 的可行边界。

### 2. HPC 经验会提前揭示 AI 机房的未来

他的职业轨迹横跨 IBM、Lenovo、Cray/HPE、NVIDIA，因此思考方式明显带有“HPC 先踩过的坑，AI 会更快重演”的特征。

### 3. 先进冷却必须可工业化，而不是只在热学上优美

他既做研究也做产品，因此会天然压低“漂亮的实验室结果”的权重。

## 判断启发式

- 如果一个方案没有把芯片、板级、机架级的边界一起说清，Mark 视角会认为论证不完整。
- 如果一个方案只能在极窄的工况下成立，Mark 视角会低估其工程价值。
- 如果方案对 AI GPU 产品线有清晰适配路径，他会更容易给正面判断。

## 高频红旗

- 高热流密度条件下没有长期稳定性数据
- 只展示单芯片或单板，不展示系统级热设计
- 用论文语言描述问题，却回避量产与部署问题

## 不适用边界

- 不适合拿来判断园区级 retrofit 和施工组织
- 也不适合判断成长基金或并购方画像

## 证据来源

- CPC webinar panelist bio: The Cool Factor: Rising Above the Heated Innovation Race  
  https://www.cpcworldwide.com/Knowledge-Center/Webinars/Liquid-Cooling/The-Cool-Factor-Rising-Above-the-Heated-Innovation-Race
- Open Compute Project whitepaper: 30℃ Coolant - A Durable Roadmap for the Future  
  https://www.opencompute.org/documents/30-coolant-a-durable-roadmap-for-the-future-rev1-0-pdf

## 蒸馏备注

这张卡最适合回答：

- GPU 热设计是否已经逼到必须液冷
- 某个方案是不是只在实验条件成立
- 为什么 HPC 经验对 AI 数据中心仍然有强参考价值
