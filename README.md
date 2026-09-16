# Logo Concept Lab

一个面向 Logo 创意发散与字母图形设计的 AI Agent skill。将参考学习、业务语义、共形／负形构思、视觉筛选和 Figma 交付连接起来。

适合：新品牌 Logo 构思、参考视频方法拆解、两字母 Monogram、多方向视觉测试，以及“设计感不足”后的重新发散。

## 核心能力

- 从参考中提取构形方法，而不是复制成品。
- 用共用轮廓、负空间、局部替换与笔画重组建立双重含义。
- 支持指定字母的纯图形测试，尊重“不加字标／不展示文字”的要求。
- 用黑白轮廓、光学平衡和缩小识别筛选，而非依赖样机包装。
- 支持 Figma 可编辑矢量交付，并要求回读与渲染验证。

## 安装到 Codex

将此仓库下载到本地，把含有 `SKILL.md` 的目录复制为：

```text
~/.codex/skills/logo-concept-lab/SKILL.md
```

如果设置了自定义 `CODEX_HOME`，使用其下的 `skills/logo-concept-lab` 目录。已有同名 skill 时先比较内容，再决定替换。

也可以直接克隆到尚不存在的目标目录：

```sh
git clone https://github.com/AIGC-Xavier/logo-concept-skill.git ~/.codex/skills/logo-concept-lab
```

在支持本地 `SKILL.md` 的其他 Agent 中，按相应产品的技能目录约定安装。

## 使用示例

```text
使用 $logo-concept-lab，根据品牌官网与这些参考，为品牌做一轮 Logo 构思。
重点找共用轮廓和负形关系，把值得保留的方向放入指定 Figma 文件。
```

```text
使用 $logo-concept-lab，以 L、X 两个字母做一轮图形测试。
不要另外展示文字、标题或编号；只比较黑白图形。
```

```text
使用 $logo-concept-lab，检查现有方案为什么缺少设计感。
保留已选方向，调整交叉关系和视觉重心，不要重新扩展整套品牌。
```

## LX 构形测试示例

![LX 六方向构思测试](examples-lx.png)

示例为探索稿，用于展示构形比较与纯图形排版；不代表已定稿、生产验证或商标近似检索结论。

## 工具与范围

skill 本身是方法指令，不附带 Figma 连接器或图像生成服务。相关工具可用且用户任务需要时再使用；没有 Figma 编辑工具时，应交付本地文件并说明尚未同步。

仓库发布的是本次工作中整理的方法与测试示例，不包含参考视频、视频截图、客户官网资料或私人 Figma 地址。
