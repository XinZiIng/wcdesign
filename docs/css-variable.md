# CSS 变量

定义默认全局常用CSS变量，修改建议局部变量重置，以免全局污染。

```scss
:root {
// 字体
--font-family: -apple-system, PingFang, 'Hiragino Sans GB', '微软雅黑', 'Microsoft YaHei', sans-serif;

--color-theme: #000;            // 主题色
--color-info: #46c2ff;          // 信息状态色
--color-success: #09bb07;       // 成功状态色
--color-warning: #f1c051;       // 危险状态色
--color-danger: #e64340;        // 警告状态色

--color-disabled: #ccc;         // 禁用状态色
--color-disabled-bg: #f5f5f5;   // 禁用状态背景色

--color-link: #1890ff;          // 链接色
--color-border: #d9d9d9;        // 边框色
--color-border-light: #f7f7f7;  // 浅边框色

--color-black: #333;            // 黑色（页面默认颜色）
--color-white: #fff;            // 白色
--color-gray: #666;             // 灰色（可用于辅助文本色）
--color-gray-light: #999;       // 浅灰色（可用于次要文本色）

--color-table-header: #fbfbfb;  // 表格头部背景色
--color-table-striped: #fbfbfb; // 表格条纹背景色
--color-table-hover: #f5f5f5;   // 表格Hover背景色

--color-mask-black: rgba(0, 0, 0, 0.7);         // 黑色遮罩层
--color-mask-white: rgba(255, 255, 255, 0.7);   // 白色遮罩层
--modal-z-index: 999;           // 遮罩层层级

--border-1px-width: 1px;        // 边框
--border-radius: 4px;           // 边框圆角
--border-radius-xs: 2px;        // 小尺寸边框圆角

--button-xs-padding: 7px;       // 按钮小尺寸内边距

--margin-padding-lg: 15px;      // 内外边距大尺寸
--margin-padding-md: 10px;      // 内外边距中等尺寸
--margin-padding-sm: 5px;       // 内外边距小尺寸

--font-size-xl: 26px;           // 大尺寸字体，对应h1标签字体大小样式
--font-size-lg: 20px;           // 大尺寸字体，对应h2标签字体大小样式
--font-size-md: 18px;           // 中尺寸字体，对应h3标签字体大小样式
--font-size-sm: 16px;           // 小尺寸字体，对应h4标签字体大小样式
--font-size: 14px;              // 默认尺寸字体，对应h5标签字体大小样式
--font-size-xs: 12px;           // 最小尺寸字体，对应h6标签字体大小样式

--height-lg: 50px;              // 大尺寸高度
--height-md: 40px;              // 中尺寸高度
--height-sm: 32px;              // 小尺寸高度
}
```