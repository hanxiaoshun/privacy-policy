# 新增产品隐私政策 · 标准流程

## 命名规范

- 目录名：全小写，`-` 连接，与包名后缀一致
- 示例：`com.bigdog.dagou_teleprompter` → `dagou-teleprompter`

## 操作步骤（5 步）

### 1. 新建子目录
在 `privacy-policy/` 仓库根下，点 **Add file → Create new file**，
文件名填 `新产品slug/index.html`。

### 2. 粘贴内容
复制 `dagou-teleprompter/index.html` 全文作为模板，
替换以下字段：
- `<title>` 中的产品名
- `<h1>` 中的产品名
- 版本号 / 生效日期 / 最近更新
- 权限清单（只保留本产品实际用到的）
- 第三方 SDK 清单
- 联系方式邮箱
- 页脚公司名

### 3. 编辑根导航页
打开根 `index.html`，在 `<ul class="product-list">` 里找到注释块：
```html
<!-- ============ 新产品加在这里 ============
<li>...</li>
=========================================== -->
