# zhang-light主题

### 灵感来源

- 本主题以Tsundoku Light主题为模板进行修改
- 字体配色采用了Obsidian中Orange主题中的7中彩虹配色,删除了带有透明度的部分
- 主题页面背景灵感来自于BluePrint-From-Tsundoku-main的格子主题

### 感谢列表

- 感谢大家对于主题的反馈和建议
- 感谢萌新，mindstudy，九炎，Roy在修复“无序列表转换成表格”这一自定义属性中提供的帮助
  - 萌新（dark+主题作者）
  - mindstudy(Concise Light极简主题作者)
  - Roy（notion theme主题作者)
  - 九炎（群内诸多挂件的作者）

### 📌注意事项

- **解压主题文件夹后，建议从下面网址下载仓耳今楷03-W04字体**
  - https://www.ztxz.org.cn/canger/549.html
  - 安装后可自动生效，不用做什么设置；如果没有立即生效，可以重启一下思源笔记
  - 字体效果示例
    - ![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzu8xqgdlvj31hc0jitnk.jpg)

- 自定义属性强烈推荐：自定义属性无序列表变为表格

### 🎉更新进度

#### 0.2版本

- 修改 PDF 标注样式，在高亮底部加上横线
- 调整 PDF 双链样式，鼠标悬浮时修改为浅绿色
- 修改分割线样式，现在分割线为动态渐变样式
- 参考 Rem Craft 主题，修改表格设置，表格默认100%宽度
- “/”调出的元素分为4栏，方便选择
- 给超级块加上虚线边框，鼠标悬浮时边框可以滚动
- 通过自定义属性，增加弹幕功能，属性值为“dm“
- 参考 Notion-theme 主题，修改了头图相关设置，效果类似于 Notion
- 优化了一些细节

#### 0.3版本

- 增加了列表转化成表格的自定义属性，f=bg (表格)
- 将浅色便利贴和深色便利贴从样式改成了自定义属性，详见“自定义属性”
- 修改了分栏样式，“/” 引出的分栏分为4栏，颜值更上一层楼
- 修改了待办事项的样式，更加好看
- 点击目录大纲时增加了顺滑的切换效果
- 给特定标签增加了特定的格式，如“选择”，“填空”，“判断”等
- 上标和下标的颜色修改为蓝色
- 去掉文档树和目录大纲后边的引用数字
- 修改文档树后边的设置和新建文档按钮
- 优化设置面板关闭按钮（鼠标悬浮时有旋转和变色效果）
- 优化了一些细节

#### 0.4版本

- 统一主题中的圆角，颜色，背景等，方便大家自定义修改（如可以很方便地将主题色修改为绿色，蓝色等）
- 增加了一些对文档的自定义属性，如修改字体，单个文档去掉自动编号、去掉标题下的圆角矩形等
- 修改了超链接和块引用的样式
- 修改了 kbd 键盘的样式
- 修改了标签样式
- 将 h1 级别标题设置为居左
- 增加下划线距离文字的高度
- 去掉文档树和大纲的引用数字，保留反向链接面板和提及面板后面的引用数字。
- 去掉 iframe 元素的边框

##### 0.4.1

- 增加自定义属性图片去掉边框和阴影`f:pic`（有群友有用到段落文字中插入图片公式的情形）

- 修改下划线的样式（下划线距离文字底部有点远）

- 取消鼠标滑选区域显示（群友反馈，感觉不必要）

- 更改行内代码的颜色（主题色）

