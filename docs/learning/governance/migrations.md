# 路径迁移说明（v1.2）

## 迁移背景
1. 自 `2026-05-25` 起，学习体系从“单层 learning 目录”升级为“治理层 + 内容层”双层结构。
2. 治理文档统一迁移至 `docs/learning/governance`。

## 旧路径到新路径映射
1. `docs/learning/index.md` -> `docs/learning/governance/index.md`
2. `docs/learning/roadmap.md` -> `docs/learning/governance/roadmap.md`
3. `docs/learning/progress-matrix.md` -> `docs/learning/governance/progress-matrix.md`
4. `docs/learning/user-profile.md` -> `docs/learning/governance/user-profile.md`
5. `docs/learning/teaching-playbook.md` -> `docs/learning/governance/teaching-playbook.md`

## 兼容窗口
1. 兼容期为 `2026-05-25` 至 `2026-06-01`（一周）。
2. 兼容期内允许在说明文档中引用旧路径，但所有新增更新必须写入新路径。
3. 兼容期结束后，旧路径引用视为无效，应全部清理。

## 验收项
1. `AGENTS.md` 中全部治理文档引用已切换到 `docs/learning/governance`。
2. 会前必读路径已切换为新治理目录。
3. 会话证据引用可追溯到 `topics/.../evidence` 或 `workspace/practice/...`。
