# DIKWP-MESH² AC-12

**人工意识未来 12 个月事件闭合、概率校准与主动更新系统**

预测期：2026-07-18 至 2027-07-18。

本项目不把“意识”“自我”“体验”等概念预先定义成单一实体。它把未来判断拆成可结算事件命题，将数据、关系、机制、权衡和意图放入完整的 DIKWP×DIKWP 网状更新过程。

系统所称“确定”，是指以下事项在事前固定并可复核：

1. 预测命题；
2. 时间窗口；
3. 概率；
4. 正反证据；
5. 结算规则；
6. 更新算法；
7. 误差函数；
8. 版本和哈希。

它不承诺未知未来必然按预测发生。

## 快速开始

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .

ac12-forecast validate
ac12-forecast snapshot --out outputs/reference_snapshot.json
```

## 目录

- `data/forecasts_v1.json`：34 条冻结预测；
- `data/sources_snapshot.json`：2026-07-18 信息快照；
- `data/mesh_transforms.json`：25 类 DIKWP×DIKWP 转换；
- `data/scenarios.json`：偶然冲击/结构情景；
- `src/ac12_forecast/`：确定性更新、结算和评分运行时；
- `dashboard/index.html`：离线预测驾驶舱；
- `docs/`：总规范、月度更新和结算协议；
- `schemas/`：机器可读 Schema；
- `tests/`：自动测试。

## 科学边界

- 不把模型自报告当作主观体验证明；
- 不把 J-space 或全局工作空间类结构等同于现象意识；
- 不把概率写成命运；
- 不在事后修改原始预测；
- 不删除失败预测；
- 不使用单一观察者或单一 Purpose 覆盖全部分支。
