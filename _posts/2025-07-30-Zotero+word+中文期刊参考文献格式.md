---
layout: post
title: "空模板"
categories: study
author:
- Vincent
---

Zoretero+ Word + 中文期刊：属性拉满！

---

参考资料：

1.  https://gitee.com/eduyob/citation-styles

2. 在 CSL (Citation Style Language) 文件中，要将期刊名称设置为斜体，可以使用 `<text>` 标签的 `font-style` 属性。以下是一个示例：

   ```
   xml<macro name="journal">
       <text variable="container-title" font-style="italic"/>
   </macro>
   ```

   在这个例子中，`container-title` 通常代表期刊名称，通过 `font-style="italic"` 的设置，使其以斜体显示。您可以将这个宏添加到适当的位置，以确保在引用中期刊名称会以斜体格式出现。

3.[ ]的定义：prefix="[" suffix="]"

4.当中文期刊要求参考文献不带最后的句点时，理应通过 .csl 文件修改，困于水平有限，提供一个通配符取巧的方式：

<img src="./../assets/images/image-20250730.png" alt="image-20250730" style="zoom:50%;" />

---

[首页]({{ site.baseurl }})
