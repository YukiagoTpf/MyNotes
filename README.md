# MyNotes

这是一个以 Unity URP 渲染技术为主题的笔记仓库，当前主要收录屏幕空间阴影与屏幕空间环境光遮蔽（SSAO）相关的技术文档。

## 仓库内容

- `Unity/URP_ScreenSpaceShadows_技术分析.md`
  - 主题：URP `ScreenSpaceShadows` Renderer Feature 的实现机制与关键词切换流程。
  - 内容：模块职责、RenderGraph Pass 行为、Shader 路径、性能与风险、接入与验证建议。

- `Unity/URP SSAO 技术说明.md`
  - 主题：URP `ScreenSpaceAmbientOcclusion`（SSAO）方案的执行流程与算法细节。
  - 内容：Feature/Pass 结构、AO 估计与滤波、质量档位、参数影响链路、常见问题排查。

## 适合读者

- Unity 图形程序员
- 技术美术（TA）
- 希望理解 URP 屏幕空间效果实现细节的开发者

## 阅读建议

1. 先阅读 `Unity/URP SSAO 技术说明.md`，建立 SSAO 的整体认知。
2. 再阅读 `Unity/URP_ScreenSpaceShadows_技术分析.md`，理解主光阴影在屏幕空间路径下的实现与切换策略。

## 说明

- 文档中的版本与路径信息以文档撰写时的源码环境为准。
- 若 URP 或 Unity 版本变化，部分实现细节可能与文档存在差异。
