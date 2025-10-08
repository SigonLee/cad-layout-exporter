# AutoCAD 布局批量导出工具

一个用于批量导出 AutoCAD 布局为独立 DWG 文件的 LISP 脚本。

## 功能特点

- ✅ 批量导出所有布局（除模型空间）
- ✅ 自动命名：原文件名_布局名.dwg
- ✅ 进度显示和完成统计
- ✅ 错误处理和命令恢复
- ✅ 执行时间统计
- ✅ 目录选择（高级版）
## 安装和使用

### 安装方法

1. 下载 `LayoutExportTool.lsp` 文件
2. 在 AutoCAD 中加载 LISP 文件：
   - 输入 `APPLOAD` 命令
   - 浏览并选择下载的 LISP 文件
   - 点击"加载"

### 使用方法

加载后，在 AutoCAD 命令行输入以下任一命令：
- 基础版：
- `BATCHEXPORT` - 完整命令
- `BE` - 简写命令
- 高级版：
- `EXPORTADV` - 完整命令
- `EA` - 简写命令
## 兼容性

- AutoCAD 2020 及更高版本
- 适用于 Windows 平台

## 代码示例

```lisp
;; 加载后使用 BE 命令
(defun c:BE () (c:BATCHEXPORT))
```

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 贡献

欢迎提交 Issue 和 Pull Request！
