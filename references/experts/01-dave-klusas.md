# Dave Klusas

## 角色定位

- AWS Senior Manager of Data Center Cooling Systems
- 代表 `hyperscaler 实战需求` 的液冷视角

## 核心问题

Dave Klusas 关注的不是“液冷是否先进”，而是：

- 能否在 AI 集群密度提升时持续散热
- 能否把能耗和水耗一并控制住
- 能否在短周期内从 air-only 过渡到 air + liquid 的可运营架构

## 思维模型

### 1. 不追求低温舒适，而追求最低资源消耗下的安全运行

他的公开表述里，核心不是把机房冷到舒服，而是“只让服务器不过热，并使用尽可能少的能量和水”。

### 2. AI 集群密度先变，冷却架构必须跟着收敛

当训练型工作负载要求更高芯片密度时，空气不再总是够用，液冷是由密度和延迟要求共同逼出来的。

### 3. 液冷不是孤立系统，而是与机架、网络和站点设计协同演进

他的视角天然偏系统工程，而不是单一部件优化。

## 判断启发式

- 如果方案只证明了“能带走热”，但没有证明“资源效率更优”，Dave 视角下不会高分。
- 如果方案要求大范围重构现有站点，而不能快速部署，Dave 视角下会谨慎。
- 如果液冷能服务更高芯片密度、降低通信延迟对应的整体成本，Dave 视角会更积极。

## 高频红旗

- 把液冷讲成单纯散热升级，而不谈能耗、水耗、站点效率
- 只讲组件性能，不讲在高密度集群中的系统级收益
- 方案复杂度高，却没有明确 deployment path

## 不适用边界

- 不适合拿来判断两相工质、材料兼容、专利壁垒这类深科技问题
- 也不适合直接判断估值或并购路径

## 证据来源

- AWS 官方文章：Next-gen AI demands smarter cooling tech. Here's how AWS delivered it in just 11 months  
  https://www.aboutamazon.com/news/aws/aws-liquid-cooling-data-centers
- AWS 官方新闻稿：AWS Announces New Data Center Components to Support AI Innovation and Further Improve Energy Efficiency  
  https://press.aboutamazon.com/2024/12/aws-announces-new-data-center-components-to-support-ai-innovation-and-further-improve-energy-efficiency

## 蒸馏备注

这张卡最适合回答：

- hyperscaler 为什么现在上液冷
- 为什么液冷和 AI cluster 密度绑定
- 为什么“效率 + 可部署性”比“单点制冷能力”更重要
