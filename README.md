# Flag Icons (纯 CSS 版)

一个 4x3 格式的 SVG 旗帜合集 —— 附带 CSS 以便于集成。

**注意：本项目仅提供 4:3 格式的旗帜，不支持 1:1 方形旗帜，且无需 npm 安装。**

## 如何使用

1. 将 `flags/4x3/` 文件夹和 `css/flag-icons.min.css` 复制到你的项目中。
2. 在 HTML 的 `<head>` 中引入 CSS：
   ```html
   <link rel="stylesheet" href="css/flag-icons.min.css" />
   ```
3. 在页面中使用旗帜：
   ```
   <span class="fi fi-cn"></span> 中国
   <span class="fi fi-us"></span> 美国
   <span class="fi fi-su"></span> 苏联
   ```

## 分类
- ISO：标准国家代码（包括港、澳、台等地区）
- Region：地区与属地（如英格兰、苏格兰、加泰罗尼亚）
- Disputed：争议地区（如阿布哈兹、南奥塞梯、德左、科索沃）
- Organization：国际组织（如联合国、欧盟、东盟）
- Historic：历史政权（如苏联、南斯拉夫）
- Other：其他

## 许可

MIT LICENSE