- 更改引用块和超链接在标题中的样式（自适应标题颜色，去掉下划线，这样不突兀）

  - ![image.png](https://tva1.sinaimg.cn/mw690/0082QUidly1h03nw5j89uj30ji07hwhv.jpg)

- 通过文档的**自定义属性**增加一些护眼色（来自群友“随船医”的推荐）

  - | 名称        | 颜色    | 代码   |
    | ----------- | ------- | ------ |
    | 杏仁黄      | #faf8df | yellow |
    | 绿豆沙      | #c8edcc | green  |
    | wps护眼模式 | #cce8cf | green1 |
    | 青草绿      | #e3eccd | green2 |
    | 极光灰      | #ebeaf0 | gray   |
    | 瑞雪白      | #f1ede1 | white  |

- 通过自定义属性将表格设置为自适应宽度，超过100%后可以左右拖拽查看，文字不会自动分行

  - ![image.png](https://tva1.sinaimg.cn/large/0082QUidly1h03qbezd5fj31080dk7bu.jpg)

### 🎈修复bug

#### 0.2版本

- 去掉使用自定义表情时带有的阴影和边框

#### 0.3版本

- 修复“[[”引出引用块时文档名称和文档路径重叠在一起的bug
- 修复给标题设置备注或命名时出现的自动序号错乱的bug
- 修复头图上传本地图片时“上传”俩字点击无效的bug
- 修复了代码行超过1000时编号会出现错乱的bug
- 修改标签页文字过长时下方会溢出文字的bug

#### 0.4版本

- 修复笔记本不能点击emoji更换图标的bug

##### 0.4.1

- 列表转化为表格的自定义属性中，表格右边界与文字距离太近

### 下步计划

#### 0.3版本

- 考虑是否去掉超级块的虚线边框（超级块嵌套很多层后会影响外观）
  - 不去掉，虚线框可以突出超级块之间的界限，特别是在没有背景颜色的时候

- 考虑是否保持默认开启标题自动编号
  - 默认开启，自动编号是本主题的特色之一，也得到了一些朋友的喜欢。但使用说明中会增加对 CSS 代码修改的说明，大家可以自行决定是否去掉自动编号。

- 给“[[”引出的引用块列表增加鼠标悬浮显示全部内容的功能
  - Loading


#### 0.4版本

- 开发 zhang-dark 版本……

### 主题截图

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsgda4t7aj31hc0smkao.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsge4flubj31hc0sm1be.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1h03bwdngb1j31hc0sm1kx.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsi13jfipj31hc0sm13h.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsi5wv36wj31hc0smgx2.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsi34942uj31hc0smdq5.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshllc8bsj31hc0sm18t.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshr7al8jj31hc0smdvk.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshswsij6j31hc0smqnu.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshutksjfj31hc0smkgl.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshvow6okj31hc0sm1j3.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzshzlzbpsj31hc0sm1kx.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsi8fsqejj31hc0smaui.jpg)

![image.png](https://tva1.sinaimg.cn/large/0082QUidly1gzsibhzoegj31hc0smkdc.jpg)

### 自定义属性

> 自定义属性针对整个段落生效，不针对段落中的部分文字生效（只能是一个段落，不能按住Enter分行，要按住Ctrl+Enter）


> 自定义属性shift+鼠标左键，弹出窗口中，选择“添加”，属性名填入“f”，属性值填入下列代码，即可实现相应效果


|分类|名称|代码|
|---|---|---|
|字体|楷体|k|
| |宋体|s|
| |黑体|h|
| |微软雅黑|w|
| |华文行楷|xk|
| |隶书|l|
|下划线|虚线|x|
| |曲线/波浪线|q|
|文字竖排|竖排|sp|
|文本缩进|缩进|sj|
|文字大小|1.1倍|1.1|
| |1.2倍|1.2|
| |1.3倍|1.3|
| |1.4倍|1.4|
| |1.5倍|1.5|
| |1.75倍|1.75|
| |2倍|2|
|英文字母大小写|首字母大写|dx|
| |所有字母都大写|ddx|
|奥运主题|冰墩墩|ay|
| |雪容融|ay2|
| 滚动弹幕 |弹幕|dm|
| 列表转化为表格 |表格|bg|

> 自定义属性shift+鼠标左键，弹出窗口中，选择“添加”，属性名填入“q”或者“s”，属性值填入下列代码，即可实现相应效果

| 便利贴 | 代码 | 值   |
| ------ | ---- | ---- |
| 浅色红 | q    | blt1 |
| 浅色黄 | q    | blt2 |
| 浅色蓝 | q    | blt3 |
| 浅色绿 | q    | blt4 |
| 深色红 | s    | blt1 |
| 深色黄 | s    | blt2 |
| 深色蓝 | s    | blt3 |
| 深色绿 | s    | blt4 |

