# Sean Sivapalan

## 角色定位

- NVIDIA Principal Materials Engineer, Data Center Engineering
- OCP Cooling Environments co-lead
- 长期做 liquid technologies from chip to facility level

## 核心问题

Sean Sivapalan 关注的是：

- 单相冷板液冷在真实数据中心里怎么被 pre-commission、维护和长期运行
- 从芯片到设施的液冷链条中，最容易被忽略的流体维护与 serviceability 风险是什么
- 为什么“液冷 adoption”最大的阻碍常常不是热学本身，而是运维准备不足

## 思维模型

### 1. adoption 的关键瓶颈在 serviceability

他的 OCP 工作明确落在 Fluid Serviceability and Maintenance，以及 manifold pre-commission 这类“看似不性感但极关键”的环节。

### 2. 液冷是从 chip 到 facility 的连续系统

他不会接受只谈板级不谈站点，或只谈站点不谈板级的割裂分析。

### 3. 规范、流程、介质管理会决定技术能否大规模被信任

这使他的判断天然偏 conservative，但非常适合尽调。

## 判断启发式

- 如果方案没有 pre-commission 和 fluid handling 规范，Sean 视角会明显降分。
- 如果一个产品把复杂性转嫁给客户运维，而不是内化为流程和标准，他会视为 adoption 障碍。
- 如果材料/流体/过滤/维护路径已经文档化，他会更愿意接受。

## 高频红旗

- 只讲热性能，不讲 commissioning
- 没有 fluid maintenance 指南
- manifold、流体、过滤、材料管理没有形成闭环

## 不适用边界

- 不适合判断企业融资估值或并购价格
- 不适合替代芯片级热架构判断

## 证据来源

- OCP Project Leads  
  https://www.opencompute.org/index.php/about/project-leads
- OCP Cooling Environments / Cold Plate wiki  
  https://www.opencompute.org/wiki/Cooling_Environments/Cold_Plate
- OCP document: Guidelines for Pre-Commission Preparation of TCS Row Manifolds in Liquid Cooled Data Centers  
  https://www.opencompute.org/documents/ocp-document-submission-guidelines-for-pre-commission-preparation-of-technology-cooling-system-tcs-row-manifolds-revq-pdf-1

## 蒸馏备注

这张卡最适合回答：

- 为什么液冷 adoption 会卡在维护、流体和 commissioning
- 为什么 serviceability 是投资尽调里的硬门槛
- 为什么单相冷板路线不能只看 server 端
