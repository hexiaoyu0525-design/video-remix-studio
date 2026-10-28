# Video Remix Studio — 爆款视频复刻导演流水线

以一条参考爆款视频为起点，克隆 / 复刻 / 翻拍 / 改编成自己版本的全流程导演方法论：**立项（BRIEF）→ 拆参考（ANALYSIS / TIMELINE）→ 改编导演案（TREATMENT）→ 脚本与时间（SCRIPT）→ 素材生产 → 合成与审片**。

**覆盖形态**：口播、盘点排行、短剧、街头采访、双人播客、讲解演示、旁白带货。

## 特点

- **方法论与生成平台解耦**：SKILL.md 与 references 只提"角色"（图生视频、配音、剪辑……），具体工具名只写在 `references/00-tool-adapters.md`；换 agent / 换平台只改这一份适配层，方法论不动。
- **六阶段流水线 + 阶段门**：按顺序推进，每阶段有产出物和"进入下一阶段的门槛"，没到门槛不生成；任何耗额度/付费生成前先向用户出示素材清单取得同意。
- **文件即记忆**：每项目五份标准文档（BRIEF / TREATMENT / SCRIPT / ANALYSIS / TIMELINE）+ 五份模板（`assets/templates/`），参考事实与新片事实严格分开。
- **与 `fashion-studio` 配套**（同作者、同许可）：时尚 / 高定大片类的克隆，生图美学与人物比例以 fashion-studio 为准，本技能负责导演流水线与跨素材编排。

## 安装

- `npx skills add <你的GitHub用户名>/video-remix-studio`，或
- 手动把 `video-remix-studio` 文件夹放进该 Agent 的 skills 目录。

## 许可

CC BY-NC 4.0（署名—非商业性使用），作者：hexiaoyu0525-design，详见 [LICENSE](LICENSE)。
