# DESERT 5000｜荒漠世界证据库

这是第32期「AI向善万物创新工作坊 × X星球实验室」下午环节使用的 GitHub 世界资料库。

## 这不是一个游戏答案库

这个仓库提供：

- 真实新闻与治沙案例资料
- 毛乌素沙地的基础气候、水、土壤与植被资料
- 若干课堂模拟数据
- 一个简化的“5000美元模拟预算”行动菜单
- 给 AI Agent / Codex 使用的建模模板
- 给 DeepSeek 世界引擎使用的接口模板

这个仓库**不会告诉学生哪一种治沙方案最好**。

学生的任务是：

1. 指挥 WorkBuddy / Trae Work 读取这个仓库；
2. 区分真实事实、课堂模拟假设和未知信息；
3. 提出自己真正想研究的荒漠问题；
4. 决定自己的荒漠世界要包含哪些变量；
5. 指挥 WorkBuddy / Trae Work 创建自己的 DESERT 5000 模拟系统；
6. 模拟5年、10年、20年后的可能变化；
7. 可选：接入 DeepSeek API，让AI成为隐藏的世界引擎；
8. 根据模拟结果修改模型和决策。

---

## 建议 Agent 阅读顺序

1. `01_MISSION.md`
2. `02_AGENT_README.md`
3. `knowledge/yin_yuzhen_case.md`
4. `knowledge/maowusu_science_notes.md`
5. `knowledge/government_and_society.md`
6. `data/classroom_site.json`
7. `data/climate_history_sample.csv`
8. `data/species_reference.csv`
9. `data/intervention_menu.csv`
10. `templates/model_design.json`
11. `templates/deepseek_world_engine_prompt.md`
12. `templates/simulation_output.schema.json`

---

## 最重要的边界

仓库中有两种资料：

### A. 真实世界资料
来自新华社、国家林业和草原局、中国科学院及公开学术资料。

### B. 课堂模拟资料
例如：

- 100英亩虚拟地块
- 5000美元模拟预算
- 各行动的模拟价格
- A/B/C/D 四个虚拟区域

这些内容**不是殷玉珍真实地块、真实历史价格或真实工程预算**，只是为了让孩子在两小时课程中能够完成建模实验。

请 Agent 在任何分析中明确区分 A 和 B。

---

## 课堂核心问题

> 同样面对5000美元模拟预算和一片荒漠，
> 为什么不同的模型、不同的判断，会产生完全不同的5年、10年、20年未来？

---

## 课堂工具分工

### 学生
主要使用：
- WorkBuddy
- Trae Work

用于读取资料、研究、建模与创造模拟系统。

### 导师
可使用：
- VS Code + Codex

用于导师样机、技术排错、检查模型结构和现场兜底。

### DeepSeek API
属于可选升级模块。
它不是学生研究 Agent，而是可以被学生创建的模拟系统调用的“世界引擎”。
