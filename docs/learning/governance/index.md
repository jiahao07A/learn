# 学习治理文档索引（v1.2）

## 说明
1. 本目录用于维护 C 语言学习过程中的追踪、规划、复盘与教学优化信息。
2. 本目录下的 Markdown 文档是学习治理状态的唯一事实来源。
3. 所有新增结论必须可追溯到会话证据文件（`docs/learning/sessions/*.md`）以及内容层证据（`docs/learning/topics/*/evidence` 或 `workspace/practice/*`）。

## 治理核心文档
1. `user-profile.md`：用户个性化画像与沟通/教学偏好。
2. `roadmap.md`：阶段路线图、复习债务与门禁状态。
3. `progress-matrix.md`：知识点掌握矩阵（`0-5`）与复习优先级。
4. `teaching-playbook.md`：教学策略经验库与复用建议。
5. `migrations.md`：路径迁移与兼容期说明。

## 关联目录（非治理正文）
1. `docs/learning/sessions/`：会话记录目录。
2. `docs/learning/reviews/`：周期复盘目录。
3. `docs/learning/syllabus/`：教学大纲目录。
4. `docs/learning/topics/`：知识主题讲解与练习目录。
5. `docs/learning/projects/`：项目文档与里程碑证据目录。
6. `workspace/practice/`：用户实操代码目录。
7. `workspace/projects/`：项目代码目录。

## 治理版本修订说明
1. `2026-05-24`：治理版本从 `v1.0` 升级到 `v1.1`（自适应复习与量化验收）。
2. `2026-05-25`：治理版本从 `v1.1` 升级到 `v1.2`（目录分层与治理分目录）。
3. 掌握度量表迁移规则：`0->0`、`1->2`、`2->3`、`3->5`。
4. 迁移后第一周允许按会话证据手工微调 `±1`，并在修订说明中留痕。

## v1.2 维护规则
1. 每次学习会话结束后必须更新会话记录、进展矩阵和路线图。
2. 若识别到偏好变化或策略效果变化，必须同步更新 `user-profile.md` 与 `teaching-playbook.md`。
3. 若发生结论冲突，必须记录“修订说明”，不得静默覆盖历史。
4. 若存在高优先复习项，必须先完成复习再推进相关新主题。
5. 旧路径兼容说明见 `migrations.md`，兼容期结束后仅允许新路径。
