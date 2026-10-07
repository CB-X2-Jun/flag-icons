# Flag Icons (纯 CSS 版)

一个 4x3 格式的 SVG 旗帜合集 —— 附带 CSS 以便于集成。

**注意：本项目仅提供 4:3 格式的旗帜，不支持 1:1 方形旗帜，且无需 npm 安装。**

我们扩充了旗帜，包含了争议实体（比如阿布哈兹），以及历史政权（比如苏联）。

## 如何使用

1. 在 HTML 的 `<head>` 中引入在线 CSS 文件：
   ```html
   <link rel="stylesheet" href="https://flags.etoj.run.place/css/flag-icons.min.css" />
   ```
2. 在页面中使用旗帜：
   ```html
   <span class="fi fi-cn"></span> 中国
   <span class="fi fi-us"></span> 美国
   <span class="fi fi-su"></span> 苏联
   <span class="fi fi-nato"></span> 北约
   <span class="fi fi-ge-os"></span> 南奥塞梯
   ```

## 分类
- ISO：标准ISO国家地区代码（包括港、澳、台、格陵兰、奥兰群岛等地区）
- Region：地区与属地（如英格兰、苏格兰、加泰罗尼亚）
- Disputed：争议地区（如阿布哈兹、南奥塞梯、德左、科索沃）
- Organization：国际组织（如联合国、欧盟、东盟、北约）
- Historic：历史或已消亡政权（如苏联、南斯拉夫、赫特河公国）
- Other：其他

## 许可

MIT LICENSE
