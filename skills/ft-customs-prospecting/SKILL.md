---
name: ft-customs-prospecting
description: 当用户提供授权海关企业明细、外贸通访问条件或品类国家时间窗口时使用。
compatibility: Requires DesireCore 10.0.203+, user-configured model service and applicable external accounts, permissions and terms. Separate costs may apply; unavailable dependencies stop related calls.
license: MIT
metadata:
  version: "0.1.0"
---

# ft-customs-prospecting

先阅读[外贸工作约定](../../references/team-work.md)。

确认数据许可、覆盖国家/时段、更新延迟、HS分类粒度及导入字段；大类名称不直接当准确HS编码。先聚合再按主体和可验证企业交易筛选，进口记录不等当前采购意向。公开宏观统计只做市场判断；缺企业许可停止企业级检索并给接入清单。不得绕付费墙、伪造交易或自动对陌生企业发送。

## 交付与缺口

返回实际产物、来源、已执行动作与回执、未知和待本人处理条件。账号、模型、数据源、素材/软件许可和服务费用由安装者提供；不包含第三方服务。缺少依赖时只交付可完成的草稿，不虚构执行。
