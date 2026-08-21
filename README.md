# 冰岛申根签证材料准备与复核 Skill

面向常住中国大陆、以冰岛为主要目的地的短期申根个人旅游申请。本 Skill 不再只给一份泛泛的材料类别列表，而是从 VFS 官方下载开始，按申请人实际操作顺序完成准备和检查。

## 它会怎么工作

1. 打开中国区 VFS 冰岛官方页面，确认当前版本和递交城市。
2. 找到并处理三份核心文件：统一申根申请表、VFS 同意函、个人旅游签证材料审核表。
3. 按官方审核表 1–13 项逐项说明要准备什么、原件还是复印件、检查什么以及缺少后怎么补。
4. 用单独的 reference 按申请表 4 页、字段 1–33 逐项说明信息来源、写法、示例、留空条件和常见误填。
5. 交叉核对护照姓名、入离境日期、第一入境国、主要目的地、机酒、保险、资金和在职信息；同时检查交通预订是否仍有效、解释信所称附件是否真实存在，以及保险地域和活动除外责任。
6. 生成按人拆分的 A4 打印与装包清单。

## 主要内容

- [SKILL.md](prepare-iceland-schengen-visa/SKILL.md)：完整工作流和输出要求
- [官方入口与下载文件](prepare-iceland-schengen-visa/references/official-research.md)：VFS、冰岛政府、申请表、同意函和旅游审核表入口
- [申请表填写指南](prepare-iceland-schengen-visa/references/application-form-guide.md)：4 页、字段 1–33 的逐项写法，含第一入境国、入境次数、酒店、费用承担和签字示例
- [逐项材料指南](prepare-iceland-schengen-visa/references/material-guide.md)：个人旅游审核表 1–13 项逐项展开
- [复核与踩坑](prepare-iceland-schengen-visa/references/review-and-pitfalls.md)：鲜章、解释信附件反查、姓名空格、交通预订状态、保险活动除外责任、PDF 可读性和打印提交

仓库不包含真实护照、订单、银行流水、签名或其他个人申请材料。

## 安装

将 `prepare-iceland-schengen-visa` 目录复制到 Codex 的个人 Skill 目录：

```text
~/.codex/skills/prepare-iceland-schengen-visa
```

## 使用示例

```text
使用 $prepare-iceland-schengen-visa，从 VFS 官方文件开始，为我生成冰岛个人旅游申根签证逐项准备与打印清单。
```

也可以让它检查已有文件夹：

```text
使用 $prepare-iceland-schengen-visa 检查这个材料文件夹。请按 VFS 个人旅游审核表逐项告诉我已有、缺失、要重开和现场再签的内容。
```

## 重要说明

- VFS 页面、PDF 版本、费用和处理时间会变化，实际使用时必须重新打开官方页面确认。
- 交通证明按个人旅游审核表提供有效预订即可，不要求先付款或出票；未付款本身不等于缺件。
- 官方要求、稳妥建议和个人成功案例会分开标注。
- 本 Skill 只做材料准备与一致性复核，不承诺审批结果，也不建议修改或伪造证明材料。
