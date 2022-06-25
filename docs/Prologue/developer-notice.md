# 开发者须知
## commit 规范
为保证 commit 的可追溯性和统一性，要求所有开发者 commit message 遵循同一套规约

前缀请遵循如下规则(套用软件开发过程)
- 修订: fix，修复
- 内容新增: feat，新增
- 内容更新；update，内容新增
- 章节结构调整: refactor
- 流水线变更: ci

例

纠正错别字和语句不通顺时：`fix: typo correction in chapter n`,“修复：第n章节的拼写修复”

新增食堂攻略时：`feat: third canteen food guide`,`update: third canteen food guide`,“新增：第三食堂美食指南”

## 分支与合并请求
提交代码时，<span style="color: red">禁止</span>在主分支上直接 Push ，请单独拉取分支提交 merge request 合并

分支名称也请遵循如下规范

- 修订: fix
- 内容新增: feature
- 章节结构调整: refactor
- 流水线变更: ci

例

纠正错别字和语句不通顺时：`fix-typo-correction`，“修复-错别字“

新增食堂攻略时：`feature-third-canteen-guide`，“更新-第三食堂内容”

相比于 commit ，更加简短